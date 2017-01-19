## Meng-commit Sebuah Perubahan

---

### Goals

* Mempelajari bagaimana cara meng-commit pada repository

### 01. Meng-commit sebuah perubahan

Cukup sudah tentang staging.  Mari kita meng-commit sebuah perubahan yang sudah berada di dalam staging area ke repository.

Sebelumnya kita pernah menggunakan perintah ```git commit``` untuk meng-commit versi pertama ```hello.html``` ke repository, dan menggunakan opsi ```-m``` untuk memberi sebuah keterangan commit di command line/terminal. Perintah commit ini dapat mempermudah kamu dalam mengedit keterangan sebuah commit. Sekarang, mari kita commit perubahan pada ```hello.html``` yang sudah kita staging tadi dan memeriksa statusnya.

#### Run:
```
git commit
```

Jika kamu tidak menggunakan opsi ```-m```, git akan membuka editor seperti berikut:

#### Result:
```
|
# Please enter the commit message for your changes. Lines starting
# with '#' will be ignored, and an empty message aborts the commit.
# On branch master
# Changes to be committed:
#   (use "git reset HEAD &lt;file&gt;..." to unstage)
#
#	modified:   hello.html
#
```

Di baris pertama, isi keterangan: &#8220;Menambahkan hi tag&#8221;. Save dan exit editor (biasanya dengan menekan ESC dan tulis ```:wq``` lalu Enter). Kamu seharusnya dapat melihat prosesnya seperti berikut:

#### Result:
```
git commit
Waiting for Emacs...
[master 569aa96] Menambahkan h1 tag
 1 files changed, 1 insertions(+), 1 deletions(-)
```

### 02. Memeriksa status

Terakhir mari kita periksa statusnya.

#### Run:
```
git status
```

Kamu akan melihat &#8230;

#### Result:
```
$ git status
# On branch master
nothing to commit (working directory clean)
```

Direktori project kamu clean, itu artinya kamu dapat melakukan pekerjaan selanjutnya.
