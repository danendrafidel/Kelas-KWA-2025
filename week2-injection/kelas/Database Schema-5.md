# Juice-Shop: Database Schema

1. Endpoint yang digunakan adalah /rest/products/search?q=. Kali ini kita tidak mengambil data dari tabel users, tetapi dari sqlite_schema (pada SQLite) untuk melihat struktur database. Pertama, kita perlu menyesuaikan jumlah kolom yang sama dengan query asli menggunakan UNION SELECT. Setelah dicoba, jumlah kolom yang cocok adalah 9.

```sql
')) UNION SELECT 1,2,3,4,5,6,7,8,sql FROM sqlite_schema--
```

![Soal 5](<../img/soal5%20(1).png>)

2. Berhasil

![Soal 5](<../img/soal5%20(2).png>)
