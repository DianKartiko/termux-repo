## Halo semua hari ini saya akan belajar nmap di termux dan beberapa command yang disupport oleh termux itu sendiri.

1. `nmap <host>` contoh `nmap 192.168.1.1` : Memiliki kegunaan untuk scanning host tunggal.
2. `nmap -sn <host_discovery>` contoh `nmap -sn 192.168.1.0/24` : Berguna untuk scanning host yang aktif dijaringan tersebut.
3. `nmap -Pn <host>` contoh `nmap -Pn 192.168.1.1` : Menganggap target hidup untuk host yang block imcp.
4. `nmap <range host>` contoh `nmap 192.168.1.1-50` atau `nmap 192.168.1.*` : Untuk scanning host tertentu atau bahkan seluruhnya.
5. `nmap -il target.txt` : Scanning banyak port yang dibaca dari file.
