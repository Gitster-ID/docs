## Persiapan Awal

---

### Goals

* Persiapan untuk mulai bekerja dengan Git.

### 01. Pengaturan nama dan alamat e-mail

Jika kamu belum pernah menggunakan git sebelumnya, pertama kamu haruslah mengatur Nama dan Alamat E-mail kamu. Jalankan perintah di bawah untuk mengatur Nama dan Alamat E-mail kamu di git client. Jika sudah pernah mengatur Nama dan Alamat E-mail, lewati step pertama ini.

#### Run:

```
git config --global user.name "Nama Kamu"
git config --global user.email "email_kamu@domain.com"
```

### 02. Installasi Options line endings

Untuk pengguna Unix/Mac:

#### Run:

```
git config --global core.autocrlf input
git config --global core.safecrlf true
```

Untuk pengguna Windows:

#### Run:

```
git config --global core.autocrlf true
git config --global core.safecrlf true
```
