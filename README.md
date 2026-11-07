# Project Android: Dua Tiga Access

Project ini dibuat secara otomatis dari kode HTML, CSS, dan JavaScript Anda menggunakan **WebToAndroid Studio**.
Project ini siap langsung dibuka dan di-build menggunakan **Android Studio** atau di-build otomatis di **GitHub Actions**.

---

## 🚀 Cara 1: Buka & Build di Android Studio (Rekomendasi untuk Play Store)

1. **Ekstrak File ZIP** ini ke dalam folder di komputer Anda.
2. Unduh dan buka **Android Studio** (versi Flamingo, Hedgehog, Iguana, atau yang lebih baru).
3. Pilih **File > Open**, lalu arahkan ke folder hasil ekstrak ini.
4. Tunggu beberapa saat hingga Gradle selesai melakukan sinkronisasi (**Gradle Sync Finished**).
5. Untuk menguji coba di HP / Emulator:
   - Hubungkan HP Android via kabel data (pastikan *USB Debugging* aktif), atau buat Emulator di *Device Manager*.
   - Klik tombol hijau **Run 'app' (Shift + F10)**.

### Cara Membuat File APK / AAB untuk Google Play Store di Android Studio:
1. Di menu atas Android Studio, klik **Build > Generate Signed Bundle / APK...**
2. Pilih **Android App Bundle (.aab)** (Wajib untuk Google Play Store) atau **APK** jika hanya ingin dibagikan langsung ke pengguna.
3. Klik **Next**.
4. Pada bagian *Key store path*, jika belum punya klik **Create new...** dan buat kunci (.jks).
5. Pilih build variant **release**, lalu klik **Finish**.
6. File .aab / .apk siap diunggah ke Google Play Console!

---

## ☁️ Cara 2: Build APK Otomatis Tanpa Android Studio (GitHub Actions Gratis)

Jika komputer Anda lambat atau tidak ingin menginstal Android Studio (ukuran ~2GB+):
1. Buat repository baru di akun **GitHub** Anda (bisa public atau private).
2. Upload semua file dari folder ini ke repository GitHub tersebut.
3. Buka tab **Actions** di GitHub.
4. Workflow **Build Android APK Otomatis** akan berjalan sendiri.
5. Setelah selesai (~2 menit), download file APK hasil kompilasi dari bagian **Artifacts**!

---

## 📋 Syarat & Panduan Menerbitkan ke Google Play Store

1. **Akun Google Play Console**:
   - Biaya registrasi: $25 USD (sekali bayar seumur hidup).
   - Verifikasi identitas (KTP / Paspor) & nomor telepon.
2. **Aturan Baru Akun Personal (Sejak Nov 2023)**:
   - Akun developer personal wajib melakukan **Closed Testing dengan minimal 20 tester selama 14 hari berturut-turut** sebelum bisa mengajukan rilis ke Publik / Produksi.
3. **Aset Toko (Store Listing)**:
   - Ikon Aplikasi: 512 x 512 piksel (PNG 32-bit).
   - Gambar Fitur (Feature Graphic): 1024 x 500 piksel (PNG/JPG).
   - Screenshot Aplikasi: Minimal 2 screenshot untuk layar ponsel (rasio 9:16 atau 16:9).
   - Tautan Kebijakan Privasi (Privacy Policy URL).

---

## 🛠️ Letak File Kode Web Anda
Semua file HTML, CSS, dan JavaScript berada di:
`app/src/main/assets/www/`
- `index.html`
- `style.css`
- `app.js`

Anda dapat mengubah atau menambah file gambar/audio kapan saja di dalam folder tersebut!
