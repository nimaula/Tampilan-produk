# Kantin Jujur — Kotlin + XML

Contoh project Android Studio untuk UI aplikasi POS Kantin Jujur berdasarkan referensi gambar.

## Fitur
- Katalog produk dalam grid dua kolom.
- 12 contoh produk, dengan kategori **Jajanan** dan **Minuman**.
- Pencarian produk dan filter kategori.
- Halaman detail produk: gambar ilustratif/emoji, kategori, nama, harga, ketersediaan, deskripsi, pengatur jumlah, dan tombol tambah ke keranjang.
- Ringkasan jumlah barang di keranjang.
- Layout ditulis menggunakan XML dan logika aplikasi menggunakan Kotlin.

## Cara membuka
1. Ekstrak folder ZIP.
2. Buka Android Studio → **Open** → pilih folder `KantinJujurKotlinXML`.
3. Tunggu Gradle Sync selesai.
4. Jalankan aplikasi di emulator atau perangkat Android.

## Catatan
- Ilustrasi produk saat ini memakai emoji sebagai placeholder agar project bisa langsung dicoba tanpa file gambar eksternal. Ganti dengan foto produk sendiri melalui `ImageView` dan drawable jika sudah ada asetnya.
- Harga dan deskripsi produk masih contoh, silakan sesuaikan.
