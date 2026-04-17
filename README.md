# 🔍 Proyek NLP: Sistem Pencarian Dokumen Industri Konveksi

Repositori ini berisi implementasi *Natural Language Processing* (NLP) untuk membangun sistem *Information Retrieval* (Sistem Pencarian Dokumen) berbasis Python. Proyek ini mendemonstrasikan perbandingan antara pendekatan leksikal (**TF-IDF**) dan semantik (**Word2Vec**) dalam menemukan ulasan atau deskripsi produk yang paling relevan pada dataset industri konveksi.

---

## 📁 Struktur File
* `proyek_nlp_konveksi.ipynb` : File Jupyter Notebook utama yang berisi seluruh *pipeline* (Import, Preprocessing, Visualisasi, Representasi Vektor, dan Mesin Pencari).
* `dataset_konveksi.csv` : Dataset berisi 500 baris teks ulasan/deskripsi produk pakaian.
* `README.md` : Dokumentasi informasi dan instruksi menjalankan proyek (file ini).

---

## ⚙️ Prasyarat (*Prerequisites*)
Untuk menjalankan program ini di komputer lokal, pastikan Anda telah memiliki:
* Python 3.8 atau versi lebih baru.
* Jupyter Notebook terinstal.

Library Python yang dibutuhkan:
```bash
pip install pandas numpy scikit-learn nltk Sastrawi gensim matplotlib wordcloud
