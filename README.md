# Rakamin Final Project Batch 17 - DataRider
## Dataset : Payment Default Prediction
## Nama Anggota :
<ol>
 <li>Tri Setiawan</li>
 <li>Ulva Dewiyanti</li>
 <li>Cristanto</li>
 <li>Steven Benny</li>
</ol>

## Problem Statement
   
Memprediksi secara akurat pelanggan mana yang paling mungkin gagal bayar merupakan peluang bisnis yang signifikan bagi semua bank. Dimana kartu kredit merupakan kartu bank yang paling umum di Taiwan, karena memberikan dampak baik pada konsumen dan bank.

Pada dataset ini juga menginformasikan keputusan bank tentang kriteria untuk menyetujui aplikasi kartu kredit dan juga memutuskan batas kredit apa yang harus diberikan.

Kumpulan data ini berisi informasi tentang pembayaran default, faktor demografis, data kredit, riwayat pembayaran, dan laporan tagihan klien kartu kredit di Taiwan dari April 2005 hingga September 2005.

Dengan menggunakan informasi yang diberikan, tim kami akan memprediksi kemungkinan pelanggan gagal bayar di bulan berikutnya.

## Goals
Mengurangi default rate

## Objective
Membuat model yang dapat memprediksi gagal bayar pada bulan berikutnya.

## Summary :
<ul>
 <li>STAGE 1 :</li>
</ul>
<ol>
  <li>Menentukan untuk memilih mengurangi default rate pada goals</li>
  <li>Menentukan bisnis metrics (support) untuk default rate</li>
  <li>Menjabarkan insight setiap variable untuk explanatory</li>
  <li>Mengexplore masing masing variabel</li>
  <li>Menentukan apakah insightnya relate dengan default ratenya</li>
 </ol>
 
<ul>
 <li>STAGE 2 :</li>
</ul>
<ol>
  <li>Menentukan nilai yang belum terdefinisi</li>
  <li>Menentukan bahwa datanya termasuk imbalance</li>
  <li>Dari hasil yang didapat pada proses EDA dapat menambahkan insight</li>
 </ol>
 
 <ul>
  <li>STAGE 3 :</li>
 </ul>
 <ol>
   <li>Memilih AUC sebagai metric utama, dan Precision serta Recall sebagai secondary metric</li>
   <li>Memilih model prediksi yang tepat yakni dari 4 Nilai metrik evaluasi dengan AUC terbesar, dipilih melalui metrix XGBoost yang telah dilakukan hyperparameter tuning yang menunjukkan AUC pada train sebesar 0.87 dan AUC pada test 0.85</li>
  </ol>
