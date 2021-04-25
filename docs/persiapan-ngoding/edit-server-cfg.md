---
title: Mengedit server.cfg
parent: Persiapan Ngoding
has_children: false
nav_order: 3
permalink: /docs/persiapan-ngoding/edit-server-cfg
---


# Mengedit server.cfg

Ketika kalian sudah mengeksraksi SA:MP server yang sudah kalian download, kini saatnya tinggal di buka file nya lalu kemudian silahkan lu pada edit server.cfg biar supaya nanti
bisa digunakan ketika saat pembelajaran berlangsung. Karena kalau tidak demikian maka nanti akan menimbulkan masalah seperti:

### Masalah Pertama | Default RCON Password

Apa itu Default RCON Password, itu adalah sebuah password untuk administrator server yang bisa disebut sebagai RCON, jadi Default RCON Password itu ya password bawaan dari SA:MP
yang wajib perlu diganti, ketika itu tidak diganti maka dia akan memunculkan masalah ketika menajalankan aplikasi samp-server.exe seperti:

```
----------
Loaded log file: "server_log.txt".
----------

SA-MP Dedicated Server
----------------------
v0.3.7-R2, (C)2005-2015 SA-MP Team

[xx:xx:xx] Error: Your password must be changed from the default password, please change it.

```

## Masalah Kedua | Grandlarc

Kita semua SA:MPers veteran tau kalau menggunakan Grandlarc untuk sebagai pembelajaran itu sangatlah tidak dianjurkan bahkan menyesatkan, karena sistemnya yang kompleks bagi
para pemula yang ingin belajar tentang bagaimana bisa mendevelop skrip mereka pertama kali. Makanya ini yang harus diganti biar nantinya dapat belajar dengan enak tanpa
perlu pusing dengan beberapa hal yang rumit xd

# Mengatasi masalah diatas

Lalu ketika sudah ditampakkan masalah-masalah diatas, cara biar ga error gimana?

Gampang, kalau untuk solusi masalah pertama tinggal diganti aja rcon_password di server.cfg menjadi sesuka kalian, asalkan aman dan juga tidak ada yang tahu karena ketika
orang tahu password RCON mu itu bisa membawa bencana bagi kalian sang pemilik server untuk di rusuhi sama si lamer ga tau diri dan akhirnya mereka bisa membuat server
kalian down terus menerus.

Untuk solusi yang kedua, silahkan kalian ganti dengan `bare`, loh kenapa `bare`? karena itu adalah sebuah gamemode paling *PEREFECT* bagi para pemula yang ingin belajar
tentang dasar membuat sebuah gamemode dengan basis bare atau bahkan melakukan experimen dengan gamemode itu.

Lalu bagaimana dengan mengganti sekalin bare? bisa kok. Mau blank script juga boleh boleh aja. Tinggal buat file dengan extensi `.pwn` (**CONTOH:** `namafile.pwn`) lalu kalian
mulai deh untuk liat liat document ini.

Simpel kan? jadi ketika semuanya sudah siap silahkan lanjut ke document berikutnya!
