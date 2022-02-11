## Developer
### 16521015 - Dimas Ridhwana Shalsareza
### Divisi  Programming

<p>&nbsp;</p>

# Rangkuman Video 3 (#3 GitHub : Branch)

## Pengertian
Branch sendiri pada Git merupakan suatu cabang yang terdiri dari titik-titik commit. Dalam suuatu repository suatu master branch yang merupakan
cabang atau jalur utama dari suatu repository, sedangkan suatu Master branch dapat terdiri dari beberapa branch lainnya. Dengan memanfaatkan branch, 
kita dapat membuat snapshot tanpa mengganggu Master branch. 

Keguanaan branch ini antara lain
1. Untuk membuat suatu fitur yang bersifat experimental
2. Digunakan saat ada beberapa orang mengerjakan repository yang sama

Kebalikan dari branch adalah merge dimana merge sendiri adalah menggabungkan commit dari branch kembali ke Master branch

## Step by Step Branching

Langkah-langkah dalam melakukan branching adalah sebagai berikut
1. Buat branch dengan seperti berikut

![Screenshot (200)](https://user-images.githubusercontent.com/88782280/153608756-40e9623d-2231-4ce7-bb09-b2f9b21b90dc.png)
<p>&nbsp;</p>
2. Klik edit, pastikan branch sudah berada pada branch yang baru kita buat

![Screenshot (201)](https://user-images.githubusercontent.com/88782280/153608892-c21893e5-acf4-4e26-a751-4ff5e35f3354.png)
<p>&nbsp;</p>

3. Lakukan edit file seperti biasa
4. Pada bagian commit, pastikan branch sudah berubah sesuai dengan branch yang baru kita buat
![Screenshot (204)](https://user-images.githubusercontent.com/88782280/153609059-5b6e66c6-49f6-41cf-b10e-924189980da0.png)


Setelah terbentuk branch kita bisa melihat bahwa sudah ada percabanngan dari master branch.
![Screenshot (205)](https://user-images.githubusercontent.com/88782280/153609540-26f99e29-c9f6-4da1-bc7a-a536103a408c.png)
<p>&nbsp;</p>

## Step by Step Merging

Apabila branch yang kita buat sudah dapat dipastikan dan kita berniat untuk menyatukan lagi branch terseubt kedalam Master branch,
cara yang kita bisa lakukan adalah dengan metode merging.

Berikut adalah langkah-langkah melakukan merging
1. Klik tombol "Compare & Pull Request"

![Screenshot (206)](https://user-images.githubusercontent.com/88782280/153611251-1e66155b-012c-4f61-ab84-d29d18d31486.png)
<p>&nbsp;</p>

2. Pastikan sudah bertanda "Able to merge", lalu klik Create pull request
![Screenshot (207)](https://user-images.githubusercontent.com/88782280/153611387-ef821fae-ee8e-4464-aa58-3972fd08fa8e.png)
<p>&nbsp;</p>

3. Lalu akan diarahkan ke tab Pull Request
4. Apabila sudah setuju dengan pull request tersebut, klik merge pull request lalu confirm merge
![Screenshot (208)](https://user-images.githubusercontent.com/88782280/153611611-c9cb7227-36b8-473e-b52f-6dd447059013.png)
<p>&nbsp;</p>

## Lainnya
Kita dapat membuat lebih dari satu branch yang masing-masing saling berparalel dengan Master branch. Untuk melakukan merging 
beberapa branch tersebut, kita bisa melakukannya secara bertahap, satu persatu dilakukan pull request terhadap master branch










