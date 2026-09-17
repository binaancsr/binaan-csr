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

## Lokasi

Peta Lokasi menggunakan data koordinat dari `Web_binaan` dan menampilkan titik program berdasarkan `Koordinat Sustain`.

Warna titik dibedakan berdasarkan `Summary Monev`:

- Masih Berjalan
- Mati
- Tidak Berkembang/Kurang Baik
- Belum Monitoring

Legend ditempatkan di dalam area peta agar tidak menutupi toolbar peta.

## Sustainability Program

Dashboard Sustainability terhubung ke Google Apps Script API dan menggunakan data monitoring program.

## Community Impact

Community Impact terhubung ke tab `penerima_manfaat` dan menampilkan data penerima manfaat. NIK tidak ditampilkan pada website publik.

Fitur Community Impact:
- Search Nama Penerima/Kelompok
- Filter Gampong
- KPI Kelompok
- KPI Individu
- KPI Laki-laki
- KPI Perempuan
- KPI Other
- Tabel Jenis Bantuan

## Catatan

File `index.html` adalah halaman utama website dan dapat langsung di-upload ke repository GitHub.

Website publik tidak menampilkan data budget pada dashboard Sustainability. Data budget disiapkan untuk menu Pagu Gampong melalui koneksi data terpisah.

## Deployment

Repository GitHub dapat dihubungkan ke Vercel. Perubahan pada branch utama dapat dideploy otomatis oleh Vercel.

**Website:** Binaan CSR  
**Subtitle:** Community Development Portal  
**Footer:** Digital Community Portal • Produk Lokal
