### Nama : Avrillia Nur Hidayah

### NIM : 312210309

### Kelas : TI.22.A3

# Praktikum 3

## Latihan 1

### penggunaan end

dalam fungsi cetak digunakan untuk menambahkan string apapun. Diakhir outputnya (end='') melewati spasi ke parameter menunjukkan bahwa karakter akhir harus diidentifikaiskan oleh spasi

```
print('A', end='')
print('B', end='')
print('C', end='')
print()
print('X')
print('Y')
print('Z')
```

![Screenshot (594)](https://user-images.githubusercontent.com/115686359/198209113-84a18816-28f0-4389-a460-56252e4e31b8.png)

### penggunaan separator

```
w, x, y, z= 10, 15, 20, 25
print(w, x, y, z)
print(w, x, y, z, sep=',')
print(w, x, y, z, sep='')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='-----')
```

![Screenshot (594)](https://user-images.githubusercontent.com/115686359/198211343-21136587-2efa-4a92-81a6-444e4ef79f0b.png)



### String Format

Format string kemungkinan memasukan item ke dalam string dari pada menggabungkan string menggunakan koma atau string contatenation.

```
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
```

![Screenshot (595)](https://user-images.githubusercontent.com/115686359/198214330-eebd10af-726e-4d85-8f8b-25a91d10c575.png)

### String Format 2

```
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
```

![Screenshot (596)](https://user-images.githubusercontent.com/115686359/198215087-002db1e5-0b56-4074-9b5b-3c84e8ef8877.png)




