# Invoice AB Project

Aplikasi invoice satu halaman yang bisa diedit dan dipublikasikan sebagai situs statis melalui GitHub Pages.

## Buka di GitHub Pages

1. Push file proyek ini ke repository GitHub.
2. Buka **Settings > Pages** pada repository.
3. Pada **Build and deployment**, pilih **Deploy from a branch**.
4. Pilih branch utama dan folder **/(root)**, lalu klik **Save**.
5. Buka URL yang ditampilkan di halaman Pages. `index.html` akan mengarahkan ke invoice.

> GitHub Pages hanya menyajikan file statis; server Node.js tidak diperlukan untuk publikasi. Perubahan invoice akan terlihat setelah di-push ke GitHub.

## Jalankan lokal

```bash
npm start
```

Buka http://127.0.0.1:3000/.

## Fitur

- Teks invoice dapat diedit langsung.
- Tambah item dan total dihitung otomatis.
- Unduh invoice sebagai PNG atau PDF.

## File utama

- `index.html` — halaman masuk GitHub Pages.
- `editable_invoice_generator.html` — tampilan dan logika invoice.
- `server.js` — server lokal ringan.
