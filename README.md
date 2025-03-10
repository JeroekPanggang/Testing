# 🫧 Bubble Popper

## Overview

Bubble Popper adalah game Puzzle Match 3 dengan mekanisme menembak, dimana Player akan menembakkan Bubble ke arah gerombolan Bubble lainnya

## Target Audience

Game ini ditargetkan untuk Keluarga dan Player yang menyukai game yang mirip seperti Bubble Shooter. Beragam game mode mulai dari yang kompetitif dan mode party, hingga mode Co-op membuat game ini bisa dinikmati bersama keluarga maupun teman.

## Detail

* Genre: Puzzle, Arcade, Party Game,&#x20;
* Jumlah Player: 2 \~ 4 Orang
* Game Design Pillar: Challenge, Competition, Fellowship \[Mode Co-op]

## Core Mechanic

1. Shooting Bubble
   1. Player menembak Bubble dari karakter di bawah layar ke kumpulan bubble di atas.
   2. Bubble bergerak lurus dan memantul saat mengenai dinding.
   3. Tekan tombol Tembak untuk menembakkan Bubble.
2. Aiming&#x20;
   1. Tahan tombol Tembak untuk membidik, lepaskan untuk menembakkan bubble.
   2. Gunakan tombol Kiri/Kanan untuk mengarahkan bidikan.
   3. Saat membidik, Player tidak bisa bergerak hingga bubble ditembakkan.
3. Bubble Swap
   1. Player dapat menampung 2 bubble: 1 untuk ditembakkan dan 1 disimpan.
   2. Setelah bubble ditembakkan, bubble cadangan otomatis berpindah ke slot tembak.
   3. Player dapat menukar bubble yang akan ditembakkan dengan bubble di slot simpan kapan saja.
   4. Setelah menembakkan bubble, player akan langsung me-reload bubble dengan warna acak.
4. Matching Bubble
   1. Player harus mencocokkan 3 atau lebih bubble dengan warna yang sama untuk meletuskannya.
   2. Semakin banyak bubble yang diletuskan, semakin besar skor yang didapatkan.
5. Bubble Pop
   1. Saat 3 atau lebih bubble dengan warna yang sama dicocokkan, bubble tersebut akan meletus.
   2. Bubble dengan warna sama yang terhubung langsung akan ikut meletus.
   3. Bubble dengan warna berbeda yang hanya menempel pada bubble yang meletus juga akan ikut meletus.
6. Bubble Spawn Mechanic
   1. Bubble muncul dari atas layar secara berkala, mendorong bubble lama ke bawah.
   2. Jika bubble menyentuh batas bawah layar, pemain akan kalah.
7. **Mekanisme Khusus:**&#x20;
   1. **Co-op Mode**
      1. \[Role Management] Setiap Player memiliki warna khusus, Bubble yang direload akan memiliki probabilitas lebih tinggi untuk muncul dengan warna yang sama dengan Player.
      2. \[Movement Mechanic] Karakter dapat bergerak ke kanan dan ke kiri. Tetapi, karakter akan diam ketika sedang Aiming.
      3. \[Event Management] Terdapat sebuah bar yang berada di layar bagian atas. Setelah bar terisi penuh maka akan terjadi salah satu Event berikut yang dipilih secara random:
         * **Color Change:** Warna pada Player akan diacak, membuat probabilitas warna Bubble yang muncul lebih sering menjadi berbeda / berubah.
         * **Spawn Spree:** Bubble akan muncul secara cepat dalam waktu yang singkat
         * **Bubble Flip:** Memputar balikkan posisi Bubble yang berada di atas layar&#x20;
   2. **Vs. Black Bubble Hunt**
      1. \[Black Bubble Mechanic] Akan muncul Bubble utama berwarna **Hitam** di tengah. Jika Player mengenai **Bubble Hitam**, maka Player akan memperoleh Poin besar dan semua Bubble akan meletus.
      2. \[Black Bubble Respawn] Setelah **Bubble Hitam** meletus, maka akan ada jeda beberapa waktu, kemudian Bubble Hitam baru akan muncul.
      3. \[Black Bubble Pity System] Bubble Hitam memiliki kecenderungan untuk spawn dengan posisi lebih mendekati Player dengan score terendah. Memudahkan mereka untuk meletuskan dan mengejar ketertinggalan.
      4. \[Bubble Spawn] Bubble akan spawn mengitari Bubble Hitam. Diawal Bubble Hitam Spawn, akan ada setidaknya 2 lapis Bubble yang melapisi **Bubble Hitam**
   3. **Classic Vs.**&#x20;
      1. \[Bubble Spawn] Saat pemain mengumpulkan poin tertentu, Bubble di layar lawan akan muncul lebih cepat untuk sementara waktu.

## Storyboard

<figure><img src=".gitbook/assets/image (1) (1) (1).png" alt=""><figcaption><p>TV Mockup - Classic Vs.</p></figcaption></figure>

<figure><img src=".gitbook/assets/image (2) (1).png" alt=""><figcaption><p>TV Mockup - Vs. Black Bubble Hunt</p></figcaption></figure>

<figure><img src=".gitbook/assets/image (1) (1) (1) (1) (1).png" alt=""><figcaption><p>TV Mockup - Coop Mode</p></figcaption></figure>

<figure><img src=".gitbook/assets/image (4).png" alt=""><figcaption><p>Phone Mockup Controller</p></figcaption></figure>

