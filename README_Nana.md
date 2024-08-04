# Capstone-Project-Modul-3
Capstone project modul 3 JCDS Purwadhika - Machine Learning Analisys on Customer Lifetime Value

## Background

Customer lifetime value atau CLV adalah suatu ukuran seberapa berharga suatu customer terhadap perusahaan. Dari nilai tersebut, perusahhan dapat menentukan berapa keuntungan yang didapatkan dari satu penumpang dan biaya yang dikeluarkan untuk memperoleh customer baru atau mempertahankan customer lama. Angka ini cukup penting diketahui oleh suatu perusahaan jika perusahaan ingin secara efektif menargetkan pemasaran kepada pelanggan yang berharga dan bagaimana pelanggan perusahaan tersebut berubah kedepannya.

Salah satu contoh penggunaan analisis CLV terdapat di perusahaan penjual kopi terbesar di Amerika, yaitu starbucks. Analisis yang dilakukan oleh perusahaan menemukan bahwa keniakan 5% tingkat kepuasan suorang customer dapat meningkatkan CLV mereka 25% hingga 95%. Selain itu, Starbucks juga menemukan biaya yang harus dikeluarkan untuk mendapatkan customer baru 6 sampai 7 kali lipat lebih tinggi dari mempertahankan customer yang sudah ada. Dengan memperhatikan hal-hal yang disebutkan sebelumnya, Starbuck mampu memiliki customer dengan CLV hingga 14000 Dollar.

Pada kasus perusahaan asuransi, mengetahui besarnya CLV dapat membantu beberapa kinerja perusahaan, diantaranya :
* Marketing bisa menggunakan informasi CLV untuk menentukan mana customer yang kemungkinan jarang melakukan klaim dan membayar premi yang tinggi. Marketing dapat memilih customer yang menghasilkan keuntungan besar untuk perusahaan,
* customer service bisa menentukan bagaimana metode yang tepat digunakan untuk tiap jenis customernya, sehingga tidak ada biaya yang tinggi digunakan kepada customer yang memiliki nilai CLV yang rendah,
* dan bagian finance dan risk management dapat menghitung bagaimana seorang customer dapat memberikan keuntungan dan langkah yang perlu dilakukan ketika customer pergi.

## Problem Statement

Lifetime value bisa  dihitung berdasarkan data dari sejarah customer bersama perusahaan, dalam konteks perusahaan asuransi bisa dihitung berdasarkan total premi yang dibayarkan dikurang klaim dan biaya oprasional yang dikelurakan oleh perusahaan pada customer tersebut. Menghitung customer lifetime value berdasarkan sejarahnya membutuhkan cukup banyak waktu (menghitung keseluruhan waktu customer bersama perusahaan). Saat perhitungan sudah selesai, strategi bisnis mungkin sudah terlambat diberlakukan. Contohnya pada penawaran perpanjangan asuransi. Diperlukan metode yang dapat memprediksi customer lifetime value.

Dengan memprediksi customer lifetime value perusahaan dapat menuntukan mana customer yang mungkin memiliki value yang tinggi dan mana yang tidak. Perusahaan bisa memfokuskan kegiatan marketing pada customer value yang tinggi sehingga pengeluaran untuk marketing jatuh pada customer yang tinggi, tidak pada customer yang memiliki value yang rendah. Hal ini dapat meningkatkan effesiensi perusahaan, walaupun kegunaan prediksi hanya berguna ketika prediksinya tepat.

## Goals

Pemodelan regresi dapat digunakkan untuk mengetahui prediksi nilai customer lifetime value berdasarkan variabel variabel customer asuransi. Machine learning dapat membantu membuat model tersebut. Pada capstone project modul 3 ini, model untuk mengestimasi berapa Customer Lifetime Value pada customer perusahaan asuransi akan dibuat.

## Analytic Approach

1. Melakukan Explantory Data Analysis (EDA) pada dataset. 
1. Melakukan Feature Engineering pada feature jika dibutuhkan.
1. Melakukan Preprocessing pada dataset.
1. Melakukan Benchmarking pada beberapa model regressi untuk memilih model yang paling tepat untuk dataset.
1. Melakukan Hyperparameter Tuning pada model terpilih untuk mendapatkan hasil error yang lebih rendah.
