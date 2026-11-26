# Analisis Business Intelligence: Retensi Nasabah Bank & Performa Penjualan Retail

Proyek pemodelan data interaktif dan *Business Intelligence* (BI) berbasis **Microsoft Excel** menggunakan **Power Query**, **Power Pivot**, **DAX**, serta **Interactive Slicers**.

- **Penyusun:** Rafif Dwi Pradipta (`E42240950`)
- **Program Studi:** Bisnis Digital — Politeknik Negeri Jember
- **Dosen Pengampu:** Eka Yuniar, S.Kom., MMSI
- **Video Presentasi:** [Tonton di YouTube](https://youtu.be/Zg8gxSKQnHU)

---

## Ringkasan Studi Kasus & Temuan Utama

### 1. Retensi Nasabah Perbankan (Customer Churn)
Analisis terhadap **10.127 nasabah** dengan rasio *churn* keseluruhan sebesar **16,07% (1.627 nasabah)**:
- **Dampak Layanan CS:** Nasabah tanpa keluhan memiliki rasio *churn* **1,75%**, namun melonjak menjadi **100%** pada nasabah yang menghubungi CS hingga **6 kali**.
- **Ketidakaktifan & Utilisasi:** Risiko *churn* memuncak pada bulan ke-3 (**21,48%**) dan bulan ke-4 (**29,89%**), dengan rata-rata utilisasi limit nasabah *churn* (**16,25%**) jauh di bawah nasabah aktif (**29,64%**).
- **Efek Multi-Produk:** Kepemilikan 4–6 produk menekan risiko *churn* hingga **10,50%–12,00%** dibandingkan pemilik 1–2 produk (**25,60%–27,84%**).

### 2. Performa Penjualan Retail (2020–2021)
Analisis terhadap **78.854 transaksi** (**5,59 juta unit** terjual) dengan total pendapatan **Rp152,53 Miliar**:
- **Lonjakan Kuartal IV:** Puncak omzet terjadi pada bulan **November (Rp21,58 Miliar)** dan **Desember (Rp20,91 Miliar)**.
- **Dominasi Pembelian Grosir:** Transaksi grosir ($\ge 12$ pcs) menyerap **>77% volume barang** dengan total omzet **Rp90,08 Miliar**.
- **Produk & Kanal Utama:** Tiga kategori terlaris adalah **Minuman**, **Kosmetik**, dan **Parfum** (~28% omzet), dengan **Toko Kelontong** menyumbang lebih dari **66% total penjualan (Rp101,21 Miliar)**.

---

## Alur Teknis & Tools
1. **Extract & Transform (Power Query):** Pembersihan data, standarisasi tipe data, serta pembuatan kolom segmentasi (*Tier Limit Kredit* dan *Tipe Order*).
2. **Data Modeling & Measures (Power Pivot & DAX):** Penyusunan relasi antar-tabel dan metrik dinamis (*Rasio Churn*, *Rata-rata Utilisasi Kredit*, dan *Rata-rata Nilai Order*).
3. **Data Visualization:** Penyusunan *Pivot Table*, grafik komparatif, serta *Slicer* interaktif untuk eksplorasi data secara *real-time*.
