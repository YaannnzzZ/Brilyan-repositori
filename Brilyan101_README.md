📊 Prediksi Penjualan Pertalite Menggunakan LSTM (Time Series Forecasting)

Proyek ini bertujuan untuk memprediksi jumlah penjualan bahan bakar jenis Pertalite di wilayah DKI Jakarta selama 3 bulan ke depan menggunakan metode Long Short-Term Memory (LSTM)
salah satu model deep learning yang bagus dalam memproses data deret waktu (time series).

📁 Dataset
- Sumber: [Satu Data Indonesia](https://katalog.satudata.go.id/dataset/?tags=BBM)
- Tahun: 2016
- Fitur penting: Jenis bahan bakar, jumlah penjualan per bulan, lokasi SPBU
- Jenis data: Public dataset (.csv)

⚙️ Tools dan Library
- Python (Google Colab)
- `pandas`, `numpy` untuk data wrangling
- `matplotlib`, `seaborn` untuk visualisasi
- `scikit-learn` untuk normalisasi dan evaluasi
- `Keras (TensorFlow)` untuk membangun model LSTM

🔄 Alur Proyek

1. **Eksplorasi dan Pembersihan Data**
   - Konversi tanggal
   - Seleksi fitur penjualan Pertalite

2. **Visualisasi Tren**
   - Melihat pola musiman konsumsi BBM

3. **Preprocessing**
   - Resampling data bulanan
   - Normalisasi (MinMaxScaler)
   - Sequence generation untuk LSTM

4. **Modeling**
   - Arsitektur LSTM dengan 64 unit
   - Pelatihan model selama 100 epoch

5. **Prediksi**
   - Forecast penjualan 3 bulan ke depan
   - Evaluasi model dengan MAE dan RMSE

📈 Hasil

Model LSTM dapat memprediksi pola musiman konsumsi Pertalite dengan cukup akurat. Grafik di bawah menunjukkan perbandingan antara data aktual dan prediksi:

![image](https://github.com/user-attachments/assets/1674c256-a4ec-442a-8084-9379a29d5b92)

📌 Insight

- Pola konsumsi BBM memiliki tren musiman
- Model LSTM efektif untuk deret waktu yang kompleks
- Forecasting seperti ini dapat bermanfaat untuk perencanaan distribusi energi

## 🔗 Link

- 📎 Dataset: [katalog.satudata.go.id](https://katalog.satudata.go.id/dataset/?tags=BBM)
- 📓 Colab: https://colab.research.google.com/drive/1DOPqa414TtouougxR2G5dmymWIUu6_Ci?usp=sharing 
- 📬 Saya di LinkedIn: https://www.linkedin.com/in/brilyan-harwan-732000300/ 


## 🙋‍♂️ Tentang Saya

Saya adalah mahasiswa Informatika yang fokus dalam bidang Data Science, Machine Learning, dan Forecasting. Proyek ini saya buat sebagai bentuk pembelajaran serta portofolio yang ingin saya kembangkan lebih lanjut — khususnya di industri energi seperti Pertamina.

## 📫 Kontak

📧 Email: brilyan@students.amikom.ac.id 
🔗 LinkedIn: https://www.linkedin.com/in/brilyan-harwan-732000300/ 


🚀 Feel free to fork, explore, or give feedback on this project!
