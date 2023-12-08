# Tugas-1-Pemrograman-Berbasis-Objek

1. Buatlah perulangan hingga 100 menggunakan Python dengan output sebagai berikut:

2. Buatlah program bebas, dengan menerapkan if else pada:
  a. For Loops
  b. While Loops

3. Buatlah sebuah variabel dengan tipe data array, kemudian tampilkan semua nilai dalam variabel tersebut menggunakan perulangan for

Pembahasan :

no 1:

![alt](https://github.com/mark19566/Tugas-1-Pemrograman-Berbasis-Objek/blob/main/Screenshot%202023-12-08%20230712.png?raw=ture)

  Program di atas adalah contoh penggunaan perulangan for dalam rentang 1 hingga 100. Berikut adalah penjelasan baris per baris:

for i in range(1, 101):: Memulai perulangan for yang akan berjalan dari 1 hingga 100. Variabel iterasi diberi nama i.

if i % 10 == 0:: Pernyataan kondisional (if) memeriksa apakah nilai i adalah kelipatan 10. Jika sisa pembagian i dengan 10 adalah 0, maka i adalah kelipatan 10.

print("Athaariq"): Jika kondisi pada langkah 2 terpenuhi (nilai i adalah kelipatan 10), maka cetak nama "Athaariq". Baris ini dicetak tiga kali berturut-turut karena ada tiga pernyataan cetak.

else:: Bagian ini dijalankan jika kondisi pada langkah 2 tidak terpenuhi, artinya nilai i bukan kelipatan 10.

print(i): Jika kondisi pada langkah 2 tidak terpenuhi, cetak nilai i. Ini akan mencetak nilai i untuk setiap iterasi di mana i bukan kelipatan 10.



no 2 :

![alt](https://github.com/mark19566/Tugas-1-Pemrograman-Berbasis-Objek/blob/main/Screenshot%202023-12-08%20230907.png?raw=true)

Pemrograman diatas merupakan penerapan for loops, untuk penjelasan lebih rincinya sebagai berikut

n = int(input("Masukkan angka: ")): Mengambil input dari pengguna untuk sebuah bilangan dan mengonversinya ke tipe data integer, kemudian menyimpannya dalam variabel n.

for i in range(n):: Memulai perulangan for dari 0 hingga n-1. Variabel iterasi diberi nama i.

if i % 5 == 0:: Pernyataan kondisional (if) memeriksa apakah nilai i habis dibagi 5. Jika sisa pembagian i dengan 5 adalah 0, maka i habis dibagi 5.

print(f"{i} habis dibagi 5."): Jika kondisi pada langkah 3 terpenuhi (nilai i habis dibagi 5), cetak pesan yang menyatakan bahwa nilai i habis dibagi 5.

else:: Bagian ini dijalankan jika kondisi pada langkah 3 tidak terpenuhi, artinya nilai i tidak habis dibagi 5.

print(f"{i} tidak habis dibagi 5."): Jika kondisi pada langkah 3 tidak terpenuhi, cetak pesan yang menyatakan bahwa nilai i tidak habis dibagi 5.
