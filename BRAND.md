# Lensadigital

Lensadigital menjual produk digital berbahasa Indonesia (ebook, cheat sheet, tracker, AI mini app) untuk pembeli di Indonesia. Toko utamanya di OrderHero (`lensadigital.orderhero.id`). Gaya visualnya berasal dari logo: lensa kamera di atas latar hitam pekat, wordmark putih, dan kata "digital" dalam oranye menyala.

## Sumber

- **Logo** (`assets/Logos/lensadigital-logo.png`): semua warna di sistem ini diambil langsung dari pikselnya.
- **Landing page OrderHero** (`toko.lensadigital.my.id/page/integrated-micro-farm-sirkular`): sumber font, skala teks, spasi, radius, serta bentuk tombol dan kartu. Semuanya diukur dari CSS halaman itu.
- Palet hijau-terakota di landing page tersebut adalah palet produk (Micro Farm), bukan palet brand, jadi tidak dimasukkan ke sini. Warna brand tetap dari logo.

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
- **Bentuk membulat.** Tombol CTA memakai `radius-md` (16px), kartu `radius-lg` (20px), dan panel section/hero `radius-xl` (28px). Chip memakai `radius-pill`.
- **Tata letak LP:** konten maksimal `content-max` (1080px), section diberi padding `space-20` atas-bawah dan `space-12` samping, kartu `space-7`.
- **Tombol CTA** bisa dua baris: aksi + harga di baris atas, keterangan kecil di baris bawah. Pakai bayangan `shadow-cta`.
- **Kedalaman:** kartu unggulan memakai `shadow-glow`. Selebihnya cukup garis `surface-200`, tanpa bayangan berat.
- Hindari gradien ungu-biru dan emoji sebagai ikon. Kilau warna-warni di lensa logo hanya milik logo.

## Tipografi

Dua keluarga dari Google Fonts:
- **Manrope** (400/600/700/800) untuk hampir semua teks. Judul memakai 800 dengan spasi huruf sedikit dirapatkan. Isi memakai 400, dan frasa penting di dalam paragraf ditebalkan ke 800.
- **DM Serif Display** miring hanya untuk `accent-serif`, yaitu satu frasa sorotan di judul atau kalimat penegas, berwarna `brand-orange-text`.

Gaya yang tersedia: `display` (54px), `h2` (40px), `h3` (21px), `accent-serif`, `lead` (19px tebal), `body` (17.5px), `body-sm` (15px), `small` (13px), dan `eyebrow` (12px kapital).

## Ikonografi

Belum ada set ikon. Sementara pakai ikon garis sederhana (stroke 1,5–2px) berwarna `silver` atau `text-muted`. Ikon oranye hanya di samping tombol utama.

## Logo

- Pakai di atas latar gelap. Logo sudah membawa lingkaran hitamnya sendiri.
- Beri ruang kosong minimal seperempat diameter logo di sekelilingnya.
- Jangan diubah warnanya, diregangkan, atau dipotong lingkarannya.
