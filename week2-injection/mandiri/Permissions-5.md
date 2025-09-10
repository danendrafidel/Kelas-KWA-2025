# Pico CTF: Permissions

https://play.picoctf.org/practice/challenge/363?page=1&search=permission

Di soal ini memanfaatkan comand terminal linux untuk menginject ke dalam root

1. Diberikan akses untuk kedalam PICO CTF
   ![Mandiri 5](<../img/mandiri5%20(1).png>)

2. Kemudian coba gunakana `sudo -l` untuk melihat folder apa saja yang tersedia
   ![Mandiri 5](<../img/mandiri5%20(2).png>)

3. Lalu dengan menggunakan command sudo untuk inject masuk kedalam akses root yang seharusnya user biasa tidak bisa
   ![Mandiri 5](<../img/mandiri5%20(3).png>)

4. Setelah berhasil maka akan masuk seperti berikut, whoami -> root -> lalu ls -a untuk mengecek apakah ada file yang menunjukan flag, dan ternyata ada `flag.txt` sebagai flagnya
   ![Mandiri 5](<../img/mandiri5%20(4).png>)
