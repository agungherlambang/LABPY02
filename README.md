# BIODATA
# NAMA: AGUNG HERLAMBANG
# NIM: 312410296
# KELAS: TI.4.A4
## TUGAS 1

### MEMBUAT PROGRAM MENENTUKAN NILAI AKHIR

### DESKRIPSI

Program ini dirancang untuk menghitung nilai akhir mahasiswa berdasarkan beberapa komponen penilaian, seperti nilai UTS (Ujian Tengah Semester), UAS (Ujian Akhir Semester), dan tugas. Program akan menampilkan nilai akhir dan memberikan keterangan mengenai status kelulusan.

 >20% untuk nilai tugas

 >40% untuk nilai UTS

 >40% untuk nilai UAS

### PENJELASAN PROGRAM

   '''pyton
    akhir = (int(tugas) * .2) + (int(uts) * .4) + (int(uas) * .4)
    
Perhitungan: Menghitung nilai akhir dengan bobot yang sesuai.

Keterangan: Menentukan apakah siswa lulus atau tidak berdasarkan nilai akhir.

Penentuan Huruf: Mengonversi nilai akhir menjadi huruf sesuai dengan kriteria yang diberikan.

Output: Menampilkan hasil perhitungan.

    akhir = (int(tugas) * .2) + (int(uts) * .4) + (int(uas) * .4)    

 Fungsi dari integer dalam pemrograman adalah untuk merepresentasikan nilai bilangan bulat, baik positif maupun negatif, serta nol. Integer biasanya digunakan dalam operasi matematika seperti penjumlahan, pengurangan, perkalian, dan pembagian.

 fungsi dari * untuk mengkalikan angka,dan fungsi dari  .2 adalah 0 koma 2

 dan nilai tugas yang di masukan 90 ,maka akan dikalikan program di atas .2 yaitu( 0.2) maka keluar cetakan 18

    keterangan = ("TIDAK LULUS", "LULUS")[akhir > 60,0]

keterangan ini hanya sebuah variable yang nantinya akan di cetakan,dan hasil ahkir akan memproses

    if akhir > 80:
    huruf = "A"
    elif akhir > 70:
    huruf = "B"
    elif akhir > 50:
    huruf = "C"
    elif akhir > 40:
    huruf = "D"
    else:
    huruf = "E"

ini adalah struktur kondisi yang menggunakan if, elif , danelse

    if akhir > 80:
       huruf = "A"

jika hasil dari nilai tersebut lebih besar dari 80 maka output yang keluar (A)

    else:
    huruf = "E"

jika tidak sesuai semuanya pada program di atas output akan keluar(E)

### struktur program

Input:

• Nama siswa

• Nilai UTS (float)

• Nilai UAS (float)

• Nilai Tugas (float)

Output:

• Nama siswa

• Nilai UTS

• Nilai UAS

• Nilai Tugas

• Nilai Akhir

• Nilai Huruf

• Keterangan ("LULUS" atau "TIDAK LULUS")

# berikut screenshot visualcode

![gambar](https://github.com/user-attachments/assets/807f2516-f3bd-49d8-a340-303c89a782aa)

# latihan 2

### MEMBUAT PROGRAM MENAMPILKAN GAJI KARYAWAN 

### DESKRIPSI

Program ini menerima input gaji, status keluarga (sudah berkeluarga atau belum), dan status kepemilikan rumah dari pengguna, kemudian melakukan beberapa pengecekan sebagai berikut:

>Apakah gaji di atas UMR (Upah Minimum Regional).

>Jika gaji di atas UMR, program akan mengecek apakah pengguna sudah berkeluarga untuk menentukan kewajibam mengikuti asuransi dan menabung.

>Program juga mengecek apakah pengguna memiliki rumah untuk menentukan kewajiban membayar pajak rumah.

### PENJELASAN PROGRAM

1.Input Data Karyawan:
Program meminta input dari pengguna untuk nama karyawan, gaji pokok, dan total potongan gaji. Menghitung Gaji Bersih:

2.Menghitung Gaji Bersih:

Gaji bersih dihitung dengan mengurangi gaji pokok dengan total potongan:

gaji_bersih

gaji_pokok − potongan

    gaji_bersih=gaji_pokok−potongan

4.Output:
Program mencetak rincian gaji karyawan, termasuk nama, gaji pokok, potongan, dan gaji bersih. struktur ini menggunakan kondisi if, elif, dan else

     gaji = int(input("Masukkan gaji:"))

inputan ini akan memasukan angka gaji,karena memiliki fungsi int

    berkeluarga = (False, True)[input("Sudah berkeluarga? (Y/T)") == "Y"]
    punya_rumah = (False, True)[input("Punya rumah? (Y/T)") == "Y"]

inputan ini menggunakan fungsi string yang di masukan berupa huruf,dan (false,true) ini adalah fungsi pemilihan Ya atau Tidak,agar tidak meggunakan if di lanjutan program tersebut

if gaji > 2500000:
    print ("Gaji sudah diatas UMR")

    if berkeluarga:
        print ("Wajib ikutan asuransi dan menabung untuk pensiun")
    else:
        print ("Tidak perlu ikutan asuransi")

jika angka gaji angka gaji lrbih dari 3 juta maka output yang keluar"gaji sudah diatas UMR" dan jika tidak,output yang keluar"Tidak perlu ikut asuransi"

if punya_rumah:
        print ("wajib bayar pajak rumah")

    else:
        print ("tidak wajib bayar pajak rumah")

Jika memiliki rumah maka output yang keluar adalah"Wajib bayar pajak", Jika tidak mempunyai rumah maka output yang keluar ialah "Tidak wajib bayar pajak"

    else:
          print ("Gaji belum UMR")        

else yang berada di paling bawah ini terhubung dengan if Gaji > 2500000: apabila gaji tidak melebihi dari 3 juta output yang keluar"gaji belum UMR"

### STRUKTUR PROGRAM

    • Input:

    • Gaji (int)

    • Status berkeluarga (Y/T)

    • Status kepemilikan rumah (Y/T)

    • Output:

    • Apakah gaji sudah di atas UMR atau belum

    • Kewajiban mengikuti asuransi jika sudah berkeluarga

    • Kewajiban membayar pajak rumah jika punya rumah

![gambar](https://github.com/user-attachments/assets/d8b63244-a5b7-41b9-a7cf-b2fff9445028)

### BERIKUT SCREENSHOT VISUALCODE

![gambar](https://github.com/user-attachments/assets/46965e65-1949-4448-81ea-4f9d0b9331bb)

# LATIHAN 3

### PENGGUNAAN KONDISI OR

### DESKRIPSI

Kondisi OR adalah operator logika yang digunakan untuk mengevaluasi dua atau lebih ekspresi kondisi. Dalam bahasa pemrograman Python, operator ini memungkinkan kita untuk memeriksa beberapa kondisi sekaligus. Jika salah satu atau lebih dari kondisi tersebut bernilai True, maka keseluruhan pernyataan akan dianggap True. Sebaliknya, jika semua kondisi bernilai False, maka hasilnya adalah False. Penggunaan kondisi OR sangat berguna dalam berbagai situasi di mana beberapa kondisi perlu dievaluasi. Operator ini memudahkan pengambilan keputusan dalam logika program, sehingga membuat kode menjadi lebih ringkas dan efisien. Dengan memahami cara kerja OR, programmer dapat menciptakan skrip yang lebih kompleks dan dinamis.

### PENJELASAN OR

1.Definisi Operator OR adalah operator logika yang digunakan untuk mengevaluasi dua atau lebih kondisi. Dalam Python, operator ini ditulis sebagai or. Jika salah satu dari kondisi tersebut bernilai True, maka keseluruhan ekspresi juga akan bernilai True. Sebaliknya, jika semua kondisi bernilai False, maka hasilnya adalah False.
2.Sintaksis Penggunaan dasar operator OR dalam Python adalah sebagai berikut:

    if kondisi1 or kondisi2:
         # lakukan sesuatu

3.Contoh Penggunaan

a. Pemeriksaan Sederhana Misalnya, kita ingin mengecek apakah sebuah angka berada di luar rentang tertentu:

    angka = 7
      if angka < 5 or angka > 10:
           print("Angka tidak dalam rentang 5 hingga 10")
    else:
      print("Angka dalam rentang 5 hingga 10")

b. Kelayakan dalam Konteks Bisnis Dalam bisnis, kita mungkin perlu memverifikasi kelayakan berdasarkan beberapa syarat:

    gaji = 2500000
    memiliki_rumah = True

    if gaji > 5000000 or memiliki_rumah:
        print("Kelayakan pinjaman terverifikasi")
    else:
        print("Kelayakan pinjaman tidak terpenuhi")

Jika gaji lebih dari 5.000.000 atau pemohon memiliki rumah, mereka dianggap layak untuk pinjaman.

c. Logika dalam Pendidikan Dalam konteks pendidikan, kita dapat menggunakan OR untuk mengevaluasi nilai siswa:

    if a + b == c or b + c == a or c + a == b:
        print("BENAR")
    else:
         print("SALAH")

Program ini memeriksa apakah jumlah dua bilangan sama dengan bilangan ketiga. Jika salah satu kondisi terpenuhi, outputnya adalah "BENAR".

4.Keuntungan Menggunakan OR

Menyederhanakan Kode: Operator OR memungkinkan kita untuk menggabungkan beberapa kondisi dalam satu pernyataan, yang membuat kode lebih bersih dan mudah dibaca.

Fleksibilitas: Dengan menggunakan OR, kita bisa menetapkan kriteria yang lebih fleksibel untuk logika keputusan.

    a = int(input("Masukkan bilangan A: "))
    b = int(input("Masukkan bilangan B: "))
    c = int(input("Masukkan bilangan C: "))
    if a+b == c or b+c == a or c+a == b:
       print("BENAR")
    else:
        print("SALAH")
    
