# Binaan CSR

**Community Development Portal**

## Update

Versi ini menambahkan data dinamis untuk:

- Produk UMKM
- UMKM Jasa
- Peternakan / Perikanan / Pertanian

Ketiga menu menggunakan **1 sumber Sheet `web_produk`** dan dibedakan berdasarkan nilai pada kolom **A — Tampil Web**:

- `Produk UMKM`
- `Produk Jasa`
- `Peternakan / Perikanan / Pertanian`

Baris dengan nilai lain pada kolom A tidak ditampilkan pada ketiga menu tersebut.

## Kartu Produk

Kartu menampilkan:

1. Foto
2. Nama Usaha
3. Jenis Produk
4. Gampong
5. Nama Pemilik
6. Stok
7. Keterangan
8. Hubungi via WhatsApp
9. Lokasi (koordinat)
10. Status

Foto menggunakan field **`Foto URL`** dari Apps Script `Web_produk`.

Kontak otomatis menggunakan link WhatsApp yang dibuat oleh Apps Script dari kolom Kontak.

## API

### Web Produk

`https://script.google.com/macros/s/AKfycby9Z4BVbERlJ13p8J_GvbakhuvhAJbxEebTTJC90BoPXnPOkizeKXsEjzuZOJZfX-QT/exec`

### Community Impact

Menggunakan deployment **Web_community_impact**:

`https://script.google.com/macros/s/AKfycbx57qGADZO1EMsINBUnMYiqvjRzKUHOd8X1Nsn3YCEyiiZ5Ruy27R7jubGu7_baSt-q/exec`

Kolom spreadsheet `Jenis Bantuan/Ternak/Budidaya/Produk` tetap digunakan sebagai sumber, tetapi tampilan website menggunakan nama pendek **Jenis Bantuan**.

NIK tidak ditampilkan.

### Sustainability / Lokasi

Bagian Sustainability dan Lokasi dipertahankan dari versi sebelumnya.

## Deployment

Upload `index.html` ke repository GitHub yang terhubung ke Vercel.


## Lokasi pada Kartu Produk

Kolom **Lokasi** pada `web_produk` digunakan sebagai koordinat `latitude, longitude`.

Contoh:
`4.135163, 96.168977`

Jika koordinat valid, kartu menyediakan dua tombol:
- 📍 Google Maps
- 🌍 Google Earth

Tombol dibuka di tab baru. Jika Lokasi kosong/tidak valid, koordinat tetap ditampilkan sebagai `-` dan tombol lokasi tidak dibuat.
