## 1.1 Latar Belakang

Perkembangan industri permainan video telah menghasilkan berbagai judul yang menawarkan pengalaman yang semakin mendalam dan kompleks bagi para pemain. Salah satu alur cerita yang sering digunakan dalam game adalah tentang seorang tokoh utama yang berjuang untuk mencapai cita-citanya. Namun, perjalanan menuju cita-cita tersebut tidak selalu mulus dan mudah. Dalam banyak permainan, pemain akan dihadapkan pada tantangan yang menguji keterampilan, strategi, dan keberanian mereka. Alur cerita semacam ini seringkali disajikan dengan elemen fantastis, seperti adanya monster-monster yang menjadi rintangan utama. Para pemain harus berusaha untuk mengalahkan monster-monster tersebut sambil mengembangkan karakter mereka sepanjang perjalanan. Game-game semacam ini tidak hanya menghibur, tetapi juga memberikan pelajaran tentang ketekunan, tekad, dan kemampuan mengatasi rintangan dalam mencapai tujuan hidup.

## 1.2. Deksripsi Teknologi Informasi

player adalah seseorang yang memiliki hambatan dalam mencapai cita-citanya. player akan diberikan nyawa 3 pada setiap awal permainan. player harus mencari peti harta karun tetapi sebelum menemukan peti, sebelumnya player harus menemukan terlebih dahulu kunci untuk membuka gerbang (dalam game di visual kan sebagai pintu) lalu ditengah-tengah perjalanannya player harus dihadapkan dengan monster yang mematikan, player harus menjauhi monster itu karena jika player terkena/bersentuhan dengan monster maka nyawa akan berkurang 1 dan jika nyawa habis maka game akan dihentikan (game over). player akan dapat menambah nyawa kembali jika player menemukan nyawa ( visual nyawa dalam game yaitu love ). setelah player menemukan beberapa kunci untuk membuka gerbang agar bisa melewati jalan menuju harta karun, maka player akan bisa membuka kotak peti harta karun yang artinya permainan selesai dan dianggap player telah dapat mencapai cita-citanya setelah banyak melewati tantangan dan rintangan dalam perjalannya.

## 1.3. Branding

### Merk : Pursuing a dream

### Tagline : relax your mind by playing games

### Target user :
- Usia 17+
- Seorang yang senang sekali bermain game
- Seorang yang senang bermain game walau sekedar menghilangkan penat
- Seorang yang senang akan tampilan game yang berbeda
- Seorang yang senang tantangan

