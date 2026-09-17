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

Dashboard Sustainability Program tetap menggunakan koneksi dan struktur yang ada pada file HTML ini. Tidak ada perubahan pada logika dashboard Sustainability.

Dashboard menampilkan:

- Total Program
- Masih Berjalan
- Mati
- Tidak Berkembang / Kurang Baik
- Belum Monitoring
- Grafik Summary Monev
- Grafik Activity
- Grafik penerima manfaat per gampong
- Activity × Summary Monev

## Lokasi

Bagian Lokasi tetap menggunakan data `Web_binaan`, kolom `Koordinat Sustain`, dan popup informasi program yang sudah ada. Perubahan pada versi ini hanya pada bentuk titik lokasi di peta:

- 🟢 Masih Berjalan
- 🔴 Mati
- 🟠 Tidak Berkembang/Kurang Baik
- ⚪ Belum Monitoring atau status kosong

Marker dibuat sebagai **titik lokasi kecil (circle marker)**, bukan pin. Klik titik tetap membuka informasi program, koordinat, Google Maps, dan Google Earth seperti sebelumnya.

## Catatan

- Layout dan fungsi Sustainability Program tidak diubah.
- Struktur dan fungsi Lokasi lainnya tidak diubah; hanya tampilan marker lokasi yang dibuat menjadi titik berwarna berdasarkan Summary Monev.
- Data budget tidak digunakan pada dashboard Sustainability.

## Deployment

Repository GitHub dapat dihubungkan ke Vercel. Setiap perubahan pada branch utama dapat dideploy otomatis oleh Vercel.

**Website:** Binaan CSR  
**Subtitle:** Community Development Portal  
**Footer:** Digital Community Portal • Produk Lokal
