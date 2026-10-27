# Kebijakan Privasi / Privacy Policy - Remiqo

*Terakhir diperbarui: 27 Oktober 2026 / Last updated: October 27, 2026*

---

## 🇮🇩 Bahasa Indonesia

Aplikasi **Remiqo** ("kami", "aplikasi") dikembangkan dengan komitmen penuh terhadap privasi dan keamanan pengguna. Kebijakan Privasi ini menjelaskan bagaimana aplikasi kami mengelola data Anda saat menggunakan Remiqo.

### 1. Pengumpulan dan Penggunaan Data
**Remiqo tidak mengumpulkan, menyimpan, mentransmisikan, atau membagikan informasi pribadi atau data penggunaan Anda kepada siapa pun.**

- **Tidak Ada Registrasi / Akun**: Anda tidak perlu mendaftar, memasukkan email, nomor telepon, atau membuat akun untuk menggunakan aplikasi ini.
- **Penyimpanan Lokal 100%**: Semua data pengingat (judul alarm, waktu, hari pengulangan, pengaturan warna visual, dan preferensi dering) disimpan secara lokal di memori internal perangkat Anda menggunakan basis data SQLite/Room terenkripsi sistem Android.
- **Tanpa Iklan dan Pelacak**: Kami tidak menyematkan pustaka iklan pihak ketiga (seperti Google AdMob) maupun analitik pelacak perilaku (seperti Firebase Analytics).

### 2. Penjelasan Izin Perangkat (Permissions)
Remiqo hanya meminta izin sistem yang benar-benar esensial untuk menjalankan fungsi inti alarm dan pengingat:

| Izin Sistem | Tujuan Penggunaan |
| :--- | :--- |
| `POST_NOTIFICATIONS` | Menampilkan pemberitahuan status alarm aktif, pengingat yang akan datang, dan kontrol snooze/dismiss. |
| `SCHEDULE_EXACT_ALARM` | Menjadwalkan alarm agar berbunyi tepat pada waktu yang telah Anda tetapkan, tanpa tertunda oleh mode hemat daya sistem (Doze mode). |
| `USE_FULL_SCREEN_INTENT` | Menampilkan layar alarm visual berkedip secara penuh saat perangkat dalam keadaan terkunci (Lock Screen). |
| `FOREGROUND_SERVICE` & `FOREGROUND_SERVICE_SPECIAL_USE` | Menjaga suara dering dan getaran tetap berbunyi terus-menerus hingga pengguna mematikan atau menunda alarm, bahkan jika layar mati. |
| `VIBRATE` | Menggetarkan perangkat saat alarm berbunyi sesuai preferensi yang Anda atur. |
| `WAKE_LOCK` | Menyalakan layar perangkat sementara saat alarm aktif agar visual pengingat langsung terlihat. |
| `RECEIVE_BOOT_COMPLETED` | Menjadwalkan ulang alarm yang aktif secara otomatis setelah perangkat Anda di-restart/dinyalakan ulang. |

Semua izin di atas digunakan secara eksklusif di dalam perangkat Anda dan tidak pernah mengakses internet untuk mentransfer data apa pun.

### 3. Privasi Anak-Anak
Aplikasi Remiqo aman untuk semua umur dan tidak menargetkan atau mengumpulkan data dari anak-anak di bawah umur 13 tahun.

### 4. Perubahan pada Kebijakan Privasi
Kami dapat memperbarui Kebijakan Privasi ini sewaktu-waktu jika terdapat pembaruan fungsi aplikasi. Setiap perubahan akan diperbarui pada halaman ini dengan tanggal pembaruan yang baru.

### 5. Kontak Pengembang
Jika Anda memiliki pertanyaan mengenai Kebijakan Privasi ini, silakan hubungi pengembang melalui:
- **Email**: `gonisetiawan0@gmail.com`
- **Repositori**: `https://github.com/setiawanboedy/remiqo-privacy-policy`

---

## 🇬🇧 English

The **Remiqo** app ("we", "our", or "the app") is committed to respecting and protecting your privacy. This Privacy Policy explains our practices regarding your data when using Remiqo.

### 1. Data Collection and Usage
**Remiqo does NOT collect, store, transmit, or share any personal information or analytics with any server or third party.**

- **No User Accounts**: You do not need to register, log in, or provide any personal details (such as name, email, or location) to use Remiqo.
- **100% Local Storage**: All your alarm data (titles, time triggers, recurrence schedules, visual color palettes, and ringtone preferences) remain exclusively on your device's internal storage via SQLite/Room.
- **No Ads & No Trackers**: Remiqo does not integrate third-party advertising SDKs or tracking mechanisms.

### 2. Device Permissions Used
Remiqo requests only the permissions strictly required to provide core alarm and reminder capabilities:

| Permission | Purpose |
| :--- | :--- |
| `POST_NOTIFICATIONS` | Displays upcoming reminder notifications and active alarm controls. |
| `SCHEDULE_EXACT_ALARM` | Ensures alarms trigger at the exact scheduled second, even during system battery-saving modes. |
| `USE_FULL_SCREEN_INTENT` | Presents the full-screen visual flashing screen when the alarm rings while the device is locked. |
| `FOREGROUND_SERVICE` & `FOREGROUND_SERVICE_SPECIAL_USE` | Ensures continuous ringtone playback and vibration until you dismiss or snooze the alarm. |
| `VIBRATE` | Powers haptic feedback and custom vibration patterns during alarms. |
| `WAKE_LOCK` | Turns on the screen when an alarm fires so the visual reminder is instantly visible. |
| `RECEIVE_BOOT_COMPLETED` | Automatically reschedules active alarms after device reboot. |

None of these permissions are used to collect or exfiltrate any data.

### 3. Children's Privacy
Remiqo does not address anyone under the age of 13 and collects zero personal data from any user.

### 4. Contact Us
For any inquiries regarding this Privacy Policy, please reach out to:
- **Email**: `gonisetiawan0@gmail.com`
- **Repository**: `https://github.com/setiawanboedy/remiqo-privacy-policy`
