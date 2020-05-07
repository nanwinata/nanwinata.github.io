---
layout: post
title: Cara install Youtube Downloader di Windows & macOS
author: admin
categories:
- tutorial
tags:
- download
- youtube
image: https://nanwinata.github.io/uploads/youtube.jpg
description: ''
featured: true
hidden: false
rating: 

---
Ada beberapa cara mendownload video dari youtube, udah banyak software-software tersedia dan juga udah banyak website youtube downloader di google.

Ada lagi cara mudah mendownload video youtube di windows menggunakan terminal aja. Langsung aja ya ..

Untuk yang menggunakan windows dapat menginstall Cygwin dulu.

Cygwin dapat di download di :

    https://cygwin.com/install.html

setelah ter-install lalu selanjutnya kita install youtube-dl, masuk ke terminal Cygwin.

di asumsikan directory cygwin sekarang di c:\\cygwin , lalu buat folder baru khusus menyimpan file video yang udah di download.

    cygwin$ mkdir youtube
    
    cygwin$ cd youtube
    
    cygwin/youtute$ sudo curl -L https://yt-dl.org/downloads/latest/youtube-dl -o /usr/local/bin/youtube-dl
    
    cygwin/youtube$ sudo chmod a+rx /usr/local/bin/youtube-dl

atau kalau di cygwinnya tidak punya command curl, bisa menggunakan command "wget"

    sudo wget https://yt-dl.org/downloads/latest/youtube-dl -O /usr/local/bin/youtube-dl

Banyak kejadian beberapa command tidak jalan karena belum terinstall atau memakai versi lama, maka daripada itu install atau upgradelah beberapa item tersebut. Penjelasannya akan langsung keluar di informasi error setelah menjalankan command tersebut.

Setelah Youtube-dl nya tersintall di Cygwin, langsung deh mencoba download youtube videonya. Di terminal cygwinnya jalankan command berikut ini.

Kita bisa langsung mendownload langsung video dari youtube tanpa format-format khusus.

* cygwin/youtube$ youtube-dl -f best [https://www.youtube.com/watch?v=bi9Y-uwxKQs](https://www.youtube.com/watch?v=bi9Y-uwxKQs "https://www.youtube.com/watch?v=bi9Y-uwxKQs")

Tapi jika ingin mendownload file yang khusus misalnya video yang kualitasnya 1080p atau 4k bisa menjalankan beberapa command ini:

* $youtube-dl -F [https://www.youtube.com/watch?v=bi9Y-uwxKQ](https://www.youtube.com/watch?v=bi9Y-uwxKQs "https://www.youtube.com/watch?v=bi9Y-uwxKQs")s

![](https://nanwinata.github.io/uploads/youtube.png)

di option itu terlihat opsi 137 untuk video 1080p , lalu dibagian audio ada opsi 140.

Maka di terminal kita jalankan command:

$ youtube-dl -f 137+140  [https://www.youtube.com/watch?v=bi9Y-uwxKQs](https://www.youtube.com/watch?v=bi9Y-uwxKQs "https://www.youtube.com/watch?v=bi9Y-uwxKQs")

Jangan kebalik ya , biasanya harus opsi video dulu baru audio.

Setelah itu tinggal di tunggu sampai downloadnya selesai.

Untuk macOS kurang lebih commandnya sama tapi nggak usah menginstall CYGWIN karena itu khusus buat windows aja. MacOS langsung menjalankan command install "youtube-dl" diatas.

Sekian.

PS: Jika ada error silahkan di comment aja dibawah ya.