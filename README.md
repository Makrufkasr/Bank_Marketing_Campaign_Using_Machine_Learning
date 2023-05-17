# Bank_Marketing_Campaign_Using_Machine_Learning
![633e2cf1994d4d44f937f3ba_marketing campaign 2](https://github.com/Makrufkasr/Bank_Marketing_Campaign_Using_Machine_Learning/assets/109516688/7a3de546-6c5c-40f0-8b51-63b4cc0ec04e)

Project ini berangkat dari sebuah masalah bisnis yaitu conversion rate nasabah yang subscribe deposito hanya 47,4% sehingga tujuan dari project ini adalah **memprediksi conversion rate nasabah yang subscribe deposito dan memberikan rekomendasi target nasabah serta metode pelaksanaan campaign yang efektif agar dapat meningkatkan conversion rate**

Langkah pre-processing data yang digunakan adalah
1. train-test split sebelum melakukan Exploratory Data Analysis,
2. Mengubah feature categorical menjadi numerical dengan metode rank encoding dan one hot encoding 
3. Memilih feature berdasarkan heatmap correlation. 
4. Setelah itu, model yang dipilih adalah random forest karna memiliki precision paling tinggi diantara beberapa model yang sudah dicoba pada project ini. Nilai precision score adalah 78,3%, yang berarti model mampu menangkap 78,3% nasabah yang sebenarnya subscribe deposito diantara semua nasabah yang diprediksi subscribe deposito, dengan kata lain conversion rate meningkat menjadi 78,3%. 
