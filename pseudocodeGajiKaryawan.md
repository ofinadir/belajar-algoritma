# PROGRAM GajiKaryawan
*(Program menghitung gaji bersih karyawan. Data masukan yaitu NIP, nama karyawan dan gaji pokok bulanannya.
 Gaji bersih = gaji pokok + tunjangan - pajak. Tunjangan adalah 25% dari gaji pokok, dan pajak adalah 10% dari gaji pokok dan tunjangan.
 Output dari program yaitu NIP, nama karyawan dan gaji bersih.)*
 
### DEKLARASI

>**const** persenTunjangan = 0.25 {persenan tunjangan gaji}

>**const** persenPajak = 0.1 {persenan potongan pajak}

>namaKaryawan : **string**

>NIP : **integer**

>gajiPokok, tunjangan, pajak, gajiBersih : **real**

### ALGORITMA

>**read**(NIP, namaKaryawan, gajiPokok)

>tunjangan <- persenTunjangan * gajiPokok

>pajak <- persenPajak * (gajiPokok + Tunjangan)

>gajiBersih <- gajiPokok + tunjangan - pajak

>**write** (NIP, namaKaryawan, gajiBersih)
