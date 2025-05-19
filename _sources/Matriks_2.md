## Sistem Persamaan Linear Dengan Menggunakan Invers OBE (Operasi Baris Elementer)

$-7x1-6x2-12x3=-33$ 

$5x1+5x2+7x3=24$

$x1+4x3=5$
    
$A=\begin{bmatrix}-7&-6&-12\\5&5&7\\1&0&4\end{bmatrix}$  
$x=\begin{bmatrix}x_1\\x_2\\x_3\end{bmatrix}$  
$b=\begin{bmatrix}-33\\24\\5\end{bmatrix}$`

Pertama Gabungkan matriks ( A ) dengan matriks identitas $( I )$ untuk membentuk matriks augmented $( [A | I] )$:


$[A | I] =
\begin{bmatrix}
-7 & -6 & -12 & | 1 & 0 & 0 \\
5 & 5 & 7 & | 0 & 1 & 0 \\
1 & 0 & 4 & | 0 & 0 & 1
\end{bmatrix}$

pakai OBE jadi yang bagian kanan menjadi $( A^{-1} )$.

Lalu kita Ubah Elemen (1,1) Menjadi 1
jadi Baris pertama dibagi dengan (-7):

$\begin{bmatrix}
1 & \frac{6}{7} & \frac{12}{7} & | -\frac{1}{7} & 0 & 0 \\
5 & 5 & 7 & | 0 & 1 & 0 \\
1 & 0 & 4 & | 0 & 0 & 1
\end{bmatrix}$

Lalu Buat Elemen Kolom Pertama (2,1) dan (3,1) Menjadi 0
- Baris kedua: $( R_2 \to R_2 - 5 R_1 )$
- Baris ketiga: $( R_3 \to R_3 - R_1 )$

Hasilnya:

$\begin{bmatrix}
1 & \frac{6}{7} & \frac{12}{7} & | -\frac{1}{7} & 0 & 0 \\
0 & \frac{5}{7} & -\frac{1}{7} & | \frac{5}{7} & 1 & 0 \\
0 & -\frac{6}{7} & \frac{16}{7} & | \frac{1}{7} & 0 & 1
\end{bmatrix}$

Ubah Elemen (2,2) Menjadi 1
Kita bagi baris kedua dengan $( \frac{5}{7} )$:

$\begin{bmatrix}
1 & \frac{6}{7} & \frac{12}{7} & | -\frac{1}{7} & 0 & 0 \\
0 & 1 & -\frac{1}{5} & | 1 & \frac{7}{5} & 0 \\
0 & -\frac{6}{7} & \frac{16}{7} & | \frac{1}{7} & 0 & 1
\end{bmatrix}$

Setelah Itu Buat Elemen Kolom Kedua (1,2) dan (3,2) Menjadi 0
- Baris pertama: $( R_1 \to R_1 - \frac{6}{7} R_2 )$
- Baris ketiga: $( R_3 \to R_3 + \frac{6}{7} R_2 )$

Hasilnya:

$\begin{bmatrix}
1 & 0 & \frac{18}{35} & | -\frac{13}{35} & -\frac{42}{35} & 0 \\
0 & 1 & -\frac{1}{5} & | 1 & \frac{7}{5} & 0 \\
0 & 0 & \frac{22}{35} & | \frac{13}{35} & \frac{42}{35} & 1
\end{bmatrix}$

Ubah Elemen (3,3) Menjadi 1
Kita bagi baris ketiga dengan $( \frac{22}{35} )$:

$\begin{bmatrix}
1 & 0 & \frac{18}{35} & | -\frac{13}{35} & -\frac{42}{35} & 0 \\
0 & 1 & -\frac{1}{5} & | 1 & \frac{7}{5} & 0 \\
0 & 0 & 1 & | \frac{13}{22} & \frac{42}{22} & \frac{35}{22}
\end{bmatrix}$

Buat Elemen Kolom Ketiga (1,3) dan (2,3) Menjadi 0
- Baris pertama: $( R_1 \to R_1 - \frac{18}{35} R_3 )$
- Baris kedua: $( R_2 \to R_2 + \frac{1}{5} R_3 )$

Hasilnya:

$\begin{bmatrix}
1 & 0 & 0 & | -3 & 5 & 2 \\
0 & 1 & 0 & | 2 & 1 & 1 \\
0 & 0 & 1 & | \frac{13}{22} & \frac{21}{11} & \frac{35}{22}
\end{bmatrix}$
Bagian kanan dari matriks ini adalah $( A^{-1} )$.

Langkah 8: Hitung $( x = A^{-1} b )$
Kita kalikan $( A^{-1} )$ dengan $( b )$:

$x = A^{-1} b =
\begin{bmatrix}
-3 & 5 & 2
\end{bmatrix}$

Sehingga diperoleh:

$x_1 = -3, \quad x_2 = 5, \quad x_3 = 2$

### Contoh Perhitungan Determinan

#### 1. Contoh Determinan Matriks 3×3
Misalkan diberikan matriks:  
$A =
\begin{bmatrix}
2 & 3 & 1 \\
4 & 5 & 6 \\
7 & 8 & 9
\end{bmatrix}$
Kita gunakan ekspansi kofaktor pada baris pertama:  
$\det(A) = 2
\begin{vmatrix}
5 & 6 \\
8 & 9
\end{vmatrix} - 3
\begin{vmatrix}
4 & 6 \\
7 & 9
\end{vmatrix} + 1
\begin{vmatrix}
4 & 5 \\
7 & 8
\end{vmatrix}$

Hitung determinan dari masing-masing submatriks 2×2:  
$\begin{vmatrix}
5 & 6 \\
8 & 9
\end{vmatrix} = (5 \times 9) - (6 \times 8) = 45 - 48 = -3$

$\begin{vmatrix}
4 & 6 \\
7 & 9
\end{vmatrix} = (4 \times 9) - (6 \times 7) = 36 - 42 = -6$

$\begin{vmatrix}
4 & 5 \\
7 & 8
\end{vmatrix} = (4 \times 8) - (5 \times 7) = 32 - 35 = -3$

Substitusi hasilnya:  
$\det(A) = (2 \times -3) - (3 \times -6) + (1 \times -3)$
$= -6 + 18 - 3 = 9$

#### 2. Contoh Determinan Matriks 4×4  
Misalkan diberikan matriks:  
$B =
\begin{bmatrix}
1 & 2 & 3 & 4 \\
5 & 6 & 7 & 8 \\
9 & 10 & 11 & 12 \\
13 & 14 & 15 & 16
\end{bmatrix}$
Gunakan ekspansi kofaktor pada baris pertama:  
$\det(B) = 1
\begin{vmatrix}
6 & 7 & 8 \\
10 & 11 & 12 \\
14 & 15 & 16
\end{vmatrix} - 2
\begin{vmatrix}
5 & 7 & 8 \\
9 & 11 & 12 \\
13 & 15 & 16
\end{vmatrix} + 3
\begin{vmatrix}
5 & 6 & 8 \\
9 & 10 & 12 \\
13 & 14 & 16
\end{vmatrix} - 4
\begin{vmatrix}
5 & 6 & 7 \\
9 & 10 & 11 \\
13 & 14 & 15
\end{vmatrix}$

Setiap submatriks 3×3 dihitung dengan metode sebelumnya:  
$\begin{vmatrix}
6 & 7 & 8 \\
10 & 11 & 12 \\
14 & 15 & 16
\end{vmatrix} = (6(11 \times 16 - 12 \times 15)) - (7(10 \times 16 - 12 \times 14)) + (8(10 \times 15 - 11 \times 14))$

$= (6(176 - 180)) - (7(160 - 168)) + (8(150 - 154))$
$= (6 \times -4) - (7 \times -8) + (8 \times -4)$
$= -24 + 56 - 32 = 0$

Karena semua submatriks 3×3 dari ekspansi kofaktor juga bernilai 0, maka:
$\det(B) = 0$


#### 3. Contoh Determinan Matriks 5×5
Misalkan diberikan matriks:
$C =
\begin{bmatrix}
1 & 2 & 3 & 4 & 5 \\
6 & 7 & 8 & 9 & 10 \\
11 & 12 & 13 & 14 & 15 \\
16 & 17 & 18 & 19 & 20 \\
21 & 22 & 23 & 24 & 25
\end{bmatrix}$

Gunakan ekspansi kofaktor pada baris pertama:

$\det(C) =
1 \times C_{11} - 2 \times C_{12} + 3 \times C_{13} - 4 \times C_{14} + 5 \times C_{15}$

di mana $( C_{ij} )$ adalah determinan dari submatriks 4×4 yang diperoleh dengan menghapus baris ke-1 dan kolom ke- $( j )$.
Hitung Submatriks 4×4
Misalkan kita hitung submatriks pertama $( C_{11} )$ dengan menghapus baris pertama dan kolom pertama:

$C_{11} =
\begin{vmatrix}
7 & 8 & 9 & 10 \\
12 & 13 & 14 & 15 \\
17 & 18 & 19 & 20 \\
22 & 23 & 24 & 25
\end{vmatrix}$

Gunakan ekspansi kofaktor pada baris pertama dari $( C_{11} )$:
$\begin{vmatrix}
7 & 8 & 9 & 10 \\
12 & 13 & 14 & 15 \\
17 & 18 & 19 & 20 \\
22 & 23 & 24 & 25
\end{vmatrix} = 7
\begin{vmatrix}
13 & 14 & 15 \\
18 & 19 & 20 \\
23 & 24 & 25
\end{vmatrix} - 8
\begin{vmatrix}
12 & 14 & 15 \\
17 & 19 & 20 \\
22 & 24 & 25
\end{vmatrix} + 9
\begin{vmatrix}
12 & 13 & 15 \\
17 & 18 & 20 \\
22 & 23 & 25
\end{vmatrix} - 10
\begin{vmatrix}
12 & 13 & 14 \\
17 & 18 & 19 \\
22 & 23 & 24
\end{vmatrix}$

Hitung Submatriks 3×3
Misalkan kita hitung determinan submatriks 3×3 pertama:

$\begin{vmatrix}
13 & 14 & 15 \\
18 & 19 & 20 \\
23 & 24 & 25
\end{vmatrix}$

Gunakan ekspansi kofaktor pada baris pertama:

$= 13
\begin{vmatrix}
19 & 20 \\
24 & 25
\end{vmatrix} - 14
\begin{vmatrix}
18 & 20 \\
23 & 25
\end{vmatrix} + 15
\begin{vmatrix}
18 & 19 \\
23 & 24
\end{vmatrix}$

Hitung determinan matriks 2×2:

$\begin{vmatrix}
19 & 20 \\
24 & 25
\end{vmatrix}
= (19 \times 25) - (20 \times 24) = 475 - 480 = -5$

$\begin{vmatrix}
18 & 20 \\
23 & 25
\end{vmatrix}
= (18 \times 25) - (20 \times 23) = 450 - 460 = -10$

$\begin{vmatrix}
18 & 19 \\
23 & 24
\end{vmatrix}
= (18 \times 24) - (19 \times 23) = 432 - 437 = -5$

Substitusi:

$= 13(-5) - 14(-10) + 15(-5)$

$= -65 + 140 - 75 = 0$

Karena semua submatriks 3×3 lainnya memiliki pola angka yang sama, maka determinan semua submatriks 3×3 adalah 0.

Karena setiap submatriks 4×4 memiliki determinan 0, maka:
$\det(C) = 1(0) - 2(0) + 3(0) - 4(0) + 5(0) = 0$

Jadi, determinan matriks 5×5 ini adalah 0