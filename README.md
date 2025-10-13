# Electricity Load Forecasting with Hybird Singular Spectrum Analysis - Deep Learning

Repository ini berisi kode dan dokumentasi skripsi **forecasting beban listrik harian** di Provinsi Jawa Tengah dan Daerah Istimewa Yogyakarta menggunakan **LSTM, BiLSTM, GRU, dan versi SSA (Singular Spectrum Analysis) dari masing-masing model**. Proyek ini bertujuan untuk mengevaluasi performa tiap model dalam memprediksi beban listrik dan menentukan model terbaik.

---

## 📂 Struktur Repository

```
Hybrid_SSA_Deep_Learning/
│
├── data/
│ ├── raw/              # Data mentah (2016-2020)
│ └── processed/        # Data yang sudah dibersihkan & di-scaling
│
├── notebooks/          # Notebook eksperimen & visualisasi
│
├── hasil/              # Hasil prediksi, plot, dan metric
│
├── requirements.txt    # Dependencies
└── thesis.pdf          # Skripsi final
```

---

## 📝 Data
- Dataset berisi data beban listrik per jam 2016-2020 dari PLN Unit Induk Distribusi Jateng dan DIY.
- Format data CSV:

```
Tanggal, 0:30, 1:00, 1:30, ..., 23:00
YYYY-MM-DD, MW, MW, MW, ..., Mw
```

> ⚠️ **Catatan:**  
> Data ini bersifat **rahasia** dan hanya menampilkan beberapa baris sebagai contoh.  
> Untuk memperoleh akses penuh terhadap dataset, silakan menghubungi penulis:  
> **Sabrina Aziz Aulia** — 📧 *saazizau@gmail.com*
---

## 📊 Notebook Eksperimen
1. `1_preprocessing_data.ipynb`
2. `2_exploratory_data_analysis.ipynb`
4. `3_singular_spectrum_analysis.ipynb`
3. `4_modeling_deep_learning.ipynb`
5. `5_modelling_hybrid_ssa_deep_learning.ipynb`
6. `6_evaluate_models.ipynb`
7. `7_forecasting.ipynb`

---

## 📈 Hasil & Evaluasi
- Semua hasil prediksi, grafik, dan metrik evaluasi disimpan di folder `hasil/`.

---

## ✨ Catatan
Repository ini dirancang untuk reproducibility, sehingga seluruh notebook dan script bisa dijalankan ulang untuk eksperimen tambahan atau validasi hasil.

