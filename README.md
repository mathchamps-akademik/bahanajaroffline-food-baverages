# Math Champs F&B Teaching Kit Offline - GitHub Pages

Paket ini adalah file raw siap upload untuk GitHub Pages. Materi dipakai untuk Holiday Program kelas offline/tatap muka, 3 pertemuan, masing-masing 100 menit. GitHub Pages hanya dipakai sebagai halaman akses online untuk guru.

## Isi Paket

- `index.html` - hub utama semua pertemuan offline.
- `pertemuan-1-teacher-deck.html`, `pertemuan-2-teacher-deck.html`, `pertemuan-3-teacher-deck.html` - teacher deck HTML.
- `pertemuan-1-teacher-deck.pdf`, `pertemuan-2-teacher-deck.pdf`, `pertemuan-3-teacher-deck.pdf` - PDF cadangan deck.
- `pre-test-1.pdf`, `post-test-1.pdf`, `kunci-jawaban-1.pdf`, dan file sejenis untuk Pertemuan 2-3 - PDF tes dan kunci jawaban.
- `spin-wheel-day1.html` - spin wheel cadangan Pertemuan 1. Aktivitas utama tetap memakai kartu blind box yang diprint dan digunting dari learning kit.
- Folder `decks/`, `pdf/`, `tests/`, dan `tools/` boleh tetap disimpan sebagai arsip, tetapi hub utama memakai file di root repository agar cocok dengan GitHub Pages yang sedang dipakai.
- `manifest.json` - daftar file penting untuk pengecekan cepat.

## Cara Upload ke GitHub Pages

1. Buat repository baru di GitHub.
2. Upload semua isi folder ini ke root repository, termasuk `index.html`. Untuk memperbaiki repo yang sudah ada, minimal replace `index.html` dan pastikan file deck/PDF/test berada di root repository.
3. Buka `Settings > Pages`.
4. Pada `Build and deployment`, pilih `Deploy from a branch`.
5. Pilih branch `main` dan folder `/root`, lalu klik `Save`.
6. Setelah deploy selesai, buka `https://USERNAME.github.io/NAMA-REPO/`.

## Catatan

Semua tombol di hub memakai link relatif, jadi tidak bergantung pada hosting sementara. Selama GitHub Pages repository aktif, hub dan file pendukungnya tetap bisa diakses.

Jangan upload paket ini ke host-html untuk versi final. Host-html menampilkan halaman di dalam iframe sandbox, sehingga Chrome bisa memblokir tombol yang membuka PDF, pre-test, post-test, atau kunci jawaban. GitHub Pages menyajikan file sebagai halaman normal, jadi link PDF/test akan terbuka seperti file biasa.

Saat upload ke GitHub, upload isi folder ini ke root repository. Jangan hanya upload file zip-nya, karena GitHub Pages perlu membaca `index.html` dan file-file HTML/PDF pendukung secara langsung.

Sebelum kelas offline dimulai, guru tetap perlu menyiapkan print worksheet, pre-test, post-test, kartu blind box, dan perlengkapan kelas sesuai checklist di hub.
