# Peta Sebaran Stadion Sepak Bola Resmi Provinsi Jawa Barat
Praktikum Sistem Informasi Geografis (SIG) - Pertemuan 3

WebGIS interaktif pemetaan sebaran 40 stadion sepak bola resmi di seluruh wilayah Provinsi Jawa Barat yang di-render langsung dari proyek peta QGIS menggunakan MapTiler Cloud CDN dan Leaflet JS.

## 🌐 Akses WebGIS Online
WebGIS interaktif dapat langsung diakses secara publik melalui tautan GitHub Pages berikut:  
👉 **[https://fajarmadn.github.io/QGIS_Stadion_Sepak_Bola_Resmi_Jawa_Barat/](https://fajarmadn.github.io/QGIS_Stadion_Sepak_Bola_Resmi_Jawa_Barat/)**

## 📂 Berkas Repositori
- `index.html` : Antarmuka WebGIS Leaflet interaktif yang mengonsumsi raster tile MBTiles melalui MapTiler Cloud CDN.
- `README.md` : Dokumentasi repositori dan tautan akses WebGIS.
- `.gitignore` : Konfigurasi pengabaian berkas lokal.

## 💡 Fitur Peta
- **Tampilan Penuh (Fullscreen)**: Tampilan peta bersih dan responsif di peramban web desktop maupun smartphone.
- **Rendering Asli QGIS**: Menampilkan gaya visual asli (simbol bintang ledakan kuning, garis batas merah Jawa Barat, dan label kotak hitam teks putih).
- **Penguncian Wilayah (maxBounds)**: Area jelajah terkunci kaku di sekeliling wilayah Provinsi Jawa Barat.
