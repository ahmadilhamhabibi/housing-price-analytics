# Housing Price Analytics

## Introduction and Background
Properti adalah salah satu kebutuhan dasar manusia. Penentuan harga properti (rumah) memerlukan perhitungan banyak faktor. Memahami faktor-faktor yang memengaruhi harga properti adalah kunci bagi pembeli, penjual, dan investor untuk membuat keputusan yang tepat.
Salah satu masalah yang bisa dijawab adalah:

**“Bagaimana hubungan harga rumah dengan luas area, airconditioning dan furniture status?”**

Untuk menjawab masalah ini, kita dapat melakukan beberapa analisis, seperti:
- Memprediksi harga berdasarkan area
- Memprediksi harga berdasarkan area dan apakah ada AC atau tidak
- Memprediksi harga berdasarkan area dan furnishing status

## Dataset
Data yang digunakan dalam penelitian kali ini berasal dari situs Kaggle, yaitu Housing Prices Datase.

## Statistical Test
1. Apakah harga rata-rata dari properti di area ini lebih dari 6.000.000?
2. Apakah proporsi properti yang memiliki AC (Air Conditioning) lebih dari 50%?
3. Apakah harga rata-rata properti dengan dan tanpa AC berbeda signifikan?
4. Apakah harga rata-rata properti tiap furnishing status berbeda signifikan?

## Regression Model
Setelah melakukan uji statistik, selanjutnya kita bisa melakukan pemodelan dengan linear regression menggunakan prediktor yang sudah kita uji. Pada kesempatan kali ini saya hanya akan menggunakan kolom area, airconditioning, dan furnishingstatus.
1. Prediksi harga berdasarkan area
2. Prediksi harga berdasarkan luas area dan apakah ada AC atau tidak
3. Prediksi harga berdasarkan area dan furnishing status

## Conclusion
**Prediksi harga berdasarkan area.**
Harga berkorelasi positif dengan area. Semakin tinggi (luas) area, harganya juga mengalami kenaikan.
**Prediksi harga berdasarkan area dan apakah ada AC atau tidak.**
Harga berkorelasi positif dengan area dan adanya fasilitas AC. Jika ada AC maka harganya akan semakin naik.
**Prediksi harga berdasarkan area dan furnishing status**
Harga berkorelasi positif dengan area dan furnitured. Rumah yang masih semi-furnitured dan unfurnitured harganya akan semakin murah.

## Recommendation
- Pembeli bisa memprediksi harga rumah berdasarkan area, airconditioning, dan furnishing status. Agar bisa membeli properti dengan harga yang sesuai.
- Penjual juga bisa menentukan harga yang adil bagi penjual dan pembeli agar sama-sama untung.
- Melakukan penelitian lebih lanjut untuk melihat hubungan harga dengan fitur-fitur lainnya.

## Reference
- Statistic for Business - Pacmann.io
- Housing Prices Dataset - Kaggle
