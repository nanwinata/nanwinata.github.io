---
layout: post
title: Cara install app dengan Brew cask di Terminal
author: admin
categories:
- IT
- Tutorial
tags:
- Tutorial
- Brew
- IT
- MacOsX
image: https://nanwinata.github.io/uploads/Screen Shot 2020-03-06 at 15.44.09.png
description: ''
featured: true
hidden: false
rating: 5

---
Sesudah kita kemaren menginstall  Brew cask di terminal MacOsX kita. Sekarang kita mencoba menginstall applikasi yang pengen atau dibutuhkan.

Sebenarnya simple karena seperti App store akan terdownload otomatis dan commandnya sangat membantu untuk install, uinstall bahkan update.

Kita ambil satu contoh aja untuk install VLC

Disini saya sendiri menggunakan OSx Catalina

Jalankan command searching :

    Brew search vlc

Setelah keluar nama packagenya, kemudian kita jalankan command install:

    Brew cask install vlc

Tunggu sampai installnya selesai.

Kalau sudah selesai maka akan keluar "🍺  vlc was successfully installed!"
Bisa di check yang sudah terinstall di Launchpad.

Untuk uninstall sangat gampang, cukup dengan command:

    brew cask uninstall vlc

==> Uninstalling Cask vlc
==> Backing App 'VLC.app' up to '/usr/local/Caskroom/vlc/3.0.8/VLC.app'.
==> Removing App '/Applications/VLC.app'.
==> Unlinking Binary '/usr/local/bin/vlc'.
==> Purging files for version 3.0.8 of Cask vlc

simple bukan?

Terlebih kurang begitu deh, saya tambahkan beberapa list.

    https://nanwinata.me/brew.txt