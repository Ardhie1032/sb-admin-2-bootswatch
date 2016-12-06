# BBS Admin (Bootstrap, Bootswatch & SB Admin 2)

## Standar

### #1
Tambahkan atribut *class* pada tag &lt;body&gt; dengan nilai ``bbs-admin active``.

```html
<body class="bbs-admin active">
```

### #2

Hapus atribut ``data-toggle`` dan ``data-target`` pada elemen ``button.navbar-toggle``

```
<div class="navbar-header">
  <button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
    <span class="sr-only">Toggle navigation</span>
    <span class="icon-bar"></span>
    <span class="icon-bar"></span>
    <span class="icon-bar"></span>
  </button>
  <a class="navbar-brand" href="index.html">SB Admin v2.0</a>
</div>
```

menjadi

```
<div class="navbar-header">
  <button type="button" class="navbar-toggle">
    <span class="sr-only">Toggle navigation</span>
    <span class="icon-bar"></span>
    <span class="icon-bar"></span>
    <span class="icon-bar"></span>
  </button>
  <a class="navbar-brand" href="index.html">BBS Admin</a>
</div>
```

### #3

Ganti berkas eksternal javascript

```html
<script src="../dist/js/sb-admin-2.js"></script>
```

menjadi

```html
<script src="../dist/js/bbs-admin.min.js"></script>
```

### #4

Opsi untuk tampilan scrollbar pada menu, instal plugin [jQuery SlimScroll](https://github.com/rochal/jQuery-slimScroll).
Tambahkan sebelum custom script *bbs-admin.min.js*.

```html
<script src="../vendor/slimScroll/jquery.slimscroll.min.js"></script>
<script src="../dist/js/bbs-admin.min.js"></script>
```

Contoh laman tersedia di ***[pages/bbs-admin-blank.html](pages/bbs-admin-blank.html)***.

## Opsional

### #1

Alternatif warna background &lt;body&gt; dengan menambahkan class ``gray-base``.

```html
<body class="gray-base">
<body class="gray-base bbs-admin active">
```

### #2

Kustom warna background navbar (bagian atas) dan sidebar (samping)

#### Default (``.navbar-default``)

```html
  <nav class="navbar navbar-default navbar-static-top" role="navigation" style="margin-bottom: 0">
    ...
    <div class="navbar-default sidebar" role="navigation">
      ...
    </div>
  </nav>
```

#### Inverted (``.navbar-inverse``)

```html
  <nav class="navbar navbar-inverse navbar-static-top" role="navigation" style="margin-bottom: 0">
    ...
    <div class="navbar-inverse sidebar" role="navigation">
      ...
    </div>
  </nav>
```

### #3

Alternatif posisi ``.sidebar`` (di luar elemen ``nav.navbar-static-top``)

```html
  <nav class="navbar navbar-inverse navbar-static-top" role="navigation" style="margin-bottom: 0">
    ...
  </nav>
  <div class="navbar-inverse sidebar" role="navigation">
    ...
  </div>
```

## Sekian & Terima Kasih!
