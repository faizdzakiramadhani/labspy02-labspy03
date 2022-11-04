#  labpy03

#  Nama = Faiz Dzaki Ramadani
# Nim  = 312210223
# Kelas  = TI.22.A2

#  Latihan 1

#  Program Sederhana Untuk N Bilangan Acak Yang Lebih Kecil Dari 0.5

##  A. Algoritma Program Untuk Kepentingan N Bilangan Acak Yang Lebih Kecil Dari 0.5
1. Masukan Jumlah N perulangan
2. Proses perulangan sesuai jumlah perulangan yang diputkan
3. Tampilkan perulangan dengan nilai di bawah 0.5
4. Selesai


#  B. Flowchart Program

![ flowchart latihan1 ](https://user-images.githubusercontent.com/46926758/53193448-8e52a380-3643-11e9-9f3e-82b74718a6aa.png)

#  C. Program Untuk Acara N Bilangan Acak Yang Lebih Kecil Dari 0.5

##  > Urutan Pembuatan Program

1. Program Ketikan *print ('Tampilkan n Bilangan Acak yang Lebih Kecil Dari 0.5')*
2. Ketikan Program *jumlah=int(input("Masukan Jumlah N : "))*
3. Program Ketikan *import random*
4. Program Ketikan *untuk i in range ( jumlah ) :*
5. Program Ketikan *print("Data ke", 1+i,"=>", (random.uniform(0.1,0.5)))* 

###  > Penjelasan Alur Program

1.  *print ('Tampilkan n Bilangan Acak yang Lebih Kecil Dari 0.5')* Untuk tampil atau Mencetak Tampilkan N Bilangan Acak yang Lebih Kecil Dari 0.5

2.  *jumlah=int(input("Masukan Jumlah N : "))* Untuk menentukan jumlah input yang diinginkan sesuai tipe data yaitu interger tipe data bilangan bulat

3.  *impor secara acak* *

4.  *untuk i dalam range ( jumlah )* : Untuk Pengulangan dengan range jumlah

5.  *print("Data ke", 1+i,"=>", (random.uniform(0.1,0.5)))* Untuk menampilkan atau urutan data sesuai jumlah inputan dengan hasil di bawah 0,5

##  D. Hasil

<img width="960" alt="Screenshot_22" src="https://user-images.githubusercontent.com/115913915/199911878-17b08841-123d-4000-910f-3215ce63b763.png">


#  Latihan 2

#  Program Sederhana Untuk Bilangan Terbesar Dari N Buah Data Yang Dinputkan

##  A. Algoritma Program Untuk Mendapat Bilangan Terbesar Dari N Buah Data Yang Dinputkan

1. mulai
2. masukan bilangan N
3. Jika max < a maka akan lanjut kerutan
4.Jika a==0 maka akan berhenti proses penahanan
5. Dan mencetak hasil nilai maxium dari N yang di isikan
6. Selesai

Setelah Anda Menegetahui Algoritma Dalam Sebuah Program Maka Langkah Berikutnya Membuat Flowchartnya. Berikut ini Flowchart Program

##  B. Flowchart Program

![ flowchart latihan2 ](https://user-images.githubusercontent.com/46926758/53195549-73366280-3648-11e9-9741-4b5eba27802d.png)

##  C. Program Untuk Menjadi Bilangan Terbesar Dari N Buah Data Yang Dinputkan


###  > Urutan Pembuatan Program

1. Program Ketikan *print ('Menampilkan Bilangan Terbesar Dari N Buah Data Yang Diinputkan')*
2. Program Ketikan *max= 0*
3. Program Ketikan *sementara benar :*
4. Program Ketikan *a=int(input("Masukan Bilangan :"))*
5. Program Ketikan *jika max < a*
6. Program Ketikan *max=a*
7. Program Ketikan *jika a==0:*
8. Program Ketikan *break*
9. Program Ketikan *print("Bilangan Tebesar Adalah :", max)*

###  > Penjelasan Alur Program

1.  *print ('Menampilkan Bilangan Terbesar Dari N Buah Data Yang Diinputkan')* Untuk menampilkan kalimat *Menampilkan Bilangan Terbesar Dari N Buah Data Yang Diinputkan*

2.  *max= 0* kode max disini untuk menentukan nilai max nya dalah 0

3.  * while true:* Untuk perulangan hingga waktu yang tidak ditentukan atau selamanya

4.  *a=int(input("Masukan Bilangan :"))* a untuk menginput tipe data interger ( bilangan bulat )

5.  *if max < a max=a* jika max kurang dari a maka max = a

6.  *if a==0: break* jika a= 0 maka akan berhenti dengan syarat break yang terpenuhi

7.  *print("Bilangan Tebesar Adalah :", max)* kagum *Bilangan Tebesar Adalah : Nilai maxiumnya

##  D. Hasil
<img width="960" alt="Screenshot_23" src="https://user-images.githubusercontent.com/115913915/199912158-3c6ad709-9570-4ace-867a-fcc1da2eb521.png">


#  Program 1

#  Program Sederhana Untuk Menghitung Jumlah Laba Hasil Investasi Seorang Pengusaha Selama 8 Bulan

##  A. Program Algoritma Untuk Menghitung Jumlah Laba Hasil Investasi Seorang Pengusaha Selama 8 Bulan

1. Mulai
2. Masukkan modal misalkan x = 20.000.000 ( deklarasikan )
3. Masukan presentase untung a=0x, b=0x, c=0.01x, d=0.01x, e=0.05x, f=0.05x, g=0.05x, h=0.03x
4. Untuk i dalam rentang (len (t))
5. Cetak (“laba bulan ke-“,i+1,”sebesar:” ,t[i])
6. Menghitung jumlah laba total u= (a+b+c+d+e+f+g+h)
7. Cetak (“total laba adalah:”)
8. selesai

##  B. Flowchart Program1

![ 53196983-d970b480-364b-11e9-846a-f738b6116a58 ](https://user-images.githubusercontent.com/115517181/199748986-d659e93e-1714-454c-8831-50bc95b1254d.png)

#  C. Program Untuk Menghitung Jumlah Laba Hasil Investasi Seorang Pengusaha Selama 8 Bulan



###  > Urutan Pembuatan Program

1. Ketikan Program *print ('Jumlah Laba Hasil Investasi Seorang Pengusaha Selama 8 Bulan')*
2. Program Ketikan *x=20000000*
3. Program Ketikan *print ("Modal Awal:",x)*
4. Program Ketikan *a=0x, b=0x, c=0.01x, d=0.01x, e=0.05x, f=0.05x, g=0.05x, h=0.03x*
5. Program Ketikan *t=[a,b,c,d,e,f,g,h]*
6. Program Ketikan *For i in range (len(t))*
7. Program Ketikan *Print (“laba bulan ke-“,i+1,”sebesar:” ,t[i])*
8. Program Ketikan *u= (a+b+c+d+e+f+g+h)*
9. Program Ketikan *Print (“total laba adalah:”)*

###  > Penjelasan Alur Program

1.  *print ('Jumlah Laba Hasil Investasi Seorang Pengusaha Selama 8 Bulan')* Untuk kalimat *Jumlah Laba Hasil Investasi Seorang Pengusaha Selama 8 Bulan*

2.  *x=20000000* Dengan pemisalan atau dideklarasikan x adalah 20000000

3.  *print ("Modal Awal:",x)* Contoh kalimat *Modal Awal : dan data yang berisi di x yaitu 20000000*

4.  *a=0x, b=0x, c=0.01x, d=0.01x, e=0.05x, f=0.05x, g=0.05x, h=0.03x* Untuk Mendeklarasikan presentase laba tiap bulan dan di kali dengan x atau data inputan modal investasi yaitu 20000000

5.  *t=[a,b,c,d,e,f,g,h]* untuk menentukan syarat t= yang berisi a,b,c,d,e,f,g,h

6.  *Untuk i in range (len (t)) Print (“laba bulan ke-“,i+1,”sebesar:” ,t[i])* untuk perulangan data dengan isi data yaitu tdengan menampilkan urutan laba perbulan sesuai range yang di tentukan dengan hasil ke untukan yang di input dari data t

7.  *u= (a+b+c+d+e+f+g+h) Print (“total laba adalah:”)* u berisi data penjumlahan data angka yang ada didalam kode a,b,c,d, e,f,g,h yang akan ditampilkan atau dicetak di jumlah laba selama 8 bulan

##  D. Hasil
<img width="960" alt="Screenshot_24" src="https://user-images.githubusercontent.com/115913915/199912021-84dbc2e2-bfb6-43bd-8113-896410019884.png">
