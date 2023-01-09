# Nama  : Zalfa Dewi Zahrani

# Nim   : 312210320

# Kelas :TI.22.A3

# Package & Module

# Tugas ini berdasarkan praktikum sebelumnya dengan struktur seperti ini :

![Screenshot (198)](https://user-images.githubusercontent.com/115516617/211242905-29ebf1c9-47f9-4cdf-833f-4928c6c14ea2.png)

```daftar_nilai.py``` Berisi Modul Untuk:

*tambah_data

*ubah_data

*hapus_data

*cari_data

```view_nilai.py``` Berisi Modul Untuk:

*cetak_daftar_nilai

*cetak_hasil_pencarian

```input_nilai.py``` Berisi Modul Untuk:

*input_data(yang meminta pengguna masukkan data)

```main.py``` Berisi Program Utama

*Memanggil semua menu yang yang ada

Kemudian saya tlah menyamtukan syntax yang nanti akan menghasilkan semua modul dari daftar_nilai yang diantaranya adalah (tambah data,ubah data,lihat data,hapus data,dan cari data)

      ```from model.daftar_nilai import *
      from view.view_nilai import *

      #Mulai
      print("===============================================================")
      print("|                           Program                           |")
      print("===============================================================")

    while True:
    print("\n")
    menu = input("(L) Lihat, (T) Tambah, (H) Hapus, (U) Ubah, (C) Cari, (K) Keluar\nPilih menu: ")
    print("\n")

    # menu
    if menu.lower() == 't':
        tambah_data()

    elif menu.lower() == 'c':
        cari_data()

    elif menu.lower() == 'l':
        lihat_data()

    elif menu.lower() == 'u':
        ubah_data()

    elif menu.lower() == 'h':
        hapus_data()

    # Keluar
    elif menu.lower() == 'k':
        break

    else:
        print("Upss ada yang salah, silahkan cek kembali.")```
OUTPUTNYA :
        
# output tambah_data

![Screenshot (206)](https://user-images.githubusercontent.com/115516617/211342606-5271a23b-9cae-4721-88fe-b2a2c97f3a3c.png)

# output lihat_data

![Screenshot (207)](https://user-images.githubusercontent.com/115516617/211342841-671b93c4-715e-4597-a93e-fa3769058884.png)

# output ubah_data

![Screenshot (208)](https://user-images.githubusercontent.com/115516617/211342982-34fb6557-cb87-4e8b-90ca-ac46ceb0b3a1.png)

# output cari_data

![Screenshot (209)](https://user-images.githubusercontent.com/115516617/211343166-726e8c70-6bf8-4f43-9bf2-f8e47be43c2b.png)

# output hapus_data

![Screenshot (210)](https://user-images.githubusercontent.com/115516617/211343267-38c38f8e-a671-4046-99a5-8a133c470b32.png)

sekian..


