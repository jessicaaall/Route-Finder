# ROUTE FINDER
Route Finder merupakan program pencarian rute sederhana, yang menerapkan algoritma pencarian rute terpendek dari lokasi asal ke lokasi tujuan. Sebagai program pencarian rute sederhana, Route Finder ini menggunakan _maze_ sebagai peta, sehingga pencarian rute dilakukan berdasarkan masukan _input_ berupa dua titik koordinat, yang menjadi lokasi asal dan lokasi tujuan, dari _maze_. Program Route Finder akan menampilkan rute terpendek dari lokasi asal hingga mencapai lokasi tujuan, dan menghitung jarak rute yang ditempuh dalam bentuk jumlah langkah.

## Cara Kerja Program
Berikut merupakan cara kerja program Route Finder dalam menghasilkan pencarian rute terpendek.
1. Program menampilkan _maze_ sebagai peta kepada pengguna.
2. Program menampilkan daftar titik koordinat jalan kepada pengguna untuk memudahkan pengguna mengetahui titik koordinat jalan yang ada pada _maze_.
3. Pengguna akan diminta memasukkan dua _input_, yaitu titik koordinat asal dan titik koordinat tujuan.
4. Program melakukan pengecekan apakah titik koordinat asal dan tujuan yang di-_input_ oleh pengguna sesuai dengan titik koordinat jalan yang ada pada _maze_. Apabila sesuai, _input_ titik koordinat asal dan tujuan akan diterima oleh program. Sebaliknya, apabila titik koordinat asal atau tujuan tidak sesuai dengan daftar titik koordinat jalan pada _maze_, maka program akan menampilkan pesan kesalahan.
5. Program melakukan pencarian rute terpendek berdasarkan _input_ titik koordinat asal dan tujuan yang valid.
6. Program akan menampilkan _maze_ yang telah dilengkapi dengaan penanda rute yang dilalui dari titik koordinat asal hingga mencapai titik koordinat tujuan.
7. Program juga menampilkan jumlah langkah yang ditempuh dari titik koordinat asal untuk mencapai titik koordinat akhir.
