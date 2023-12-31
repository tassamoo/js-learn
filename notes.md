# This is repository to learn about JS

### Saturday November 18th 2023

## Pengenalan JS
JS History:
- dibuat di netscape oleh Brandan Eich
- Awalnya buat client-side
- Dengan adanya node.js kita bisa pake jadi backend
- Standarisasi oleh organisasi ECMA Internasional - ECMAScript

JS VS Java
- Bukan bahasa yang sama

Peralatan Development
- Text Editor : vscode, atom, sublime, webstorm, notepad++, emacs dll.
- Browser: Google Chrome, Firefox, Edge, Safari, Opera 

## Program Hello World
Intinya ada 2 cara buat munculin script js di html yaitu dengan:
1. di embed
2. di load dari file .js

caranya
1. pake tag script langsung ditulis kode JSnya <script></script>
2. di load pake tag script <script src="script/hello-world.js"></script>

[**hello-world.html**](./js-learn/hello-world.html) 

## Komentar di JS ini berlaku di dalam tag script <script></script>
1. Komentar satu baris pake "//"
//komentar satu baris

2. Komentar lebih satu baris
/*
isi komentarnya
*/


## Tipe Data Number
1. di JS tipe data hanya satu namanya number bisa bilangan bulat ataupun desimal
Contoh:
<script> 
document.writeln(100)
document.writeln(<br>)
document.writeln(100)
</script>
2. Notasi Angka di Tipe data number ada 3:
- Number Notation (heexadecimal, binary, octal)
        document.writeln(0b10011001) //binary starts with 0b 153
        document.writeln(0xFF) //hexadecimal starts with 0xFF 255
        document.writeln(0010) //Octal starts with 0o10 8

## Tipe Data Booleam
1. Tipe data yang direpresentasikan dengan true atau false


## Tipe Data String
1. string/text adalah tipe data yang isinya kumpulan kosong atau lebih karakter (bisa "" atau "abc")
2. Perlu menggunakan petik dua tau petik satu untuk mendeklarasikan tipe data string (misal 'contohteks' atau "contohteks string")
3. Bisa menambahkan karakter menggunakan operator plus (+)

## Escape Sequence
Escape sequence dalam JavaScript digunakan untuk menyisipkan karakter khusus dalam string, yang seharusnya memiliki makna khusus, seperti karakter kutip (') atau karakter baris baru. Escape sequence dimulai dengan karakter backslash (`\`) diikuti oleh karakter khusus.

Berikut beberapa escape sequence umum dalam JavaScript:

1. `\n`: Mewakili karakter baris baru.
   Contoh:
   ```javascript
   console.log("Baris pertama\nBaris kedua");
   // Output:
   // Baris pertama
   // Baris kedua
   ```

2. `\'` dan `\"`: Digunakan untuk menyisipkan tanda kutip tunggal atau ganda di dalam string.
   Contoh:
   ```javascript
   console.log('Ini adalah tanda kutip tunggal (\')');
   console.log("Ini adalah tanda kutip ganda (\")");
   ```

3. `\\`: Digunakan untuk menyisipkan karakter backslash.
   Contoh:
   ```javascript
   console.log("Ini adalah karakter backslash: \\");
   ```

4. `\t`: Mewakili karakter tab.
   Contoh:
   ```javascript
   console.log("Kolom 1\tKolom 2\tKolom 3");
   ```

5. `\uXXXX`: Representasi Unicode untuk karakter dengan kode Unicode `XXXX`.
   Contoh:
   ```javascript
   console.log("\u00A9"); // Output: ©
   ```

Jadi, escape sequence membantu Anda menulis string dengan karakter khusus tanpa membingungkan interpreter JavaScript.

## Variable
1. Variable adalah tempat untuk menyimpan data
2. reusable, bisa digunakan berulang-ulang
3. bisa pake var, const, atau let
4. JS dynamic, kita bisa ubah tipe data di variable yang sama

Contoh
var fullname; //tidak boleha da spasi

## Mengakses Variable
1. Bisa digunakan Kembali
2. Mempermudah ketika membutuhkan data yang sama berkali-kali
3. Untuk akses sebutkan nama variablenya aja




