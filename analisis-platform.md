# Analisis Komparatif Platform

**Nama:** Fatihatul Ikrimah
**NIM:** 240511136
**Kelas:** TI24D
**Mata Kuliah:** Pemrograman Berbasis Platform
**Tugas:** Pertemuan 1 - Eksplorasi Platform & Setup Environment

---

## 1. Pendahuluan

Dalam pengembangan perangkat lunak, **platform** adalah lingkungan tempat sebuah aplikasi dibangun dan dijalankan. Platform menentukan bahasa pemrograman yang dipakai, alat pengembangan, cara aplikasi didistribusikan, serta pengalaman yang diterima pengguna. Tiga platform yang paling umum adalah **Web**, **Desktop**, dan **Mobile**. Ketiganya memiliki karakteristik berbeda sehingga pemilihan platform harus disesuaikan dengan kebutuhan pengguna, anggaran, dan tujuan aplikasi.

## 2. Gambaran Singkat Tiga Platform

### 2.1 Platform Web

Aplikasi web berjalan di dalam browser dan diakses melalui alamat URL. Kode antarmuka (frontend) dijalankan di sisi pengguna, sedangkan logika bisnis dan penyimpanan data (backend) dijalankan di server. Karena hanya membutuhkan browser, aplikasi web dapat dibuka dari berbagai perangkat dan sistem operasi tanpa instalasi.

### 2.2 Platform Desktop

Aplikasi desktop diinstal dan dijalankan langsung di sistem operasi komputer seperti Windows, macOS, atau Linux. Aplikasi jenis ini dapat mengakses sumber daya perangkat secara lebih leluasa, misalnya prosesor, memori, penyimpanan, dan perangkat eksternal, sehingga cocok untuk pekerjaan berat seperti pengolahan gambar, video, atau pengembangan perangkat lunak.

### 2.3 Platform Mobile

Aplikasi mobile berjalan di perangkat bergerak seperti ponsel pintar dan tablet dengan sistem operasi Android atau iOS. Aplikasi ini dapat memanfaatkan sensor dan fitur khas perangkat, seperti kamera, GPS, akselerometer, dan notifikasi push, serta digunakan kapan saja dan di mana saja.

## 3. Tabel Perbandingan

| Aspek | Web | Desktop | Mobile |
|---|---|---|---|
| Bahasa utama | HTML, CSS, JavaScript (frontend); PHP, Node.js, Python, Java (backend) | C++, C#, Java, Python | Kotlin dan Java (Android), Swift (iOS), Dart (Flutter), JavaScript/TypeScript (React Native) |
| Arsitektur | Client-server. Browser sebagai client, server menyimpan logika bisnis dan data, komunikasi lewat HTTP/HTTPS dan API | Berjalan langsung di sistem operasi, bisa standalone (berdiri sendiri) atau terhubung ke server | Berjalan di OS mobile, umumnya terhubung ke API atau backend dan memakai komponen bawaan OS |
| Cara distribusi | Diakses lewat URL di browser tanpa instalasi; developer cukup mengunggah ke server hosting | Installer (.exe, .msi, .dmg, .deb) yang diunduh dari situs resmi, atau toko aplikasi seperti Microsoft Store | Google Play Store, Apple App Store, atau file APK untuk Android |
| Keunggulan | Lintas perangkat dan OS, tidak perlu instalasi, pembaruan terpusat di server, mudah dijangkau banyak pengguna | Performa tinggi, akses penuh ke hardware dan file sistem, dapat digunakan offline, cocok untuk pekerjaan berat | Portabel, dapat mengakses sensor (GPS, kamera), mendukung notifikasi push, pengalaman pengguna terasa personal |
| Keterbatasan | Bergantung pada internet dan browser, akses ke hardware terbatas, performa umumnya di bawah aplikasi native | Harus diinstal di tiap perangkat, bergantung pada sistem operasi, pembaruan perlu dilakukan per perangkat | Layar kecil, ada proses review toko aplikasi, fragmentasi perangkat dan versi OS, daya baterai terbatas |
| Contoh aplikasi | Google Docs, Canva, Tokopedia (versi web), Wikipedia | Microsoft Word, Visual Studio Code, Adobe Photoshop, VLC Media Player | WhatsApp, Gojek, Instagram, Shopee |

## 4. Penjelasan Detail Tiap Aspek

### 4.1 Bahasa Pemrograman

