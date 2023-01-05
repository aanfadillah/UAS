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

<img width="404" alt="a2" src="https://user-images.githubusercontent.com/115763475/210725559-e81beb43-1064-4640-9aa9-b1d737815827.png">


* **Output ubah_data**

<img width="203" alt="a3" src="https://user-images.githubusercontent.com/115763475/210726060-5fb8a36d-01b5-4a4f-83e1-dbc5a0e929b8.png">

<img width="413" alt="a4" src="https://user-images.githubusercontent.com/115763475/210726391-74483094-805a-40ab-8921-41ca75f9ef80.png">


* **Output Cari_data**

<img width="416" alt="a6" src="https://user-images.githubusercontent.com/115763475/210727007-793773ca-cfe2-4a36-bc42-7c77d25009d4.png">


* **Output Hapus_data**

<img width="166" alt="a5" src="https://user-images.githubusercontent.com/115763475/210727212-e82eadd3-d58e-4dfb-adee-e40f7b41c871.png">


<img width="411" alt="a7" src="https://user-images.githubusercontent.com/115763475/210727265-4f9a36b2-fdd0-49df-a549-26180fd3cc16.png">


## **TERIMA KASIH**
