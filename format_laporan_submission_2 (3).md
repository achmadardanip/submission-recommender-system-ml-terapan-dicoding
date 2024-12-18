# Laporan Proyek Machine Learning - Achmad Ardani Prasha

## Project Overview

Dunia hiburan tak terlepas dari industri film yang berkembang sangat pesat dan disertai dengan pertumbuhan  data  yang  sangat besar [1]. Industri  film  juga  didukung  dengan keberadaan  platform streaming dan peningkatan penggunaan internet. Dengan hal tersebut,masyarakat umum dapat lebih leluasa  dengan  memiliki  akses  yang  mudah  untuk  menikmati  berbagai  jenis  film.  Dengan  disertai banyaknya film yang dihadirkan berbagai platform streaming, jumlah konten yang ada akan semakin berlimpah menjadikan tantangan yang muncul, salah satunya yaitu kaitannya bagaimana cara untuk menyajikan rekomendasi film yang sesuai dengan preferensi penggunaseiring pesatnya pertumbuhan data. Data-data  ini  dimanfaatkan  untuk  membangun  sistem-sistem  yang  inovatif,  efisien  dan  lebih efektif. Di masa data melimpah ini, mesin rekomendasi menjadi salah satu kategori penting dalam sistem penyaringan data yang berfungsi untuk memprediksi tingkat penilaian atau rating yang akan diberikan oleh pengguna terhadap objek-objek yang diminatinya di internet. Butuh hampir 15 tahun tanpa henti untuk menyaksikan seluruh koleksi Netflix, HBO Go, Prime Video, dan Disney Hotstar saja.  Mayoritas  pelanggan  tidak  sanggup  menyaksikan  sebagian  kecil  saja  koleksi  tontonannya [2]. Sehingga  perlu  suatu  mesin  pemberi  rekomendasi. Dalam  konteks  ini,  rekomendasi  film  dapat dianggap sebagai sebuah implementasi dari pendekatan pengolahan data besar. Pada umumnya, mesin rekomendasi bekerja dengan menyaring kualitas hasil pencarian dan kemudian menampilkan item-item yang paling relevan dengan minat pengguna berdasarkan riwayat pencarian mereka [3].

Ledakan  data  dan  informasi  memunculkan  permasalahan  penemuan  kembali  informasi (information retrieval). Semakin banyak bisnis yang hadir secara online untuk melacak keunggulan kompetitif  mereka  karena  pertumbuhan  besar-besaran  jaringan  internet.  Agar  organisasi  mana  pun bisa sukses secara domestik atau internasional, internet telah menjadi instrumen yang sangat penting. Pertumbuhan  Internet  yang  eksponensial  telah  mengubah  cara  kerja  sebagian  besar  perusahaan. Internet menyediakan platform unik bagi perusahaan e-Commerce untuk menawarkan dan membeli produk dan layanan bagi konsumen Semakin banyak bisnis yang hadir secara online untuk melacak keunggulan kompetitif mereka karena pertumbuhan besar-besaran jaringan internet. Agar organisasi mana  pun  bisa  sukses  secara domestik atau internasional, internet  telah  menjadi  instrumen  yang sangat penting. Pertumbuhan Internet yang eksponensial telah mengubah cara kerja sebagian besar perusahaan. Internet  menyediakan  platform  unik  bagi  perusahaan e-Commerce untuk  menawarkan dan  membeli  produk  dan  layanan  bagi  konsumen Mesin  pencari  (search  engine) memecahkan sebagian masalah itu, namun personalisasi informasi tidak diberikan karena mesin pencari terbatas pada kata/query yang dimasukkan pengguna, persoalan muncul ketika pengguna mengetahui produk yang  dibutuhkan  tapi  tidak  mengetahui  nama  produk  tersebut  atau  kata  yang  mewakili  produk tersebut, seperti berkeliling di salah satu mall besar atau perpustakkaan besar dimana setelah berputar seharian  tidak  menemukan  barang  yang  dicari. Rekomendasi  dari  seorang  ahli  yang  mengerti kebutuhan dan profil pengguna menjadi sangat dibutuhkan. Disinilah era digital membawa era Big Data meninggalkan popularitas mesin pencari menuju mesin rekomendasi [4].

Belakangan  ini,  sistem  rekomendasi  memegang  peranan  penting  dalam  berbagai  bidang penelitian  dan  implementasikan  pada  banyak  platform  pengambilan  informasi seperti  Amazon, Netflix,  dan  YouTube. Sistem  pemberi  rekomendasi  memperoleh  informasi  dari  klien  dan merekomendasikan  barang  yang  menurutnya  paling  bernilai  di  antara  produk  yang  ada [5]. Sistem rekomendasi ini bekerja dengan menghasilkan rekomendasi berdasarkan riwayat pencarian pengguna dan data dari platform-platform seperti LinkedIn, Facebook, Amazon, dan Netflix. Tujuan utama dari platform  tersebut  adalah  untuk  memberikan  pengalaman  yang  lebih  baik  kepada  penggunanya [6]. Sistem rekomendasi adalah salah satu yang paling penting aplikasi dalam analisis data besar dan telah berkinerja sangat baik untuk banyak bisnis [7],[8]. Salah  satu  pendekatan  yang  paling  populer  dalam  sistem  rekomendasi  adalah Collaborative Filtering (CF), dimana  rekomendasi  dihasilkan  dengan  menganalisis  pola  preferensi pengguna  yang memiliki selera  serupa. Namun, CF tradisional menghadapi beberapa tantangan, termasuk masalah cold start untuk pengguna baru, skalabilitas, dan sparsitas data [9].

Untuk mengatasi tantangan tersebut, proyek ini bertujuan untuk mengembangkan sistem rekomendasi film dengan membandingkan beberapa algoritma CF yang berbeda untuk selanjutnya dievaluasi demi menentukan algoritma mana yang terbaik. Penggunaan beberapa algoritma ynag berbeda dalam CF, seperti KNN (K-Nearest Neighbors), SVD (Singular Value Decomposition), dan NMF (Non-negative Matrix Factorization), untuk mengembangkan sistem rekomendasi film yang lebih efektif.

