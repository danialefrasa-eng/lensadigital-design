# Lensadigital

Lensadigital menjual produk digital berbahasa Indonesia (ebook, cheat sheet, tracker, AI mini app) untuk pembeli di Indonesia. Toko utamanya di OrderHero (`lensadigital.orderhero.id`). Gaya visualnya berasal dari logo: lensa kamera di atas latar hitam pekat, wordmark putih, dan kata "digital" dalam oranye menyala.

## Sumber

- **Logo** (`assets/Logos/lensadigital-logo.png`): semua warna di sistem ini diambil langsung dari pikselnya.
- **Font Poppins**: ini asumsi karena wordmark mirip sans geometris tebal. Ganti kalau font aslinya diketahui.
- Spasi, radius, dan komponen masih set awal yang kecil, belum diambil dari landing page yang sudah jadi.

## Konten dan nada bicara

- Bahasa Indonesia sehari-hari yang sopan. Pakai "kamu", bukan "Anda", kecuali untuk audiens orang tua.
- Kalimat pendek dan langsung ke manfaat. Contoh: "Menu MPASI seminggu, jadi dalam 2 menit."
- Angka ditulis apa adanya ("Rp49.000", "7 hari"), tanpa klaim yang tidak bisa dibuktikan.
- Tombol memakai kata kerja: **Ambil Sekarang**, **Lihat Isi Produk**, **Coba Gratis**.

## Fondasi visual

- **Gelap dulu.** Tema utama `dark`: latar `surface-000` (#010508), kartu di `surface-100`, garis di `surface-200`. Tema `light` dipakai untuk halaman panjang yang banyak teksnya.
- **Oranye itu sinyal.** `brand-orange` hanya untuk satu hal terpenting per layar: tombol utama, harga, atau satu kata sorotan di judul (seperti "digital" di logo). Jangan dipakai sebagai latar section penuh.
- **Teks di atas oranye** selalu `on-brand` (hitam), bukan putih. Putih di atas oranye hanya 2,7:1 dan tidak lolos.
- **Teks oranye** memakai `brand-orange-text`, yang otomatis lebih gelap di tema terang.
- **Bentuk membulat.** Logonya lingkaran, jadi tombol utama memakai `radius-pill` dan kartu memakai `radius-lg`.
- **Kedalaman:** kartu unggulan memakai `shadow-glow`. Selebihnya cukup garis `surface-200`, tanpa bayangan berat.
- Hindari gradien ungu-biru dan emoji sebagai ikon. Kilau warna-warni di lensa logo hanya milik logo.

## Tipografi

Satu keluarga, yaitu Poppins (Google Fonts, berat 400/500/600/700). Judul tebal 700 dan rapat, isi 400. Gaya yang tersedia: `display`, `h1`–`h3`, `body-lg`, `body`, `caption`.

## Ikonografi

Belum ada set ikon. Sementara pakai ikon garis sederhana (stroke 1,5–2px) berwarna `silver` atau `text-muted`. Ikon oranye hanya di samping tombol utama.

## Logo

- Pakai di atas latar gelap. Logo sudah membawa lingkaran hitamnya sendiri.
- Beri ruang kosong minimal seperempat diameter logo di sekelilingnya.
- Jangan diubah warnanya, diregangkan, atau dipotong lingkarannya.
