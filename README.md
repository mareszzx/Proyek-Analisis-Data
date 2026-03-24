# E-Commerce Data Analysis Project

## Project Overview
Proyek ini merupakan bagian dari submission akhir kelas "Analisis Data dengan Python" di Dicoding. Proyek ini melakukan analisis mendalam pada E-Commerce Public Dataset untuk menggali insight mengenai performa kategori produk, distribusi pendapatan geografis, serta pemetaan demografi pelanggan di wilayah Brazil.

## Fitur Utama Dashboard
- Product Performance: Visualisasi kategori produk dengan pendapatan tertinggi dan terendah.
- Geospatial Revenue: Analisis total nilai transaksi berdasarkan negara bagian (states).
- Customer Distribution: Pemetaan lokasi pelanggan di seluruh wilayah Brazil.
- Customer Segmentation: Pengelompokan pelanggan berdasarkan nilai pengeluaran (Low, Medium, High Spend).

## Persiapan Environment
Instruksi ini akan membantu Anda menjalankan dashboard secara lokal di komputer Anda.

1. Clone Repositori
```bash
git clone https://github.com/username-anda/proyek-analisis-data.git
cd proyek-analisis-data
```
2. Membuat Virtual Environment (Disarankan)
Sangat disarankan untuk menggunakan virtual environment agar tidak terjadi konflik library dengan proyek lain.

Windows:
```bash
python -m venv venv
venv\Scripts\activate
```
3. Instalasi Library
Pastikan Anda berada di direktori utama proyek, lalu jalankan perintah berikut untuk menginstal semua dependensi yang dibutuhkan:
```bash
pip install -r requirements.txt
```

## Menjalankan Dashboard Streamlit
### Masuk ke direktori proyek (folder dashboard), lalu jalankan perintah berikut:

```bash
streamlit run dashboard/dashboard.py
```

## Struktur Proyek
.
├── dashboard/
│   ├── dashboard.py       # Script utama Dashboard Streamlit
│   └── main_data.zip      # Dataset yang telah dibersihkan (dikompres)
├── data/
│   ├── (raw_data).csv     # Kumpulan berkas CSV asli dari sumber
├── notebook.ipynb         # Alur analisis data lengkap (Wrangling - Viz)
├── README.md              # Dokumentasi proyek
├── requirements.txt       # Daftar library python yang dibutuhkan
└── url.txt                # Tautan dashboard yang sudah di-deploy
