# Mini Project Data Engineer

## 1. Pengantar
ETL adalah singkatan dari Extract, Transform, Load. Tujuan utama dari notebook ini adalah untuk membersihkan kumpulan data dan menggabungkannya menjadi satu tabel yang nantinya bisa digunakan untuk menjalankan model prediksi biaya total proyek Bank Dunia.

## 2. Ekstraksi Data (Extract)
### 2.1 File CSV
Data diekstrak dari file CSV yang menyimpan data terstruktur dalam format tabel sederhana.

### 2.2 File JSON
Mengambil data dari file JSON yang sering digunakan untuk pertukaran data di web.

### 2.3 API
Data juga diekstrak dari berbagai API yang menyediakan data dinamis yang diperbarui secara berkala.

### 2.4 File XML
Mengambil data dari file XML yang sering digunakan untuk pertukaran data di web.

### 2.5 Database
Mengambil data dari database SQLite yang menyimpan data dalam format tabel yang terstruktur.

## 3. Transformasi Data (Transformation)
### 3.1 Menggabungkan Data dari Berbagai Sumber (Combining Data from Different Sources)
Mengintegrasikan data yang diperoleh dari file CSV, JSON, XML, DB, dan melalui API ke dalam satu dataset yang konsisten untuk analisis lebih lanjut.

### 3.2 Pembersihan Data (Data Cleaning)
Melakukan pembersihan data yang mencakup:
- Mengatasi Data yang Hilang (Handling Missing Data)
- Menghapus Data Duplikat (Removing Duplicate Data)

### 3.3 Transformasi 
Melakukan transformasi lanjutan pada data, termasuk:
- Mengubah Tipe Data (Changing Data Types)
- Menguraikan Tanggal (Parsing Dates)
- Menangani Encoding File (Handling File Encodings)
- Menghapus Outliers (Removing Outliers)
- Penskalaan Fitur (Scaling Features)
- Membuat Variabel Dummy (Creating Dummy Variables)
- Rekayasa Fitur (Engineering Features)


## 4. Memuat Data (Load)
Mengirim data yang telah ditransformasi ke Firebase untuk penyimpanan dan akses di masa mendatang 

## 6. Tools
- Python
- Library in Python: Pandas, Numpy, Matplotlib, Seaborn, Plotly, etc.
- Jupyter Notebook
- Google Cloud Storage
- SQLite
- API World Bank
- XML
- JSON
- CSV
- DB
- Apache Airflow
- Dataflow
- other, etc.

## 7. Dataset
Berikut adalah beberapa dataset yang digunakan dalam proyek ini:
- **electricity_access_percent.csv**: Data tentang persentase akses listrik di berbagai negara.
- **gdp_data.csv**: Data tentang Produk Domestik Bruto (GDP) negara-negara.
- **mystery.csv**: Sebuah dataset dengan konten yang belum ditentukan, memerlukan investigasi lebih lanjut.
- **population_data.csv**: Data populasi negara-negara dalam format CSV.
- **population_data.db**: Database SQLite yang berisi data populasi negara-negara.
- **population_data.json**: Data populasi negara-negara dalam format JSON.
- **population_data.xml**: Data populasi negara-negara dalam format XML, yang diurai menggunakan library seperti BeautifulSoup.
- **projects_data.csv**: Data tentang proyek-proyek yang telah atau sedang dilaksanakan oleh Bank Dunia.
- **rural_population_percent.csv**: Data tentang persentase populasi pedesaan di berbagai negara.
- **API World Bank**: API yang menyediakan data populasi negara-negara.
