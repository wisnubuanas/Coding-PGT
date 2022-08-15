**Langkah 1: Inisialisasi Proyek Baru**

1. Buka Github dan klik tombol '+' di pojok kanan rop dan pilih 'New Repository'.

![gambar](https://user-images.githubusercontent.com/111225906/184666599-aba3c3b6-7890-48b8-9f11-e8fdc55ba2f8.png)

2. Kemudian isi kolom Repository name dan Description. 

![](Aspose.Words.4287b99a-d0cf-4980-ba64-acb7151cf845.002.png)

3. Klik “create repository”

![](Aspose.Words.4287b99a-d0cf-4980-ba64-acb7151cf845.003.png)

4. Selanjutnya Anda akan melihat halaman setup. Ini adalah petunjuk untuk menghubungkan Repo yang anda buat di Github ke direktori yang anda buat di komputer Anda.

![](Aspose.Words.4287b99a-d0cf-4980-ba64-acb7151cf845.003.png)

5. Selanjutnya menghubungkan Repo yang baru di buat ke di Github ke direktory 'Lokal' dan menambahkan 1 file bernama Readme.
```
$ echo "# Hello" >> README.md

$ git init

$ git add README.md

$ git commit -m "first commit"

$ git branch -M main

$ git remote add origin https://github.com/wisnubuanas/test-github.git

$ git push -u origin main
```
![](Aspose.Words.4287b99a-d0cf-4980-ba64-acb7151cf845.003.png)

6. Setelah itu halaman repo akan menjadi seperti ini

![](Aspose.Words.4287b99a-d0cf-4980-ba64-acb7151cf845.003.png)

7. Kemudian saya ingin memasukan beberapa file ke dalam Repo dari lokal direktori dengan menggunakan command

![](Aspose.Words.4287b99a-d0cf-4980-ba64-acb7151cf845.003.png)

8. Masukan kode berikut
```
$ git add .

$ gir commit -m

$ git push
```
![](Aspose.Words.4287b99a-d0cf-4980-ba64-acb7151cf845.003.png)

9. Setelah itu cek kembali halaman repo 

![](Aspose.Words.4287b99a-d0cf-4980-ba64-acb7151cf845.003.png)
## **Langkah 2: *Menyiapkan Tim***
1. Klik tab Setting lalu klik Collaborators

![](Aspose.Words.4287b99a-d0cf-4980-ba64-acb7151cf845.003.png)

2. Masukan nama atau email rekan yang akan anda ajak kolaborasi kemudian klik “add to this repository”

![](Aspose.Words.4287b99a-d0cf-4980-ba64-acb7151cf845.003.png)

3. Kolaborator dapat meng-clone repo ke direktory lokal dengan command :

![](Aspose.Words.4287b99a-d0cf-4980-ba64-acb7151cf845.004.png)

```
$ get clone https://github.com/wisnubuanas/test-github.git

$ cd Hello
```

