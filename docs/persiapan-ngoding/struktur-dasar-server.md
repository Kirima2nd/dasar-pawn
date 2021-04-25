---
title: Struktur dasar Server
parent: Persiapan Ngoding
has_children: false
nav_order: 2
permalink: /docs/persiapan-ngoding/struktur-dasar-server
---

# Struktur Dasar Server

Struktur yang dimagsud adalah list tree dari isian .zip atau .tar.gz yang sudah kalian extract ke `Desktop` itu, jadi disini kita akan membahas (ga) semua tentang isi dari
SA:MP Server itu sendiri.

# Directory Tree SA:MP Server

Jadi, didalam folder SA:MP Server terdapat beberapa bahan yang ketika kalian telusuri maka akan mendapati file dan directory seperti berikut:

```
├───filterscripts
|   ├───a51_base.amx
|   ├───...
|   └───vspawner.amx
|
├───gamemodes
|   ├───bare.amx
|   ├───...
|   └───timertest.amx
├───include
├───npcmodes
│   └───recordings
├───pawno
│   └───include
│───scriptfiles
│   ├───properties
│   └───vehicles
|
|───announce.exe
|───samp-license.txt
|───samp-npc.exe
|───samp-server.exe
|───server.cfg
└───server-readme.txt
```

Lalu kita harus fokus yang mana. Kalian mesti fokus ke `gamemodes`, `server.cfg`, `samp-server.exe` dan `pawno`. Loh Loh Loh kok harus kesana? iya karena kita cuma mau pake
samp-server untuk menjalanka skrip pawn doang, jadi yang lain itu ga berguna (Untuk belajar biasa yang tidak memerlukan storing data/addons tambahan).

Jadi folder `gamemodes` adalah folder dimana nanti "Mode Game" kalian akan ditaruh disana, dan ditempat itu kalian dapat membuat apa saja yang kalian mau tapi sayangnya
ada limitnya coy, gabisa sembarangan :( untuk melihat limit tersebut silahkan lihat referensi di paling bawah docs.

Folder `scriptfiles` sama seperti folder `gamemode` namun dia hanyalah "Add-ons" saja, atau pelengkap gamemode. Misalkan kalian punya skrip terbang yang ga ada di gamemode
tapi ada di filterscript, nah untuk menjalankannya kan kita haurs meload si filterscript ini, makanya disebut sebagai Add-ons.

Tapi kadang juga ambigu dengan yang di `pawno/include`, tapi tenang. Yang `pawno/include` hanya tambahan biasa sementara filterscript itu lebih condong ke gamemodes namun beda.

Disini kita akan fokus untuk membicarakan file `server.cfg` karena ini penting sekali, jadi langsung aja tinggal kebawah ya.
