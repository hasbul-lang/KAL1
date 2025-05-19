# Persamaan Linier

## **Pengertian Persamaan Linear**
### Apa sih pengertian persamaan linier?

Persamaan Linier adalah merupakan persamaan matematika yang di dalamnya berisi konstanta dan variabel, konstanta merupakan nilai yabg sudah ditemukan dan variabel nilai yang harus dicari.Contoh : *a* x + *b* = 0

*a* dan *b* merupakn konstanta 
x merupakan variabelnya

Jika terdapat lebih dari satu persamaan linear, maka persamaan linear tersebut akan menjadi sebuah sistem.

### **Pembagian persamaan linier**
#### 1. Persamaan Linier 1 Variabel
Merupakan persamaan linier yang variabel hanya ada 1 disebut persaan linier 1 variabel.Contoh : *a* x + *b* = 0

**KETERANGAN**

*a* = Konstanta
*b* = Konstanta
x   = Variabel x
#### 2. Persamaan Linier 2 Variabel
Merupakan persamaan linier yang variabel hanya ada 2 disebut persaan linier 2 variabel.Contoh : *a* x + *b* y = 0

**KETERANGAN**

*a* = Konstanta
*b* = Konstanta
x   = Variabel x
y   = Variabel y
#### 3. Persamaan Linier 3 Variabel
Merupakan persamaan linier yang variabel hanya ada 3 disebut persaan linier 3 variabel.Contoh : *a* x + *b* y - z = 0

**KETERANGAN**

*a* = Konstanta
*b* = Konstanta
x   = Variabel x
y   = Variabel y
z   = Variabel z

### Metode Penyelesain persamaan Linier
#### 1. Metode Eliminasi Gauss/Eliminasi Gauss-Jordan
istem persamaan liniear yang terdiri atas persamaan-persamaan (1), (2) dan (3) dapat juga dinyatakan dalam bentuk matriks teraugmentasi seperti berikut

