# RELLZ STORE — Website Katalog

Website katalog jual beli akun game dengan desain dark navy + neon biru, mobile-first, memakai logo yang diberikan.

## Fitur
- Profil toko dan logo RELLZ STORE
- Katalog MLBB dan Free Fire
- Filter game, pencarian, dan urut harga
- Detail produk dalam modal
- Tombol order yang membuka WhatsApp admin
- Bagian layanan, contoh biaya admin, pembayaran, dan pengingat keamanan
- Tidak memerlukan build step atau database untuk versi katalog ini

## Penting sebelum dipublikasikan
1. Buka `index.html`.
2. Cari `const products = [` lalu ganti produk contoh dengan listing asli, harga, detail, dan status ketersediaan.
3. Cari `ADMIN_WA` untuk mengganti nomor WhatsApp jika diperlukan.
4. Periksa bagian biaya admin dan sesuaikan dengan aturan toko.
5. Tambahkan nomor/QR pembayaran hanya jika sudah siap dan pastikan data pembayaran benar.
6. Jangan meminta atau menyimpan password, OTP, maupun kode pemulihan pelanggan di website publik.

## Deploy ke Vercel (mudah via GitHub)
1. Ekstrak ZIP ini di HP/komputer.
2. Buat akun atau masuk ke GitHub, lalu buat repository baru bernama `rellz-store`.
3. Upload `index.html`, `vercel.json`, folder `assets/`, dan `README.md` ke repository (pastikan `index.html` berada di root).
4. Buka https://vercel.com dan masuk menggunakan GitHub.
5. Pilih **Add New → Project**, lalu import repository `rellz-store`.
6. Framework preset: **Other**. Build command dan output directory bisa dikosongkan/default karena ini situs statis.
7. Klik **Deploy**. Setelah selesai, Vercel memberikan URL website.
8. Jika mengubah file di GitHub, Vercel akan otomatis deploy ulang.

## Uji lokal
Buka `index.html` langsung di browser. Untuk hasil paling konsisten, jalankan melalui server statis lokal.

## Struktur
- `index.html` — seluruh tampilan, gaya, dan interaksi katalog
- `assets/logo.png` — logo toko yang diunggah
- `vercel.json` — konfigurasi deployment statis
