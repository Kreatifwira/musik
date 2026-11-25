# DuoMotion AI

Studio awal untuk menyiapkan video musik duet dari MP3 dan dua gambar karakter.

## Fitur tahap 1
- Dashboard responsif.
- Pilih MP3 dan pratinjau audio lokal.
- Pilih foto penyanyi pria dan wanita dengan pratinjau.
- Pilih gaya dance dan format video.
- Validasi bahan di browser.

## Belum tersedia
- Login, database, dan penyimpanan Supabase.
- Integrasi AI lip-sync dan dance.
- Antrean pemrosesan dan rendering MP4.

Tidak ada API berbayar yang dipanggil pada tahap ini.

## Deploy Cloudflare Pages
1. Connect repository ini di Cloudflare Pages.
2. Framework preset: None.
3. Build command: kosong.
4. Build output directory: / (root).
5. Pilih branch utama (biasanya main).

## Rencana tahap berikutnya
Integrasi Supabase Auth, tabel proyek, dan Storage privat. Proses AI/video akan dijalankan pada worker atau compute terpisah; Pages hanya untuk frontend.
