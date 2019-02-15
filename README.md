#tugas2
Algoritma menentukan nilai terbeasar dari 3 buah bilangan.

Diketahui 3 buah bilangan Bil1, Bil2, Bil3 akan dicari nilai terbesar.

1. Mulai
2. Inisiasi Bil1, Bil2, Bil3 sebagai Integer
3. Baca Bil1
4. Baca Bil2
5. Baca Bil3
6. Jika Bil1 > Bil2 dan Bil1 > Bil3 maka kerjakan langkah nomor 8, selain itu.
7. Jika Bil2 > Bil1 dan Bil2 > Bil3 maka kerjakan langkah nomor 9, selain itu kerjakan langkah nomor 10
8. Cetak "Bilangan terbesar bilangan pertama"
9. Cetak "Bilangan terbesar bilangan kedua"
10. Cetak "Bilangan terbesar bilangan ketiga"
11. Selesai

Berikut dibawah ini Flowchart dari program tersebut
flowchart-1

![flowchart](https://user-images.githubusercontent.com/46748866/52863131-9b662300-3169-11e9-81c9-d5e1cea9e139.jpg)


Gunakan statement if untuk A sebagai inisiasi Bilangan Pertama.
Gunakan statement elif untuk B sebagai inisiasi Bilangan Kedua.
Gunakan statement else untuk C sebagai inisiasi Bilangan Ketiga.
Kemudian Run
Silahkan lihat contoh di bawah ini :

('menentukan bilangan terbesar')

print ('masukan 3 bilanngan yang diinginkan')

a = int (input ('bilangan pertama = '))

b = int (input ('bilangan kedua = '))

c = int (input ('bilangan ketiga = '))


if a>b and a>c :
  
  print ('bilangan terbesar =',a)

elif b>a and b>c :
  
  print ('bilangan terbesar =',b)

else :
  
  print (c,'bilangan terbesar =',c)

Berikut hasil screenshot dari program tersebut :
1. Bilangan Pertama yang menjadi bilangan terbesar.if

![gambar 1](https://user-images.githubusercontent.com/46748866/52863400-57bfe900-316a-11e9-8d8a-659aecd0ea5e.png)


2. Bilangan Kedua yang menjadi bilangan terbesar.elif

![gambar 2](https://user-images.githubusercontent.com/46748866/52863559-d0bf4080-316a-11e9-9b58-ab6a19ad3696.png)


3. Bilangan Ketiga sebagai bilangan terbesar.else

![gambar 3](https://user-images.githubusercontent.com/46748866/52864605-0ebd6400-316d-11e9-964d-0f73f1fe9e4b.png)

Terima Kasih.