### Inspirasi Desain
![inspirasi desain](https://github.com/fatmaar/job-interview-pdp.md/assets/144698418/b7be2cb3-a24e-48a8-b1df-ac90b59d162a)
![inspirasi desain 2](https://github.com/fatmaar/job-interview-pdp.md/assets/144698418/7de0bda6-ffee-4887-9fe0-842db74b9ff4)


## 2. User Story

sebagai | saya ingin bisa | sehingga | prioritas
---|---|---|---
player | bergerak maju,mundur,samping kanan & kiri | dapat mengeksplor area sekitar | ⭐⭐⭐⭐⭐
player | mengambil kunci | dapat membuka pintu | ⭐⭐⭐⭐⭐
player | mengambil icon love nyawa | dapat menambah nyawa | ⭐⭐⭐
player | melawan monster | bisa melanjutkan perjalanan dengan aman | ⭐⭐⭐
player | menggunakan senjata | bisa melawan dan mematikan monster | ⭐⭐⭐
player | membeli senjata | bisa mengganti senjata | ⭐⭐⭐
player | mengganti backsound music | bisa menikmati music yang berbeda-beda | ⭐⭐⭐⭐
player | menonaktifkan backsound | bisa menyesuaikan keadaan | ⭐⭐⭐⭐
player | mengganti character player | bisa bermain dengan character yang berbeda-beda | ⭐⭐⭐
player | membeli character player | bisa tampil dengan beda | ⭐⭐⭐
player | mengganti suasana background game | tidak mudah bosan | ⭐⭐⭐
player | membeli kendaraan | bisa menggunakan kendaraan selama perjalanan game dimulai | ⭐⭐⭐


## 3. Struktur Data
![game drawio](https://github.com/fatmaar/job-interview-pdp.md/assets/144698418/ed37742f-3921-4147-b0d6-e4d21ce8f809)

## 4. Flowchart
![flowchartPDP drawio](https://github.com/fatmaar/job-interview-pdp.md/assets/144698418/6a9288e5-bd69-4018-aa1d-73ab9d15a078)


## 5. Desain User Experience dan User Interface
![Screenshot 2023-12-17 212538](https://github.com/fatmaar/job-interview-pdp.md/assets/144698418/cbad68c3-e8c3-49d8-96dd-ccb0f31f4f35)

![Screenshot 2023-12-17 212641](https://github.com/fatmaar/job-interview-pdp.md/assets/144698418/685d62c9-b19d-4630-ad91-24568b8fdfda)

![Screenshot 2023-12-17 212625](https://github.com/fatmaar/job-interview-pdp.md/assets/144698418/5f023c4b-48ac-4e9e-9340-34450a81663d)

![Screenshot 2023-12-17 212604](https://github.com/fatmaar/job-interview-pdp.md/assets/144698418/da19769f-21e8-4b50-9b1c-8a3b760e898c)


## 6. Demonstrasi Video
[https://www.youtube.com/watch?v=i55g3PnSae8]

## 7. Game menerapkan prinsip-prinsip dasar pemrograman seperti
Variable
Data type
Operator
Boolean
Conditions: If / else / switch
Looping: while / for
Array
Method
Class

## 8. Bagaimana konsep variable, data type dan operator pada bahasa pemrograman digunakan dalam pembuatan game ini ?
Konsep tersebut digunakan untuk membuat logika permainan, mengelola data permainan, dan berinteraksi dengan pengguna melalui input dan output.

## 9. Bagaimana konsep boolean dan conditions pada bahasa pemrograman digunakan dalam pembuatan game ini ?
konsep boolean digunakan untuk mengevaluasi kondisi atau pernyataan tertentu. 

- Metode isValidMove: Metode ini menggunakan kondisi boolean untuk memeriksa apakah langkah pemain valid. Jika pemain bergerak ke petak yang berisi simbol 'O' (batu), maka langkah dianggap tidak valid.

- Metode encounterMonster: Metode ini menggunakan kondisi boolean untuk menentukan apakah pemain bertemu monster atau tidak. Jika monsterCount lebih besar atau sama dengan 2, pemain kalah dan permainan berakhir.

- Metode openTreasureDoor: Metode ini menggunakan kondisi boolean untuk menentukan apakah pemain memiliki cukup kunci untuk membuka pintu peti harta karun. Jika keyCount lebih besar atau sama dengan 3, pemain dapat membuka pintu.

- Metode printMaze: Metode ini tidak secara langsung menggunakan boolean, tetapi menggunakan kondisi untuk menentukan apa yang akan dicetak. Misalnya, jika sel dalam maze adalah 'J', itu akan dicetak, dan jika sel adalah 'O', itu tidak akan dicetak.

## 10. Bagaimana konsep looping dan array pada bahasa pemrograman digunakan dalam pembuatan game ini ?
- Looping dalam Metode play: Metode play menggunakan loop while untuk terus memainkan permainan selama treasureCount kurang dari 1. Ini memungkinkan permainan berlanjut sampai pemain menemukan peti harta karun.

- Looping dalam Metode printMaze: Metode ini menggunakan dua loop for untuk mencetak seluruh struktur maze. Loop pertama untuk baris, dan loop kedua untuk kolom.

- Array pada Variabel mazeCells: Variabel mazeCells adalah array dua dimensi yang digunakan untuk menyimpan struktur maze. Ini mencerminkan struktur permainan dan memungkinkan representasi visual petak-petak dalam maze.

## 11. Bagaimana konsep method pada bahasa pemrograman digunakan dalam pembuatan game ini ?
- Penggunaan Method movePlayer: Metode ini digunakan untuk memindahkan pemain ke sel baru dalam maze. Ini mencakup logika untuk memeriksa validitas langkah dan menangani interaksi dengan elemen-elemen lain dalam maze.

- Penggunaan Method isValidMove: Metode ini memeriksa apakah langkah yang diminta oleh pemain valid. Ini menggunakan kondisi boolean dan merupakan bagian dari logika permainan untuk memastikan pemain tidak bergerak ke petak yang tidak valid.

## 12. Bagaimana konsep class pada bahasa pemrograman digunakan dalam pembuatan game ini ?
- Penggunaan Class Maze: Kelas ini digunakan untuk merepresentasikan struktur maze. Ini memiliki atribut cells yang merupakan array dua dimensi dari karakter.

- Penggunaan Class Player: Kelas ini merepresentasikan pemain dalam permainan. Ini memiliki atribut row dan col untuk menyimpan posisi pemain.

- Penggunaan Class Game: Kelas ini mengatur jalannya permainan dan interaksi antara pemain dan maze. Ini mengandung metode-metode yang mengimplementasikan logika permainan dan menggunakan objek dari kelas Maze dan Player.
