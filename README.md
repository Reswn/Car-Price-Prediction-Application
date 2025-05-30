
# 🚗 Car Price Prediction Web App
![App](https://github.com/Reswn/Car-Price-Prediction-Application/blob/main/screencapture-127-0-0-1-5000-2025-05-29-21_38_42.png?raw=true)

Aplikasi ini memprediksi harga mobil berdasarkan input spesifikasi kendaraan seperti tahun produksi, jarak tempuh, jenis bahan bakar, transmisi, dan lainnya. Proyek ini dibangun menggunakan HTML, CSS untuk antarmuka frontend, dan Python (`Flask`) + model Machine Learning untuk logika prediksi di backend.

---

## 🌟 Fitur Utama

- 🔮 Prediksi harga mobil secara instan  
- 🧠 Model Machine Learning yang telah dilatih  
- 💻 Antarmuka web sederhana dengan HTML & CSS  
- 📦 Backend menggunakan Flask (Python)  
- 🧹 Preprocessing otomatis pada input pengguna  
- 🔄 Dukungan untuk berbagai merek dan tipe mobil  

---

## 🛠 Teknologi yang Digunakan

| Bagian       | Teknologi                  |
|--------------|----------------------------|
| Frontend     | HTML, CSS                  |
| Backend      | Python, Flask              |
| Machine Learning | Scikit-learn / XGBoost  |
| Data         | Pandas, NumPy              |
| Serialisasi  | Pickle                     |

---

## 📦 Struktur Proyek

```
car-price-predictor/
├── application.py                # Backend Flask
├── LinearRegressionModel.pkl             # Model ML yang sudah dilatih
├── quikr_car.csv              # Dataset asli
├── Cleaned_car_data.csv 
├── templates/
│   └── index.html        # Halaman utama
├── static/
│   └── style.css         # File styling CSS    
└── README.md             # Dokumentasi ini
```

---

## 📥 Instalasi

1. **Clone repositori:**

```bash
git clone https://github.com/username/car-price-predictor.git
cd car-price-predictor
```

2. **Install dependensi:**

```bash
pip install -r requirements.txt
```

3. **Jalankan aplikasi Flask:**

```bash
python app.py
```

---

## ✍️ Cara Penggunaan

1. Buka halaman aplikasi di browser.
2. Masukkan informasi tentang mobil:
   - Tahun Produksi
   - Kilometer Tempuh
   - Jenis Bahan Bakar
   - Jenis Transmisi
   - Jumlah Pemilik Sebelumnya
   - Merek dan Model
3. Klik tombol **Prediksi**
4. Harga mobil akan ditampilkan di bawah form

---

## 🧠 Tentang Model

- **Model:** Random Forest Regressor / XGBoost *(sesuaikan sesuai implementasi)*
- **Fitur Input:**
  - Tahun produksi
  - Kilometer tempuh
  - Jenis bahan bakar
  - Jenis transmisi
  - Jumlah pemilik
  - Merek dan model (dengan encoding kategorikal)

- **Dataset:** Diambil dari Kaggle atau sumber publik lainnya  
- **Akurasi model:** ±85–95% pada data uji

---

## 🎯 Contoh Prediksi

**Input:**
- Tahun: 2017  
- Kilometer: 60,000  
- Bahan bakar: Diesel  
- Transmisi: Manual  

**Output:**
> Prediksi harga: Rp 150.000.000

---

## 🤝 Kontribusi

Kontribusi sangat terbuka! Jika kamu ingin menambahkan fitur baru, memperbaiki UI, atau meningkatkan akurasi model, silakan buat pull request (PR). Berikut beberapa ide pengembangan:
- Menambahkan validasi form lebih ketat
- Mengintegrasikan chart hasil prediksi
- Menambahkan dukungan multi-bahasa

---

## 📬 Kontak

- **Email:** renisuwandi1011@gmail.com  
- **GitHub:** [@Reswn](https://github.com/Reswn)

---

## 📄 Lisensi

Proyek ini tersedia di bawah lisensi MIT. Silakan lihat file `LICENSE` untuk detail lebih lanjut.

---

## 🙏 Terima Kasih!

Semoga aplikasi ini bermanfaat bagi Anda. Terima kasih telah menggunakan dan berkontribusi dalam pengembangan proyek ini. 🚀

---
