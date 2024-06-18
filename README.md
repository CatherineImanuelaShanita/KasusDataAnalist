# KasusDataAnalist


Sebuah perusahaan yang berbisnis di bidang e-commerce bernama "PT. Shopping 
Day" adalah perusahaan yang berfokus pada penjualan elektronik dan barang 
rumah tangga (home goods). PT. Shopping Day memiliki beberapa cabang yang 
tersebar di 15 provinsi di Indonesia. Di bulan Juni 2024, Direktur akan 
melakukan analisis tengah tahun atas penjualan Cabang Semarang bulan Mei 
2024, sehingga manajer Arya Winata melakukan analisis data dan customer 
dengan bantuan analist data perusahaan. Berikut adalah data penjualan atas 
barang elektronik dan barang rumah tangga PT. Shopping Day yang telah 
terjual, beserta dengan data transaksi dan rating dari customer:

Data di bawah berkaitan dengan produk yang tersedia di bulan Mei 2024
### Products

| ProductID | NamaProduk     | Kategori    | Harga | KuantitasBarang |
|-----------|----------------|-------------|-------|-----------------|
| 1         | Smartphone X   | Elektronik  | 999   | 50              |
| 2         | Laptop Y       | Electronik  | 1500  | 30              |
| 3         | Headphones Z   | Electronik  | 199   | 100             |
| 4         | Coffee Maker A | Home Goods  | 79    | 75              |
| 5         | Blender B      | Home Goods  | 129   | 60              |


Data di bawah berkaitan dengan customer di bulan Mei 2024
### Customers

| CustomerID | Nama          | Usia | JenisKelamin | Daerah       |
|------------|---------------|------|--------------|--------------|
| 1          | Alif Rahman   | 28   | L            | Banyumanik   |
| 2          | Gea Danisha   | 34   | P            | Gajahmungkur |
| 3          | Alisa Yudhani | 22   | P            | Genuk        |
| 4          | Yusuf Gerry   | 45   | L            | Gunungpati   |
| 5          | Bulan Pertiwi | 31   | P            | Ngaliyan     |
| 6          | Ilham Arya    | 39   | L            | Banyumanik   |
| 7          | Wahidin       | 56   | L            | Banyumanik   |
| 8          | Yustina       | 35   | P            | Gunungpati   |
| 9          | Bintang Agung | 20   | L            | Gajahmungkur |
| 10         | Gisel Natanya | 22   | P            | Genuk        |
| 11         | Nabila Putri  | 23   | P            | Genuk        |
| 12         | Natasha       | 34   | P            | Gunungpati   |
| 13         | Muladi Raihan | 37   | L            | Banyumanik   |
| 14         | Jody Akbar    | 27   | L            | Genuk        |
| 15         | Jessica Hari  | 34   | P            | Gunungpati   |
| 16         | Antoni        | 25   | L            | Genuk        |
| 17         | Gilang Haikal | 36   | L            | Gajahmungkur |
| 18         | Lukas Aji     | 40   | L            | Banyumanik   |
| 19         | Laura Gisela  | 22   | P            | Ngaliyan     |
| 20         | Kevin Adi     | 27   | L            | Gajahmungkur |
| 21         | Adi Riyanto   | 20   | L            | Genuk        |
| 22         | Elisa Riana   | 26   | P            | Ngaliyan     |
| 23         | Giyanti       | 37   | P            | Gunungpati   |
| 24         | Reynara Ali   | 28   | L            | Gunungpati   |
| 25         | Abimanyu      | 21   | L            | Gajahmungkur |

Data di bawah berkaitan dengan transaksi produk terjual di bulan Mei 2024
### Transactions

