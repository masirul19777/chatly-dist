CHATLY v1.3 - PAKET SIAP HOSTING
================================

Cara upload:
1. Ekstrak isi ZIP ini ke folder publik hosting (public_html / www / root domain).
   Pastikan index.html berada langsung di root, bukan di dalam subfolder.
2. Aktifkan HTTPS (wajib untuk mikrofon, kamera, notifikasi, panggilan).
3. Buka domain, lalu hard reload (Ctrl+Shift+R / tutup semua tab).

File konfigurasi:
- _redirects  -> Netlify / Cloudflare Pages (SPA routing otomatis)
- .htaccess   -> Apache/cPanel (SPA routing otomatis)

Cek versi:
Pengaturan > paling bawah harus tertulis:
"Chatly v1.3 - avatar fix - TURN aktif"

Perbaikan v1.3:
- Foto profil tidak lagi keluar dari bingkai (settings, panggilan, daftar chat)
- Panggilan: dering berhenti saat dijawab di perangkat lain, watchdog 25 detik,
  tidak ada dering ganda, TURN Metered aktif
