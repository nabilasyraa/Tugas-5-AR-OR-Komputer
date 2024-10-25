## MODE PENGALAMATAN MEMORI

### Pengalamatan Langsung
- Instruksi: LOAD A, 2000
- Perhitungan: Pada pengalamatan langsung, alamat operand langsung disebutkan dalam instruksi
- Alamat yang diakses = 2000

### Pengalamatan Tidak Langsung:
- Instruksi: LOAD A, (R1) dimana R1 = 1500
- Perhitungan: Pada pengalamatan tidak langsung, register berisi alamat operand
- Alamat yang diakses = 1500 (nilai yang ada di R1)

### Pengalamatan Indeks:
- Instruksi: LOAD A, 500(R2) dimana R2 = 100
- Perhitungan: Alamat efektif = Alamat dasar + Isi register indeks
- Alamat yang diakses = 500 + 100 = 600

### Pengalamatan Relatif:
- Instruksi: LOAD A, 40 dimana PC = 1200
- Perhitungan: Alamat efektif = Alamat instruksi saat ini + Displacement
- Alamat yang diakses = 1200 + 40 = 1240

### Pengalamatan Segmen:
- Segment Base = 4000
- Offset = 300
- Perhitungan: Alamat efektif = Segment Base + Offset
- Alamat yang diakses = 4000 + 300 = 4300

### Latihan Campuran:
- Instruksi: LOAD A, 1000(R3) dimana R3 = 250
- Perhitungan: Sama seperti pengalamatan indeks
- Alamat yang diakses = 1000 + 250 = 1250

### Semua perhitungan di atas mengasumsikan bahwa:
- Tidak ada overflow atau error alamat
- Semua nilai dalam desimal
- Pengalamatan menggunakan aritmatika biasa

### Penting untuk diingat:
- Pengalamatan Langsung: Alamat operand langsung ada di instruksi
- Pengalamatan Tidak Langsung: Alamat operand disimpan di register
- Pengalamatan Indeks: Alamat dasar + isi register indeks
- Pengalamatan Relatif: Alamat instruksi saat ini + displacement
- Pengalamatan Segmen: Segment base + offset

Setiap mode pengalamatan memiliki kegunaannya masing-masing dalam pemrograman dan manajemen memori.
