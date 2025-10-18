# AutoForm Demo — Situs Mock Entri Data

Website statis sederhana untuk mendemonstrasikan bagaimana cara **mengotomatisasi input form dari file Excel/CSV** ke sebuah website. Dirancang untuk tutorial, demo otomasi, atau proyek RPA (Robotic Process Automation). Dapat langsung di-host di **GitHub Pages** tanpa backend.

---

## 🌐 Demo Langsung
Setelah di-deploy ke GitHub Pages:
```
https://auliaardan.github.io/website-auto-mockup
```

---

## 🚀 Fitur Utama
- **Tiga contoh form:** Pasien, Inventori, Kontak.
- **Penyimpanan lokal:** Semua data disimpan di LocalStorage browser.
- **Import CSV/XLSX:** Unggah data massal langsung dari Excel.
- **Export CSV:** Unduh data tersimpan per tab atau semua tab sekaligus.
- **Template CSV:** Unduh contoh header CSV siap pakai.
- **Fungsi Hapus / Reset / Bersihkan.**
- **Sepenuhnya statis:** Berfungsi offline, tanpa database atau server.

---

## 📂 Struktur Folder
```
📁 autoform-demo/
├── index.html   ← file utama aplikasi
└── README.md    ← file panduan ini
```

---

## 🛠️ Cara Menjalankan Secara Lokal
1. **Kloning atau unduh** repository ini.
   ```bash
   git clone https://github.com/auliaardan/website-auto-mockup.git
   ```
2. Buka file `index.html` di browser Anda.
3. Website langsung berfungsi — data yang dimasukkan akan tersimpan di LocalStorage.

---

## 🧠 Cara Hosting di GitHub Pages
1. Upload repo ini ke GitHub.
2. Buka menu **Settings → Pages** di repo Anda.
3. Di bagian “Source,” pilih branch `main` dan folder `/ (root)`.
4. Simpan. Tunggu beberapa detik, lalu buka URL yang diberikan.

Website Anda siap digunakan!

---

## 📊 Contoh Penggunaan untuk Demo Otomasi
Website ini ideal untuk menunjukkan:
- Bagaimana Python + Selenium / Playwright mengisi form otomatis.
- Cara membaca data Excel menggunakan pandas atau openpyxl.
- Proses pengulangan data otomatis ke form web seperti manusia.

---

## 📦 Dependensi (via CDN)
- [Bootstrap 5](https://getbootstrap.com/): Tampilan UI.
- [SheetJS (xlsx)](https://github.com/SheetJS/sheetjs): Parsing file CSV/XLSX.

Tidak perlu instalasi tambahan atau npm — hanya satu file HTML.

---

## 🧹 Menghapus Data
Untuk menghapus semua data tersimpan (dari LocalStorage):
- Klik **Clear All** di antarmuka, atau
- Jalankan di konsol browser:
  ```js
  localStorage.clear();
  ```

---

## 💡 Tips untuk Konten Sosial Media atau Video Demo
- Rekam layar Anda saat menunjukkan proses: Excel → script otomasi → website terisi otomatis.
- Tunjukkan bagaimana data muncul di tabel “Saved Data”.
- Sebutkan bahwa website ini **tanpa backend, hanya LocalStorage + JavaScript + GitHub Pages**.

---

## 🧑‍💻 Pembuat
Dibuat oleh **Aulia Rahman Ardan** — untuk keperluan demo edukatif dan otomasi data.

---

## 📜 Lisensi
Lisensi MIT — bebas digunakan untuk tujuan pribadi atau edukasi.


*OpenAI CHATGPT was used for the code of this mockup website
