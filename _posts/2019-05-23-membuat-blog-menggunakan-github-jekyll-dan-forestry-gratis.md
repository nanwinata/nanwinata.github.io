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
rating: "5"

---
Ngeblog menggunakan Github, Jekyll dan Forestry ini sepertinya masih agak langka di Indonesia. Banyak blogger masih banyak menggunakan wordpress , blogspot dll.

Masih banyak static hosting yang mendukung pembuatan blog dan sampai sekarang bertambah terus. Tapi kali ini kita bahas dulu Github + Jekyll dan Forestry.

Jadi ada 5 hal yang  disiapkan:

1. **Account github.**
2. **Jekyll theme**
3. **Account forestry. ( untuk posting )**
4. **Domain**
5. **Waktu yang cukup untuk belajar.**

**Buat account github terlebih dahulu.**

* Langsung aja ke

      https://github.com/join?source=header-home

Isi data sampai kelar dan konfirmasi email.

* Kemudian kita cari theme Jekyll yang gratis.

Kita bisa langsung forking theme tersebut melalui github.

_Caranya gampang :_

Saya kasih theme bagus dan gratis untuk kita fork nantinya.

* Cari theme gratis Jekyll , saya kasih contoh satu.

      https://github.com/wowthemesnet/mundana-theme-jekyll

**Forking dibagian kanan atas**

![](https://nanwinata.github.io/uploads/forking.png)

![](https://nanwinata.github.io/uploads/prosesfork.png)

* Setelah selesai fork themes tinggal di rename repository tadi menjadi repository github pages agan dibagian setting.
* ![](https://nanwinata.github.io/uploads/githubpages.png)

      https://github.com/[usernameagan]/mundana-theme-jekyll/settings 

Seperti gambar di atas

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

* _Langsung saja kesini_

      https://app.forestry.io/signup

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
* Jika prosesnya benar maka otomatis pembuatan blognya selesai.

Lalu yang terakhir tinggal buka github pages agan yang udah dibuat tadi

    https://usernameagan.github.io

Github pagesnya juga bisa di add domain atau subdomain.

Dibagian github setting seperti gambar dibawah ini.

![](https://nanwinata.github.io/uploads/adddomain.png)

Cara posting di [**forestry**](https://nanwinata.me/cara-posting-dengan-forestry/ "Cara posting dengan forestry") akan dibahas di postingan saya selanjutnya berikut template postingnya.

Terima kasih sudah berkunjung, happy blogging.