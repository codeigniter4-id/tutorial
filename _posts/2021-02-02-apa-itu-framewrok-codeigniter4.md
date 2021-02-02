---
layout: post
title: "Apa itu framework codeigniter4"
date: 2020-02-02 22:08:07 +0800
categories: umum
tags: codeigniter, framework
author: Firdaus Siregar
comments: 1
---
Framework dalam bahasa indonesia artinya kerangka kerja.
Saya yakin,
kamu yang sedang membaca artikel ini sudah pernah membuat web dengan PHP.
Setidaknya membuat web sederhana yang berisi beberapa halaman.
Apa yang akan kamu lakukan jika webnya semakin kompleks?

Ya ditambahin lagi donk kodenya.

Tapi..
Kadang ini tidak berjalan mulus.
Kode website kita akan semakin ribet dan berantakan. Bisa jadi disbeabkan karena kita asal-asalan menambahkan kode.
Belum lagi, kita dituntut menulis kode yang rapi agar bisa dipahami orang lain (misalnya teman satu tim).
Maka di sini kita tidak boleh seenaknya menulis kode yang asal-asalan.
Karena itu, diciptakanlah framework atau kerangka kerja.
Kerangka kerja dibuat agar kita bisa bekerja lebih mudah. Biasanya, framework menyediakan bahan-bahan yang siap pakai, sehingga kita tidak harus membuatnya dari nol.
Selain itu, framework juga memiliki aturan-aturan yang harus diikuti.

Contohnya seperti:

<li>Harus menaruh kode yang memiliki fungsi yang sama dalam satu folder</li>
<li>Harus mengikuti aturan penulisan kode (writing conventions) yang disepakati</li>
<li>Harus menggunakan pola desain ini, dan itu</li>
<li>dan lain sebagainya.</li>
Jadi apa itu framework?

Framework adalah sebuah kerangka kerja yang digunakan untuk membantu developer dalam mengembangkan kode aplikasi secara konsisten.
Codeigniter4 merupakan framework PHP untuk membangun aplikasi berbasis web.

Codeigniter 4 mendukung PHP versi 7.2+, jika web server Anda belum support PHP 7.2+, saya sarankan untuk mengupgrade versi PHP Anda.

Selain itu, Codeigniter 4 juga tidak dapat dijalankan jika web server Anda tidak mengaktifkan intl extention, php-json, php-mbstring, php-mysqlnd, dan php-xml.


Anda dapat mengeceknya di phpinfo, jika salah satu extention tersebut tidak aktif (disabled), silahkan aktifkan pada file php.ini.

C:/xampp/php

Sedangkan jika Anda menggunakan WampServer, file php.ini terdapat pada folder:

C:/wamp64/bin/php/php7.4.3


Selain itu, Codeigniter 4 tidak memiliki file “index.php” pada root project, dan file “index.php” dipindahkan ke folder “public” dengan alasan keamanan.

Codeigniter 4 memudahkan web developer dengan penulisan kode program yang lebih singkat dan memberikan kemudahan dalam melacak error melalui mode “development”.


Tidak hanya itu, Codeigniter 4 juga memudahkan web developer untuk membuat RESTful API
Itulah yang membuat Codeigniter 4 menjadi semakin menarik



Jika Anda menggunakan XAMPP, file php.ini terdapat pada folder:
