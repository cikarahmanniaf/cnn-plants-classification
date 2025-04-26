# cnn-plants-classification

# 🌿 Klasifikasi Tanaman: 10 Jenis Tanaman Tropis Indonesia

Proyek ini merupakan aplikasi deep learning untuk mengklasifikasi gambar tanaman tropis Indonesia ke dalam 10 kategori menggunakan Convolutional Neural Network (CNN).

## Gambaran Proyek

- Dataset berasal dari [Kaggle - Plant Classification](https://www.kaggle.com/datasets/marquis03/plants-classification).
- Dipilih 10 dari 30 jenis tanaman dan split data (train, val, test) digabungkan dan dibagi ulang secara acak untuk keperluan training.
- Proyek ini bertujuan untuk membangun model klasifikasi gambar yang mampu mengenali spesies tanaman berdasarkan fitur visual.
- Model yang telah dilatih kemudian dikonversi ke format TensorFlow.js, serta disimpan dalam format SavedModel dan TensorFlow Lite untuk keperluan deployment web dan mobile.

## Isi Proyek

- **Data Loading dan Preprocessing:** Pengambilan dan persiapan data gambar.
- **Data Augmentation:** Teknik augmentasi data untuk meningkatkan keragaman dataset.
- **Pembangunan Model CNN:** Pembuatan arsitektur model CNN.
- **Training dan Evaluasi Model:** Proses pelatihan model dan pengukuran performa.
- **Export Model:** Ekspor model ke format SavedModel, TensorFlow Lite, dan TensorFlow.js.

## Cara Menjalankan

1. **Clone repository ini:**
   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```
2. **Instal dependensi:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Jalankan Jupyter Notebook:**
   ```bash
   jupyter notebook notebook.ipynb
   ```

## Author

- **Nama:** Cika Rahmannia Febrianti
- **Email:** mc004d5x2144@student.devacademy.id
- **Dicoding ID:** cikarahmanniaf

