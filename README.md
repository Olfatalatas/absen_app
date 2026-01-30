# absen_app ✅

**Aplikasi Absensi** sederhana yang dibuat dengan Flutter untuk keperluan mobile (Android/iOS). README ini menjelaskan cara menjalankan, membangun, dan berkontribusi pada proyek ini. 💡

---

## 🔎 Ringkasan

- **Nama:** absen_app
- **Platform:** Android, iOS, Web (opsional)
- **Stack:** Flutter, Dart
- **Fitur utama:** login, absen, absen terlambat, ijin, profil, riwayat

---

## 🚀 Quick Start (Instal & Jalankan)

Prasyarat:
- Flutter SDK (stable)
- Android SDK (atau Xcode untuk iOS)
- Git

Langkah singkat:
```bash
# clone repo
git clone https://github.com/ezyrangers/absenceapps.git
cd absen_app

# install dependencies
flutter pub get

# jalankan di device/emulator
flutter run
```

> Catatan: Pastikan device/emulator tersambung dan konfigurasi SDK sudah benar.

---

## 🛠 Struktur Proyek (singkat)

- `lib/main.dart` — entry point aplikasi
- `lib/page/` — halaman UI (login, home, absen, profile, dll.)
- `lib/API_code/` — kode untuk berinteraksi dengan backend / API
- `assets/` — fonts, icons, images
- `android/`, `ios/` — konfigurasi masing-masing platform

---

## ✅ Fitur Utama

- Autentikasi (Login, Register)
- Absen: masuk/keluar
- Absen terlambat
- Permintaan ijin (izin keluar/masuk)
- Profil pengguna & foto
- Riwayat absensi

---

## ⚙️ Konfigurasi & Environment

- Jika aplikasi membutuhkan endpoint backend, periksa `lib/API_code/` untuk lokasi konfigurasi URL/API. Sesuaikan nilai pada file konfigurasi atau environment sesuai kebutuhan.
- Pastikan `assets/` terdaftar pada `pubspec.yaml` jika menambahkan file baru.

---

## 🧪 Testing

Jalankan tes unit/widget (jika ada):
```bash
flutter test
```

---

## 🧩 Membangun Aplikasi (Release)

Android APK:
```bash
flutter build apk --release
```

iOS (dengan Xcode):
```bash
flutter build ios --release
# lalu buka Xcode untuk archive & upload
```

---

## 🤝 Kontribusi

Sambutan untuk PR & issue:
- Buka issue untuk mendiskusikan fitur/bug sebelum mengirim PR besar.
- Ikuti standar penamaan branch dan sertakan deskripsi perubahan pada PR.

---

## 📄 Lisensi

Tambahkan file `LICENSE` jika ingin melisensikan proyek ini (mis. MIT). Jika belum, tambahkan lisensi yang sesuai.

---

## 📬 Kontak

Jika butuh bantuan lebih lanjut atau akses ke backend/API, hubungi maintainer repository atau buka issue di GitHub.

---

Terima kasih sudah menggunakan/berkontribusi pada proyek ini! 🙏

