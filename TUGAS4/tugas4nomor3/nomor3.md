1. lakukan instalasi bind9
![alt text](<Screenshot 2024-03-24 153949.png>)
2. cek instalasi di /etc/bind
![alt text](image.png)
3. cek konfigurasi utama bind di named.conf.
![alt text](image-1.png)
4. Menambahkan ACL (access list), control, dan include 3 file.
![alt text](image-2.png)
5. Buka named.conf.deafult-zones.
![alt text](image-3.png)
6. Buka named.conf.option, mengisi provider dan listen-on. Listen ditambahkan sesuai kelompok masing-masing
![alt text](image-4.png)
7. Buka named.conf.local, untuk mengset atau konfigurasi zone file. Melakukan pengubahan zone sesuai nama kelompok.
![alt text](image-5.png)
8. Lakukan sudo named-checkconf untuk mengeck pesan error. jika tidak ada pesan error yang keluar itu berarti konfigurasi yang dilakukan telah benar.
![alt text](image-9.png)
9. Pergi ke arah configuration zone file. 
![alt text](image-7.png)
10. Masuk ke zone file pertama dan mengubah data di dalamnya.
![alt text](image-8.png)
11. Masuk ke zone file kedua (.inv) untuk mengubah data seperti file sebelumnya.
![alt text](image-10.png)
12. Jalankan sudo systemctl restart named untuk menjalankan sistem bind.
![alt text](image-11.png)
13. Cek status bind apakah running atau tidak.
![alt text](image-15.png)
14. Cek apakah port terbuka atau tidak.
15. Gunakan perintah dig.
![alt text](image-14.png)
![alt text](image-12.png)
16. Gunakan perintah nslookup.
![alt text](image-13.png)
