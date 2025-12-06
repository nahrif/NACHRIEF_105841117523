# 📊 Proyek Analisis dan Pemodelan Rombongan Belajar SD Indonesia 2024

Repositori ini berisi keseluruhan artefak proyek Tugas Besar Applied Machine Learning. Proyek ini berfokus pada analisis data rombongan belajar Sekolah Dasar (SD) di Indonesia tahun 2024 dan pembangunan model Machine Learning (ML).

---

## 🎯 Tujuan Proyek

Proyek ini bertujuan untuk:

1.  Melakukan analisis dan eksplorasi mendalam terhadap data jumlah Rombongan Belajar SD per provinsi dan tingkat di Indonesia.
2.  Membangun model **Machine Learning (Random Forest)** untuk [**Prediksi/Klasifikasi**] Rombongan Belajar.
3.  Menyediakan dokumentasi lengkap mulai dari tahap perancangan hingga laporan akhir.

## 📁 Struktur Repositori

| Nama File | Deskripsi |
| :--- | :--- |
| **`NACHRIEF NACHRIEF - LK Perancangan Projec...`** | Dokumen Lembar Kerja (LK) Perancangan Proyek yang berisi tahap awal, perencanaan, dan batasan proyek. |
| **`LAPORAN TUGAS BESAR.docx`** | Dokumen Laporan Akhir yang berisi latar belakang, metodologi, hasil Analisis Data Eksplorasi (EDA), proses pemodelan, evaluasi, kesimpulan, dan saran. |
| **`Mid.ipynb`** | *Jupyter Notebook* utama yang mencakup seluruh alur kerja proyek, mulai dari pemuatan data, *data cleaning*, EDA, *Feature Engineering*, hingga pelatihan dan evaluasi model. |
| **`jumlah-rombongan-belajar-menurut-tingkat-tiap-propinsi-indonesia-sd-2024.xlsx`** | Dataset *input* utama proyek, berisi data mentah/bersih mengenai jumlah rombongan belajar SD per provinsi dan tingkat di Indonesia tahun 2024. |
| **`model_rf_rombel.pkl`** | Model *Machine Learning* (Random Forest) yang telah dilatih dan siap digunakan untuk inferensi atau prediksi data baru. |
| **`feature_cols.pkl`** | Daftar atau urutan fitur (kolom) yang digunakan saat melatih model. File ini penting untuk memastikan data baru dapat diproses dengan benar oleh model `.pkl`. |
| **`README.md`** | File dokumentasi yang sedang Anda baca ini. |

---

## 🛠️ Persyaratan dan Cara Menjalankan

Untuk mereplikasi analisis dan model ini secara lokal, Anda memerlukan lingkungan Python dengan pustaka utama seperti `jupyter`, `pandas`, `numpy`, dan `scikit-learn`.

### Langkah Menjalankan Analisis:

1.  **Instal Pustaka:** Buka Terminal/CMD dan jalankan:
    ```bash
    pip install jupyter pandas numpy scikit-learn openpyxl
    ```
2.  **Jalankan Jupyter:** Navigasi ke folder proyek Anda dan ketik:
    ```bash
    jupyter notebook
    ```
3.  **Buka Notebook:** Klik file **`Mid.ipynb`** di *browser* Jupyter yang terbuka.
4.  **Eksekusi:** Jalankan seluruh sel di dalam *notebook* untuk melihat seluruh proses analisis dan pemodelan.

---

## ✉️ Kontak

Jika Anda memiliki pertanyaan atau ingin berdiskusi mengenai proyek ini, silakan hubungi:

* **Nama:** [Nachrief]
* **Email:** [Nachriefarie@gmail.com]
