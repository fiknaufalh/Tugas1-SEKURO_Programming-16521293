# Rangkuman Video 3 [Github : Branch]
### Oleh Fikri Naufal Hamdi (16521293) 
---
<p>&nbsp;</p>

## Apa itu Branch?
-	Branch adalah jalur ‘development’ bebas dari sebuah commit

## Istilah yang perlu diketahui
-	Checkout adalah berpindah ke branch atau commit yang lain
-	Pull Request adalah meminta pemilik repository untuk ‘mengambil’ perubahan yang telah dilakukan
-	Merge adalah proses menggabungkan 2 branch
-	Merge Conflict adalah kondisi saat terdapat baris yang sama diubah oleh 2 branch yang berbeda

## Apa itu Branching?
-	Branching adalah proses membuat Git Branch atau membuat snapshot tanpa mengganggu jalur utama (Master branch)

## Manfaat Branching
-	Membuat perubahan tanpa mengganggu jalur utama atau master branch
-	Membuat fitur eksperimental secara bebas
-	Melakukan pengerjaan project bersama (2+ orang) pada repository yang sama

## Cara membuat Branch di Github
-	Cara pertama
1.	Pilih file yang akan diedit
2.	Klik edit berlogo pensil di pojok kanan atas bagian file
3.	Edit isi file sesuai keinginan
4.	Jika sudah, isikan pesan commit yang sesuai
5.	Jika ingin memberikan deskripsi yang lebih detail, isikan pada kolom di bawahnya
6.	Klik ‘Create a new branch for this commit and start a pull request’
-	Cara kedua
1.	Buka halaman repository yang ingin dibuat Branchnya berada
2.	Klik ‘Branch: master’ (master adalah branch utama)
3.	Ketik nama branch yang ingin dibuat
4.	Klik ‘Create branch: <nama_branch>’ 

## Cara melakukan Merging di Github
1.	Buka branch yang ingin dimerge ke branch utama
2.	Klik ‘Compare & pull request’ dan akan masuk ke halaman ‘Open a pull request’
3.	Jika terdapat keterangan ‘Can’t automatically merge’, artinya terdapat perbedaan perubahan atau perubahan yang tumpeng tindih pada isi branch. Tetap bisa dilakukan pull request, tetapi perlu dilakukan ‘Resolve conflicts’ ketika akan merging, yaitu menyelesaikan perbedaan yang ada pada code editor yang diarahkan oleh github. Jika sudah, klik ‘Mark as resolved’. 
4.	Jika terdapat keterangan ‘Able to merge’, artinya branch tersebut aman untuk dimerge
5.	Masukkan pesan pull request pada kolom pesan
6.	Klik ‘Create pull request’ dan akan masuk ke tab Pull requests
7.	Jika sudah merasa yakin dan aman dengan perubahannya, klik ‘Merge pull request’
8.	Masukkan pesan sebagai feedback atas pull request (dalam hal ini pesan terkirim kepada kita sendiri sebagai pengirim pull request) jika merasa perlu.
9.	Klik ‘Confirm merge’

## Cara menghapus Branch yang tidak diperlukan
1.	Buka halaman repository tempat branch berada
2.	Buka bagian ‘branches’
3.	Klik tombol delete branch berupa tempat sampah berwarna merah