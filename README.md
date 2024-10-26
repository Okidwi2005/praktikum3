# 1.Program Mencari Bilangan Terbesar Dari N Bilangan
Program untuk mencari nilai terbesar dari bilangan yang dimasukan oleh pengguna menggunakan loop while True dan break statement.

## Deskripsi Program
    - Menampilkan bilangan terbesar
    - Menggunakan while true untuk mengulang
    - Mengunakan break statement untuk memberhentikan program
    - Membandingkan setiap input dengan nilai maksimum yang tersimpan

## Flowchart Program
![Flowchart](https://github.com/user-attachments/assets/95cc0530-a1e8-42d2-a03b-bfd2b392838e)

## Code Program
```Python
max = 0

while True:
    bilangan = int(input("Masukan bilangan(0 untuk berhenti): "))
    if bilangan == 0:
        break
    if bilangan > max:
        max = bilangan

print(f"Bilangan terbesar: {max}")
```

## Output Program
````
Masukan bilangan(0 untuk berhenti): 8
Masukan bilangan(0 untuk berhenti): 5
Masukan bilangan(0 untuk berhenti): 8
Masukan bilangan(0 untuk berhenti): 98
Masukan bilangan(0 untuk berhenti): 57
Masukan bilangan(0 untuk berhenti): 0
Bilangan terbesar: 98
````

## Cara Kerja Program
Program menginisialisasi variabel max dengan nilai 0
Program memulai loop tak terbatas dengan while True
Di dalam loop:

Program meminta user memasukkan bilangan
Jika user memasukkan 0, program akan keluar dari loop dengan break
Jika bilangan yang dimasukkan lebih besar dari nilai max saat ini, nilai max diperbarui


Setelah keluar dari loop, program menampilkan bilangan terbesar

# 2.Mencari Bilangan Terbesar Dari 3 Variabel
Program untuk menentukan bilangan terbesar dari tiga angka yang diinputkan pengguna.

## Deskripsi Program
    - Menampilkan hasil ke layar
    - Membandingkan ketiga bilangan
    - Menentukan bilangan mana yang terbesar
    - Meminta user memasukan 3 bilangan berbeda

## Flowchart Program
![FLOWCHART (2)](https://github.com/user-attachments/assets/0df46d4f-4a56-49b1-91a8-a19dbc92aeb4)

## Code Program

```python
a = int(input("Masukkan bilangan A: "))
b = int(input("Masukkan bilangan B: "))
c = int(input("Masukkan bilangan C: "))

if a > b:
    if a > c:
        print("Terbesar adalah A")
        terbesar = a
    else:
        print("Terbesar adalah c")
        terbesar = c
else:
    if b > c:
        print("Terbesar adalah B")
        terbesar = b
    else:
        print("Terbesar adalah C")

print(f"Bilangan terbesar adalah: {terbesar}")
```

## Output Program

```
Masukkan bilangan A: 8
Masukkan bilangan B: 2
Masukkan bilangan C: 5
Terbesar adalah A
Bilangan terbesar adalah: 8
```

## Cara Kerja Program
Program bekerja dengan algoritma:
1. Menerima input 3 bilangan (A, B, C) dari user
2. Melakukan pengecekan dengan urutan:
     - Apakah A > B?
       - Jika ya: cek apakah A > C?
       - Jika ya: A adalah terbesar
       - Jika tidak: C adalah terbesar
     - Jika tidak: cek apakah B > C?
       - Jika ya: B adalah terbesar
       - Jika tidak: C adalah terbesar
3. Menampilkan hasil bilangan terbesar yang ditemukan
