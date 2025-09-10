# Juice-Shop: NoSQL Manipulation

1. Untuk memanipulasi semua product reviews sekaligus, bisa kita lakukan lewat satu endpoint /rest/products/reviews. Di endpoint ini tersedia beberapa parameter yang bisa diubah. Dengan melakukan intercept pada request ke endpoint tersebut, kita bisa ubah isi dari field review
   ![Soal 8](<../img/soal8 (1).png>)

2. Request default menggunakan PUT, tapi untuk update review kita harus ganti metodenya jadi PATCH. Lalu ganti beberapa paramaeternya, dengan trik ini server akan menganggap semua produk valid.
   ![Soal 8](<../img/soal8 (2).png>)
   ![Soal 8](<../img/soal8 (3).png>)
