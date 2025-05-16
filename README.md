### Golang Installation

- Buka https://go.dev/dl/ 
- Download sesuai dengan sistem operasi
- Lakukan step instalasi nya
- Cek apakah golang sudah terinstall dengan benar : go version


### Cara buat project golang

- Buat folder misalnya belajar-golang-dasar
- Jalankan perintah ini di terminal : 
- mkdir belajar-golang-dasar
- cd belajar-golang-dasar
- go mod init belajar-golang-dasar
- Biasanya nama module nya disamain dengan nama folder nya

### Main Function

- Go-lang mirip dengan C/C++ , perlu main function
- Titik koma di Golang gak wajib
- Main function harus terdapat di dalam main package
- buat function, pakai kata kunci func
- golang sensitif huruf besar ataupun kecil

### Println

- Untuk menulis tulisan, perlu import module fmt terlebih dahulu

### Kompilasi File Go-lang

- Kalau mau compile: go build
- Nanti akan di buat nama file sesuai dengan nama module nya
- step nya : 
- go build
- ./nama-module -> ini berlaku di mac/linux. Kalau windows jalankan nama-module saja

### Jalankan aplikasi tanpa kompilasi

- Kalau mau cepat, jalanin aplikasi golang nya pakai perintah: go run nama-file


### Multiple Main Function

- Di Golang, function dalam module / project itu unik, jadi gak boleh buat nama function yang sama

### Tipe Data Number

- Ada dua jenis tipe data Number: Integer & Floating point
- Integer : int8, int16, int32, int64
- Pakai yang sesuai kebutuhan saja, kalau pakai int64 jadi makin banyak memori yang terpakai padahal mungkin saja yang diperlukan gak sampai segitu
- uint8, uint16, uint32, uint64. Tipe data ini nilai minimum nya 0. Yang int tadi nilai minimum nya negatif.
- Floating Point : float32, float64, complex64, complex128.

### Alias

| Tipe data        | Alias untuk |
| ---------------- | -----      :|
| byte             | uint8       |
| rune             | int32       |
| int              | minimal int32 |
| uint             | minimal uint32 |
