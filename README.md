# tugaspemrogramanpert5
tugas pemrograman dasar


## BIODATA
NAMA: Dhani Naufal Habibie

KELAS TI 24.A.4

NIM: 312410300

MATKUL:BAHASA PEMOGRAMAN
Dosen Pengampu: Agung Nugroho, S.Kom, M.Kom

![Screenshot 2024-10-19 095852](https://github.com/user-attachments/assets/18c4eb26-8df1-45df-afb3-dee64f83a5f9)
## PRAKTIKUM 3

# LATIHAN 1

<img width="712" alt="image" src="https://github.com/user-attachments/assets/1447f1ff-cdc7-42cd-a86c-90956cac26f5">
<p># PEMBAHSAN MENGENAI:</p>
<p># PENGGUNAAN END</p>
<p># PENGGUNAAN SEREPATOR</p>
<p># STRING FORMAT</p>

## PENGGUNAAN END
<img width="286" alt="image" src="https://github.com/user-attachments/assets/6d7f5c02-fa7a-46bf-97b4-1bf8f3a45e90">

```python
print('A', end='')
print('b', end='')
print('c', end='')
print()
print('x')
print('y')
print('z')
````

Parameter end dalam fungsi `Print ()` di python di gunakan untuk menambahkan string(" ")apapun diakhir dan mengeluarkan pertanyaan print

```python
print()
````

Secara default,fungsi `print()` akan mengakhiri dengan baris baru,dan akan secara otomatis karakter baris baru di akhir outputnya

inilah hasil program tersebut:

![Screenshot 2024-10-19 105401](https://github.com/user-attachments/assets/e4be0ae6-0c1e-46ab-a947-1470668b5387)

dan ini hasil tanpa menggunakan fungsi `print()` di tengah pada kode program di atas:

![Screenshot 2024-10-19 105727](https://github.com/user-attachments/assets/ce8c4426-642e-4460-b59e-31b88d4bd59b)

## PENGGUNAAN SEREPATOR

![Screenshot 2024-10-19 105946](https://github.com/user-attachments/assets/f883e3f9-751b-4be6-973a-a1720cf8d062)

```python
w, x, y, z, =10, 15, 20, 25
print(w, x, y, z,)
print(w, x, y, z, sep=',')
print(w, x, y, z, sep='')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='-----')
````
pada python penggunaan serepator dapat menggunakan fungsi `split()` atau `sep` yang seperti dalam kode program di atas

serepator ini menentukan pembatasan yang digunakan untuk memisahkan sting,serepator dapat berupa karakter tunggal atau beberapa karakter.jika tidak ditentukan,maka python akan menggunakan spasi sebagai pemisah.

Berikut Hasil Kode Program Diatas:

![Screenshot 2024-10-19 111502](https://github.com/user-attachments/assets/9afa0286-fcd8-437e-8319-0da6019ef34e)

```python
w, x, y, z, =10, 15, 20, 25
````
Variable yang seperti ini menentukan parameter,jadi variable ini tidak bisa memasukan variable angka yang sudah ditentukan w = 10,x=15,y=20,z=25

```python
print(w, x, y, z,)
````

Fungsi ini hanya mencetak saja yang menggunakan fungsi `print()`, tetapi di karenakan mencetak parameter,koma tersebut di hilangkan

```python
print(w, x, y, z, sep=',')
````
karena pemisahnya dihilangkan,kita menggunakan fungsi `sep`atau`split()`dan kita memasukkan pemisahnya didalam string akan memunculkan cetakan yang sesuai keinginan anda dalam memisahkan sesuatu parameter

## STRING FORMAT

![Screenshot 2024-10-19 112724](https://github.com/user-attachments/assets/d5f2d127-76c0-4653-996c-aa5e6d201274)

```python
print(0, 10**0)
print(1, 10**1)
print(2, 10**2)
print(3, 10**3)
print(4, 10**4)
print(5, 10**5)
print(6, 10**6)
print(7, 10**7)
print(8, 10**8)
print(9, 10**9)
print(10, 10**10)

print('{0:>3} {1:>16}'.format(0, 10**0))
print('{0:>3} {1:>16}'.format(1, 10**1))
print('{0:>3} {1:>16}'.format(2, 10**2))
print('{0:>3} {1:>16}'.format(3, 10**3))
print('{0:>3} {1:>16}'.format(4, 10**4))
print('{0:>3} {1:>16}'.format(5, 10**5))
print('{0:>3} {1:>16}'.format(6, 10**6))
print('{0:>3} {1:>16}'.format(7, 10**7))
print('{0:>3} {1:>16}'.format(8, 10**8))
print('{0:>3} {1:>16}'.format(9, 10**9))
print('{0:>3} {1:>16}'.format(10, 10**10))
````
String Format adalah proses memasukan variable atau string kustom ke dalam teks yang sudah ditentukan,dan dapat digunakan untuk berbagai keperluan,seperti memasukan judul dalam grafik,menampilkan pesan atau kesalahan, atau meneruskan kesalahan ke suatu fungsi 

```python
print(0, 10**0)
print(1, 10**1)
print(2, 10**2)
print(3, 10**3)
print(4, 10**4)
print(5, 10**5)
print(6, 10**5)
print(8, 10**8)
print(9, 10**9)
print(10, 10**10)
````

Nilai pertama dalam setiap pasangan adalah angka dari 0 hingga 10, kode program ini dihitung dengan menggunakan operasi pangkat atau fungsinya `(**)` untuk menaikkan 10 ke pangkat yang sesuai dengan angka pertama, yang bisa di bahasa manusiakan variable 0 = 10 pangkat 0, variable 1 10 pangkat 1 dan seterusnya hingga variable 10 yaitu 10 pangkat 10, dan di cetak dengan fungsi `print()`

```python
print('{0:>3} {1:>16}'.format(0, 10**0))
print('{0:>3} {1:>16}'.format(1, 10**1))
print('{0:>3} {1:>16}'.format(2, 10**2))
print('{0:>3} {1:>16}'.format(3, 10**3))
print('{0:>3} {1:>16}'.format(4, 10**4))
print('{0:>3} {1:>16}'.format(5, 10**5))
print('{0:>3} {1:>16}'.format(6, 10**6))
print('{0:>3} {1:>16}'.format(7, 10**7))
print('{0:>3} {1:>16}'.format(8, 10**8))
print('{0:>3} {1:>16}'.format(9, 10**9))
print('{0:>3} {1:>16}'.format(10, 10**10))
````

Kode ini mencetak 11 baris dengan format `{0:3}` `{1:16}` yang di gunakan untuk mengatur format string

Pada string pertama, angka `0` di format untuk memeliki lebar 3 karakter atau yang bisa disebut 3 kali spasi dengan perataan kanan.

angka 1 diformat untuk memiliki lebar 16 Karakter atau 16 kali spasi dengan perataan kanan, dan masing-masing mencetak nilai seperti format di atas dengan fungsi `print()`

# KODE PROGRAM

# 3 INPUT BILANGAN

```Python
a = int(input("masukan angka pertama: "))
b = int(input("masukan angka kedua: "))
c = int(input("masukan angka ketiga: "))

if a > b and a > c:
    print(f"angka lebih besar adalah {a}")
elif b > a and b > c:
    print(f"angka lebih besar adalah {b}")
else:
    print(f"angka lebih besar adalah {c}")
````
Program ini akan menginputkan 3 bilangan dari a yang sampai dengan c.

```python
if a > b and a > c:
    print(f"angka lebih besar adalah {a}")
````
Karna Jika {a} lebih besar dari {b} dan {a} lebih besar dari {c}, output yang keluar adalah {a}

```python
elif b > a and b > c:
   print(f"angka lebih besar adalah {b}")
````
dan jika {b} lebih besar dari {a} dan {b} lebih besar dari {c} maka output yang keluar adalah {b}

```python
else:
    print(f"angka lebih besar adalah {c}")
````
Jika inputan yang diatas lebih kecil dari {c} maka output {c} yang akan keluar

Ini adala hasil program tersebut :

![Screenshot 2024-10-21 145006](https://github.com/user-attachments/assets/f4c76948-9da2-4752-a3fe-94fbcb870e05)



dengan eksekusi program:

![Screenshot 2024-10-21 144833](https://github.com/user-attachments/assets/96aebd26-ec7a-4138-be89-5901c27ee1ce)



dan flowchart sebagai berikut:

<img width="380" alt="Screenshot 2024-10-21 142927" src="https://github.com/user-attachments/assets/a1324c9c-b6c4-437d-9c3b-ae2ee7d217ed">




# MENENTUKAN BILANGAN TERBESAR DARI N DAN BERIKAN ANGKA 0

```python
while True:   
    N = int(input("masukan angka: "))

    if N == 0:
        print(f"angaka terbesar adalah: {max}")
        break
    if N > max:
        max = N
````

Untuk menentukan bilangan terbesar dari n dalam Python, Anda bisa menggunakan fungsi `max()`

```python
max = 0
````
Masukkan daftar angka ke fungsi `max()`, Fungsi `max()` akan mengembalikan angka terbesar dalam daftar

Fungsi `max()` adalah fungsi bawaan Python yang berguna untuk menemukan nilai terbesar dalam suatu iterable atau dalam serangkaian argumen reguler.

```python
if N == 0:
        print(f"angka yang terbesar adalah: {max}")
        break
```
Fungsi ini jika Kita memasukan inputan integer yaitu 0 akan berlanjut ke fungsi break program dihentikan yang artinya selesai.

```python
if N > max:
        max = N
````
Jika Inputan yang kita masukan lebih besar dari fungsi `max()` di atas, program akan melanjutkan ke proses `max = N` yang artinya Angka terbesar akan Mencetak Inputan Bilangan yang kita masukan yang terbesar di cetak

```python
while True:
````
`While true:` adalah konstruksi perulangan dalam bahasa pemrograman Python yang memungkinkan blok kode diulang tanpa batas. dan karna di kode program diatas ada fungsi `While True:` Program terus berlanjut terus menerus, dan ketika kita ingin berhenti saya berikan decision `N==0` dengan fungsi di bawahnya `break` seperti di atas yang berarti Inputan Integer yang di masukan angka 0 program akan di hentikan dan memunculkan cetakan yang terbesar

dan ini hasil program tersebut:

![Screenshot 2024-10-19 124253](https://github.com/user-attachments/assets/4b0860e1-7210-48e9-832d-dbc75982f2a0)

screnshot kode program:

![Screenshot 2024-10-19 124142](https://github.com/user-attachments/assets/6d5e4e98-68cc-48a3-ab4b-e14fd07837f6)

Dan hasil flowchart dari program tersebut:

![WhatsApp Image 2024-10-21 at 14 19 37_0e9774ee](https://github.com/user-attachments/assets/c4e23c81-a18b-4a8b-ac8b-e434261940c5)
