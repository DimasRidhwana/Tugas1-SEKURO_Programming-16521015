## Developer
### 16521015 - Dimas Ridhwana Shalsareza
### Divisi  Programming

<p>&nbsp;</p>

# Rangkuman Video 12 (#6 Gitignore)
## Pengertian
.gitignore ini merupakan suatu file yang disimpan alam repository yang berfungsi untuk menngabaikan beberapa file yang kita pilih
agar tidak ikut ter-commit

# Latihan
1. Buat repository kosong pada gitHub
2. Buat folder berisi 2 file index.html dan style.css
3. Ubah folder menjadi repository
4. Hubungkan repository lokal kepada github
![Screenshot (235)](https://user-images.githubusercontent.com/88782280/153650489-ee9d62d7-e0d1-4f32-a616-16403ff625f4.png)
<p>&nbsp;</p>

5. Masukkan file kedalam stagging area lalu commit file tersebut
![Screenshot (236)](https://user-images.githubusercontent.com/88782280/153650660-5c2c6b5a-bba0-4306-b6ed-f387f046df86.png)
<p>&nbsp;</p>

6. Push 2 file tersebut kedalam github kita dengan cara
  ```
  $ git push -u origin master
  ```
  ![Screenshot (237)](https://user-images.githubusercontent.com/88782280/153651172-d72a2aff-dd09-4f7b-b898-1195c64b11c5.png)
<p>&nbsp;</p>

7.  Buat 2 file baru dan 1 file .gitignore dan daftarkan beberapa file kedalam .gitignore
  ![image](https://user-images.githubusercontent.com/88782280/153651949-c2f50b7f-35d6-4c0c-a267-51e55db725ed.png)
  
  file yang didaftarkan pada .gitigore tersebut tidak akan terbawa commit dengan file lainnya

## File yang disarankan untuk masuk .gitignore
Dapat dilihat di
<li>https://github.com/github/gitignore</li>
<li>https://www.toptal.com/developers/gitignore</li>

