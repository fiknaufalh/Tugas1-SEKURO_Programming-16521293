# Rangkuman Video 5 [Bekerja dengan Git]
### Oleh Fikri Naufal Hamdi (16521293) 
---
<p>&nbsp;</p>

## Cara menginstall Git
1.	Buka browser
2.	Buka halaman https://git-scm.com
3.	Klik ‘Download <version> for <operating system>’
4.	Open file installer berformat exe
5.	Ikuti instruksi penginstalan, secara default akan terinstall Git Bash, yaitu software tempat kita dapat menjalankan perintah Git.
6.	Klik ‘Finish’

## Perintah di Gitbash:
-	```git``` : menampilkan macam-macam command yang bisa digunakan

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/git.png?raw=true)

-	```pwd``` (print working directory) : menampilkan lokasi directory yang sedang digunakan

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/pwd.png?raw=true)

-	```clear``` : untuk membersihkan tampilan terminal

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/clear1.png?raw=true)

  Setelah di enter:
  
![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/clear2.png?raw=true)

-	```ls``` : untuk mengetahui apa saja file dan folder yang terdapat di dalam folder/directory terkini

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/ls.png?raw=true)

-	```cd <nama_folder>``` : untuk masuk ke directory folder yang diinput

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/cd.png?raw=true)

-	```git --version``` : untuk mengetahui versi git yang terinstall di local computer

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/git%20--version.png?raw=true)

-	```git init``` : untuk menginisialisasi git repository di local computer

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/init.png?raw=true)

-	```git add <file(s)>``` : untuk menambahkan file ke staging area

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/git%20add.png?raw=true)

-	```git add .``` : untuk menambahkan semua perubahan ke staging area

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/git%20add%20(.).png?raw=true)

-	```git status``` : untuk mengetahui status repository kita terkini (apakah ada file baru, file yang berubah, file yang hilang, dll)

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/git%20status.png?raw=true)

-	```git config --global user.name “<username>”``` : Untuk mengkonfigurasi git dengan nama pengguna
-	```git config --global user.email “<email>”``` : Untuk mengkonfigurasi git dengan email pengguna

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/git%20config%20--global%20username%20dan%20email.png?raw=true)


-	```git config user.name``` : Untuk melihat konfigurasi nama pengguna

-	```git config user.email``` : Untuk melihat konfigurasi email pengguna

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/git%20config%20username%20dan%20email.png?raw=true)

-	```git commit``` : untuk melakukan commit

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/git%20commit%20-m.png?raw=true)

-	```git log``` : untuk melihat apa saja yang sudah dilakukan

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/git%20log.png?raw=true)

-	```git checkout <5_digit_pertama_commit_hash> -- <file/folder>``` : untuk kembali ke kondisi commit yang pernah dilakukan (bisa mengembalikan file/folder yang pernah didelete dan dicommit selama keberadaan file sudah pernah dicommit)

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/git%20checkout.png?raw=true)

-	```git branch``` : untuk membuat branch

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid6/git%20branch%20nama_branch.png?raw=true)

-	```git help``` : untuk mengetahui cara menggunakan suatu perintah

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/git%20help.png?raw=true)

## Tiga area pada repository Git:
1.	Working tree : folder tempat bekerja
2.	Staging area : tempat penyimpanan perubahan sementara sebelum di-commit (tersimpan di folder .git)
3.	History : penyimpanan riwayat perubahan file atau folder yang sudah di-commit pada repository (tersimpan di folder .git)

## Workflow menggunakan Git untuk pertama kali:
1.	Buka folder directory yang diinginkan di Terminal atau Git Bash

2.	Ketikkan instruksi ```git init``` untuk menginisialisasi sebuah folder biasa menjadi repository

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/init.png?raw=true)

3.	Ketikkan instruksi ```git status``` untuk melihat status repository yang baru kita buat (file dan/atau folder apa saja yang belum ‘terdaftar’ di Git)

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/git%20status.png?raw=true)

4.	Jika ada file/folder yang belum ‘terdaftar’, file/folder tersebut tidak dapat di-commit. Untuk mendaftarkan atau menyimpan file/folder ke staging area, masukkan instruksi ```git add <file>```. Untuk menyimpan file ke staging area sekaligus, masukkan instruksi ```git add .```

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/git%20add.png?raw=true)

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/git%20add%20(.).png?raw=true)

5.	Untuk melihat apakah file/folder sudah tersimpan di git, masukkan kembali instruksi ```git status```

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/git%20add%20(.).png?raw=true)

6.	Jika ingin mengeluarkan kembali file dari staging area, masukkan instruksi ```git rm –cached <file>```

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/git%20rm.png?raw=true)

7.	Untuk melanjutkan ke proses commit, kita harus mengkonfigurasi username dan email pada git jika sebelumnya belum pernah terkonfigurasi.

8.	Untuk mengkonfigurasi username dan email, masukkan instruksi ```git config --global user.name “<username>”``` dan ```git config --global user.email “<email>```. Username dan email yang dimasukkan merupakan username dan email yang tertaut di akun Github

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/git%20config%20--global%20username%20dan%20email.png?raw=true)


9.	Selanjutnya, untuk melakukan commit suatu perubahan yang telah dilakukan, masukkan instruksi ```git commit``` dan akan otomatis masuk ke code editor default untuk memasukkan pesan commit (cara ini jika ingin memasukkan pesan commit yang panjang). 

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/git%20commit.png?raw=true)

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/git%20commit2.png?raw=true)

Namun, jika pesan commit tidak panjang, cukup masukkan instruksi ```git commit -m “<pesan_commit_singkat>”```.

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/git%20commit%20-m.png?raw=true)

10.	Untuk melihat status perubahan setelah dicommit, masukkan instruksi ```git status```

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/git%20status%20akhir.png?raw=true)

11.	Untuk melihat apa saja yang sudah dilakukan, masukkan instruksi ```git log```.

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/git%20log.png?raw=true)

 Masukkan instruksi ```git log -<berapa commit terakhir yang ingin dilihat>``` untuk melihat log perubahan sejumlah yang diinginkan dan ```git log -- <file/folder>``` untuk melihat log perubahan dari suatu file/folder secara spesifik.

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/git%20log%20-1.png?raw=true)

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/git%20log%20--%20file.png?raw=true)

12.	Jika terdapat file yang sudah terhapus dan dicommit tetapi memerlukan file itu kembali, kita dapat mengembalikan file dengan memasukkan instruksi ```git checkout <5 digit pertama commit hash> -- <file>``` selama keberadaan file sudah pernah dicommit

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid5/git%20checkout.png?raw=true)

13.	Selesai. Jika melakukan perubahan lagi, add lagi file/folder yang berubah ke dalam staging area dan lakukan commit agar perubahan dapat tercatat di history.
