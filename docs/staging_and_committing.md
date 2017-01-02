## Staging dan committing

---

Langkah-langkah staging di git dapat membiarkan kita untuk membuat perubahan pada direktori kerja, dan setiap kita akan berinteraksi dengan version control, kita dapat membuat perubahan dengan beberapa commit dan git akan memonitornya.

Contoh kasus, misalkan kamu telah merubah tiga file (```a.html```, ```b.html```, dan ```c.html```). Setelah itu yang perlu kita lakukan adalah menambahkan semua perubahan tersebut yang di mana perubahan pada file ```a.html``` dan ```b.html``` adalah satu commit yang sama, sedangkan perubahan pada file ```c.html``` adalah commit yang berbeda dengan kedua file tersebut.

Dalam contoh kasus di atas, kita dapat menggunakan perintah-perintah sebagai berikut:

```
git add a.html
git add b.html
git commit -m "Perubahan untuk a dan b"
```

```
git add c.html
git commit -m "Perubahan untuk c"
```

Membedakan staging dan committing, akan mempermudah kita untuk mengatur apa yang ada pada sebuah commit.
