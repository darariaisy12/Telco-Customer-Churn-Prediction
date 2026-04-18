# Telco Customer Churn: Analisis Prediksi & Strategi Retensi

## Tentang Projek Ini
Di industri bisnis manapun, mempertahankan pelanggan yang sudah ada selalu lebih hemat biaya dibandingkan mencari pelanggan baru. Dalam projek ini, saya mengolah dataset Telco Customer Churn untuk mencari tahu pola perilaku pelanggan yang berhenti berlangganan (*churn*). 

Selain melakukan analisis data, saya juga membangun model Machine Learning untuk memprediksi pelanggan mana yang memiliki risiko *churn* tinggi. Harapannya, insight dari model ini bisa digunakan oleh tim bisnis untuk memberikan penawaran khusus sebelum pelanggan benar-benar pindah ke kompetitor.

## Temuan & Hasil Prediksi
**Performa Model:** Menggunakan algoritma **Random Forest Classifier**, model yang dibangun berhasil mencapai akurasi **78.54%** dalam memprediksi nasib pelanggan.

**Faktor Pemicu Utama:** Dari hasil analisis fitur, ternyata masalah utamanya ada di angka. Total tagihan (**TotalCharges**), tagihan bulanan (**MonthlyCharges**), dan lama berlangganan (**tenure**) adalah tiga alasan terkuat pelanggan memutuskan untuk pergi.

**Rekomendasi Bisnis:** Berdasarkan data tersebut, perusahaan sebaiknya fokus mengevaluasi penyesuaian harga paket dan membuat program loyalitas yang ditargetkan khusus untuk pelanggan dengan sistem kontrak bulanan (*Month-to-Month*).

## Tools & Library yang Digunakan
**Pemrosesan Data:** Pandas, NumPy (Data cleaning, handling missing values, Label & One-Hot Encoding).
**Visualisasi EDA:** Matplotlib, Seaborn (Menganalisis tren, distribusi, dan komparasi data).
**Machine Learning:** Scikit-Learn (Train-Test split, pembuatan model, dan evaluasi matriks).

*Projek ini saya kerjakan untuk mempraktikkan secara langsung bagaimana mengubah raw data yang berantakan menjadi insight bisnis yang jelas dan siap dieksekusi.*
