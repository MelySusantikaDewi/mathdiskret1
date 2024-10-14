---
title: Aljabar Boolean Logika

---

### Aljabar Boolean dan Gerbang Logika
* Aljabar Boolean adalah sistem matematika untuk manipulasi variabel yang dapat memiliki salah satu dari dua nilai.  
1.Dalam logika formal, nilai-nilai ini adalah "benar" dan "salah."  
2.Dalam sistem digital, nilai-nilai ini adalah "nyala" dan "mati," 1 dan 0, atau "tinggi" dan "rendah."  
* Ekspresi Boolean dibuat dengan melakukan operasi pada variabel Boolean.  
* Operator Boolean yang umum termasuk AND (AND), (OR), dan (NOT).


* #### Operator Biner:
Aljabar Boolean memiliki dua operator biner:
Penjumlahan (+): Digunakan untuk operasi disjungsi (OR).
Perkalian (⋅): Digunakan untuk operasi konjungsi (AND).

* #### Operator Uner:
Komplemen (’): Digunakan untuk menghasilkan nilai yang berlawanan dari suatu elemen. Misalnya, jika a = 1, maka a’ = 0, dan sebaliknya.

### Manfaat Dalam Pemrograman 
Aljabar Boolean sering digunakan dalam pemrograman untuk mengevaluasi ekspresi logika.

* ### Aksioma-Aksioma:
Untuk setiap a, b, c ∈ B, berlaku aksioma-aksioma berikut:
Closure: a + b ∈ B dan a ⋅ b ∈ B.
Identitas: a + 0 = a dan a ⋅ 1 = a.
Komutatif: a + b = b + a dan a ⋅ b = b ⋅ a.
Distributif: a ⋅ (b + c) = (a ⋅ b) + (a ⋅ c) dan a + (b ⋅ c) = (a + b) ⋅ (a + c).
Komplemen: Untuk setiap a ∈ B, terdapat elemen unik a’ ∈ B sehingga a + a’ = 1 dan a ⋅ a’ = 0

#### Aljabar Boolean
Sebuah operator Boolean dapat dijelaskan sepenuhnya menggunakan tabel kebenaran.Tabel kebenaran untuk operator Boolean D (AND) dan (OR) ditunjukkan di sebelah kanan.Operator AND  juga dikenal sebagai produk Boolean. Operator OR adalah jumlah Boolean.


#### X AND Y
|  X  | Y | XY |
| -------- | -------- | -------- |
| 0 | 0   | 0  |
| 0 | 1   | 0  |
| 1 | 0   | 0  |
| 1 | 1   | 1  |

#### X OR Y
|  X  | Y | XY |
| -------- | -------- | -------- |
| 0 | 0   | 0  |
| 0 | 1   | 1  |
| 1 | 0   | 1  |
| 1 | 1   | 1  |

#### Boolean Algebra
* Tabel kebenaran untuk operator Boolean (NOT) ditunjukkan di sebelah kanan.  
* Operasi NOT paling sering dilambangkan dengan garis atas. 

|Identity Name| AND Form | OR From |
| -------- | -------- | -------- |
| Identity Law | $1x=1$ | $0+x=x$ |
| Null Law | $0x=0$ | $1+x=1$ |
| Idempotent Law | $xx=x$ | $x+x=x$ |
| Inverse Law | $x\overline{\rm x }=0$ | $x+\overline{\rm x }=1$  |
| Commutative Law | $xy=yx$ | $x+y=y+x$ |
| Associative Law | $(xy)z=x(yz)$ | $(x+y)+=x+(y+z)$ |    
| Distributive Law | $x+yz=(x+y) (x+z)$ | $x(y+z)=xy+xz$ |
| Absorption Law | $x(x+y)=x$ | $x+xy=x$ |
| Text     | $\overline{\rm (xy) }=\overline{\rm x }+\overline{\rm y }$ | $\overline{\rm (x+y) }=\overline{\rm x }\overline{\rm y }$ |
| Double Complement Law    | $\overline{\rm (\overline{\rm x }) }=x$ | $\overline{\rm (\overline{\rm x }) }=x$  |

#### Logic Gates
Fungsi Boolean diimplementasikan dalam sirkuit komputer digital yang disebut gerbang (gates).  Gerbang adalah perangkat elektronik yang menghasilkan hasil berdasarkan dua atau lebih nilai input.  
Dalam kenyataannya, gerbang terdiri dari satu hingga enam transistor, tetapi desainer digital menganggapnya sebagai satu kesatuan.  
Sirkuit terintegrasi mengandung kumpulan gerbang yang sesuai untuk tujuan tertentu.
##### Tiga gerbang AND, OR, dan  NOT.
![Screenshot 2024-10-14 080812](https://hackmd.io/_uploads/Hyp7Jl5ykl.png)

##### NAND dan NOR 
dikenal dengan gerbang universal  karena mereka murah untuk diproduksi dan setiap fungsi Boolean dapat dibangun menggunakan gerbang ini. NAND atau hanya gerbang NOR .  
![Screenshot (1)](https://hackmd.io/_uploads/SJlzglcJyx.png)








