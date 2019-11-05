# TUGAS PRAKTIKUM 3
# Latihan1

    Source Code
```
n=int(input("Masukkan Nilai N: "))          ## Memperkenalkan variable n sebagai integer, kemudian menginputkan nilainya

from random import random                   ## Mengimport fungsi random
a=random()                                  ## Memperkenalkan variale a sebagai random

jumlah=n+1                                  ## Jumlah = varible n + 1
start=1                                     ## Dimulai dari angka 1
stop=jumlah                                 ## Berhenti ketika variable jumlah sudah sesuai
step=1                                      ## Step angka 1

for i in range(start,stop,step):            ## Perulangan i dengan nilai awal variable start, nilai akhir variable stop dan step variable step
    print("data ke : ",i,"=",(a))           ## Mencetak hasil
print("\nDone")
```
```
    Algoritma

A. Input 
    Print
        >> print berfungsi untuk mencetak atau menampilkan objek ke perangkat keluaran (layar) atau ke file teks.
    from random import random
        >> import yaitu fungsi lanjut yang dipanggil oleh statement import.sedangankan random untuk menentukan suatu
        pilihan. yang berarti menggabungkan dua operasi.
    a=random()
        >> memperkenalkan variale a sebagai random
    jumlah=n+1
        >> Jumlah = varible n + 1
    start=1
        >> Dimulai dari angka 1
    stop=jumlah
        >> Berhenti ketika variable jumlah sudah sesuai
    step=1
        >> Step angka 1
        
B. Process 
    n = int(input("Masukan Nilai N: "))
        >>merupakan fungsi untuk menghasilkan interger
    for i in range(start,stop,step):
        >>Perulangan i dengan nilai awal variable start, nilai akhir variable stop dan step variable step\
        
C. Output
    print("data ke : ",i,"=",(a))
        >> Mencetak hasil
    print("\nDone")
        >>Berfungsi untuk mencetak teks "Done" yang bertanda bahwa program sudah berakhir
 ```
