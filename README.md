Naive Bayes Classification - Diabetes Dataset

# Deskripsi
Project ini merupakan implementasi algoritma Naive Bayes untuk melakukan klasifikasi pada dataset diabetes.
Model digunakan untuk memprediksi apakah seseorang memiliki diabetes (Outcome = 1) atau tidak (Outcome = 0) berdasarkan beberapa fitur kesehatan.

# Dataset
Dataset yang digunakan adalah Diabetes Dataset dengan beberapa fitur utama:
* Glucose
* BMI (Body Mass Index)
* Age
  
Target:
* 0 → Tidak diabetes
* 1 → Diabetes

# Tools & Library
Project ini menggunakan:
* Python
* Google Colab
* Library:

  * `pandas`
  * `numpy`
  * `scikit-learn`

# Alur Pengerjaan
1. Load dataset (.csv)
2. Pemilihan fitur (Glucose, BMI, Age)
3. Split data:
   * Training (80%)
   * Testing (20%)
4. Training model menggunakan **Gaussian Naive Bayes**
5. Evaluasi model menggunakan **accuracy**
6. Perhitungan manual:
   * Prior probability
   * Mean (μ)
   * Variance (σ²)
   * Likelihood
   * Posterior
   * Prediksi

# Cara Menjalankan
1. Buka file notebook `.ipynb` di Google Colab
2. Upload dataset atau gunakan file dari repository
3. Jalankan semua cell
4. Lihat hasil prediksi dan accuracy

# Repository

Link repository GitHub:
https://github.com/naylaviona/Kecerdasan-Buatan

---

## 👩‍💻 Author

Nayla Viona Azahra