| TransactionID | CustomerID | ProductID | Kuantitas | TanggalTransaksi |
|---------------|------------|-----------|-----------|------------------|
| 1             | 1          | 1         | 1         | 2024-05-01       | 
| 2             | 2          | 3         | 2         | 2024-05-03       |
| 3             | 3          | 4         | 1         | 2024-05-03       |
| 4             | 4          | 2         | 1         | 2024-05-06       |
| 5             | 5          | 5         | 1         | 2024-05-10       |
| 6             | 6          | 4         | 5         | 2024-05-11       |
| 7             | 7          | 2         | 2         | 2024-05-13       |
| 8             | 8          | 3         | 4         | 2024-05-14       |
| 9             | 9          | 4         | 2         | 2024-05-15       |
| 10            | 10         | 4         | 4         | 2024-05-16       |  
| 11            | 11         | 1         | 3         | 2024-05-19       |
| 12            | 12         | 2         | 2         | 2024-05-20       |
| 13            | 13         | 3         | 5         | 2024-05-20       |
| 14            | 14         | 5         | 2         | 2024-05-23       |
| 15            | 15         | 5         | 1         | 2024-05-24       |
| 16            | 16         | 3         | 7         | 2024-05-25       |
| 17            | 17         | 5         | 1         | 2024-05-27       |
| 18            | 18         | 3         | 3         | 2024-05-27       |
| 19            | 19         | 2         | 1         | 2024-05-28       |
| 20            | 20         | 3         | 2         | 2024-05-28       |
| 21            | 21         | 4         | 5         | 2024-05-28       |
| 22            | 22         | 2         | 2         | 2024-05-29       |
| 23            | 23         | 1         | 2         | 2024-05-29       |
| 24            | 24         | 1         | 5         | 2024-05-30       |
| 25            | 25         | 3         | 2         | 2024-05-30       |
                               

Data di bawah berkaitan dengan rating atas produk di bulan Mei 2024
### Reviews

| ReviewID | CustomerID | ProductID | Rating | TanggalReview |
|----------|------------|-----------|--------|---------------|
| 1        | 1          | 1         | 5      | 2024-05-11    |
| 2        | 2          | 3         | 4      | 2024-05-12    |
| 3        | 3          | 4         | 3      | 2024-05-13    |
| 4        | 4          | 2         | 4      | 2024-05-14    |
| 5        | 5          | 5         | 5      | 2024-05-15    |
| 6        | 6          | 4         | 5      | 2024-05-17    |
| 7        | 7          | 2         | 3      | 2024-05-18    |
| 8        | 8          | 3         | 3      | 2024-05-18    |
| 9        | 9          | 4         | 3      | 2024-05-20    |
| 10       | 10         | 4         | 5      | 2024-05-21    |
| 11       | 11         | 1         | 4      | 2024-05-27    |
| 12       | 12         | 2         | 5      | 2024-05-28    |
| 13       | 13         | 3         | 4      | 2024-05-29    |
| 14       | 14         | 5         | 5      | 2024-05-31    |
| 15       | 15         | 5         | 5      | 2024-05-31    |
| 16       | 16         | 3         | 5      | 2024-06-04    |
| 17       | 17         | 5         | 5      | 2024-06-06    |
| 18       | 18         | 3         | 3      | 2024-06-07    |
| 19       | 19         | 2         | 4      | 2024-06-09    |
| 20       | 20         | 3         | 4      | 2024-06-10    |
| 21       | 21         | 4         | 4      | 2024-06-12    |
| 22       | 22         | 2         | 4      | 2024-06-13    |
| 23       | 23         | 1         | 5      | 2024-06-14    |
| 24       | 24         | 1         | 4      | 2024-06-15    |
| 25       | 25         | 3         | 5      | 2024-06-16    |


Diandaikan Anda saat ini merupakan seorang analist data "Shopping Day" Cabang Semarang, buatlah:
1. Analisis dan visualisasi dari:
  a. Jumlah Penjualan per Produk Elektronik dan Produk House Goods selama Mei 2024
  b. Perbandingan Customer dilihat dari jenis kelaminnya, selama Mei 2024
  c. Perbandingan Customer dilihat dari usianya, selama Mei 2024 
  d. Perbandingan Customer dilihat dari asal daerahnya, selama Mei 2024 
  e. Jumlah Persediaan setelah penjualan bulan Mei 2024
2. Analisis data atas data penjualan bulan Mei 2024 PT. Shopping Day, yang terdiri dari:
  a. Analisis Perbandingan antar barang di setiap kategori selama bulan Mei 2024
  b. Analisis Perbandingan per kategori (antara barang elektronik dan barang rumah tangga/house goods) Mei 2024
  c. Analisis Prediksi Penjualan bulan Juni 2024
2. Visualisasi data atas penjualan bulan Mei 2024 PT. Shopping Day
3. Interpretasi yang sesuai atas hasil penjualan bulan Mei 2024 PT. Shopping Day


# Langkah-Langkah Analisis Data
Untuk analisis dari kasus di atas, beberapa langkah yang dilakukan, yaitu:
1. Persiapan Lingkungan Kerja

