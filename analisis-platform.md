# Analisis Perbandingan Platform

| Aspek | Web | Desktop | Mobile |
| :--- | :--- | :--- | :--- |
| **Arsitektur** | Client-Server (berjalan di atas web browser dan berkomunikasi dengan server melalui protokol HTTP/HTTPS). | Standalone / Monolitik atau Client-Server lokal (terinstal dan berjalan langsung di atas sistem operasi host). | Event-Driven & Client-Server (berjalan di lingkungan sandbox OS mobile dan terhubung ke backend via REST API). |
| **Bahasa Utama** | HTML5, CSS3, JavaScript / TypeScript (Front-End); Node.js, PHP, Python (Back-End). | Java (JavaFX/Swing), C# (.NET), C++, Python, JavaScript (Electron). | Kotlin / Java (Android), Swift / Objective-C (iOS), Dart (Flutter). |
| **Distribusi** | Melalui URL/domain via web browser tanpa perlu proses instalasi manual oleh pengguna. | Melalui file installer (`.exe`, `.dmg`, `.deb`, atau `.jar`) yang diunduh dan dipasang langsung pada OS. | Melalui toko aplikasi resmi (Google Play Store, Apple App Store) atau paket instalasi (`.apk` / `.ipa`). |
| **Keunggulan** | Lintas platform secara otomatis (cukup punya browser), pembaruan aplikasi terpusat di server, dan mudah dibagikan. | Performa komputasi tinggi, dapat berjalan secara offline penuh, serta memiliki akses penuh ke perangkat keras dan sistem file. | Akses langsung ke sensor perangkat (GPS, kamera, akselerometer), portabilitas tinggi, dan mendukung push notification. |
| **Keterbatasan** | Sangat bergantung pada koneksi internet, akses ke hardware perangkat terbatas oleh keamanan browser. | Membutuhkan spesifikasi hardware yang sesuai, proses update aplikasi bergantung pada instalasi ulang di sisi pengguna. | Ukuran layar terbatas, sumber daya baterai dan memori lebih ketat, serta aturan publikasi store yang cukup ketat. |
| **Contoh Aplikasi** | Tokopedia, Gmail, Google Docs, Portal Akademik. | Visual Studio Code, Adobe Photoshop, Spotify Desktop. | WhatsApp, Gojek, Instagram, Mobile Banking. |
