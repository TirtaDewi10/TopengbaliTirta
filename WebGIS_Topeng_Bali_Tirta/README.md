# WebGIS Persebaran Topeng Tradisional Bali
Sistem Informasi Geografis berbasis Web ini dirancang khusus untuk draf Skripsi **Luh Made Tirta Dewi (NIM. 2201010085)** - Program Studi Informatika, Fakultas Teknologi dan Informatika, **INSTIKI**, Bali.

## 🌟 Fitur Utama Sistem:
1. **Interactive Map (Leaflet.js):** Peta interaktif dengan pembagian koordinat presisi berdasarkan buku *'Mask of Bali Vol. II'*.
2. **Layer Switcher (QGIS Style):** Bisa berganti tampilan antara peta jalan biasa (OpenStreetMap) dan visualisasi Satelit Bumi (Esri Satellite Layer).
3. **Marker Clustering Engine:** Mengelompokkan titik-titik koordinat topeng yang berdekatan agar visualisasi rapi dan responsif (bebas lag meskipun memuat 300 data sekaligus).
4. **Interactive Sidebar List:** Daftar komplit koleksi topeng di sebelah kanan yang terhubung langsung dengan pin di peta saat diklik.
5. **Real-time Live Filter:** Kolom pencarian responsif untuk mencari data topeng berdasarkan nama karakter atau instansi penyimpan/lokasi asalnya secara langsung.

## 📂 Cara Deploy / Hosting ke GitHub Pages:
1. Buat sebuah Repositori baru di akun GitHub Anda dengan nama (contoh): `webgis-topeng-bali`.
2. Unggah file `index.html` ini ke dalam repositori tersebut.
3. Jika Anda memiliki folder foto peninggalan/arsip topeng, buat folder bernama `images` di dalam repositori tersebut lalu masukkan semua file foto (`TP001.jpg`, `TP002.jpg`, dst.). Jika foto belum siap, sistem otomatis menampilkan *placeholder* gambar kosong yang informatif.
4. Buka menu **Settings** pada Repositori GitHub Anda.
5. Geser ke menu **Pages** di bilah menu samping kiri.
6. Pada bagian **Build and deployment**, ubah Source menjadi `Deploy from a branch`.
7. Di bagian Branch, pilih `main` (atau `master`) dan folder `/ (root)`, lalu klik **Save**.
8. Tunggu waktu pemrosesan sekitar 1-2 menit. URL website WebGIS Skripsi Anda akan muncul di bagian atas halaman tersebut (misal: `https://username-anda.github.io/webgis-topeng-bali/`).

*Aplikasi ini siap diujikan di hadapan dosen pembimbing dan penguji Seminar Skripsi.*
