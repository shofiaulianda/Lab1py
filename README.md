# Lab1py
### Nama  : Shofi Aulianda
### NIM  : 312510183
### Kelas : TI.25.A.2

## Latihan 1 :
<img width="539" height="123" alt="latihan 1" src="https://github.com/user-attachments/assets/f55206bc-01cb-44e0-a395-9cae1816cbf7" />

## Latihan 2 :
<img width="537" height="186" alt="Screenshot_20251019_184218" src="https://github.com/user-attachments/assets/e626b61e-c6a4-4270-9f52-9f4b49df96f7" />

## Latihan 3 :
Code program :    
<img width="587" height="273" alt="Screenshot_20251019_200746" src="https://github.com/user-attachments/assets/66a8e287-b029-41bb-9057-04e9ad12b78c" />

Output :    
<img width="782" height="173" alt="Screenshot_20251019_201207" src="https://github.com/user-attachments/assets/12522094-ee6f-4217-9d38-b239788fc981" />

### Penjelasan dari proses program :
```
a = input("Masukkan nilai a: ")
b = input("Masukkan nilai b: ")
```
Penjelasan :    
Program meminta pengguna (user) untuk memasukkan dua nilai, yaitu a dan b.    
Fungsi input() akan selalu menghasilkan tipe data string.   
Jadi di tahap ini, a dan b masih berupa teks.    

```
print("Variabel a =", a)
print("Variabel b =", b)
```
Penjelasan :   
Menampilkan nilai a dan b yang telah dimasukkan oleh user agar bisa dilihat ulang.    

```
print("Hasil penggabungan {1}&{0} = {2}".format(a, b, a + b))
```

Penjelasan :
Karena a dan b masih berupa string, maka tanda + akan menggabungkan teks, bukan menambahkan angka.   

```
a = int(a)
b = int(b)
```

Penjelasan :   
Mengubah nilai a dan b dari string menjadi integer supaya bisa digunakan untuk operasi matematika seperti penjumlahan dan pembagian.   

```
print("Hasil penjumlahan {1}+{0} = {2}".format(a, b, a + b))
```

Penjelasan :
Sekarang karena a dan b sudah bertipe int, operator + akan menghitung hasil penjumlahan.   

```
print("Hasil pembagian {1}/{0} = {2}".format(a, b, a / b))
```

Penjelasan :   
Operator / digunakan untuk menghitung hasil pembagian dua angka.    
Hasilnya berupa bilangan pecahan (float).   
