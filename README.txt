JIMPITAN RT - PROTOTIPE PWA

File prototipe PWA: index.html, manifest.webmanifest, sw.js, icon.svg
Fitur prototipe yang tersedia: login admin, dashboard, data warga, input setoran, rekap bulanan dan cetak, ganti password.

CATATAN PENTING:
- Prototipe saat ini menyimpan data lokal di browser (localStorage). Belum ada database online, akun petugas terpisah, sinkronisasi antar-HP, atau keamanan server.
- Login demo: admin / admin123.
- Ganti password hanya mengubah password lokal di browser tersebut.
- Agar fitur install PWA/service worker aktif, deploy folder ini ke host HTTPS seperti GitHub Pages atau Netlify. Untuk menjalankan instalasi, buka URL HTTPS di Chrome Android dan pilih menu Install/Add to Home Screen.
- Jika ingin data bersama antar pengurus, tahap berikutnya perlu backend/database (misalnya Supabase/Firebase), autentikasi, dan rules keamanan.
