# Visualization Project Pacman - Analisis Eksploratif Pemain dan Tim Esport :  Distribusi Negara, Pendapatan Tertinggi, Genre Game, dan Partisipasi Turnamen

## **Background Problems**
Industri esports telah menjadi salah satu industri yang paling berkembang pesat dalam beberapa tahun terakhir. 
Dalam ekosistem ini, pemain dari berbagai negara berkompetisi dalam turnamen dan kompetisi global, sementara tim esports juga memainkan peran penting dalam dinamika industri ini. 
Untuk memahami lebih dalam tentang dinamika di balik industri ini, penting untuk menganalisis data pemain esports dan tim esports dengan lebih rinci. 
Analisis data pemain esports meliputi pemahaman tentang distribusi pemain berdasarkan negara asal, pemain dengan pendapatan tertinggi, dan genre game yang paling banyak dimainkan oleh mereka. 
Di sisi lain, analisis tim esports memerlukan pemahaman tentang partisipasi mereka dalam berbagai game, pendapatan tertinggi yang diperoleh oleh beberapa tim, dan jumlah turnamen yang diikuti oleh mereka.

## **Objectives**
- Objective Data Player
1. Mengetahui distribusi pemain esports dari beberapa negara yang berpartisipasi dalam industri ini.
2. Menganalisis beberapa pemain yang memiliki pendapatan tertinggi dalam industri esports.
3. Mengidentifikasi genre game yang paling sering dimainkan oleh para pemain esports.

- Objective Data Team
1. Mengetahui distribusi game dalam kegiatan turnamen pada industri esports.
2. Menganalisis beberapa tim dengan pendapatan tertinggi dalam industri esports.
3. Melihat perbandingan jumlah turnamen yang diikuti oleh beberapa tim esports.

## **Goals**
Tujuan dari proyek ini adalah untuk memahami distribusi geografis pemain esports dari berbagai negara, menganalisis pemain dengan pendapatan tertinggi, serta mengidentifikasi genre game yang paling sering dimainkan. 
Dari sisi data tim, kita ingin memahami distribusi game yang diikuti oleh tim esports, menganalisis tim dengan pendapatan tertinggi, dan melihat perbandingan jumlah turnamen yang diikuti oleh tim.
Dengan mencapai tujuan-tujuan ini, kita dapat memperoleh insight yang lebih mendalam tentang dinamika industri esports.

## **Data Set**
### Dataset 1 : highest_earning_players.csv
Ini adalah dataset yang berisi informasi tentang pemain esports, Kolom-kolom dalam dataset ini adalah sebagai berikut:

* `PlayerId` : ID unik untuk setiap pemain.
* `NameFirst` : Nama depan pemain.
* `NameLast` : Nama belakang pemain.
* `CurrentHandle` : Nama pengguna atau alias saat ini yang digunakan oleh pemain.
* `CountryCode` : Kode negara asal pemain.
* `TotalUSDPrize` : Total hadiah dalam dolar AS yang diperoleh oleh pemain.
* `Game` : Nama game yang dimainkan oleh pemain.
* `Genre` : Genre dari game yang dimainkan oleh pemain.

### Dataset 2 : highest_earning_teams.csv
Ini adalah dataset yang berisi informasi tentang tim esports, Kolom-kolom dalam dataset ini adalah sebagai berikut :

* `TeamId` : ID unik untuk setiap tim.
* `TeamName` : Nama tim esports.
* `TotalUSDPrize` : Total hadiah dalam dolar AS yang diperoleh oleh tim.
* `TotalTournaments` : Jumlah total turnamen yang diikuti oleh tim.
* `Game` : Nama game yang dimainkan oleh tim.
* `Genre` : Genre dari game yang dimainkan oleh tim.

## **Tahapan Pengerjaan**
* Mencari Dataset di situs `kaggle.com`
* Melakukan cleansing dataset yang meliputi
  - Identifikasi Duplikat
  - Identifikasi Missing Value
  - Identifikasi Outlier
  - Handling Outlier
  - Identifikasi Inkonsistensi
* Menyimpan data yang sudah di cleansing
* Membuat visualisasi data menggunakan aplikasi `tableau`
* Membuat Dashboard
* Melakukan analisis dari visualisasi yang telah dibuat untuk mendapatkan insight dan rekomendasi

## **Deskripsi File**
* Data `highest_earning_players.csv` merupakan dataset yang digunakan untuk cleansing data.
* Data `highest_earning_teams.csv` merupakan dataset yang digunakan untuk cleansing data.
* Data `filtered_dataplayer.csv` merupakan dataset yang digunakan untuk membuat visualisasi.
* Data `filtered_datateams.csv` merupakan dataset yang digunakan untuk membuat visualisasi.
  
## **Link**
* Link Dataset : https://www.kaggle.com/datasets/jackdaoud/esports-earnings-for-players-teams-by-game/data?select=highest_earning_teams.csv
* Link Tableau : https://public.tableau.com/shared/638H6RQMZ?:display_count=n&:origin=viz_share_link
* Link Medium :
* Link Video :
* Link Linkedin : https://www.linkedin.com/in/reza-saputra-67a067301/ , https://www.linkedin.com/in/safa-arub-nadia-nd24


