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

5. Buatlah direktori Latihan6 sebanyak 2 kali dan belokkan standard error ke file rmdirerror.txt

   Jawab :

   Pertama-tama kita buat direktori Latihan6 sebanyak 2 kali dengan menggunakan command prompt mkdir
   ![Screenshot from 2024-09-12 09-25-14](https://github.com/user-attachments/assets/9ff2865a-fef5-481b-b13d-16d503da4a55)
   Lalu kita akan membelokkan standard error nya ke file rmdirerror.txt. Caranya kita ketik mkdir Latihan6 2> rmdirerror.txt (angka 2 itu merujuk pada stream standard           error). Kemudian kita ketik cat rmdirerror.txt untuk melihat isinya
   ![Screenshot from 2024-09-12 09-25-29](https://github.com/user-attachments/assets/ed86239d-2ac1-4e77-87e7-5cd477658b37)

6. Urutkan kalimat berikut :

     Jakarta

     Bandung

     Surabaya

     Padang

     Palembang

     Lampung

   Dengan menggunakan notasi here document (<@@@...@@@)

   Jawab :

   Untuk mengurutkan kalimat diatas dengan menggunakan notasi yang sudah disebutkan, caranya adalah kita ketik sort <@@@, lalu kita enter. Kemudian kita ketik kalimat-          kalimat diatas, dan diakhiri dengan @@@
   ![Screenshot from 2024-09-12 09-34-23](https://github.com/user-attachments/assets/fe544aa4-d663-4e7f-afa9-5e8e8c5f9aa5)

7. Hitung jumlah baris, kata dan karakter dari filebaru.urut dengan menggunakan filter dan tambahkan data tersebut ke file baru

   Jawab :

   Untuk menghitung jumlah baris, kata dan karakter dari filebaru.urut, kita bisa menggunakan command prompt wc. Caranya kita ketik wc filebaru.urut. Lalu kita ingin            menambahkan data tersebut ke file baru. Caranya kita ketik wc filebaru.urut >> (nama file baru lagi). Misal, wc filebaru.urut >> baru.txt. Kemudian kita ketik cat            baru.txt untuk melihat isinya
   ![Screenshot from 2024-09-12 09-39-07](https://github.com/user-attachments/assets/565ec8a3-de99-4fef-8915-b1f06f0c002d)

8. Gunakan perintah dibawah ini dan perhatikan hasilnya.

   $ cat /etc/passwd | sort | pr -n | grep tty03

   $ find /etc -print | head

   $ head /etc/passwd | tail -5 | sort

   Jawab :

   ![Screenshot from 2024-09-12 09-43-06](https://github.com/user-attachments/assets/77cfddcd-07a6-45a9-8714-d9b967170209)
   Penjelasan :

   - cat /etc/passwd | sort | pr -n | grep tty03

     Untuk menampilkan isi dari file /etc/passwd, kemudian diurutkan menggunakan command sort, lalu di beri nomor baris menggunakan command pr -n, dan mencari baris yang         berisi tty03. Tapi dikarenakan tidak ada baris tty03, maka tidak ada output yang keluar

   - find /etc -print | head
  
     Untuk mencari semua file, direktori dan subdirektori yang ada didalam /etc, kemudian menampilkan 10 baris pertama yang ditemukan menggunakan command head

   - head /etc/passwd | tail -5 | sort
  
     Untuk menampilkan 10 baris pertama dari file /etc/passwd, lalu mengambil 5 baris terakhir dari output head menggunakan command tail -5, lalu mengurutkannya

9. Gunakan perintah $ who | cat | cat | sort | pr | head | cat | tail dan perhatikan hasilnya

   Jawab :

   ![Screenshot from 2024-09-12 09-44-20](https://github.com/user-attachments/assets/ea56c2f2-279f-48c2-91b4-ea10eda852f4)
   Command who untuk menampilkan pengguna yang sedang login. Lalu, output who diteruskan melalui dua kali cat, yang tidak mengubah data namun menambah beberapa langkah        tambahan. Kemudian, data tersebut diurutkan dengan sort, dan hasilnya diformat untuk pencetakan menggunakan pr. Setelah itu, head menampilkan 10 baris pertama dari          output yang sudah diformat. Output dari head kemudian diteruskan ke cat, yang tidak mengubahnya, dan akhirnya tail menampilkan 10 baris terakhir dari hasil tersebut.        Secara keseluruhan, Command diatas menghasilkan output yang sama dengan hasil dari head sebelum diteruskan ke tail




