# LatihanVCS

Tugas pertemuan ke 4 Bahasa Pemrograman

Nama  : Bangkit Akbar Anggara

NIM   : 312010148

Kelas : TI.20.B.1

Prodi : Teknik Informatika

# Cara Menggunakan Git dan Github:

1.Install git terlebih dahulu(www.git-scm.com)

2.Setalah menginstall Git, Silahkan cek untuk melihat versi Git yang anda install dengan mengetik

![Screenshot (17)](https://user-images.githubusercontent.com/73011140/96491142-05eb3280-126c-11eb-8e9c-830ae94a4ffa.png)

    git version
  
3.Anda bisa melakukan login awal pada Git  menggunakan Command Prompt  (Windows)

![Screenshot (30)](https://user-images.githubusercontent.com/73011140/96490761-734a9380-126b-11eb-93ec-ffc0f93e506f.png)

4.Selanjutnya, masukkan username GitHub Anda menggunakan perintah di bawah ini. Lalu tekan ENTER jika sudah benar.

![Screenshot (18)](https://user-images.githubusercontent.com/73011140/96491257-303cf000-126c-11eb-81a0-290f589975d8.png)

    $ git config --global user.name "UsernameAnda"
  
6.Kemudian masukkan email yang terdaftar di GitHub Anda menggunakan perintah di bawah  ini. Lalu tekan ENTER jika sudah benar.

![Screenshot (19)](https://user-images.githubusercontent.com/73011140/96491382-5d899e00-126c-11eb-99b4-2bbad1f2b12f.png)
      
    $ git config --global user.email emailanda
  
7.Selanjutnya untuk memastikan proses login Anda berhasil, masukkan perintah berikut.

![Screenshot (19)](https://user-images.githubusercontent.com/73011140/96491464-7c883000-126c-11eb-8267-6c692909cb09.png)
       
    $ git config --list
  
8.Login ke Github

![Screenshot (20)](https://user-images.githubusercontent.com/73011140/96491541-96297780-126c-11eb-86e3-f09f98fbdba2.png)
  
9.Buat akun terlebih dahulu jika anda baru pertama kali menggunakan Github

![Screenshot (31)](https://user-images.githubusercontent.com/73011140/96492371-bd347900-126d-11eb-8bcf-971c457a871f.png)
  
10.Setelah berhasil login ke GitHub, Anda bisa mulai membuat repository. Klik tombol New pada menu Repositories untuk membuat repository baru.

![Screenshot (21)](https://user-images.githubusercontent.com/73011140/96492789-5b284380-126e-11eb-99f8-c2cc72ae2ebc.png)  

11.Selanjutnya, Anda perlu membuat folder pada local disk komputer Anda. Fungsinya adalah untuk menyimpan update file dari repository GitHub yang telah Anda buat.

![Screenshot (22)](https://user-images.githubusercontent.com/73011140/96492882-798e3f00-126e-11eb-9394-71dd7fc93679.png)
  
12.Setelah berhasil membuat folder pada local disk komputer Anda, buka folder tersebut dengan cara klik kanan lalu pilih Git Bash Here. Setelah itu, Command Prompt akan muncul seperti di bawah ini. 

![Screenshot (24)](https://user-images.githubusercontent.com/73011140/96492986-97f43a80-126e-11eb-95ba-5b359f011357.png)
  
13.Setelah itu, ubah folder tersebut menjadi repository menggunakan perintah berikut

![Screenshot (6)](https://user-images.githubusercontent.com/73011140/96493117-c70aac00-126e-11eb-95b7-ec774a4ad708.png)
       
    $ git init

14.Untuk bisa menambahkan file ke repository GitHub, Anda perlu menerapkan langkah-langkah di bawah ini

![Screenshot (23)](https://user-images.githubusercontent.com/73011140/96493299-01744900-126f-11eb-8e28-0d0fb707e2b7.png)
   
->Buat file di folder yang sudah dibuat (LatihanVCS). Contohnya, di sini kami membuat file README.md

15.Buka GitBash lalu masukkan perintah berikut

![Screenshot (25)](https://user-images.githubusercontent.com/73011140/96493433-341e4180-126f-11eb-9b18-0cd20f140e17.png)
      
    $ git add README.md
   
16.Lalu setelah itu ketik perintah berikut

![Screenshot (26)](https://user-images.githubusercontent.com/73011140/96493769-97a86f00-126f-11eb-8a1a-2129c2d8211e.png)

    $ git add .
    
17.Selanjutnya, Anda perlu membuat Commit. Commit berfungsi untuk menambahkan update file serta komentar. Jadi setiap kontributor bisa memberikan konfirmasi update file di proyek yang sedang dikerjakan. Masukkan perintah berikut untuk membuat Commit

![Screenshot (11)](https://user-images.githubusercontent.com/73011140/96493870-be66a580-126f-11eb-82f3-07c35e1c239c.png)
    
    $ git commit -m "first commit"
   
18.Setelah git commit, lalu anda masukan perintah git log

![Screenshot (29)](https://user-images.githubusercontent.com/73011140/96493959-dfc79180-126f-11eb-9305-73ff40b7d9b5.png)

        
    $ git log
     
19.Lakukan Remote repository berfungsi untuk mengupload file yang telah Anda buat sebelumnya di local disk. Masukkan perintah berikut ini untuk melakukan remote repository

![Screenshot (32)](https://user-images.githubusercontent.com/73011140/96494572-be1ada00-1270-11eb-8303-7250be1dcb14.png)
        
    $ git remote add origin https://github.com/AkbarXelion/LatihanVCS.git
   
20.Langkah terakhir adalah push ke GitHub Push ini berfungsi untuk mengupload hasil akhir dari langkah-langkah di atas. Masukkan perintah berikut untuk melakukan push ke GitHub

![Screenshot (11)](https://user-images.githubusercontent.com/73011140/96494723-f4585980-1270-11eb-9a2a-fb53b9f7be8c.png)
        
    $ git push -u origin main

->Perintah di atas akan menampilkan pop up sign in GitHub. Anda perlu login untuk melanjutkan proses push ke GitHub.
      
21.Selesai anda sudah berhasil menginstall git juga menggunakan git dan github

![Screenshot (12)](https://user-images.githubusercontent.com/73011140/96494849-1b169000-1271-11eb-8174-3fcfc8989cb4.png)
      
