# UAS Bahasa Pemrograman 1


1. Pertama Kita Lakukan Fork dari repository berikut: https://github.com/abuazzam/uaspy, kemudian Clone
ke local repository.

![Fork](https://user-images.githubusercontent.com/46512870/55852808-a1381d80-5b88-11e9-83f8-daceedc167f6.png)

![clone](https://user-images.githubusercontent.com/46512870/55854898-32f75900-5b90-11e9-9064-3cac2cef95e3.png)


2. Kedua Lakukan konfigurasi virtual environment pada project anda.

![Env](https://user-images.githubusercontent.com/46512870/55852858-ccbb0800-5b88-11e9-83b3-b40c7b92b93c.png)

3. Ketiga Install requirements yang dibutuhkan (pip install atau dari PyCharm).

![pip](https://user-images.githubusercontent.com/46512870/55855948-11e43780-5b93-11e9-98b0-3963555bf045.png)

4. Keempat Buat class utama dengan menurunkan dari class BaseApp dengan nama App (seusikan kode
program pada main.py)

5. Kelima Jalankan aplikasi sehingga muncul tampilan seperti berikut:

![game](https://user-images.githubusercontent.com/46512870/55856158-b2d2f280-5b93-11e9-8751-794a542eed86.png)

6. Lakukan override pada method on_playing() tambahkan kode, apabila Player menyentuh
Meteor lebih dari 5x maka program akan berakhir. (dengan perintah self.stop()) (Point: 10)
Perintah untuk mengetahui apakah player menyentuh meteor adalah:
self.check_collision(self.player, self.enemies)
