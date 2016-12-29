## Membuat Perubahan

---

### Goals

* Mempelajari bagaimana memonitor direktori project

### 01. Merubah file untuk halaman “Hello, World”

Mari kita menambahkan beberapa tag HTML di file ```hello.html```. Rubah isi dalam file menjadi:

#### File: *hello.html*

```
<h1>Hello, World!</h1>
```

### 02. Memeriksa status

Periksa status direktori project

#### Run:

```
git status
```

Kamu akan melihat &#8230;

#### Hasil:

```
$ git status
# On branch master
# Changes not staged for commit:
#   (use "git add <file>..." to update what will be committed)
#   (use "git checkout -- <file>..." to discard changes in working directory)
#
#	modified:   hello.html
#
no changes added to commit (use "git add" and/or "git commit -a")
```

Poin penting di sini yaitu, git tahu bahwa file ```hello.html``` telah termodifikasi, tetapi file tersebut belum dimasukkan ke repository.

Poin lainnya yang ada pada laporan status di atas adalah petunjuk tentang apa yang harus dilakukan selanjutnya. Jika kamu ingin memasukkan file yang telah dimodifikasi tersebut ke repository, gunakan perintah ```git add```. Untuk mengembalikan file ke awal gunakan perintah ```git checkout```.


## 03. Selanjut &#8230;

Staging perubahan.
