# Binaan CSR

**Community Development Portal**

Website digital masyarakat binaan untuk menampilkan informasi program, produk lokal, lokasi, community impact, sustainability program, dan galeri kegiatan.

## Struktur Menu

- Home
- Produk UMKM
- Peternakan / Perikanan / Pertanian
- UMKM Jasa
- Lokasi
- Pagu Gampong
- Community Impact
- Sustainability Program
- Galeri

## Teknologi

- HTML
- CSS
- JavaScript
- Google Apps Script API
- Google Sheets
- Vercel
- GitHub

## Data Sustainability

Dashboard Sustainability Program terhubung ke Google Apps Script API dan menggunakan data:

- Monitoring Code
- Sustain/No
- Summary Monev
- Activity
- Tahun Budget
- Deskripsi

Program dihitung berdasarkan **Monitoring Code unik** agar satu program tidak dihitung berulang.

Dashboard menampilkan:

- Total Program
- Masih Berjalan
- Mati
- Tidak Berkembang / Kurang Baik
- Belum Monitoring
- Grafik Summary Monev
- Grafik Activity
- Grafik penerima manfaat per gampong (struktur tampilan)
- Activity × Summary Monev

## Pengembangan Berikutnya

Bagian berikut disiapkan untuk dikembangkan menjadi data dinamis:

- Produk UMKM: foto, lokasi gampong, PIC, WhatsApp, stok/status tersedia-habis
- Peternakan / Perikanan / Pertanian: foto, lokasi, PIC, kontak
- UMKM Jasa: foto, lokasi, PIC, kontak
- Lokasi: koordinat, peta interaktif, Google Maps, program per titik, jumlah penerima manfaat
- Pagu Gampong: filter tahun, gampong, jenis program, pagu, realisasi
- Community Impact: kelompok, individu, laki-laki, perempuan, instansi/other
- Galeri: foto kegiatan dan deskripsi singkat

## Catatan

File `index.html` adalah halaman utama website dan dapat langsung di-upload ke repository GitHub.

Website publik tidak menampilkan data budget pada dashboard Sustainability. Data budget hanya disiapkan untuk menu **Pagu Gampong** melalui koneksi data terpisah pada tahap pengembangan berikutnya.

## Deployment

Repository GitHub dapat dihubungkan ke Vercel. Setiap perubahan pada branch utama dapat dideploy otomatis oleh Vercel.

**Website:** Binaan CSR  
**Subtitle:** Community Development Portal  
**Footer:** Digital Community Portal • Produk Lokal
