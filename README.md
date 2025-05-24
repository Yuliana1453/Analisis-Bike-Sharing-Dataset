# 🚲 Analisis Bike Sharing Dataset

Repositori ini berisi notebook analisis data dari dataset **Bike Sharing** yang diambil dari Kaggle. Tujuan dari proyek ini adalah melakukan eksplorasi dan analisis terhadap data peminjaman sepeda berdasarkan waktu (harian dan per jam), serta melihat faktor-faktor yang mempengaruhi jumlah peminjaman.

---

## 📦 Dataset

Dataset diperoleh dari Kaggle:  
🔗 [Bike Sharing Dataset – Kaggle](https://www.kaggle.com/datasets/lakshith25pathi/bike-sharing-dataset)

**Catatan:** File `day.csv` dan `hour.csv` telah disertakan langsung dalam repositori ini untuk memudahkan pengguna menjalankan notebook tanpa perlu mengunduh data secara terpisah.

---

## 🛠️ Tools yang Digunakan

- Google Colab
- Python 3
- Pandas
- Matplotlib / Seaborn (jika digunakan untuk visualisasi)

---

## 🗂️ Struktur Folder

Analisis-Bike-Sharing-Dataset/

├── Dataset

    └── day.csv
  
    └── hour.csv
  
├── Proyek_Analisis_Data.ipynb

├── requirements.txt

├── Bike_Dashboard.py

└── README.md

---


- `day.csv`: Data peminjaman sepeda harian
- `hour.csv`: Data peminjaman sepeda per jam

---

## 📊 Fitur Dashboard

Dashboard dibangun menggunakan **Streamlit** dan memiliki fitur:

- Pilihan antara data harian dan data per jam
- Filter rentang tanggal, musim, dan cuaca
- Visualisasi interaktif:

  1. **📈 Tren Jumlah Penyewa Sepeda**  
     Menampilkan total penyewa dari waktu ke waktu.
     
  2. **📊 Distribusi Penyewa Sepeda**  
     Histogram dengan kurva KDE untuk melihat sebaran jumlah penyewa.
     
  3. **🕐 Distribusi berdasarkan Musim**  
     Boxplot yang membandingkan jumlah penyewa antar musim.

---

## ▶️ Menjalankan Aplikasi

### 1. Clone repositori:

```bash
git clone https://github.com/Yuliana1453/Analisis-Bike-Sharing-Dataset.git
cd Analisis-Bike-Sharing-Dataset
---

## 📊 Output

Notebook ini mencakup:
- Pemuatan dan pemeriksaan awal dataset
- Proses data wrangling
- Analisis statistik sederhana
- Visualisasi tren peminjaman sepeda

---

## 🧑‍💻 Kontributor

- [Yuliana1453](https://github.com/Yuliana1453)

---

## ⚠️ Lisensi

Dataset mengikuti lisensi yang disediakan oleh pemilik aslinya di Kaggle. Silakan cek halaman dataset untuk informasi lebih lanjut.

