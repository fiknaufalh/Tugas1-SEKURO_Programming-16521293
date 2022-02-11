# Rangkuman Video 6 [Git Branch & Merge]
### Oleh Fikri Naufal Hamdi (16521293) 
---
<p>&nbsp;</p>

## Cara membuat Branch:
1.	Siapkan setup terminal dan code editor yang digunakan
2.	Masukkan instruksi ```git branch``` untuk melihat apa saja branch yang ada di repository. Pointer ‘Head’ menunjukkan posisi branch yang aktif terkini.

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid6/git%20branch.png?raw=true)

3.	Masukkan instruksi ```git branch <nama_branch>``` untuk membuat branch yang baru

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid6/git%20branch%20nama_branch.png?raw=true)

4.	Untuk melihat perjalanan dari branch kita dengan graph, masukkan instruksi ```git log --all --decorate --oneline --graph```. 

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid6/git%20log%20graph.png?raw=true)

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid6/git%20log%20graph2.png?raw=true)

Jika ingin dipersingkat untuk keperluan ke depannya, kita dapat membuat aliasnya dengan memasukkan instruksi ```alias graph=”git log --all --decorate --oneline –graph”```

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid6/git%20log%20graph%20alias.png?raw=true)

5.	Untuk berpindah ke branch lain, masukkan instruksi ```git checkout <nama_branch>```. Lalu pointer ‘Head’ akan berpindah ke branch yang telah diinput.

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid6/git%20checkout%20(pindah%20branch).png?raw=true)

## Jenis Merge:
1.	Fast Forward : Terjadi ketika branch yang ingin kita gabungkan berada dalam jalur langsung atau direct path
2.	Three-way Merge Halo : Terjadi ketika branch yang ingin kita gabungkan tidak berada dalam jalur langsung/direct path

## Cara melakukan Merging:
1.	Pindahkan pointer atau posisi branch terkini ke branch master dengan memasukkan instruksi ```git branch master```

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid6/How%20to%20Merge/merge-step1.png?raw=true)

2.	Untuk melakukan merge, masukkan instruksi ```git merge <branch_yang_akan_dimerge>```

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid6/How%20to%20Merge/merge-step2.png?raw=true)

3.	Untuk melihat dan memastikan branch mana yang berhasil dimerge, masukkan instruksi ```git branch --merged```

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid6/How%20to%20Merge/merge-step3.png?raw=true)

4.	Setelah selesai merging, kita dapat menghapus branch yang sudah tidak digunakan. Caranya dengan memasukkan instruksi ```git branch -d <branch_yang_dihapus>```

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid6/How%20to%20Merge/merge-step4.png?raw=true)

5.	Jika branch yang belum dimerge ingin dihapus, masukkan instruksi ```git branch -D <branch_yang_akan_dihapus>``` (-D artinya menghapus apapun kondisinya, sudah dimerge atau belum)

![](https://github.com/fiknaufalh/Tugas1-SEKURO_Programming-16521293/blob/main/Pictures/Vid6/How%20to%20Merge/merge-step5.png?raw=true)
