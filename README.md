# 🌍 Prediksi Strategis Kunjungan Wisatawan Mancanegara ke Indonesia 🇮🇩

Proyek ini adalah aplikasi berbasis C++ untuk **prediksi jumlah total wisatawan mancanegara** ke Indonesia menggunakan **regresi linear berganda**. 
Aplikasi ini juga menghitung akurasi prediksi menggunakan **MAPE (Mean Absolute Percentage Error)**.

---

## 📈 Deskripsi Singkat

Program ini memanfaatkan **3 variabel independen**:
- **X1**: Jumlah wisatawan dari pintu masuk udara ✈️  
- **X2**: Jumlah wisatawan dari pintu masuk darat 🚗  
- **X3**: Jumlah wisatawan dari pintu masuk laut 🚢  

dan satu variabel dependen:
- **Y**: Total jumlah wisatawan mancanegara

Model persamaan regresi dibentuk secara manual melalui perhitungan **rata-rata**, **deviasi**, dan **penyelesaian sistem persamaan** menggunakan **rumus regresi linear multivariat**.

---

## 🧪 Fitur

- Input jumlah data berdasarkan bulan (X1, X2, X3, dan Y)
- Hitung nilai:
  - Intercept (A)
  - Slope B1, B2, B3
- Cetak persamaan regresi linear:  
  `Y = A + B1*X1 + B2*X2 + B3*X3`
- Prediksi jumlah wisatawan untuk bulan berikutnya
- Hitung tingkat akurasi menggunakan **MAPE**

---

## 📌 Contoh Output

```text
Persamaan regresi: Y = 500.32 + 1.25 * X1 + 0.98 * X2 + 1.14 * X3
Prediksi Y: 15789.22
MAPE: 4.52%
