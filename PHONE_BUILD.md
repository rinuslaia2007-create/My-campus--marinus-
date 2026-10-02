# Cara membuat APK langsung dari HP

1. Buat akun/login GitHub di browser HP.
2. Buat repository baru, misalnya `mycampus-marinus`.
3. Upload seluruh isi ZIP ini ke repository (termasuk folder `.github`).
4. Buka tab **Actions** → workflow **Build MyCampus APK** → **Run workflow**.
5. Tunggu sampai selesai.
6. Buka hasil run → bagian **Artifacts** → download `MyCampus-debug-apk`.
7. Ekstrak ZIP hasil download, lalu buka `app-debug.apk` dan instal di HP.

Catatan: GitHub yang melakukan proses build di cloud, jadi HP tidak perlu Android Studio atau Android SDK.
