# Sentiment Analysis Dana Platform

## 📊 Deskripsi

**Sentiment Analysis Dana Platform** adalah proyek analisis sentimen berbasis _machine learning_ yang berfokus pada ulasan, komentar, atau data sosial seputar aplikasi/platform Dana (e-wallet Indonesia). Proyek ini dibangun menggunakan _Jupyter Notebook_ dan memanfaatkan berbagai pustaka _data science_ serta _machine learning_ untuk melakukan ekstraksi, preprocessing, pemodelan, dan visualisasi sentimen.

## 🚀 Fitur Utama

- **Ekstraksi Data**: Pengambilan data review/komentar dari berbagai sumber (misal Google Play, media sosial, dsb).
- **Preprocessing Teks**: Pembersihan data review seperti lowercase, menghapus tanda baca, filtering stopwords, stemming, dsb.
- **Analisis Sentimen**: Klasifikasi sentimen menggunakan model machine learning (misal: Logistic Regression, SVM, Naive Bayes, atau model transformer seperti BERT/IndoBERT).
- **Visualisasi Data**: Diagram distribusi sentimen, wordcloud, dan analisis statistik lain terkait sentimen pengguna.
- **Evaluasi Model**: Mengukur performa model (akurasi, precision, recall, f1-score, confusion matrix).

> **Catatan:** Semua eksperimen, pipeline, dan hasil dapat dijalankan langsung di Jupyter Notebook.

## 📁 Struktur Proyek

- `*.ipynb` — Notebook utama eksperimen, eksplorasi data, pemodelan dan visualisasi.
- `requirements.txt` — Daftar dependensi Python yang diperlukan.
- `LICENSE` — Lisensi proyek (MIT License).

## 🛠️ Instalasi & Menjalankan Proyek

1. **Klon repositori**
    ```bash
    git clone https://github.com/NibroosAbrar/Sentimen-Analysis-Dana-Platform.git
    cd Sentimen-Analysis-Dana-Platform
    ```

2. **Buat & aktifkan virtual environment** (opsional, direkomendasikan)
    ```bash
    python -m venv venv
    source venv/bin/activate  # Linux/Mac
    venv\Scripts\activate     # Windows
    ```

3. **Instal semua dependensi**
    ```bash
    pip install -r requirements.txt
    ```

4. **Buka Jupyter Notebook**
    ```bash
    jupyter notebook
    ```
    Kemudian buka file `.ipynb` yang diinginkan.

## 📦 Dependensi Utama

Beberapa library penting yang digunakan:
- pandas, numpy, matplotlib, seaborn
- scikit-learn, xgboost, lightgbm, imbalanced-learn
- nltk, Sastrawi, spacy, textblob, wordcloud
- huggingface transformers (opsional untuk model BERT)
- Flask (jika ada deployment API sederhana)

Lihat file `requirements.txt` untuk daftar lengkap.

## 📈 Contoh Output Visualisasi

- Wordcloud kata positif/negatif
- Pie chart distribusi sentimen
- Confusion matrix hasil prediksi model

> *Tampilan visualisasi dapat ditemukan langsung di notebook.*

## ⚖️ Lisensi

MIT License © 2025 Muhammad Nibroos Abrar

---

_Dibuat untuk keperluan riset, edukasi, dan pengembangan teknologi analisis sentimen di Indonesia._
