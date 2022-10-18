Hallo, nama saya Dhea Dwi Adelia. Saya akan menjelaskan cara menggunakan Git, yang kita perlukan adalah aplikasi Git, dan akun Git. Sebelum itu kita harus menginstall aplikasi Git. Berikut tutorial penginstallan aplikasi Git.
###Tutorial penginstallan aplikasi Git
- Pertama, anda buka situs resminya di git-scm.com .
![Screenshot (17)](https://user-images.githubusercontent.com/115794875/196307674-ffdad09c-0d19-402d-9fa6-273234d85d80.png)
Download sesuai dengan bit (32 bit atau 64 bit) agar laptop anda support. Selesai download klik install.
- Lalu klik next simpan lokasi di C:\ProgramFiles\Git(disesuaikan), lalu di next sampai ke step install, tunggu sampai selesai.
![image](https://user-images.githubusercontent.com/115794875/196308523-5e75a8a3-3eee-4a70-8833-b0e109d6ae8f.png)
- Setelah melakukan penginstalan, buka git cmd untuk mengetahui apakah sudah bisa melakukan proses atau belum jika muncul git version berarti sudah siap melakukan proses. Untuk mengetahui versinya ketikan perintah git --version. Saya memakai versi 2.38.0.windows.1
![Screenshot (18)](https://user-images.githubusercontent.com/115794875/196309682-34ba4745-f521-4192-81ef-633bacd85922.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Cara membuat akun git
- Disini anda harus membuat akun git terlebih dahulu  untuk membuat repository server bukalah link tersebut http://github.com

![Screenshot (19)](https://user-images.githubusercontent.com/115794875/196310564-a1305abf-bf10-4357-9416-b5bee7777a98.png)

- Pada langka selanjutnya anda boleh langsung diskip saja.
   
  ### Membuat repositori baru

- Ini adalah tampilan pertama setelah kalian selesai membuat akun git

![Screenshot (13)](https://user-images.githubusercontent.com/115677959/195978469-53789f6c-4d88-4b94-ac44-77d8c05be1f0.png)

- Langkah selanjutnya nanti anda akan dialihkan ke tab baru untuk membuat repositori baru, isi susuai inspirasi anda setelah selesai klik buat repositori. 

 ![Screenshot (14)](https://user-images.githubusercontent.com/115677959/195978342-860c1ebf-98a0-470c-8586-272e72bfc79d.png)

-  Lalu nanti di tab baru ada url, url ini akan digunakan untuk remote GitHub.

  ![Screenshot (18)](https://user-images.githubusercontent.com/115677959/195978391-435ade62-7139-47d7-b50b-073c6c000bdb.png)

### Membuat Repository Local

- Lalu kita buka file explorer pilih dilocal disk (c) (atau dmana saja sesuai keinginan anda), lalu klik kanan pilih *Git Bash here* .
![Screenshot (20)](https://user-images.githubusercontent.com/115677959/195978607-35aa8e50-d7fd-4451-b5a6-754d887eb31f.png)


- Lalu kita akan menambahkan Config Global Repository  pakai user name dan user email yang tadi sudah dibuat, dengan perintah : 	
      *$ git config --global user.email “email_user”*
      *$ git config --global user.name “nama_user”*

  ![Screenshot (21)](https://user-images.githubusercontent.com/115677959/195978719-d22ef8c7-0654-47b5-bc06-0ef830e067d6.png)


- Buatlah direktori baru dengan menggunakan perintah " mkdir lab_pemrograman1 "  LALU *" cd lab_pemrograman1![Screenshot (22)](https://user-images.githubusercontent.com/115677959/195978992-de8cc7b2-e91a-45b7-9c71-d8c019d9b6c8.png)
 "*.

 ##### Cara penggunaan git dengan perintah daasar git init fungsi  perintahnya  untuk membuat repository local 

- Lalu jalankan perintah git init untuk membuat membuat file kosong berformat GIT. File ini fungsinya untuk menyimpan semua perubahan pada working directory dan file ini terbentuknya hidden.
 
   ![Screenshot (23)](https://user-images.githubusercontent.com/115677959/195979071-05dae59d-5418-4612-bf24-c4f39c767a11.png)


-  Lalu buat 1 file baru bernama README.md, dengan memasukan perintah _echo “#latihan1” >> README.md. Lalu untuk melihat file ketik perintah “ls 

    ![Screenshot (24)](https://user-images.githubusercontent.com/115677959/195979189-8f39f73d-dcea-4d35-982d-d84ddefad965.png)

 ##### Cara penggunaan git dengan perintah dasar git add  fungsi perintahnya untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit
- Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add. Dengan perintah $ git add README.md. Kalau ingin melihat infonya ketik perintah git status.
  ![Screenshot (26)](https://user-images.githubusercontent.com/115677959/195979269-80794fee-01bd-4fab-b200-a13256253af6.png)


- Untuk menyimpan perubahan yang ada kedalam database gunakan perintah git commit -m “komentar commit"
  ![67557721-cadd1e80-f73f-11e9-8f44-dc52f8676eb3](https://user-images.githubusercontent.com/115677959/195979372-25d6dfbd-f125-4b89-9d0a-d4d48f5efc75.png)

##### *File berhasil tersimpan*

-  Langkah berikutnya kita kembali ke website GitHub untuk melihat repositori yang sudah dibuat.
Nah di Quick Setup nanti ada url github kita, url tersebut untuk perintah_ “git remote add origin [url] “ DAN PERINTAH GIT CLONE “ git clone [ url ] “_

 ##### Cara penggunaan git dengan perintah dasar  git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)

- Sudah mengetahui url githubnya lalu ketik perintah git remote add origin [url],urlnya diganti dengan url github anda https://github.com/Hazelnuts22/Latihan_1.git
   ![Screenshot (8-)](https://user-images.githubusercontent.com/115677959/195979558-eb6c7913-ade9-4381-8584-d3ad396d119f.png)


 ##### Cara penggunaan git dengan perintah dasar git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository

- Untuk  mengirim perubahan pada local repository ke server gunakan perintah “git push -u origin master”. Ingat pada langkah ini kita harus memasukan usernam dan pasword gethub.
   ![git_push](https://user-images.githubusercontent.com/115677959/195979685-82932b67-cc7a-458a-beb6-4c6a4a12612a.png)

 ##### Cara penggunaan git dengan perintah dasar  git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.

- Kalau ingin melakukan cloning, gunakan perintah git clone [url], urlnya diganti dengan url github anda https://github.com/Hazelnuts22/Latihan_1.git . Jika ingin masuk kedirektorti gunakan perintah “cd [nama direktori anda]”, dan jika ingin melihat semua isi direektori gunakan perintah “ls -1"
  ![git_push](https://user-images.githubusercontent.com/115677959/195979779-f936d543-9d8c-49e7-8e8c-dcedaa119557.png)


-  Selesai Jika ingin melihat hasilnya cek di  laman gethub arahkan ke repositorinya
  
#### *FILE README.md tersebut masih kosong jikalau anda ingin mengisi kekosongan file tersebut silahkan klik saja icon pensil yang berada di kanan atas*.
### *Terimakasih*
