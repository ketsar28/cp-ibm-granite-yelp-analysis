# 🧠 Mengungkap Suara Pelanggan dengan IBM Granite  
## 🎯 Analisis Sentimen & Topik pada Yelp Reviews dengan LLM

![banner](https://img.shields.io/badge/Powered%20By-IBM%20Granite-blue) ![Status](https://img.shields.io/badge/Status-Selesai-brightgreen)  

> Proyek ini dilakukan sebagai bagian dari **Capstone Hacktiv8 x IBM SkillsBuild** dengan fokus pada _Data Classification & Summarization using LLM (IBM Granite)_

---

## 🔍 Project Overview

### 🎯 Tujuan
Memanfaatkan kecerdasan buatan, khususnya **Large Language Model (LLM)** IBM Granite, untuk mengekstraksi *insight* strategis dari data review pelanggan di platform Yelp yang sangat tidak terstruktur.

### 💼 Latar Belakang
Setiap hari, bisnis menerima ribuan ulasan dari pelanggan melalui platform seperti Yelp. Namun, tantangan utama:
- Data berupa teks bebas (unstructured)
- Tidak efisien jika dibaca manual
- Banyak insight penting tersembunyi di dalamnya

> Solusi: Menggunakan AI (LLM) untuk membaca, memahami, dan menganalisis pola sentimen & topik utama dari review pelanggan.

---

## 📁 Raw Dataset

- **Sumber**: Kaggle (Yelp Reviews Public Dataset)  
- **Kolom utama**: `text` (ulasan pelanggan), `stars` (rating asli)
- **Link dataset**: [Download Yelp.csv di sini](https://www.kaggle.com/datasets/yelp-dataset/yelp-dataset)  
- 📦 File dataset juga tersedia di repo ini: `yelp.csv`

---

## 🧪 Analysis Process

### 🛠️ Tools & Teknologi
- Python, Pandas, Matplotlib, Seaborn
- LangChain + [Replicate](https://replicate.com/) (untuk integrasi model LLM IBM Granite)
- Google Colab & Google Drive

### 🔗 Model AI
- Model: `ibm-granite/granite-3.3-8b-instruct`
- Diakses melalui platform **Replicate API**

### 🔄 Alur Analisis:
1. **Pra-pemrosesan**: Bersihkan data ulasan yang kosong
2. **Klasifikasi Sentimen**: Gunakan prompt → Klasifikasi menjadi Positif / Netral / Negatif
3. **Identifikasi Topik**: Tentukan topik utama dari daftar yang sudah ditentukan
4. **Ringkasan Otomatis**: Ringkas ulasan dalam 1-2 kalimat tanpa kehilangan detail penting
5. **Visualisasi**: Grafik distribusi sentimen dan topik
6. **Insight & Rekomendasi Bisnis**

---

## 📊 Insight & Findings

### 📈 Sentimen
- **78% ulasan** bersentimen **positif** → pelanggan puas
- **18% negatif** → dominan membahas kualitas makanan
- Sisanya netral atau tidak terklasifikasi

### 💡 Temuan Menarik
- **Topik "Food Quality"** muncul paling sering, baik dalam ulasan positif maupun negatif → indikator utama persepsi pelanggan
- **Korelasi kuat** antara prediksi sentimen dengan rating bintang → validasi prediksi LLM IBM Granite

---

## 🤖 AI Support Explanation

Model LLM digunakan untuk 3 tugas utama:

| Tugas AI | Penjelasan | Prompt |
|----------|------------|--------|
| 🧭 Sentiment Classification | Mengidentifikasi emosi pelanggan dari teks ulasan | `"Klasifikasikan sentimen ulasan ini sebagai Positive, Neutral, atau Negative"` |
| 🧩 Topic Extraction | Mengelompokkan ulasan ke dalam topik seperti Service, Food Quality, Price, dll. | `"Identifikasi 1-2 topik dari daftar berikut..."` |
| 📝 Summarization | Merangkum ulasan panjang ke dalam kalimat ringkas yang tetap bermakna | `"Ringkas ulasan berikut dalam 1-2 kalimat..."` |

> Semua tugas menggunakan teknik **prompt engineering** dengan pengaturan parameter seperti temperature = 0.3, max_tokens, dan top_k untuk menjaga konsistensi.

---

## ✅ Conclusion & Recommendations

### 🎯 Kesimpulan:
- IBM Granite terbukti efektif dalam membaca dan memahami konteks dari review pelanggan
- Memberikan insight yang relevan, cepat, dan dapat diandalkan untuk strategi bisnis

### 🚀 Rekomendasi:
- Fokus pada **peningkatan kualitas makanan** sebagai area paling sering dikritik
- Gunakan ulasan positif sebagai bahan promosi brand
- Terapkan sistem **monitoring otomatis berbasis AI** untuk feedback berkelanjutan
- Manfaatkan **ringkasan otomatis** untuk laporan manajerial yang lebih cepat dan tajam

---

## 📂 File dalam Repo Ini

| Nama File | Fungsi |
|-----------|--------|
| `AnalisisUlasanProduk_IBM_Granite_Ketsar.ipynb` | Notebook utama berisi seluruh pipeline analisis |
| `yelp.csv` | Dataset ulasan pelanggan dari Yelp |
| `PPT_CP_HACKTIV8_IBM_SENTIMENT ANALYSIS_MUHAMMAD KETSAR ALI ABI WAHID.pptx` | Presentasi final proyek Capstone dalam format PowerPoint |

---

## 🙌 Profil

**Muhammad Ketsar Ali Abi Wahid**  
📫 Email: muhammadketsar2@gmail.com  
🌐 Website: [k-folio-prod.vercel.app](https://k-folio-prod.vercel.app)  
📷 Instagram: [@ketsar.aaw](https://www.instagram.com/ketsar.aaw/)  
🔗 LinkedIn: [@ketsarali](https://www.linkedin.com/in/ketsarali/)  

> Seorang problem solver di dunia Data Science yang fokus pada transformasi data menjadi insight yang berdampak nyata. Selalu siap menghadapi tantangan analitis berikutnya.

---

> Terima kasih telah mengunjungi repositori ini! Jangan lupa ⭐ jika kamu suka dengan project ini 😄
