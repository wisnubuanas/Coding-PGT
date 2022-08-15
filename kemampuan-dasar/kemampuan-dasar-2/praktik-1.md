**Langkah 1: Inisialisasi Proyek Baru**

1. Buka Github dan klik tombol '+' di pojok kanan rop dan pilih 'New Repository'.

![gambar](https://user-images.githubusercontent.com/111225906/184666599-aba3c3b6-7890-48b8-9f11-e8fdc55ba2f8.png)

2. Kemudian isi kolom Repository name dan Description. 

![gambar](https://user-images.githubusercontent.com/111225906/184666748-c4eb5bd7-5001-48b3-9d79-3791f20d2282.png)

3. Klik “create repository”

![gambar](https://user-images.githubusercontent.com/111225906/184666872-316d4620-796d-4d0f-8ad3-865a6ce54585.png)

4. Selanjutnya Anda akan melihat halaman setup. Ini adalah petunjuk untuk menghubungkan Repo yang anda buat di Github ke direktori yang anda buat di komputer Anda.

![gambar](https://user-images.githubusercontent.com/111225906/184666985-30953e43-fe66-4b84-8a02-6cee4abbbb85.png)


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
![gambar](https://user-images.githubusercontent.com/111225906/184667302-97e3213c-47d3-488d-b249-ccb8743b045f.png)


6. Setelah itu halaman repo akan menjadi seperti ini

![gambar](https://user-images.githubusercontent.com/111225906/184667344-160506b2-34dc-46dd-b8da-e27631e9a965.png)


7. Kemudian saya ingin memasukan beberapa file ke dalam Repo dari lokal direktori dengan menggunakan command

![gambar](https://user-images.githubusercontent.com/111225906/184667383-7500ff02-1362-4e73-b322-c9d9757e6378.png)

8. Masukan kode berikut
```
$ git add .

$ gir commit -m

$ git push
```
![gambar](https://user-images.githubusercontent.com/111225906/184667498-13e3fe49-c9bf-43d9-8a7c-15f0046a56f4.png)

9. Setelah itu cek kembali halaman repo 

![gambar](https://user-images.githubusercontent.com/111225906/184667585-de3ad190-f93d-4c06-9bf5-a77d27b084c4.png)
## **Langkah 2: *Menyiapkan Tim***
1. Klik tab Setting lalu klik Collaborators

![gambar](https://user-images.githubusercontent.com/111225906/184667702-8df1aa27-6643-47dd-b0ea-568404a947fb.png)
2. Masukan nama atau email rekan yang akan anda ajak kolaborasi kemudian klik “add to this repository”

![gambar](https://user-images.githubusercontent.com/111225906/184667753-4720a32c-b2dd-4bb7-82c2-016401605eb0.png)

3. Kolaborator dapat meng-clone repo ke direktory lokal dengan command :
![gambar](https://user-images.githubusercontent.com/111225906/184667800-31898569-2c2e-4a9b-95e4-af4e6ec2969a.png)

```
$ get clone https://github.com/wisnubuanas/test-github.git

$ cd Hello
```

