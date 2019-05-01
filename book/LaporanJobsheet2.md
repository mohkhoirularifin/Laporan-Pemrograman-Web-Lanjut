** TUGAS PERORANGAN/INDIVIDU **


** LAPORAN JOBSHEET 2 **

** Typescript **


** Disusun Sebagai: **

MATA KULIAH: PEMROGRAMAN WEB LANJUT


** Oleh: **

** Moh. Khoirul Arifin/1741720051 **

** TI-2B **



![](image/Logo/Polinema.png)



** PROGRAM STUDI D-IV TEKNIK INFORMATIKA **

** JURUSAN TEKNOLOGI INFORMASI **

** POLITEKNIK NEGERI MALANG **

** 2019 **



### Praktikum – Bagian 1: Instalasi Typescript

- Soal 1
Cara mengistal **typescript** dengan perintah berikut `npm install -g typescript`
![](image/Jobsheet1/1.png)


- Soal 2
Cek version dari typescript yang terinstall `tsc --version`
![](image/Jobsheet1/2.png)

- Membuat folder **ts-hello** menggunakan `mkdir ts-hello`
- Tulisakan file **main.ts** dengan code berikut:

```typescript
function log(message) {
    console.log(message);
}

let message = "Hello World";

log(message);
```

- Kemudian ketik perintah `tsc main.ts` untuk melakukan transpile file **typescript** kedalam **javascript**

- Soal 3
Cek apakah sudah terbuat file **main.js**, lakukan perintah `ls`
![](image/Jobsheet1/3a.png)
![](image/Jobsheet1/3b.png)



- Soal 4
Buka file javascript, perhatikan apakah sama isi dari file **main.ts** dan `main.js`
![](image/Jobsheet1/4a.png)
![](image/Jobsheet1/4b.png)


- Soal 5
Lakukan execute pada file **main.js** dengan perintah `node main.js`
![](image/Jobsheet1/5.png)


### Praktikum - Bagian 2: Declaring Variables
- Buka file **main.ts**, kemudian tulis code berikut:
```typescript
function doSomething(){
    for (let i = 0; i < 5; i++){
        console.log(i);
    }
    console.log('Finally: ' + i);
}
doSomething();
```


- Soal 6
Remove file **main.js** hasil praktikum bagian 1 dengan perintah `rm main.js`
![](image/Jobsheet1/6.png)


- Soal 7
Lakukan transpile file **main.ts** dengan perintah yang ada pada praktikum bagian 1 langkah No 10

![](image/Jobsheet1/7.png)

- Soal 8
Execute file javascript dengan perintah `node main.js`
![](image/Jobsheet1/8.png)

### Praktikum - Bagian 3: Types
- Buka file **main.ts**, kemudian tuliskan listing program berikut:
```typescript
let count =5;
count = 'a';
```

- Akan terdapat masalah pada file **main.ts**
![](image/Jobsheet1/9.png)

- Soal 9
Lakukan proses transpile file **main.ts** dengan perintah `tsc main.ts` 
![](image/Jobsheet1/9b.png)

- Hasil transpile file **main.ts**, menghasilkan file **main.js** seperti beriku:
```typescript
var count = 5;
count = 'a'; 
```

### Praktikum – Bagian 4: Type Assertion

- Buka file **main.ts**, kemudian tuliskan code berikut:
```typescript
let pesan;
pesan='abc';
let percobaan=(<string>pesan).endsWith('c');
let alternative=(pesan as string).endsWith('c');
```

- Soal 10
Remove file **main.js** sebelumnya, lalu Lakukan proses transpile file **main.ts** dengan perintah `tsc main.ts`. Hasil file **main.js**
```typescript
var pesan;
pesan = 'abc';
var percobaan = pesan.endsWith('c');
var alternative = pesan.endsWith('c');
```

![](image/Jobsheet1/10.png)

### Praktikum – Bagian 5: Arrow Function

- Buka file **main.ts**, kemudian tuliskan code berikut:

```typescript
let log = function pesan(){
    console.log();
}

//kode diatas bisa disingkat menggunakan fungsi arrow
let doLog=(pesan)=>{
    console.log(pesan);
}

//atau seperti berikut
let doLog1=(pesan)=>console.log(pesan);
```

- Soal 11
Remove file **main.js** sebelumnya, lalu Lakukan proses transpile file **main.ts** dengan perintah `tsc main.ts`. Hasil file **main.js**
```typescript
var log = function pesan() {
    console.log();
};
//kode diatas bisa disingkat menggunakan fungsi arrow
var doLog = function (pesan) {
    console.log(pesan);
};
//atau seperti berikut
var doLog1 = function (pesan) { return console.log(pesan); };
```

![](image/Jobsheet1/11.png)

- Soal 12
Remove file **main.js** sebelumnya, lalu Lakukan proses transpile file **main.ts** dengan perintah `tsc main.ts`. Hasil file **main.js**
```typescript
var drawPoint = function (point) {
    //...
};
drawPoint({
    x: 1,
    y: 3
});
```

![](image/Jobsheet1/12a.png)
![](image/Jobsheet1/12b.png)

### Praktikum – Bagian 7: Classes

- Buka file **main.ts**, kemudian tuliskan code berikut:
```typescript
class Pointku{
    a:number;
    b:number;

    draw(){
        //...
    }

    getDistance(another:Pointku){
        //...
    }
}
```

![](image/Jobsheet1/13a.png)
![](image/Jobsheet1/13b.png)

### Praktikum – Bagian 8: Objects

- Buka file **main.ts**, kemudian tuliskan code berikut:
```typescript
class Pointku{
    a:number;
    b:number;

    draw(){
        console.log('X' + this.a + ',Y' + this.b);
    }

    getDistance(another:Pointku){
        //...
    }
}
```

![](image/Jobsheet1/14a.png)
![](image/Jobsheet1/14b.png)
![](image/Jobsheet1/14c.png)