---
layout: post
title: "membuat index.html dan jekyll serve"
---

membuat index.html dan jekyll serve

2025 maret 07
-membuat index.html dan jekyll serve

# menjalankan jekyll serve

- setelah membuat sebuah respository dengan nama sendiri
- clone respository tersebut ke local
  kemudian masuk ke dalam folder respository tersebut dan install melalui terminal visual studio code dengan perintah berikut:
    * gem install jekyll bundler
    * bundler unit
- kemudian masuk ke folder gemfile yang muncul dan tambahkan
    * gem "jekyll" di baris baru
- tambahkan file baru dengan nama index.html dan isi dengan kode berikut <!DOCTYPE html>

 Hello World

 - lalu ketik "jekyll build" di terminal agar menghasilkan directory_site
 - dan jalankan "jekyll serve" dan klik url https://localhost : 4000 yang muncul.
 - jika websudah berhasil dibuka,edit gemfile.lock dan tambahkan "x86_64-linux" pada bagian "platfroms"
 - dan ketik perintah berikut untuk push ke respository github:
    * git add .
    * git commit -m "pub: first publish"
    * git push