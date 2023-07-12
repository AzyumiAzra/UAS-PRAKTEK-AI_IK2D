# Laporan Akhir Kecerdasan Buatan

**Anggota Kelompok :**

1. Azyumi Azra - NIM. 3.34.21.3.05
2. Yudha Zaniargo - NIM. 3.34.21.3.25



## Domain Proyek

Harga mobil adalah topik yang sangat relevan dan menarik bagi banyak orang. Dalam kehidupan sehari-hari, mobil menjadi salah satu aset berharga yang banyak orang ingin miliki. Oleh karena itu, mempelajari faktor-faktor yang mempengaruhi harga mobil dapat memberikan wawasan berharga bagi individu yang tertarik dalam membeli atau menjual mobil.

Data harga mobil dapat dengan mudah ditemukan secara online melalui situs web penjualan mobil, platform perdagangan, atau sumber data terbuka lainnya. Banyak situs web memiliki fitur pencarian yang memungkinkan pengguna untuk mengakses informasi tentang harga mobil baru dan bekas. Ketersediaan data yang melimpah memudahkan kita dalam membangun dan menganalisis model prediksi harga mobil. Penggunaan Machine Learning: Domain proyek dataset harga mobil memberikan peluang yang bagus untuk mengaplikasikan teknik machine learning dan pemodelan prediktif. Dengan menggunakan dataset harga mobil yang luas, kita dapat mengembangkan model yang dapat memprediksi nama mobil, jenis bahan bakar, aspirasi, nomor pintu, badan mobil, roda penggerak, lokasi mesin, jarak sumbu roda, panjang mobil, lebar mobil, tinggi mobil, berat trotoar, jenis mesin, nomor silinder, ukuran mesin, sistem bahan bakar, boreratio, langkah, rasio kompresi, tenaga kuda, rpm puncak, kotampg, jalan raya mpg, harga. Ini akan membantu pembeli atau penjual dalam membuat keputusan yang lebih baik dan memberikan panduan tentang harga pasar yang wajar.

Pengetahuan tentang faktor-faktor yang mempengaruhi harga mobil dapat memiliki nilai bisnis yang signifikan. Dealer mobil, perusahaan asuransi, perusahaan pembiayaan, dan bahkan individu yang tertarik dalam perdagangan mobil dapat menggunakan analisis harga mobil untuk mengoptimalkan keputusan mereka. Misalnya, dealer mobil dapat menggunakannya untuk menentukan harga jual yang optimal, sementara perusahaan pembiayaan dapat menggunakannya untuk menilai risiko dan menentukan suku bunga yang sesuai.Industri otomotif mengalami perkembangan pesat dalam beberapa tahun terakhir dengan munculnya teknologi baru seperti kendaraan otonom, mobil listrik, dan fitur-fitur keamanan terbaru. Mempelajari harga mobil dan faktor-faktor yang mempengaruhinya juga memungkinkan kita untuk melihat tren dan pola di industri otomotif serta memahami bagaimana faktor-faktor tersebut berperan dalam penentuan harga mobil di masa depan.

Dalam kesimpulannya, memilih untuk membahas domain proyek dataset harga mobil memiliki relevansi yang tinggi, ketersediaan data yang melimpah, peluang untuk menerapkan machine learning, nilai bisnis yang signifikan, dan kaitannya dengan kemajuan teknologi otomotif. Semua ini membuatnya menjadi topik menarik dan bermanfaat untuk dieksplorasi.



## Business Understanding

Sebuah perusahaan mobil bercita-cita untuk memasuki pasar dunia dengan mendirikan unit manufaktur mereka di sana dan memproduksi mobil secara lokal untuk bersaing dengan rekan-rekan mereka.

Mereka telah mengontrak perusahaan konsultan mobil untuk memahami faktor-faktor yang menentukan harga mobil. Secara khusus, mereka ingin memahami faktor-faktor yang mempengaruhi harga mobil di pasar dunia, karena mungkin sangat berbeda dengan pasar yang sebelumnya. 

Berdasarkan berbagai survei pasar, perusahaan konsultan tersebut telah mengumpulkan kumpulan data besar dari berbagai jenis mobil di seluruh pasar dunia.



## Problem Statements

Berdasarkan permasalahan yang diuraikan sebelumnya, dari proyek kali ini adalah sebagai berikut  :

1. Variabel mana yang signifikan dalam memprediksi harga mobil
2. Seberapa baik variabel tersebut menggambarkan harga sebuah mobil



## Goals

Adapun tujuan yang ingin dicapai dari projek kali ini adala sebagai berikut  :

