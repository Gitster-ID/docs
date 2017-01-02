## Staging Perubahan

---

### Goals

* Mempelajari bagaimana staging perubahan yang akan ditambahkan ke repository nantinya

### 01. Menambahkan perubahan

Jalankan perintah git add, lalu periksa status direktori

#### Run:
```
git add hello.html
git status
```

Kamu akan melihat &#8230;

#### Result:
```
$ git add hello.html
$ git status
# On branch master
# Changes to be committed:
#   (use "git reset HEAD <file>..." to unstage)
#
#	modified:   hello.html
#
```

Perubahan pada ```hello.html``` telah dimasukkan ke dalam stage. Ini artinya git mengetahui kalau ada perubahan pada direktori, akan tetapi ini tidak akan permanen di repository. Untuk membuatnya permanen di repository kita harus commit perubahannya terlebih dulu.

Yakinkan kamu meng-commit file yang benar-benar ingin kamu tambahkan ke repository, tapi jika tidak yakin seperti yang ada pada laporan git status tadi kamu dapat mengembalikan status file yang telah dimasukkan ke stage tadi dengan perintah ```git reset```.
