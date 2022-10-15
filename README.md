Tutorial cara penggunaan git

Pertama kalian harus instal terlebih dahulu software Git
Lalu kalian bisa buka software tersebut

1. Login Git

Langkah pertama kalian adalah memasukan username dengan menggunakan perintah 

$ git config --global user.name "UsernameAnda"

lalu kalian tambahkan juga email dengan menggunakan perintah 

$ git config --global user.email "email anda"

![image](https://user-images.githubusercontent.com/48305171/195885286-2548f545-1616-4d80-9494-aee6bfa22e72.png)

2. Login Github

Langkah kedua kalian bisa login ke dalam website github, Setelah kalian login akan muncul tampilan dashboard dari github tersebut

![image](https://user-images.githubusercontent.com/48305171/195887444-b88aa516-4432-43a5-983d-264dc9916b2f.png)

3. Buat Repository

Setelah berhasil login ke GitHub, Anda bisa mulai membuat repository. Klik tombol New pada menu Repositories untuk membuat repository baru.

![image](https://user-images.githubusercontent.com/48305171/195888036-db38d3f8-9a88-468d-95a3-a5a8de9a7faf.png)

Kemudian kaliam akan diarahkan pada halaman untuk membuat repository baru seperti gambar di bawah ini.

![image](https://user-images.githubusercontent.com/48305171/195888551-40316f34-ed37-4e1d-94eb-052ed774a7f7.png)

4. Buat Folder 

Lalu kalian buat folder di localdisk koomputer kalian 

![image](https://user-images.githubusercontent.com/48305171/195889040-41cb25e2-7829-414c-b966-71777b300128.png)

jika sudah kalian klik kanan pada folder tersebut lalu klik Git Bash

![image](https://user-images.githubusercontent.com/48305171/195889426-8c0f4ae8-972c-4f31-84b0-5483ab38c9b4.png)

Buat folder dengan menggunakan perintah dan buka folder tersebut

$mkdir latihan1

$cd latihan1

![image](https://user-images.githubusercontent.com/48305171/195969412-4673d1fe-3b8a-4734-a465-f81cabc63bf6.png)

dan tambahkan file README.md dengan menggunakan perintah 

$echo "#LatihanVCS" >> README.md

![image](https://user-images.githubusercontent.com/48305171/195970348-dadffc9f-f112-4af3-afb5-0eb9972d7ad6.png)

kemudian buat repository lokal menggunakan perintah

$git init

![image](https://user-images.githubusercontent.com/48305171/195981148-99b3ed48-2540-4b03-a58c-7dd455343bcc.png)

Untuk menambahkan file yang baru saja dibuat tersebut menggunakan perintah

$git add README.md

![image](https://user-images.githubusercontent.com/48305171/195981284-5e583447-5439-468d-973b-b68eb53af57b.png)

Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah

$git add README.md

![image](https://user-images.githubusercontent.com/48305171/195981348-019acff4-afec-4c7c-835a-88b62322d2e4.png)

Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah

$git commit -m "first commit"

![image](https://user-images.githubusercontent.com/48305171/195981416-70e001c2-5c59-4110-8560-4bb069b188d7.png)

kemudian gunakan perintah 

$git branch -M main

![image](https://user-images.githubusercontent.com/48305171/195981938-a5ef769c-1158-4380-8fa9-c8aca58f8c2b.png)


Setelah itu menambahkan remote repository. remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository,
sehingga dapat diakses oleh banyak user. dengan menggunakan perintah

$git remote add origin https://github.com/dedialdians12/LatihanVCS.git

![image](https://user-images.githubusercontent.com/48305171/195981659-9941682e-63f5-4164-8bc7-7e9234fdf998.png)

Dan untuk mengirim perubahan pada local repository ke server gunakan perintah

$git push -u origin main

Dan kita bisa cek di repository langsung pada website github
![image](https://user-images.githubusercontent.com/48305171/195981879-d65092b8-c323-41f5-bf6b-9d4f6c1da659.png)

