# UTS Machine Learning (Linear & Logistic Regression)

Repositori ini dibuat untuk memenuhi Ujian Tengah Semester (UTS) mata kuliah **Machine Learning**. Seluruh implementasi model dan evaluasi dibangun secara manual menggunakan pustaka dasar NumPy, Pandas, dan Matplotlib.

## 👤 Identitas Mahasiswa
* **Nama:** Roma Susanti Manalu
* **NIM:** 241011400981
* **Kelas:** 05PLM004
* **Program Studi:** Teknik Informatika

---

## 📂 Ringkasan Hasil & Pembahasan
1. **Bagian A – Linear Regression (35%):**
   * Menggunakan dataset `Ads_Data.csv` dengan `RANDOM_STATE = 81`.
   * Berhasil melatih model menggunakan *Normal Equation* dan mengevaluasinya dengan metrik MAE, MSE, RMSE, serta $R^2$.
   * Melakukan eksperimen *Gradient Descent* dengan berbagai variasi *learning rate* (`0.001`, `0.02`, `0.1`) beserta analisis kurva *loss*.

2. **Bagian B – Logistic Regression (40%):**
   * Menggunakan dataset `Email_Data.csv` untuk klasifikasi spam.
   * Melatih model via *Gradient Descent* dan mengevaluasi performa menggunakan *Accuracy*, *Precision*, *Recall*, *F1-Score*, serta *Confusion Matrix*.
   * Melakukan visualisasi *decision boundary* (`contourf`) dan eksperimen pengaturan *threshold* probabilitas (`0.3`, `0.5`, `0.7`).

3. **Bagian C – Pemahaman Konsep (15%):**
   * Berisi penjelasan konseptual mengenai fungsi sigmoid, perbedaan *Normal Equation* dan *Gradient Descent*, pemilihan fungsi *loss* (MSE vs *Log Loss*), serta pencegahan *overfitting*.

4. **Bagian Bonus (+5):**
   * Perbandingan performa model implementasi manual dengan pustaka bawaan `scikit-learn` (`LinearRegression` dan `LogisticRegression`).

---
