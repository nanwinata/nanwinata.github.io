---
layout: post
title: Cara colouring terminal di Mac Os X
author: admin
categories:
- zsh
- macosx
- Dev
- Git
- IT
- tutorial
image: ''
featured: false
hidden: false
tags: []
description: ''
rating: 

---
Ketika Terminal default di Mac Os terlihat membosankan, buram maka membuat terminal itu lebih berwarna adalah jalan keluarnya.

Ada 4 hal penting :

1. Menginstall Homebrew
2. Menginstall iTerm2
3. Menginstall ZSH dan Oh My ZSH
4. Setting themes.

* Menginstall Homebrew.

  Homebrew adalah free open-source yang mempermudah menginstall software di mac os.

  Sebelum menginstall homebrew kita membutuhkan CLI tools buat Xcode.

  Buka Terminal lalu jalankan command :

      xcode-select —-install

  Tunggu sampai selesai installasinya dan bila ada error jalankan command:

      xcode-select -r to reset xcode-select.

  Lalu install Homebrew :

      /usr/bin/ruby -e "$(curl -fsSLhttps://raw.githubusercontent.com/Homebrew/install/master/install)"

Install iTerm2

iTerm2 adalah pengganti default terminal yang sangat di rekomendasikan oleh engineers. Cara installnya sangat gampang, buka terminal lalu ketik command :

    brew cask install iterm2

Selanjutnya, Install ZSH di iTerm2

    brew install zsh

Untuk mendukung ZSH kita perlu Oh My ZSH untuk configurasi ZSH. Oh My ZSH running di ZSH yang confignya berada di \~/.zshrc , ini adalah config filenya.

Command :

    sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

lalu check installasi zshnya dengan command:

    zsh --version

Kalau masih menggunakan versi lama, maka kita bisa mengupdate dengan command:

    upgrade_oh_my_zsh

Lalu tutup iTerm2 dan jalankan kembali, voila!

Hal yang paling menyenangkan sebenarnya dibagian ini, yaitu ganti-ganti THEME untuk Oh My ZSH dan pilih mana yang disuka. Caranya :

Masuk ke dalam iTerm2 kembali lalu jalankan command:

    nano ~/.zshrc

Carilah line atau baris **ZSH_THEME**

Setelah di ganti dengan tema theme yang disukai lalu jalankan command

    source ~/.zhrc

Untuk tema themenya silahkan pilih sendiri di website Oh My ZSH, ini listnya

    https://github.com/ohmyzsh/ohmyzsh/wiki/Themes

Ingat , yang diganti cuma bagian theme aja di config file \~/.zhrc

Kalau langkahnya benar maka iTerm2 atau terminalnya akan kelihatan berwarna.

Happy Coding.