Beberapa penelitian terkait telah dilakukan untuk membandingkan berbagai algoritma CF dalam konteks rekomendasi film. Sebuah studi oleh Çano dan Morisio (2016) membandingkan algoritma CF berbasis pengguna dan berbasis item dengan berbagai indeks kesamaan untuk rekomendasi film. Mereka menggunakan metrik akurasi statistik untuk menentukan algoritma yang memberikan rekomendasi paling akurat. Hasil penelitian menunjukkan bahwa algoritma berbasis item umumnya memberikan hasil yang lebih baik daripada algoritma berbasis pengguna [10].

Studi oleh Purnomo dan Sukmawati Nur Endah (2019) membandingkan algoritma CF tradisional (CFA) dengan algoritma CF persentase disimetris (DSPCFA) untuk prediksi peringkat dalam sistem rekomendasi film. Mereka juga menggunakan dua metode pengukuran kesamaan, yaitu metode kesamaan korelasi Pearson dan metode kesamaan kosinus. Hasil eksperimen menunjukkan bahwa algoritma DSPCFA menghasilkan nilai kesalahan yang lebih rendah dibandingkan algoritma CFA, dengan penurunan kesalahan sekitar 5% untuk metode evaluasi RMSE dan 7% untuk metode evaluasi MAE [11].

Penelitian terbaru oleh Triyanna Widiyaningtyas et al. (2022) membandingkan kinerja fungsi kesamaan berdasarkan peringkat pengguna dengan fungsi kesamaan berdasarkan perilaku pengguna dalam sistem rekomendasi film. Mereka menerapkan beberapa fungsi kesamaan seperti Cosine similarity, User score Probability Collaborative Filtering (UPCF), User Profile Correlation-based Similarity (UPCSim), dan Clustering-Based UPCSim (CB-UPCSim). Hasil eksperimen pada dataset MovieLens 100K dan MovieLens 1M menunjukkan bahwa kesamaan yang mempertimbangkan perilaku pengguna dapat mengurangi nilai Mean Absolute Error (MAE) dan Root Mean Squared Error (RMSE) dibandingkan dengan kesamaan yang hanya bergantung pada peringkat pengguna [12].

Penelitian  oleh  Adyatama  dan  Baizal  (2023)  membuat  sistem  rekomendasi  buku menggunakan SVD  didapatkan  hasil Root  Mean  Square  Error (RMSE) sebesar  0.868  sedangkan menggunakan ALS hasil RMSE sebesar 109.320. Kesimpulan dari penelitian ini metode SVD lebih baik  dibandingkan  dengan  metode  ALS  dalam  implementasi  sistem  rekomendasi [13].

Dengan mempertimbangkan penelitian-penelitian ini, proyek perbandingan algoritma CF untuk sistem rekomendasi film dapat memberikan wawasan berharga tentang kinerja relatif dari berbagai pendekatan. Hal ini dapat membantu dalam pemilihan algoritma yang paling sesuai untuk dataset dan juga untuk tantangan yang sudah diuraikan sebelumnya, serta memberikan dasar untuk pengembangan lebih lanjut dalam meningkatkan akurasi dan efektivitas sistem rekomendasi film.

## Business Understanding
## Problem Statements
1. **Volume Data yang Sangat Besar di Platform Streaming Film**  
   Platform streaming menghadirkan jumlah konten yang sangat besar, sehingga pengguna kesulitan menemukan film yang sesuai dengan preferensi mereka. Hal ini menyebabkan pengalaman pengguna menjadi kurang optimal.
2. **Tantangan pada Sistem Rekomendasi Tradisional**  
   Sistem rekomendasi tradisional berbasis Collaborative Filtering (CF) menghadapi beberapa tantangan, seperti:
   - **Masalah Cold Start**: Kesulitan memberikan rekomendasi untuk pengguna baru yang belum memiliki riwayat interaksi.
   - **Skalabilitas**: Kinerja sistem menurun seiring dengan bertambahnya jumlah pengguna dan data.
   - **Kelangkaan Data**: Data pengguna sering kali tidak lengkap atau terlalu sedikit untuk menghasilkan rekomendasi yang akurat.
3. **Kurangnya Personalisasi pada Mesin Pencari Umum**  
   Mesin pencari hanya menyediakan informasi berdasarkan kata kunci, sehingga tidak mampu memberikan rekomendasi yang relevan berdasarkan preferensi pengguna.

## Goals
1. **Mengembangkan Sistem Rekomendasi Film yang Efektif**  
   Mengembangkan sistem rekomendasi film yang mampu memberikan rekomendasi personal berdasarkan preferensi pengguna dengan memanfaatkan pendekatan Collaborative Filtering.
2. **Membandingkan Algoritma Collaborative Filtering**  
   Membandingkan berbagai algoritma Collaborative Filtering, seperti K-Nearest Neighbors (KNN), Singular Value Decomposition (SVD), dan Non-negative Matrix Factorization (NMF), untuk menentukan algoritma terbaik dalam meningkatkan akurasi rekomendasi.
3. **Mengatasi Tantangan pada Sistem CF Tradisional**  
   Mengatasi masalah-masalah seperti cold start, skalabilitas, dan kelangkaan data dengan pendekatan algoritma yang lebih canggih.

## Solution Approach

### Solution Statements

1. **Perbandingan Algoritma**  
   Membandingkan algoritma Collaborative Filtering berikut:
   - **K-Nearest Neighbors (KNN)**: Mencari kesamaan antar pengguna atau item untuk menghasilkan rekomendasi.
   - **Singular Value Decomposition (SVD)**: Memanfaatkan dekomposisi matriks untuk menyelesaikan masalah kelangkaan data.
   - **Non-negative Matrix Factorization (NMF)**: Alternatif SVD yang membatasi nilai negatif, menghasilkan representasi fitur yang lebih dapat diinterpretasikan.

