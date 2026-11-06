# Single Layer Perceptron (SLP) for Iris Dataset Binary Classification

Repository ini berisi implementasi dan eksperimen algoritma **Single Layer Perceptron (SLP)** untuk klasifikasi biner pada dataset bunga Iris (*Setosa* vs *Versicolor*). Eksperimen dilakukan melalui dua pendekatan: pengolahan spreadsheet (Google Sheets / Microsoft Excel) dan pemrograman Python.

---

## Deskripsi Proyek
Proyek ini bertujuan untuk memahami mekanisme kerja jaringan saraf tiruan sederhana (Single Layer Perceptron) dalam mempelajari pola data melalui:
1. Feedforward Processing: Menghitung kombinasi linear $z$ dan fungsi aktivasi Sigmoid $g(z)$.
2. Gradient Descent: Memperbaiki nilai bias dan bobot ($\theta_1, \theta_2, \theta_3, \theta_4$) secara bertahap setelah setiap sampel data latih diproses.
3. Cross-Sheet Validation: Menguji ketangguhan bobot hasil training terhadap 20 data uji baru pada validation set tanpa mengubah nilai bobot (weights locked).

---

## Ringkasan Hasil Eksperimen (5 Epoch)

Berikut adalah tabel hasil perbandingan rata-rata Loss (MSE) dan Akurasi dari Epoch 1 hingga Epoch 5:

| Epoch | Training Loss (MSE) | Training Accuracy (%) | Validation Loss (MSE) | Validation Accuracy (%) |
| :---: | :---: | :---: | :---: | :---: |
| Epoch 1 | 0.4499 | 52.50% | 0.3290 | 50.00% |
| Epoch 2 | 0.0375 | 95.00% | 0.2473 | 50.00% |
| Epoch 3 | 0.0244 | 97.50% | 0.1759 | 50.00% |
| Epoch 4 | 0.0174 | 97.50% | 0.1194 | 85.00% |
| Epoch 5 | 0.0127 | 98.75% | 0.0816 | **100.00%** |

---

## Visualisasi Grafik Performa

### 1. Accuracy Chart (Training vs Validation)
![Accuracy Chart](page3_accuracy_chart.png)

### 2. Loss Chart (Training vs Validation)
![Loss Chart](page5_loss_chart.png)

---

## Struktur Repositori & Berkas

* `slp_iris_classification.py` : Script Python untuk pelatihan, validasi, dan plotting grafik.
* `PMM-TemplateSLP.xlsx` : File Excel lengkap berisi perhitungan rumus `SLP-Training`, `SLP-Validation`, dan `Resume`.
* `README.md` : Dokumentasi utama proyek.

---
