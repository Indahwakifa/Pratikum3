(# Praktikum 3 - Tipe Data, Variable, dan Operator

Nama :indah wafikah

Kelas : TI.24.A.5

NIM : 312410559

Mata Kuliah : Bahasa Pemograman


## mencari bilangan terbesar dari bilangan yang di inputkan
program ini menentukan bilangan terbesar dari serangkaian bilangan yang di inputkan hingga input 0,program ini menggunakan loop `while` dan kondisi `if` untuk memperbarui nilai terbesar yang ditemukan

## Flowchart Program
![Foto](https://github.com/Indahwakifa/Flow-chart/blob/d481cd30572e66f9de422a85779f3337fdc4d1a5/IMG-20241021-WA0112.jpg) 

```python
largest = float('-inf')  # Menginisialisasi Largest dengan -∞

while True:
    print("Enter 0 to stop")
    n = float(input("Input a number: "))  # Meminta input dari pengguna

    if n == 0:
        break  # Keluar dari loop jika input adalah 0

    if n > largest:
        largest = n  # Update nilai Largest jika n lebih besar

if largest == float('-inf'):
    print("No numbers were entered.")
else:
    print("The largest number is:", largest)
```
## penjelasan kode program

```python
maxBilangan = float('-inf')  # -∞
count = 0
```

N = int(input("Masukkan jumlah bilangan: "))
Bagian ini meminta pengguna untuk memasukkan jumlah bilangan yang akan dimasukkan (dalam bentuk bilangan bulat). Fungsi input() mengambil input dari pengguna, lalu int() mengubahnya menjadi tipe data integer.

```python
max_num = 0

Di sini, variabel max_num diinisialisasi dengan nilai 0. Variabel ini akan digunakan untuk menyimpan bilangan terbesar yang ditemukan dalam proses loop
```
for i in range(1, N+1): num = int(input(f"Masukkan bilangan ke-{i}: "))

Bagian ini adalah loop for yang berjalan sebanyak N kali, mulai dari 1 hingga N. Pada setiap iterasi, pengguna diminta untuk memasukkan bilangan melalui input(). Setiap bilangan yang dimasukkan dikonversi menjadi tipe integer dan disimpan dalam variabel num.

```python
if num > max_num:
    max_num = num
```
Pada setiap iterasi, bilangan yang dimasukkan `(num)` akan dibandingkan dengan `max_num`. Jika `num` lebih besar dari `max_num`, maka `max_num` akan diperbarui dengan nilai `num`. Hal ini memastikan bahwa `max_num` selalu menyimpan bilangan terbesar yang ditemukan sejauh ini.

```python
print("Bilangan terbesar adalah:", max_num)
```
Setelah loop selesai, program akan mencetak nilai dari max_num, yaitu bilangan terbesar yang ditemukan dari seluruh input.

## hasil kode program

![foto](https://github.com/Indahwakifa/Flow-chart/blob/841e85e121070df48c53a34f9838035486966ed1/IMG-20241021-WA0122.jpg) 
