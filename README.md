# Klasifikasi Kondisi Permukaan Jalan: Perbandingan Kinerja KNN dan CNN

## 📝 Deskripsi Proyek
Proyek ini membandingkan kinerja algoritma **K-Nearest Neighbors (KNN)** dan **Convolutional Neural Network (CNN)** dalam mengklasifikasikan kondisi permukaan jalan berdasarkan citra. Sistem ini dapat mengidentifikasi tiga kondisi jalan: mulus, retak, dan berlubang.

## 📊 Dataset
Dataset dalam penelitian ini diperoleh melalui web scraping dari berbagai sumber online yang menyediakan gambar kondisi permukaan jalan. Dataset lengkap dapat diakses pada [Google Drive](https://drive.google.com/drive/folders/1kyRJT3bmx2oKr5Q1bG_XIAe1dab30O3v?usp=drive_link). Dataset terdiri dari:

| Kelas | Jumlah Data | Deskripsi |
|-------|-------------|-----------|
| Jalan Mulus | 500 Gambar | Gambar yang menunjukkan permukaan jalan yang rata dan tidak terdapat kerusakan atau lubang. |
| Jalan Retak | 500 Gambar | Gambar yang menggambarkan jalan dengan kerusakan permukaan seperti retakan atau degradasi ringan. |
| Jalan Berlubang | 500 Gambar | Gambar yang memperlihatkan jalan dengan lubang besar atau kerusakan yang cukup parah. |

## 🚀 Fitur Utama
- Klasifikasi citra jalan menggunakan dua algoritma berbeda
- Perbandingan hasil kinerja antara KNN dan CNN
- Visualisasi hasil prediksi
- Unduh paper penelitian dalam format PDF

## 💻 Persyaratan Sistem
- Python 3.7+
- TensorFlow 2.x
- scikit-learn
- OpenCV
- NumPy
- Matplotlib
- Pandas

## 📈 Hasil Eksperimen
Eksperimen menunjukkan perbandingan kinerja kedua algoritma:

| Model | Akurasi | Kelebihan | Kekurangan |
|-------|---------|-----------|------------|
| CNN   | 93,8%   | Ekstraksi fitur otomatis, akurasi tinggi | Waktu pelatihan lama |
| KNN   | 57,2%   | Sederhana, pelatihan cepat | Kurang efektif untuk pola kompleks |

## 📑 Kesimpulan
  Eksperimen ini menunjukkan bahwa Convolutional Neural Network (CNN) memiliki 
akurasi sebesar 93,8%, sedangkan K-Nearest Neighbors (KNN) memiliki akurasi 57,2%. CNN 
menunjukkan prediksi yang lebih akurat pada semua kelas terutama pada kondisi retak dengan 
lebih sedikit kesalahan klasifikasi dibandingkan KNN. Prediksi CNN konsisten mengenali pola 
visual kompleks, sementara KNN cenderung menghasilkan kesalahan lebih tinggi terutama pada 
kelas retak dan berlubang. 
  Hasil ini menegaskan bahwa CNN lebih unggul untuk klasifikasi kondisi permukaan 
jalan karena kemampuannya dalam ekstraksi fitur otomatis, meskipun membutuhkan waktu 
pelatihan yang lebih lama. Sebaliknya, KNN lebih sederhana namun kurang efektif dalam 
menangani pola yang kompleks.

## 📄 Download Paper
Untuk informasi lebih detail tentang penelitian ini, Anda dapat mengunduh paper dalam format PDF:

[Download Paper Penelitian (PDF)](https://github.com/user-attachments/files/19788875/535210001.1.1.pdf)

## 👥 Kontributor
Fenny Jong
