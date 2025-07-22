# **Analisis Klaster dengan Metode K-Means** 📊🤖

## **Deskripsi Proyek** 💡
Proyek ini bertujuan untuk melakukan **analisis klaster** menggunakan metode **K-Means** pada dataset **Spotify**, untuk mengelompokkan musik berdasarkan **durasi** dan **kepopuleran**. Metode ini membantu untuk mengidentifikasi pola dalam data musik dan memberikan wawasan lebih lanjut tentang karakteristik musik berdasarkan durasi dan popularitasnya.

---

## **Langkah-langkah Proyek** 📝

1. **Persiapan Data** 📂  
   Menghubungkan ke **Google Drive** dan memuat dataset Spotify yang akan dianalisis.

2. **Visualisasi Data** 📊  
   Membuat plot untuk menggambarkan distribusi data dan melihat pola yang ada.

3. **Normalisasi Data** 🔄  
   Menormalisasi data agar semua fitur berada pada skala yang seragam.

4. **Metode Elbow** 🦵  
   Menentukan jumlah cluster yang optimal menggunakan **Metode Elbow** untuk analisis inertia.

5. **K-Means Clustering** 🔥  
   Mengaplikasikan **K-Means** untuk mengelompokkan data berdasarkan durasi dan kepopuleran, serta memberikan label pada setiap data.

---

## **Hasil Analisis** 🔍

Setelah menerapkan **K-Means**, ditemukan **3 cluster** musik berdasarkan durasi dan kepopulerannya:

- **Cluster 0** (Durasi 2-5 menit):  
  Musik yang memiliki durasi paling lama, dengan tingkat kepopuleran yang bervariasi dari populer hingga tidak populer.
  
- **Cluster 1** (Durasi <=1.5 menit):  
  Musik dengan durasi sangat singkat dan cenderung memiliki kepopuleran di tengah, namun jumlahnya sedikit.

- **Cluster 2** (Durasi 1.5-2.5 menit):  
  Musik yang lebih populer dengan durasi menengah dan kepopuleran yang lebih tinggi dibandingkan cluster lainnya.

---

## **Kesimpulan** 📝

- **Kesulitan dalam Clustering**: Beberapa variabel dalam data tidak dapat dikelompokkan dengan baik, terlihat dari titik-titik yang saling bertumpukan pada plot, menunjukkan data yang terlalu beragam.
- **Data Unik**: Variabel dengan nilai unik atau distribusi data yang tidak seragam cenderung gagal dalam proses klastering.
- **Model Kurang Optimal**: Beberapa cluster tidak terbentuk dengan baik karena model yang tidak cukup optimal untuk menangani data kompleks.

---

## **Prasyarat** ⚙️

- Python 3.x
- **Library yang dibutuhkan**:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `sklearn`

---

## **Instalasi** 💻

Untuk menginstal semua dependensi, gunakan pip:

```bash
pip install numpy pandas matplotlib scikit-learn
