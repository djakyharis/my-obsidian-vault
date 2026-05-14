---
date: 2025-11-04 07:24
status: evergreen
tags: [artificial-intelligence, machine-learning, data]
source: Dicoding - Belajar Dasar AI
---

# Data untuk AI

## 📝 Notes

Tata Sutabri dalam buku Konsep Sistem Informasi, "data adalah kenyataan untuk menggambarkan suatu kejadian serta suatu bentuk yang masih mentah dan belum dapat bercerita banyak sehingga perlu diolah lebih lanjut melalui suatu model untuk menghasilkan informasi."

Bisa disimpulkan kalau data dalam AI itu adalah kumpulan fakta yang menjadi faktor utama yang mempengaruhi model akhir.

## Data, Dataset, dan Basis Data
Data adalah fakta, nyata, dan informasi yang tersimpan di dalamnya dapat berbentuk teks, angka, gambar, suara, dan banyak bentuk lainnya. Data dalam konteks dataset dan basis data mengacu pada kumpulan informasi yang relevan serta dikumpulkan, disimpan, dan dikelola untuk tujuan tertentu. Dengan kata lain, data merupakan entri tunggal atau informasi individual.

Dataset adalah kumpulan data yang disusun secara terstruktur. Biasanya, dataset dipresentasikan dalam bentuk tabel alias kumpulan baris dan kolom yang dapat disimpan pada beberapa format, seperti CSV, Excel, JSON, dan format lainnya. Digunakan untuk tujuan tertentu, seperti pembangunan machine learning, analisis statistik, dan visualisasi data.

Basis data merupakan kumpulan data yang diatur dan disimpan secara terorganisir sehingga dapat diambil dan diakses dengan mudah. Selain itu, ia juga dapat menyimpan berbagai macam tipe data, termasuk teks, nomor, gambar, dan tipe data lainnya.

### Tipe Data
- **Data Terstruktur**
	Data terstruktur merupakan jenis data yang memiliki format dan tata letak yang tetap atau teratur. Artinya, data ini diatur dalam suatu pola atau struktur yang konsisten sehingga mudah dibaca, diproses, dan dianalisis oleh komputer atau manusia. Jenis data terstruktur umumnya memiliki definisi yang jelas seperti kolom dalam tabel atau bidang dalam dokumen teks. Data ini memiliki 2 turunan, yaitu data kuantitatif dan data kategorikal.

- **Data Unstructured**
	Data tidak terstruktur adalah jenis data yang tidak memiliki format atau struktur yang jelas. Data ini cenderung bervariasi bentuknya dan sulit untuk diorganisasi dalam kategori atau kolom tertentu. Data tidak terstruktur seringkali memiliki sifat lebih bebas, tidak terbatas, dan lebih kompleks dibandingkan dengan data terstruktur.

- **Data Kuantitatif**
	Data kuantitatif adalah jenis data yang dapat diukur atau diungkapkan dalam bentuk angka. Data ini digunakan untuk mengukur atau menggambarkan jumlah, besaran, atau atribut-atribut yang dapat diukur secara numerik.
	- _**Data Kontinu**_ — dapat direpresentasikan dalam berbagai nilai numerik (desimal, bulat, dll). Contoh: tinggi, berat, waktu, suhu, usia.
		![[_assets/dos-f0b910e6ed7b0006e7498a2f8c96326f20240119170810.png]]
	- _**Data Diskrit**_ — data numerik yang hanya bisa direpresentasikan dengan bilangan bulat dan tidak dapat dibagi ke dalam unit yang lebih kecil.
		![[_assets/Pasted image 20251106155841.png]]

- **Data Kategorikal**
	Data kategorikal mengacu pada bentuk informasi yang dapat disimpan dan diidentifikasi berdasarkan nama atau labelnya. Dari data kategorikal, ada dua pembagian:
	- _**Data Ordinal**_ — memiliki urutan atau harus disusun secara berurutan dengan mekanisme peringkat.
		![[_assets/Pasted image 20251106160100.png]]
	- _**Data Nominal**_ — tidak memiliki keterkaitan dengan data lainnya dan tidak memiliki arti khusus. Dapat dibedakan tanpa harus mengurutkan.
		![[_assets/dos-13fcddecfd74310a1949f61bb1cb185120240119171122.png]]

## Garbage in, Garbage out (GIGO)
Sampah di sini berarti data yang buruk, tidak wajar, tidak relevan, dan keliru sehingga nantinya akan menghasilkan AI yang tidak sesuai dengan harapan pengembang.

![[_assets/dos-46ba7fae9b392b7bc2551bb2b7a1260d20240119171218.png]]

Keluaran dari AI yang kita bangun sangat bergantung pada data masukkan yang diterima. Jika kita memiliki data masukkan yang buruk, besar kemungkinan AI yang dihasilkan tidak sesuai harapan.

## Masalah dalam Data
Permasalahan yang terjadi pada data biasanya disebabkan oleh kesalahan ketika pengumpulan atau pencatatan data. Permasalahan umum pada kualitas data: data tidak relevan (_irrelevant_), data berbeda dengan yang lain (_outlier_), data duplikat, data kosong, dan data yang tidak benar.

Untuk data kosong, dapat ditangani dengan menghapus data tersebut atau mengisi dengan nilai rata-rata/median jika datanya berupa numerik.

## Infrastruktur Data di Industri
Tujuan dari infrastruktur data adalah untuk menyediakan pengelolaan data yang baik, memproses data, dan menganalisis data yang ada.

1. **Manajemen data** — penyimpanan data terpusat agar lebih aman dan mudah dikelola.
2. **Pemrosesan data** — daya komputasi untuk memproses dan menganalisis data dalam jumlah besar.
3. **Integrasi data** — mengintegrasikan data dari berbagai sumber.
4. **Keamanan data** — fitur dan protokol keamanan untuk melindungi data sensitif.

## Data Engineer
Sebagai Data Engineer, kita bisa memprediksi dan mempersiapkan sebelum terjadinya kejadian yang mau diprediksi, juga harus mencari tahu bagaimana mendapatkan data yang berkorelasi.

- **Data Processing** — Konversi "Raw data" menjadi informasi yang berarti.
- **Data Infrastructure** — Set dari teknologi, proses, dan resources yang mendukung collection, storage, dan analysis dari data.

Cara mengambil data: Sensor, Database.

## 🔗 Related
- [[AI Workflow]]
- [[Algorithm]]

## References
- Dicoding - Belajar Dasar AI
- Tata Sutabri - Konsep Sistem Informasi
