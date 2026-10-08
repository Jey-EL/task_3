# Tugas Individu 3 - Pemrograman Aplikasi Web

Halaman web sederhana dengan dua halaman: pendaftaran dan detail pendaftar.

## Identitas
- Nama: Jundi Lamtara
- NIM: 124140190
- GitHub: Jey-EL

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

## Link Website
- GitHub Repository: https://github.com/Jey-EL/task_3
- GitHub Pages: https://jey-el.github.io/task_3/

## Screenshot

**Halaman Pendaftaran (`index.html`)**

<img width="1920" height="1080" alt="Screenshot 2026-10-09 000439" src="https://github.com/user-attachments/assets/edcd8b1a-8385-471f-9d8b-ba28284fefee" />

**Halaman Detail Pendaftar (`detail.html`)**

<img width="1920" height="1080" alt="Screenshot 2026-10-09 000130" src="https://github.com/user-attachments/assets/ea3a12d4-09dd-4baa-a87e-5badb2bb5149" />

## Ketentuan yang Dipenuhi

- Dua halaman: pendaftaran dan detail informasi pendaftar.
- Form pendaftaran memakai `method="GET"` dengan `action="detail.html"`.
- Query string hanya didesain, data tidak ditangkap. Halaman detail berisi data dummy.
- CSS memakai lebih dari 3 selektor: elemen (`body`, `table`), class (`.box`), id (`#judul`), turunan (`form input`), dan grup (`th, td`).
- Layout, box, tabel, dan form didesain dengan CSS.
