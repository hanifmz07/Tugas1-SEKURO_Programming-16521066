# Rangkuman Video 3 - GitHub: Branch

<p>&nbsp;</p>

## Nama/NIM:
### 16521066 - Hanif Muhammad Zhafran

<p>&nbsp;</p>

## Video 3 - GitHub: Branch
Branch merupakan cabang commit yang dibuat ketika ingin mengembangkan suatu projek/source code tanpa mengganggu jalur utama (Master branch).

Berikut fungsi-fungsi dari branching:
1. Membuat Git Branch
2. Membuat snapshot tanpa mengganggu jalur utama (Master branch)
3. Untuk mengembangkan fitur experimental
4. 2 orang mengerjakan repo yang sama

Cara membuat branch baru langkahnya adalah sebagai berikut:
1. Tekan tombol branch pada menu code di repo kalian.
2. Isi dengan nama branch yang belum pernah ada sebelumnya, kemudian klik create branch

Branch yang telah dibuat dapat digunakan untuk menyimpan/membuat file-file baru. File-file baru tersebut tidak akan mempengaruhi branch master.

Cara menggabungkan lagi branch ke dalam master branch adalah dengan cara merge. Langkahnya adalah sebagai berikut:
1. Pada menu code, terdapat tombol 'Compare & pull request'. Klik tombol tersebut.
2. Terdapat branch 'base' dan 'compare', base merupakan branch patokan yang akan di merge, compare merupakan branch yang akan di-merge-kan. Tentukan branch base dan branch compare.
3. Isi deskripsi dari pull request dan tambahkan comment untuk menambah keterangan.
4. Klik tombol pull request.
5. Pada menu pull request, akan muncul pull request baru. Jika branch tidak ada konflik dengan branch utama, klik 'Merge pull request', kemudian bisa tambahkan deskripsi merge dan membalas comment kepada yang melakukan pull request (pada kasus ini, kepada diri kita sendiri).
6. Klik 'Confirm merge' jika sudah yakin.

Jika terdapat konflik antara branch yang baru dengan branch yang utama, orang yang ditujukan pull request harus menyelesaikan konflik ini secara manual (mengedit file dalam branch yang dibandingkan)