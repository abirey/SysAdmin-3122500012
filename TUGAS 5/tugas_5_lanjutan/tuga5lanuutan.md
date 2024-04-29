Setting DHCP
1. Buka DHCP
![alt text](image.png)

2. Pilih bridge1
![alt text](image-1.png)

3. Masukkan Address Space
![alt text](image-2.png)

4. Masukkan gateway 
![alt text](image-3.png)

5. Masukkan addresses to give out
![alt text](image-4.png)

6. Masukkan DNS server
![alt text](image-5.png)

7. Masukkan lease time
![alt text](image-6.png)

8. Cek Koneksi
![alt text](image-7.png)

9. Ubah adapter 1
![alt text](image-8.png)

Percobaan
10. Ping kelompok lain
![alt text](image-9.png)

11. Ubah forwarders, allow-transfer, allow-query, allow-recursion, dan listen-on.
![alt text](image-10.png)

12. Ubah nameserver menjadi 192.168.2.10 di resolv.conf 
![alt text](image-11.png)

13. Ubah connection menjadi static
![alt text](image-12.png)

14. Jalankan perintah /var/lib/bind$ nslookup -q=MX kelompok2.local
![alt text](image-13.png)

15. Tes kirim dan receive email ke kelompok lain
![alt text](image-14.png)

16. Ping 1.1.1.1
![alt text](image-15.png)