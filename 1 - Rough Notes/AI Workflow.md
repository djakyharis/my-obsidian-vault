
2025-11-06 13:17

# AI Workflow

![[dos-995b2dfe375d3fb637f70e926b21bc1e20231217182606.jpeg]]

1. ***Digitalise & Collect***
	_Digitalise & collect_ merupakan tahapan pengumpulan dan penyimpanan data yang akan digunakan pada proses pembangunan AI. Perlu kalian pahami, _digitalise_ di sini berarti kita perlu melakukan perubahan data agar dapat disimpan pada penyimpanan komputer.
	
	Jika Anda ingin membuat AI dengan permasalahan pribadi, proses pengumpulan data tidak semudah ketika mengunduh _dataset_ (kumpulan data) yang sudah jadi. Anda perlu mengumpulkan dan mengekstrak sendiri data dari berbagai sumber, seperti database, file, data sensor, dan sumber lainnya. Pada tahap ini Anda juga perlu berurusan dengan berbagai jenis tipe data, **seperti structured data (seperti berkas excel atau basis data SQL) dan unstructured data (seperti berkas teks, email, video, audio, gambar, data sensor, dan lainnya).**

2. _**Transform**_
	Pada tahapan ini, data yang telah dikumpulkan akan diproses secara berulang mulai dari persiapan data, mengubah data menjadi format yang dibutuhkan, hingga mengevaluasi data dengan mengidentifikasi data yang tidak dibutuhkan.

3. _**Train**_
	pada tahap pelatihan/train, kita akan menentukan algoritma yang cocok untuk pengembangan AI ini. Proses pelatihan/train ini bertujuan untuk membuat komputer dapat mempelajari data yang diberikan sehingga komputer dapat melakukan tugas berdasarkan data yang telah ia pelajari.
	
	Jie Ding, dkk yang berjudul “_Model Selection Techniques -An Overview_” menyatakan bahwa tidak ada model yang cocok secara universal untuk data dan tujuan apa pun. Oleh karena itu, kita harus melakukan _trial and error_ sendiri agar menemukan algoritma yang cocok dengan data yang kita miliki sehingga dapat menghasilkan AI dengan performa optimal.

4. _**Execute**_
	Setelah melalui tahap _train_, model AI yang telah dilatih dan disempurnakan dapat digunakan untuk melakukan hal yang bisa manusia lakukan. Selama fase ini, keakuratan model juga dievaluasi secara terus-menerus. Proses eksekusi dianalisis ulang untuk memastikan bahwa sistem memenuhi harapan dan memberikan umpan balik untuk perbaikan.

5. _**Provide Insights to Make Decisions**_
	Ketika model AI sudah dapat melakukan tugasnya dengan baik, sekarang kita harus melakukan ekstraksi dari pengetahuan yang diberikan oleh model tersebut. Proses ini membantu pengambilan keputusan serta meningkatkan pemahaman kita dalam pengembangan AI selanjutnya.

Jika ingin membangun model AI yang datanya terus berubah, Anda perlu memperbarui dataset dan melatih ulang model Anda secara reguler atau biasa disebut _retraining model_. Selain itu, Anda juga perlu membuat sistem yang dapat membuat proses update ini berjalan secara otomatis.
## References
