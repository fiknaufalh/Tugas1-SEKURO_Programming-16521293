# Rangkuman Video 6 [Git Branch & Merge]
### Oleh Fikri Naufal Hamdi (16521293) 
---
<p>&nbsp;</p>

## Cara membuat Branch:
1.	Siapkan setup terminal dan code editor yang digunakan
2.	Masukkan instruksi ```git branch``` untuk melihat apa saja branch yang ada di repository. Pointer ‘Head’ menunjukkan posisi branch yang aktif terkini.
3.	Masukkan instruksi ```git branch <nama_branch>``` untuk membuat branch yang baru
4.	Untuk melihat perjalanan dari branch kita dengan graph, masukkan instruksi ```git log --all --decorate --oneline --graph```. Jika ingin dipersingkat untuk keperluan ke depannya, kita dapat membuat aliasnya dengan memasukkan instruksi ```alias graph=”git log --all --decorate --oneline –graph”```
5.	Untuk berpindah ke branch lain, masukkan instruksi ```git checkout <nama_branch>```. Lalu pointer ‘Head’ akan berpindah ke branch yang telah diinput.

## Jenis Merge:
1.	Fast Forward : Terjadi ketika branch yang ingin kita gabungkan berada dalam jalur langsung atau direct path
2.	Three-way Merge Halo : Terjadi ketika branch yang ingin kita gabungkan tidak berada dalam jalur langsung/direct path

## Cara melakukan Merging:
1.	Pindahkan pointer atau posisi branch terkini ke branch master dengan memasukkan instruksi ```git branch master```
2.	Untuk melakukan merge, masukkan instruksi ```git merge <branch_yang_akan_dimerge>```
3.	Untuk melihat dan memastikan branch mana yang berhasil dimerge, masukkan instruksi ```git branch --merged```
4.	Setelah selesai merging, kita dapat menghapus branch yang sudah tidak digunakan. Caranya dengan memasukkan instruksi ```git branch -d <branch_yang_dihapus>```
5.	Jika branch yang belum dimerge ingin dihapus, masukkan instruksi ```git branch -D <branch_yang_akan_dihapus>``` (-D artinya menghapus apapun kondisinya, sudah dimerge atau belum)