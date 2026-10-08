# Tugas Individu 3 - Pemrograman Aplikasi Web

Halaman web sederhana dengan dua halaman: pendaftaran dan detail pendaftar.

**Nama:** Jundi Lamtara
**NIM:** 124140190
**Kelas:** Pemrograman Aplikasi Web (PAW) RB

## Isi Folder

| File | Keterangan |
|------|------------|
| `index.html` | Halaman pendaftaran (form dengan method GET) |
| `detail.html` | Halaman detail pendaftar (data dummy) |
| `style.css` | CSS untuk kedua halaman |

## Cara Menjalankan

1. Download atau clone repository ini.
2. Buka file `index.html` di browser.
3. Isi form lalu klik tombol **Daftar**.
4. Browser akan membuka `detail.html` dengan data form terkirim lewat URL (query string), contoh:

```
detail.html?nama=Budi+Santoso&nim=123456789&email=budi%40mail.com&jurusan=Teknik+Informatika
```

## Screenshot

**Halaman Pendaftaran (`index.html`)**

![Halaman Pendaftaran](<Screenshot 2026-10-09 000439.png>)

**Halaman Detail Pendaftar (`detail.html`)**

![Halaman Detail](<Screenshot 2026-10-09 000130.png>)

## Ketentuan yang Dipenuhi

- Dua halaman: pendaftaran dan detail informasi pendaftar.
- Form pendaftaran memakai `method="GET"` dengan `action="detail.html"`.
- Query string hanya didesain, data tidak ditangkap. Halaman detail berisi data dummy.
- CSS memakai lebih dari 3 selektor: elemen (`body`, `table`), class (`.box`), id (`#judul`), turunan (`form input`), dan grup (`th, td`).
- Layout, box, tabel, dan form didesain dengan CSS.
