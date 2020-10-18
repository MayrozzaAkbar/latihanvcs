**_CARA PENGGUNAAN GIT_**

**1.Download Aplikasi Git**
Buka website resmi git https://git-scm.com/, kemudian pilih git sesuai perangkat yang anda gunakan. Jika menggunakan windows maka klik pada tulisan windows, kemudian unduh Git sesuai dengan arsitektur komputer anda. Jika menggunakan 64bit, unduh yang 64bit. Begitu juga jika menggunakan 32bit.
![2020-10-18 (26)](https://user-images.githubusercontent.com/73070964/96374029-71fd6600-119a-11eb-9920-1e5bb8310140.png)

**2. Instalasi Git**
Instal Git pada perangkat komputer anda.

Jika sudah berhasil terinstal, untuk mencobanya, silahkan buka CMD atau PowerShell, kemudian ketik perintah

git --version
![2020-10-18 (25)](https://user-images.githubusercontent.com/73070964/96374064-ad983000-119a-11eb-88f5-97ac40679227.png)

**3. Melakukan Konfigurasi Awal**
Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi user.name dan user.email.
Apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi kegagalan saat menjalankan perintah git commit.

Silahkan lakukan konfigurasi dengan perintah berikut ini: $ git config --global user.name "username anda" $ git config --global user.email "email anda"
![IMG-20201018-WA0004](https://user-images.githubusercontent.com/73070964/96374094-e46e4600-119a-11eb-8c77-5d480ebb1532.jpg)

**4. Membuat Repositori Lokal**

- Buat folder aktif, misalnya Lab_pemrogramans1, kemudian klik kanan pada folder tersebut, lalu klik git bash here

![2020-10-18 (16)](https://user-images.githubusercontent.com/73070964/96374156-34e5a380-119b-11eb-91ed-589454b017f9.png)

- Kemudian buat folder project praktikum dengan nama Latihan1 dengan cara memasukan perintah berikut:

$ mkdir Latihan1 $ cd Latihan1
![IMG-20201018-WA0005](https://user-images.githubusercontent.com/73070964/96374206-6fe7d700-119b-11eb-83ce-1f233665ac54.jpg)

- Jalankan perintah git init untuk membuat repository lokal

$ git init
![IMG-20201018-WA0006](https://user-images.githubusercontent.com/73070964/96374240-a7ef1a00-119b-11eb-89b9-8faaed137929.jpg)

**5. Menambahkan File Baru Pada Repository**
Untuk membuat file dapat menggunakan text editor, lalu menyimpan filenya pada direktori aktif (repository). disini kita akan coba buat satu file bernama README.md (text file) dengan menggunakan perintah :
$ echo "#Latihan 1" >> README.md
![IMG-20201018-WA0007](https://user-images.githubusercontent.com/73070964/96374270-e71d6b00-119b-11eb-8c3c-58aaf5f96beb.jpg)

Untuk menambah file yang baru saja dibuat tersebut gunakan perintah git add
$ git add README.md
![IMG-20201018-WA0008](https://user-images.githubusercontent.com/73070964/96374283-fd2b2b80-119b-11eb-92cf-0e590c7351a1.jpg)

**6. Commit (Menyimpan perubahan ke database)**
Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah berikut: $ git commit -m "komentar commit"
![IMG-20201018-WA0009](https://user-images.githubusercontent.com/73070964/96374312-2f3c8d80-119c-11eb-92d8-ae0ad79bfdc5.jpg)

**7. Membuat Repository Server**

1. Server repository yang digunakan adalah http://github.com
2. Buatlah akun github, kemudian pada laman github klik tombol start a project
![2020-10-18 (17)](https://user-images.githubusercontent.com/73070964/96374410-d6212980-119c-11eb-9db5-73d3ae80e838.png)
3. atau klik new repository dari menu icon +
<img width="182" alt="96281939-3b8de280-1004-11eb-966a-870696a987c9" src="https://user-images.githubusercontent.com/73070964/96374432-0668c800-119d-11eb-90af-282a677df9ac.png">
4. Isi nama repositorynya, misalnya: latihanvcs, kemudian klik tombol create repository.


**8. Menambahkan Remote Repository**
Untuk menambahkan remote repository server, gunakan perintah: $ git remote origin [url]
![IMG-20201018-WA0010](https://user-images.githubusercontent.com/73070964/96374520-79723e80-119d-11eb-99ba-37afbf310808.jpg)

**9. PUSH (Mengirim Perubahan Ke Server)**

- Untuk mengirim perubahan pada local repository ke server gunakan perintah berikut:
$ git push -u origin master
![IMG-20201018-WA0011](https://user-images.githubusercontent.com/73070964/96374550-94dd4980-119d-11eb-96b1-e108efaa8a44.jpg)

- Perintah ini akan meminta memasukkan username dan password pada akun https://github.com/
![2020-10-18 (20)](https://user-images.githubusercontent.com/73070964/96374578-bcccad00-119d-11eb-8d4c-b2fe1678b080.png)

**10. Melihat Hasil Pada Server Repository**
Buka laman [https://github.com/], arahkan pada repositorinya. Maka halaman tersebut akan berubah sesuai dengan repository yang telah anda buat sebelumnya.
![2020-10-18 (22)](https://user-images.githubusercontent.com/73070964/96374605-ebe31e80-119d-11eb-9b61-3a21458629f8.png)

**11. Clone Repository**
Clone repository, pada dasarnya adalah mengcopy repository server dan secara otomatis membuat satu direktory sesuai dengan nama repositorynya (working directory). untuk melakukan cloning, gunakan perintah berikut: $ git clone [url]
![IMG-20201018-WA0012](https://user-images.githubusercontent.com/73070964/96374643-0ae1b080-119e-11eb-9d1b-e55ba8c1c0c4.jpg)

SELESAI
Akbar
Mahasiswa Universitas Pelita Bangsa
