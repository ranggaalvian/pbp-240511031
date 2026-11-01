# Analisis Komparatif Platform

Perbandingan tiga platform pengembangan aplikasi: Web, Desktop, dan Mobile.

| Aspek | Web | Desktop | Mobile |
|---|---|---|---|
| **Bahasa utama** | HTML, CSS, JavaScript/TypeScript (frontend); PHP, Python, Node.js, Java, Go (backend) | C++, C#, Java, Python, Swift (macOS), Rust; Electron memakai JavaScript | Kotlin dan Java (Android); Swift dan Objective-C (iOS); Dart (Flutter); JavaScript/TypeScript (React Native) |
| **Arsitektur** | Client-server: browser sebagai client, server dan database di sisi backend; komunikasi lewat HTTP/HTTPS dan REST/GraphQL API | Aplikasi berjalan langsung di sistem operasi lokal (standalone), memakai sumber daya perangkat secara langsung; dapat bersifat offline atau terhubung ke server | Aplikasi native atau cross-platform yang berjalan di OS mobile (Android/iOS), umumnya terhubung ke backend lewat API, dengan akses sensor perangkat (kamera, GPS, dsb.) |
| **Cara distribusi** | Diakses melalui URL di browser tanpa instalasi; di-deploy ke server atau cloud hosting | Installer (.exe, .msi, .dmg, .deb), situs resmi vendor, atau toko aplikasi seperti Microsoft Store dan Mac App Store | Toko aplikasi resmi (Google Play Store, Apple App Store) atau file APK untuk Android; melalui proses review dan penandatanganan aplikasi |
| **Keunggulan** | Lintas platform otomatis; tidak perlu instalasi; pembaruan langsung bagi semua pengguna; mudah dijangkau banyak orang | Performa tinggi; akses penuh ke hardware dan sistem file; dapat berjalan offline; cocok untuk tugas berat (desain, video, pengembangan) | Portabel dan selalu dibawa pengguna; akses ke sensor dan fitur perangkat; mendukung notifikasi push; pengalaman pengguna yang akrab dengan sentuhan |
| **Keterbatasan** | Bergantung pada koneksi internet dan browser; performa dan akses hardware terbatas; kompatibilitas antarbrowser | Harus diinstal dan diperbarui per perangkat; tergantung sistem operasi (perlu versi berbeda untuk Windows/macOS/Linux); tidak mobile | Perlu mengikuti aturan toko aplikasi; biaya pengembangan untuk dua platform; ukuran layar kecil; baterai dan penyimpanan terbatas |
| **Contoh aplikasi** | Google Docs, Tokopedia (versi web), GitHub, Canva (web) | Microsoft Word, Visual Studio Code, Adobe Photoshop, VLC Media Player | WhatsApp, Gojek, Instagram, Google Maps |

## Kesimpulan

- **Web** cocok untuk aplikasi yang harus mudah diakses oleh banyak pengguna tanpa instalasi.
- **Desktop** cocok untuk aplikasi yang membutuhkan performa tinggi dan akses penuh ke perangkat keras.
- **Mobile** cocok untuk aplikasi yang dekat dengan aktivitas harian pengguna dan memanfaatkan fitur perangkat bergerak.

Pemilihan platform sebaiknya disesuaikan dengan kebutuhan pengguna, anggaran, dan kompleksitas fitur aplikasi.
