# Rangkuman video (12) "Git Ignore"

## Pengertian 

<p>Git ignore adalah sebuah file yang dapat kita simpan di repository git kita, agar saaat melakukan add dan commit ada file yang tidak ikut terbawa ke dalam proses commitnya</p>


## Laman web yang  merekomendasikan file untuk diberlakukan ignore

<ol>
<li> https://github.com/github/gitignore</li>
<li> gitignore.io</li>
</ol>

## Cara menggunakan git ignore 

<ol>
<li>Membuat file .gitignore dalam repository yang ingin diberlakukan git ignore</li>
<li>Ketik file dan jenis file yang ingin di ignore, contohnya : chara.txt</li>
<li>Save perubahan</li>
</ol>

## Percobaan 
 
![](https://i.ibb.co/V2cqKKC/git-61.jpg)

<ol>
<li>Membuat folder coba-gitignore, lalu menginit dan mengedit folder tersebut</li>
<li>Mengambil remote dari github</li>
<li>Menambahkan 2 file ke dalam folder lalu melakukan commit </li>

<p>&nbsp<p>

![](https://i.ibb.co/QkBysqw/git-62.jpg)

<ol>
<li>melakukan commit dan push ke github</li>
<li>Menambahkan file git ignore (dalam git ignore terdapat list file chara.txt sehingga tidak tertampil)</li>
<li>melakukan add dan commit</li>
</ol>

<p>&nbsp<p>

![](https://i.ibb.co/0Xkf3KH/git-63.jpg)

<ol>
<li>lalu melakukan push ke github</li>
</ol>

<p>chara.txt tidak keluar karena telah dimasukan ke daftar .gitignore</p>
