MongoDB adalah salah satu produk database noSQL Open Source yang menggunakan 
struktur data JSON untuk menyimpan datanya. 
MongoDB adalah merupakan database noSQL yang paling populer di internet. 
MongoDB sering dipakai untuk aplikasi berbasis Cloud, Grid Computing, atau Big Data. 
Pada praktikum kali ini saya menggunakan mongoDB dengan versi 32 bit. 
Kemudian saya membuka cmd dan melakukan langkah-langkah sebagai berikut :

* C:\Users\DENI>F:
* F:\>cd/ 
* F:\>cd mongo => maka akan menggunakan folder mongo
* F:\mongo\bin>mongod.exe
* F:\mongo\bin>mongod --dbpath "F:\mongo\data\db"
* F:\mongo\bin>mongod -storageEngine=mmapv1 -dbpath F:\mongo\data

Kemudian dari langkah-langkah diatas masuk ke dalam folder bin, 
selanjutnya akan membuka file mongo dan didalam file mongo tersebut 
maka dijalankan dan membuat database.
