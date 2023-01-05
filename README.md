# UAS
# PACKAGE & MODULE
**saya di beri tugas UAS ini  dengan struktur seperti sebagai berikut:**

![soal uas](https://user-images.githubusercontent.com/93035757/149618916-d7707552-7229-4def-930f-5a706dd00ac1.png)
 
* ``daftar_nilai.py`` berisi modul untuk  :
    * tambah_data
    * ubah_data
    * hapus_data
    * cari_data 
* ``view_nilai.py`` berisi modul untuk : 
    * cetak_daftar_nilai 
    * cetak_hasil_pencarian
* ``input_nilai.py`` berisi modul untuk :
    * input_data (yang meminta pengguna memasukkan data).
* ``main.py`` berisi program utama (menu pilihan yang memanggil semua menu yang ada).

* hasil package yang saya buat sebagai berikut :

<img width="232" alt="m6" src="https://user-images.githubusercontent.com/115542704/210501105-4bef13cb-9371-4df1-9482-431a33f11b31.png">

* pertama saya telah menyantumkan beberapa syntax yang nantinya akan menghasilkan semua modul dari package Daftar_Nilai yang diantaranya adalah (Tambah Data, Ubah Data, Hapus Data, Dan Cari Data)

```py

from view.input_nilai import *
data={}
class daftarnilai():
    def tambah_data(self):
        tambah_nama = nama()
        tambah_nim = nim()
        tambah_tugas = tugas()
        tambah_uts = uts()
        tambah_uas = uas()
        tambah_akhir = akhir()
        data[tambah_nama]= tambah_nim,tambah_tugas,tambah_uts,tambah_uas,tambah_akhir

    def ubah_data(self):
        ubah_nama = nama()
        if ubah_nama in data.keys():
           
            tambah_nim = nim()
            tambah_tugas = tugas()
            tambah_uts = uts()
            tambah_uas = uas()
            tambah_akhir = akhir()
            data[ubah_nama]= tambah_nim,tambah_tugas,tambah_uts,tambah_uas,tambah_akhir
        else:
            print('data tidak ditemukan !!!')

    def hapus_data(self):
        hapus_nama = nama()
        if hapus_nama in data.keys():
            del data[hapus_nama]
            print('data berhasil di hapus')
        else:
            print('data tidak ditemukan !!!')

    def keluar(self):
    
```
     
* **Output tambah_data**

<img width="217" alt="a1" src="https://user-images.githubusercontent.com/115763475/210725396-05be56c9-e2d0-4944-89a8-cf5b97beea10.png">


* **Output daftar_nilai**

<img width="413" alt="j5 1" src="https://user-images.githubusercontent.com/115516607/210513194-f3706531-005d-4203-b1f7-01e2ccbbbf44.png">

* **Output ubah_data**

<img width="200" alt="j2" src="https://user-images.githubusercontent.com/115516607/210513325-58a3b99e-5b96-4533-b6a6-5a6acf16c5a2.png">

<img width="419" alt="j5 2" src="https://user-images.githubusercontent.com/115516607/210513354-9c7fca26-78c8-4ece-81f1-be38843934ca.png">

* **Output Cari_data**

<img width="413" alt="j3" src="https://user-images.githubusercontent.com/115516607/210513550-018c6c56-e175-4657-ac41-c3e2788419bd.png">

* **Output Hapus_data**

<img width="173" alt="j4" src="https://user-images.githubusercontent.com/115516607/210513657-65b12d03-342e-437d-800a-1833830d77db.png">

<img width="419" alt="j5 3" src="https://user-images.githubusercontent.com/115516607/210513684-25508ba2-6b8d-4147-9721-2fcb81922d4c.png">

## **TERIMA KASIH**
