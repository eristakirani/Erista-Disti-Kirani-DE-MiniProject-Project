
ETL Pipeline and Visualization 

ETL, yang merupakan singkatan dari Extract, Transform, Load, adalah proses penting dalam pengelolaan data yang melibatkan tiga tahap utama: ekstraksi data dari berbagai sumber, transformasi data ke dalam format yang sesuai, dan pemuatan data ke dalam sistem tujuan. Dalam konteks notebook ini, tujuan utamanya adalah untuk menjalankan serangkaian langkah yang diperlukan untuk membersihkan dan menyatukan berbagai kumpulan data menjadi satu tabel komprehensif. Tabel ini nantinya akan berfungsi sebagai fondasi untuk menjalankan model prediktif yang mampu memperkirakan biaya total proyek Bank Dunia dengan akurasi yang tinggi.

Proses ETL ini sangat penting karena memungkinkan integrasi data dari berbagai sumber yang berbeda, yang mungkin memiliki format, struktur, dan kualitas yang beragam. Dengan membersihkan data, kita dapat menghilangkan kesalahan dan inkonsistensi, sementara transformasi data memastikan bahwa informasi tersebut diubah menjadi format yang dapat dianalisis secara efektif. Akhirnya, dengan memuat data ke dalam satu tabel yang terintegrasi, kita menciptakan basis data yang konsisten dan siap digunakan untuk analisis prediktif.

Melalui proses ETL yang efektif, kita dapat memastikan bahwa data yang digunakan dalam model prediksi adalah berkualitas tinggi dan siap untuk analisis lebih lanjut. Ini tidak hanya meningkatkan keakuratan prediksi biaya proyek, tetapi juga membantu dalam pengambilan keputusan yang lebih baik berdasarkan data yang telah diolah dan disiapkan dengan seksama. Oleh karena itu, notebook ini tidak hanya berfungsi sebagai alat untuk membersihkan dan menggabungkan data, tetapi juga sebagai langkah krusial dalam menciptakan dasar yang kuat untuk analisis data yang canggih dan handal.

Tools dan Library 

**Tools** 

-Visual Studio

-Jupyter notebook

-Python


**Library** 

-Library Preprocessing Data

`  `Pandas

`  `Numpy

`  `Json

`  `re

-Library Visualisasi Data

`  `Matplotlib

`  `Seaborn

`  `Plotly 

-Library Scarp API

`  `BeautifulSoup

`  `Sqlite3

`  `requests

`  `lxml  

-Library Models Machine  Learning

`  `MinMaxScaler

`  `SimpleImputer

-Library Database

`  `Google Cloud

`  `Sqlalchemy



Struktur Program 

1. Extract Data: Ekstraksi data dari berbagai sumber (CSV, JSON, XML, SQLite, dan API) menggunakan teknik dan library yang sesuai.Penyesuaian tipe data, pengecekan dan penanganan missing values, duplikasi data, dan lain-lain.

2. Transform Data: Kombinasi dan penggabungan dataset dari berbagai sumber untuk membentuk dataset yang konsisten. Pembersihan data untuk memastikan kualitas dan konsistensi. Penyesuaian tipe data. Encoding dataset dengan encoding tertentu jika diperlukan. Imputasi data untuk menangani missing values. Penghapusan duplikasi data. Pembuatan dummy variables untuk kolom kategorikal. Penggantian nilai menggunakan regex dan replace. Penghapusan outliers dan visualisasi data sebelum dan sesudah penghapusan outliers. Scaling fitur data untuk konsistensi skala. Feature engineering untuk menambah informasi yang berguna pada dataset.

3. Load Data: Memuat data hasil transformasi ke dalam database, file, atau cloud storage dengan kolom yang ditentukan.

4. Data Visualization: Visualisasi data menggunakan berbagai teknik visualisasi untuk membuat presentasi data yang informatif dan menarik.  Analisis data yang informatif dan menarik menggunakan berbagai teknik analisis.

