# Analisis Pemetaan Pemain dan Tim Esport Berdasarkan Pendapatan dan Partisipasi

## **Background Problems**
Industri esports telah mengalami pertumbuhan yang pesat dalam beberapa tahun terakhir. Dalam ekosistem ini, pemain dari berbagai negara bersaing dalam turnamen global, sementara tim esports juga memainkan peran penting. Untuk memahami lebih dalam dinamika industri ini, analisis data pemain dan tim esports perlu dilakukan. Ini mencakup distribusi pemain berdasarkan negara, pemain dengan pendapatan tertinggi, genre game yang paling banyak dimainkan, partisipasi tim dalam turnamen, dan pendapatan tertinggi serta jumlah turnamen yang diikuti oleh tim.


## **Objectives**
- Objective Data Player
1. Menganalisis distribusi geografis pemain esports dari berbagai negara.
   - Mengapa penting untuk memahami asal negara pemain esports?
2. Mengidentifikasi pemain dengan pendapatan tertinggi.
   - Mengapa penting untuk mengetahui pemain dengan pendapatan tertinggi?
3. Mengidentifikasi genre game yang paling sering dimainkan oleh para pemain esports.
   - Mengapa perlu mengetahui genre game yang paling populer di kalangan pemain esports?

- Objective Data Team
1. Mempelajari distribusi game dalam turnamen esports.
   - Mengapa penting untuk memahami game apa yang paling sering diikuti dalam turnamen esports?
2. Menganalisis tim dengan pendapatan tertinggi.
   - Mengapa perlu untuk mengetahui tim dengan pendapatan tertinggi dalam industri esports?
3. Melihat perbandingan jumlah turnamen yang diikuti oleh tim esports.
   - Mengapa penting untuk membandingkan jumlah turnamen yang diikuti oleh tim esports?

## **Goals**
Tujuan proyek ini adalah untuk mendapatkan pemahaman yang lebih baik tentang distribusi pemain dan tim esports, pendapatan tertinggi, serta preferensi game. Dengan demikian, kita dapat mengidentifikasi peluang dan tren di industri ini.

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
* Dataset : https://www.kaggle.com/datasets/jackdaoud/esports-earnings-for-players-teams-by-game/data?select=highest_earning_teams.csv
* Tableau : https://public.tableau.com/shared/638H6RQMZ?:display_count=n&:origin=viz_share_link
* Medium : https://medium.com/@safaarub24/analisis-eksploratif-pemain-dan-tim-esport-distribusi-negara-pendapatan-tertinggi-genre-game-841c24bfa065
* Video : https://youtu.be/DE_k5nlbHwQ
* Linkedin : https://www.linkedin.com/in/reza-saputra-67a067301/ , https://www.linkedin.com/in/safa-arub-nadia-nd24


