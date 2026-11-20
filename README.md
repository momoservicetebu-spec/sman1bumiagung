# Portal Resmi & 23 Aplikasi Terpadu — SMAN 1 Bumi Agung

Sistem Informasi Website Sekolah dan Launcher **23 Aplikasi Digital Terpadu** untuk **SMAN 1 Bumi Agung**, Kabupaten Way Kanan, Provinsi Lampung, dengan arsitektur *Frontend* statis (*Stale-While-Revalidate*) dan *Backend* Google Sheets + Google Apps Script.

## Endpoint Backend Terpasang

URL Web App Google Apps Script yang terkonfigurasi pada `index.html`, `login.html`, dan `admin.html`:
```text
https://script.google.com/macros/s/AKfycbw397Xhh415MSyr9Dkx1iuQWhNODzXUUeJdmZmbne9U6k0DJtBgs_kIUy4lwk4oj1A2/exec/exec
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
