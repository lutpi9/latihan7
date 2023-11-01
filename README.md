#LATIHAN 1(7)
TUGAS STRUKTUR KONDISI
#LATIHAN 1
Buat program sederhana dengan input 2 buah bilangan, kemudian tentukan bilangan terbesar dari kedua bilangan tersebut menggunakan statement if.

#Masukan input 
bil1 = int (input("Masukan bilangan : "))
bil2 = int (input("Masukan bilangan : "))

#Nilai terbesar

if (bil1 > bil2):
   print("Bilangan terbesar :",bil1)

#Nilai terkecil

if (bil1 < bil2):
   print("Bilangan terbesar :",bil2)
   #HASIL PROGRAM
   ![image](https://github.com/lutpi9/latihan7/assets/147919251/840fa5cd-1323-441a-b7ec-f436abdd0ba6)

   
#LATIHAN 2
Buat program untuk mengurutkan data berdasarkan input sejumlah data (minimal 3 variable input atau lebih), kemudian tampilkan hasilnya secara berurutan mulai dari data terkecil.

#Masukan inputan
bil1 = int(input("Bilangan ke-1: "))
bil2 = int(input("Bilangan ke-2: "))
bil3 = int(input("Bilangan ke-3: "))

#Buat variable data
data = [bil1, bil2, bil3]

#Menampilkan data
print("Data sebelum di urutkan :", data)
list.sort(data)
print("Data setelah di urutkan :", data)
#HASIL PROGRAM
![image](https://github.com/lutpi9/latihan7/assets/147919251/8100890f-635f-4ba4-9fcb-585cb40b9ad9)


#LATIHAN2(7)
TUGAS PERULANGAN
buat program dengan perulangan bertingkat (nested) for yang menghasilkan output sebagai berikut:
#LATIHAN 1
Buat program sederhada dengan input 2 buah bilangan, kemudian tentukan bilangan terbesar dari kedua bilangan tersebut menggunakan statement if.
baris = 10
kolom = baris

for bar in range(baris):
    for col in range(kolom):
        tab = bar+col
        print("{0:>5}".format(tab), end='')
    print()
#HASIL PROGRAM
    ![image](https://github.com/lutpi9/latihan7/assets/147919251/bf1d176f-bb8a-4f2d-8056-30a59769f8c3)

    
#LATIHAN 2
TUGAS PERULANGAN
tampilkan bilangan acak yang lebih kecil dari 0.5. nilai diisi pada saat runtime anda bisa menggunakan kombinasi while dan for untuk menyelesaikannya.
import random

print("===========================================")
print("= Bilangan acak yang lebih kecil dari 0,5 =")
print("===========================================")

jum = int( input("Masukan nilai: "))
i = 0
while i in range(jum):
    i += 1
    angkarandom = random.uniform(0,0.5)
    print("Bilangan ke :", i, " : ", angkarandom)
#HASIL PROGRAM
![image](https://github.com/lutpi9/latihan7/assets/147919251/b5f136c8-4e0b-4473-aea2-9f54c2826557)





    




