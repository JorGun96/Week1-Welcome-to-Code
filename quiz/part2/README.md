# Quiz Pemrograman Sebelum Masuk Looping | Part 2
## Soal 1
```js
//1. Let's Form a Sentence

// Problem
// Pada tugas ini kamu diminta untuk melakukan penambahan string menggunakan simbol +.
//  Disediakan variable word. Tambahkan nilai word satu per satu dengan nilai variable lain
//  untuk membentuk sebuah kalimat. Jangan lupa menambahkan spasi di setiap kata, dan
//   tampilkan di console hasil penggabungannya! Kamu tidak perlu membuat variable baru!

let word = 'JavaScript';
let second = 'is';
let third = 'awesome';
let fourth = 'and';
let fifth = 'I';
let sixth = 'love';
let seventh = 'it!';

//code herelet word = 'JavaScript';
let word = 'JavaScript';
let second = 'is';
let third = 'awesome';
let fourth = 'and';
let fifth = 'I';
let sixth = 'love';
let seventh = 'it!';

console.log(word+ " " +second+ " " +third+ " " +fourth+ " " +fifth+ " " +sixth+ " " +seventh)



```
## Soal 2. Index Accessing - 1 by 1
```js
// Problem
// Pada tugas ini kamu diminta untuk "memecah" sebuah kalimat dan menampilkan setiap kata didalamnya.
//  Untuk soal nomor ini, gunakan akses satu per satu karakter dari string untuk mengambil setiap huruf dalam kata.
//   Terasa manual? Tidak apa-apa, kita coba ini dulu untuk saat ini.

// Hints
// Saat kamu mendapatkan tiap huruf, untuk membentuk setiap kata kamu tinggal menggunakan simbol + untuk membentuk kata
//  tersebut!

let word = 'wow JavaScript is so cool';
let exampleFirstWord = word[0] + word[1] + word[2];

console.log('First Word: ' + exampleFirstWord);
//lanjutkan dengan struktur log diatas

let word = 'wow JavaScript is so cool';
let exampleFirstWord = word[0] + word[1] + word[2];
let secondWord = word[4] + word[5] + word[6] + word[7] + word[8] + word[9] + word[10] + word[11] + word[12] + word[13];
let thirdWord = word[15] + word[16];
let forthWord = word[18] + word[19];
let fifthWord = word[21] + word[22] + word[23] + word[24];

console.log('First Word: ' + exampleFirstWord);
console.log('Second Word: ' + secondWord);
console.log('Third word: ' + thirdWord);
console.log('forth word: ' + forthWord);
console.log('fifth word: ' + fifthWord);

```
## Soal 3. Breaking Sentence (Again) using Substring
```js
// Problem
// Mirip seperti soal nomor 2, namun kali ini gunakan substring untuk mengambil potongan dari tiap kata!

let word3 = 'wow JavaScript is so cool';
let exampleFirstWord3 = word3.substring(0, 3);

console.log('First Word: ' + exampleFirstWord3);
//answer :
let word = "wow Javascript is so cool"

let stringFirstWord = word.substring(0, 3);
let stringSecondWord = word.substring(4, 14);
let stringThirdWord = word.substring(15, 17);
let stringForthWord = word.substring(18, 20);
let stringFifthWord = word.substring(21, 25);

console.log(stringFirstWord);
console.log(stringSecondWord);
console.log(stringThirdWord);
console.log(stringForthWord);
console.log(stringFifthWord);

```

## Soal 4. Breaking Sentence (yet Again) and Count Each Length
```js
// Problem
// Mirip seperti soal nomor 3, tapi tampilkan juga panjang kata masing-masingnya!


let word4 = 'wow JavaScript is so cool';
let exampleFirstWord4 = word4.substring(0, 3);

let firstWordLength = exampleFirstWord4.length;

console.log('First Word: ' + exampleFirstWord + ', with length: ' + firstWordLength);
```

tulis code sesuai dengan keterangan soalnya dan pola example yang ada

let word = "wow Javascript is so cool"

let stringFirstWord = word.substring(0, 3);
let firstWordLength = stringFirstWord.length;
let stringSecondWord = word.substring(4, 14);
let secondWordLength = stringSecondWord.length;
let stringThirdWord = word.substring(15, 17);
let thirdWordLength = stringThirdWord.length;
let stringForthWord = word.substring(18, 20);
let forthWordLength = stringForthWord.length;
let stringFifthWord = word.substring(21, 25);
let fifthWordLength = stringFifthWord.length;


console.log('First Word: ' + stringFirstWord + 'with Length: ' + firstWordLength);
console.log('Second Word: ' + stringSecondWord + 'with Length: ' + secondWordLength);
console.log('Third word: ' + stringThirdWord + 'with Length: ' + thirdWordLength);
console.log('forth word: ' + stringForthWord + 'with Length: ' + forthWordLength);
console.log('fifth word: ' + stringFifthWord + 'with Length: ' + fifthWordLength);



Selamat Mengerjakan 👨🏻‍🌾
