## Membuat Sebuah Project

---

### Goals

* Mempelajari bagaimana membuat sebuah git repository dari nol.

### 01. Membuat sebuah halaman “Hello, World”

Mari kita mulai dengan membuat sebuah direktori kosong bernama "hello", dan membuat sebuah file html bernama ```hello.html``` di dalamnya.

#### Run:

```
mkdir hello
cd hello
touch hello.html
```

#### Isi konten: *hello.html*

```
Hello, World
```

### 02. Membuat sebuah repository

Sekarang kamu mempunyai sebuah direktori dan sebuah file html di dalamnya. Jalankan perintah ```git init``` di dalam direktori tersebut untuk membuat sebuah git repository.

#### Run:

```
git init
```
#### Hasil:

```
$ git init
Initialized empty Git repository in /Users/Gitster-ID/Github/Tutorial/hello/.git/
```

#### 03. Menambahkan sebuah file ke repository

Sekarang kita tambahkan halaman “Hello, World” yang baru saja dibuat ke repository.</p>

#### Run:

```
git add hello.html
git commit -m "Commit pertama"
```

Kamu akan melihat &#8230;

#### Hasil:

```
$ git add hello.html
$ git commit -m "Commit pertama"
[master (root-commit) 911e8c9] First Commit
 1 files changed, 1 insertions(+), 0 deletions(-)
 create mode 100644 hello.html
 ```
