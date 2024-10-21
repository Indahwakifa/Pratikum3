# Praktikum 3 - Tipe Data, Variable, dan Operator

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

## hasil kode program
![foto]
