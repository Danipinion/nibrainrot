# 🧠 Nibrainrot (Android)

> **Solusi offline anti-brainrot, detoks doom-scrolling, dan pelindung fokus produktivitas Anda.**

Nibrainrot adalah aplikasi Android open/distribusi mandiri yang dirancang untuk membantu Anda membatasi dan memblokir aplikasi pemicu adiksi digital (seperti media sosial, video pendek, game) secara 100% lokal tanpa ketergantungan server luar.

---

## 🚀 Fitur Utama

- ⏱️ **Daily Usage Quota**: Tentukan batas harian spesifik per aplikasi (misal: TikTok 10 menit, Instagram 15 menit). Saat kuota tercapai, aplikasi otomatis terkunci.
- 🧱 **Monk Mode / Mode Bata**: Blokir langsung seluruh akses aplikasi target seketika saat Anda butuh fokus mendalam.
- 🌙 **Detoks Malam (Scheduled Detox)**: Otomatis membatasi akses aplikasi adiktif pada jam istirahat malam (21:00 - 06:00).
- 🛡️ **Strict Anti-Bypass Shield**:
  - Emergency Math Challenge (soal hitung acak dua digit) untuk mencegah pembatalan impulsif.
  - Penjaga tombol kembali (*BackHandler intercept*) dan status bar.
- 🔒 **100% Privasi & Offline**: Data penggunaan dan aturan disimpan lokal menggunakan MMKV tercepat di perangkat Anda. Tanpa analitik pelacak.

---

## 📥 Download Aplikasi (Release v1.0.0)

Pilih APK sesuai arsitektur prosesor smartphone Android Anda:

| File APK | Target Arsitektur | Ukuran | Rekomendasi |
| :--- | :--- | :---: | :--- |
| [**app-arm64-v8a-release.apk**](https://github.com/Danipinion/nibrainrot/releases/download/v1.0.0/app-arm64-v8a-release.apk) | **ARM64 (64-bit)** | **~23 MB** | ⚡ **Sangat Disarankan** (Hampir semua HP Android modern sejak 2018) |
| [**app-universal-release.apk**](https://github.com/Danipinion/nibrainrot/releases/download/v1.0.0/app-universal-release.apk) | **Universal (Semua CPU)** | **~69 MB** | 📱 Kompatibel untuk semua tipe perangkat jika ragu |
| [**app-armeabi-v7a-release.apk**](https://github.com/Danipinion/nibrainrot/releases/download/v1.0.0/app-armeabi-v7a-release.apk) | **ARM 32-bit** | **~18 MB** | 📟 HP Android lawas / spesifikasi rendah |
| [**app-x86_64-release.apk**](https://github.com/Danipinion/nibrainrot/releases/download/v1.0.0/app-x86_64-release.apk) | **x86_64** | **~23 MB** | 💻 Emulator Android 64-bit / PC |
| [**app-x86-release.apk**](https://github.com/Danipinion/nibrainrot/releases/download/v1.0.0/app-x86-release.apk) | **x86 32-bit** | **~24 MB** | 💻 Emulator Android 32-bit |

---

## ⚙️ Petunjuk Instalasi & Perizinan

Agar aplikasi dapat memantau dan memblokir aplikasi adiktif dengan lancar:

1. **Download APK** (pilih `arm64-v8a` untuk HP modern).
2. **Pasang / Install APK**:
   - Jika muncul peringatan *"Install unknown apps"*, izinkan browser atau file manager Anda memasang APK.
3. **Berikan 3 Izin Utama saat pertama kali dibuka**:
   - 📊 **Akses Penggunaan (Usage Access)**: Untuk menghitung durasi buka aplikasi secara akurat.
   - ♿ **Layanan Aksesibilitas (Accessibility Service)**: Aktifkan **Nibrainrot** agar sistem dapat mencegat dan memblokir aplikasi target saat kuota habis.
   - 🪟 **Tampil di Atas Aplikasi Lain (Display Over Other Apps)**: Agar dialog peringatan pemblokiran dapat muncul di atas aplikasi yang dibuka.

### 💡 Tips Khusus Pengguna Realme / Oppo / Xiaomi / Vivo:
Untuk memastikan sistem pembersih RAM (*Close All*) tidak mematikan service pelindung:
- Buka **Recent Apps** (geser layar ke atas tahan).
- Ketuk titik tiga (**⋮**) di atas kartu **Nibrainrot**, lalu pilih **Kunci (Lock / Ikon Gembok)**.
- Di Pengaturan Baterai, pilih Nibrainrot → setel ke **Jangan Optimalkan / Allow background activity**.

---

## 📄 Lisensi
Didistribusikan untuk publik oleh [Danipinion](https://github.com/Danipinion).
