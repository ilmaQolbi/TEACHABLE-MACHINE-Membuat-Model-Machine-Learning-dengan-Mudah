# TEACHABLE-MACHINE-Membuat-Model-Machine-Learning-dengan-Mudah

## Machine Learning
Menurut IBM, “Machine learning is a branch of artificial intelligence (AI) and computer science which focuses on the use of data and algorithms to imitate the way that humans learn, gradually improving its accuracy.” Artinya, Machine Learning adalah salah satu cabang dari AI yang berfokus pada penggunaan data dan algoritma untuk mengikuti pola pikir manusia yang terus berkembang dalam meningkatkan hasil akurasi. Dari machine learning kita bisa mendapatkan machine learning model yang merupakan file yang telah dilatih (train) dengan banyak data sehingga membentuk algoritma untuk mengenali pola tertentu.

## Teachable Machine
Teachable Machine adalah alat berbasis web yang membuat pembuatan model pembelajaran mesin menjadi cepat, mudah, dan dapat diakses oleh semua orang. Teachable machine bekerja dengan cara mengumpulkan data kedalam kelas-kelas atau kategori kemudian melatih model berdasarkan kelas yang telah dibentuk dan akhirnya menghasilkan model machine learning dalam bentuk Tensorflow.js yang dapat di export dan diunduh.

## Pratik Menggunakan Hasil Foto MRI Kasus Alzheimer
### Tools
1. Dataset
2. Teachable Machine

### Langkah-langkah
1. Unduh Alzheimer Dataset
   Dataset ini merupakan data yang telah di kumpulan dari berbagai website dengan masing-masing data memiliki label yang telah terverifikasi. Dataset ini berisi foto/gambar hasil MRI yang memiliki 4 kelas/tipe Alzheimers yaitu Mild Demented, Moderate Demented, Non Demented, dan Very Mild Demented. Tujuan dari publikasi dataset ini sendiri adalah untuk membuat model yang mampu memprediksi tipe Alzheimers dengan tingkat akurasi yang sangat tinggi.

2. Buka [Teachable Machine](https://teachablemachine.withgoogle.com/train?source=post_page-----27de270a6107--------------------------------)
3. Pilih Image project dan memilih kategori yang sesuai dengan image model yang kita butuhkan (standard image model atau embedded image model).
4. Buat 4 kelas sesuai dengan tipe Alzeimer’s dan input data berupa foto hasil MRI dari dataset sebelumnya menggunakan pilihan upload melalui file.
5. Setelah semua foto terupload, pilih train embedded model dalam menu training.
   Dalam menu training ini kita juga dapat memiliki opsi lebih lanjut seperti Epochs, Batch size dan learning rate dengan memilih pilihan advance. Proses training sendiri memerlukan lama waktu sesuai besar data dalam masing-masing kelas.
6. Export model Machine Learning dengan cara memilih Export model pada preview dan download my model pada menu Tensorflow.js
   Selain itu kita juga dapat mencoba model yang telah dibuat dengan cara upload salah satu foto hasil mri dalam dataset Alzheimer. dari hasil download tadi dapat kita lanjutkan membuat aplikasi Machine Learning seperti:
- streamlit
- Apache Mahout
- Compose
- Core ML Tools

## Referensi
Dianita Olipmimi (2021) TEACHABLE MACHINE: Membuat Model Machine Learning dengan Mudah diakses dari https://medium.com/statistics-uii/teachable-machine-membuat-model-machine-learning-dengan-mudah-27de270a6107
