# 📝 Simple Blog Manager 
  
 Aplikasi blog sederhana berbasis **localStorage** – ringan, cepat, dan offline-friendly.   
 Tulis, edit, dan hapus postingan tanpa database. Semua data tersimpan di browser Anda. 
  
 ## ✨ Fitur 
  
 - ➕ Buat postingan baru (judul + konten) 
 - ✏️ Edit postingan yang sudah ada 
 - 👁️ Lihat detail postingan dalam modal 
 - 🗑️ Hapus postingan dengan konfirmasi 
 - 💾 Penyimpanan otomatis ke `localStorage` 
 - 📱 Desain responsif (mobile friendly) 
 - 🎨 UI modern dengan Font Awesome & Google Fonts 
 - 📊 Menampilkan jumlah postingan & timestamp 
  
 ## 🛠 Teknologi 
  
 - HTML5, CSS3, JavaScript (ES6) 
 - Font Awesome 6 
 - Google Fonts – Inter 
 - LocalStorage API 
  
 ## 📂 Struktur Proyek 
 simple-blog/ 
 ├── index.html # Aplikasi utama (satu file) 
 └── README.md   # Dokumentasi 
  
 ## 🚀 Cara Menjalankan Lokal 
  
 ### 1. Buka langsung di browser 
 - Download file `index.html` 
 - Klik dua kali atau buka dengan browser modern (Chrome, Firefox, Edge) 
  
 ### 2. Gunakan Live Server (disarankan) 
 ```bash 
 npx live-server 
 ```
 atau 
 ```bash 
 python -m http.server 8000 
 ```
 Lalu buka http://localhost:8000 
  
 Data tersimpan di localStorage – tetap ada meski browser ditutup (kecuali dibersihkan). 
  
 🌐 Deployment (GitHub Pages) 
  
 Karena aplikasi ini menggunakan `index.html` sebagai file utama, Anda dapat dengan mudah melakukan deployment ke GitHub Pages tanpa konfigurasi tambahan. 
  
 ### GitHub Pages: 
 1. Push repositori Anda ke GitHub. 
 2. Buka **Settings** > **Pages**. 
 3. Pilih branch `main` (atau `master`) dan folder `/ (root)`. 
 4. Klik **Save**. 
  
  
 📝 Catatan Penting 
 Data hanya disimpan di browser – jika pengguna membersihkan cache/localStorage, data akan hilang. 
  
 Tidak ada fitur ekspor/impor (bisa ditambahkan mandiri). 
  
 Aplikasi tidak memerlukan koneksi internet setelah halaman dimuat (kecuali untuk ikon Font Awesome dan Google Fonts). 
  
 Untuk penggunaan banyak pengguna, pertimbangkan mengganti localStorage dengan backend database. 
  

  
 📄 Lisensi 
 MIT – bebas digunakan, dimodifikasi, dan didistribusikan. 
  
 Dibuat dengan ☕ dan semangat berbagi. 
