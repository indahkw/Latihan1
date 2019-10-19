TUTORIAL MEMBUAT FILE README.MD

1.	Download git bash http://git-scm.com/ download sesuai OS masing-masing
Jika menggunakan 64bit, unduh yang 64bit. Begitu juga jika menggunakan 32bit.		

 ![1](https://user-images.githubusercontent.com/56398559/67141233-9ecb2480-f28b-11e9-804d-3167ccad88f9.jpg)

2.	Jika sudah di download dan di install, langkah selanjutnya yaitu buka aplikasi git bash yang tadi sudah di install.

![2](https://user-images.githubusercontent.com/56398559/67141235-9ffc5180-f28b-11e9-83bd-9f6313eee94f.jpg) 
 
3.	Jika sudah masuk ke Git Bash ketik perintah : git config --global user.name “nama user”

 ![3](https://user-images.githubusercontent.com/56398559/67141237-a094e800-f28b-11e9-8d21-b18feb378104.jpg)

4.	Selanjutnya ketik : git config --global user.email “nama user”

 ![4](https://user-images.githubusercontent.com/56398559/67141238-a12d7e80-f28b-11e9-8e29-20cfdbd79e32.jpg)

5.	Selanjutnya ketik : mkdir latihan1

![5](https://user-images.githubusercontent.com/56398559/67141239-a12d7e80-f28b-11e9-94a2-225ca2d155d4.jpg)
!

6.	Selanjutnya ketik : cd latihan1
 
![6](https://user-images.githubusercontent.com/56398559/67141240-a25eab80-f28b-11e9-857d-1d01042d7d7c.jpg)

7.	Selanjutnya ketik : git init untuk membuat repository local
8.	Berikutnya untuk membuka file readme.md dan isi dengan teks latihan1 dengan menjalankan perintah  echo”#latihan1”README.md

![7-8](https://user-images.githubusercontent.com/56398559/67141929-c79fe980-f28c-11e9-9d7d-e35e9937e3a2.jpg)
 
9.	Apabila anda telah berhasil  menjalankan perintahnya maka akan muncul file README.md di dalam folder latihan1
 
![9](https://user-images.githubusercontent.com/56398559/67141930-c79fe980-f28c-11e9-8112-de1381c30630.jpg)

![9-](https://user-images.githubusercontent.com/56398559/67141931-c8388000-f28c-11e9-8f56-9f07d03d6059.jpg)

10.	 Selanjutnya ketik git add README.md di git bash

![10](https://user-images.githubusercontent.com/56398559/67141932-c8d11680-f28c-11e9-83b9-a8a38fc8a0ba.jpg)
 
11.	 Selanjutnya ketik perintah git commit –m”file pertama” untuk membuat file.
→ saya membuat file bernama “file pertama” seperti dibawah ini :

 ![11](https://user-images.githubusercontent.com/56398559/67141937-ca024380-f28c-11e9-9804-c6cde4041d21.jpg)

TUTORIAL MEMBUAT REPOSITORY SERVER

1.	Server repository yang akan kita gunakan adalah http://github.com
2.	Anda harus membuat akun git hub terlebih dahulu
3.	Pada halaman github klik ( icon + ) klik new repository

 ![image](https://user-images.githubusercontent.com/56398559/67142693-084c3280-f28e-11e9-8c68-b65eea779d2e.png)
 
4.	Isi nama repository misal : Latihan1, lalu klik buat repository.

 ![15](https://user-images.githubusercontent.com/56398559/67141940-cb337080-f28c-11e9-8e07-af6dec3e0e07.jpg)
 
MENAMBAHKAN REMOTE REPOSITORY
1.	Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository, sehingga dapat diakses oleh banyak user.
2.	Untuk menambahkan remote repository server, gunakan perintah git remote add origin [url] pada git bash.
 
 ![16](https://user-images.githubusercontent.com/56398559/67141941-cbcc0700-f28c-11e9-9400-426a99e48c8b.jpg)

PUSH ( MENGIRIM PERUBAHAN KE SERVER )
1.	Untuk mengirim perubahan pada local repository ke server gunakan perintah git push -u origin master
(untuk menaruh file README.md yang tadi sudah dibuat)

 ![17](https://user-images.githubusercontent.com/56398559/67141942-cbcc0700-f28c-11e9-92d7-f28869d3c0ba.jpg)
 
2.	Perintah ini akan meminta memasukkan username dan password pada akun github.com, dan akan muncul tampilan seperti ini.
             
![18](https://user-images.githubusercontent.com/56398559/67141943-cc649d80-f28c-11e9-9090-659925d9df7d.jpg)

MELIHAT HASILNYA PADA SERVER REPOSITORY
1.	Buka halaman github.com arahkan pada repositorynya, maka perubahan akan terlihat pada tampilan berikut. ( Jika berhasil akan muncul gambar dibawah,dan file README.md sudah berada di repository latihan1 di github.com yang telah dibuat.

![19](https://user-images.githubusercontent.com/56398559/67141945-ce2e6100-f28c-11e9-9d4b-53188aad7031.jpg)
 
CLONEY REPOSITORY
1.	Clone repository, pada dasarnya adalah meng-copy repository server dan secara otomatis membuat satu direktory sesuai dengan nama repositorynya (working directory).
2.	Untuk melakukan cloning, gunakan perintah git clone [url]
 
![image](https://user-images.githubusercontent.com/56398559/67142735-582af980-f28e-11e9-8007-47f733bb46fd.png)

NOTE : Sekian penjelasan dari saya, semoga dapat bermanfaat untuk saya pribadi selaku penulis dan teman-teman yang akan membacanya.