![Screenshot 2025-02-18 103827](https://hackmd.io/_uploads/HyhplY-5yg.png)

Dengan melakukan serangkaian operasi baris (Eliminasi Gauss), kita dapat menyederhanakan matriks di atas untuk menjadi matriks Eselon-baris.

![Screenshot 2025-02-18 103919](https://hackmd.io/_uploads/ryvgWFbcye.png)

Kemudian kita bisa substitusikan kembali nilai-nilai yang kita dapat untuk mencari nilai dari semua variabel. Atau, kita juga bisa meneruskan dengan serangkaian operasi baris lagi sehingga matriks di atas menjadi matriks yang Eselon-baris tereduksi (dengan menggunakan Eliminasi Gauss-Jordan).

![Screenshot 2025-02-18 104001](https://hackmd.io/_uploads/HyX7-K-5kl.png)

Dengan melakukan operasi Eliminasi Gauss-Jordan, kita mendapatkan solusi dari sistem persamaan linier di atas pada kolom terakhir: 
x = 2, y = 3, z = 4 .

#### 2. Metode Eliminasi

Metode ini bekerja dengan care mengeliminasi (menghilangkan) variabel-variabel di dalam sistem persamaan hingga hanya satu variabel yang tertinggal.

Pertama-tama, lihat persamaan-persamaan yang ada dan coba cari dua persamaan yang mempunyai koefisien yang sama (baik positif maupun negatif) untuk variabel yang sama. Misalnya, lihat persamaan (1) dan (3).Koefisien untuk y adalah 1 dan −1 untuk masing-masing persamaan. Kita dapat menjumlah kedua persamaan ini untuk menghilangkan y dan kita mendapatkan persamaan (4).

![Screenshot 2025-02-18 101749](https://hackmd.io/_uploads/rkN63OWq1l.png)

Perhatikan bahwa persamaan (4) terdiri atas variabel x dan z. Sekarang kita perlu persamaan lain yang terdiri atas variabel yang sama dengan persamaan(4).Untuk mendapatkan persamaan ini, kita akan menghilangkan y dari persamaan (1)dan (2). Dalam persamaan (1) dan (2), koefisien untuk y adalah 1 dan 3 masing-masing. Untuk menghilangkan y, kita kalikan persamaan (1) dengan 3 lalu mengurangkan persamaan (2) dari persamaan (1).

![Screenshot 2025-02-18 103003](https://hackmd.io/_uploads/r1AAA_b51x.png)

Dengan persamaan (4) dan (5), mari kita coba untuk menghilangkan z.

![Screenshot 2025-02-18 103250](https://hackmd.io/_uploads/rkkFyFW91e.png)

Dari persamaan (6) kita dapatkan x = 2. Sekarang kita bisa subtitusikan (masukkan) nilai dari x ke persamaan (4) untuk mendapatkan nilai z.

![Screenshot 2025-02-18 103434](https://hackmd.io/_uploads/H1001YW9ye.png)

Akhirnya, kita substitusikan (masukkan) nila dari x dan z ke persamaan (1) untuk mendapatkan y.

![Screenshot 2025-02-18 103559](https://hackmd.io/_uploads/SyZElKb5Jx.png)

Jadi solusi sistem persamaan linier di atas adalah x = 2, y = 3, z = 4.

#### 3. Metode Grafik
 Penyelesaian sistem persamaan linier dengan metode grafik dilakukan dengan cara menggambar garis garis atau bidang planar yang merupakan representasi dari persamaan-persamaan yang ada dalam sistem tersebut. Solusinya adalah koordinat-koordinat yang merupakan titik potong dari garis-garis ataupun bidang-bidang planar itu.

Sebagai contoh, marilah kita lihat sistem persamaan liniear dengan dua variabel berikut ini.

![Screenshot 2025-02-18 104235](https://hackmd.io/_uploads/Bkb6WKWckx.png)

Gambar kedua garis dari persamaan-persamaan di atas.![slm2vargraph](https://hackmd.io/_uploads/Hk7gzYWqke.gif)

Seperti terlihat pada grafik di atas, kedua garis itu bertemu (mempunyai titik potong) pada titik (0,3). Ini adalah solusi dari sistem persamaan linier tersebut, yaitu x = 0, y = 3.

Untuk persamaan linier dengan tiga variabel, solusinya adalah titik pertemuan dari tiga bidang planar dari masing-masing persamaan.

## Penyelesaian Soal Persamaan Linier

1.$$
\begin{array}{cc}
x_1+2x_2+3x_3=6\\
2x_1+4x_2+6x_3=12\\
x_3+x_2=2\\
\end{array}
$$

Penyelesaian:

$$ \begin{array}{cc} x_1 + 2x_2 + 3x_3 = 6 \\ 2x_1 + 4x_2 + 6x_3 = 12 \\ x_3 + x_2 = 2 \\ \end{array} $$

Matriks augmented:

$$ \begin{bmatrix} 1 & 2 & 3 & | & 6 \\ 2 & 4 & 6 & | & 12 \\ 0 & 1 & 1 & | & 2 \\ \end{bmatrix} $$

Baris kedua dikurangi 2 kali baris pertama:

$$ \begin{bmatrix} 1 & 2 & 3 & | & 6 \\ 0 & 0 & 0 & | & 0 \\ 0 & 1 & 1 & | & 2\\ \end{bmatrix} $$

Maka,

$$ x_1 + 2x_2 + 3x_3 + 6 = x_1 + 2(2 - x_3) + 3x_3 = 6 \\ x_1+ 4 -2x_2 + 3x_3 = 6\\ x_1+x_3 = 6 - 4\\ x_1 = 2 - x_3  $$



Karna ada variabel bebas $$x_3 = t $$ Sehingga, solusi umum dari sistem persamaan tersebut adalah:

$$\begin{aligned} x_1 &= 2-t, \\ x_2 &= 2-t, \\ x_3 &= t, \quad t \in \mathbb{R}. \end{aligned}$$

2.$$
\begin{array}{cc}
x_1+x_2+x_3=3\\
2x_1+x_3=5\\
x_1+2x_2=3\\
\end{array}
$$
Penyelesaian : 


$$\begin{array}{ccc|c}
1 & 1 & 1 & 3 \\
2 & 0 & 1 & 5 \\
1 & 2 & 0 & 3
\end{array}$$

Langkah 1: Eliminasi Baris Pertama
Kita akan mengeliminasi elemen di bawah elemen pertama pada kolom pertama dengan mengurangi baris kedua dengan 2 kali baris pertama dan mengurangi baris ketiga dengan baris pertama.

- Baris 2 → Baris 2 - 2 × Baris 1
- Baris 3 → Baris 3 - Baris 1

Maka hasilnya adalah:

$$\begin{array}{ccc|c}
1 & 1 & 1 & 3 \\
0 & -2 & -1 & -1 \\
0 & 1 & -1 & 0
\end{array}$$

Langkah 2: Eliminasi Baris Kedua
Sekarang kita akan mengeliminasi elemen di bawah elemen kedua pada kolom kedua dengan menambah baris ketiga dengan setengah baris kedua.

- Baris 3 → Baris 3 + 1/2 dikali baris 2

Hasilnya adalah:


$$\begin{array}{ccc|c}
1 & 1 & 1 & 3 \\
0 & -2 & -1 & -1 \\
0 & 0 & -\frac{3}{2} & -\frac{1}{2}
\end{array}$$

Langkah 3: Normalisasi Baris Ketiga
Kita akan mengalikan baris ketiga dengan \(-\frac{2}{3}\) untuk menjadikan elemen di baris ketiga, kolom ketiga menjadi 1:

- Baris 3 → -2/3 dikali baris 3

Hasilnya menjadi:

$$\begin{array}{ccc|c}
1 & 1 & 1 & 3 \\
0 & -2 & -1 & -1 \\
0 & 0 & 1 & \frac{1}{3}
\end{array}$$


Langkah 4: Eliminasi Kolom Ketiga
Sekarang kita akan mengeliminasi elemen-elemen di atas kolom ketiga.

- Baris 1 → Baris 1 - Baris 3
- Baris 2 → Baris 2 + Baris 3

Maka hasilnya adalah:

$$\begin{array}{ccc|c}
1 & 1 & 0 & \frac{8}{3} \\
0 & -2 & 0 & -\frac{2}{3} \\
0 & 0 & 1 & \frac{1}{3}
\end{array}$$


Langkah 5: Normalisasi Baris Kedua
Kita akan mengalikan baris kedua dengan -1/2 untuk menjadikan elemen di baris kedua, kolom kedua menjadi 1:

- Baris 2 → -1/2 x baris 2

Hasilnya menjadi:

$$\begin{array}{ccc|c}
1 & 1 & 0 & \frac{8}{3} \\
0 & 1 & 0 & \frac{1}{3} \\
0 & 0 & 1 & \frac{1}{3}
\end{array}$$

Langkah 6: Eliminasi Kolom Kedua
Sekarang kita akan mengeliminasi elemen di atas kolom kedua.

- Baris 1 → Baris 1 - Baris 2

Hasil akhirnya menjadi:

$$\begin{array}{ccc|c}
1 & 0 & 0 & \frac{7}{3} \\
0 & 1 & 0 & \frac{1}{3} \\
0 & 0 & 1 & \frac{1}{3}
\end{array}$$


Solusi
Solusi akhir dari persamaan diatas adalah: 

$$\begin{array}{cc}
x_1=\frac{7}{3} \\
x_2=\frac{1}{3} \\
x_3=\frac{1}{3}
\end{array}
$$

3.$$
\begin{array}{cc}
2x_1+2x_2=4\\
x_1+x_2=2
\end{array}
$$
Penyelesaian :

$$\begin{array}{cc} 2x_1 + 2x_2 = 4 \quad (1) \\ x_1 + x_2 = 2 \quad (2) \end{array} $$

matriks augmented:

$$\begin{bmatrix} 2 & 2 & | & 4 \\ 1 & 1 & | & 2 \end{bmatrix}$$

Membuat elemen di bawah pivot menjadi nol. Kita dapat melakukannya dengan mengurangi baris pertama dengan dua kali baris kedua:

$$ R_1 \leftarrow R_1 - 2R_2 $$

Maka:

$$ R_1: \quad 2 - 2 \cdot 1 = 0 \\ 2 - 2 \cdot 1 = 0 \\ 4 - 2 \cdot 2 = 0 $$

Sehingga:

$$ \begin{bmatrix} 0 & 0 & | & 0 \\ 1 & 1 & | & 2 \end{bmatrix} $$

Matriks ini menunjukkan bahwa kita memiliki satu persamaan yang valid dan satu persamaan yang identik (0 = 0). Dari baris kedua, kita dapat menuliskan persamaan:

$$ x_1 + x_2 = 2 \quad (2) $$

Karena baris pertama adalah 0 = 0, ini menunjukkan bahwa sistem ini memiliki solusi tak terhingga. Kita dapat menyelesaikan untuk salah satu variabel. Misalkan kita menyelesaikan untuk (x_1):

$$ x_1 = 2 - x_2 $$

Dengan demikian, solusi umum untuk sistem persamaan ini adalah:

$$(x_1, x_2) = (2 - x_2, x_2) \quad \text{untuk setiap } x_2 \in \mathbb{R} $$

Sebagai contoh, jika kita memilih $(x_2 = 0)$, maka:

$$ x_1 = 2 - 0 = 2 \quad \Rightarrow \quad (x_1, x_2) = (2, 0)$$

Jika kita memilih $(x_2 = 1)$, maka:

$$x_1 = 2 - 1 = 1 \quad \Rightarrow \quad (x_1, x_2) = (1, 1)$$

Dan jika kita memilih $(x_2 = 2)$, maka:

$$ x_1 = 2 - 2 = 0 \quad \Rightarrow \quad (x_1, x_2) = (0, 2)$$

Dengan demikian, solusi dari sistem persamaan ini adalah semua pasangan $((x_1, x_2))$ yang memenuhi:

$$ (x_1, x_2) = (2 - x_2, x_2) \quad \text{untuk setiap } x_2 \in \mathbb{R} $$

## Penyelesaian Sistem Persamaan Linear

Diberikan sistem persamaan:

$$
x_1 + x_2 = 5
$$
$$
x_1 + 2x_3 = 6
$$

Kita akan menyelesaikannya menggunakan metode eliminasi Gauss. Pertama, kita tuliskan sistem ini dalam bentuk matriks augmented:

$$
\begin{bmatrix}
1 & 1 & 0 & | & 5 \\
1 & 0 & 2 & | & 6
\end{bmatrix}
$$

Langkah pertama adalah membuat elemen di bawah pivot (elemen pertama di kolom pertama) menjadi nol. Kita lakukan operasi berikut:

$$
R_2 \leftarrow R_2 - R_1
$$

Setelah melakukan perhitungan, kita mendapatkan:

$$
R_2: \quad 1 - 1 = 0 \\
0 - 1 = -1 \\
2 - 0 = 2 \\
6 - 5 = 1
$$

Sehingga, matriks augmented menjadi:

$$
\begin{bmatrix}
1 & 1 & 0 & | & 5 \\
0 & -1 & 2 & | & 1
\end{bmatrix}
$$

Selanjutnya, kita dapat menyelesaikan baris kedua untuk mengekspresikan \(x_2\) dalam bentuk \(x_3\):

$$
-1x_2 + 2x_3 = 1 \implies x_2 = 2x_3 - 1
$$

Sekarang kita substitusi \(x_2\) ke dalam persamaan pertama:

$$
x_1 + (2x_3 - 1) = 5
$$

Maka kita dapatkan:

$$
x_1 + 2x_3 - 1 = 5 \implies x_1 = 6 - 2x_3
$$

Karena kita memiliki dua persamaan dengan tiga variabel, kita dapat menyatakan solusi dalam bentuk parameter. Misalkan \(x_3 = p\), maka:

$$
x_1 = 6 - 2p
$$
$$
x_2 = 2p - 1
$$
$$
x_3 = p
$$

Jadi, solusi umum dari sistem persamaan ini adalah:

$$
\begin{cases}
x_1 = 6 - 2p \\
x_2 = 2p - 1 \\
x_3 = p
\end{cases}
$$

di mana \(p\) adalah parameter bebas.