2. **Metrik Evaluasi**  
   Menggunakan metrik evaluasi:
   - **Root Mean Squared Error (RMSE)**: Mengukur rata-rata kesalahan kuadrat antara prediksi dan nilai sebenarnya, untuk mengevaluasi akurasi algoritma.

## Expected Results

1. **Peningkatan Akurasi Rekomendasi**  
   Algoritma terbaik dapat memberikan rekomendasi yang lebih akurat berdasarkan nilai RMSE yang lebih rendah.
2. **Sistem yang Skalabel dan Efisien**  
   Sistem rekomendasi yang dapat menangani jumlah data dan pengguna yang besar tanpa mengurangi kinerja.
3. **Pengalaman Pengguna yang Lebih Baik**  
   Pengguna mendapatkan rekomendasi film yang relevan dan personal, sehingga meningkatkan kepuasan mereka terhadap platform streaming.

---
## Data Understanding

Dataset yang digunakan dalam proyek ini adalah dataset MovieLens. Dataset MovieLens disediakan untuk umum oleh GroupLens Research, sebuah laboratorium ilmu komputer di University of Minnesota. Ini adalah salah satu dataset tolok ukur paling populer yang digunakan untuk menguji potensi berbagai model collaborative filtering dan biasanya tersedia di sebagian besar library.

MovieLens memberikan peringkat pengguna pada berbagai film dan tersedia dalam berbagai ukuran. Versi lengkapnya terdiri dari lebih dari 26.000.000 peringkat yang diterapkan pada 45.000 film oleh 270.000 pengguna. Namun, demi komputasi yang cepat, saya akan menggunakan 100.000 dataset yang jauh lebih kecil, yang berisi 100.000 peringkat yang diberikan oleh 1.000 pengguna untuk 1.700 film. Dataset yang tersedia di situs resmi GroupLens tidak lagi memberikan informasi demografis pengguna. Oleh karena itu, saya akan menggunakan dataset lama yang tersedia di Kaggle oleh Prajit Datta.

