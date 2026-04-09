# Klasifikasi Tanaman Uvaria grandiflora Menggunakan Convolutional Neural Network (CNN)

**Proyek Penelitian** • Taman Kupu-Kupu Gita Persada  
**Periode**: Mei 2024 – Oktober 2024  
**Akurasi terbaik**: **85%**

Proyek ini mengembangkan model deep learning untuk mengidentifikasi tanaman **Uvaria grandiflora** secara otomatis dari gambar. Data primer dikumpulkan langsung di lokasi Taman Kupu-Kupu Gita Persada.

## 🎯 Tujuan Proyek
- Mengumpulkan dataset gambar tanaman secara primer
- Membangun model CNN untuk klasifikasi Tanaman Uvaria Grandiflora
- Mengeksplorasi performa model dengan variasi epoch (10, 100, dan 200)
- Mempublikasikan paper jurnal

## 📊 Hasil Eksperimen Epoch
Model diuji dengan 3 konfigurasi epoch training:

| Epoch | Akurasi (%) | Keterangan                  |
|-------|-------------|-----------------------------|
| 10    | 50% | Training cepat, akurasi rendah |
| 100   | 82.5% | Performa meningkat          |
| **200** | **85%**   | **Akurasi terbaik**         |

## 🛠️ Tech Stack
- **Python** • Google Colab
- TensorFlow / Keras
- Convolutional Neural Network (CNN)
- OpenCV • Matplotlib • Seaborn
- Google Colab (Training)

## 📁 Dataset
- **400 gambar** tanaman
- **4 kelas** (batang, daun, pohon, ranting)
- Data primer diambil langsung di Taman Kupu-Kupu Gita Persada

## 📁 Struktur Folder
- dataset/              ← 400 gambar (4 kelas)
- notebooks/            ← Training & evaluasi model
- models/               ← File .h5 model terbaik

## 🚀 Cara Menjalankan
1. Buka notebook di Google Colab
2. Jalankan seluruh cel

## Visualisasi Hasil
- Grafik Akurasi
  <img width="843" height="387" alt="image" src="https://github.com/user-attachments/assets/1b9eefe1-2c3f-4db5-8b70-00c149d11a38" />

- Grafik Loss

  <img width="838" height="391" alt="image" src="https://github.com/user-attachments/assets/b531c46c-4641-4034-a361-fac8014b3045" />

- Confusion Matrix

  <img width="666" height="536" alt="image" src="https://github.com/user-attachments/assets/65be8bbf-3c28-454f-bab0-7b66f5459fd9" />

- Hasil Evaluasi Class

  <img width="441" height="185" alt="image" src="https://github.com/user-attachments/assets/602b22e4-05a4-44b2-8b16-35f6de3c9008" />

## Publikasi
Paper jurnal berdasarkan hasil penelitian dan model ini telah dipublikasikan: https://penerbitgoodwood.com/index.php/jatra/article/view/5012/1419
