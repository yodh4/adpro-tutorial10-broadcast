<b>2.1 Original Code</b>
![img](1.png)
Untuk menjalankan program ini pengguna harus memasukkan command `cargo run --bin server` dan `cargo run --bin client`. Setelah program berjalan pengguna dapat menginput text pada aplikasi client dan selanjutnya server akan mem-broadcast text tersebut ke client lainnya yang terhubung, untuk melihat pesan tersebut dibroadcast ke client lain pengguna dapat me-run beberapa aplikasi client.

<b>2.2 Modifying Port</b>

Ketika kita mengubah port pada aplikasi client maka outputnya akan seperti ini
![img](2.png)
Untuk memperbaiki error tersebut kita harus mengganti juga port pada aplikasi server menjadi `8080` agar aplikasi dapat berjalan lancar seperti berikut
![img](3.png)