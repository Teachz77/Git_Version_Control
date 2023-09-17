# Git_Version_Control

### Mengenal Branch pada Git

Sebelumnya kamu sudah tahu cara untuk membuat repository dan melakukan commit. Jika diperhatikan lagi, yang Kamu lakukan ialah melakukan commit pada branch utama yaitu branch main.
Branch main merupakan branch yang dibagikan kepada programmer lain dan merupakan branch utama dari seluruh branch yang ada. Nantinya semua branch yang dibuat oleh setiap programmer akan digabungkan ke branch main tersebut.
Dalam menggunakan Git sebagai alat untuk berkolaborasi bersama programmer lain, biasanya setiap programmer akan membuat branchnya masing-masing untuk menghindari terjadinya conflict pada perubahan yang dikirimkan terhadap branch utama. Misalnya, Kamu melakukan perubahan pada file readme.md dan programmer lain juga melakukan hal sama namun dengan perubahan yang berbeda, maka nantinya di Git akan terjadi conflict karena terdapat 2 perubahan yang terjadi dalam 1 file yang sama.

### Membuat Branch Pribadi Kamu

Untuk membuat branch baru dengan nama menambahkan-readme, masukkan perintah dibawah ini:
| git branch menambahkan-readme |
