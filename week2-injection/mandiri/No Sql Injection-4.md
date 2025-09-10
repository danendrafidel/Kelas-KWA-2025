# Pico CTF: No Sql Injection

https://play.picoctf.org/practice/challenge/443?page=1&search=inject

Disini ada beberapa clue untuk injection yang akan diberikan oleh soal, untuk penyelesaiannya menggunakan payload yang boleh dan tidak diperbolehkan oleh soal

1. Diberikan file berisi email yang bisa dipakai
   ![Mandiri 4](<../img/mandiri4%20(3).png>)

2. Gunakan Payload password untuk masuk, kemudian inspect netwoknya
   ![Mandiri 4](<../img/mandiri4%20(2).png>)

   `Payload PASS: {"$ne":"null"}`

   ![Mandiri 4](<../img/mandiri4%20(1).png>)

3. Maka akan berhasil login seperti ini namun bukan ini yang dicari untuk flagnya, kemudian cek kembali untuk inspect networknya
   ![Mandiri 4](<../img/mandiri4%20(4).png>)

4. Dengan menggunakan burpsuit akan didapatkan akses token
   ![Mandiri 4](<../img/mandiri4%20(5).png>)

5. Dari token tersebut decode memakai base64
   ![Mandiri 4](<../img/mandiri4%20(6).png>)

`FLAG: picoCTF{jBhD2y7XoNzPv_1YxS9Ew5qL0uI6pasql_injection_25ba4de1`
