---
layout: post
title: Membuat blog menggunakan Github , Jekyll dan Forestry gratis.
author: admin
categories:
- Tutorial
- IT
tags:
- Blog
- Forestry
- Github
- Jekyll
image: https://nanwinata.github.io/uploads/jekyll.png
description: ''
featured: false
hidden: false
rating: 5

---
**Buat account github terlebih dahulu.**

* Langsung aja ke [https://github.com/join?source=header-home](https://github.com/join?source=header-home "https://github.com/join?source=header-home")

isi data sampai kelar dan konfirmasi email.

Bikin repository di https://github.com/new

Tinggalkan github sebentar.

* Kemudian kita cari theme Jekyll yang gratis.

Kita bisa langsung forking theme tersebut melalui github.

_Caranya gampang :_

Saya kasih theme bagus dan gratis untuk kita fork nantinya.

* Cari theme gratis Jekyll , saya berikan satu 
* [https://github.com/wowthemesnet/mundana-theme-jekyll](https://github.com/wowthemesnet/mundana-theme-jekyll "https://github.com/wowthemesnet/mundana-theme-jekyll")

**Forking dibagian kanan atas**

![](https://nanwinata.github.io/uploads/forking.png)

![](https://nanwinata.github.io/uploads/prosesfork.png)

* Setelah selesai fork themes tinggal di rename repository tadi menjadi repository github pages agan dibagian setting.
* ![](https://nanwinata.github.io/uploads/githubpages.png)

[https://github.com/usernameagan/mundana-theme-jekyll/settings](https://github.com/usernameagan/mundana-theme-jekyll/settings "https://github.com/usernameagan/mundana-theme-jekyll/settings") seperti di gambar.

Langkah selanjutnya adalah edit config.yml

![](https://nanwinata.github.io/uploads/config.png)

* Kosongkan baseurl: " "

Untuk yang lain seperti analytics, disqus comment dll itu terserah aja.

Jadi saya asumsikan sudah di edit, saya contohkan config.yml saya deh.

Jadi untuk theme setting saya anggap selesai, kalau ada  yang mau ditanyakan langsung comment aja.

* **_Kita pindah ke Forestry_**

Sebelumnya saya jelaskan dulu Forestry ini akan digunakan untuk mendukung post di blog jekyll agan.

Jadi nanti agan cuma mengakses forestry untuk memposting sesuatu maka akan langsung terposting ke blog jekyll agan.

Forestry menawarkan harga bermacam-macam tapi tentu saja kita nyari yang gratisan aja sesuai judul.

* _Langsung saja kesini_ [_https://app.forestry.io/signup_](https://app.forestry.io/signup "https://app.forestry.io/signup")

Sebaiknya register langsung tanpa sync dari account github, biar nanti setupnya nggak bikin agan bingung.

Setelah login, masuklah ke dashboard forestry seperti gambar.

![](https://nanwinata.github.io/uploads/addsite.png)

* Langkah selanjutnya add site lalu pilih Jekyll , selanjutnya pilih Github ( gambar octopus )

Pilih repository github pages agan tadi, ingat sebelumnya github harus diloginkan dulu.

Pilih github pages usernameagan.github.io lalu dibawahnya pilih Master branch.

Kalau github pagesnya sudah ready maka akan keluar Config file found.

* Next guest invite di skip aja lalu langsung **_IMPORT SITE_** dan tunggu prosesnya selesai.

Maka akan keluar seperti gambar dibawah :

![](https://nanwinata.github.io/uploads/configfound.png)

* _Mark as done_ semua opsi lalu buka github pages agan.

Kalau prosesnya benar maka otomatis pembuatan blognya selesai.

Proses gimana cara posting di **_forestry_** akan dibahas di postingan saya selanjutnya.