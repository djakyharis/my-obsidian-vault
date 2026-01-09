
2025-11-04 07:24

# Pengertian Data
Tata Sutabri dalam buku Konsep Sistem Informasi, "data adalah kenyataan untuk menggambarkan suatu kejadian serta suatu bentuk yang masih mentah dan belum dapat bercerita banyak sehingga perlu diolah lebih lanjut melalui suatu model untuk menghasilkan informasi."

Bisa disimpulkan kalau data dalam AI itu adalah kumpulan fakta yang menjadi faktor utama yang mempengaruhi model akhir.

## Data, Dataset, dan Basis Data
Data adalah fakta, nyata, dan informasi yang tersimpan di dalamnya dapat berbentuk teks, angka, gambar, suara, dan banyak bentuk lainnya. Data dalam konteks dataset dan basis data mengacu pada kumpulan informasi yang relevan serta dikumpulkan, disimpan, dan dikelola untuk tujuan tertentu. Dengan kata lain, data merupakan entri tunggal atau informasi individual.

Dataset adalah kumpulan data yang disusun secara terstruktur. Biasanya, dataset dipresentasikan dalam bentuk tabel alias kumpulan baris dan kolom yang dapat disimpan pada beberapa format, seperti CSV, Excel, JSON, dan format lainnya. Digunakan untuk tujuan tertentu, seperti pembangunan machine learning, analisis statistik, dan visualisasi data.

Basis data merupakan kumpulan data yang diatur dan disimpan secara terorganisir sehingga dapat diambil dan diakses dengan mudah. Selain itu, ia juga dapat menyimpan berbagai macam tipe data, termasuk teks, nomor, gambar, dan tipe data lainnya.

### Tipe Data
- Data Terstruktur
	Data terstruktur merupakan jenis data yang memiliki format dan tata letak yang tetap atau teratur. Artinya, data ini diatur dalam suatu pola atau struktur yang konsisten sehingga mudah dibaca, diproses, dan dianalisis oleh komputer atau manusia. Jenis data terstruktur umumnya memiliki definisi yang jelas seperti kolom dalam tabel atau bidang dalam dokumen teks. Data ini memiliki 2 turunan, yaitu data kuantitatif dan data kategorikal. Mari kita bahas keduanya!


- Data Untructured
	Data tidak terstruktur adalah jenis data yang tidak memiliki format atau struktur yang jelas. Data ini cenderung bervariasi bentuknya dan sulit untuk diorganisasi dalam kategori atau kolom tertentu. Data tidak terstruktur seringkali memiliki sifat lebih bebas, tidak terbatas, dan lebih kompleks dibandingkan dengan data terstruktur. Berikut merupakan contoh dari data tidak terstruktur.

-   **Data Kuantitatif**
	Data kuantitatif adalah jenis data yang dapat diukur atau diungkapkan dalam bentuk angka. Data ini digunakan untuk mengukur atau menggambarkan jumlah, besaran, atau atribut-atribut yang dapat diukur secara numerik. Perhatikan contoh data kuantitatif berikut.
	- _**Data Kontinu**_
		Data kontinu dapat direpresentasikan dalam berbagai nilai numerik, seperti bilangan desimal, bulat, dan lain-lain. Beberapa contoh tipe data kontinu yang umum adalah tinggi, berat, waktu, suhu, usia, dan lain-lain.
		![[dos-f0b910e6ed7b0006e7498a2f8c96326f20240119170810.png]]
	- _**Data Diskrit**_
		Data diskrit merupakan data numerik yang hanya bisa direpresentasikan dengan bilangan bulat dan tidak dapat dibagi ke dalam unit yang lebih kecil.
		![[Pasted image 20251106155841.png]]
		

