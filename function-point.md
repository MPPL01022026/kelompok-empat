# FUNCTION POINT ANALYSIS
## Digital Twin Product Kopi Gayo

### 1. Tujuan

Function Point Analysis digunakan untuk mengestimasi ukuran fungsional aplikasi berdasarkan fungsi yang tersedia pada rancangan Sprint 1.

### 2. Identifikasi Fungsi Sistem

| No | Fungsi Sistem | Jenis Fungsi | Kompleksitas |
|---|---|---|---|
| 1 | Menampilkan halaman Beranda | EQ | Low |
| 2 | Menampilkan informasi Tentang | EQ | Low |
| 3 | Menampilkan daftar Produk | EQ | Low |
| 4 | Menampilkan detail informasi produk | EQ | Low |
| 5 | Menampilkan halaman QR Code | EQ | Low |

### 3. Bobot Function Point

| Function Type | Low | Average | High |
|---|---:|---:|---:|
| EI | 3 | 4 | 6 |
| EO | 4 | 5 | 7 |
| EQ | 3 | 4 | 6 |
| ILF | 7 | 10 | 15 |
| EIF | 5 | 7 | 10 |

### 4. Perhitungan UFP

| Jenis Fungsi | Low | Average | High | Total |
|---|---:|---:|---:|---:|
| EI | 0 | 0 | 0 | 0 |
| EO | 0 | 0 | 0 | 0 |
| EQ | 5 | 0 | 0 | 15 |
| ILF | 0 | 0 | 0 | 0 |
| EIF | 0 | 0 | 0 | 0 |
| UFP | | | | 15 |

UFP = (5 × 3)

UFP = 15

### 5. General System Characteristics

| No | Karakteristik | Nilai |
|---|---|---:|
| 1 | Data Communications | 2 |
| 2 | Distributed Data Processing | 0 |
| 3 | Performance | 2 |
| 4 | Heavily Used Configuration | 1 |
| 5 | Transaction Rate | 1 |
| 6 | On-Line Data Entry | 0 |
| 7 | End-User Efficiency | 3 |
| 8 | On-Line Update | 0 |
| 9 | Complex Processing | 0 |
| 10 | Reusability | 2 |
| 11 | Installation Ease | 3 |
| 12 | Operational Ease | 3 |
| 13 | Multiple Sites | 2 |
| 14 | Facilitate Change | 2 |
| | Total TDI | 21 |

### 6. Value Adjustment Factor

VAF = 0,65 + (0,01 × TDI)

VAF = 0,65 + (0,01 × 21)

VAF = 0,86

### 7. Function Point Akhir

FP = UFP × VAF

FP = 15 × 0,86

FP = 12,90 FP

Dibulatkan menjadi:

**13 Function Point**

### 8. Kesimpulan

Berdasarkan perhitungan Function Point Analysis pada Sprint 1 Digital Twin Product Kopi Gayo, diperoleh nilai UFP sebesar 15 dan VAF sebesar 0,86.

Dengan demikian, estimasi ukuran fungsional aplikasi pada Sprint 1 adalah sebesar 12,90 Function Point atau sekitar 13 Function Point.

Nilai Function Point dapat berubah pada sprint berikutnya apabila sistem ditambahkan fungsi seperti autentikasi, pengelolaan data, database, input, edit, dan penghapusan data.
