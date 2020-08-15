# Belajar-MIT-App-Inventor-2-dan-Firebase

## A. Belajar membuat Kalkulator penghitung luas Persegi Panjang 

1. Masuk kedalam situs https://appinventor.mit.edu/. Kemudian pilih Create Apps. 
![1](https://user-images.githubusercontent.com/49858542/90304641-171e6880-dee4-11ea-8afe-06d5e8a64b06.png)

2. Buatlah layout seperti pada gambar dibawah ini.

| Gambar                                                                                                      |  Properties |   Value        |
|-------------------------------------------------------------------------------------------------------------|-------------|----------------|
|  ![1](https://user-images.githubusercontent.com/49858542/90304864-41712580-dee6-11ea-96f1-d2f64b9e39cf.png) | Label 1<br />Label 2<br />Label 3<br />Label 4<br />Label 5<br />TextBoxt 1<br />TextBox 2<br/>Button | Kalkulator<br />Panjang<br />Lebar<br />Hasil<br />Nilai<br />Nilai Panjang<br />Nilai Lebar<br />Tekan     |

###### Catatan:<br />
Gunakan Layout Vertical Scroll untuk base, selanjutnya untuk setiap baris menggunakan Layout Horizontal.

3. Setelah pembuatan layout selesai selanjutnya kebagian block programming. Masukkan block Programming seperti pada gambar dibawah ini.

![image](https://user-images.githubusercontent.com/49858542/90305087-ee4ca200-dee8-11ea-885a-c7d618bb1912.png)

4. Untuk menjalankan program silahkan download terlebih dahulu aplikasi untuk menghubungkan App Inventor dengan Android, dengan link download https://play.google.com/store/apps/details?id=edu.mit.appinventor.aicompanion3<br />Setelah aplikasi berhasil didownload selanjutnya kembali ke App Inventor kemudian pilih menu Connect -> AI Companion. Lalu scan barcode yang ditampilan dan aplikasi yang baru dibuat akan ditampilkan secara otomatis pada aplikasi android.

5. Untuk mengexport aplikasi menjadi .apk dapat dilakukan dengan memilih menu Build -> Pilih salah satu apakah akan dieksport melalui QR Code atau disimpan di komputer.

## B. Menampilkan data Firebase ke Aplikasi dengan APP Inventor

1. Buat database Firebase dengan akun Google melalui link berikut https://firebase.google.com/

2. Setelah berhasil login selanjutnya buat database baru menggunakan Realtime database dengan mengikuti langkah seperti pada video pada link berikut https://youtu.be/PTmKysmX29c<br />
## Atau bisa klik gambar dibawah ini

[![Watch the video](https://cdn.shortpixel.ai/client/to_webp,q_glossy,ret_img,w_1314/https://www.initekno.com/wp-content/uploads/2019/04/firebase1.png)](https://youtu.be/PTmKysmX29c)

3. Buat Layout seperti pada gambar dibawah ini:

| Gambar                                                                                                      |  Properties |   Value        |
|-------------------------------------------------------------------------------------------------------------|-------------|----------------|
| ![image](https://user-images.githubusercontent.com/49858542/90311885-ff69d300-df29-11ea-971e-c805474d122a.png) | Label1<br />Label2<br /> | Data Firebase<br />Nilai|

4. Pada block program buat seperti pada gambar dibawah ini

![image](https://user-images.githubusercontent.com/49858542/90311966-bd8d5c80-df2a-11ea-90bf-990e78a7b8c6.png)

5. Masukkan Token dan link app pada FirebaseDB1 di App Inventor

   Lokasi link Firebase

![image](https://user-images.githubusercontent.com/49858542/90312012-368cb400-df2b-11ea-88f9-d1484a30ae83.png) 

   Lokasi Token Firebase<br />
   Masuk ke menu Settingan Project -> Akun Layanan -> Rahasia Database

![sdfg](https://user-images.githubusercontent.com/49858542/90312054-8cf9f280-df2b-11ea-96e4-4515ad7d35aa.png) 

6. Masukkan link dan token sesuai dengan properti pada App Inventor

![image](https://user-images.githubusercontent.com/49858542/90312139-37721580-df2c-11ea-9f11-55c8a2c8ae2e.png)

## Catatan :<br />
Kosongkan pada Properti " ProjectBucket "!

7. Jalankan Aplikasi 





