# 🧠 HoloCam Studio - by Rafashacode.id

HoloCam Studio adalah aplikasi interaktif yang memungkinkan kamu menggambar langsung dengan gerakan tangan menggunakan deteksi jari secara real-time. Dibangun dengan Python, OpenCV, dan MediaPipe dalam antarmuka grafis berbasis Tkinter.

---

## 🎯 Fitur Utama

* Deteksi gerakan tangan menggunakan MediaPipe
* Menggambar menggunakan gerakan jari (nonaktif jika jempol terbuka)
* UI modern dengan antarmuka grafis Tkinter
* Snapshot gambar yang dapat disimpan otomatis
* Pilihan warna, ketebalan, dan opasitas garis

---

## 📦 Instalasi

### 1. Clone Repository:

```bash
git clone https://github.com/rafashacodeid/holocam-studio.git
cd holocam-studio
```

### 2. Buat dan Aktifkan Virtual Environment (Opsional Tapi Disarankan):

```bash
python -m venv venv
# Windows:
venv\Scripts\activate
# macOS/Linux:
source venv/bin/activate
```

### 3. Install Semua Dependensi:

```bash
pip install -r requirements.txt
```

Jika kamu tidak menggunakan `requirements.txt`, kamu bisa install manual:

```bash
pip install opencv-python mediapipe pillow numpy
```

---

## 🚀 Cara Menjalankan Aplikasi

```bash
python holocam.py
```

> **Pastikan kamera kamu aktif** dan memiliki izin akses.

---

## 📁 Struktur Folder

```
holocam-studio/
├── holocam.py
├── snapshots/         # Folder tempat menyimpan snapshot
├── requirements.txt
└── README.md
```

---

## 🛠️ Penggunaan

* Tekan tombol **Mulai Menggambar** untuk mengaktifkan kamera
* Aktifkan mode menggambar, lalu arahkan jari telunjuk ke layar
* Gambar akan muncul saat jempol kamu tertutup (gesture tertutup)
* Gunakan slider untuk mengatur warna, ketebalan, dan opasitas
* Tekan **Ambil Snapshot** untuk menyimpan hasilnya

---

## ✅ Requirements

* Python 3.8 atau lebih baru
* Kamera aktif dan terhubung
* Sistem operasi Windows/Linux/macOS

---

## 🧑‍💻 Dibuat Oleh

**Rafashacode.id**

Temukan lebih banyak tools menarik lainnya di: [https://github.com/rafashacodeid](https://github.com/rafashacodeid)

---

## 💡 Tips

* Gunakan lingkungan virtual agar dependensi tidak bentrok
* Jalankan dari VS Code agar bisa debug dengan mudah
* Simpan hasil karya kamu di folder `snapshots`

---

Selamat mencoba! 🚀
