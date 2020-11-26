# Pertemuan9

### NAMA  : MUHAMMAD BISMA PUTRA H
### NIM   : 312010443   
### KELAS : TI.20.A.1

________________________________________________________________________________________________________________
## Program Data Mahasiswa
pada praktikum 5 ini, saya akan membuat program sederhana untuk menginput data kedalam list.



### Membuat Pintasan "Keluar"
Kali ini kita akan membuat pintasan "keluar" dengan baris perintah sebagai berikut

```python
    if menu.lower() == 'k':
        break
```
![gitpush](foto/1.png) <br>

### Membuat Pintasan "lihat"
dan ini adalah baris perintah untuk membuat perintah "lihat"

```python
    elif menu.lower() == 'l':
        print("Daftar Nilai:")
        print("_______________________")
        print("| No |      Nama      |    NIM    | Tugas |  UTS  |  UAS  | Akhir |")
        print("===================================================================")
        no = 1
        for tabel in data.values():
            print("| {0:2} | {1:14} | {2:9} | {3:5} | {4:5} | {5:5} | {6:5} |".format
                  (no, tabel[0],
                   tabel[1], tabel[2],
                   tabel[3], tabel[4], tabel[5]))
            no += 1
```
![gitpush](foto/2.png) <br>

