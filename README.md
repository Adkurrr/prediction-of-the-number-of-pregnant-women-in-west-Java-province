# prediction-of-the-number-of-pregnant-women-in-West-Java-province-using-ANN

- sumber data : https://opendata.jabarprov.go.id/id/dataset/jumlah-ibu-hamil-berdasarkan-kabupatenkota-di-jawa-barat
- Dataset ini berisi data jumlah ibu hamil berdasarkan kabupaten/kota di Provinsi Jawa Barat dari tahun 2016 s.d. 2020.
- Analisis hasil prediksi jumlah ibu hamil tahun 2023 :
1.	Epoch dan Loss: Model neural network dilatih selama 50 epoch (siklus latihan). Setiap epoch menunjukkan satu iterasi melalui keseluruhan dataset pelatihan. Pada setiap epoch, loss (mean squared error) dihitung untuk mengevaluasi sejauh mana prediksi model cocok dengan target yang sebenarnya. Terlihat bahwa loss berkurang seiring dengan peningkatan jumlah epoch, yang menunjukkan model sedang belajar dari data pelatihan.
2.	Mean Squared Error (MSE): Pada akhir pelatihan, model diuji pada data pengujian dan MSE dihitung. MSE merupakan metrik evaluasi yang mengukur rata-rata dari kuadrat selisih antara prediksi model dengan target yang sebenarnya. Semakin kecil nilai MSE, semakin baik kualitas prediksi model. Pada contoh ini, MSE diperoleh sebesar 2,738,273,024.
3.	Prediksi untuk Tahun 2024: Setelah melatih model, kita menggunakan model tersebut untuk memprediksi jumlah ibu hamil pada tahun 2023. Prediksi yang diberikan adalah sekitar 96.10855. Perlu diingat bahwa angka ini harus diinterpretasikan dengan konteks dataset dan pengaturan model yang spesifik.

- kesimpulan : model jaringan saraf tiruan yang dilatih belum menghasilkan prediksi yang akurat untuk jumlah ibu hamil pada tahun 2023. Hal ini dapat dilihat dari nilai MSE yang besar, yaitu sekitar 2,740,507,648.

