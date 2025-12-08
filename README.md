# ❤️ Heart Attack Risk Analysis Using Exploratory Data Analysis & Discrete Mathematics

Proyek ini berisi proses analisis risiko serangan jantung menggunakan **Exploratory Data Analysis (EDA)** dan penerapan konsep **Matematika Diskrit** seperti logika proposisional, himpunan & relasi, *decision tree* manual, dan probabilitas diskrit.

Seluruh analisis dilakukan menggunakan **Python** (Jupyter Notebook).

---

## 📂 Struktur Analisis

Analisis ini dibagi menjadi dua bagian utama:

### 1. Exploratory Data Analysis (EDA)

Bagian ini bertujuan untuk memahami dan memvisualisasikan data:

* **Overview Dataset:** Pemeriksaan baris/kolom, tipe data, dan *missing values*.
* **Distribusi Variabel Numerik:** Visualisasi (histogram, boxplot) dan statistik deskriptif.
* **Distribusi Variabel Kategorikal.**
* **Distribusi Variabel Target:** Analisis variabel `heart_attack`.
* **Crosstab Faktor Risiko → heart_attack:** Analisis hubungan antar faktor.
* **Korelasi & Heatmap:** Identifikasi korelasi antar variabel numerik.
* **Analisis Threshold:** Penentuan batas kritis untuk variabel (age, blood pressure, LDL, sleep).

### 2. Penerapan Matematika Diskrit

Bagian ini mengaplikasikan konsep matematis pada hasil EDA:

* **Logika Proposisional:** Perumusan aturan IF–THEN berbasis hasil *crosstab*.
* **Himpunan & Relasi:** Kategorisasi data berdasarkan *threshold* dan korelasi yang ditemukan.
* **Decision Tree Manual:** Pembuatan pohon keputusan berdasarkan korelasi dan *cut-off* yang dianalisis.
* **Probabilitas Diskrit:** Perhitungan $P(A)$ dan probabilitas bersyarat $P(A|B)$ berdasarkan temuan EDA.

---

## 🛠️ Tools & Library

Proyek ini dikembangkan menggunakan Python dengan *library* berikut:

| Kategori | Library | Tujuan Utama |
| :--- | :--- | :--- |
| **Data Manipulasi** | `pandas`, `numpy` | Pengolahan dan perhitungan data. |
| **Visualisasi** | `matplotlib`, `seaborn` | Pembuatan plot dan *heatmap* untuk EDA. |
| **Validasi** | `scikit-learn` (opsional) | Validasi/perbandingan hasil *decision tree* manual. |

---

## 🎯 Tujuan Proyek

1.  Memahami faktor-faktor risiko serangan jantung.
2.  Menggunakan EDA untuk membentuk dasar analisis matematis yang kuat.
3.  Menghubungkan data klinis dengan konsep Matematika Diskrit secara aplikatif.

## 📄 Catatan

* Kode utama dan hasil analisis lengkap tersedia dalam **Jupyter Notebook**.
* Data dan hasil perhitungan digunakan sebagai dasar penyusunan Bab 3 dan Bab 4 penelitian.