1. Untuk memodelkan harga mobil dengan variabel independen yang tersedia. Ini akan digunakan oleh manajemen untuk memahami bagaimana tepatnya harga bervariasi dengan variabel independen. Dengan demikian, mereka dapat memanipulasi desain mobil, strategi bisnis, dll.
2. Untuk memenuhi tingkat harga tertentu. Selanjutnya, model tersebut akan menjadi cara yang baik bagi manajemen untuk memahami dinamika penetapan harga pasar baru.



## Solution Statements

Adapun solusi yang kami ajukan untuk menyelesaikan permasalahan adalah sebagai berikut  :

1. Membaca dan Memahami Data

   Mengimpor data menggunakan perpustakaan panda dan memahami struktur data yang berada pada file CarPrice_Assigtment.csv

2.  Pembersihan dan Persiapan Data

   Tujuan utama dari pembersihan dan persiapan data adalah untuk memastikan bahwa data yang digunakan dalam analisis bersih, konsisten, relevan, dan siap untuk dianalisis. Dengan melakukan pembersihan dan persiapan data dengan baik, dapat meningkatkan kualitas analisis, mengurangi bias, dan menghasilkan wawasan yang lebih akurat dan bermanfaat. Contohnya yang kami terapkan memisahkan nama perusahaan dari kolom CarName, mendapatkan daftar semua perusahaan mobil yang terdapat dalam dataset tersebut, tanpa adanya duplikasi dan membenarkan atau mengganti kata kata yang masih salah ke kata yang seharusnya.

3.  Visualizing the data

   Bertujuan untuk menggambarkan, mengklarifikasi, dan menyampaikan informasi yang terkandung dalam dataset dengan cara yang mudah dipahami dan menarik. Visualisasi data membantu kita untuk menjelajahi, menganalisis, dan memahami data dengan lebih baik, serta mendukung pengambilan keputusan yang lebih baik berdasarkan wawasan yang ditemukan. Dari data kategori dan numerik.

4. Deriving new features

   Tujuan dari "Deriving new features" atau membuat fitur baru dalam analisis data adalah menurunkan fitur baru dalam analisis data adalah untuk memperkaya informasi, meningkatkan representasi, menggambarkan korelasi yang kompleks, meningkatkan performa model, mengurangi dimensi, dan memfasilitasi pemahaman yang lebih baik tentang data. Melalui proses ini, kita dapat mendapatkan wawasan yang lebih dalam dan komprehensif tentang data yang sedang dianalisis.

5.  Bivariate Analysis

   Dalam keseluruhan, tujuan dari analisis bivariat adalah untuk memahami hubungan, mengidentifikasi korelasi, menemukan pola atau tren, menguji hipotesis, mendukung pengambilan keputusan, dan memvalidasi model. Analisis bivariat membantu kita untuk mendapatkan wawasan yang lebih dalam tentang hubungan antara dua variabel dalam dataset dan memberikan dasar untuk pengambilan keputusan yang lebih baik.

6.  Dummy variables

   Tujuan dari dummy variables adalah untuk memberikan representasi numerik bagi variabel kategorikal dalam analisis atau pemodelan. Dengan menggunakan dummy variables, kita dapat memasukkan variabel kategorikal ke dalam model statistik, memahami pengaruhnya, membandingkan kategori, dan mengatasi nonlinearitas yang mungkin ada.

7.   Train-Test Split and feature scaling

   Tujuan dari train-test split adalah untuk mengevaluasi kinerja model, mencegah overfitting, dan membantu pengambilan keputusan yang lebih baik. Sementara itu, tujuan dari feature scaling adalah untuk meningkatkan kinerja algoritme, memudahkan interpretasi, mempercepat konvergensi, dan mencegah dominasi atribut. Keduanya merupakan langkah penting dalam proses pengembangan dan evaluasi model machine learning yang baik.

8. Model Building

   Tujuan dari model building adalah untuk menciptakan model yang dapat memprediksi, mengklasifikasikan, atau menggambarkan fenomena berdasarkan data yang ada. Model building membantu dalam prediksi, klasifikasi, deskripsi, pengambilan keputusan, peningkatan kinerja, dan penemuan pengetahuan. Dengan menggunakan model yang valid dan akurat, kita dapat mengambil keuntungan dari informasi yang terkandung dalam data dan menghasilkan wawasan yang berharga.

9.   Residual Analysis of Model

   Tujuan dari analisis residu adalah untuk mengevaluasi kualitas model, mendeteksi kekeliruan atau pelanggaran asumsi, verifikasi asumsi statistik, identifikasi outlier, penyesuaian model, dan validasi model. Dengan memeriksa residu, kita dapat memperoleh wawasan yang penting tentang kinerja dan validitas model yang dibangun dan memberikan informasi tentang area yang perlu perbaikan atau pengembangan lebih lanjut.

