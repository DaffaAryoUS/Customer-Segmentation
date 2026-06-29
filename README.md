# Customer Segmentation Analysis 📊🧩

## 📌 Project Overview

Proyek ini bertujuan untuk menganalisis segmentasi pelanggan pada dataset e-commerce guna memahami kontribusi tiap segment terhadap revenue serta mengidentifikasi potensi risiko pada pelanggan bernilai tinggi (high-value segment).

Analisis difokuskan pada perbedaan perilaku antar segment, termasuk tren revenue, jumlah transaksi, dan faktor operasional seperti delivery time yang berpotensi memengaruhi performa bisnis.

---

## ⚠️ Problem Statement

Dalam industri e-commerce, pelanggan memiliki perilaku yang beragam sehingga pendekatan umum (one-size-fits-all) kurang efektif dalam memaksimalkan revenue dan retensi pelanggan.

Customer segmentation menjadi strategi penting untuk memahami nilai dan karakteristik pelanggan, sehingga perusahaan dapat menerapkan strategi yang lebih tepat sasaran. Studi dari McKinsey & Company menunjukkan bahwa segmentasi yang efektif dapat meningkatkan profitabilitas melalui targeting yang lebih akurat.

Namun, perusahaan masih menghadapi tantangan dalam memahami kontribusi tiap segment serta mengidentifikasi risiko pada pelanggan bernilai tinggi yang menjadi kontributor utama revenue.

---

## 📂 About Data

* Dataset: Brazilian E-commerce Public Dataset
* Format: CSV
* Periode Data: 2016 – 2018
* Baris: 100,000
* Kolom: 23
* Data mencakup:

  * Customer information
  * Orders & transactions
  * Payment data
  * Delivery performance

---

## 🛠️ Tech Stack & Tools

* Language: Python
* Libraries: Pandas, NumPy, Matplotlib, Seaborn, Statsmodels, SciPy
* Environment: Jupyter Notebook (VS Code)
* Visualization: Matplotlib / Seaborn

---

## 💡 Key Insights

### 1. Segment Contribution to Revenue

* Segment High memberikan kontribusi revenue terbesar dibanding segment lainnya
* Namun kontribusi order dari segment ini relatif lebih rendah

### 2. Revenue Decline in High Segment

* Terjadi penurunan revenue signifikan pada segment High dalam 3 bulan terakhir (Juni – Agustus 2018)
* Mengindikasikan potensi perubahan perilaku atau risiko bisnis

### 3. Delivery Time Disparity

* Segment High memiliki rata-rata delivery time paling lama dibanding segment lain
* Hal ini berpotensi memengaruhi kepuasan pelanggan bernilai tinggi

### 4. Statistical Validation

* Uji Kruskal-Wallis menunjukkan adanya perbedaan signifikan delivery time antar segment
* Mengindikasikan faktor operasional berperan dalam perbedaan performa segment

---

## 🚀 Actionable Recommendations

### 1. Improve Delivery Performance for High Segment

* Prioritaskan pengiriman untuk pelanggan bernilai tinggi
* Optimalkan logistik pada area dengan delay tinggi

### 2. Segment-Based Strategy

* Terapkan strategi berbeda untuk tiap segment (personalization)
* Fokus pada retention untuk High segment

### 3. Monitoring & Early Warning System

* Implementasikan monitoring khusus untuk segment High
* Deteksi dini penurunan performa

### 4. Operational Optimization

* Evaluasi proses fulfillment & delivery
* Identifikasi bottleneck dalam supply chain

---

## 📊 Business Value

Analisis ini membantu perusahaan untuk:

* Memahami kontribusi tiap segment
* Mengidentifikasi risiko pada high-value customers
* Mengoptimalkan strategi berbasis data
* Meningkatkan customer retention & revenue

---

## 📎 Notes

Project ini menunjukkan bagaimana pendekatan data-driven dapat digunakan untuk menghubungkan customer behavior dengan performa bisnis serta menghasilkan insight yang actionable.

