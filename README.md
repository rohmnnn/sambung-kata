# Sambung Kata

Aplikasi pencarian kata berdasarkan awalan dan akhiran (frontend statis) dengan data yang digenerate dari beberapa file kata.

## Sumber Data

Sumber utama kata Bahasa Indonesia diambil dari:

- https://github.com/damzaky/kumpulan-kata-bahasa-indonesia-KBBI

## Fitur

- Cari kata berdasarkan awalan
- Cari kata berdasarkan akhiran
- Bisa kombinasi awalan + akhiran
- Input bisa lebih dari 1 huruf
- Data dibersihkan (hanya huruf, tanpa simbol)
- Data unik (tanpa duplikat)

## Struktur Proyek

- `hm.js` : generator data (dijalankan lokal)
- `index.html` : aplikasi web statis
- `data.js` : output data kata untuk frontend

## Cara Menjalankan Lokal

1. Pastikan Node.js sudah terpasang.
2. Generate data:

```bash
node hm.js
```

3. Buka `index.html` langsung di browser.

## Catatan

- Setiap ada perubahan sumber kata (`.txt`), jalankan ulang `node hm.js` lalu commit hasilnya.
