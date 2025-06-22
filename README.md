# Time Series Forecasting - E-commerce Transactions

## Objective
Melakukan analisis dan forecasting terhadap data transaksi harian dari sebuah platform e-commerce. Tujuan akhir adalah memprediksi jumlah transaksi dan memberikan rekomendasi bisnis berdasarkan pola historis.

## Dataset
Dataset `superstore_train.csv` berisi data pesanan dari tahun 2014–2017, mencakup informasi produk, customer, tanggal transaksi, dan penjualan.

## Workflow
1. Eksplorasi dan pembersihan data
2. Analisis pola tren dan musiman
3. Identifikasi produk dan kota teratas
4. Pembuatan model forecasting:
   - Moving Average
   - ARIMA (1,1,1)
5. Evaluasi model menggunakan MAPE
6. Insight bisnis dan rekomendasi strategi

## Business Insight
- Penjualan meningkat tajam setiap bulan November → momentum promo tahunan
- Produk dengan revenue tinggi cocok untuk bundling premium
- Kota New York, Los Angeles, dan San Francisco mendominasi order dan revenue
- ARIMA menjadi model terbaik dalam memprediksi transaksi harian

## Tools Used
- Python (pandas, numpy, matplotlib, statsmodels, scikit-learn)
- Jupyter Notebook / Google Colab

## Output
Model prediksi transaksi harian 1 bulan ke depan, dilengkapi insight dan rekomendasi berbasis data historis.
