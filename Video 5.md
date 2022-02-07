# Rangkuman video (5)) "Bekerja dengan Git"

## Menginstall Git Bash 
<ol>
<li>Kunjungi laman git-scm.com</li>
<li>Download git sesuai dengan spesifikasi komputer/PC yang dimiliki</li>
<li>Setup dan install git yang telah di download</li>
</ol>

## Git Command 
<ol>
    <li>git status : untuk mengechek status dari git pada directory</li>
    <li>git : memunculkan help bagiaman cara untuk memakai git</li>
    <li>git --version: melihat versi dari git yang telah terinstal</li>
    <li>git init : menginisialisasikan repo git di komputer kita</li>
    <li> git add : untuk menambahkan file menuju staging area</li>
    <li>Git commit : untuk melakukan commit </li>
    <li>git config: untuk mengetahui configurasi dari git</li>
    <li>git branch : untuk membuat branch</li>
</ol>

## 3 area pada repo git 
<ol>
    <li>Working Tree</li>
    <li>Staging Area</li>
    <li>History</li>
</ol>
<p> Staging area dan history tersimpan dalam file berbentuk git. pada folder yang telah di git init.</p>

## Percobaan 

<p>&nbsp</p>

<p>Menggunakan git</p>

![Menggunakan perintah git untuk melihat help](https://i.ibb.co/JrQnwQZ/git-11.jpg)

<p>Mengecheck versi dari git</p>

![](https://i.ibb.co/58TY9M2/git-2.jpg)

<p>Menggunakan ls untuk melihat list dari folder, pwd untuk mengechek lokasi folder yang di buka saat ini</p>

![](https://i.ibb.co/qY369Rn/git-3.jpg)

<p>Menggunakan perintah cd untuk masuk ke dalam salah satu folder dalam list</p>

![](https://i.ibb.co/Jn8KyHy/gitu-4.jpg)

<p>Menggunakan git init pada folder wpu-test-repo, mengecheck git status untuk mengetahui apakah ada folder yang belum terupdate pada git, lalu menambahkan file tersebut dalam staging.</p>

![](https://i.ibb.co/h83sXBw/git-5.jpg)

<p>Melakukan configurasi awal terhadap nama dan email, lalu melakukan git commit pada branch master</p>

![](https://i.ibb.co/VJCfqzb/git-6.jpg)

<p>Mengechek status ulang setelah adanya modifikasi pada file SEKURO.html serta penambahan file style.css pada folder, serta menambahkan ke dalam stages</p>

![](https://i.ibb.co/sRS0JTt/git-7.jpg)

<p>Melakukan commit, lalu memiliki perubahan lagi pada file style.css dan SEKURO.html, serta penambahan javascript.js, lalu di add dan di commit lagi. Untuk melihat history commit dapat digunakan git log</p>

![](https://i.ibb.co/ZGTdszh/git-8.png)

<p>Gunakan perintah git log -x, dengan x untuk melihat berapa commit terakhir yang ingin dilihat, menggunakan perintah git log -- "nama file", untuk melihat log secara khusus dari perubahan file. Menggunakan git checkout untuk mengambil file css yang telah dihilangkan menjadi muncul kembali sebelum commit penghilangan</p>

![](https://i.ibb.co/47FK0s3/git-9.png)

<p>Melakukan commit ulang agar file style.css dapat kembali ke folder<p>

![](https://i.ibb.co/JymGWVw/git-10.jpg)