10.    Prediction and Evaluation

    Tujuan dari prediksi dan evaluasi adalah untuk menghasilkan prediksi yang akurat, mengukur kinerja model, mengoptimalkan model, menilai risiko, memahami data, dan membandingkan model yang berbeda. Melalui prediksi yang baik dan evaluasi yang cermat, kita dapat memperoleh wawasan yang berharga dan membuat keputusan yang lebih baik dalam berbagai domain dan aplikasi.

    

## Data Understanding

Variabel - variabel pada data CarPrice_Assightmen dataset adalah sebagai berikut:

car_ID : id dari mobil tersebut

symboling : simbol yang menggambarkan sesuai mobil yang ada

CarName : nama mobil

fueltype : jenis bahan bakar yang digunakan

aspiration : mengacu pada jenis sistem pengisian udara di mesin mobil, yaitu apakah mobil menggunakan aspirasi alami (NA) atau supercharged/turbocharged (turbo).

doornumber : menunjukkan jumlah pintu yang ada pada mobil

carbody : Mengacu pada jenis badan mobil, seperti sedan, hatchback, coupe, SUV, atau lainnya.

drivewheel :jenis roda penggerak pada mobil, apakah mobil menggunakan penggerak roda depan (FWD), penggerak roda belakang (RWD), atau penggerak semua roda (AWD).

enginelocation : Menunjukkan lokasi mesin pada mobil, apakah mesin berada di bagian depan (front), tengah (mid), atau belakang (rear).

wheelbase : arak antara sumbu roda depan dan belakang pada mobil, yang dapat mempengaruhi stabilitas dan ukuran kabin mobil.

carlength : Panjang total mobil dari ujung depan hingga ujung belakang.

carwidth : Lebar total mobil dari sisi ke sisi, mengukur ukuran horizontal mobil.

carheight : Tinggi total mobil dari tanah hingga titik tertinggi mobil.

curbweight : berat mobil dalam keadaan kosong tanpa penumpang atau beban tambahan

enginetype : Menunjukkan jenis mesin yang digunakan pada mobil, seperti mesin bensin (gasoline), mesin diesel, atau jenis mesin lainnya

cylindernumber : jumlah silinder yang ada dalam mesin mobil, yang dapat mempengaruhi tenaga dan kinerja mobil.

enginesize : Mengacu pada kapasitas mesin mobil, sering diukur dalam liter atau cc, dan dapat berhubungan dengan kinerja mesin.

fuelsystem : Menunjukkan jenis sistem bahan bakar yang digunakan pada mobil, seperti injeksi bahan bakar (fuel injection), karburator, atau jenis sistem lainnya.

boreratio : perbandingan diameter silinder dengan langkah piston, yang dapat mempengaruhi karakteristik mesin.

stroke : arak pergerakan piston dalam satu siklus kerja, yang juga mempengaruhi karakteristik mesin.

compressionratio : Mengacu pada perbandingan volume ruang bakar saat kompresi maksimum dengan volume ruang bakar saat kompresi minimum, yang mempengaruhi efisiensi dan performa mesin.

horsepower : Mengukur daya atau tenaga maksimum yang dihasilkan oleh mesin mobil.

peakrpm : putaran mesin maksimum yang dianjurkan untuk mencapai performa maksimum.

citympg : estimasi konsumsi bahan bakar mobil dalam kondisi perjalanan di kota.

highwaympg : estimasi konsumsi bahan bakar mobil dalam kondisi perjalanan di jalan raya.

price : arga mobil dalam unit mata uang tertentu, yang mencerminkan nilai atau harga pasar mobil tersebut.

Tahapan-tahapan di atas membantu untuk memahami dan menggali informasi yang ada dalam dataset CarPrice, serta mempersiapkan dasar untuk tahapan berikutnya dalam proses analisis data, seperti preprocessing data, pemodelan, evaluasi, dan interpretasi hasil.

## Data Preparation

pada tahapan ini, saya melakukan beberapa proses sebagai berikut

1.Pembersihan Data: Selanjutnya, periksa dataset Anda dan bersihkan nilai-nilai kosong atau outlier jika ada. Hal ini dapat dilakukan dengan menghapus baris atau kolom dengan nilai kosong atau melaksanakan imputasi data menggunakan metode seperti mean, median, atau modus. Jika terdapat outlier signifikan, pertimbangkan apakah harus dihilangkan atau dilakukan transformasi pada nilainya.

2.Pemeriksaan Hubungan Variabel: Lakukan eksplorasi awal terhadap hubungan antara variabel dependen dan independen menggunakan metode visualisasi seperti scatter plot atau matriks korelasi. Proses ini membantu dalam memahami pola hubungan antar variabel sebelum menjalankan analisis regresi linear.

3.Encoding Variabel Kategorikal: Jika terdapat variabel kategorikal dalam dataset Anda, pertimbangkan untuk mengubahnya menjadi bentuk angka melalui proses encoding seperti one-hot encoding atau label encoding agar dapat dimasukkan ke dalam model regresi linear.

