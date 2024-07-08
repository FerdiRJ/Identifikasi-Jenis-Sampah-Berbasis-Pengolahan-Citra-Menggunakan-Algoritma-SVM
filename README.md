# Identifikasi-Jenis-Sampah-Berbasis-Pengolahan-Citra-Menggunakan-Algoritma-SVM
Repositori ini berisi proyek Ujian Akhir Semester S1 Sains Data Fakultas Matematika dan Ilmu Pengetahuan Alam Universitas Negeri Surabaya dengan topik **“Identifikasi Jenis Sampah Berbasis Pengolahan Citra”**. Proyek ini bertujuan untuk mengembangkan sistem pendeteksi jenis sampah menggunakan teknologi pengolahan citra dan algoritma machine learning.

## Deskripsi

Masalah sampah merupakan isu lingkungan yang mendesak di Indonesia dengan volume sampah yang terus meningkat setiap tahun. Pada tahun 2022, Indonesia menghasilkan 35,93 juta ton sampah, meningkat 22,04% dari tahun sebelumnya. Untuk mengatasi masalah ini, daur ulang sampah secara efektif sangat penting, dan identifikasi jenis sampah merupakan langkah awal yang krusial.

Proyek ini mengembangkan sistem otomatis untuk mengidentifikasi jenis sampah dari gambar menggunakan metode klasifikasi berbasis pengolahan citra. Kami menggunakan dataset berisi 1889 gambar sampah yang dikategorikan ke dalam tiga kelas: besi, kertas/kardus, dan plastik. Metode yang diterapkan meliputi preprocessing gambar, ekstraksi fitur menggunakan Principal Component Analysis (PCA), dan klasifikasi menggunakan Support Vector Machine (SVM) dengan dua jenis kernel: Radial Basis Function (RBF) dan Linear.

<img width="375" alt="image" src="https://github.com/FerdiRJ/Identifikasi-Jenis-Sampah-Berbasis-Pengolahan-Citra-Menggunakan-Algoritma-SVM/assets/131805279/1846ab4f-7fe3-4086-9214-1b2ec18a0c7e">

## Metode

- **Preprocessing Gambar**: Penghapusan latar belakang dan normalisasi gambar untuk meningkatkan kualitas data.
- **PCA (Principal Component Analysis)**: Reduksi dimensi data gambar untuk mempertahankan variansi informasi penting.
- **Klasifikasi**: Menggunakan Support Vector Machine (SVM) dengan kernel Linear dan RBF untuk mengklasifikasikan jenis sampah.
- **Evaluasi Kinerja**: Mengukur performa model dengan metrik seperti akurasi, precision, recall, dan f1-score.
- **Prediksi**: Mengidentifikasi jenis sampah dari gambar baru menggunakan model yang telah dilatih.

## Hasil

- **Kernel RBF**: Akurasi tertinggi sebesar 68% dengan PCA dan tanpa edge detection.
- **Kernel Linear**: Akurasi 49% dengan PCA, menunjukkan performa yang lebih rendah dibandingkan kernel RBF.
- **Edge Detection**: Menerapkan edge detection malah menurunkan akurasi, menunjukkan bahwa pendekatan ini tidak efektif dalam konteks ini.



<img width="198" alt="image" src="https://github.com/FerdiRJ/Identifikasi-Jenis-Sampah-Berbasis-Pengolahan-Citra-Menggunakan-Algoritma-SVM/assets/131805279/9d2f6760-0077-4cda-81ca-8e05bb48f5bf">
