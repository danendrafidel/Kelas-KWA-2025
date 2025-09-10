# Juice-Shop: Ephemeral Accountant

1. Kita perlu login ke akun yang sebenarnya tidak ada, yaitu acc0unt4nt@juice-sh.op, caranya, manfaatkan endpoint Search yang sebelumnya kita gunakan untuk menemukan database schema, dari situ bisa melihat query pembuatan tabel Users, dan dari situ kita bisa tahu struktur kolom yang dipakai untuk membuat user.
   ![Soal 7](<../img/soal7 (1).png>)

2. Buat query sendiri menggunakan UNION untuk membuat akun ini. Dengan struktur kolom dari tabel Users, lewat database schema tadi, dari situ kita bisa menginject data user baru ke hasil query, seakam akun acc0unt4nt@juice-sh.op muncul di sistem.
   ![Soal 7](<../img/soal7 (2).png>)
   ![Soal 7](<../img/soal7 (3).png>)
