# 🚧 Sistem Informasi dan Analisis Kondisi Jalan di Kalimantan Timur

Proyek ini merupakan inisiatif berbasis data yang bertujuan untuk mendukung Dinas PUPR Provinsi Kalimantan Timur dalam memantau dan menangani kondisi jalan. Kami menganalisis dataset kondisi jalan eksisting dan membangun sebuah website pengaduan untuk melibatkan partisipasi masyarakat dalam pelaporan jalan rusak secara real-time.

---

## 📌 Latar Belakang

Kalimantan Timur memiliki jaringan jalan yang sangat luas dan berperan penting dalam mobilitas ekonomi, sosial, dan logistik. Namun, pemantauan kondisi jalan secara menyeluruh masih menjadi tantangan, terutama di wilayah pelosok.

Melalui proyek ini, kami:

- Menganalisis dataset kondisi jalan berdasarkan klasifikasi kerusakan dan panjang ruas.
- Mengelompokkan kondisi jalan menggunakan metode **Clustering** seperti `K-Means` dan `DBSCAN`.
- Mengembangkan website pelaporan berbasis web yang dapat digunakan masyarakat luas.

---

## 🧑‍💻 Tim Pengembang

| Nama              | Peran             |
|-------------------|------------------|
| Muhammad Daffa Ezra Putra         | Project Manager  |
| Fatur & Tim       | Data Analyst     |
| [Nama Frontend]   | Frontend Dev     |
| [Nama Backend]    | Backend Dev      |


---

## 📊 Modul Proyek

### 1. `data-analysis/`
> Folder ini berisi seluruh proses analisis data kondisi jalan:
- `dataset_kondisi_jalan.csv` – Dataset mentah dari Dinas PUPR
- `preprocessing.ipynb` – Pembersihan dan visualisasi data
- `clustering_model.ipynb` – Model KMeans & DBSCAN untuk klasifikasi kerusakan
- `road_priority.xlsx` – Output prioritas ruas jalan berdasarkan tingkat kerusakan dan panjang ruas

### 2. `frontend-app/`
> Aplikasi antarmuka berbasis web:
- Menampilkan peta kondisi jalan
- Form pengaduan kerusakan
- Peta interaktif & visualisasi

### 3. `backend-api/`
> API server untuk komunikasi data:
- Menyimpan pengaduan pengguna
- Mengelola data kondisi jalan
- Integrasi database & auth

### 4. `project-docs/`
> Dokumen pendukung:
- Proposal proyek
- Progress dan timeline
- Hasil evaluasi dan laporan akhir

---

## 🌐 Fitur Website

- 🗺️ **Peta Jalan Interaktif** – Visualisasi jalan rusak berdasarkan kategori
- 📝 **Formulir Pengaduan** – Masyarakat bisa melapor jalan rusak dengan foto dan lokasi
- 📈 **Dashboard Admin** – Khusus PUPR untuk memantau dan menindaklanjuti laporan
- 📂 **Riwayat Pengaduan** – Tersimpan dan bisa ditinjau kapan saja

---

## 🧠 Teknologi yang Digunakan

| Komponen     | Teknologi                |
|--------------|---------------------------|
| Frontend     | HTML, CSS, JS, Leaflet.js |
| Backend      | PHP / Node.js, MySQL      |
| Data Science | Python, Pandas, Scikit-Learn, Matplotlib |
| Deployment   | GitHub, Vercel/Netlify, Hosting Lokal |

---

## 📈 Contoh Output Analisis

- Cluster: Jalan dalam kondisi **baik**, **rusak ringan**, **rusak berat**
- Visualisasi: Heatmap & Peta Klaster Kerusakan
- Skor Prioritas: Kombinasi panjang ruas dan klasifikasi kerusakan

---

## ✅ Status Proyek

- [x] Desain UI/UX
- [x] Pengumpulan dataset
- [x] Analisis clustering kondisi jalan
- [ ] Integrasi website pelaporan ke database
- [ ] Deployment final & dokumentasi

---

> _"Data jalan bukan hanya angka. Ia adalah suara dari lapisan aspal yang menopang aktivitas masyarakat."_  
