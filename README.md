# GitHub File Sync

Web app buat connect akun GitHub, terus kelola & upload file langsung ke repo dari browser — tanpa perlu buka terminal atau Git command sama sekali. Cocok buat push perubahan cepat, upload dari HP, sampe deploy ke Vercel dalam beberapa klik.

🔗 **Live demo:** https://uploader-git.vercel.app/
📱 **Install aplikasi (APK):** _https://github.com/zaxeonking/github-uploader-showcase/releases/download/v1.0.0/Uploader-git.apk_

## Apa yang bisa dilakuin

- **Login GitHub lewat OAuth** — klik "Connect dengan GitHub", approve, langsung bisa akses repo kamu (public maupun private).
- **Upload & kelola file** — upload file satuan atau zip, lihat isi repo, edit file langsung di browser (dengan syntax highlighting), rename, hapus, sampe deteksi konflik kalau file udah keburu diubah dari tempat lain.
- **Deploy ke Vercel** — connect akun Vercel sekali, abis itu tiap repo bisa langsung di-deploy/redeploy dan diatur environment variable-nya dari sini juga. Ada juga opsi deploy hook manual (Vercel/Netlify) buat yang nggak mau connect OAuth.
- **PWA & bisa di-share dari app lain** — bisa di-"Add to Home Screen" di HP, dan muncul di menu "Share to..." Android buat langsung kirim file/foto/link ke repo dari app lain.
- **Build App (APK/TWA)** — generate APK Android atau TWA dari repo mana pun, lengkap dengan share target otomatis dan konfigurasi login yang tetap di dalam app (nggak lempar ke Chrome).
- **Rate limiting & testing** — proteksi API sendiri per-IP, plus test suite (Jest) yang jalan otomatis lewat GitHub Actions tiap push/PR.

## Tech stack

Next.js 14 · React 18 · GitHub OAuth & Contents API · Vercel API · Jest

## Cara install (APK)

1. Download file APK lewat link di atas.
2. Kalau muncul peringatan "Install dari sumber tidak dikenal", izinkan dulu di pengaturan HP.
3. Buka file APK yang sudah di-download, ikuti proses install seperti biasa.

## Catatan

Ini repo showcase — source code lengkapnya ada di tempat lain (nggak di-publish di sini). Ada pertanyaan atau mau kontak? Chat lewat Telegram: [@Zypherium_OFFC](https://t.me/Zypherium_OFFC)
