
Login Pada Termux ( Termux Login )

Berikut cara pemasangan Script Login Termux :

Pertama - tama installah git dengan perintah :
pkg install git

Selanjutnya install python2 dengan perintah :
pkg install python2

Klon script login termux nya dengan perintah :
git clone git clone https://github.com/khilhim27/termux-loginv2fx.git

Setelah itu pergilah ke folder termux-loginv2fx dengan perintah :
cd termux-loginv2fx
Jalankan setup dengan perintah :
python2 setup.py

Pergilah ke Home dengan perintah :
cd $HOME

Lalu jalankan useradd untuk menambahkan username dan password untuk login nantinya, dengan perintah :
python2 useradd.py
 Nah setelah menjalankan useradd kalian akan disuruh mengisi username , password ,dan yang lainnya seperti gambar dibawah ini
.Perintah lainnya :

Untuk menambah User :
useradd

Mengganti Password :
passwd

Untuk melihat info User :
info

Untuk melihat pembuat script :
me
Nah itulah cara menginstall script Login Untuk Termux, sekian sampai jumpa di tutorial menarik lainnya.
