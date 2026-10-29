# Praktikum Pertemuan 9 — Clustering dengan K-Means

## Deskripsi
Repository ini berisi tugas praktikum mata kuliah Pembelajaran Mesin mengenai clustering menggunakan algoritma K-Means. Praktikum ini bertujuan untuk mengelompokkan data pelanggan berdasarkan usia, pendapatan, dan skor belanja tanpa menggunakan label kelas.

## Tujuan Praktikum
1. Menyiapkan data tanpa label untuk proses clustering.
2. Melakukan scaling menggunakan StandardScaler.
3. Menentukan jumlah cluster optimal menggunakan metode Elbow.
4. Menerapkan algoritma K-Means dengan K=3.
5. Mengevaluasi hasil clustering menggunakan Silhouette Score.
6. Menginterpretasikan karakteristik setiap cluster.

## Dataset
Dataset yang digunakan memiliki tiga fitur:
- **Usia:** Umur pelanggan.
- **Pendapatan:** Pendapatan pelanggan.
- **Skor Belanja:** Skor yang menggambarkan perilaku belanja pelanggan.

Catatan: Notebook ini menggunakan dataset sintetis yang dibuat untuk keperluan praktikum karena dataset asli tidak disertakan dalam modul.

## Metode yang Digunakan
- **StandardScaler:** Menyamakan skala fitur.
- **Elbow Method:** Membantu menentukan jumlah cluster.
- **K-Means Clustering:** Mengelompokkan data menjadi beberapa cluster.
- **Silhouette Score:** Mengevaluasi kualitas hasil clustering.
- **Visualisasi:** Menampilkan grafik Elbow dan scatter plot hasil clustering.

## Teknologi dan Library
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook / Google Colab

## Cara Menjalankan
1. Unduh file notebook `Praktikum_Pertemuan9_Clustering_KMeans.ipynb`.
2. Buka Google Colab atau Jupyter Notebook.
3. Upload file notebook.
4. Jalankan seluruh kode menggunakan menu **Runtime → Run all** jika menggunakan Google Colab.
5. Amati hasil clustering, grafik Elbow, Silhouette Score, dan visualisasi cluster.

## Latihan Mandiri
1. Membandingkan hasil clustering K=3 dan K=5 berdasarkan Silhouette Score.
2. Membandingkan hasil K-Means dengan scaling dan tanpa scaling.
3. Membuat scatter plot berdasarkan fitur usia dan skor belanja.

## Kesimpulan
Algoritma K-Means dapat digunakan untuk mengelompokkan pelanggan berdasarkan kemiripan karakteristiknya. Metode Elbow membantu menentukan jumlah cluster, sedangkan Silhouette Score digunakan untuk mengevaluasi kualitas pengelompokan. Scaling diperlukan agar perbedaan skala antarfitur tidak mendominasi perhitungan jarak.

---
**Mata Kuliah:** Pembelajaran Mesin  
**Praktikum:** Pertemuan 9 — Clustering dengan K-Means  
**Kode Mata Kuliah:** INF62325
