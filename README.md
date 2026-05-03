# Klasifikasi Penyakit Daun Jagung 🌽

Repositori ini berisi proyek *Deep Learning* untuk mengklasifikasikan kondisi daun jagung menggunakan arsitektur **MobileNetV3-Small** dengan PyTorch. Proyek ini dikembangkan untuk mengidentifikasi status kesehatan dan penyakit pada tanaman dengan akurat, dan berhasil mencapai hasil evaluasi yang sangat baik pada data uji.

## 🚀 Ringkasan Proyek

Tujuan utama dari proyek ini adalah untuk mengotomatisasi deteksi penyakit pada daun jagung. Dengan memanfaatkan arsitektur *Convolutional Neural Network* (CNN) yang ringan dan efisien—yaitu MobileNetV3-Small—model dapat melakukan inferensi dengan cepat namun tetap mempertahankan tingkat akurasi yang tinggi. Hal ini membuatnya sangat cocok untuk diaplikasikan pada perangkat *mobile* atau sistem komputasi ringan.

### Poin Utama
- **Arsitektur:** Implementasi `MobileNetV3-Small` menggunakan PyTorch.
- **Performa:** Mencapai tingkat presisi dan *recall* yang luar biasa pada *test set*, dengan prediksi yang sempurna (tidak ada yang salah tebak) pada evaluasi akhir.
- **Pipeline Data:** Dibangun dengan DataLoader bawaan PyTorch, transformasi gambar (*augmentation*) yang baik, serta pembagian *dataset* yang proporsional agar pelatihan model stabil.

## 📁 Struktur Repositori

- `corn_classification.ipynb` - File Jupyter Notebook utama yang berisi seluruh tahapan proses dari awal hingga akhir (Pembersihan Data, *Preprocessing*, Pembuatan Model, Pelatihan, Validasi, dan Evaluasi).
- `Laporan_Corn_Classification.docx` - Laporan komprehensif proyek yang mendokumentasikan metodologi, jalannya eksperimen, dan hasil akhir.

## 🛠️ Teknologi yang Digunakan

- **Python**
- **PyTorch & Torchvision** (Arsitektur Model, DataLoader, Transformasi)
- **Matplotlib** (Visualisasi Data)
- **NumPy & Pandas** (Manipulasi Data)
- **Scikit-learn** (Metrik & Evaluasi)

## 📊 Metodologi

1. **Preprocessing & Augmentasi Data:** Gambar daun dibersihkan, diubah ukurannya, dinormalisasi, dan diberikan augmentasi untuk meningkatkan kemampuan generalisasi model serta mencegah *overfitting*.
2. **Pelatihan Model:** Menggunakan arsitektur `MobileNetV3-Small`, dioptimasi dengan fungsi *loss* dan *optimizer* standar untuk klasifikasi gambar.
3. **Evaluasi:** Model divalidasi secara ketat selama proses pelatihan dan diuji coba pada data yang belum pernah dilihat sebelumnya (*holdout set*). Di dalam notebook juga disertakan visualisasi detail dari prediksi model.

---
*Proyek ini merupakan bagian dari portofolio Machine Learning & Data Science milik Zalsa.*
