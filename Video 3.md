# Rangkuman video (3) "Branch"

## Brancing 

<ol>
    <li>Membuat Git Branch</li>
    <li>Membuat snapshot tanpa menganggu jalur utama (Master branch)</li>
    <li>Fitur Experimental </li>
    <li>2 orang dapat mengerjakan repo yang sama</li>
</ol>

## Cara membuat branch ada 2 

### Pertama 

<ol>
    <li>Edit file yang ingin di buat branchingnya</li>
    <li>Setelah melakukan perubahan, pilih create a new branch</li>
    <li>Lalu simpan</li>
</ol>

### Kedua 

<ol> 
    <li>Dalam repositery, tekan Swtich branches</li>
    <li>Ketik nama branches, jika tidak ada maka otomatis membuat branches baru</li>
</ol>

## Branch 

<p> Perlu diketahui bahwa jalur utama dan branch adalah jalur yang berbeda, sehingga perubahan yang telah dilakukan di branch tidak mengganti jalur utama.<p>

## Cara merge branch 

<ol>
    <li>Tekan Compare and pull request pada repository branch utama</li>
    <li>Setelah masuk kedalam window open pull request, lalu create a pull request untuk meminta agar branch dimasukan ke dalam jalur utama.<li>
    <li>Kembali ke jalur utama, lalu tekan pull request</li>
    <li>Check apakah ada konflik atau tidak agar bisa di merge</li>
    <li>Lalu mtekan confirm merge, agar branch masuk ke dalam jalur utama.</li>
</ol>

## Cara memperbaiki konflik branch 

<p>Konflik branch dapat terjadi apabila, kita mengubah isi dalam baris ( tidak hanya menambahkan ), contoh pada main branch baris ke-1 berisi string "URO", lalu pada cabang branch baris pertama berisi string "SEKURO" pada file yang sama. Hal ini dapat diselesaikan dengan langkah-langkah berikut</p>

<ol>
    <li>Tekan Resolve conflicts pada pull request</li>
    <li>Setelah diarahkan ke kode editor, kita perlu mengubah isi dari file tersebut</li>
    <li>Kita harus memilih salah satu, kita memilih isi dari jalur utama atau jalur branch tersebut, sehingga kita perlu menghapus salah satunya</li> 
    </li>Setelah konflik terselesaikan, kita menggunakan perintah Merge untuk mengeluarkan hasil seperti pada saat kita mengedit pada kode editor</li>
</ol>

## Notebook 
<ol>
    <li>Apabila terdapat 3 hingga lebih branch, maka branch harus di merge satu persatu ke main branch ( tidak bisa 3 atau lebih sekaligus)</li>
    <li>Apabila ada konflik antara jalur utama dan branch yang menyebab kan tidak bisa di merge (adanya perubahan baris), harus di resolve oleh owner yang memiliki jalur utama</li>