## Developer
### 16521015 - Dimas Ridhwana Shalsareza
### Divisi  Programming

<p>&nbsp;</p>

# Rangkuman Video 6 (#6 GitHub : Git Branch & Merge)
## Branch
Pada dasarnya, Git Branch sama dengan Branch yang ada pad github. Namun, kali ini kita melakukannya di dalam komputer sendiri 
bukan di website yang terbuka secara public kepada massa international

## Latihan Pembuatan Branch
1. Buat folder dan file
2. Contoh file seperti berikut
![image](https://user-images.githubusercontent.com/88782280/153638157-88df552b-94f3-4283-b935-ff0dfa3b3d9e.png)
<p>&nbsp;</p>

3. Lakukan commit seperti pada step di rangkuman video 5
![Screenshot (225)](https://user-images.githubusercontent.com/88782280/153639759-1b306910-d3a0-4a08-b5d1-9a5e32dea268.png)
<p>&nbsp;</p>

4. Buat branch dengan menggunakan code berikut
  ```
  $ git branch <nama_branch>
  ```
  
  ![Screenshot (226)](https://user-images.githubusercontent.com/88782280/153640161-117f1dcd-b1d6-4c36-8929-dce1b2200a1f.png)
  <p>&nbsp;</p>
  
5. Untuk visualisasi dapat dilakukan dengan cara 
  ```
  $ git log --all --oneline --graph
  ```
  <p>&nbsp;</p>
  
6. Untuk mempersingkat, kita bisa membuaut suatu alias dengan cara
  ```
  $ alias graph="git log --all --decorate --oneline --graph"
  ```
  ![Screenshot (227)](https://user-images.githubusercontent.com/88782280/153640968-37a3d684-a6ff-418a-882e-9ac4edc3cdba.png)
  <p>&nbsp;</p>
  
7.  Untuk mengakses branch, kita dapat melakukan
```
$ git chechout <nama_branch>
```
8.  Penambahan file dosen.html pada branch
![Screenshot (228)](https://user-images.githubusercontent.com/88782280/153642282-917de08f-2ff1-47c0-8f5f-af3adbe73b1c.png)

9.  Commit kembali file dosen tersebut
10.  Penambahan file staff pada branch staff
![image](https://user-images.githubusercontent.com/88782280/153643274-c7d064c6-a1a8-40ec-961a-ba6c59013430.png)

11.  Commit kembali file staff tersebut

<p>&nbsp;</p>

## Merge
Jenis Merge pada Git :
1. Fast Forward Merge : Terjadi ketika branch yang ingin kita satukan berada dalam jalur langsung 
2. Three-way Merge


## Latihan Merge
Untuk branch master dan dosen termasuk pada fast forward merge sehingga tahap untuk melakukan merge sebagai berikut,
1. Untuk melakukan merge kita dapat menggunakan code sebagai berikut
  ```
  $ git merge <nama_branch>
  ```
  ![Screenshot (230)](https://user-images.githubusercontent.com/88782280/153645076-b73f76dc-7357-48b0-9470-6c4c8634d46c.png)
  <p>&nbsp;</p>

2. Menghapus branch
  ```
   $ git branch -d dosen 
  ```
  ![Screenshot (232)](https://user-images.githubusercontent.com/88782280/153645573-102bb97c-d4c5-4985-8142-9489ed40dfbe.png)
  <p>&nbsp;</p>


Untuk branch master yang merged dengan dosen tidak dapat langsung dilakukan fast forward merge karena kedua branch tidak saling
berhubungan, maka langkah untuk melakukan merge sebagai berikut,
1. Gunakan code
  ```
  $ git merge <staff>
  ```
2. Akan keluar tampilan Vim
untuk keluar dari vim gunakan :wq!


3. Untuk mengecek apa saja branch yang sudah di merge bisa gunakan code
  ```
  $ git branch --merged
  ```

4. Hapus branch staff

![Screenshot (233)](https://user-images.githubusercontent.com/88782280/153647655-d860e890-3c6f-414f-bfc8-10d85d62546b.png)
















