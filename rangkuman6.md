# Rangkuman Video 6 - Git Branch & Merge

<p>&nbsp;</p>

## Nama/NIM:
### 16521066 - Hanif Muhammad Zhafran

<p>&nbsp;</p>

## Video 6 - Git Branch & Merge
Commit memiliki hash uniknya masing. Commit juga selalu terhubung ke sebuah branch (defaultnya adalah branch master). Kemudian head menunjukkan kita sedang ada di branch mana. 

Untuk membuat branch baru syntaxnya adalah: 

git branch <nama_branch>

![](https://cdn.discordapp.com/attachments/941701680100151326/941704288676249620/unknown.png)

Setelah itu, untuk melihat branch apa saja yang terdapat dalam repo, bisa ketik git branch

![](https://cdn.discordapp.com/attachments/941701680100151326/941707169038999582/unknown.png)

Berikut cara untuk membuat visualisasi branch dalam git. Alias digunakan untuk mempermudah dalam pemanggilan visualisasi.

![](https://cdn.discordapp.com/attachments/941701680100151326/941707512233738280/unknown.png)

Untuk pindah ke branch lain, bisa menggunakan git checkout <nama_branch>. Berikut contoh dalam mengedit file dalam branch masing-masing.

![](https://cdn.discordapp.com/attachments/941701680100151326/941707601601789983/unknown.png)

![](https://cdn.discordapp.com/attachments/941701680100151326/941707675803189288/unknown.png)

Cara merge branch dengan master branch dapat menggunakan git merge <nama_branch> saat berada di master branch.

Merge ada 2 jenis, yaitu ada Fast Forward dan Three-Way Merge. Fast Forward merge terjadi ketika 2 branch yang akan di merge terhubung secara langsung. Sementara Three-Way merge terjadi ketika 2 branch yang akan di-merge tidak terhubung secara langsung.

Berikut contoh Fast Forward merge:
![](https://cdn.discordapp.com/attachments/941701680100151326/941707675803189288/unknown.png)

Contoh Three-Way merge:
![](https://cdn.discordapp.com/attachments/941701680100151326/941707838068256768/unknown.png)