4.Pembagian Dataset Menjadi Data Training dan Testing Sets: Bagilah dataset menjadi dua bagian yaitu training set (untuk melatih model) dan testing set (untuk mengevaluasi performa model). Biasanya, alokasi yang umum digunakan adalah sekitar 70-80% untuk training set dan 20-30% untuk testing set. Pastikan bahwa kedua set tersebut mewakili dengan baik data asli.

5.Melakukan Feature Scaling: Jika perlu, lakukan feature scaling pada variabel independen agar memiliki skala yang serupa sehingga tidak mengganggu hasil regresi linear. Metode yang umum digunakan antara lain normalisasi atau standarisasi.![image-20230712225910644](C:\Users\yudha\AppData\Roaming\Typora\typora-user-images\image-20230712225910644.png)

![image-20230712230111834](C:\Users\yudha\AppData\Roaming\Typora\typora-user-images\image-20230712230111834.png)

## Modelling

Pada tahap ini akan dibuat model untuk menjawab 2 *problem statement* yang berbeda, yakni mengenai segmentasi karyawan dan prediksi yang layak dipromosikan. Untuk segmentasi, saya menggunakan algoritma K-Means Clustering, sedangkan untuk klasifikasi saya menggunakan Regresion Linear dan ini merupakan Train-Tesr Split nya

![image-20230712232836184](C:\Users\LENOVO\AppData\Roaming\Typora\typora-user-images\image-20230712232836184.png)

Subset atribut independen yang dipilih menggunakan Recursive Feature Elimination (RFE) pada dataset pelatihan dan menghasilkan subset atribut independen yang telah dipilih menggunakan RFE, sehingga kita dapat melatih model pada subset atribut yang paling penting atau relevan dalam memprediksi atribut target.

![image-20230712232351534](C:\Users\LENOVO\AppData\Roaming\Typora\typora-user-images\image-20230712232351534.png)

## Clustering

Disini kami melakukan evaluasi model regresi dengan memplotting nilai yang diprediksi (`y_pred`) versus nilai sebenarnya (`y_test`).

![image-20230712232550294](C:\Users\LENOVO\AppData\Roaming\Typora\typora-user-images\image-20230712232550294.png)



Dan juga evaluasi model regresi dengan menggunakan statistic

![image-20230712232702430](C:\Users\LENOVO\AppData\Roaming\Typora\typora-user-images\image-20230712232702430.png)



## Classification

Regresi linear sebenarnya lebih umum digunakan untuk masalah regresi (prediksi nilai numerik) daripada masalah klasifikasi (prediksi kelas atau label). Namun, dalam beberapa kasus, Anda dapat menggunakan regresi linear untuk melakukan klasifikasi dengan memanfaatkan threshold atau batas tertentu.

Berikut merupakan klasifikasi yang menggunakan metode Ordinary Least Squares (OLS) menggunakan pustaka statsmodels.

![image-20230712233108125](C:\Users\LENOVO\AppData\Roaming\Typora\typora-user-images\image-20230712233108125.png)

![image-20230712233239830](C:\Users\LENOVO\AppData\Roaming\Typora\typora-user-images\image-20230712233239830.png)

## Evaluation

sangat penting untuk memahami sejauh mana model yang digunakan berhasil dalam melakukan prediksi. Berikut adalah beberapa metrik evaluasi umum yang dapat digunakan

Untuk kasus klasifikasi, terdapat 4 metrics yang dapat digunakan, yaitu accuracy, precision, recall, dan f1-score

1. Akurasi (Accuracy): Mengukur persentase jumlah prediksi yang benar dari keseluruhan data.
2. Presisi (Precision): Mengukur seberapa presisi model dalam mengidentifikasi kelas positif dengan memperhatikan false positive rate.
3. Recall (Sensitivity atau True Positive Rate): Mengukur seberapa baik model dalam menemukan semua instansi kelas positif dengan memperhatikan false negative rate.
4. F1-Score: Rata-rata harmonis antara presisi dan recall, memberikan gambaran keseluruhan performa model secara seimbang.



## REFERENSI

[1] https://www.kaggle.com/code/goyalshalini93/input

[2] https://idschool.net/olah-data/regresi-linear-sederhana-dengan-python/

[3] https://chat.openai.com/

[4] https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://dqlab.id/belajar-python-dengan-kenali-sedikit-mengenai-regresi-linier&ved=2ahUKEwiejt3ayImAAxU08zgGHZ9XB_sQFnoECA4QAQ&usg=AOvVaw3cCwdGGdvVX52ni9m2kAqK

[5] https://dqlab.id/kenali-analisis-regresi-linear-metode-pengolahan-data-yang-sering-digunakan



**---Ini adalah bagian akhir laporan---**
