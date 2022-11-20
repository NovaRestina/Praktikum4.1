# Praktikum4.1
## Penjelasan Program

Tampilan Program menggunakan Bahasa Python

![ss1](https://user-images.githubusercontent.com/115637858/202917388-4806e4c7-5da4-4647-9646-a282472c2e7f.png)

1. Untuk Membuat tabel disini saya menggunakan PrettyTable yang sudah tersedia diPython ,dibagian Pyhton Packages lalu tulis prettytable kemudian muncul tulisan dan klik instal prettytable dan untuk menggunakan prettytable kita harus import dahulu prettytable kedalam program.

      >  format prettytable import PrettyTable

2.  print("Program input Data Mahasiswa")
    print() untuk menampilkan kalimat yang akan diinput

    tabelNama = PrettyTable(["No" ,"Nama" ,"NIM" ,"Nilai Tugas" ,"Nilai UTS" ,"Nilai UAS" ,"Nilai Akhir"])
    a = 0

    mengimput data tabelNama untuk memanggil.lalu Prettytable digunakan untuk memasukkan semua list tersebut. a = 0 digunakan untuk menambhkan nomor pada tabel

3. Membuat Perulangan Menggunakan While True

        >while True:
        > a += 1
        > b = input("Masukkan Nama : ")
        > c = input("Masukkan NIM : ")
        > d = int(input("Masukkan Nilai Tugas : "))
        > e = int(input("Masukkan Nilai UTS : "))
        > f = int(input("Masukkan Nilai UAS :" ))
        > g = "{:.2f}".format((d*.30) + (e*.35) + (f*.35))

    a untuk menginput nomer pada awal tabel, input () digunakan untuk menulis apa yang diinginkan oleh user , lalu yang g di gunakan untuk menjumlahkan  semua nilai tugas 30% + uts 35% + uas 35%  menjadi hasil rata-rata atau Nilai  Akhir dengan perhitungan 3 komponen nilai. 
        
            tabelNama.add_row([a,b,c,d,e,f,g])
            tabelNama.horizontal_char = "="
            tabelNama.junction_char = "="
    digunakan untuk membuat kolom pada tabel.

4. Setelah itu masukkan semua data yang sudah diisi ke dalam tabel. Didalam program ada pilihan [y/t] , apabila jawabanya t (tidak), maka program otomatis berhenti dengan statement break dan akan menampilkan data yang sudah diinput tadi.

# Tampilan  hasil dari output programnya

![ss2](https://user-images.githubusercontent.com/115637858/202917400-5109b39f-42b5-4adc-9eb2-f915169381b9.png)

# FLOWCHART

Berikut ini tampilan Flowchart

<img width="312" alt="ss3" src="https://user-images.githubusercontent.com/115637858/202917427-5fcf7781-b033-43a3-b0c2-425e60df6f74.png">