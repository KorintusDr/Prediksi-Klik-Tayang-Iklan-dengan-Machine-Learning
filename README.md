### Prediksi Rasio Klik-Tayang Iklan

Proyek ini bertujuan untuk menganalisis dan memprediksi rasio klik-tayang iklan berdasarkan beberapa fitur pengguna menggunakan Machine Learning dengan model RandomForestClassifier. Di bawah ini adalah langkah-langkah untuk menjalankan dan memahami proyek ini.

#### Langkah-langkah

1. **Instalasi dan Persiapan Lingkungan**

   Pastikan Anda telah menginstal Python dan paket-paket yang diperlukan:
   - Python 3.x
   - Pandas
   - NumPy
   - Plotly
   - Scikit-learn

2. **Persiapan Data**

   Pastikan file `data.csv` sudah tersedia. File ini harus berisi data dengan kolom sebagai berikut:
   - `Daily Time Spent on Site`: Waktu harian yang dihabiskan di situs (dalam jam)
   - `Age`: Usia pengguna
   - `Area Income`: Pendapatan daerah pengguna (dalam USD)
   - `Daily Internet Usage`: Penggunaan internet harian (dalam jam)
   - `Gender`: Jenis kelamin pengguna (Laki-laki = 1, Perempuan = 0)
   - `Clicked on Ad`: Label target dengan nilai 0 (Tidak diklik) atau 1 (Diklik)

3. **Analisis Data**

   - Data akan dimuat menggunakan Pandas dan kolom `Clicked on Ad` akan diubah dari nilai 0 dan 1 menjadi "Tidak" dan "Ya".
   - Dilakukan analisis rasio klik-tayang berdasarkan fitur-fitur seperti waktu yang dihabiskan di situs, penggunaan internet harian, usia, dan pendapatan daerah menggunakan grafik boxplot.

4. **Pelatihan Model Machine Learning**

   - Data akan dibagi menjadi set pelatihan dan pengujian menggunakan `train_test_split` dari Scikit-learn.
   - Model RandomForestClassifier akan digunakan untuk memprediksi rasio klik-tayang berdasarkan fitur-fitur yang ada.

5. **Prediksi Rasio Klik-Tayang**

   - Setelah melatih model, pengguna dapat memasukkan nilai untuk fitur-fitur yang relevan (waktu harian di situs, usia, pendapatan daerah, penggunaan internet harian, dan jenis kelamin).
   - Model akan memprediksi apakah pengguna akan mengklik iklan atau tidak.

#### Menjalankan Proyek

1. Pastikan lingkungan Python dan paket-paket yang dibutuhkan telah diinstal.
2. Unduh dan simpan file data.csv dalam direktori yang sama dengan notebook Jupyter Anda.
3. Buka Jupyter Notebook menggunakan langkah-langkah di atas.
4. Buka notebook yang berisi kode proyek (main.ipynb atau sesuai nama yang Anda berikan).
5. Jalankan setiap sel kode secara berurutan untuk meload data, melakukan analisis, melatih model, dan melakukan prediksi.
6. Ikuti instruksi di notebook untuk memasukkan nilai fitur yang diperlukan dan melihat hasil prediksi.

Dengan mengikuti langkah-langkah ini menggunakan Jupyter Notebook, Anda dapat menjalankan analisis dan prediksi rasio klik-tayang iklan dengan menggunakan data pengguna yang diberikan.
