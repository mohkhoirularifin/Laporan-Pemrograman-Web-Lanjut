**TUGAS PERORANGAN/INDIVIDU**


**LAPORAN JOBSHEET 3**

**Angular Fundamental**


**Disusun Sebagai:**

MATA KULIAH: PEMROGRAMAN WEB LANJUT


**Oleh:**

**Moh. Khoirul Arifin/1741720051**

**TI-2B**



![](image/Logo/Polinema.png)



**PROGRAM STUDI D-IV TEKNIK INFORMATIKA**

**JURUSAN TEKNOLOGI INFORMASI**

**POLITEKNIK NEGERI MALANG**

**2019**



### Praktikum – Bagian 1: Component Basic
- Soal 1
Buatlah sebuah componen dengan nama **courses** dengan cara `ng generate component name atau ng g c name`

![](image/Jobsheet2/1.png)


- Buka file **app.component.html**, lakukan modifikasi code nya menjadi seperti berikut :

```html
<app-courses></app-courses>

<router-outlet></router-outlet>
```

- Kemudian open terminal dan jalan kan perintah ng serve, lalu perhatikan pada browser

- Soal 2
hasilnya


![](image/Jobsheet2/2.png)


- Buka file app.modules.ts dan hapus coursecomponent pada declarations


- Soal 3
Hasil pada browser
![](image/Jobsheet2/3.png)


- Soal 4
Kemudian lakukan inspect pada halaman localhost : 4200 di browser, apa yang terlihat? Berikan penjelasan


### Praktikum - Bagian 2: Templates

- Buka file courses.component.ts tambahkan property baru dengan nama title

- Soal 5
Hasil

![](image/Jobsheet2/5.png)


-Tambahkan string pada binding datanya. Buka file courses.component.html. 

- Soal 6
Hasil

![](image/Jobsheet2/6.png)


- Buka file courses.component.ts dan buatlah sebuah method dengan nama getTitle

- Kemudian buka file courses.component.html, lakukan modifikasi 

- Soal 7
Hasil

![](image/Jobsheet2/7.png)


### Praktikum - Bagian 3: Types
- Buka file courses.component.ts dan buat property dengan nama course dengan data berupa array

- Buka file courses.component.html lalu tambahkan directive ngFor dan string interpolation

- Soal 8
Hasil

![](image/Jobsheet2/8.png)

- Buatlah service baru yang bernama **courses** dengan perintah : `ng generate service courses` atau `ng g s courses`

- Soal 9
Hasil

![](image/Jobsheet2/9.png)

- Buka file courses.service.ts kemudian tambahkan method getCourse

- Buka file courses.component.ts, kemudikan lakukan modifikasi codenya

- Soal 10
Hasil

![](image/Jobsheet2/10.png)

- Tambahkan constructor

- Soal 11
Hasil

![](image/Jobsheet2/11.png)
