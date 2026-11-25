# Do You Mind — KYLA

Halaman lirik **Do You Mind** oleh **KYLA** (2009) dalam satu file HTML: editorial, responsif, aksesibel, dan dilengkapi pemutar audio remix DJ Paleface versi slowed.

**Demo:** https://ikyletwar.github.io/do-you-mind-lyrics/

## Isi repository

- `index.html` — seluruh halaman: 73 baris lirik, metadata, Konteks, Sumber, dan pemutar audio. Tanpa build step dan tanpa dependency.
- `assets/do-you-mind-remix.mp3` — audio yang dipakai pemutar (192 kbps, 4:21).
- `.nojekyll` — menyajikan file statis apa adanya di GitHub Pages.

## Fitur

- 73 baris lirik bernomor `01`–`73`.
- Pemutar sticky: play/pause, seek bar, waktu berjalan, volume, kecepatan `1× / 0.8× / 1.2×`, sembunyikan dan pulihkan pemutar.
- Tombol salin tautan, toggle tema terang/gelap dengan preferensi sistem, serta skip link.
- State loading, disabled, success, dan error pada kontrol.
- Animasi reveal berbasis `transform`/`opacity`, dinonaktifkan otomatis untuk `prefers-reduced-motion`.
- Layout diuji pada 390, 768, dan 1440 px tanpa overflow horizontal.

## Menjalankan lokal

Buka `index.html` langsung di browser, atau layani lewat HTTP:

```bash
python3 -m http.server 8000
# lalu buka http://localhost:8000
```

## Catatan sumber

Teks lirik berasal dari salinan yang diberikan pengguna. Metadata dan konteks lagu diverifikasi dari Wikipedia, Official Charts, dan PRS for Music. Tautannya tersedia di bagian **Sumber** pada halaman.
