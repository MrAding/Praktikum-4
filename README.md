# Tugas Praktikum

Buat program sederhana untuk menambahkan data kedalam sebuah list dengan rincian sebagai berikut:
- Progam meminta memasukkan data sebanyak-banyaknya (gunakan perulangan)
- Tampilkan pertanyaan untuk menambah data (y/t?), apabila jawaban t (Tidak), maka program akan menampilkan daftar datanya.
- Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%, uts: 35%, uas: 35%)
- Buat flowchart dan penjelasan programnya pada README.md
- Commit dan push repository ke github.

# Codingan
```
nama = input("Masukan Nama:")
nim = input("Masukan NIM:")
uts = input("Masukan Nilai UTS:")
uas = input("Masukan Nilai UAS:")
tugas = input("Masukan Nilai Tugas:")

akhir = (int(tugas) * .2) + (int(uts) * .4) + (int(uas) * .4)

print("\nNama               :",nama)
print("\nNIM                :",nim)
print("Nilai UTS            :",uts)
print("Nilai UAS            :",uas)
print("Nilai Tugas          :",tugas)
print("Nilai Akhir          :",akhir)

print ('')
print ('Tambah Data? (ya/tidak)')
x=input()
```
# Tampilan Codingan :
![ss codingan 1](https://user-images.githubusercontent.com/46867774/143394772-fbebca81-6870-4034-910b-e066eec40b0e.PNG)


# Hasil Codingan :
![ss codingan 2](https://user-images.githubusercontent.com/46867774/143394817-945f1d7f-4af1-4192-9f0f-cd20c8706a4f.PNG)
