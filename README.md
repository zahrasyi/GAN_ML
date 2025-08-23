# Implementasi Generative Adversarial Network (GAN)
Proyek ini merupakan implementasi Generative Adversarial Network (GAN) sederhana menggunakan PyTorch.
Tujuan dari proyek ini adalah mempelajari cara kerja GAN dalam menghasilkan gambar baru dari dataset MNIST, serta memvisualisasikan proses pelatihan melalui grafik loss dan contoh gambar yang dihasilkan Generator.

# Struktur Project

Proyek ini memiliki struktur folder sebagai berikut:

📦 GAN-Project
 ┣ 📂 outputs/                # Hasil gambar Generator
 ┣ 📂 checkpoints/            # Model yang sudah dilatih
 ┣ 📜 train_gan.ipynb         # Notebook utama (kode GAN + visualisasi)
 ┣ 📜 README.md               # Dokumentasi proyek
 ┗ 📜 requirements.txt        # Daftar library yang dibutuhkan
 ⚙️ Setup Environment

# Clone repository

git clone https:[//github.com/username/GAN-Project.git](https://github.com/zahrasyi/GAN_ML.git)
cd GAN-Project


Install dependency
🔹 Dengan pip
pip install torch torchvision matplotlib


🔹 Dengan conda

conda install pytorch torchvision torchaudio cpuonly -c pytorch
