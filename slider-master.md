# Slider Master

## Overview

Slide Master adalah game Puzzle Slide dimana gerakan karakter berupa Slide horizontal ataupun vertikal dari satu sisi ke sisi lain&#x20;

## Target Audience

Game ini ditargetkan untuk Player casual yang menyukai game bergenre Puzzle Slider. Game ini juga cocok dimainkan bareng keluarga karena walaupun bersifat kompetitif, mekanisme dan kontrol dari Game ini sangat mudah untuk dipelajari

## Detail

* Genre: 2D, Puzzle, Slider
* Jumlah Player: 2 \~ 4 Orang
* Game Design Pillar: Challenge, Competition, Fantasy

## Art Reference



## Core Mechanic

1. Sliding Movement
   1. Player dapat bergerak secara Vertikal dan Horizontal dari satu sisi ke sisi lain.
   2. Pergerakan akan menggunakan tombol D - pad (Atas, Bawah, Kiri, Kanan).
2. Item Spawn
   1. Item akan spawn pada lokasi secara random di Map
3. Collecting Item
   1. Player dapat mengumpulkan Item yang spawn di Map dengan cara menabrak Item tersebut.
   2. Item yang dikumpulkan akan masuk ke dalam Inventory pemain
4. Inventory
   1. Setiap Player akan memiliki Inventory untuk menampung Item yang dikumpulkan.
   2. Jika Inventory penuh maka Item lain yang dilewati akan diabaikan&#x20;
5. Collect Area
   1. Digambarkan sebagai kotak merah pada Diagram.
   2. Jika Player memasuki Collect Area maka:
      1. \[Mode Classic] Semua Item diambil dari Inventory Player, Player mendapat Poin sebanyak Item yang diambil dan Player akan teleport ke Spawn Point&#x20;
      2. \[Mode Kitchen Madness] Item yang sesuai permintaan akan diambil dari Inventory Player, Player mendapat Poin berdasarkan Item yang diambil dan Player akan teleport ke Spawn Point.
6. Cliff / Remove Area
   1. Digambarkan sebagai kotak abu-abu pada Diagram.
   2. Jika Player memasuki Remove Area maka Item yang berada di Inventory Player akan hilang dan Player teleport ke Spawn Point.
   3. Player tidak mendapat Poin dari Item yang&#x20;

## Storyboard

<figure><img src=".gitbook/assets/image (23).png" alt=""><figcaption><p>TV Screen Mockup (Max Example)</p></figcaption></figure>

<figure><img src=".gitbook/assets/image (24).png" alt=""><figcaption><p>Controller Mockup</p></figcaption></figure>

#### Game Flow Example: Classic Mode

<figure><img src=".gitbook/assets/image (28).png" alt=""><figcaption><p>Player spawn di Spawn Point</p></figcaption></figure>

<figure><img src=".gitbook/assets/image (29).png" alt=""><figcaption><p>[Kiri] Player bergerak secara Horizontal<br>[Kanan] Player bergerak secara Vertikal</p></figcaption></figure>

<figure><img src=".gitbook/assets/image (30).png" alt=""><figcaption><p>[Kiri] Player masuk ke Jurang, Item Hilang dan balik ke Spawn.<br>[Kanan] Player masuk ke Collect Area, Item diambil, poin bertambah dan balik ke Spawn.</p></figcaption></figure>

