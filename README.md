# Proyek: Sentiment Analysis Review Aplikasi 

## Intruksi proyek

Dalam proyek ini, saya diberikan kebebasan untuk memilih topik atau pembahasan yang ingin dianalisis sentimennya, serta platform yang ingin digunakan sebagai sumber data untuk analisis, asalkan sesuai dengan etika dan norma, serta tidak boleh mengandung unsur kontroversial atau isu-isu sensitif yang dapat menimbulkan masalah. Selain itu, harus mematuhi kebijakan dan pedoman dari platform sumber data dan menghindari tindakan yang dapat dianggap sebagai pencurian data.

### Dataset

Adapun dataset yang digunakan adalah dataset review sebuah aplikasi yang bersumber dari Google Playstore. Dataset ini diambil menggunakan teknik web scraping. Dataset yang berhasil discraping berjumlah sekitar 10000. Setelah melalui tahapan pre-processing, data yang digunakan hanya sekitar 6000-an.


### Cakupan Proyek

Dalam proyek ini dilakukan web scraping hingga pengklasifikasian data menggunakan python. Adapun algoritma yang digunakan untuk klasifikasi adalah SVM dan Logistic regression.


### Persiapan
Berikut tahapan yang dilakukan jika anda ingin menjalankan proyek tersebut

Setup environment:

Buka terminal atau PowerShell. Kemudian buat sebuah folder baru bernama proyek_sentimen_analysis dengan menjalankan perintah berikut.
```
mkdir proyek_sentimen_analysis

```
Kemudian pindah ke folder terbaru tersebut menggunakan perintah berikut.
```
cd proyek_sentimen_analysis

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
pip install -r requirements.txt

```
Buka jupyter-notebook dengan menjalankan perintah berikut.
```
jupyter-notebook .

```


## Kesimpulan & Saran

Algoritma SVM dan logistic regression sama-sama mendapatkan **akurasi sebesar 87%**. 


