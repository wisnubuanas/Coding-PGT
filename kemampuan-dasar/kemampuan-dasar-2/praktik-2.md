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


4. Selanjutnya kita clone Repository ini ke komputer Lokal :

![gambar](https://user-images.githubusercontent.com/111225906/184919361-12b0d8dc-e04f-4a2d-859c-0febb3470cf5.png)

```
$git Clone https://github.com/wisnubuanas/tes-github.git
cd Oreo
```
![gambar](https://user-images.githubusercontent.com/111225906/184919448-b77cce30-8679-4f68-8b6d-d5c4ac58b216.png)

5. Kemudian buat cabang baru untuk membuat perubahan yang sangat sederhana untuk mengubah readme.md file :
![gambar](https://user-images.githubusercontent.com/111225906/184922867-0c70c1e4-5dbd-47a3-9f37-09b508f37e83.png)


```
git clone git@github.com:wisnubuanas/test-github.git
cd test-github
git checkout -b NEW
echo "# Test" >> README.md
git add README.md
git commit -m "information"
git push origin NEW
```

6. Kembali di akun Contributor kita ke branch yang baru di buat & meng-klik Pull request secara otomatis kembali ke repo asli : 

![gambar](https://user-images.githubusercontent.com/111225906/184922658-07201bf6-d06b-40e4-b9aa-3411b44b02b6.png)

![gambar](https://user-images.githubusercontent.com/111225906/184922767-87f18354-bcbc-4fde-8cd2-885298dea668.png)
![gambar](https://user-images.githubusercontent.com/111225906/184922805-70ba1e10-ab1f-4fe9-a33a-d1f716ae8aec.png)
