# Juice-Shop: Login Bender

1. Mengscanning mencari email yang ada unsur bender
   ![Soal 3](<../img/soal3%20(1).png>)

2. Mengubah entri di bidang masukan email untuk menyertakan muatan injeksi SQL: bender@juice-sh.op' AND '1'='1' --. Muatan ini mencoba memanipulasi kueri SQL di balik formulir masuk dengan menutup rangkaian email (dengan tanda kutip tunggal), menambahkan kondisi yang selalu bernilai benar ( AND '1'='1'), lalu mengomentari sisa perintah SQL dengan --.
   ![Soal 3](<../img/soal3%20(2).png>)

3. 3. Berhasil masuk sebagai Bender, kondisi AND '1'='1' -- selalu bernilai benar, yang memungkinkan akses tidak sah ke akun Bender.
      ![Soal 3](<../img/soal3%20(3).png>)
