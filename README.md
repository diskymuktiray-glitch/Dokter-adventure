# Dokter Adventure

Game petualangan 2D sederhana untuk Android, memakai dua foto yang diberikan sebagai karakter utama dan partner.

## Cara menjalankan di Android
1. Ekstrak ZIP ini.
2. Buka folder `dokter_adventure` melalui Android Studio.
3. Tunggu Gradle Sync selesai (Android Studio perlu akses internet untuk mengunduh Android Gradle Plugin).
4. Pilih perangkat Android atau emulator, lalu tekan **Run**.
5. Untuk membuat APK: **Build > Build Bundle(s) / APK(s) > Build APK(s)**. APK debug biasanya berada di `app/build/outputs/apk/debug/app-debug.apk`.

## Cara mencoba tanpa Android Studio
Buka `app/src/main/assets/index.html` di browser yang mendukung JavaScript. Untuk pengalaman terbaik, jalankan melalui server lokal atau dari aplikasi Android.

## Kontrol
- ◀ / ▶: bergerak
- ⬆: melompat
- Kumpulkan koin dan kotak P3K, hindari duri.
- Kotak P3K bernilai 5 poin; koin bernilai 1 poin.

## Catatan
- Proyek ini adalah source project Android Studio, bukan APK yang sudah dikompilasi.
- Kompilasi APK memerlukan Android Studio, Android SDK 35, dan koneksi internet untuk sinkronisasi Gradle pertama kali.
