# Pengertian Blockchain
blockchain adalah sebuah block yang berfungsi untuk menyimpan data / mencatat data dan transaksi digital. setiap block akan divalidasi.
Semua data terdesentralisasi sehingga tidak bisa di edit atau mengubah data. Semua data trasaksi akan tercatat di blockchain, dan setiap transaksi akan dikelompokkan sebagai block block.

# Cara Blockchain berkerja
ada block genesis, yang merupakan sebuah block awal yang menjadi pemicu untuk block block lain.
Ketika ada suatu transaksi, transaksi tersebut akan di buat salinannya pada block, block pertama ini adalah block genesis dan di hashing. Ketika ada transaksi baru, maka hashing di block genesis ini akan masuk ke block baru lalu di hasing dengan transaksi yang baru ini, dan seterusnya. Setiap block memiliki aturan dan algoritma tertentu yang harus dipecahkan oleh seorang miner, seorang miner harus memecahkan sebuah kunci bernama Nonce, sehingga bisa melakukan validasi terhadap block tersebut.
## Hashing
merupakan kunci utama dari sebuah blockchain. Sebuah data yang masuk lalu di hashing dengan SHA256 maka akan menghasilkan sebuah string random dari data tersebut.
dari genesis block di hash, block ke2 akan di hashing lagi dari hash pertama, sampai seterusnya. Setiap hash yang disimpan dari genesis sampai block selanjutnya tidak akan bisa dubah, ketika diubah maka hashnya menjadi tidak valid

## NONCE
sebuah nomor untuk mengatur agar para miner harus melakukan pemecahan algoritma setiap transaksi yang berbeda beda, tidak sama setiap proses penyelesaian algoritma NONCE ini adalah kunci yang harus dipecahkan.

NONCE > TO > VALUE > GAS PRICE > START / GAS LIMIT > v r s 
v r s adalah untuk menggenerate sender account address. di generate dari private key pengirim. Karena ini lah untuk menverifikasi jika transaksi itu sah atau tidak.,
