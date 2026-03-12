# Tugas Individu 3: Praktik Machine Learning (Computer Vision - OpenCV Part 3)
**Dosen Pengampu:** Herfandi, Ph.D.

Repositori ini berisi dokumentasi dan hasil praktik mandiri mengenai teknik pengolahan citra menggunakan library OpenCV. Praktikum ini mencakup teknik penghalusan gambar, binarisasi, dan deteksi tepi yang merupakan komponen penting dalam alur kerja Machine Learning dan Computer Vision.

---

## Identitas Mahasiswa
- **Nama:** Sherly Novia Indriani
- **NIM:** 231001057
- **Kelas:** Informatika – C

---

## Hasil Praktik OpenCV (Part 3)
Berikut adalah materi dan fungsionalitas yang telah dipraktikkan:
- **Editor:** Jupyter Notebook / VS Code
- **Library Utama:** `OpenCV (cv2)`, `NumPy`
- **Topik Utama:** Image Smoothing, Thresholding (Binarization), dan Canny Edge Detection.

### Langkah-Langkah Praktik:
1. **Import Library:** Menyiapkan lingkungan kerja dengan mengimpor library `cv2` dan `numpy`.
2. **Image Smoothing:**
   - Menerapkan `cv2.blur()` (Averaging) untuk mengurangi noise gambar.
   - Menggunakan `cv2.GaussianBlur()` untuk hasil penghalusan yang lebih natural.
   - Membuat trackbar untuk mengatur ukuran kernel secara dinamis.
3. **Image Binarization (Thresholding):**
   - Mengonversi gambar ke Grayscale.
   - Menerapkan `cv2.threshold()` dengan berbagai tipe: `BINARY`, `BINARY_INV`, `TRUNC`, `TOZERO`.
   - Implementasi **Otsu’s Thresholding** untuk menentukan nilai ambang batas secara otomatis.
4. **Edge Detection:**
   - Menggunakan algoritma **Canny Edge Detection** (`cv2.Canny`) untuk mengekstraksi garis tepi objek.
5. **Interactive Task:**
   - Membuat aplikasi interaktif yang menggabungkan Binary Thresholding dan Canny Edge Detection dalam satu jendela menggunakan trackbar.
   - Menggunakan manipulasi array NumPy (`np.zeros`) untuk menyusun tampilan gambar secara vertikal dan horizontal.

---

## Analisis & Kesimpulan
Berdasarkan praktikum ini, dapat disimpulkan bahwa:
- **Pentingnya Grayscale:** Proses Thresholding dan Canny Edge Detection memerlukan input gambar grayscale karena algoritma tersebut bekerja berdasarkan intensitas cahaya (kecerahan), bukan warna.
- **Smoothing sebagai Pre-processing:** Image smoothing (seperti Gaussian Blur) sangat penting dilakukan sebelum deteksi tepi atau thresholding untuk menghilangkan noise kecil agar hasil deteksi lebih akurat.
- **Interaktivitas:** Penggunaan Trackbar sangat memudahkan dalam menentukan nilai parameter (seperti ukuran kernel atau nilai threshold) yang paling optimal untuk gambar tertentu secara cepat.

---

## Video Presentasi & Demonstrasi
Penjelasan lengkap mengenai proses koding, analisis baris per baris, dan hasil eksekusi program dapat dilihat melalui tautan video berikut:

👉 [https://youtu.be/jfVwUtapYp8?si=AcoYUEJ6yNYyFD56]

---

