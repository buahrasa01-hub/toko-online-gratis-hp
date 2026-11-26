# Toko Online Gratis dari HP

Template toko online statis gratis — cukup HP, tanpa laptop, tanpa modal.
Buka `index.html` di browser, ganti isi `products.json` dengan produk kalian,
dan toko kalian langsung bisa dibagikan lewat tautan.

Dibuat untuk tutorial YouTube channel **Bu Ah (@buah2891)**:
**"Bikin Toko Online Gratis dari HP"** (slot 27 Nov 2026, 01:00 WIB).
Video: https://youtu.be/DbR_gbfYsSQ

## Yang ada di repo ini

| File | Isi |
| --- | --- |
| `index.html` | Halaman toko: memuat `products.json`, menampilkan kartu produk + tombol **Pesan via WhatsApp** di tiap produk. |
| `products.json` | Data toko: nama toko, nomor WhatsApp, dan 6 produk contoh (nama, harga, deskripsi, stok, foto). |
| `PANDUAN.md` | Panduan langkah demi langkah: dari produk pertama sampai toko beneran. |
| `LICENSE` | MIT — bebas dipakai, diubah, dan dibagikan. |

## Cara pakai (5 menit, dari HP)

1. Unduh repo ini (tombol **Code → Download ZIP** di GitHub, atau `git clone`
   dari HP dengan aplikasi Git).
2. Buka `products.json`, ganti `store.name` dengan nama toko kalian,
   `store.whatsapp` dengan nomor WhatsApp kalian (format internasional tanpa
   `+`, misal `6281234567890`), lalu ganti 6 produk contoh dengan produk
   kalian sendiri (nama, harga, deskripsi, stok).
3. Ganti foto: isi `image` dengan tautan foto produk kalian, atau simpan foto
   di folder yang sama dan tulis nama filenya (misal `foto-keripik.jpg`).
   Foto contoh di repo ini memakai gambar acak dari `picsum.photos` —
   **wajib diganti** dengan foto produk kalian sendiri.
4. Buka `index.html` di browser HP. Kalau produk tampil, toko kalian jadi.
5. Sebarkan: hosting gratis (GitHub Pages, lihat `PANDUAN.md` bab 6), atau
   kirim file ini lewat tautan, atau cukup bagikan tautan katalog
   WhatsApp Business kalian.

## Yang sudah terverifikasi vs yang belum

Jujur, supaya tidak ada yang salah paham:

- ✅ **Template sudah dirender dan diperiksa**: `index.html` + `products.json`
  dibuka lewat server lokal dan di-render di browser headless — keenam produk
  contoh tampil lengkap dengan nama, harga, stok, dan tombol WhatsApp yang
  mengarah ke `wa.me/<nomor>` dengan pesan pesanan yang sudah terisi.
  Bukti: tangkapan layar render tersimpan di repo video (bukan di repo ini).
- ✅ **JSON valid**: `products.json` lolos pemeriksaan JSON.
- ⚠️ **Belum diuji deploy ke GitHub Pages**: langkahnya ditulis di `PANDUAN.md`
  mengikuti dokumentasi GitHub Pages, tapi belum dijalankan untuk repo ini.
- ⚠️ **Belum diuji order sungguhan lewat WhatsApp**: tombolnya mengarah ke
  tautan `wa.me` yang benar, tapi belum ada pesanan sungguhan yang masuk
  lewat tombol ini.
- ⚠️ **Angka biaya marketplace dan QRIS di video** dicek dari panduan resmi
  penjual (Pusat Edukasi Penjual Shopee, panduan penjual Tokopedia) dan
  halaman resmi Bank Indonesia (MDR QRIS) pada 26 Nov 2026 — tapi angka itu
  bisa berubah. **Cek lagi di aplikasi** sebelum menentukan harga jual.

Kalau ada yang tidak jalan saat kalian pakai, buka **Issue** di repo ini
dan ceritakan langkah yang kalian lakukan + apa yang tampil di layar.

## Toko ini gratis — tapi tidak semua hal gratis

Bedakan dengan tegas:

- **Gratis**: membuka toko di Shopee/Tokopedia, aplikasi WhatsApp Business
  + katalog, template toko ini, hosting GitHub Pages untuk situs statis.
- **Berbayar (potongan per penjualan)**: biaya admin marketplace per pesanan
  selesai (Shopee Non-Star ±2,5–10% + Rp1.250/pesanan; Tokopedia ±0,5–2,5%
  per produk terjual — besarannya tergantung kategori dan bisa berubah,
  cek di aplikasi). Program bebas biaya admin Shopee untuk penjual baru
  sudah berakhir 31 Juli 2026.
- **Berbayar (lainnya)**: domain sendiri, iklan marketplace, dan WhatsApp
  Business API untuk perusahaan besar. Ketiganya **tidak dibutuhkan**
  untuk toko pemula.

## Repo terkait (channel Bu Ah)

- Panduan drama AI: https://github.com/buahrasa01-hub/drama-ai-pipeline
- Game Cloud Rider: https://github.com/buahrasa01-hub/cloud9-booth-game

Kalau repo ini membantu, beri ⭐ — gratis, dan itu cara paling gampang
mendukung proyek gratis supaya ditemukan orang lain.
