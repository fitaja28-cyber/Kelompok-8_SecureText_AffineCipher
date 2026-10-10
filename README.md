# SecureText - Caesar & Affine Cipher

Project Matematika Diskrit - Program Studi Ilmu Komputer
Kelompok 8
Dosen: Nurul Maulida Surbakti, M.Si.

Anggota:
- Fitry Meriyana Halawa (4253550010)
- Lilis Kesia Aprilia Ambarita (4252250001)
- Fenissia Vania Theola Br Purba (4253550034)
- Tahsia Khezia Sianturi (4253550002)
- Pestauli Desi Natalia (4251250013)

Demo web: https://fitaja28-cyber.github.io/Kelompok-8_SecureText_AffineCipher/

## Cara menjalankan
Buka file `index.html` dengan browser (Chrome/Edge/Firefox).
Tidak perlu instalasi, internet, atau library tambahan.

## Fitur
- Enkripsi dan dekripsi Caesar Cipher dan Affine Cipher
- Validasi kunci (FPB(a, 26) harus 1) dan invers modulo (Euclid diperluas)
- Tabel langkah perhitungan per huruf
- 8 test case otomatis (expected vs actual)

## Contoh input
- Pesan `MATEMATIKA DISKRIT`, Affine, a = 5, b = 8 -> `QIZCQIZWGI XWUGPWZ`
- Pesan `HELLO`, Caesar, k = 3 -> `KHOOR`
