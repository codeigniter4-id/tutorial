---
layout: post
title: "Menginstall Codeigniter4 melalui Composer"
date: 2020-02-02 22:08:07 +0800
categories: umum
tags: codeigniter framework instalasi
author: Firdaus Siregar
comments: 1
---
Codeigniter 4 memungkinkan Anda untuk melakukan instalasi melalui composer.

Composer merupakan Dependency Manager untuk PHP, sama halnya dengan NPM pada node.js.

Untuk dapat melakukan instalasi codeigniter 4 menggunakan composer, Anda harus menginstal composer terlebih dahulu di computer Anda.

Jika Anda menggunakan windows, Anda dapat mendownload Composer-Setup.exe pada link berikut:

https://getcomposer.org/download/


Jika Anda menggunakan Linux/Unix/macOS, cek link berikut untuk info lebih lengkap:


https://getcomposer.org/doc/00-intro.md



Untuk memastikan apakah composer telah terinstal dengan baik di computer Anda, silahkan buka Terminal / Command Prompt dan ketikan perintah berikut

<br/>
{% highlight shell linenos %}
composer -v

{% endhighlight %}

<br/>Untuk menginstal CI 4 dengan composer, silahkan ketik perintah berikut.
<br/>
{% highlight shell linenos %}
composer create-project codeigniter4/appstarter ci-news -vvv

{% endhighlight %}
Tungulah sampai prosesnya selesai.

Ada beberapa argumen yang kita berikan pada perintah ini:

<li><b>create-project</b> adalah perintah untuk membuat proyek baru dengan composer</li>
<li><b>codeigniter4/appstarter</b> adalah file CI yang akan di-download</li>
<li><b>ci-news</b> adalah nama proyek yang akan kita buat</li>
<li><b>-vvv</b> berfungsi untuk melihat proses install lebih detail</li>
Setelah prosesnya selesai, kita akan mendapatkan folder baru dengan nama ci-news</>

buka folder ci-news dengan teks editor VS Code.

Setelah itu buka terminal dengan menekan <kbd>Ctrl</kbd>+<kbd>`</kbd> dan jalankan perintah:
<br/>
{% highlight shell linenos %}

composer install -vvv

{% endhighlight %}

Perintah ini akan menginstal semua library yang dibutuhkan CI 4.
Setelah selesai, coba ketik perintah:

<br/>
{% highlight shell linenos %}
php spark serve

{% endhighlight %}
Perintah ini akan menjalankan server CI 4 pada port 8080.
Coba buka web browser dan arahkan ke alamat http://localhost:8080,
CI 4 sudah berhasil diinstal.
