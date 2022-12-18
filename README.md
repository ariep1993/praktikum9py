# Praktikum 9

# Nama : saripudin

# NIM : 312210077

# Kelas : TI. 22. B1

# Contoh dan Penjelasan Modul Praktikum 13

### 1. Berikut adalah fungsi yang mengubah suhu dari derajat derajat Kelvin menjadi derajat Fahrenheit. Karena nol derajat derajat Kelvin sedingin yang didapat, fungsi tersebut ditebus jika melihat suhu negatif.

![208232159-2b286b13-53a9-4d40-b83e-efa40f909c42](https://user-images.githubusercontent.com/115473865/208298934-5924779a-4175-41a9-9c8f-06e6ae29ff12.png)


Ketika kode di atas dijalankan, muncul Exception yang bernama Traceback... AssertionError artinya terjadi error pada pernyataan assert.

### 2. Contoh ini untuk membuka file, menulis konten di file dan keluar dengan lancar karena tidak ada masalah sama sekali.
prak 9

![208232774-4146e137-d051-47c8-8432-8e1f8936e12a](https://user-images.githubusercontent.com/115473865/208299004-96c54e91-a191-4d28-89bb-141fc2839f51.png)

hasil:
Written content in the file successfully

### 3. Contoh ini mencoba membuka file di mana Anda tidak memiliki izin menulis, sehingga menimbulkan pengecualian.

![208233322-41ef7a58-a485-4632-99a5-29a10950fae6](https://user-images.githubusercontent.com/115473865/208299244-d0ce92a4-5f97-4a80-bddf-ea87be7f0d6c.png)

Mengapa hasilnya error?
r adalah read - Membuka file untuk membaca, akan error jika file tidak ada. Disini ingin membaca file bukan menulis maka dibawahnya fh = open("testfile", "r") tambahkan print(fh.readline()) dan fh.write dihapus. Setelah dijalankan, try dan else ditampilkan.
### 4. Contoh keempat

![208242848-5e8f3f5d-5a07-4bb7-81c2-c211f3c23da0](https://user-images.githubusercontent.com/115473865/208299309-b398b591-5a8a-4cde-996d-5712775cf164.png)


Hasil diatas bukan error, karena finally dijalankan ketika try dan except dijalankan. Dan berhasil dibuat filenya setelah dijalankan.
### 5. Contoh single exception

![208243105-f48bd09a-f68c-4cda-ad11-64b3b7b4950b](https://user-images.githubusercontent.com/115473865/208299339-863949ec-4c3c-4991-bb8f-e2701d369209.png)


Hasilnya :
The argument does not contain numbers 
invalid literal for int() with base 10: 'xyz'
ketika dijalankan, maka muncul error. Hapus #!/usr/bin/python dan di except ValueError, Argument: ganti koma dengan as seperti except ValueError as Argument:agar tidak error. Jika dijalankan akan muncul error lagi. Kenapa? karena parameter def temp_convert harus mengandung angka.
### 6. Contoh dan penjelasan keenam

![208243725-a8418191-cedb-436b-8719-2c4d27a95c3a](https://user-images.githubusercontent.com/115473865/208299369-18d95bd0-a267-4ae3-acc3-b1f266afcec8.png)

Jika dijalankan muncul SyntaxError artinya ada kesalahan sintaks. Pada raise "Invalid level!", level ganti tanda koma dengan tanda plus. Cetak def dengan angka yang lebih besar dari 1.

### Selesai
