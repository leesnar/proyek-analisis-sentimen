# Proyek Analisis Sentimen Ulasan Aplikasi

## 📜 Deskripsi Proyek

Proyek ini bertujuan untuk membangun model Machine Learning yang dapat mengklasifikasikan sentimen dari ulasan pengguna sebuah aplikasi (misalnya dari Google Play Store) ke dalam kategori positif, negatif, atau netral. Proyek ini merupakan bagian dari submission kelas **Belajar Fundamental Deep Learning** di Dicoding.

## 📌 Latar Belakang

Ulasan pengguna adalah sumber data yang sangat berharga bagi pengembang aplikasi untuk memahami kelebihan dan kekurangan produk mereka. Namun, menganalisis ribuan ulasan secara manual tidak efisien. Model analisis sentimen dapat mengotomatiskan proses ini, memberikan insight cepat mengenai persepsi publik terhadap sebuah aplikasi.

## 📊 Dataset

Dataset yang digunakan dalam proyek ini adalah hasil _scraping_ mandiri dari ulasan pengguna di platform publik (seperti Google Play Store atau sejenisnya). Data mentah kemudian melalui proses pelabelan dan ekstraksi fitur sebelum digunakan untuk melatih model.

## 🛠️ Teknologi yang Digunakan

- **Python**: Bahasa pemrograman utama.
- **Pandas**: Untuk manipulasi dan pembersihan data.
- **Scikit-learn**: Untuk pra-pemrosesan data dan membangun model machine learning.
- **TensorFlow/Keras**: Untuk membangun model deep learning.
- **Matplotlib/Seaborn**: Untuk visualisasi data.
- **Jupyter Notebook**: Sebagai lingkungan pengembangan.

## ⚙️ Tahapan Proyek

1.  **Data Scraping**: Mengambil data ulasan mentah dari sumber publik.
2.  **Data Preprocessing**: Membersihkan teks ulasan (menghilangkan tanda baca, stopwords, dll.).
3.  **Feature Extraction**: Mengubah teks menjadi representasi numerik (misalnya menggunakan TF-IDF).
4.  **Model Development**: Melatih beberapa algoritma klasifikasi untuk menemukan model terbaik.
5.  **Model Evaluation**: Mengevaluasi performa model menggunakan metrik akurasi, presisi, dan recall.

## ✨ Hasil Utama

- Model yang dikembangkan berhasil mencapai **akurasi testing di atas 85%**, menunjukkan kemampuannya untuk mengklasifikasikan sentimen dengan baik.
- Proyek ini berhasil mengimplementasikan alur kerja NLP (Natural Language Processing) dari awal hingga akhir.

## 🚀 Cara Menjalankan Proyek

1.  **Clone Repositori**:
    ```bash
    git clone [https://github.com/leesnar/proyek-analisis-sentimen.git](https://github.com/leesnar/proyek-analisis-sentimen.git)
    ```
2.  **Install Dependensi**:
    ```bash
    pip install -r requirements.txt
    ```
3.  **Jalankan Notebook**: Buka dan jalankan file `.ipynb` yang tersedia di dalam repositori ini menggunakan Jupyter Notebook atau Google Colab.
