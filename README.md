# BIODATA
# NAMA: AGUNG HERLAMBANG
# NIM: 312410296
# KELAS: TI.4.A4
## TUGAS 1

### MEMBUAT PROGRAM MENENTUKAN NILAI AKHIR

### DESKRIPSI

Program ini dirancang untuk menghitung nilai akhir mahasiswa berdasarkan beberapa komponen penilaian, seperti nilai UTS (Ujian Tengah Semester), UAS (Ujian Akhir Semester), dan tugas. Program akan menampilkan nilai akhir dan memberikan keterangan mengenai status kelulusan.

 20% untuk nilai tugas

 40% untuk nilai UTS

 40% untuk nilai UAS

### PENJELASAN PROGRAM

 # Contoh dalam Markdown
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