Memastikan telah menginstall Virtual Studio Code (selanjutnya disebut VS Code) dan ekstensi Python (seperti Python Extension dan Jupyter Extension).
Buat proyek atau folder kerja baru di VS Code untuk menyimpan semua file terkait dengan analisis data.

![image](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/1a0f607f-1005-4ed4-9ca5-461b89511752)

![image](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/a3a8edba-0652-4edd-a6a2-f1927f18d1fd)


2. Data Collecting
   
Siapkan dataset transaksi produk, rating produk, dan informasi produk dalam format yang dapat dibaca oleh Python (misalnya CSV).
Letakkan file-file data ini dalam folder proyek (misal: Kasus_Data).

![image](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/84b28add-0b71-4a59-ac55-9c31022fc863)

![image](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/8d567482-37f5-4095-8b9a-8465fb449ba9)

![image](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/9e960f80-f9af-49a1-8e3f-72ee754d6c70)

![image](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/9d4acad0-b772-4b92-94fe-ca66edf53472)


3. Data Integration
   
Gunakan pandas untuk membaca file CSV ke dalam dataframe.

![image](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/08fe6248-5073-40c1-9787-fe547f52b639)

![image](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/6b64ce63-20c8-4e14-9b92-f01b8b25ac67)

![image](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/994c13c0-e0ce-46bd-a7f3-e91638b007c8)

4. Data Cleaning
   
Melakukan pembersihan data seperti mengatasi nilai yang hilang atau duplikat, dan pastikan tipe data yang benar. Gabungkan dataframe berdasarkan kunci (seperti ProductID atau CustomerID).

![image](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/51e0c3f7-19b3-478b-827c-053a899b5394)

![image](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/8582d0d5-dbd6-4eae-9120-81bd3ebb215b)


5. Exploratory Data Analysis (EDA)

Melakukan EDA untuk memahami data. Buat visualisasi seperti histogram, scatter plot, dan box plot untuk menganalisis distribusi, korelasi, dan outlier.

Pertanyaan 1A:
![image](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/bae38b1f-346c-4a46-80b9-e6f1141c306f)

Pertanyaan 1B:
![image](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/aa0e4362-959c-472c-947e-6d096fa75e8a)

![image](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/e92a0727-e6b5-4ada-883e-7c7b5710605d)

Pertanyaan 1C:
![image](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/c8c69d46-c068-4224-938d-71f7218948de)

![image](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/99ec5658-b2e4-4335-988a-6abe3c3ce993)

![image](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/e7335c72-724c-4136-afc3-6ddf6e0b6dc8)

Pertanyaan 1D:
![image](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/a0a06590-d326-41b8-9ea2-51afb50d2afe)

Pertanyaan 1E:
![image](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/37a541f4-df83-4d20-a267-541f3df0755b)

Pertanyaan 2A (Analisis Per Produk)
![image](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/21fb40ad-02cb-4e54-92e4-c99108809621)

Pertanyaan 2B (Analisis Per Kategori)
![image](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/1cdb9341-b1c8-44a1-a45a-18c3e7ecf0fa)

Pertanyaan 2C (Analisis Prediksi Penjualan)
![image](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/d4065667-115a-488b-9cc6-b44e028d64cb)

![image](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/8c1c7e57-5700-44a8-a624-0e6c70f353e0)


7. Analisis Statistik dan Regresi

Lakukan analisis statistik deskriptif dan regresi untuk memeriksa hubungan antara rating produk dan total penjualan produk.

Visualisasi Analisis Data

Soal 1A
![soal 1a](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/e6dc224d-8f7a-4a9a-bf38-13b1da08d6d7)

Soal 1B
![soal 1b](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/1cda30b2-614c-4ce8-9ff5-a81794cc7dda)

Soal 1C
![soal 1c](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/e1b08c34-a09a-423b-b229-20184205a07f)

Soal 1D
![soal 1d](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/00e719b9-9f12-4519-803b-e97751d8145c)

Soal 1E
![soal 1e](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/da5f5cca-9215-43cd-90ce-f71a5720dd3e)

Soal 2A
![soal 2a](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/6cea304d-4b6c-484b-a56d-9363917722e4)

![soal 2a boxplot](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/913de56a-0a23-4f19-9880-23bc13889893)

Soal 2B
![soal 2b](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/d1b95dc5-7a05-4902-af40-a61884cb0cfd)

Soal 2C
![soal 2c](https://github.com/CatherineImanuelaShanita/KasusDataAnalist/assets/167211624/1c84d298-2bde-4700-a5b4-a8b2277f0a22)
