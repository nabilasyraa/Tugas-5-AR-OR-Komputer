# MODE PENGALAMATAN MEMORI

### Pengalamatan Langsung

Instruksi: LOAD A, 2000

Pada pengalamatan langsung, alamat operand disebutkan langsung dalam instruksi

Alamat yang diakses = 2000


### Pengalamatan Tidak Langsung:

Instruksi: LOAD A, (R1) dimana R1 = 1500

Pada pengalamatan tidak langsung, register berisi alamat operand

Alamat yang diakses = 1500 (nilai yang ada di R1)


### Pengalamatan Indeks:

Instruksi: LOAD A, 500(R2) dimana R2 = 100

Pada pengalamatan indeks, alamat efektif = alamat dasar + isi register indeks

Alamat yang diakses = 500 + 100 = 600


### Pengalamatan Relatif:

Instruksi: LOAD A, 40 dimana PC = 1200

Pada pengalamatan relatif, alamat efektif = alamat instruksi saat ini + displacement

Alamat yang diakses = 1200 + 40 = 1240


### Pengalamatan Segmen:

Segment Base = 4000, Offset = 300

Pada pengalamatan segmen, alamat efektif = segment base + offset

Alamat yang diakses = 4000 + 300 = 4300


### Latihan Campuran:

Instruksi: LOAD A, 1000(R3) dimana R3 = 250

Mirip dengan pengalamatan indeks

Alamat yang diakses = 1000 + 250 = 1250

### Semua perhitungan di atas mengasumsikan bahwa:

- Tidak ada overflow atau error alamat
- Semua nilai dalam desimal
- Pengalamatan menggunakan aritmatika biasa
