# implementasi-ai-data-analysis-high-performance-computing_by-Waridhania-As-Syifa

(Waridhania As Syifa G1A023075)

Repository ini berisi dua studi kasus berdasarkan materi Praktisi Mengajar, yaitu analisis data dan AI untuk mengevaluasi kesalahan deteksi sampah plastik menggunakan YOLOv8, serta implementasi batch processing citra dengan konsep High Performance Computing (HPC) pada lingkungan pesisir Bengkulu.

## 👩‍💻 Konteks Pembelajaran

Repository ini disusun sebagai implementasi pembelajaran dari kegiatan Praktisi Mengajar dan sebagai latihan penerapan pemrograman dalam bidang analisis data, kecerdasan buatan, serta komputasi berkinerja tinggi.

# Studi Kasus Praktisi Mengajar: Analisis Data dan High Performance Computing

Repository ini berisi dua studi kasus implementasi pemrograman berdasarkan materi Praktisi Mengajar, yaitu **Make Sense of Data with Analysis and AI** dan **Bridging Global Infrastructure to Address Local Challenges in High Performance Computing**.

Kedua studi kasus mengangkat pemanfaatan teknologi komputasi dan analisis data untuk mendukung penyelesaian permasalahan lingkungan, khususnya deteksi sampah plastik di wilayah pesisir Bengkulu.

## 📚 Daftar Studi Kasus

### 1. Analisis Data dan AI untuk Evaluasi Deteksi Sampah Plastik

Studi kasus ini menerapkan analisis data menggunakan Python untuk mengevaluasi kinerja model deteksi sampah plastik YOLOv8. Analisis dilakukan berdasarkan data hasil deteksi dengan memperhatikan *True Positive* (TP), *False Negative* (FN), dan *False Positive* (FP).

**Tujuan:**

* Memahami penerapan analisis data untuk mengevaluasi hasil deteksi objek.
* Menghitung metrik evaluasi, seperti *recall*, *false negative rate*, dan *false positive rate*.
* Menyajikan hasil analisis dalam bentuk tabel dan visualisasi grafik.

**Teknologi:** Python, Pandas, dan Matplotlib.

### 2. Implementasi Batch Processing dengan Konsep High Performance Computing (HPC)

Studi kasus ini menerapkan pemrosesan sejumlah citra secara berkelompok (*batch processing*) menggunakan model YOLOv8. Program dirancang untuk memproses gambar dalam jumlah banyak dan menyimpan hasil deteksi sebagai bagian dari simulasi alur kerja komputasi untuk permasalahan lingkungan pesisir.

Disertakan pula contoh berkas konfigurasi pekerjaan berbasis SLURM sebagai gambaran penjadwalan tugas pada lingkungan HPC.

**Tujuan:**

* Memahami konsep pemrosesan citra secara berkelompok.
* Mengimplementasikan inferensi model YOLOv8 pada sekumpulan gambar.
* Mengenal alur kerja dan konfigurasi dasar pekerjaan pada lingkungan HPC.

**Teknologi:** Python, Ultralytics YOLOv8, dan SLURM.

## 🛠️ Instalasi dan Penggunaan

1. Pastikan Python telah terpasang pada komputer.

2. Unduh atau *clone* repository ini:

   ```bash
   git clone https://github.com/waridhaniaassyifa/implementasi-ai-dan-high-performance-computing_by-Waridhania-As-Syifa/tree/main
   ```

3. Masuk ke folder studi kasus yang ingin dijalankan.

4. Instal dependensi sesuai berkas `requirements.txt`:

   ```bash
   pip install -r requirements.txt
   ```

5. Jalankan program Python sesuai petunjuk pada README masing-masing studi kasus.

**Catatan:** Studi kasus pertama menggunakan data contoh untuk demonstrasi analisis. Studi kasus kedua membutuhkan model YOLOv8 dan kumpulan citra sebagai masukan. Berkas SLURM merupakan template yang perlu disesuaikan dengan konfigurasi klaster HPC yang digunakan.

## 🎯 Kesimpulan

Kedua studi kasus ini menunjukkan bagaimana analisis data, kecerdasan buatan, dan konsep komputasi berkinerja tinggi dapat diterapkan untuk mendukung evaluasi deteksi sampah plastik. Penerapan tersebut menjadi contoh pemanfaatan teknologi untuk memahami dan mengevaluasi permasalahan lingkungan pesisir secara lebih terstruktur.

