# 📊 Proyek Analisis dan Pemodelan Rombongan Belajar SD Indonesia 2024

Repositori ini berisi keseluruhan artefak proyek Tugas Besar Analisis Data dan Pemodelan Machine Learning. Proyek ini berfokus pada analisis data rombongan belajar Sekolah Dasar (SD) di Indonesia tahun 2024 dan pembangunan model prediktif.

---

## 🎯 Tujuan Proyek

Proyek ini bertujuan untuk:

1.  Menganalisis dan mengeksplorasi data **Jumlah Rombongan Belajar** berdasarkan tingkat dan provinsi di seluruh Indonesia.
2.  Membangun model **Machine Learning (Random Forest)** untuk [**Prediksi/Klasifikasi**] Rombongan Belajar.
3.  Menyediakan laporan lengkap yang menjelaskan metodologi, hasil analisis, dan evaluasi pemodelan.

## 📁 Struktur Repositori

| Nama File | Deskripsi |
| :--- | :--- |
| **`LAPORAN TUGAS BESAR.docx`** | Dokumen Laporan Akhir yang berisi latar belakang, metodologi, hasil Analisis Data Eksplorasi (EDA), proses pemodelan, evaluasi, kesimpulan, dan saran. |
| **`Mid.ipynb`** | *Jupyter Notebook* utama yang mencakup seluruh alur kerja proyek, mulai dari pemuatan data, *data cleaning*, EDA, *Feature Engineering*, hingga pelatihan dan evaluasi model. |
| **`jumlah-rombongan-belajar-menurut-tingkat-tiap-propinsi-indonesia-sd-2024.xlsx`** | Data *input* utama proyek, berisi data mentah/bersih mengenai jumlah rombongan belajar SD per provinsi dan tingkat di Indonesia tahun 2024. |
| **`model_rf_rombel.pkl`** | Model *Machine Learning* yang telah dilatih (Random Forest) dan siap digunakan untuk inferensi atau prediksi data baru. |
| **`feature_cols.pkl`** | Daftar atau urutan fitur (kolom) yang digunakan saat melatih model. File ini krusial untuk memastikan data baru dapat diproses dengan benar oleh model `.pkl`. |

---

## 🛠️ Persyaratan dan Cara Menjalankan

Untuk menjalankan ulang analisis dan model ini secara lokal, Anda memerlukan lingkungan Python dengan pustaka berikut:

### Persyaratan Pustaka:

* **Python** (Disarankan versi 3.8+)
* `jupyter` atau `jupyterlab`
* `pandas`, `numpy`
* `scikit-learn` (untuk pemodelan dan tools ML)
* `openpyxl` (untuk membaca file `.xlsx`)

### Langkah Menjalankan Analisis:

1.  **Instal Pustaka:** Buka Terminal/CMD dan jalankan:
    ```bash
    pip install jupyter pandas numpy scikit-learn openpyxl
    ```
2.  **Jalankan Jupyter:** Navigasi ke folder proyek Anda di Terminal/CMD dan ketik:
    ```bash
    jupyter notebook
    ```
3.  **Buka Notebook:** Di *browser* Jupyter yang terbuka, klik file **`Mid.ipynb`**.
4.  **Eksekusi:** Jalankan seluruh sel di dalam *notebook* untuk mereplikasi hasil analisis dan pemodelan.

---

## ✉️ Kontak

Jika Anda memiliki pertanyaan atau ingin berdiskusi mengenai proyek ini, silakan hubungi:

* **Nama:** [NACHRIEF]
* **Email:** [Nachriefarie@gmail.com]