Web memakai tiga bahasa inti di sisi client: **HTML** untuk struktur halaman, **CSS** untuk tampilan, dan **JavaScript** untuk interaksi. Di sisi server tersedia banyak pilihan seperti PHP, Node.js, dan Python. Desktop memakai bahasa yang dapat dikompilasi menjadi aplikasi yang berjalan di OS, seperti C++ dan C#. Mobile memiliki bahasa resmi masing-masing OS, yaitu Kotlin untuk Android dan Swift untuk iOS, serta pilihan lintas platform seperti Flutter (Dart) dan React Native.

### 4.2 Arsitektur

Arsitektur web bersifat **client-server**: browser mengirim permintaan, server memproses dan mengirim kembali hasilnya. Aplikasi desktop bisa berdiri sendiri tanpa server, tetapi banyak juga yang memakai arsitektur client-server untuk sinkronisasi data. Aplikasi mobile biasanya menjadi client yang berkomunikasi dengan backend melalui API, sambil menyimpan sebagian data secara lokal agar tetap bisa dipakai saat koneksi buruk.

### 4.3 Cara Distribusi

Distribusi web paling sederhana: cukup unggah ke server dan bagikan URL. Desktop didistribusikan lewat file installer atau toko aplikasi. Mobile umumnya melalui toko resmi (Play Store dan App Store) yang memiliki proses peninjauan dan aturan tertentu, tetapi menjangkau pengguna dalam jumlah besar.

### 4.4 Pembaruan Aplikasi

Pada web, pembaruan dilakukan sekali di server dan langsung dirasakan semua pengguna. Pada desktop dan mobile, pengguna perlu mengunduh atau memperbarui aplikasi di perangkatnya, meskipun mobile sudah dibantu fitur pembaruan otomatis dari toko aplikasi.

### 4.5 Performa dan Akses Perangkat

Desktop unggul dalam performa dan akses ke hardware. Mobile unggul dalam pemanfaatan sensor dan mobilitas. Web memiliki akses perangkat paling terbatas, namun teknologi modern seperti Progressive Web App (PWA) dan Web API mulai memperluas kemampuannya, misalnya notifikasi dan akses kamera.

## 5. Ringkasan Perbandingan Tambahan

| Kriteria | Web | Desktop | Mobile |
|---|---|---|---|
| Kebutuhan instalasi | Tidak ada | Ya | Ya (lewat toko aplikasi/APK) |
| Koneksi internet | Umumnya wajib | Opsional | Bervariasi, banyak yang wajib |
| Akses hardware | Terbatas | Penuh | Luas (sensor, kamera, GPS) |
| Kemudahan pembaruan | Sangat mudah (terpusat) | Perlu per perangkat | Lewat toko aplikasi |
| Jangkauan pengguna | Sangat luas | Terbatas pada pengguna komputer | Sangat luas |
| Cocok untuk | Layanan online, e-commerce, dasbor | Aplikasi produktivitas dan kreatif | Layanan harian, komunikasi, transportasi |

## 6. Kesimpulan

Ketiga platform memiliki kelebihan dan keterbatasan masing-masing. **Web** unggul dalam kemudahan akses dan pembaruan terpusat. **Desktop** unggul dalam performa dan akses penuh ke sistem. **Mobile** unggul dalam mobilitas dan pemanfaatan sensor perangkat. Tidak ada platform yang paling baik untuk semua kasus, sehingga pemilihannya harus mempertimbangkan kebutuhan pengguna, sumber daya pengembang, dan tujuan aplikasi. Dalam praktiknya, banyak layanan modern menyediakan ketiganya sekaligus, misalnya Spotify atau WhatsApp yang tersedia di web, desktop, dan mobile.

## 7. Catatan Setup Environment

- Git, Node.js + NPM, Visual Studio Code, dan Java JDK sudah terinstall dan hasil versinya dilampirkan pada laporan PDF.
- Android Studio: sudah terinstall (versi 2026.2, build AI-262.9437.185.2621.16467767), terpasang di C:\Program Files\Android\Android Studio1.

## 8. Referensi

1. MDN Web Docs. *Learn web development*. https://developer.mozilla.org/en-US/docs/Learn
2. Android Developers. *Android Developer Documentation*. https://developer.android.com/docs
3. Microsoft Learn. *Windows app development documentation*. https://learn.microsoft.com/en-us/windows/apps/
4. Flutter. *Flutter documentation*. https://docs.flutter.dev
5. GitHub Docs. *Get started with Git and GitHub*. https://docs.github.com/en/get-started
