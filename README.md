# Fast Food Marketing Campaign A/B Test Analysis

## Executive Summary
Proyek ini menganalisis efektivitas tiga strategi promosi pemasaran pemasaran pada restoran cepat saji untuk menentukan kampanye yang memberikan dampak penjualan tertinggi di berbagai skala pasar.

## Key Findings & Business Insights
- **Promosi Terbaik:** Promosi 1 dan 3 secara konsisten menghasilkan penjualan rata-rata tertinggi.
- **Promosi Paling Efektif Rendah:** Promosi 2 menghasilkan performa paling rendah secara signifikan.
- **Validasi Statistik:** Uji One-Way ANOVA menghasilkan **p-value $6.76 \times 10^{-10}$ ($p < 0.05$)**, mengonfirmasi bahwa perbedaan performa penjualan antar promosi bernilai **signifikan secara statistik**.

## Business Recommendations
1. **Hentikan Promosi 2:** Dialokasikan ulang anggarannya untuk memfokuskan ekspansi Promosi 1 dan 3.
2. **Optimalisasi Berdasarkan Market Size:** Gunakan kombinasi Promosi 1 dan 3 pada wilayah *Large* dan *Medium Market* untuk memaksimalkan ROI.

## Repository Structure
```text
├── data/
│   └── fastfood_marketing.csv
├── notebooks/
│   └── 01_data_cleaning_eda.ipynb
├── .gitignore
└── README.md