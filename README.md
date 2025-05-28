# AsterAutoBot-SOUIY

![Banner](https://private-user-images.githubusercontent.com/81974190/448452258-c1b763be-d424-47d9-8b02-b0310738e52d.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDg0NDQ2NTgsIm5iZiI6MTc0ODQ0NDM1OCwicGF0aCI6Ii84MTk3NDE5MC80NDg0NTIyNTgtYzFiNzYzYmUtZDQyNC00N2Q5LThiMDItYjAzMTA3MzhlNTJkLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTA1MjglMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwNTI4VDE0NTkxOFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTVmNDQyMWQ4MmM1MmM4Yjk5YTM5YjM2OWU1YjdlMTI4MjFiYjVlZmYzYTVkNDVmZjc1M2NmZDhiOTdhNmQ3Y2MmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.fbeYhK3K-QHd31qISvtNDYT-i_IRhbe9OLHY0YvEjWA) <!-- Anda bisa menambahkan gambar banner di sini -->

Bot otomatis untuk menyelesaikan tugas harian dan sosial di platform AsterAI, dengan dukungan proxy dan manajemen multi-akun.

## ✨ Fitur

- ✅ Dukungan multi-akun (membaca token dari `token.txt`)
- 🌐 Dukungan proxy (HTTP/SOCKS4/SOCKS5)
- 📊 Pelacakan tugas dan statistik detail
- 🔄 Mekanisme retry otomatis untuk request yang gagal
- 🎨 Tampilan console yang indah dengan warna dan gradient
- ⏳ Otomatisasi siklus 24 jam
- 📝 Sistem logging yang komprehensif

## 📦 Persyaratan

- Node.js v16 atau lebih tinggi
- Package manager npm/yarn
- Token akun AsterAI

## 🚀 Instalasi

1. Clone repository:
```bash
git clone https://github.com/Souiy/AsterAutoBot-SOUIY.git
cd AsterAutoBot-SOUIY
```

2. Install dependensi:
```bash
npm install
```
atau
```bash
yarn install
```

## ⚙️ Konfigurasi

1. Buat file `token.txt` di root project dan tambahkan token AsterAI Anda (satu token per baris)
```
nano token.txt
```
   
3. (Opsional) Buat file `proxy.txt` untuk proxy (satu proxy per baris, format: http://, https://, socks4://, socks5://)
   
```
nano proxy.txt
```

Contoh `token.txt`:
```
eyj...
eyj..
```

Contoh `proxy.txt`:
```
http://user:pass@host:port
socks5://user:pass@host:port
```

## 🏃‍♂️ Cara Menggunakan

Jalankan bot:
```bash
node index.js
```

Bot akan:
1. Menanyakan apakah ingin menggunakan proxy
2. Memuat token dan proxy (jika diaktifkan)
3. Memproses setiap akun secara berurutan
4. Menampilkan progress bar dan pembaruan status
5. Berjalan dalam siklus 24 jam secara otomatis

## 📊 Kategori Tugas yang Didukung

- Tugas sosial (Twitter, Telegram, dll.)
- Tugas referral
- Tugas harian
- Tugas platform lainnya

## 🛠️ Detail Teknis

- Dibangun dengan Node.js
- Menggunakan Axios untuk HTTP request
- Menerapkan rotasi proxy
- Fitur penanganan error yang komprehensif
- Termasuk mekanisme retry untuk request yang gagal
- Tampilan console yang indah dengan `chalk`, `gradient-string`, dan `cfonts`

## 📝 Sistem Logging

Bot ini memiliki sistem logging yang lengkap dengan:
- Timestamp
- Level log (INFO, WARN, ERROR, DEBUG)
- Informasi kontekstual
- Indikator emoji
- Pesan berwarna

## 🤝 Berkontribusi

Kontribusi diterima! Silakan fork repository dan ajukan pull request.

## 📜 Lisensi

MIT

## 💌 Kontak

Untuk dukungan atau pertanyaan, silakan hubungi:
- TikTok: [@Souiy1](https://www.tiktok.com/@Souiy1)
- GitHub: [Souiy](https://github.com/Souiy)

## 🙏 Donasi

Dukung bantuan untuk Palestina:
🔗 [Donasi Disini](https://digital.dompetdhuafa.org/donasi/jagapalestina)

---

**Catatan Tambahan:**
- Bot ini dibuat untuk memudahkan penyelesaian tugas harian AsterAI
- Gunakan dengan bijak dan sesuai aturan platform
- Jangan lupa follow TikTok @Souiy1 untuk update terbaru
- Satukan solidaritas untuk membantu Palestina! 🇵🇸

**Perubahan Terakhir:** 28 Mei 2025
