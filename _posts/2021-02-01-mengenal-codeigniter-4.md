---
layout: post
title: "Apa itu framework codeigniter4"
date: 2020-02-01 21:08:07 +0800
categories: umum
tags: codeigniter, framework
author: Firdaus Siregar
comments: 1
---

Codeigniter merupakan framework PHP untuk membangun aplikasi berbasis web.
Berkat perkembangan teknologi yang cepat, Codeigniter dipaksa melakukan perubahan besar-besaran.

Codeigniter 4 mendukung PHP versi 7.2+, jika web server Anda belum support PHP 7.2+, saya sarankan untuk mengupgrade versi PHP Anda.

Selain itu, Codeigniter 4 juga tidak dapat dijalankan jika web server Anda tidak mengaktifkan intl extention, php-json, php-mbstring, php-mysqlnd, dan php-xml.
Anda dapat mengeceknya di phpinfo, jika salah satu extention tersebut tidak aktif (disabled), silahkan aktifkan pada file php.ini.
Jika Anda menggunakan XAMPP, file php.ini terdapat pada folder:

C:/xampp/php

Sedangkan jika Anda menggunakan WampServer, file php.ini terdapat pada folder:

C:/wamp64/bin/php/php7.4.3

Selain itu, Codeigniter 4 tidak memiliki file “index.php” pada root project, dan file “index.php” dipindahkan ke folder “public” dengan alasan keamanan.


Codeigniter 4 memudahkan web developer dengan penulisan kode program yang lebih singkat dan memberikan kemudahan dalam melacak error melalui mode “development”.

Tidak hanya itu, Codeigniter 4 juga memudahkan web developer untuk membuat RESTful API, 
