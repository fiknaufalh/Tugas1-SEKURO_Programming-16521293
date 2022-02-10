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

-	```pwd``` (print working directory) : menampilkan lokasi directory yang sedang digunakan
-	```clear``` : untuk membersihkan tampilan terminal

-	```ls``` : untuk mengetahui apa saja file dan folder yang terdapat di dalam folder/directory terkini

-	```cd <nama_folder>``` : untuk masuk ke directory folder yang diinput

-	```git --version``` : untuk mengetahui versi git yang terinstall di local computer

-	```git init``` : untuk menginisialisasi git repository di local computer

-	```git add <file(s)>``` : untuk menambahkan file ke staging area

-	```git status``` : untuk mengetahui status repository kita terkini (apakah ada file baru, file yang berubah, file yang hilang, dll)

-	```git config --global user.name “<username>”``` : Untuk mengkonfigurasi git dengan nama pengguna

-	```git config --global user.email “<email>”``` : Untuk mengkonfigurasi git dengan email pengguna

-	```git config user.name``` : Untuk melihat konfigurasi nama pengguna

-	```git config user.email``` : Untuk melihat konfigurasi email pengguna

-	```git commit``` : untuk melakukan commit

-	```git log``` : untuk melihat apa saja yang sudah dilakukan

-	```git checkout <5_digit_pertama_commit_hash> -- <file/folder>``` : untuk kembali ke kondisi commit yang pernah dilakukan (bisa mengembalikan file/folder yang pernah didelete dan dicommit selama keberadaan file sudah pernah dicommit)

-	```git config``` : untuk memasukkan konfigurasi ke dalam git

-	```git branch``` : untuk membuat branch

-	```git help``` : untuk mengetahui cara menggunakan suatu perintah

## Tiga area pada repository Git:
1.	Working tree : folder tempat bekerja
2.	Staging area : tempat penyimpanan perubahan sementara sebelum di-commit (tersimpan di folder .git)
3.	History : penyimpanan riwayat perubahan file atau folder yang sudah di-commit pada repository (tersimpan di folder .git)

## Workflow menggunakan Git untuk pertama kali:
1.	Buka folder directory yang diinginkan di Terminal atau Git Bash

2.	Ketikkan instruksi ```git init``` untuk menginisialisasi sebuah folder biasa menjadi repository

3.	Ketikkan instruksi ```git status``` untuk melihat status repository yang baru kita buat (file dan/atau folder apa saja yang belum ‘terdaftar’ di Git)

4.	Jika ada file/folder yang belum ‘terdaftar’, file/folder tersebut tidak dapat di-commit. Untuk mendaftarkan atau menyimpan file/folder ke staging area, masukkan instruksi ```git add <file>```. Untuk menyimpan file ke staging area sekaligus, masukkan instruksi ```git add```

5.	Untuk melihat apakah file/folder sudah tersimpan di git, masukkan kembali instruksi ```git status```

6.	Jika ingin mengeluarkan kembali file dari staging area, masukkan instruksi ```git rm –cached <file>```

7.	Untuk melanjutkan ke proses commit, kita harus mengkonfigurasi username dan email pada git jika sebelumnya belum pernah terkonfigurasi.

8.	Untuk mengkonfigurasi username dan email, masukkan instruksi ```git config --global user.name “<username>”``` dan ```git config --global user.email “<email>```. Username dan email yang dimasukkan merupakan username dan email yang tertaut di akun Github

9.	Selanjutnya, untuk melakukan commit suatu perubahan yang telah dilakukan, masukkan instruksi ```git commit``` dan akan otomatis masuk ke code editor default untuk memasukkan pesan commit (cara ini jika ingin memasukkan pesan commit yang panjang). Namun, jika pesan commit tidak panjang, cukup masukkan instruksi ```git commit -m “<pesan_commit_singkat>”```.

10.	Untuk melihat status perubahan setelah dicommit, masukkan instruksi ```git status```

11.	Untuk melihat apa saja yang sudah dilakukan, masukkan instruksi ```git log```. Masukkan instruksi ```git log -<berapa commit terakhir yang ingin dilihat>``` untuk melihat log perubahan sejumlah yang diinginkan dan ```git log -- <file/folder>``` untuk melihat log perubahan dari suatu file/folder secara spesifik.

12.	Jika terdapat file yang sudah terhapus dan dicommit tetapi memerlukan file itu kembali, kita dapat mengembalikan file dengan memasukkan instruksi ```git checkout <5 digit pertama commit hash> -- <file>``` selama keberadaan file sudah pernah dicommit

13.	Selesai. Jika melakukan perubahan lagi, add lagi file/folder yang berubah ke dalam staging area dan lakukan commit agar perubahan dapat tercatat di history.