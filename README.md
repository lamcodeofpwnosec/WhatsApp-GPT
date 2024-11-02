# WhatsApp-GPT

**WhatsApp-GPT** adalah solusi canggih untuk mengotomatiskan balasan pesan di WhatsApp menggunakan teknologi AI ChatGPT (GPT-4) yang ditawarkan oleh OpenAI. Bot ini mengintegrasikan kemampuan pemrosesan bahasa alami yang luar biasa dengan antarmuka WhatsApp, memungkinkan pengguna untuk menjawab pertanyaan secara otomatis dan memberikan balasan yang cerdas dalam waktu nyata. 

AutoResponder ini sangat cocok digunakan untuk bisnis, layanan pelanggan, atau bahkan kebutuhan pribadi, dengan keunggulan dari model AI yang dapat menangkap konteks, menjawab pertanyaan kompleks, dan menghasilkan tanggapan yang sangat alami.

---

# ✨ Fitur Utama

- **Integrasi AI Cerdas**: Menggunakan teknologi OpenAI ChatGPT untuk memberikan balasan pesan yang akurat dan relevan.
- **Gambar Generatif dengan DALL-E**: Menghasilkan gambar berdasarkan perintah teks menggunakan model DALL-E.
- **Pengelolaan Pesan Grup**: Kemampuan menangani dan merespons pesan dari grup WhatsApp secara efektif.
- **Dukungan untuk Perintah Custom**: Anda dapat menambahkan dan memodifikasi perintah sesuai kebutuhan.
- **Log dan Notifikasi**: Memantau log aktivitas bot dengan warna yang berbeda untuk tampilan yang lebih informatif dan mudah dibaca.

---

# 🚀 Panduan Instalasi Lengkap

Ikuti langkah-langkah di bawah ini untuk mengatur dan menjalankan WhatsApp-GPT di sistem Anda:

### 1. **Kloning Repositori**
Pertama, Anda perlu mengkloning repositori dari GitHub ke komputer Anda:
```bash
   git clone https://github.com/lamcodeofpwnosec/WhatsApp-GPT.git
   cd WhatsApp-GPT
```
2. Menginstal Dependensi
Pastikan Anda telah menginstal Node.js di sistem Anda. Jika belum, unduh dan instal dari sini. Setelah itu, jalankan perintah berikut untuk menginstal semua dependensi:
```
npm install
```
3. Konfigurasi API Key OpenAI
Buat akun OpenAI dan buat API key di OpenAI Account.
Masukkan API key Anda ke dalam file `key.json`. Buat file key.json jika belum ada, dengan struktur sebagai berikut:
```json
{
  "keyopenai": "ISI_API_KEY_ANDA_DI_SINI"
}
```
4. Menjalankan Bot
Untuk menjalankan bot, jalankan perintah berikut di terminal Anda:
```
node index.js  
```
Bot akan mulai berjalan, dan QR code akan ditampilkan di terminal Anda. Pindai QR code dengan aplikasi WhatsApp untuk menghubungkan bot ke akun WhatsApp Anda.
5. Memantau Log Aktivitas
 * Anda dapat memantau log aktivitas bot di terminal. Log akan berisi informasi tentang pesan masuk, perintah yang diterima, dan balasan yang dikirim.
 * Pesan yang diterima dari pengguna akan ditampilkan dengan warna yang berbeda, membuatnya lebih mudah untuk dibaca dan dianalisis.


# 📚 Dokumentasi Perintah
 * Perintah AI (ChatGPT)
   * Cmd: `/ai`
   * _Deskripsi_: Mengajukan pertanyaan atau permintaan kepada AI dan menerima balasan yang dihasilkan oleh model GPT.
   * Contoh Penggunaan: `/ai Apa itu resesi ekonomi?`
  
 * Perintah Gambar (DALL-E)
   * Cmd: `/img`
   * Deskripsi: Membuat gambar dari deskripsi teks menggunakan DALL-E.
   * Contoh Penggunaan: `/img Rumah kayu di gunung bersalju`
  
 * Perintah Lainnya
   * Cmd: /sc atau /script
   * Deskripsi: Menampilkan sumber kode bot.

# 🛠️ Pemecahan Masalah
1. QR Code Tidak Muncul: Pastikan Anda memiliki koneksi internet yang stabil dan tidak ada proses yang mengganggu terminal.
2. Error API Key: Periksa kembali apakah API key Anda sudah benar dan file `key.json` sudah diisi dengan benar.
3. Bot Tidak Merespons: Cek apakah ada error yang muncul di terminal dan perbaiki berdasarkan pesan error tersebut.

# 📦 Dependensi yang Digunakan
 * **@whiskeysockets/baileys:** Untuk menghubungkan bot ke WhatsApp.
 * **axios:** Untuk mengelola permintaan HTTP.
 * **OpenAI:** Untuk integrasi API OpenAI GPT dan DALL-E.
 * **chalk:** Untuk tampilan log berwarna di terminal.
 * **figlet:** Untuk membuat header teks yang keren di terminal.


# 🤝 Kontribusi
Kami menyambut kontribusi dalam bentuk pull request, masalah (issues), atau saran untuk perbaikan. Silakan fork repositori ini dan kirimkan pull request dengan perubahan Anda!
&copy; [PT. Pwn0Sec DIGITAL TECHNOLOGIES LTD.](https://www.pwn0sec.com/) 


