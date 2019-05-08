**TUGAS PERORANGAN/INDIVIDU**

**LAPORAN BAB 10**

**ROUTING DAN NAVIGASI**

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

**Praktikum – Bagian 1: Configure the routes**

1.  Buat project baru yang berisi komponen posts (praktikum http service),
    form-member (soal uts), navbar, not-found, home

    ![](media/2a8a636e2ca303cf9e402c4c16c81051.png)

2.  Jika node_modules belum tersida, install menggunakan **npm install**

3.  Buka file app.module.ts. Pastikan komponen pada langkah 1 sudah terdaftar
    seperti gambar dibawah ini

    ![](media/6f1e648cf299fe5e6d9abee7fe03c531.png)

4.  Tambahkan module router pada halaman app.module.ts seperti gambar dibawah
    ini:

    ![](media/8a50e52860a8d491c8cb18c6188cd499.png)

5.  Buka halaman navbar.component.html dan tambahkan kode dibawah ini:

    ![](media/d727dd518eb018ee2d49a1315e779eae.png)

6.  Buka halaman app.component.html. tambahkan kode dibawah ini:

    ![](media/80b66193a927509a9e1d18bc44023621.png)

7.  Jalankan dan catat hasilnya (soal no. 1)

    ![](media/bd101ec633af0373be83196d3b476e94.png)

    ![](media/280b7c1d3a57d3158ee64acfd2bfddf0.png)

**Praktikum - Bagian 2 : Router Outlet**

1.  Buka halaman app.component.html dan rubah menjadi seperti dibawah ini:

    ![](media/0cefa867074366888c73170ace9d0a7c.png)

2.  Jalankan dan inspect elemen seperti pada gambar dibawah ini

    ![](media/94580a42fd0a88c9ba8f95c43bd5ad11.png)

    ![](media/a5469a28b3295c3546f6b083a87434c0.png)

    Apa yang bisa anda simpulkan? (Soal No 2)

3.  Jalankan link dibawah ini localhost:4200/form seperti gambar dibawah ini:

    ![](media/1f28f02790867dad8f90586043af8898.png)

    ![](media/285779b4f00b1bd1d3cae386a0e74c7e.png)

    catat hasilnya (Soaln No. 3)

4.  Jalankan link dibawah ini localhost:4200/post seperti gambar dibawah ini:

    ![](media/8d4792442bcd00dacc08414d744bf813.png)

    ![](media/af1e74d21f93cb45c2ec6c45bc6905f4.png)

    catat hasilnya (Soaln No. 4)

5.  Jalankan link dibawah ini localhost:4200/coba seperti gambar dibawah ini:

    ![](media/19ebb3d0e45bde04267853b00536294e.png)

    ![](media/05f56c9c1b3b4af001aa887d2f313d11.png)

    catat hasilnya (Soaln No. 5)

6.  SImpulkan langkah 3, 4 dan 5 (Soal No. 6)

**Praktikum - Bagian 3 : Add Link**

1.  Buka halaman navbar.component.html. tambahkan link pada href tiap menu
    seperti gambar dibawah ini:

    ![](media/f295dd6e8b9bde2538c33b9b9e22ac7f.png)

2.  Jalankan, catat dan berikan penjelasan (Soal No. 7)

    ![](media/5a6ea629481ff32dcdea5511fddbafb5.png)

    ![](media/2a47c53be7e4f2ecd6b7d3d71e32eb14.png)

    ![](media/e5e0847a57bc1e0453269d413375d258.png)

3.  Modifikasi href menjadi routerLink pada halaman navbar.component.html
    seperti gambar dibawah ini:

    ![](media/05ae90103740ca298cd144c194ce42e4.png)

4.  Jalankan, inspect element, coba link dan cek pada tab network. Catat dan
    beri penjelasan (Soal No. 8)

    ![](media/7e80fab735d47b943076dd282f8b081a.png)

    ![](media/abc20c0d246ef5964d57ed50e72f1f82.png)

    ![](media/411bed25752a22e2cf92015ec1dafa17.png)

5.  Modifikasi class li pada halaman navbar.component.html menjadi seperti pada
    gambar dibawah ini:

    ![](media/1635d9b4ec76042a921bd1f098d48779.png)

6.  Jalankan, catat dan beri penjelasan (Soal No. 9)

    ![](media/8029dc85f0fdc46de4f8c03199174221.png)

    ![](media/29af93cd59ec0536a401d0a7803d5bfd.png)

    ![](media/0b4e4981e5dd134a2f3b45c0c3e01fb8.png)

**Praktikum - Bagian 4 : Accesing Route Parameter**

1.  Buat komponen baru dengan nama profile dengan perintah **ng g c profile**

    ![](media/2a08e7d65df8181ce9b0c8d7b3f76ef7.png)

    ![](media/5b6ae73184ac7fe7f239ab734dea26eb.png)

2.  Buka app.module.ts dan tambahkan route untuk profile seperti gambar dibawah
    ini:

    ![](media/94bca279b354abef0301c79b5b5dea2d.png)

3.  Modifikasi halaman [home.component.html](http://home.component.html) menjadi
    seperti gambar dibawah ini:

    ![](media/72d767f2d811dacae9b6fbd5c1385792.png)

4.  Modifikasi file profile.component.ts menjadi seperti pada gambar dibawah
    ini:

    ![](media/9469927c6cc51bdad54e8de2e9a73cc8.png)

5.  Jalankan, klik tombol home kemudian kliklink joko bowo kemudia inspect
    element seperti dibawah ini:

    ![](media/bc60d9d3f5ce4d8fd150090f4f598579.png)

    ![](media/6710bba530589a4c3d33b93a23b031fe.png)

    Catat dan berikan penjelasan (Soal No. 10)

6.  Modifikasi file profile.component.ts menjadi seperti pada gambar dibawah
    ini:

    ![](media/5b7ea642527e05c89df622cd124c3308.png)

7.  Jalankan, klik tombol home kemudian klik link joko bowo kemudia inspect
    element. Catat dan berikan penjelasan (Soaln No. 11)

    ![](media/c07454a066cebf30b396da63cbd0586f.png)
