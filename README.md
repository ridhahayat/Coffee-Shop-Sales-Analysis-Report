# Coffee Shop Sales Analysis Report

## Business Understanding

Bisnis ini mengoperasikan jaringan kedai kopi dengan saluran penjualan melalui toko fisik (beberapa wilayah NYC: Lower Manhattan, Hell’s Kitchen, dan Astoria) serta kanal penjualan online.

### Penawaran Produk:
- Minuman kopi (espresso, organik, premium)
- Teh (special blends, chai)
- Cokelat minum
- Baked goods (roti & kue)
- Produk ritel (biji kopi, sirup, cokelat kemasan)

**Kategori kopi menyumbang pendapatan tertinggi**, dengan penjualan ~Rp270K hanya dalam enam bulan.

### Tujuan Bisnis:
- Optimalisasi inventaris & desain menu
- Efisiensi penempatan promosi
- Personalisasi pemasaran
- Identifikasi produk top dan low performer

---

## Problem Statement

Analisis ini bertujuan untuk menjawab pertanyaan utama berikut:

- Kategori/lini produk mana yang berkinerja tertinggi dan terendah?
- Bagaimana tren penjualan berdasarkan waktu (bulan, hari, jam)?
- Kanal atau lokasi mana yang menghasilkan pendapatan terbesar?
- Produk apa yang paling sering dibeli dan produk mana yang tidak laku?

---

## Dataset

Dataset penjualan coffee shop mencakup transaksi dari kanal offline dan online.

### Fitur penting dalam dataset:
- `Transaction ID`: ID transaksi unik
- `Product Category` & `Product`: Informasi produk
- `Price`, `Quantity`, `Total`: Informasi penjualan
- `Order Date`, `Order Time`: Waktu transaksi
- `Sales Channel`: Online atau Offline
- `Store Location`: Lokasi toko (NYC Area)

---

## Data Preparation

Langkah-langkah preprocessing:
- Membersihkan data duplikat
- Mengubah format tanggal dan waktu
- Menambahkan kolom waktu baru: `Month`, `Day`, `Hour`
- Visualisasi distribusi dan frekuensi produk

---

## Exploratory Data Analysis (EDA)

Beberapa analisis dan visualisasi yang dilakukan:

- **Penjualan berdasarkan kategori produk**
- **Tren penjualan per bulan & hari**
- **Jam sibuk pembelian produk**
- **Kontribusi kanal penjualan (online vs offline)**
- **Performa lokasi toko**
- **Produk paling laris & kurang diminati**
- **Heatmap korelasi variabel numerik**

---

## Insight Penting

- **Produk kopi** (premium dan espresso) mendominasi penjualan.
- Penjualan tertinggi terjadi di **akhir pekan dan jam 10–12 siang**.
- Kanal **offline masih menyumbang mayoritas pendapatan**.
- **Astoria dan Lower Manhattan** menunjukkan performa toko terbaik.
- Produk **cokelat kemasan** dan **teh chai** merupakan produk dengan penjualan terendah.

---

## Tools & Library

- Python (Pandas, NumPy)
- Matplotlib & Seaborn
- Jupyter Notebook

---

## Kesimpulan & Rekomendasi

- **Perkuat promosi untuk kategori non-kopi** agar distribusi produk lebih merata.
- Fokuskan kampanye dan staf pada jam sibuk (10:00–12:00).
- **Optimalkan performa kanal online** agar bisa menyaingi kanal offline.
- Evaluasi kelayakan stok produk yang tidak diminati untuk efisiensi biaya.
- Gunakan insight waktu dan produk favorit untuk menyusun program loyalitas.

---
