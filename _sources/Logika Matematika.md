---
title: Logika Matematika

---

# Logika Matematika
Pengertian 
Logika merupakan dasar-dasar matematis suatu perangkat lunak, digunakan untuk memformalkan semantik bahasa pemrograman dan spesifikasi program, serta menguji ketepatan suatu program.
Logika matematika (mathematical logic) adalah cabang ilmu di bidang matematika yang memperdalam masalah logika, atau lebih tepatnya memperjelas logika dengan kaidah-kaidah matematika. Logika matematika sendiri juga terus berkembang, mulai dari logika proposional, logika predikat, pemrograman logika, dan sebagainya.
sumber:https://binus.ac.id/malang/2022/03/logika-informatika/


## Negasi
Kalimat negasi dalam konteks informatika adalah sebuah pernyataan yang digunakan untuk menolak atau menyangkal permintaan atau perintah yang diberikan oleh pengguna pada sistem atau aplikasi komputer.

    



| Pernyataan ( P ) | Negasi $\neg p$ |
| -------- | -------- |
| True        |    False     |
| False        |    True     |

## Konjungsi
Dalam logika informatika, konjungsi berperan sebagai kata hubung di dalam proposisi majemuk, di mana konotasi yang digunakan adalah menggunakan simbol “^” (huruf v terbalik) untuk mewakili kata hubung “dan” atau biasa disebut “AND.
sumber:https://www.geeksforgeeks.org/proposition-logic/




|  Pernyataan ( P ) |Pernyataan ( Q ) |  Konjungsi $P\wedge Q$ |
| -------- | -------- | -------- |
|  True    | True | True     |
|  True    | False| False     |
|  True    | True| True     |
|  False    | True| False     
|  False    | False| False     |


## Disjungsi
disjungsi, atau atau, adalah operator logika dalam kalkulus proposisional. Hasil dari dua proposisi juga disebut disjungsi mereka. Hasil disjungsi adalah salah jika kedua proposisinya salah; jika tidak, hasilnya adalah benar.
sumber:https://id.wikipedia.org/wiki/Logika_disjungsi#:~:text=Dalam%20logika%20dan%20bidang%20teknik%20yang%20memakainya%2C%20disjungsi%2C,kedua%20proposisinya%20salah%3B%20jika%20tidak%2C%20hasilnya%20adalah%20benar.



| Pernyataan ( P ) |Pernyataan ( Q ) | Konjungsi $P\vee Q$ |
| -------- | -------- | -------- |
| True     | True     | True     |
| True     | False     | True     |
| False     | True     | True     |
| False     | False     | False     |


## Implikasi
Implikasi Implikasi merupakan logika matematika berupa pernyataan majemuk. Implikasi menunjukkan hubungan sebab dan akibat, menggunakan konjungsi seperti “jika” dan “maka”, juga disimbolkan oleh karakter "→".
sumber:https://www.kompas.com/skola/read/2022/06/02/145036669/negasi-konjungsi-disjungsi-implikasi



| Pernyataan ( P ) | Pernyataan ( Q ) | Konjungsi $P\implies Q$
| -------- | -------- | -------- |
| True     | True     | True     |
| True     | False     | False     |
| False     | True     | True     |
| False     | False     | True     |



## Biimplikasi
Biimplikasi adalah logika matematika yang ditandai dengan penggunaan kata “jika dan hanya jika”. Implikasi ganda terjadi dalam kalimat majemuk dan diwakili oleh "↔". Bi-implikasi benar hanya jika dua pernyataan (p dan q) keduanya benar atau keduanya salah. Jika salah satu pernyataan salah, implikasi kondisional salah.
sumber:https://www.kompas.com/skola/read/2022/06/02/145036669/negasi-konjungsi-disjungsi-implikasi-dan-biimplikasi



| Pernyataan ( P ) |Pernyataan ( Q ) | Konjungsi $P\iff Q$|
| -------- | -------- | -------- |
| True    | True     | True     |
| True    | False     | False     |
| False    | True     | False     |
| False    | False     | True     |

Buatlah tabel kebenaran untuk~pernyataan berikut $$P\lor(R\to\ Q)$$

$$\begin{array}{c|c|c|c|cc}P&Q&R&\ Q&R\to\ Q&P\lor(R\to\ Q)\\\hline\text{Т}&\text{Т}&\text{Т}&\text{T}&\text{T}&\text{T}\\\text{Т}&\text{Т}&\text{F}&\text{F}&\text{F}&\text{T}\\\text{T}&\text{F}&\text{T}&\text{T}&\text{T}&\text{T}\\\text{T}&\text{F}&\text{F}&\text{F}&\text{T}&\text{T}\\\text{F}&\text{T}&\text{T}&\text{T}&\text{T}&\text{T}\\\text{F}&\text{T}&\text{F}&\text{F}&\text{F}&\text{F}\\\text{F}&\text{F}&\text{T}&\text{T}&\text{T}&\text{T}\\\text{F}&\text{F}&\text{F}&\text{F}&\text{T}&\text{T}&\text{T}\end{array}$$





