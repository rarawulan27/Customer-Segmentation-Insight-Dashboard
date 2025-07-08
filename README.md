# 📊 Customer Segmentation Insight Dashboard

Dashboard ini saya bangun menggunakan **Power BI** dengan data dari **Data Public Big Query (The Look E-commerce)**, yang diolah melalui SQL untuk mendukung analisis bisnis yang lebih strategis dan berbasis data. Fokus utama dari analisis ini adalah melihat **performa penjualan**, **perilaku pelanggan**, dan **product funnel**.

---

## 🔍 Insight Utama

- Jumlah cancel profit mencapai **468.33K** dengan **Average Order Value (AOV)** sebesar **84.84**.
- Total pesanan berstatus **Cancelled** mencapai **8.000 orders/tahun 2024**, disusul dengan jumlah **Returned** yang mencapai **5.000 orders/tahun 2024**.
- Breakdown cancel berdasarkan kategori dan produk menunjukkan bahwa beberapa produk memiliki tingkat pembatalan lebih tinggi dari pengiriman.
- Analisis funnel mengidentifikasi konversi tiap tahap dan potensi bottleneck dalam proses transaksi.
- Visualisasi top product performance meng-highlight produk unggulan & produk bermasalah.

---

## 🧭 User Funnel

### 1️⃣ Registered → Ordered (80%)
✅ **Positif, funnel awal efektif**
- UX awal (onboarding, homepage) bagus
- Produk/jasa menarik bagi first-timer
- Kemungkinan ada promo user baru

---

### 2️⃣ Ordered → Processed (28.15%)
⚠️ **Red Flag**
- Banyak order dibatalkan
- Order tertunda hingga tidak tercatat
- Masalah fulfillment/inventory

---

### 3️⃣ Processed → Shipped (144.3%)
⚠️ **Data Quality Alert**
- Ada lonjakan dari Ordered langsung ke Shipped
- Status Processed kemungkinan tidak lengkap
- Kemungkinan split orders

---

## 🧠 Behavior Sebelum Cancelled Orders

Analisis ini bertujuan mengetahui:
1. Apakah mereka cancel berkali-kali?  
2. Kapan (jam/hari) cancel terjadi?  
3. Dari mana asal user? (traffic source)  
4. Produk/kategori paling sering dicancel?

> Sepanjang 2024 terdapat **8.367 orders**, dengan **4.899 cancelled (~55%)** dan tidak kembali melakukan pembelian.

---

## 🕒 Waktu Cancel Customer

- **Senin jam 13.00** (171 cancel)
- **Selasa jam 07.00 & 05.00** (169 & 168)
- **Minggu jam 08.00 & 07.00** (163 & 161)

📌 **Insight:**  
Puncak pembatalan terjadi **pagi–siang hari kerja** & **akhir pekan**. Kemungkinan customer membandingkan produk atau berubah pikiran sebelum pengiriman.

---

## 🌐 Traffic Source by Cancelled Orders

- Cancel rate sebesar **70.36%** pada user dengan **4 orders & 3 canceled**
- Indikasi adanya **pain point** dalam proses pembelian
- User berminat tapi terhambat sistem atau kejelasan proses

🛠 **Rekomendasi:**  
Tingkatkan **trust & clarity** untuk konversi yang lebih baik.

---

## 🛍️ Canceled by Category & Brand

- Kategori **Intimates** & **Jeans** mendominasi pembatalan
- Tidak hanya karena volume pesanan tinggi, tapi karena faktor kategori
- Produk dari brand besar (**Wrangler**, **Calvin Klein**) juga tetap dibatalkan

📌 **Insight:**  
Reputasi brand **tidak cukup** — perlu perbaikan pada deskripsi produk & UX saat checkout.

---

## 🖥️ Fitur Dashboard

- Interaktif & responsif
- Filter status order (Cancelled, Shipped, Returned, dll)
- Filter berdasarkan tahun
- Dirancang untuk membantu pemangku kepentingan dalam eksplorasi data dan pengambilan keputusan

---

## 📌 Catatan

> Semua analisis dilakukan untuk meningkatkan efektivitas strategi bisnis berbasis data, dengan fokus pada perbaikan pengalaman pelanggan dan efisiensi proses.

---
