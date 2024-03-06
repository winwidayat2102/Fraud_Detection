# FRAUD Detection Transaksi Keuangan pada Perbankan
Dalam era globalisasi dan digitalisasi, sektor keuangan, khususnya perbankan, menjadi lebih rentan terhadap berbagai risiko, termasuk penipuan keuangan. 
Penipuan keuangan dapat merugikan perbankan dan nasabahnya, menyebabkan kerugian finansial yang signifikan dan merusak reputasi lembaga keuangan. Oleh karena itu, 
deteksi transaksi keuangan yang terindikasi fraud menjadi suatu kebutuhan mendesak bagi lembaga perbankan guna menjaga integritas sistem keuangan dan melindungi 
kepentingan nasabah.
#### Link dataset : https://www.kaggle.com/datasets/gopalmahadevan/fraud-detection-example


![image](https://github.com/winwidayat2102/Fraud_Detection/assets/153416421/f9e846ad-7a41-42f2-bdb8-1cc5bf1eac60)


![image](https://github.com/winwidayat2102/Fraud_Detection/assets/153416421/2581ad28-b41c-4a28-aabb-e51059e22cfb)


![image](https://github.com/winwidayat2102/Fraud_Detection/assets/153416421/0465644b-64f1-4e30-955d-52b6e4b76f5f)



![image](https://github.com/winwidayat2102/Fraud_Detection/assets/153416421/3228aaff-76f5-47f8-8de4-8cadb25279a1)
#### Target variabel sangat tidak seimbang (imbalance) antara kelas non-Fraud dan Fraud, pada kasus ini  metrik evaluasi yg digunakan yaitu F1-score, karena F1-score memberikan gambaran yang lebih baik tentang kinerja model di tengah ketidakseimbangan, disamping itu F1-score mengambil keseimbangan nilai rata-rata dari Precision dan Recall, dan juga F1-score dapat mengidentifikasi model yang baik secara keseluruhan dalam menangani False Positives dan False Negatives


![image](https://github.com/winwidayat2102/Fraud_Detection/assets/153416421/6d9cdc07-4a5b-4a5c-b333-06434990decf)
![image](https://github.com/winwidayat2102/Fraud_Detection/assets/153416421/cf6bd24a-f485-4a1f-a6e1-79550b39d9c3)
#### Dari ketiga model yg dicoba pemodelannya, model XGBoost menghasilkan F1-score tertinggi dgn 83%, Hasil F1-score 83% --> menggambarkan keseimbangan rata-rata dari precision sebesar 94% dan recall sebesar 75%, disini model dapat dikatakan menunjukkan tingkat ketelitian yg tinggi dalam memprediksi transaksi yg terindikasi Fraud tanpa menghasilkan terlalu banyak kesalahan dalam memprediksi transaksi yg Fraud, dan model cukup baik dalam mendeteksi semua transaksi yg sebenarnya terindikasi Fraud tanpa terlalu banyak melewatkan transaksi Fraud yg seharusnya terdeteksi. 

![image](https://github.com/winwidayat2102/Fraud_Detection/assets/153416421/745e9b48-1ba7-4b6e-97e3-eaad33b60d14)
![image](https://github.com/winwidayat2102/Fraud_Detection/assets/153416421/c4a5d2f7-a16b-4b7b-a9cd-9ec78350f731)
#### Setelah dilakukan Hyperparameter Tuning dgn GridSearchCV, performa model meningkat menjadi 86%, model dapat dikatakan semakin memperkecil terjadinya false positive dan false negative.


