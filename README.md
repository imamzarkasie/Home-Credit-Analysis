# Home-Credit-Analysis

# 1- Full Name & Batch
Full Name: Imam Buchori Zarkasie

Batch: RMT-019

# 2 - Deployment Link
(https://huggingface.co/spaces/imamzarkasie/HOME-CREDIT-ANALYSIS)

# 3 - Project Title

**Home Credit Analysis**

# 4 - Project Description

Many people struggle to get loans due to insufficient or non-existent credit histories. And, unfortunately, this population is often taken advantage of by untrustworthy lenders. In this project Home Credit will using some statistical and machine learning methods to make a prediction. The output will be interpreted from some Exploratory Data Analysis and classification prediction model.

# 5 - Conclusion
## 5.1 - Model Analysis

* Model **Random Forest** menghasilkan dugaan yang palig baik dibanding model **Logistic Regression** dari nilai accuracy, precission, recal, dan f1-score juga pemetaannya bisa dilihat pada confussion matrix.

* Berdasarkan dari visualisasi Confusion Matrix - Test Set - **Random Forest** menunjukkan bahwa:

  Ada **24.808** pelanggan yang aktualnya adalah menunggak (0) dan benar-benar terprediksi demikian. **True Negative**

  Ada **868** pelanggan yang aktualnya adalah menunggak (0) tetapi terprediksi sebagai tepat waktu (1). **False Positive**

  Ada **356** pelanggan yang aktualnya adalah tepat waktu (1) tetapi terprediksi sebagai menunggak (0). **False Negative**

  Ada **25.540** pelanggan yang terprediksi tepat waktu (1) dan benar-benar terprediksi demikian. **True Positive**

  Klasifikasi model sudah sangat baik membedakan pembayaran tiap nasabah. Sehingga model ini disimpulkan sebagai **Good Fit**.

  * Terdapat kelemahan pada model ini yaitu: kurang baik untuk memprediksi nasabah yang menunggak dikarenakan data sample didominasi oleh data yang memiliki Target = 0 (Tepat Waktu).

## 5.2 - Overall Analysis

* Ditemukan variabel-variabel yang paling berpengaruh dalam menduga pembayaran nasabah, yaitu:

1.   NAME_EDUCATION_TYPE
2.   OCCUPATION_TYPE
3.   NAME_HOUSING_TYPE
4.   NAME_CONTRACT_TYPE
5.   NAME_INCOME_TYPE
6.   ORGANIZATION_TYPE
7.   OCCUPATION_TYPE
8.   CODE_GENDER
9.   NAME_HOUSING_TYPE
10.  LIVINGAREA_AVG
11.  AMT_GOODS_PRICE
12.  BASEMENTAREA_AVG
13.  FLOORSMIN_AVG
14.  LIVINGAREA_MEDI
15.  FLOORSMAX_MODE
16.  AMT_INCOME_TOTAL
17.  DAYS_EMPLOYED
18.  REGION_RATING_CLIENT_W_CITY

* Jika melihat dari segi bisnis, **jenis tempat tinggal nasabah** didominasi (**88,7%**) oleh nasabah yang sudah memiliki Rumah / Apartemen pribadi (**House /  Apartment**) sebanyak **272.868**, dari kesimpulan ini besar kemungkinan bahwa nasabah memerlukan layanan kredit untuk **kebutuhan rumah tangga** sehingga bisa dilakukan **partnership** dengan produk-produk kebutuhan rumah tangga yang bisa menguntungkan kedua pihak.

* Pengguna kartu kredit didominasi oleh **Gender = FEMALE**. Ini menandakan bahwa customer wanita lebih banyak melakukan pinjaman kartu kredit. Sehingga perlu dilakukan penawaran yang bisa menarik minat nasabah wanita.

* Nasabah yang **menunggak** tidak ditentukan dengan nilai **Pinjaman** atau nilai **Anuitas** karena tetap terdapat nasabah yang menunggak entah dari nilai pinjaman yang rendah/tinggi.




