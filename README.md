# Face_Detect

Proyek `Face_Detect` adalah aplikasi sederhana yang dikembangkan untuk mendeteksi wajah manusia pada gambar statis maupun *video stream* secara *real-time* menggunakan pustaka *Computer Vision* terkemuka.

---

## 🌟 Fitur Utama

* **Deteksi Wajah *Real-Time***: Mampu mendeteksi wajah secara instan dari input *webcam* atau kamera yang terhubung.
* **Deteksi Gambar Statis**: Memproses gambar yang sudah ada dan menandai lokasi wajah yang terdeteksi.
* ***Bounding Box***: Secara otomatis menggambar persegi (*bounding box*) di sekitar setiap wajah yang berhasil dideteksi. 

[Image of face detection bounding box]

* **Performa Tinggi**: Menggunakan algoritma yang dioptimalkan (seperti Haar Cascades atau model DL ringan) untuk kinerja yang cepat.

---

## 🛠️ Teknologi yang Digunakan

Proyek ini dibangun terutama menggunakan Python dan pustaka *Computer Vision* yang populer:

| Kategori | Teknologi | Deskripsi |
| :--- | :--- | :--- |
| **Bahasa Pemrograman** | Python 3.x | Bahasa utama untuk implementasi skrip dan logika. |
| **Computer Vision** | OpenCV (`cv2`) | Pustaka wajib untuk pemrosesan gambar, akses kamera, dan penerapan model deteksi. |
| **Komputasi Numerik** | NumPy | Untuk penanganan data gambar dalam bentuk array multidimensi yang efisien. |
| **Model** | Haar Cascades / Pre-Trained Model | File model yang digunakan oleh OpenCV untuk mengenali pola wajah (misalnya, `haarcascade_frontalface_default.xml`). |

---

## ⚙️ Prasyarat Instalasi

Pastikan sistem Anda telah memenuhi prasyarat dasar berikut:

1.  **Python 3.6** atau versi yang lebih baru.
2.  **`pip`** (Manajer paket Python).
3.  **Kamera atau Webcam** (Diperlukan untuk menguji fitur *real-time*).

## 💻 Instalasi dan Penyiapan

Ikuti langkah-langkah sederhana di bawah ini untuk menjalankan proyek di lingkungan lokal Anda.

### 1. Kloning Repositori

Buka terminal Anda dan klon repositori ini:

```bash
git clone [https://github.com/pashya166/Face_Detect.git](https://github.com/pashya166/Face_Detect.git)
cd Face_Detect