Berikut tautan dataset: [https://www.kaggle.com/datasets/prajitdatta/movielens-100k-dataset/](https://www.kaggle.com/datasets/prajitdatta/movielens-100k-dataset/)

### Struktur Dataset
Dataset ini terdiri atas beberapa file CSV, namun yang digunakan hanya 3 file berikut:
1. **u.data**: Berisi rating yang diberikan oleh pengguna untuk film.
2. **u.user**: Berisi informasi demografis pengguna seperti usia, jenis kelamin, pekerjaan, dan kode pos.
3. **u.item**: Berisi informasi tentang film seperti judul, tanggal rilis, URL IMDb, dan genre.

### Variabel atau Fitur Dataset
- **userId**: ID unik pengguna yang memberikan rating.
- **movieId**: ID unik film yang diberi rating.
- **rating**: Rating yang diberikan oleh pengguna terhadap film (skala 1-5).
- **timestamp**: Waktu ketika rating diberikan (format Unix timestamp).


### Kondisi Dataset
1. **Missing Values**:
   - Tidak ditemukan *missing values* pada dataset **ratings**, **movies**, dan **users**.
   ```python
   print(ratings.isnull().sum())
   print(users.isnull().sum())
   print(movies.isnull().sum())
   ```

2. **Duplicates**:
   - Dataset telah dicek untuk data duplikat, dan tidak ditemukan baris duplikat dalam dataset **ratings**, **users**, maupun **movies**.
   ```python
   print(ratings.duplicated().sum())
   print(users.duplicated().sum())
   print(movies.duplicated().sum())
   ```

3. **Kesalahan Tipe Data**:
   - Dari tiga dataset yang telah diperiksa tipe datanya, hanya kolom **release date** pada dataset **movies** yang memiliki kesalahan tipe data yaitu bertipe objek, seharusnya dikonversi ke tipe datetime untuk mempermudah analisis waktu.
   - Semua kolom lainnya memiliki tipe data yang sesuai dengan konteksnya.
   - Namun, perlu dicatat bahwa kolom ini tidak terlalu signifikan dan tidak digunakan dalam tahap modelling, maka dari itu bisa kita abaikan saja, namun jika ingin dikonversi bisa mengikuti kode berikut
   ```python
   movies['release date'] = pd.to_datetime(movies['release date'], errors='coerce')
   ```

4. **Distribusi Data**:
   - Dataset **ratings** memiliki dengan mayoritas rating berkisar pada angka 4 dan 3.
   - Sebagian besar pengguna hanya memberikan sedikit rating, dan sebagian besar film memiliki sedikit rating.

### Exploratory Data Analysis (EDA)
**1. Distribusi Rating**
- Visualisasi distribusi rating menggunakan histogram.
```python
plt.hist(ratings['rating'], bins=5, edgecolor='black')
plt.title('Distribusi Rating')
plt.xlabel('Rating')
plt.ylabel('Frekuensi')
plt.show()
```
![distribusi rating](https://github.com/user-attachments/assets/54f26e18-e377-4391-9edd-5c5e7a7388a2)



**2. Jumlah Rating per Film**
- Sebagian besar film mendapatkan jumlah rating yang sedikit, memperlihatkan pola distribusi *long-tail*.
```python
ratings_per_movie = ratings.groupby('movie_id').size()
ratings_per_movie.plot(kind='hist', bins=30, title='Distribution of Ratings per Movie')
plt.xlabel('Number of Ratings')
plt.ylabel('Frequency')
plt.show()
```
![jumlah rating per film](https://github.com/user-attachments/assets/3ea1e05c-b62c-4f63-bb85-f256a3fc6e22)


**3. Jumlah Rating per Pengguna**
- Sebagian besar pengguna memberikan rating untuk jumlah film yang terbatas, menunjukkan sparsitas data.
```python
ratings_per_user = ratings.groupby('user_id').size()
ratings_per_user.plot(kind='hist', bins=30, title='Distribution of Ratings per User')
plt.xlabel('Number of Ratings')
plt.ylabel('Frequency')
plt.show()
```
![jumlah rating per pengguna](https://github.com/user-attachments/assets/13fb16e3-a4c8-4d0f-ae0c-112b491608fd)


**4. Rata-Rata Rating per Film**
- Rata-rata rating menunjukkan bias positif, di mana film lebih cenderung diberi rating tinggi.
```python
avg_rating_per_movie = ratings.groupby('movie_id')['rating'].mean()
avg_rating_per_movie.plot(kind='hist', bins=30, title='Average Rating per Movie')
plt.xlabel('Average Rating')
plt.ylabel('Frequency')
plt.show()
```
![rata-rata rating per film](https://github.com/user-attachments/assets/de5fc1e8-62f2-4896-8749-6df04a1a1f4e)


**5. Rata-Rata Rating per Pengguna**
- Pola rating pengguna menunjukkan keragaman perilaku pemberian rating.
```python
avg_rating_per_user = ratings.groupby('user_id')['rating'].mean()
avg_rating_per_user.plot(kind='hist', bins=30, title='Average Rating per User')
plt.xlabel('Average Rating')
plt.ylabel('Frequency')
plt.show()
```

![rata-rata rating per user](https://github.com/user-attachments/assets/985f12c4-5c54-45f4-a06d-139eb321f1b9)

### Insight Penting
- Dataset bersifat sparsitas tinggi (data pengguna memberikan rating pada sebagian kecil film).
- Bias positif terlihat pada pola rating pengguna.
- Sistem rekomendasi yang digunakan harus mampu menangani sparsitas dan bias data ini dengan efektif.


---

## Data Preparation
Karena data sudah bersih pada saat dicek di bagian data understanding, maka pada tahap ini hanya mencakup **Feature Engineering** dan **Data Splitting** untuk memastikan dataset siap digunakan dalam proses modeling. Langkah-langkah ini berfokus pada pemilihan fitur yang relevan dan penghapusan fitur yang tidak diperlukan.

### 1. Pemilihan Fitur dari Dataset Film
Dari dataset film, hanya kolom `movie_id` dan `title` yang dipilih. Kolom lain, seperti genre, tanggal rilis, dan URL IMDb, diabaikan karena tidak relevan untuk proses rekomendasi berbasis collaborative filtering.

```python
movies = movies[['movie_id', 'title']]
movies.head()
```

**Alasan:** Informasi seperti genre atau tanggal rilis tidak memengaruhi model rekomendasi yang berbasis rating. Dengan hanya mempertahankan ID dan judul film, dataset menjadi lebih sederhana dan efisien.

### 2. Penghapusan Kolom yang Tidak Relevan dari Dataset Rating
Kolom `timestamp` dihapus dari dataset rating karena tidak berkontribusi pada analisis rekomendasi.

```python
ratings = ratings.drop('timestamp', axis=1)
ratings.head()
```

**Alasan:** Waktu pemberian rating (`timestamp`) tidak relevan dalam proyek ini. Dengan menghapusnya, kompleksitas data berkurang tanpa memengaruhi kualitas rekomendasi.

### 3. Pembagian Dataset
Dataset kemudian dibagi menjadi dua bagian:
- **Training Set (75%)**: Digunakan untuk melatih model.
- **Testing Set (25%)**: Digunakan untuk mengevaluasi performa model.

Pembagian dilakukan menggunakan metode **stratified splitting** untuk menjaga proporsi data setiap pengguna:

```python
X = ratings.copy()
y = ratings['user_id']
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.25, stratify=y, random_state=42)
```

**Alasan:** Pembagian ini memastikan bahwa model dapat dilatih dengan data yang memadai dan dievaluasi pada data baru, sehingga performanya dapat diukur dengan lebih akurat.

### 4. Pembuatan Matriks Rating dengan Pivot Table
Tahap selanjutnya adalah kita membuat matriks rating dengan pivot table. kode ini mengubah data pelatihan dari format panjang menjadi format matriks yang memetakan setiap pengguna ke setiap film dengan nilai rating yang diberikan dan membuat Salinan Matriks dengan Mengisi Nilai NaN dengan 0

```python
r_matrix = X_train.pivot_table(values='rating', index='user_id', columns='movie_id')
r_matrix_dummy = r_matrix.copy().fillna(0)
```

**Alasan:** Matriks ini mempermudah analisis berbasis matriks, seperti dalam Collaborative Filtering, di mana algoritma memanfaatkan data dari pengguna serupa atau film serupa untuk memberikan rekomendasi. Format ini juga lebih efisien dalam mengakses informasi rating pengguna terhadap film tertentu dibandingkan format data panjang (long format).

---

# Modelling

Tahapan ini membahas model sistem rekomendasi yang dibuat untuk menyelesaikan permasalahan pada dataset MovieLens. Pendekatan yang digunakan melibatkan berbagai algoritma dengan tujuan memberikan rekomendasi film kepada pengguna berdasarkan data rating. Selain itu, laporan ini juga menyajikan *Top-N Recommendation* sebagai hasil akhir.

## Perhitungan Matriks Kesamaan
Matriks kesamaan kosinus (cosine_sim) akan digunakan untuk mencari pengguna-pengguna yang memiliki pola rating serupa, sehingga bisa merekomendasikan film berdasarkan kesamaan preferensi antar pengguna.

```python
cosine_sim = cosine_similarity(r_matrix_dummy, r_matrix_dummy)
cosine_sim = pd.DataFrame(cosine_sim, index=r_matrix.index, columns=r_matrix.index)
```

## Algoritma yang Digunakan

### 1. **Baseline Model**
- **Deskripsi**: Model sederhana yang selalu memprediksi nilai rata-rata rating (yaitu, 3.0).
- **Cara Kerja**:
Model ini selalu menghasilkan nilai prediksi sebesar 3.0, terlepas dari input `user_id` atau `movie_id`. Model ini bertujuan untuk memberikan tolok ukur sederhana dalam menilai efektivitas model rekomendasi yang lebih kompleks.

**Parameter**:
- **Tidak ada parameter spesifik yang digunakan.**
- **Value Output**: `3.0`

```python
def baseline(user_id, movie_id):
    return 3.0
```
- **Keunggulan**:
  - Mudah diimplementasikan.
  - Memberikan tolok ukur dasar untuk membandingkan model lain.
- **Kelemahan**:
  - Tidak memanfaatkan informasi pengguna atau film.
  - Prediksi tidak relevan dengan preferensi pengguna.


### 2. **User-Based Collaborative Filtering (Mean)**
- **Deskripsi**: Memberikan rekomendasi berdasarkan rata-rata rating suatu film.
- **Cara Kerja**:
Model ini memprediksi rating berdasarkan rata-rata rating untuk suatu item (movie) yang diberikan oleh semua pengguna. Jika `movie_id` tidak tersedia dalam dataset, maka model mengembalikan nilai default 3.0.

**Parameter**:
- **`movie_id`**: ID film yang diprediksi.
- **Value Output**: Rata-rata rating film atau `3.0` jika `movie_id` tidak ditemukan.

```python
def cf_user_mean(user_id, movie_id):
    return r_matrix[movie_id].mean() if movie_id in r_matrix else 3.0
```
- **Keunggulan**:
  - Mudah dihitung.
  - Berguna untuk memberikan gambaran umum preferensi film.
- **Kelemahan**:
  - Tidak memperhatikan hubungan antar pengguna.
  - Kurang personal dalam rekomendasi.


### 3. **User-Based Collaborative Filtering (Weighted Mean)**
- **Deskripsi**: Memanfaatkan kesamaan antar pengguna menggunakan *cosine similarity* untuk memberikan rekomendasi.
- **Cara Kerja**:
Model ini menghitung prediksi rating dengan mempertimbangkan kesamaan (*similarity*) antar pengguna. Kesamaan dihitung menggunakan cosine similarity, dan rating pengguna yang memiliki kemiripan lebih besar diberi bobot lebih tinggi.

**Parameter**:
- **`user_id`**: ID pengguna yang sedang diprediksi.
- **`movie_id`**: ID film yang sedang diprediksi.
- **`cosine_sim`**: Matriks kesamaan antar pengguna.
- **Value Output**: Rating yang dihitung berdasarkan bobot kesamaan, atau `3.0` jika tidak ada data kesamaan.

```python
def cf_user_wmean(user_id, movie_id):
    if movie_id in r_matrix:
        sim_scores = cosine_sim[user_id]
        m_ratings = r_matrix[movie_id].dropna()
        sim_scores = sim_scores.loc[m_ratings.index]
        if sim_scores.sum() != 0:
            return np.dot(sim_scores, m_ratings) / sim_scores.sum()
        else:
            return 3.0
    return 3.0
```
- **Keunggulan**:
  - Rekomendasi lebih personal karena mempertimbangkan kesamaan preferensi.
- **Kelemahan**:
  - Rentan terhadap masalah sparsity data.
  - Membutuhkan waktu komputasi lebih besar untuk dataset besar.


### 4. **NMF (Non-Negative Matrix Factorization)**
- **Deskripsi**: Mengungkap fitur laten untuk mengurangi dimensi data dan menangani sparsity.
- **Cara Kerja**:
Model ini mendekonstruksi matriks interaksi pengguna-item menjadi dua matriks dengan fitur laten (pengguna dan item), kemudian merekonstruksi matriks untuk memprediksi rating.

**Parameter**:
- **`rating_scale`**: Skala rating yang digunakan (default: `(1, 5)`).
- **Value Output**: Prediksi rating berdasarkan fitur laten.

```python
reader = Reader(rating_scale=(1, 5))
data = Dataset.load_from_df(ratings[['user_id', 'movie_id', 'rating']], reader)

nmf = NMF()
nmf_results = cross_validate(nmf, data, measures=['RMSE'], cv=5, verbose=True)
```

- **Keunggulan**:
  - Efektif untuk data sparsity tinggi.
  - Skalabilitas baik untuk dataset besar.
- **Kelemahan**:
  - Hasil model sulit untuk diinterpretasikan secara langsung.
  - Memerlukan waktu pelatihan lebih lama dibandingkan metode sederhana.


### 5. **kNN (k-Nearest Neighbors)**
- **Deskripsi**: Menggunakan kesamaan antar pengguna atau item untuk memberikan rekomendasi.
- **Cara Kerja**:
Model ini menggunakan pendekatan tetangga terdekat (*nearest neighbors*) untuk memprediksi rating berdasarkan kemiripan langsung antara pengguna atau item.

**Parameter**:
- **`measures`**: Metode evaluasi (default: `['RMSE']`).
- **`cv`**: Jumlah lipatan validasi silang.
- **Value Output**: Prediksi berdasarkan tetangga terdekat.

```python
knn = KNNBasic()
knn_results = cross_validate(knn, data, measures=['RMSE'], cv=5, verbose=True)
```
- **Keunggulan**:
  - Mudah dipahami dan dijelaskan.
- **Kelemahan**:
  - Rentan terhadap sparsity.
  - Membutuhkan waktu komputasi besar untuk dataset besar.


### 6. **SVD (Singular Value Decomposition)**
- **Deskripsi**: Menggunakan dekomposisi matriks untuk mengidentifikasi fitur laten dalam data pengguna-item.
- **Cara Kerja**:
Model ini memecah matriks interaksi pengguna-item menjadi faktor-faktor laten untuk menangkap pola mendasar dalam data. Metode ini efektif untuk menangani data yang jarang (*sparse*) dan dataset besar.

**Parameter**:
- **`measures`**: Metode evaluasi (default: `['RMSE']`).
- **`cv`**: Jumlah lipatan validasi silang.
- **Value Output**: Prediksi berdasarkan faktor laten.

```python
svd = SVD()
svd_results = cross_validate(svd, data, measures=['RMSE'], cv=5, verbose=True)
```
- **Keunggulan**:
  - Akurasi tinggi untuk menangani sparsity.
  - Skalabilitas baik untuk dataset besar.
- **Kelemahan**:
  - Membutuhkan proses pelatihan yang lebih kompleks.
  - Memerlukan penyesuaian parameter agar optimal.
 
## Top-N Recommendation
Bagian terakhir dari kode menghasilkan Top-N Recommendations menggunakan berbagai model algoritma yang sudah di kembangkan di atas. Rekomendasi ini dihasilkan dengan memprediksi rating untuk semua pasangan user-item, mengurutkan film berdasarkan prediksi rating tertinggi, dan menampilkan 10 film terbaik untuk setiap pengguna. Misalnya, untuk lima pengguna pertama, film yang direkomendasikan ditampilkan beserta prediksi ratingnya.

Dari hasil top n recommendation dan perbandingan model saya memilih SVD sebagai model terbaik karena model ini dapat menangani dataset besar dan sparsity, memberikan rekomendasi yang lebih personal dan akurat. Pendekatan ini sangat sesuai untuk aplikasi dunia nyata, seperti platform streaming film.

Berikut hasilnya dengan mengambil beberapa user:

### Baseline Model Top-N Recommendations

| User ID | Movie                                                    | Predicted Rating |
|---------|----------------------------------------------------------|------------------|
| 196     | Toy Story (1995)                                         | 3.00             |
| 196     | GoldenEye (1995)                                         | 3.00             |
| 196     | Four Rooms (1995)                                        | 3.00             |
| 196     | Get Shorty (1995)                                        | 3.00             |
| 196     | Copycat (1995)                                           | 3.00             |
| 196     | Shanghai Triad (Yao a yao yao dao waipo qiao) (1995)     | 3.00             |
| 196     | Twelve Monkeys (1995)                                    | 3.00             |
| 196     | Babe (1995)                                              | 3.00             |
| 196     | Dead Man Walking (1995)                                  | 3.00             |
| 196     | Richard III (1995)                                       | 3.00             |


### User-Based Collaborative Filtering (Mean) Top-N Recommendations

| User ID | Movie                                                    | Predicted Rating |
|---------|----------------------------------------------------------|------------------|
| 196     | Great Day in Harlem, A (1994)                            | 5.00             |
| 196     | Two or Three Things I Know About Her (1966)              | 5.00             |
| 196     | They Made Me a Criminal (1939)                           | 5.00             |
| 196     | Prefontaine (1997)                                       | 5.00             |
| 196     | Letter From Death Row, A (1998)                          | 5.00             |
| 196     | Star Kid (1997)                                          | 5.00             |
| 196     | Faust (1994)                                             | 5.00             |
| 196     | Saint of Fort Washington, The (1993)                     | 5.00             |
| 196     | Santa with Muscles (1996)                                | 5.00             |
| 196     | World of Apu, The (Apur Sansar) (1959)                   | 5.00             |


### User-Based Collaborative Filtering (Weighted Mean) Top-N Recommendations

| User ID | Movie                                                    | Predicted Rating |
|---------|----------------------------------------------------------|------------------|
| 1       | Prefontaine (1997)                                       | 5.00             |
| 1       | Great Day in Harlem, A (1994)                            | 5.00             |
| 1       | They Made Me a Criminal (1939)                           | 5.00             |
| 1       | Letter From Death Row, A (1998)                          | 5.00             |
| 1       | Star Kid (1997)                                          | 5.00             |
| 1       | Faust (1994)                                             | 5.00             |
| 1       | Saint of Fort Washington, The (1993)                     | 5.00             |
| 1       | Santa with Muscles (1996)                                | 5.00             |
| 1       | World of Apu, The (Apur Sansar) (1959)                   | 5.00             |
| 1       | Aiqing wansui (1994)                                     | 5.00             |


### NMF Top-N Recommendations

| User ID | Movie                                                    | Predicted Rating |
|---------|----------------------------------------------------------|------------------|
| 196     | Secrets & Lies (1996)                                    | 4.28             |
| 196     | Waiting for Guffman (1996)                               | 4.25             |
| 196     | Being There (1979)                                       | 4.18             |
| 196     | Men in Black (1997)                                      | 4.12             |
| 196     | Raising Arizona (1987)                                   | 4.10             |
| 196     | Stand by Me (1986)                                       | 4.08             |
| 196     | Fish Called Wanda, A (1988)                              | 4.08             |
| 196     | Babe (1995)                                              | 4.02             |
| 196     | Shall We Dance? (1996)                                   | 4.01             |
| 196     | Kolya (1996)                                             | 3.95             |


### kNN Top-N Recommendations

| User ID | Movie                                                    | Predicted Rating |
|---------|----------------------------------------------------------|------------------|
| 196     | English Patient, The (1996)                              | 4.86             |
| 196     | Secrets & Lies (1996)                                    | 4.56             |
| 196     | Babe (1995)                                              | 4.42             |
| 196     | Stand by Me (1986)                                       | 4.39             |
| 196     | Being There (1979)                                       | 4.39             |
| 196     | Fish Called Wanda, A (1988)                              | 4.24             |
| 196     | Shall We Dance? (1996)                                   | 4.20             |
| 196     | Raising Arizona (1987)                                   | 4.12             |
| 196     | American President, The (1995)                           | 4.04             |
| 196     | Mrs. Brown (Her Majesty, Mrs. Brown) (1997)              | 4.03             |


### SVD Top-N Recommendations

| User ID | Movie                                                    | Predicted Rating |
|---------|----------------------------------------------------------|------------------|
| 196     | Secrets & Lies (1996)                                    | 4.48             |
| 196     | English Patient, The (1996)                              | 4.28             |
| 196     | Being There (1979)                                       | 4.26             |
| 196     | Babe (1995)                                              | 4.21             |
| 196     | Cold Comfort Farm (1995)                                 | 4.19             |
| 196     | Fish Called Wanda, A (1988)                              | 4.12             |
| 196     | Mrs. Brown (Her Majesty, Mrs. Brown) (1997)              | 4.06             |
| 196     | Waiting for Guffman (1996)                               | 3.99             |
| 196     | Kolya (1996)                                             | 3.94             |
| 196     | Groundhog Day (1993)                                     | 3.90             |


---

## Evaluation

## Root Mean Squared Error (RMSE)
Walaupun rating hanya memiliki lima nilai (1, 2, 3, 4, 5), kita akan memodelkan ini sebagai masalah regresi, bukan klasifikasi. Mengapa? Karena model regresi lebih sensitif terhadap tingkat kesalahan. Sebagai contoh, jika rating sebenarnya adalah 5, prediksi 4 dianggap lebih baik daripada prediksi 1. Model regresi akan memberikan penalti lebih besar untuk prediksi 1 dibandingkan prediksi 4, sesuai dengan apa yang kita inginkan. Sebaliknya, model klasifikasi memperlakukan semua kesalahan sama, terlepas dari seberapa jauh nilai prediksi dari nilai sebenarnya.

Untuk mengevaluasi performa dan keakuratan dari model rekomendasi film yang dihasilkan, matriks Root Mean Squared Error (RMSE) digunakan sebagai ukuran kesalahan prediksi rating. Root Mean Squared Error (RMSE) merupakan matriks evaluasi yang paling umum digunakan dalam sistem rekomendasi berbasis rating. Matriks ini yang dapat mengukur akar rata-rata kuadrat dari selisih antara nilai rating yang sebenarnya (Rij) yang diberikan oleh pengguna dengan nilai rating prediksi (R̂ij) yang dihasilkan oleh model yang dibangun.

Secara matematis, Root Mean Squared Error (RMSE) didefinisikan sebagai:

RMSE = √(1/|R| ∑(Rij - R̂ij)²)

**Keterangan**:
- R : himpunan pasangan pengguna dan item (i,j) yang memiliki nilai rating sebenarnya
- Rij : nilai rating sebenarnya yang diberikan oleh pengguna (i) untuk item (j)
- R̂ij : nilai rating yang diprediksi oleh model untuk pengguna (i) dan item (j)
- |R| : jumlah total pasangan pengguna dan item yang memiliki rating

Nilai RMSE biasanya berkisar antara 0 hingga 1. Semakin rendah nilai RMSE, semakin akurat performa model dalam memprediksi rating yang mendekati nilai sebenarnya.

**Performa Model**
Berikut adalah hasil evaluasi model berdasarkan nilai *Root Mean Squared Error* (RMSE):
- **Baseline Model**: RMSE = 1.248
- **User-Based Collaborative Filtering (Mean)**: RMSE = 1.030
- **User-Based Collaborative Filtering (Weighted Mean)**: RMSE = 1.023
- **NMF**: RMSE = 0.963
- **kNN**: RMSE = 0.979
- **SVD**: RMSE = 0.936

**Interpretasi**:
- **Model terbaik adalah SVD**, karena menghasilkan RMSE terendah, menunjukkan kemampuan yang baik dalam menangkap pola laten dan menangani sparsity.
- **Alternatif lain adalah NMF**, yang juga cocok untuk dataset sparsity tinggi.
- Pendekatan berbasis kesamaan seperti kNN dan Weighted Mean memberikan performa cukup baik tetapi kurang optimal untuk dataset besar.

## Evaluasi Dampak Model terhadap Business Understanding

### Apakah Sudah Menjawab Problem Statement?
### Problem Statement 1: Volume Data yang Sangat Besar di Platform Streaming Film
- **Evaluasi**: Model SVD dan NMF secara khusus mampu menangani sparsity pada dataset yang besar. Hal ini memungkinkan pengguna mendapatkan rekomendasi yang relevan dari jumlah konten yang besar di platform streaming film.
- **Kesimpulan**: Problem statement ini berhasil dijawab dengan pendekatan Collaborative Filtering berbasis SVD dan NMF.

### Problem Statement 2: Tantangan pada Sistem Rekomendasi Tradisional
- **Cold Start**: Meski NMF dan SVD menangani sparsity dengan baik, cold start tetap menjadi tantangan karena mereka membutuhkan data minimal dari pengguna baru. Solusi tambahan seperti hybrid filtering atau content-based filtering dapat melengkapinya.
- **Skalabilitas**: SVD dan NMF dirancang untuk menangani skala besar dengan efisiensi tinggi, sehingga tantangan skalabilitas dapat diatasi.
- **Kelangkaan Data**: NMF dan SVD menunjukkan performa unggul dalam menangani kelangkaan data dengan menangkap fitur laten.
- **Kesimpulan**: Tantangan utama dari sistem rekomendasi tradisional sebagian besar berhasil diatasi oleh model SVD dan NMF.

### Problem Statement 3: Kurangnya Personalisasi pada Mesin Pencari Umum
- **Evaluasi**: Model NMF dan SVD memberikan rekomendasi yang sangat personal berdasarkan pola laten dalam data user-item, melampaui pendekatan berbasis kata kunci sederhana.
- **Kesimpulan**: Problem statement ini terjawab dengan solusi berbasis Collaborative Filtering.

### Apakah Berhasil Mencapai Goals yang Diharapkan?
### Goal 1: Mengembangkan Sistem Rekomendasi Film yang Efektif
- **Hasil**: NMF dan SVD memberikan hasil rekomendasi yang akurat dengan RMSE rendah.
- **Kesimpulan**: Goal ini tercapai dengan mengembangkan sistem yang efektif untuk rekomendasi personal.

### Goal 2: Membandingkan Algoritma Collaborative Filtering
- **Hasil**: Model terbaik (SVD dan NMF) diidentifikasi melalui evaluasi menggunakan metrik RMSE.
- **Kesimpulan**: Goal ini tercapai dengan pemilihan algoritma berdasarkan performa.

### Goal 3: Mengatasi Tantangan pada Sistem CF Tradisional
- **Hasil**: Masalah sparsity dan skalabilitas berhasil diatasi oleh SVD dan NMF, meskipun cold start masih memerlukan solusi tambahan.
- **Kesimpulan**: Sebagian besar tantangan berhasil diatasi, mendekati pencapaian goal sepenuhnya.

### Apakah Solusi Statement yang Direncanakan Berdampak?
### Solusi 1: Perbandingan Algoritma
- **Hasil**: Pemilihan algoritma SVD dan NMF yang unggul berdasarkan RMSE menunjukkan dampak positif dalam meningkatkan akurasi rekomendasi.
- **Dampak**: Sistem rekomendasi yang lebih efektif, relevan, dan personal untuk pengguna.

### Solusi 2: Metrik Evaluasi
- **Hasil**: Penggunaan RMSE sebagai metrik memberikan kejelasan dalam menilai performa model.
- **Dampak**: Implementasi solusi dapat diukur secara objektif, memudahkan evaluasi keberhasilan.
  
---

## Kesimpulan Umum
- **Problem Statement Terjawab**: Model NMF dan SVD menunjukkan kemampuan menangani tantangan utama dalam sistem rekomendasi.
- **Goals Tercapai**: Sistem rekomendasi yang efektif, personal, dan skalabel berhasil dikembangkan.
- **Solusi Berdampak**: Pendekatan berbasis SVD dan NMF membawa dampak positif dalam meningkatkan pengalaman pengguna dan akurasi rekomendasi, sejalan dengan tujuan platform streaming.

---

# Referensi
1. I. P. Putri, "Industri Film Indonesia Sebagai Bagian Dari Industri Kreatif Indonesia," *J. Ilm. LISKI (Lingkar Stud. Komunikasi)*, vol. 3, no. 1, p. 24, 2017, doi: [10.25124/liski.v3i1.805](https://doi.org/10.25124/liski.v3i1.805).  
2. M. Kris, "Koleksi Film Melimpah, Pelanggan Kewalahan Menonton," *Kompas.id*, 2023.  
3. A. A. Rehma, M. J. Awan, and I. Butt, "Comparison and Evaluation of Information Retrieval Models," *VFAST Trans. Softw. Eng.*, vol. 6, no. 1, pp. 7–14, 2018, doi: [10.21015/vtse.v13i1.496](https://doi.org/10.21015/vtse.v13i1.496).  
4. R. K. Sorde and S. N. Desmukh, "Comparative Study on Approaches of Recommendation Systems," *Adv. Intell. Syst. Comput.*, vol. 118, no. 2, pp. 10–14, 2015, doi: [10.1007/978-981-15-0947-6_72](https://doi.org/10.1007/978-981-15-0947-6_72).  
5. H. Hwangbo, Y. S. Kim, and K. J. Cha, "Recommendation system development for fashion retail e-commerce," *Electron. Commer. Res. Appl.*, vol. 28, pp. 94–101, 2018, doi: [10.1016/j.elerap.2018.01.012](https://doi.org/10.1016/j.elerap.2018.01.012).  
6. F. Amato, V. Moscato, A. Picariello, and G. Sperli, "KIRA: A System for Knowledge-Based Access to Multimedia Art Collections," 2017, p. 1.  
7. Q. Zhao, Y. Zhang, D. Friedman, and F. Tan, "E-commerce recommendation with personalized promotion," *RecSys 2015 - Proc. 9th ACM Conf. Recomm. Syst.*, no. August, pp. 219–225, 2015, doi: [10.1145/2792838.2800178](https://doi.org/10.1145/2792838.2800178).  
8. J. Bobadilla, F. Ortega, A. Hernando, and A. Gutiérrez, "Recommender systems survey," *Knowledge-Based Syst.*, vol. 46, pp. 109–132, 2013, doi: [10.1016/j.knosys.2013.03.012](https://doi.org/10.1016/j.knosys.2013.03.012).  
9. D. Shyam Prakash, A. S. Abirami, P. Muthuraman, C. Sathish, and K. L. Sundharabalaji, "Personalized Movie Recommendations: A Comprehensive Review and Analysis," *2024 10th International Conference on Advanced Computing and Communication Systems (ICACCS)*, vol. 1, pp. 2042–2045, 2024.  
10. E. Çano and M. Morisio, "Hybrid recommender systems: A systematic literature review," *Intell. Data Anal.*, vol. 21, pp. 1487–1524, 2019.  
11. J. E. Purnomo and S. N. Endah, "Rating Prediction on Movie Recommendation System: Collaborative Filtering Algorithm (CFA) vs. Dissymetrical Percentage Collaborative Filtering Algorithm (DSPCFA)," *2019 3rd International Conference on Informatics and Computational Sciences (ICICoS)*, pp. 1–6, 2019.  
12. T. Widiyaningtyas, I. Hidayah, and T. B. Adji, "Comparing User Rating-Based Similarity to User Behavior-Based Similarity in Movie Recommendation Systems," *2022 International Conference on Electrical and Information Technology (IEIT)*, pp. 52–58, 2022.  
13. H. A. Adyatma and Z. K. A. Baizal, "Book Recommender System Using Matrix Factorization with Alternating Least Square Method," *J. Inf. Syst. Res.*, vol. 4, no. 4, pp. 1286–1292, 2023, doi: [10.47065/josh.v4i4.3816](https://doi.org/10.47065/josh.v4i4.3816).  




