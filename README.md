# Proyek Akhir: Menyelesaikan Permasalahan Perusahaan Edutech

## Business Understanding

PT Jaya Jaya Maju merupakan salah satu perusahaan multinasional yang telah berdiri sejak tahun 2000 yang memiliki lebih dari 1000 karyawan yang tersebar di seluruh penjuru negeri. Akan teteapi, Jaya Jaya Maju masih cukup kesulitan dalam mengelola karyawan. Hal ini berimbas tingginya attrition rate (rasio jumlah karyawan yang keluar dengan total karyawan keseluruhan) hingga lebih dari 10%. Oleh karena itu, diperlukanlah analisis terkait faktor-faktor yang membuat hal itu terjadi.

### Permasalahan Bisnis

Tingginya attrition rate (rasio jumlah karyawan yang keluar dengan total karyawan keseluruhan) hingga lebih dari 10% pada perusahaan.


### Cakupan Proyek

Untuk menjawab permasalahan bisnis tersebut, kita akan membuat Business Dashboard untuk mengetahui faktor-faktor penyebab permasalahan tersebut. ***Proyek ini dilakukan dengan dua tools, yaitu python dan metabase***. Dalam python dilakukan data preparation/ data cleaning kemudian untuk visualisasi dilakukan di Metabase.

### Persiapan

Sumber data: Adapun sumber data menggunakan <a href="https://github.com/dicodingacademy/dicoding_dataset/tree/main/employee"> Employee Data</a> 

Setup environment:

Buka terminal atau PowerShell. Kemudian buat sebuah folder baru bernama proyek_attrition_rate dengan menjalankan perintah berikut.
```
mkdir proyek_attrition_rate

```
Kemudian pindah ke folder terbaru tersebut menggunakan perintah berikut.
```
cd proyek_attrition_rate

```
Kita buat sebuah virtual environment dengan menjalankan perintah berikut.
```
pipenv install

```
Aktifkan virtual environment dengan menjalankan perintah berikut.
```
pipenv shell

```
Instal semua library yang dibutuhkan menggunakan perintah berikut.
```
pip install numpy pandas scipy matplotlib seaborn jupyter sqlalchemy 

```
Buka jupyter-notebook dengan menjalankan perintah berikut.
```
jupyter-notebook .

```


## Business Dashboard

Dalam business dashboard yang telah dibuat, terdapat beberapa visualisasi yang membantu menganalisis faktor apa yang membuat tingginya attrition rate tersebut. Anatara lain:
- Terdapat 3 KPI yaitu jumlah karyawan aktif, jumlah karyawan resign dan persentase resign karyawan.
- Ditampilkan detail karyawan resign per departemen dan jenis pekerjaannya
- Sebaran gaji, umur, berapa tahun bekerja di PT jaya jaya maju dan pengalaman kerja dari karyawan yang resign
- Scatter plot dari gaji bulanan yang didapat vs lamanya bekerja di PT jaya jaya maju
- Kategori gaji bulanan yang didapatkan karyawan yang resign 
- Bar chart dari kepuasan karyawan yang resign terhadap relation, environtment, job, dan work-life balance 

Adapun dashboard dapat dilihat pada link <a href="http://localhost:3000/public/dashboard/c7c86f9f-91c2-4521-94e5-c104caf665b3">berikut </a>

## Conclusion

Berdasarkan dashboard yang telah dibuat dan analisis yang telah dilakukan, dapat disimpulkan bahwa:
- Attrition rate sekitar 12% 
- Banyak karyawan yang resign terbilang masih "baru" (kurang dari 5 tahun) bekerja di perusahaan Jaya Jaya maju 
- Mayoritas karyawan yang resign mendapatkan gaji dalam kategori middle low (Antara $2000 dan $4999 ) padahal 
- Mayoritas karyawan yang resign berasal dari departemen Reseach & development
- Karyawan resign paling banyak dari jenis pekerjaan yang labroratory technisian
- Karyawan yang resign banyak merasa kurang puas terhadap lingkungan kerjanya

### Rekomendasi Action Items (Optional)

Oleh karena itu, saya merekomendasikan perusahaan melakukan hal-hal sebagai berikut:

- Perusahaan harus mengevaluasi cara perekrutan karyawan baru. Bisa dengan cara menampilkan/memberitahukan gaji yang diperoleh selama bekerja 
- Mempertimbangkan ulang nominal gaji bulanan yang diberikan kepada karyawan baru, terlebih lagi pada karyawan yang baru namun memiliki pengalaman kerja. Karena berdasarkan data diketahui bahwa terdapat karyawan yang telah berpengalaman namun masih "baru" di PT jaya jaya maju.
- Membenahi pekerjaan di bidang laboratory technision. Karena dari data menunjukkan bahwa karyawan resign terbanyak dari Job role tersebut
