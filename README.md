# 🏦 Banking Customer & Transaction Analysis
### Power BI Portfolio Project | Muhammad Fauzi Romadhoni

---

## 📌 Project Overview
Dashboard analitik perbankan end-to-end menggunakan Power BI untuk menganalisis perilaku nasabah, tren transaksi, dan profil risiko kredit berdasarkan data akun dan transaksi banking.

---

## 🎯 Business Questions
- Bagaimana distribusi tipe akun dan profil kredit nasabah?
- Apa tren transaksi bulanan dan cabang paling aktif?
- Seberapa besar proporsi nasabah berisiko tinggi (Credit Score < 650)?
- Apakah nasabah bersaldo tinggi selalu memiliki profil kredit yang sehat?

---

## 📂 Dataset
| File | Baris | Deskripsi |
|---|---|---|
| `Customer_Account_Details.csv` | 800 | Data akun nasabah: saldo, kredit skor, tipe akun, pinjaman |
| `Banking_Transactions_Dataset.csv` | 1.000 | Data transaksi: tipe, nominal, cabang, mata uang, waktu |

**Relasi:** `AccountNumber` sebagai primary key penghubung kedua tabel.

---

## 🛠️ Tools & Techniques
- **Power BI Desktop** — visualisasi & dashboard
- **Power Query** — data cleaning & transformasi
- **DAX** — kalkulasi measures (% High Risk, Avg Credit Score, dll)
- **Data Modeling** — relasi one-to-many antar tabel

---

## 📊 Dashboard Pages

### Page 1 — Customer Overview
Gambaran umum profil nasabah: distribusi tipe akun, segmentasi credit score, dan hubungan antara saldo dengan jumlah pinjaman.

### Page 2 — Transaction Analysis
Tren transaksi bulanan, volume per tipe transaksi, dan Top 10 cabang paling aktif berdasarkan nilai transaksi. Dilengkapi slicer interaktif (Transaction Type, Currency, Time of Day).

### Page 3 — Risk & Executive Summary
Analisis risiko kredit nasabah: gauge credit score vs target 700, distribusi kategori risiko, perbandingan saldo antar segmen, dan tabel detail nasabah high risk.

---

## 💡 Key Findings
- **63.4%** nasabah masuk kategori High Risk (Credit Score < 650)
- Rata-rata credit score keseluruhan **574.8** — di bawah threshold sehat 700
- Nasabah dengan saldo tertinggi tidak selalu aman — rata-rata credit score 10 nasabah bersaldo tertinggi hanya **513**
- Transaksi terbesar didominasi oleh tipe **Transfer** senilai 1.15M

---

## 🎨 Design
- **Tema warna:** Navy `#0D1B2A` + Gold `#C9A84C` + Teal `#2EC4B6`
- **Proporsi layout:** Golden Ratio (1440 x 890px)
- **Conditional formatting** pada tabel risiko untuk identifikasi visual cepat

---

## 👤 Author
**Muhammad Fauzi Romadhoni**  
D4 Teknik Elektro Industri — Politeknik Elektronika Negeri Surabaya (PENS)  
Data Analyst — Banking Analyst — Monitoring and Evaluator
[https://www.linkedin.com/in/mfauziromadhoni/](#) | [mfauzir2477@gmail.com](#)
