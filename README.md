Labpy03

Latihan 1

Program Sederhana Menampilkan n Bilangan Acak Yang Lebih Kecil Dari 0.5
Algoritma Program Menampilkan n Bilangan Acak Yang Lebih Kecil Dari 0.5
Masukan Jumlah n Pengulangan
Proses pengulangan sesuai jumlah pengulangan yang diinputkan
Tampilkan pengulangan dengan nilai di bawah 0.5
Finish
Setelah kita membuat Algoritma tersebut Maka Langkah selanjutnya membuat Flowchart program Menampilkan Bilangan Acak Yang Lebih Kecil Dari 0.5.

Program Menampilkan n Bilangan Acak Yang Lebih Kecil Dari 0.5


print ('Menampilkan n Bilangan Acak yang Lebih Kecil Dari 0.5')
jumlah =int (input( " Masukan Jumlah n : "))
import random
for i in range (jumlah) :
    print (" Data ke -> ", 1+i, "=",(random.uniform(0.1,0.5)))
print ("  SELESAI  ")
Penjelasan Program
print ('Menampilkan n Bilangan Acak yang Lebih Kecil Dari 0.5') Untuk Menampilkan atau Mencetak kalimat Tampilkan n Bilangan Acak yang Lebih Kecil Dari 0.5
jumlah =int (input( " Masukan Jumlah n : ")) Untuk menentukan jumlah input yang di inginkan sesuai tipe data yaitu interger tipe data bilangan bulat
import random Untuk pengulangan secara acak
for i in range (jumlah) : Untuk Pengulangan dengan range jumlah
print (" Data ke -> ", 1+i, "=",(random.uniform(0.1,0.5))) Untuk menampilkan atau mencetak urutan data sesuai jumlah inputan dengan hasil di bawah 0.5

Hasil Program







Latihan 2
Program Sederhana Untuk Menampilkan bilangan Terbesar dari n buah data yang di Masukkan
Algoritma Program Sederhana Untuk Menampilkan bilangan Terbesar dari n buah data yang di Masukkan
Start
input bilangan n
Jika max < x maka akan lanjut pengulangan
Jika x==0 maka akan berhenti proses pengulangan
Dan mencetak hasil nilai maxium dari n yang di isikan
Finish
Setelah kita membuat Algoritma tersebut Maka Langkah selanjutnya membuat Flowchart program Sederhana Untuk Menampilkan bilangan Terbesar dari n buah data yang di Masukkan


Program Sederhana Untuk Menampilkan bilangan Terbesar dari n buah data yang di Masukkan

print (' Bilangan Terbesar Dari n Buah Data Yang Dimasukan ')
max = 0
while True:
    x=int(input("Masukan Bilangan : "))
    if max < x:
        max = x
    if x==0:
        break
print ("Bilangan Terbesar Adalah : ", max)
Penjelasan program
print (' Bilangan Terbesar Dari n Buah Data Yang Dimasukan ') Untuk menampilkan kalimat Menampilkan Bilangan Terbesar Dari n Buah Data Yang Diinputkan
max = 0 kode max disini untuk menentukan nilai max nya dalah 0
while True: Untuk perulangan hingga waktu yang tidak di tentukan atau selamanya
x=int(input("Masukan Bilangan : ")) x untuk menginput tipe data interger ( bilangan bulat )
if max < x: jika max kurang dari x maka max = x
if x==0: break jika x= 0 maka akan berhenti dengan syarat break yang terpenuhi
print ("Bilangan Terbesar Adalah : ", max) Menampilkan *Bilangan Terbesar Adalah : Nilai maxiumnya



Hasil Program


latihan3
Program Sederhana Menghitung Total Keuntungan Selama 8 Bulan
Algoritma Program Sederhana Menghitung Total Keuntungan Selama 8 Bulan
Start
Input modal misalkan n = 100.000.000 ( deklarasikan )
Input presentase untung A=0n, B=0n, C=0.01n, D=0.01n, E=0.05n, F=0.05n, G=0.05n, H=0.03n
For i in range (len (y)) pengulangan
Print (“keuntungan bulan ke “,i+1,”sebesar:” ,y[i])
Menghitung jumlah laba keseluruhan x= (A+B+C+D+E+F+G+H)
Print (“ Jumlah Keuntungan Selama 8 Bulan Adalah :”)
Finish


Program Program Sederhana Menghitung Total Keuntungan Selama 8 Bulan

print ( 'Total Keuntungan Selama 8 Bulan Berjalannya Usaha' )

#Modal Awal
n=100000000
print ("Awal Modal : ", n )

#presentase Keuntungan
A=0*n
B=0*n
C=0.01*n
D=0.01*n
E=0.05*n
F=0.05*n
G=0.05*n
H=0.03*n

y=[A,B,C,D,E,F,G,H]

for i in range (len(y)):
    print (" Keuntungan Bulan ke ",i+1 , "-> ", y[i])

x= (A+B+C+D+E+F+G+H)
print (" Jumlah Keuntungan Selama 8 Bulan Adalah :",x)
Penjelasan Program
print ( 'Total Keuntungan Selama 8 Bulan Berjalannya Usaha' ) Untuk Menampilkan kalimat Total Keuntungan Selama 8 Bulan Berjalannya Usaha
n=100000000 Dengan pemisalan atau dideklarasikan n adalah 100000000
print ("Awal Modal : ", n ) Menampilkan kalimat Modal Awal : dan data yang berisi di n yaitu 100000000
A=0n, B=0n, C=0.01n, D=0.01n, E=0.05n, F=0.05n, G=0.05n, H=0.03n Untuk Mendeklarasikan presentase laba tiap bulan dan di kali dengan x atau data inputan modal investasi yaitu 100000000
y=[A,B,C,D,E,F,G,H] untuk menentukan syarat y= yang berisi A,B,C,D,E,F,G,H
for i in range (len(y)): print (" Keuntungan Bulan ke ",i+1 , "-> ", y[i]) untuk perulangan data dengan isi data yaitu Y dengan menampilkan urutan laba perbulan sesuai range yang di tentukan dengan hasil ke untukan yang di inpput dari data Y
x= (A+B+C+D+E+F+G+H) print (" Jumlah Keuntungan Selama 8 Bulan Adalah :",x) x berisi data penjumlahan data angka yang ada didalam kode A,B,C,D,E,F,G,H yang akan di tampilakan atau dicetak di jumlah laba selama 8 bulan


Hasil Program









NAMA : R Iwan D
NIM : 311720879
KELAS : TI.18 B.1
