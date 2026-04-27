# Kelengkapan TIKA AI Bot (Live TikTok Automation)

Repository ini berisi file-file instalasi APK yang diperlukan untuk menjalankan sistem otomatisasi (Live TikTok Automation) menggunakan **TIKA AI Bot**. Aplikasi-aplikasi ini dikembangkan untuk bekerja sama dalam mengambil token tiktok dan memproses data dari sesi Live TikTok.

## Daftar File & Fungsinya

### 1. `TikTok-Khusus-TIKA.apk`
- **Fungsi:** Ini adalah aplikasi TikTok yang telah dikonfigurasi dan disesuaikan untuk kebutuhan TIKA AI. Aplikasi ini digunakan untuk melakukan *Live* atau berinteraksi di ruang *Live streaming*. 

### 2. `TIKA GET TOKEN.apk`
- **Fungsi:** Aplikasi pendukung yang bertugas sebagai pengambil token dari sesi live tiktok dan pengekstrak data penting lainnya. 

## Panduan Penggunaan Singkat
1. Pasang/instal aplikasi **TIKA GET TOKEN.apk** di perangkat Android (atau emulator).
2. Pasang/instal aplikasi **TikTok-Khusus-TIKA.apk** di perangkat yang sama.
3. Jalankan aplikasi *TIKA GET TOKEN* terlebih dahulu untuk mengaktifkan proksi layanan dan memonitor trafik.
4. Buka aplikasi *TikTok-Khusus-TIKA*, lakukan login seperti biasa, lalu jalankan/gabung ke *Live*. 
5. Sistem (aplikasi get token) akan secara otomatis menangkap *payload data webcast* yang kemudian dapat dimanfaatkan oleh sistem _bot_.

---
*Catatan: Repository ini menggunakan sistem **Git Large File Storage (LFS)** karena ukuran file APK (TikTok) melebihi batas reguler GitHub.*
