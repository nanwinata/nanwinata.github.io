---
layout: post
title: Cara install Git di Mac OS X
author: admin
categories:
- IT
- tutorial
image: https://nanwinata.github.io/uploads/7A9DAA55-3654-4E70-83A3-206764081B2C.png
featured: true
hidden: false

---
Ada beberapa cara untuk menginstall Git di Mac OS X, tapi jika di Mac Os X terminal kamu sudah terinstall XCode maka Git sudah terinstall dengan sendirinya. Untuk mencari tau apakah itu sudah terinstall, jalankan

$ git --version

Jika sudah maka akan keluar "git version 2.7.0 ( Apple Git-66)"

Installer Git untuk Mac :

1. Download Git terbaru di [https://sourceforge.net/projects/git-osx-installer/files/](https://sourceforge.net/projects/git-osx-installer/files/ "https://sourceforge.net/projects/git-osx-installer/files/")
2. Ikuti langkah sampai selesai.
3. Setelah selesai menginstall buka Terminal atau iTerm yang ada di Mac dan verify dulu apakah sudah terinstall :

       ╭─NAN@Milan.local ~

       ╰─➤ git --version

       git version 2.21.1 (Apple Git-122.3)
4. Lalu lakukan Git configurasi :

       ╰─➤ git config --global user.name "nan winata"

       ╭─NAN@Milan.local ~

       ╰─➤ git config --global user.email "nanwinata@gmail.com"

Selesai.