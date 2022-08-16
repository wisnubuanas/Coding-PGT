## ***Kolaborasi tim dengan github***

**1. Organization**
1. klik profile kemudian setting
![gambar](https://user-images.githubusercontent.com/111225906/184904153-c719551a-e023-40d9-b426-6fac35ec53b0.png)
2. klik organization kemudian new organization
![gambar](https://user-images.githubusercontent.com/111225906/184904392-64502eb1-0705-423f-8522-af6ab64d3f5f.png)
3. isi nama organisasi dan email
 ![gambar](https://user-images.githubusercontent.com/111225906/184904486-8e97f58b-d32e-4b92-894a-516419347ab3.png)
4. kemudian centang accept lalu klik next
 ![gambar](https://user-images.githubusercontent.com/111225906/184904617-133ca1e0-ee61-4c1a-8a16-e52123d56bc7.png)

 
    Ada 3 Perizinan yang bisa di berikan :

    - Pull Only : Fetch and Merge dengan repositori lain atau salinan lokal. Akses hanya baca.
    - Push and Pull : bersama dengan pembaruan Repo jarak jauh. Baca + Akses tulis
    - Push, Pull & Administrative : bersama dengan hak atas info penagihan, membuat tim serta membatalkan akun Organization. Baca + Tulis + akses Admin

atau bisa dengan command
```
 https://github.com/organizations/[organization-name]/teams/new
 ```
 
 **2. Collaborator**
 Collaborators digunakan untuk memberikan akses Read + Write access ke satu repositori yang dimiliki oleh akun pribadi. Untuk menambahkan Collaborators, (akun pribadi Github lainnya), cukup buka ```https://github.com/[username]/[repo-name]/settings/collaboration:```
 
Setelah kita memiliki akses Write ke repositori kita dapat melakukan :  
* ```git clone``` untuk mengubah
* ```git pull``` untuk mengambil dan menggabungkan setiap perubahan dalam repositori jarak jauh
* ```git push``` untuk memperbarui repositori jarak jauh dengan perubahan kita sendiri:

## ***Pull Request***
Memulai Pull Request

Ada dua model pull request di Github:

    - Fork & Pull Model - Digunakan di repositori publik yang tidak memiliki akses push
    - Share Repository Model - Digunakan dalam repositori pribadi yang kita miliki akses push. Fork tidak diperlukan adalah case ini.
    
1. klik fork
![gambar](https://user-images.githubusercontent.com/111225906/184915239-fd4201e9-f9be-4488-b29b-b3d969fff1d1.png)


2. klik create a fork
![gambar](https://user-images.githubusercontent.com/111225906/184915369-78798c72-6f7a-42e3-936a-20948528ca84.png)

3. berikut hasil setelah fork repo
![gambar](https://user-images.githubusercontent.com/111225906/184915617-6ecc4205-a5e2-4ca5-8654-9c8a5c83164c.png)


5. Selanjutnya kita clone Repository ini ke komputer Lokal :


```git Clone https://github.com/wisnubuanas/tes-github.git
cd Oreo
```
4. Kemudian buat cabang baru untuk membuat perubahan yang sangat sederhana untuk mengubah readme.md file :


```
git clone git@github.com:wisnubuanas/test-github.git
cd test-github
git checkout -b NEW
echo "# Test" >> README.md
git add README.md
git commit -m "information"
git push origin NEW
```

Kembali di akun Contributor kita ke branch yang baru di buat & meng-klik Pull request secara otomatis kembali ke repo asli : 

