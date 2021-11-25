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
![ss codingan 1](https://user-images.githubusercontent.com/46867774/143392046-4feb4521-efb9-4200-a78f-74fa8e6043ef.PNG)

# Hasil Codingan :
![ss codingan 2](https://user-images.githubusercontent.com/46867774/143392401-903457e4-6096-492d-b870-737e10b91a4b.PNG)
