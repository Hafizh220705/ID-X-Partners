# Final Project - Data Science Internship (ID/X Partners)

## 📌 **Deskripsi Proyek**
Tugas akhir ini merupakan bagian dari **internship Data Scientist** di **ID/X Partners**. Dalam proyek ini, saya membangun **model prediksi credit risk** menggunakan dataset yang berisi informasi tentang **pinjaman yang diterima dan yang ditolak**.

Model yang dikembangkan diimplementasikan menggunakan bahasa pemrograman **Python**, dengan pendekatan **end-to-end solution** yang mencakup **data preprocessing, eksplorasi data, pemodelan, evaluasi, dan visualisasi hasil**.

## 📂 **Struktur Proyek**

📁 **[Nama Lengkap]_VIX_IDX_Partners/**
- 📜 `final_project.ipynb` - Notebook berisi seluruh proses analisis dan pemodelan.
- 📜 `main.py` - File Python untuk menjalankan pipeline model.
- 📜 `data.csv` - Dataset utama yang digunakan dalam analisis.
- 📜 `data_dictionary.xlsx` - Penjelasan tentang setiap kolom dalam dataset.
- 📜 `infografis.pdf` - Media visual untuk presentasi end-to-end solution.

## 🛠 **Teknologi yang Digunakan**
- **Python** (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, XGBoost)
- **Machine Learning** (Random Forest, Logistic Regression, Decision Tree, Gradient Boosting, KNN)
- **Google Colab / Jupyter Notebook**

## 🔍 **Tahapan Pengerjaan**
1. **Pemahaman Dataset** - Menganalisis data dan memahami fitur yang tersedia.
2. **Preprocessing Data** - Membersihkan data, menangani missing values, dan encoding variabel kategorikal.
3. **Eksplorasi Data** - Melakukan visualisasi untuk memahami pola dalam data.
4. **Pemodelan** - Menggunakan beberapa algoritma Machine Learning dan memilih model terbaik.
5. **Evaluasi Model** - Mengukur performa model menggunakan metrik seperti **accuracy, precision, recall, dan f1-score**.
6. **Pembuatan Laporan** - Menyusun hasil analisis ke dalam media presentasi yang informatif.

## 📊 **Hasil dan Kesimpulan**
Dari berbagai model yang diuji, **XGBoost Classifier** dipilih sebagai model terbaik berdasarkan akurasi dan performanya. Fitur yang paling berpengaruh dalam prediksi credit risk adalah:
- `recoveries` - Indikator apakah ada rencana pembayaran untuk pinjaman.
- `pymnt_time` - Selisih bulan antara `last_pymnt_d` dan `next_pymnt_d`.
- `out_prncp` - Sisa pokok pinjaman yang belum dibayar.
- `total_rec_late_fee` - Denda keterlambatan yang telah diterima.
- `term` - Lama pinjaman dalam bulan (36 atau 60 bulan).
- `initial_list_status_f` - Status awal listing pinjaman (Whole atau Fractional).
- `int_rate` - Tingkat bunga pinjaman.

## 🚀 **Cara Menjalankan Proyek**
1. Clone repository ini:
   ```bash
   git clone https://github.com/username/repo-name.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Jalankan Notebook atau file Python:
   ```bash
   jupyter notebook final_project.ipynb
   ```
   atau
   ```bash
   python main.py
   ```

## 📢 **Kontribusi**
Jika ingin memberikan saran atau kontribusi, silakan lakukan **pull request** atau hubungi saya melalui email/LinkedIn.

## 📜 **Lisensi**
Proyek ini dirilis di bawah lisensi **MIT** - Bebas digunakan dan dimodifikasi dengan mencantumkan kredit.

---

✍ **Dibuat oleh:** [Nama Lengkap]  
📅 **Internship Data Scientist - ID/X Partners**

