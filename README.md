# Reflection

## Experiment 3.1: Original code

![image](https://github.com/DaWanAnOnli/YewChat/assets/124868777/dae70321-663c-4a81-96d9-34a9d76538a7)

## Experiment 3.2: Be creative!

![image](https://github.com/DaWanAnOnli/YewChat/assets/124868777/6b49cf6b-1ea4-4060-82d7-be3897e4ad6d)

Saya membuat dark mode sederhana untuk chatting page. Di sebelah kanan tombol send, ada toggle dark mode yang akan mentoggle antara dark mode dan light mode. Pertama, saya tambahkan atribut boolean dark_mode di struct Chat. Lalu di impl Chat, saya tambahkan function toggle dark_mode, yang akan flip nilai dari nilai dark_mode yang ada sekarang. Setelah itu, saya membuat file css untuk menentukan warna yang akan ditampilkan saat dark mode. Terakhir, saya ubah fungsi view pada chat.rs dengan menambahkan beberapa variable indicator dark mode dan menempatkannya pada bagian-bagian teks dan background dari html. 
