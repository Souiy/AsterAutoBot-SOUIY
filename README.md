# AsterAutoBot-SOUIY

![Banner](https://i.imgur.com/placeholder.png) <!-- Anda bisa menambahkan gambar banner di sini -->

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
2. (Opsional) Buat file `proxy.txt` untuk proxy (satu proxy per baris, format: http://, https://, socks4://, socks5://)

Contoh `token.txt`:
```
token_anda_1
token_anda_2
token_anda_3
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
