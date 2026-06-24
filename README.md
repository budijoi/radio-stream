# Radio Stream

Aplikasi web radio streaming Indonesia. Dengarkan stasiun radio dari berbagai kota di Indonesia langsung dari browser.

## Fitur

- Streaming radio dari 15+ kota di Indonesia (Jakarta, Bandung, Surabaya, Yogyakarta, dll)
- Daftar stasiun dikelompokkan per kota, bisa expand/collapse
- Indikator status online/offline tiap stasiun
- Pencarian stasiun berdasarkan nama atau kota
- Tambah stasiun radio kustom (URL, nama, kota)
- Player tetap di bagian bawah halaman
- Status penyimpanan di localStorage

## Cara Pakai

1. Buka `index.html` di browser
2. Klik header kota untuk melihat daftar stasiun
3. Klik stasiun untuk mulai memutar
4. Gunakan kolom cari untuk filter stasiun
5. Klik "+ Tambah" untuk menambahkan stasiun radio sendiri

## Tech Stack

- HTML, CSS, JavaScript murni (tanpa framework)
- Audio HTML5 untuk streaming
- Fetch API + AbortController untuk pengecekan status stream
- localStorage untuk menyimpan stasiun kustom
