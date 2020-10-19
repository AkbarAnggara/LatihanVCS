# LatihanVCS

Tugas pertemuan ke 4 Bahasa Pemrograman

Nama  : Bangkit Akbar Anggara

NIM   : 312010148

Kelas : TI.20.B.1

Prodi : Teknik Informatika

# Cara Menggunakan Git dan Github:

1.Install git terlebih dahulu(www.git-scm.com)
  
2.Setelah download klik next saja terus lalu pilih install
  
3.Setelah selesai install git, login ke github
  
4.Anda bisa melakukan login awal pada Git  menggunakan Command Prompt  (Windows) atau Command Line (Linux)
![Screenshot (1)](https://user-images.githubusercontent.com/73011140/96333957-51001c80-1097-11eb-8a2b-5457e397af4f.png)
  
5.Selanjutnya, masukkan username GitHub Anda menggunakan perintah di bawah ini. Lalu tekan ENTER jika sudah benar.

  $ git config --global user.name "UsernameAnda"
  
6.Kemudian masukkan email yang terdaftar di GitHub Anda menggunakan perintah di bawah  ini. Lalu tekan ENTER jika sudah benar.
       
  $ git config --global user.email emailanda
  
7.Selanjutnya untuk memastikan proses login Anda berhasil, masukkan perintah berikut.
       
  $ git config --list
  
8.Login ke Github
![Screenshot (13)](https://user-images.githubusercontent.com/73011140/96335044-90326b80-109f-11eb-9755-a58c0f12bdfc.png)
  
9.Buat akun terlebih dahulu
  
10.Setelah berhasil login ke GitHub, Anda bisa mulai membuat repository. Klik tombol New pada menu Repositories untuk membuat repository baru.
![Screenshot (3)](https://user-images.githubusercontent.com/73011140/96334112-78a3b480-1098-11eb-9de0-5cc74f101cc7.png)
  
11.Selanjutnya, Anda perlu membuat folder pada local disk komputer Anda. Fungsinya adalah untuk menyimpan update file dari repository GitHub yang telah Anda buat.
![Screenshot (4)](https://user-images.githubusercontent.com/73011140/96334135-9c66fa80-1098-11eb-940e-1903c0abb2be.png)
  
12.Setelah berhasil membuat folder pada local disk komputer Anda, buka folder tersebut dengan cara klik kanan lalu pilih Git Bash Here. Setelah itu, Command Prompt akan muncul seperti di bawah ini. 
![Screenshot (5)](https://user-images.githubusercontent.com/73011140/96334171-dc2de200-1098-11eb-8f65-a904d254f5c5.png)
  
13.Setelah itu, ubah folder tersebut menjadi repository menggunakan perintah berikut
![Screenshot (6)](https://user-images.githubusercontent.com/73011140/96334206-2f079980-1099-11eb-953b-e5820a9841fd.png)
       
  $ git init

14.Untuk bisa menambahkan file ke repository GitHub, Anda perlu menerapkan langkah-langkah di bawah ini
![Screenshot (7)](https://user-images.githubusercontent.com/73011140/96334272-ad643b80-1099-11eb-9e96-7de04820e9ae.png)
   
->Buat file di folder yang sudah dibuat (LatihanVCS). Contohnya, di sini kami membuat file index.txt(ubah ke README.txt)
->Buka GitBash lalu masukkan perintah berikut:
      
  $ git add README.txt
   
15.Lalu setelah get init ketik seperti gambar di bawah ini
![Screenshot (9)](https://user-images.githubusercontent.com/73011140/96334535-beae4780-109b-11eb-924f-6f4f4e0cfb60.png)
       
  $ git status
  
16.Selanjutnya, Anda perlu membuat Commit. Commit berfungsi untuk menambahkan update file serta komentar. Jadi setiap kontributor bisa memberikan konfirmasi update file di proyek yang sedang dikerjakan. Masukkan perintah berikut untuk membuat Commit
    
  $ git commit -m "first commit"
   
17.Setelah git commit, lalu anda masukan git log
![Screenshot (10)](https://user-images.githubusercontent.com/73011140/96334624-5ca21200-109c-11eb-8f84-d24eb96a9d36.png)
        
  $ git log
     
18.Lakukan Remote repository berfungsi untuk mengupload file yang telah Anda buat sebelumnya di local disk. Masukkan perintah berikut ini untuk melakukan remote repository
        
  $ git remote add origin https://github.com/AkbarXelion/LatihanVCS.git
   
19.Langkah terakhir adalah push ke GitHub Push ini berfungsi untuk mengupload hasil akhir dari langkah-langkah di atas. Masukkan perintah berikut untuk melakukan push ke GitHub
![Screenshot (11)](https://user-images.githubusercontent.com/73011140/96334627-61ff5c80-109c-11eb-9bf3-d2cf4efc7ce5.png)
        
  $ git push -u origin main

->Perintah di atas akan menampilkan pop up sign in GitHub. Anda perlu login untuk melanjutkan proses push ke GitHub.
      
20.Selesai anda sudah berhasil menginstall git dan menggunakan git dan github
![Screenshot (12)](https://user-images.githubusercontent.com/73011140/96334776-6415eb00-109d-11eb-87a1-85436eda6d79.png)
      