- **Data Kategorikal**
	Data kategorikal mengacu pada bentuk informasi yang dapat disimpan dan diidentifikasi berdasarkan nama atau labelnya. Data kategorikal merupakan data yang dapat dikelompokkan dan terbagi berdasarkan karakteristik atau ciri khasnya masing-masing. Dari data kategorikal, ada dua pembagian, yaitu ordinal dan nominal.
	- _**Data Ordinal**_
		Data ordinal adalah jenis pengelompokan data yang memiliki urutan atau harus disusun secara berurutan dengan mekanisme peringkat.
		![[Pasted image 20251106160100.png]]
	- _**Data Nominal**_
		Berkebalikan dengan data ordinal, data nominal adalah jenis pengelompokan data yang tidak memiliki keterkaitan dengan data lainnya dan tidak memiliki arti khusus. Jadi, data ini dapat dibedakan tanpa harus mengurutkan atau dibandingkan dengan data lainnya. ![[dos-13fcddecfd74310a1949f61bb1cb185120240119171122.png]]


## Garbage in, Garbage out (GIGO)
Sampah di sini berarti data yang buruk, tidak wajar, tidak relevan, dan keliru sehingga nantinya akan menghasilkan AI yang tidak sesuai dengan harapan pengembang.
![[dos-46ba7fae9b392b7bc2551bb2b7a1260d20240119171218.png]]
Dari gambar di atas kita bisa mendapatkan kesimpulan bahwa keluaran dari AI yang kita bangun sangat bergantung pada data masukkan yang diterima. Jika kita memiliki data masukkan yang buruk, besar kemungkinan AI yang dihasilkan tidak sesuai harapan.


## Masalah dalam Data
Permasalahan yang terjadi pada data biasanya disebabkan oleh kesalahan ketika pengumpulan atau pencatatan data. Data yang diperoleh dengan cara yang salah atau bahkan diambil dari sumber yang tidak dapat dipercaya juga bisa disebut sebagai data sampah. 

Dari hal tersebut muncullah permasalahan umum pada data. Permasalahan umum yang sering terjadi terdapat pada kualitas data di antaranya, seperti data yang tidak relevan (_irrelevant_), data berbeda dengan yang lain (_outlier_), data duplikat, data kosong, data yang tidak benar, dan masih banyak lagi. Pada kesempatan ini, kita akan membahas beberapa permasalahan umum yang terjadi dan bagaimana cara menanganinya. 

Dari beberapa permasalahan di atas, setidaknya kita akan sering menemui data kosong. Kita dapat menanganinya dengan beberapa cara, seperti menghapus data yang kosong tersebut atau mengisi data kosong dengan nilai rata-rata atau median jika datanya berupa numerik.


## Infrastruktur Data di Industri
Tujuan dari infrastruktur data adalah untuk menyediakan pengelolaan data yang baik, memproses data, dan menganalisis data yang ada. 

1. **Manajemen data**
	Dengan menggunakan infrastruktur data yang baik maka tempat penyimpanan data akan terpusat. Hal ini akan membuat data dalam sebuah organisasi menjadi lebih aman dan mudah untuk dikelola.

2. **Pemrosesan data**
	Infrastruktur data menyediakan daya komputasi dan sumber daya yang dibutuhkan untuk memproses dan menganalisis data dengan jumlah besar. Hal ini memungkinkan organisasi untuk melakukan analisis dan membuat pemodelan yang kompleks sehingga dapat membantu untuk mendapatkan informasi dan keputusan yang tepat berdasarkan data.

3. **Integrasi data**
	Seperti yang sudah dijelaskan sebelumnya, dengan menggunakan infrastruktur data yang baik, kita dapat mengintegrasikan data dari berbagai sumber.

4. **Keamanan data**
	Infrastruktur data menyediakan fitur dan protokol keamanan untuk melindungi data sensitif dari akses yang tidak sah, pencurian, atau penyalahgunaan. Hal ini memastikan kepatuhan terhadap peraturan dan praktik terbaik untuk keamanan dan privasi data.






## References
Dicoding. Belajar Dasar AI. Data untuk AI
