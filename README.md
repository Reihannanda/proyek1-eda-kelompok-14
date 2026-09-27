# proyek1-eda-kelompok-14

### Analisis Eksplorasi Data Pola Permintaan Sewa Sepeda BoomBikes di Pasar Amerika Serikat (2018–2019)
* Ananda Reihan Nur Ikbar / 5027261057
* Raisya Nurosiana Salsabilla / 5027261130
* Khoirun Naafi Pratama Putra / 5027261118

Topik: **Smart City**

* **Sumber Data:** Bike Sharing Dataset yang diunggah oleh M Yasser H di platform [Kaggle](https://www.kaggle.com/datasets/yasserh/bike-sharing-dataset).
* **Link Dataset:** [Kaggle Bike Sharing Dataset](https://www.kaggle.com/datasets/yasserh/bike-sharing-dataset)
* **Lisensi Data:** Data ini berstatus *Public Domain* (CC0: Public Domain) https://creativecommons.org/publicdomain/zero/1.0/

Setelah kami cek isi tabel data sepeda BoomBikes lewat kodingan di atas, ini adalah hasil temuan kelompok kami :
* Apakah ada kotak yang kosong? (df.isna().sum()): Dari hasil analisis kelompok kami, kami tidak menemukan adanya kotak yang kosong, hal ini dibuktikan dengan adanya pengecekan jumlah data kosong yang menampilkan angka "0".
* Apakah ada tipe data yang salah? (df.info()): Kami tidak menemukan adanya tipe data yang salah, semuaya sesuai dengan tempatnya masing-masing. contoh untuk kolom tanggal dibaca sebagai teks biasa, kolom angka hitungan (seperti jumlah sepeda atau nomor urut) dibaca sebagai angka bulat, dan kolom pecahan desimal (seperti suhu udara) dibaca sebagai angka koma.
* Apakah ada angka yang aneh atau ngawur?: Kami tidak menemukan adanya angka yang aneh seperti angka minus atau negatif. Semua berada pada batasan rentang yang normal dan semestinya.
* Apakah ada data yang kembar atau duplikat? (df.duplicated().sum()): Dari data yang kami periksa, kami tidak menemukan adanya data kembar atau duplikat, semua tercatat di hari serta tanggal yang berbeda.

**Keputusan Akhir Kelompok Kami:** Karena kelompok kami tidak menemukan adanya kesalahan pada data diatas, maka kami memutuskan untuk membiarkan semua datanya tetap utuh seperti aslinya. Kelompok kami tidak melakukan revisi apapun dan kelompok kami langsung lanjut ke tahap berikutnya.

Cara menjalankan Notebook: 	Jalankan Kernel > Restart & Run All sebelum diunggah, supaya semua output dan grafik tampil saat dibuka di GitHub
