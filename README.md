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
