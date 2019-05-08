**TUGAS PERORANGAN/INDIVIDU**

**LAPORAN BAB 11**

**AUTHENTICATION AND AUTHORIZATION**

**Disusun Sebagai:**

MATA KULIAH: PEMROGRAMAN WEB LANJUT

**Oleh:**

**Moh. Khoirul Arifin/1741720051**

**TI-2B**

![](media/29ead6ace402fb3f4cef7f2678b2ecf2.png)

**PROGRAM STUDI D-IV TEKNIK INFORMATIKA**

**JURUSAN TEKNOLOGI INFORMASI**

**POLITEKNIK NEGERI MALANG**

**2019**

**Praktikum – Bagian 1: Implementation Login**

1.  Buka folder auth-demo-starter kemudian open terminal dan lakukan ng serve.
    Catat hasil nya (soal 1)

    ![](media/7ee2b6ad6c0545b07d66592f833a8d65.png)

2.  Apabila terjadi error seperti dibawah ini :

    ![../../../../../Desktop/Screen%20Shot%202019-04-22%20at%2017.01.37.png](media/bcb631f3ac43be4696a622c81d69ed2f.png)

    Maka lakukan perintah untuk menginstall angular2-jwt, dengan perintah :

    **npm install angular2-jwt –save** kemudian lakukan **ng serve –open**

    catat hasilnya (soal 2)

    ![](media/9527df2e37dc7645314ff2325565968e.png)

3.  Ketika kita klik menu **Login** untuk masuk ke aplikasi, hasilnya akan
    kembali ke menu semula dengan kondisi [NAME] tidak ada perubahan. Sehingga
    akan ditambahkan autentikasi pada menu tersebut.

    ![](media/15943fb5b01adec01ac15cece8f471bc.png)

4.  Buka file auth.service.ts lalu tambahkan perintah seperti berikut ini :

    ![](media/ad5d14f5d5dbac0f9eccd167e25006fd.png)

5.  Jika sudah ditambahkan, jalankan perintah ng serve, dan klik bagian login
    lalu masukkan email address : <mosh@domai.com> dan password 1234 kemudian
    klik sign in. perhatikan apa yang terjadi? Catat hasilnya (soal 3)

    ![](media/748e5153194857fd92d87f86775d03f0.png)

6.  Kemudian lakukan login dengan email yang formatnya tidak valid contoh email
    kita isi 1234 dengan password 1234 maka ketika kita login dan kita inspect
    response apa yang muncul ? Catat hasilnya (soal 4)

    ![](media/4736a75940a88c74ed24f95226735fc2.png)

7.  Buka file auth.service.ts kemudian lakukan perubahan seperti berikut :

    ![](media/86dd2b724f2e8099606f9bc7732b4f77.png)

8.  Kemudian jalankan dan lakukan login dengan username dan password yang sesuai
    pada no 5, kemudian lakukan inspect pilih menu application liat di local
    storage, apa yang terlihat ? catat hasilnya (soal 5)

    ![](media/bac7635094e562a8c8fae01a2b7cb916.png)

**Praktikum – Bagian 2: Implemetasi Logout**

1.  Open file [home.component.html](http://home.component.html), tambahkan

    ![../../../../../Desktop/Screen%20Shot%202019-04-27%20at%2011.48.06.png](media/276e565f26dce8fea96fdd02a1a56a3a.png)

    ![](media/703118b1f744f9e008f0ef0af604e4dc.png)

2.  Open file auth.service.ts lalu tambahkan pada bagian logout :

    ![../../../../../Desktop/Screen%20Shot%202019-04-27%20at%2011.49.39.png](media/9639f9081aaaf3352443400ed1de058a.png)

    ![](media/2ae281a1116403931a59f6a7c3d560e8.png)

3.  Jalankan aplikasi, lalukan login dengan username dan password seperti
    sebelumnya dan lakukan inspect, cek pada local storage harusnya token nya
    sudah ada di local storage. Kemudian lakukan logout. Apa yang terjadi pada
    local storage ?

    Catat hasil (soal 6)

    ![](media/6863c403636e93f969e8c208b98052dc.png)

**Praktikum - Bagian 3 : Getting the Current User**

1.  Buka <https://jwt.io>, kita akan membuat token yang nantinya akan kita
    tempelkan di fake-backed.ts

    **IxNzQxNzIwMDUxIiwibmFtZSI6Ik1vaCBLaG9pcnVsIEFyaWZpbiIsImFkbWluIjp0cnVlfQ.2KVAU31v1mdqqrbztmL1HbZRy2npO9sHbUMlRJmAlnQ**

2.  Open auth.service.ts, lakukan modifikasi pada part isLoggeedIn() sehingga
    menjadi seperti berikut :

    ![](media/229d2262ea03595a8a4c976baf3abc55.png)

3.  Kemudian tambahkan code berikut tepat dibawah langkah no 2 :

    ![](media/d0759f9de60f30a0ce8d696ded2dc876.png)

4.  Open fake-backend.ts, ganti token yang lama menjadi token pada no 1

    ![](media/05132a671bc7b8e13d1428d2c0e1731a.png)

5.  Open file home.component.html , modifikasi seperti berikut :

    ![](media/3731e3aedd47ba4ad728eb3ff8ec246e.png)

6.  Jalankan aplikasi. Cek apa yang terjadi dan beri penjelasan (soal 7)

    ![](media/74b9c0c682847210329891c37ac224f5.png)

    ![](media/c2e712370c466c08055c90c6e59a1fc9.png)
