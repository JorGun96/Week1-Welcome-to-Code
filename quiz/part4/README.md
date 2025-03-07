# Sepaham apakah kalian tentang fungsi? | Part 4

## Soal 1
```js
// Tugas 1
// Buatlah sebuah fungsi bernama shoutOut(), yang mengembalikan nilai berupa "Halo Function!", 
// yang kemudian akan ditampilkan di console.

//bikin fungsinya disini

console.log(shoutOut());


// ------------------------------------
//Jawaban:

function shortOut(){

    console.log('Halo Function!');

    return;
}

console.log(shortOut());
// ------------------------------------
```

## Soal 2
```js
// Buatlah sebuah fungsi bernama calculateMultiply(), yang mengembalikan nilai berupa hasil kali dari 
// dua parameter yang dikirim.

//bikin fungsinya disini

let num1 = 1
let num2 = 2

let hasilPerkalian = calculateMultiply(num1,num2);
console.log(hasilPerkalian);

// ------------------------------------
//Jawaban

let num1 = 1;
let num2 = 2;

function calculateMultiply(a, b){
    return a * b;
}

let hasilPerkalian = calculateMultiply(num1, num2);
console.log(hasilPerkalian);

// -----------------------------------
```
## Soal 3
```js
// Buatlah sebuah fungsi bernama processSentence(), yang akan memproses seluruh parameter yang diinput menjadi 
// satu kalimat berikut: 
// "Nama saya [Name], umur saya [Age] tahun, alamat saya di [Address], dan saya punya hobby yaitu [hobby]!"

//bikin fungsinya disini

let name = "Agus";
let age = 30;
let address = "Jln. Malioboro, Yogjakarta";
let hobby = "gaming";

let fullSentence = processSentence(name,age,address,hobby);
console.log(fullSentence); // Menampilkan "Nama saya Agus, umur saya 30 tahun, alamat saya di Jln. Malioboro, Yogjakarta, dan saya punya hobby yaitu gaming!"
```
//Jawaban

function processSentence(name, age, address, hobby){
    return `Halo, name saya ${name}, saya berusia ${age} tinggal di ${address}, dan hobby saya adalah ${hobby}`;
}

name = "Agus Pedas";
age = 30;
address = "Jln. Malioboro, Yogjakarta";
hobby = "gaming";

let fullSentence = processSentence(name, age, address, hobby);

console.log(fullSentence);

---
Materi Function: [Link](../../study-materials/part6.md)
