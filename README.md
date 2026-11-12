# Deep Learning Projects: Image Classification (CNN) & Time-Series Forecasting (LSTM)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-CNN%20%7C%20LSTM-orange)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)

Repository ini berisi implementasi arsitektur *Deep Learning* untuk menyelesaikan dua studi kasus berbeda: **klasifikasi citra penyakit daun padi** menggunakan *Convolutional Neural Network* (CNN) dan **prediksi curah hujan harian** menggunakan *Long Short-Term Memory* (LSTM). Proyek ini disusun sebagai bagian dari evaluasi Tugas Tengah Semester (TTS) mata kuliah Deep Learning.

---

## Ringkasan Proyek

### 1. Klasifikasi Penyakit Daun Padi (CNN)
* **File Kode:** `672024170_TTS_soal1_CNN.ipynb`
* **Dataset:** *Rice Leaf Disease Extensive Image Dataset*
* **Tujuan:** Membangun model klasifikasi citra berbasis *Convolutional Neural Network* (CNN) untuk mendeteksi dan mengklasifikasikan jenis penyakit pada daun padi secara otomatis.
* **Tahapan Utama:** Preprocessing citra (*resizing*, normalisasi, augmentasi data), perancangan arsitektur layer konvolusi & *pooling*, pelatihan model, serta evaluasi performa menggunakan *accuracy* dan *confusion matrix*.

### 2. Prediksi Curah Hujan Harian (LSTM)
* **File Kode:** `672024170_TTS_soal2_LSTM.ipynb`
* **Dataset:** *Daily Rainfall Observations from 460 Stations*
* **Tujuan:** Memodelkan data deret waktu (*time-series*) meteorologi untuk memprediksi curah hujan harian menggunakan jaringan saraf berulang *Long Short-Term Memory* (LSTM).
* **Tahapan Utama:** Pembersihan data (*handling missing values*), normalisasi fitur, pembentukan *sequence/windowing* data deret waktu, pelatihan arsitektur LSTM, dan evaluasi prediksi.

## Sumber Dataset
Dataset yang digunakan dalam proyek ini bersumber dari repositori terbuka **Mendeley Data** (tidak disertakan langsung di dalam repository GitHub karena ukuran file melebihi batas unggah maksimal 100 MB):

* **Dataset Soal 1 (CNN — Rice Leaf Disease):** [Rice Leaf Disease](https://data.mendeley.com/datasets/t46kkgh2yw/1)
* **Dataset Soal 2 (LSTM — Daily Rainfall Observations):** [Daily Rainfall Observations](https://data.mendeley.com/datasets/d7j3s64vvr/3) 

---

## Struktur Repository

```text
CNN-LSTM-Deep-Learning-Projects/
├── 672024170_TTS_soal1_CNN.ipynb              # Notebook eksperimen & pelatihan model CNN
├── 672024170_TTS_soal2_LSTM.ipynb             # Notebook eksperimen & pelatihan model LSTM
├── Laporan_TTS_672024170_Deep Learning.pdf    # Laporan lengkap metodologi, analisis, & hasil evaluasi
└── README.md                                  # Dokumentasi proyek
