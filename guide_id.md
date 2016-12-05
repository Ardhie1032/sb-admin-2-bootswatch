# BBS Admin (Bootstrap, SB Admin 2 & Bootswatch)

## HTML Class
Tambahkan attribut *class* pada tag &lt;body&gt; dengan nilai ``bbs-admin active``.

```html
<body class="bbs-admin active">
```

Alternatif warna background &lt;body&gt; dengan menambahkan class ``gray-base``.

```html
<body class="gray-base">
<body class="gray-base bbs-admin active">
```

## JavaScript

Ganti external file javascript

```html
<script src="../dist/js/sb-admin-2.js"></script>
```

menjadi

```html
<script src="../dist/js/bbs-admin.min.js"></script>
```

Opsi untuk tampilan scrollbar pada menu, instal plugin [jQuery SlimScroll](https://github.com/rochal/jQuery-slimScroll).
Tambahkan sebelum custom script *bbs-admin.min.js*.

```html
<script src="../vendor/slimScroll/jquery.slimscroll.min.js"></script>
<script src="../dist/js/bbs-admin.min.js"></script>
```

Contoh laman tersedia di ***pages/bbs-admin-blank.html***.

## NB: Jangan Pelit dengan Bintang-nya!!!

## Sekian & Terima Kasih!
