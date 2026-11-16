# Janu TTS

Dashboard sederhana untuk mengubah teks menjadi suara memakai suara **Janu** (ElevenLabs, Voice ID `TIXYCOMzK2Vw9OZovSLs`). Satu file statis, tanpa server.

## Cara memakai di GitHub Pages

1. Buat repository baru, lalu unggah `index.html` dan `README.md`.
2. Buka **Settings → Pages**, pilih branch `main` dan folder `/ (root)`, lalu simpan.
3. Buka alamat Pages yang diberikan GitHub.
4. Masukkan API key ElevenLabs di kolom Pengaturan, tulis teks, lalu tekan **Buat suara**.

## Keamanan

- Jangan menulis API key di dalam kode atau meng-commit-nya ke GitHub.
- Key hanya diketik di browser. Jika kotak "Ingat di browser ini" dicentang, key disimpan di localStorage browser tersebut saja.
- Karena halaman ini publik, orang lain harus memakai key mereka sendiri.

## Catatan

- Suara dari voice library biasanya perlu paket berbayar untuk dipakai lewat API, dan suara Janu perlu sudah ditambahkan ke akunmu.
- Tag ekspresi seperti `[whispers]` dan `[giggles]` hanya bekerja di model v3 atau v4.
