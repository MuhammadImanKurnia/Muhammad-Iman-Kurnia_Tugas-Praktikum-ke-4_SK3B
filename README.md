# Muhammad-Iman-Kurnia_Tugas-Praktikum-ke-4_SK3B

Tugas Praktikum ke 4

Nama   : Muhammad Iman Kurnia

NIM    : 09011282328044

Kelas  : SK3B 

1. Lihat daftar secara lengkap pada direktori aktif, 

   Jawab :

   Jika kita ingin melihat daftar direktori aktif secara lengkap, kita bisa menggunakan command prompt ls -al
   ![Screenshot from 2024-09-12 08-55-23](https://github.com/user-attachments/assets/86711a2d-ebb2-4139-abc3-fd7786a60eef)
   Kemudian, jika kita ingin membelokkan tampilan standard output ke file baru, kita bisa menggunakan command prompt ls -al > (nama file baru). Misal, ls -al > newfile.txt.
   Kalau selesai, kita bisa menggunakan command prompt cat untuk melihat isi dari file baru tersebut. Misal, cat newfile.txt
   ![Screenshot from 2024-09-12 08-55-58](https://github.com/user-attachments/assets/953288d3-c434-4a5b-8772-dcdca8ae1cd3)

2. Lihat daftar secara lengkap pada direktori /etc/passwd, belokkan tampilan standard output ke file baru tanpa menghapus file baru sebelumnya

   Jawab :

   Untuk melihat daftar lengkap direktori /etc/passwd, pertama-tama kita masuk ke direktori etc dulu dengan menggunakan command prompt cd /etc. Kemudian kita ingin melihat      daftar lengkap dari passwd. Caranya dengan menggunakan cat passwd
   ![Screenshot from 2024-09-13 09-55-59](https://github.com/user-attachments/assets/7a5be843-f080-4cb1-97f6-c043943ff194)
   Kemudian kita ingin membelokkan tampilan standard outputnya ke file baru tanpa menghapus file baru sebelumnya. Caranya adalah kita ketik cat /etc/passwd >> (nama file        baru yang tadi(newfile.txt)). Misal, cat /etc/passwd >> newfile.txt. Kemudian kita ketik cat newfile.txt untuk melihat isi dari file baru tersebut
   ![Screenshot from 2024-09-12 09-14-18](https://github.com/user-attachments/assets/6b62a6db-273f-4424-8ef4-06738abaabd6)
   ![Screenshot from 2024-09-12 09-14-43](https://github.com/user-attachments/assets/a42eb2ce-e4de-49e0-8ca8-eb35391eef3e)

3. Urutkan file baru dengan cara membelokkan standard input

   Jawab :

   Untuk mengurutkan file baru tersebut, kita bisa menggunakan command prompt sort < newfile.txt
   ![Screenshot from 2024-09-12 09-18-40](https://github.com/user-attachments/assets/726fcf03-fcbb-4dd4-996b-a41ab5799092)
   ![Screenshot from 2024-09-12 09-19-08](https://github.com/user-attachments/assets/8401e2cc-7180-4c5a-aaa7-2af2dfe235a0)
   Bisa kita lihat isi dari file baru itu berurutan sesuai abjad

4. Urutkan file baru dengan cara membelokkan standard input dan standard output ke file baru.urut

   Jawab :

   Untuk mengurutkan file baru dan membelokkannya ke file baru.urut, kita bisa menggunakan command prompt sort < newfile.txt > (nama file baru lagi). Misal, sort <              newfile.txt > filebaru.urut. Kemudian kita ketik cat filebaru.urut untuk melihat isinya
   ![Screenshot from 2024-09-12 09-21-57](https://github.com/user-attachments/assets/44aad206-3c97-4529-aceb-b0eb3f345be1)

5. Urutkan kalimat berikut :

     Jakarta

     Bandung

     Surabaya

     Padang

     Palembang

     Lampung

   Dengan menggunakan notasi here document (<@@@...@@@)

   Jawab :

   
   


