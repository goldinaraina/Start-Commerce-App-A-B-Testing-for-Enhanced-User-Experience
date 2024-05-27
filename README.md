# Start-Commerce App: A/B Testing for Enhanced User Experience

## Background Problem

Tim Data Start-Commerce mengalami penurunan konversi situs web sebesar 10%, yang menjadi masalah utama manajemen perusahaan. Situs web merupakan jembatan utama antara pelanggan dan mitra, sehingga menjadi metrik penting sebagai penentu keberhasilan perusahaan karena revenue diperoleh dari tingkat transaksi yang terjadi.

Melalui survei pengguna App, Tim Data menemukan bahwa pengguna tidak nyaman dengan tampilan ukuran ikon menu yang terlalu kecil dan banyak. Hal ini menyebabkan kesalahan klik dan pengguna merasa frustasi dengan keterlambatan dalam memuat halaman.

Untuk memperbaiki masalah ini, manajemen menugaskan Tim Data untuk melakukan perbandingan antara desain aplikasi sebelumnya dan versi terbaru melalui A/B testing. Tujuannya adalah untuk mengidentifikasi perbedaan utama dan menentukan perubahan yang diperlukan untuk meningkatkan kinerja tampilan aplikasi, dengan fokus pada tata letak, warna, ukuran tombol, dan navigasi.

## Objective

1. Menentukan jumlah sampel dari data yang diperlukan untuk testing pada App.
2. Mengolah data untuk menentukan conversion rate App versi terbaik.
3. Memberikan rekomendasi manajemen perusahaan berdasarkan testing yang telah dilakukan.

## Tujuan

Meningkatkan metrik conversion rate menjadi 20% melalui A/B testing.

## Metodologi

### Menentukan Ukuran Sampel

Testing ini memerlukan 199 sampel pada setiap kelompok untuk melanjutkan A/B testing dengan tingkat signifikansi 95% dan daya uji (power) 80% untuk mendeteksi perbedaan conversion rate antara kedua kelompok.

### Hasil Analisis Statistik

- **Uji F**: Menunjukkan terdapat perbedaan yang signifikan antara kedua kelompok, dengan F-Statistic sebesar 70.973 dan p-value sebesar 0.00.
- **Uji t**: Menunjukkan ada perbedaan yang signifikan antara rata-rata conversion rate kedua kelompok, dengan p-value sebesar 0.00 dan nilai t-statistic sebesar -8.425.
- **Analisis Bland-Altman**: Mean difference (rata-rata selisih) antara observasi pada kelompok testing dan kelompok kontrol adalah 0.29. Standard deviation of difference (standar deviasi dari selisih) sebesar 0.47, menunjukkan variasi yang signifikan dalam perbedaan antara kedua kelompok. Agreement limit yang dihitung sebagai 1.96 kali standard deviation of difference sebesar 0.933, menunjukkan bahwa hasilnya dapat diterima.
- **Confidence Interval**: Menunjukkan bahwa perbedaan rerata antara sample control dan testing berada dalam rentang 0.2245 hingga 0.3612 pada tingkat signifikansi 0.05 (95%). Ini menandakan bahwa terjadi kenaikan sebesar 32% secara statistik berdasarkan data sampel yang digunakan pada A/B testing aplikasi Start-Commerce.

## Kesimpulan

Berdasarkan hasil analisis, dapat disimpulkan bahwa perlakuan yang diberikan pada kelompok testing memiliki dampak yang signifikan terhadap tingkat konversi dibandingkan dengan kelompok kontrol.

## Rekomendasi

1. **Lanjutkan A/B Testing**: Dengan 199 sampel pada setiap kelompok, lanjutkan A/B testing untuk memvalidasi efektivitas perubahan.
2. **Terapkan Perubahan**: Perlakuan pada kelompok testing memiliki dampak yang signifikan terhadap tingkat konversi. Oleh karena itu, dianjurkan untuk menerapkan perubahan atau fitur yang diuji pada kelompok testing secara luas dalam aplikasi Start-Commerce.
3. **Pemantauan Kinerja**: Pantau kinerja aplikasi secara berkala untuk memastikan bahwa peningkatan dalam tingkat konversi dapat dipertahankan dan ditingkatkan seiring waktu.

---

Harapannya, dengan mengikuti rekomendasi ini, perusahaan dapat mengatasi masalah penurunan konversi pada aplikasi Start-Commerce dan meningkatkan kepuasan pengguna serta kinerja aplikasi.
