## Developer
### 16521015 - Dimas Ridhwana Shalsareza
### Divisi  Programming

<p>&nbsp;</p>

# Rangkuman Video 5 (#5 GitHub : Bekerja Dengan Git)
buku panduan Git dapat diakses pada https://git-scm.com/book/en/v2

## Instalasi git
1. Download git dari https://git-scm.com
2. Tunggu hingga download selesai
3. Bereskan instalasi

<p>&nbsp;</p>

## Komponen pada Git 
1. $ git init
2. $ git add <file>
3. $ git status
4. $ git commit
5. $ git config
6. $ git branch
7. $ git help

<p>&nbsp;</p>
  
## Area
Setelah instalasi, komputer akan mengenali 3 area
1. Working tree : Folder tempat bekerja
2. Staging area : Memberitahu git kalau kita sudah melakukan perubahan -> akan tersimpan dalam folder .git
3. History : setelah di commit akan masuk ke History -> akan tersimpan dalam folder .git
 
<p>&nbsp;</p>
  
## Step by Step
1. Buat file yang akan dijadikan repository
2. Klik kanan dan buka Git Bash
3. Masukkan command  
  ```
  $ git init
  ```
  (File tersebut sudah berhasil diubah menjadi repository)

<p>&nbsp;</p>
  
## Latihan
1. Buat contoh file index.html
2. Masukkan file tersebut kedalam staging area dengan
  ```
  $ git add index.html
  ```
  maka ketika ditampilkan status akan muncul seperti ini
  ![Screenshot (216)](https://user-images.githubusercontent.com/88782280/153630692-151c8793-ff03-4ca7-ac9e-c0f4e33d9b28.png)
  <p>&nbsp;</p>
  
3. Sebelum melakukan commit, lakukan configurasi identitas terlebih dahulu dengan
  ```
  $ git config --global user.name "DimasRidhwana"
  $ git config --global user.email "16521015@mahasiswa.itb.ac.id"
  ```
  ![Screenshot (218)](https://user-images.githubusercontent.com/88782280/153630798-24b41323-ce17-4e4f-847e-2518efc57982.png)
<p>&nbsp;</p>

4. Commit file tersebut dengan
  ```
  $ git commit -m "Menambahkan file index"
  ```
  maka akan menampilkan tampilan seperti ini
  
  ![Screenshot (219)](https://user-images.githubusercontent.com/88782280/153630958-0a68ae17-4731-4cc4-aa97-494aae30d72d.png)
<p>&nbsp;</p>

5. Buat file style.css lalu isi dengan mengganti font pada index.html
  ketika run $ git status maka akan ada tampilan seperti berikut
  ![Screenshot (220)](https://user-images.githubusercontent.com/88782280/153631062-f7a43a65-2353-4b98-aad6-7a65e65f357b.png)
<p>&nbsp;</p>
  
6. Gunakan 
  ```
  $ git add .
  ```
  untuk memasukan semua file yang ada pada folder kedalam area stagging. Setelah itu lakukan Commit seperti pada step sebelumnya
  
7. Untuk melihat perubahan yang sudah kita lakukan gunakan
  ```
  $ git log
  ```
![Screenshot (222)](https://user-images.githubusercontent.com/88782280/153631245-d5965770-fe06-47b7-b025-d5419132802f.png)
<p>&nbsp;</p>
  
8. Untuk kembali kepada commit sebelumnya dapat digunakan
  ```
  $ git checkout <5 dijit hash> -- <nama file>
  ```
 ![Screenshot (224)](https://user-images.githubusercontent.com/88782280/153631364-2663b57b-6c2d-48b2-8a33-3a20f3aea118.png)

  
  
 
