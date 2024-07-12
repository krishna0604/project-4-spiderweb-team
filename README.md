# project-4-spiderweb-team

<h1><b> PROJECT DATA ENGINEER BY SPIDERWEB TEAM </b></h1> 
<hr>
<h2> Kelompok 5 FTDE-01 Digital Skola </h2> 
Selamat datang, kami sudah menyelesaikan berbagai problem bisnis berupa mini project dari Bootcamp data Engineer, Digital Skola. Kami telah menyelesaikan tahap data Streaming Processing dengan best practicenya. 
<br>
Teman - teman bisa mengakses full langkah demi langkah tahap pengerjaan project dengan mengakses file "Step by step PROJECT 4 by Spiderweb.pdf.pdf" yang tertera dalam repositori ini
<hr>

<h2> Nama anggota Kelompok : ( Nama lengkap - username github - email ) </h2>

1. I Gusti Agung Krishna Dwipayana - krishna0604 - agungkrishna04@gmail.com
2. Hafidha Harfiana Dewi - HafidhaHD - harfiana.hafidha@gmail.com
3. hermawan Adi Prasetyo - adiprasetyohermawan - adiprasetyohermawan00@gmail.com
4. Humairoh - humairoh22 - humairohhumay@yahoo.co.id
5. I Putu Ferry Wistika - putuwistika - 12820001@mahasiswa.itb.ac.id
6. Fenny Inriana - Fennyinriana
<hr>

<h2> Tahap Pengerjaan : </h2>  

1. <b>Tahap Pertama</b> : Kami melengkapi system requirements, yaitu install kafka docker zookeper, running mongodb, postgres di Docker. Dan juga running airflow. Lalu membuat file DAG python untuk mengorkestrasi data dari PostgreSQL ke Apache Airflow. File python bernama “load_postgres_table.py”. Setelah itu trigger DAG di UI Airflow.

<br>

2. <b>Tahap Kedua</b> : Selanjutnya adalah mengerjakan Data Pipeline.  Kami running Tes-Model.ipynb melalui Jupyter lokal untuk akses file FraudModel.py dari folder modelling. kami akan memakai modelnya dengan mengambil dari data transaksi pada file FraudModel.py untuk inputan data. Lalu kami akan memakai modelnya ambil dari data transaksi pada file FraudModel.py untuk inputan path. Dari sini kita dapat melihat bahwa posisi FraudModel.py sudah benar, yaitu pada folder modelling. 

<br>

3. <b>Tahap Ketiga</b> :  Kami melakukan analisis bahwa terdapat 9 Library Python yang digunakan di folder ‘DE - STREAM PROCESSING’ yang harus kami install terlebih dahulu. Kami akan running file Tes-Model.ipynb  dan kode berhasil dijalankan.

<br>

4. <b>Tahap Keempat</b> : Kami masuk ke dalam folder producer dan melakukan connection PostgreSQL databse. Lalu kami mengakses datadump.ipynb untuk masukin data PostgreSQL ini ke database lokal. Data dump berhasil di running dan success

<br>

5. <b>Tahap Kelima</b> : Kami akan membuka folder producer dan mengakses file producer.ipynb untuk melakukan simulasi transaksi yang terjadi di mobile dan terjadi di kafka. Jadi ada producer, lalu lempar data ke kafka dengan nama ftde01-project4.

<br>

6. <b>Tahap Keenam</b> : Lalu kami akan mengambil data ini di Kafka, sehingga kami mengakses notebook consumer.ipynb dan notebook Tes-Consumer.ipynb. Pada consumer.ipynb kami menyesuaikan kode agar sesuai dengan versi Python terbaru 3.12.2. Dan kode blok ini berhasil dijalankan ( data tersebut berhasil ditangkap ). Pada saat ini kami akan memberhentikan producer.ipynb untuk mendapat data hasil producer yang secukupnya. Kami mengeksekusi setiap cell di Tes-Consumer. Kami berhasil running kode-kode tersebut.

<br>

7. <b>Tahap Ketujuh</b> : Consumer sudah berhasil kami ambil, kami akan melakukan join dengan mengubah data producer dalam bentuk dict ke dataframe. Join data sudah berhasil dilakukan, lalu kami akan melakukan prediksi Fraud dan prediksi berhasil dilakukan.

<br>

8. <b>Tahap Kedelapan</b> : Langkah terakhir adalah insert ke MongoDB. Dari data ini dipindahkan lagi ke dalam dalam google sheet. lalu visualisasikan ke google studio.

<br>

Lebih lengkapnya silahkan akses file "Step by step PROJECT 4 by Spiderweb.pdf.pdf" yang tertera dalam repositori ini
