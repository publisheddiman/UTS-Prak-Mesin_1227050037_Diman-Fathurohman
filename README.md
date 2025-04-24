# UTS Praktikum Mesin – Klasifikasi Menggunakan Decision Tree

## Identitas
- **Nama:** Diman Fathurohman  
- **NIM:** 1227050037  
- **Metode yang Digunakan:** Decision Tree (karena NIM ganjil)

---

## Tahapan Pembuatan Model Klasifikasi

Berikut adalah tahapan-tahapan yang dilakukan dalam membangun model klasifikasi menggunakan algoritma **Decision Tree**:

### 1. Persiapan Data
- Mengimpor dataset (`dataset_buys_comp.csv`).
- Membersihkan dan memformat data:
  - Menghapus nilai kosong (jika ada).
  - Mengonversi data kategorikal ke bentuk numerik (jika diperlukan).
  - Menyesuaikan nama kolom agar konsisten.

### 2. Eksplorasi Data
- Melihat distribusi kelas target.
- Analisis korelasi antar fitur (jika relevan).
- Menampilkan statistik deskriptif dasar.

### 3. Pemisahan Data
- Membagi data menjadi data latih dan data uji (misalnya 80:20).
  
### 4. Pembuatan Model
- Menggunakan model **DecisionTreeClassifier** dari library `sklearn`.
- Melatih model pada data latih.

### 5. Prediksi
- Menggunakan model untuk memprediksi kelas pada data uji.

### 6. Evaluasi Model
- Menghitung akurasi, precision, recall, dan f1-score menggunakan `classification_report`.
- Menampilkan confusion matrix.
- Menampilkan visualisasi pohon keputusan (opsional).



![image](https://github.com/user-attachments/assets/43b98cac-07f3-4dfb-ab6d-672e78bf9e55)
![image](https://github.com/user-attachments/assets/91172a60-4b4e-4360-827b-f15bb9cc01bb)
![image](https://github.com/user-attachments/assets/1ebd709f-b6c3-408f-b84a-aabdbba5a0a3)


