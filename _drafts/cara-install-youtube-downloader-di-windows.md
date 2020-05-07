---
layout: post
title: Cara install Youtube Downloader di windows
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
Langsung aja, untuk yang menggunakan windows dapat menginstall Cygwin dulu.

Cygwin dapat di download di :

    https://cygwin.com/install.html

setelah ter-install lalu selanjutnya kita install youtube-dl, masuk ke terminal cygwin :

di asumsikan directory cygwin sekarang di c:\\cygwin , lalu buat folder baru khusus menyimpan file video yang udah di download.

    cygwin$ mkdir youtube
    cygwin$ cd youtube
    cygwin/youtute$ sudo curl -L https://yt-dl.org/downloads/latest/youtube-dl -o /usr/local/bin/youtube-dl
    cygwin/youtube$ sudo chmod a+rx /usr/local/bin/youtube-dl