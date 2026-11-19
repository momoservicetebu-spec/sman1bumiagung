# Portal Resmi & 23 Aplikasi Terpadu — SMAN 1 Bumi Agung

Sistem Informasi Website Sekolah dan Launcher **23 Aplikasi Digital Terpadu** untuk **SMAN 1 Bumi Agung**, Kabupaten Way Kanan, Provinsi Lampung, dengan arsitektur *Frontend* statis (*Stale-While-Revalidate*) dan *Backend* Google Sheets + Google Apps Script.

## Endpoint Backend Terpasang

URL Web App Google Apps Script yang terkonfigurasi pada `index.html`, `login.html`, dan `admin.html`:
```text
https://script.google.com/macros/s/AKfycbwbGrBHzKP7oFu2-fHzQ478kxVpuf1FdXlpc6Tiq9YLJQl3nrnSpAlpYJu4e_m3Wq_4/exec
```

## Struktur Folder Proyek

```text
sman1bumiagung-main/
├── index.html      # Halaman utama publik, portal 23 aplikasi, berita & halaman dinamis
├── login.html      # Halaman autentikasi Admin Sekolah & Super Admin
├── admin.html      # Dashboard CMS pengelolaan profil, menu, aplikasi, berita & kontak
├── 404.html        # Halaman error 404 dengan pengalihan otomatis ke beranda
└── README.md       # Dokumentasi instalasi dan struktur database
```
