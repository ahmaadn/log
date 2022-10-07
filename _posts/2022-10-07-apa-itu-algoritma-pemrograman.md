---
layout: distill_post
title: Apa Itu Algoritma Pemrograman
date: 2022-10-07 00:00:00
description: Mengenal lebih jauh tentang Algorima dan Pemograman
comments: false
categories: Pemrograman
tags: Algoritma, Pemrograman

toc:
  - name: Pengertian
  - name: Fungsi
  - name: Notasi Algotitma
    subsections:
      - name: Desktiptif
      - name: Flowchart
      - name: PseudoCode
---

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/posts/post-1_0.webp" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

## Pengertian
Algorima adalah urutan langkah-langkah logis peyelesaian masalah yang disusun secara sistematis dan logis serta dapat ditentukan bernilai salah atau benar.

Pemrograman adalah proses menulis, menguji dan memperbaiki (debug), dan memelihara kode yang membangun suatu program komputer `(KBBI)`.

Dengan kata lain, Algoritma pemrograman adalah adalah serangkaian proses yang wajib diikuti dalam suatu perhitungan pemecahan masalah yang lain, terutama pada program komputer. 

Untuk melakukan pemrograman memerlukan keterampilan algoritma, logika, pengetahuan seperti matematika , dan bahasa pemrograman.
<div class="profile rounded mx-auto d-block">
    {% include figure.html path="assets/img/posts/post-1_2.webp" class="img-fluid rounded z-depth-1 float-right" %}
</div>
<div class="caption">
    Penemu Aljabar dan algoritma Muḥammad bin Mūsā al-Khawārizmī.
</div>

## Fungsi
Pada dasarnya fungsi dari algoritma adalah untuk membantu memecahkan suatu masalah. Suatu algoritma pemrograman membawa keuntungan serta fungsi penting dalam aktivitas pembuatan program. Berikit ini fungsi dari algoritma pemrograman yaitu:
1. Algoritma dapat membantu menyederhanakan suatu program yang rumit.
2. Penggunaan Algoritma lebih efektif dan efisien.
3. Memiliki alur yang jelas yang dimiliki algoritma, sehingga dapat meminimalisir kesalahan dan mudah mencari kesalahan pada program.
4. Dapat digunakan secara berulang untuk meminimalkan penulisan program yang berulang.

## Notasi Algotitma
Notasi algoritma adalah suatu notasi yang digunakan untuk menuliskan langkah-langkah dalam pembuatan suatu program menggunakan bahasa pemrograman.

Notasi algoritma tidak dituliskan dalam bahasa pemrograman tetapi notasi ini dapat diterjemahkan kedalam berbagai bahasa pemrograman. penotasian ini harus dilakukan sedemikain hingga mudah dibaca dam dimengerti.

Secara umum terdapat tiga cara dalam menuliskan algoritma yaitu sebagai berikut:
1. [Desktiptif](#desktiptif)
2. [flowchart](#flowchart)
3. [PseudoCode](#pseudocode)

### Desktiptif
Uraian deskriptif adalah suatu penjabaran masalah dengan uraian bahasa sehari-hari.
Contoh Algoritma `menghitung Volume Kerucut` dengan notasi Desktiptif:
1. Mulai
2. Tentukan nilai konstanta phi = 3.14
3. Masukan nilai r (jari-jari)
4. Masukan nilai t (tinggi)
5. Hitung rumus volume kerucut dengan rumus `V = 1/3 * phi * r * r * t`
6. Tampilkan hasil volume
7. Selesai

### Flowchart
Flowchart adalah jenis notasi algoritma dengan menggunakan grafis atau diagram alir untuk menampilkan langkah-langkah algoritma dalam suatu program.
Flowchart tidak cocok untuk masalah yang rumut kerena tidak efisien dalam penggunaannya dan flowchart membutuhkan keterampilan menggambar yang baik sehingga penulisan algoritma dengan cara ini sering kali penyelesaiannya memerlukan waktu.
Contoh Algoritma `menghitung luas permukaan bola` dengan flowchart:
<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/posts/post-1_1.webp" class="img-fluid rounded z-depth-1 float-left w-50" %}
    </div>
</div>

### PseudoCode
PseudoCode adalah kode (Pseudo) program atau struktur bahasa yang hampir mendekati bahasa pemograman sehingga mudah ditranslasikan kedalam bahasa pemrograman.
Contoh penulusan PseudoCode.<br>

**Program** rumus_percepatan<br>
{program untuk menghitung rumus percepatan} <br>
**Kamus** (Deklarasi Algoritma) <br>
kecepatan, waktu, percepatan : Integer <br>
**Algoritma**<br>
INPUT(kecepatan, waktu) &nbsp;&nbsp;&nbsp;&nbsp; {Inputan untuk mengisi variable kecepatan dan waktu}<br>
SET percepatan = kecepatan / waktu &nbsp;&nbsp;&nbsp;&nbsp; {Memasukan hasil Operasi kali panjang dan lebar}<br>
OUTPUT(percepatan) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; {Menampilkan luas hasil kali panjang dan lebar}<br>