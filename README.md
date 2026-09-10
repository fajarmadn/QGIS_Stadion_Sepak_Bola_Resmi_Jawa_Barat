# Peta Sebaran Stadion Sepak Bola Resmi Provinsi Jawa Barat
Praktikum Sistem Informasi Geografis (SIG) - Pertemuan 3

Repositori ini memuat data spasial, proyek QGIS, dan WebGIS interaktif pemetaan sebaran 40 stadion sepak bola resmi di seluruh wilayah Provinsi Jawa Barat.

## 🌐 Akses WebGIS Online
WebGIS interaktif dapat langsung diakses secara publik melalui tautan GitHub Pages berikut:  
👉 **[https://fajarmadn.github.io/QGIS_Stadion_Sepak_Bola_Resmi_Jawa_Barat/](https://fajarmadn.github.io/QGIS_Stadion_Sepak_Bola_Resmi_Jawa_Barat/)**

## 📂 Struktur Berkas & Repositori
- `index.html` : Berkas antarmuka WebGIS interaktif berbasis Leaflet JS.
- `data/` :
  - `batas_jawa_barat.js` : Data vektor GeoJSON poligon batas wilayah Provinsi Jawa Barat (~104 KB).
  - `stadion.js` : Data vektor GeoJSON 40 titik stadion sepak bola resmi Jawa Barat (~7.5 KB).
- `stadion_sepak_bola_jawa_barat.csv` : Dataset koordinat (Latitude, Longitude) dan nama 40 stadion sepak bola resmi di Jawa Barat.
- `Batas_Provinsi_Jawa_Barat.*` : Shapefile (SHP, DBF, PRJ, SHX, CPG) batas administrasi Provinsi Jawa Barat.
- `Tugaspertemuan3.qgz` : Berkas proyek peta QGIS 3.44.
- `.gitignore` : Konfigurasi pengabaian file berukuran besar (`.mbtiles` dan folder tile raster lokal).

## 💡 Fitur WebGIS
- **Clean & Responsive Map**: Peta tampil penuh (fullscreen) di peramban web desktop maupun smartphone.
- **Dynamic Basemap**: Peta dasar OpenStreetMap yang termuat secara mulus melalui CDN.
- **Interactive Tooltip & Pop-up**:
  - *Hover* pada titik stadion untuk melihat nama stadion.
  - *Klik* pada titik stadion untuk memunculkan jendela informasi nama stadion dan koordinat (Latitude, Longitude).
- **Auto-Fit Bounds**: Kamera peta secara otomatis menyesuaikan batas wilayah Provinsi Jawa Barat saat pertama kali dibuka.
