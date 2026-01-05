Belajar 50 basic commmand linux

==== Manajemen File dan Direktori ====
1. pwd - Untuk menampilkan direktori saat ini (Print Working Directory)
2. ls - Untuk menampilkan isi dari directory
3. ls -l - Untuk menampilkan detail file seperti izin, ukuran, dll.
4. ls -a - Untuk menampilkan file tersembunyi
5. cd [nama] - Untuk berpindah direktori
6. cd .. - Untuk keluar dari direktori 1 tingkat
7. cd ~ - Untuk menuju home direktori
8. mkdir [nama] - Untuk membuat direktori baru
9. rmdir [nama] - Untuk mmenghapus direktori 
10. touch [file] - Untuk membuat file baru
11. cp [sumber] - Untuk menyalin file/direktori
12. mv [sumber] [tujuan] - untuk memindah file atau mengganti nama file
13. rm [file] - untuk menghapus file
14. rm -r [direktori] - Menghapus direktori beserta isinya.
15. cat [file] - menampilkan isi dari file

==== Membaca dan memproses file ====
16. less [file] - Membaca file dari halaman perhalaman
17. head [file] - Menampilkan 10 baris pertama
18. tail [file] - Menampilkan 10 baris terakhir
19. tail -f [file] - Menampilkan update file secara realtime
20. nano [file] - Untuk membuka nano text editor.
21. vim [file] - Untk membuka vim text editor.
22. grep "pattern" [file] - Mencari teks dalam file
23. ws [file] - Menghitung baris, kata, karakter.

==== Sistem Informasi ====
24. whoami - Menampilkan siapa username saat ini 
25. uname -a - Menampilkan informasi sistem kernel
26. top/htop - Monitor proses dan resource system.
27. ps aux - Menampilkan semua proses yang saat ini tengah berjalan
28. kill [PID] - Mengehentikan proses dengan proses ID
29. df -h - Menampilkan penggunaan disk (human readable)
30. du -sh [direktori] - Menampilkan ukuran dari direktori
31. free -h - Menampilkan pengguaan memori
32. date - Menampilkan tanggal dan waktu saat ini

==== Permission ====

33. chmod [izin] [file] - Mengubah izin file (contoh: `chmod 755 file.txt`)
34. chown [user]:[group] [file] - Mengubah kepemilikan file
35. sudo [perintah] - Menjalankan perintah sebagai superuser
36. su [username] - Beralih user (switch user)

==== Manajemen Paket ====
37. apt updat - Update daftar paket
38. apt upgrade - Upgrade paket yang terinstall
39. apt install [paket] - Install paket
40. apt remove [paket] - menghapus paket

==== Networking ====
41. ping [host] - Untuk cek koneksi ke host
42. ifconfig/ip addr - Menampilkan konfigurasi jaringan
43. curl [URL] - Transfer data dari/ke server
44. wget [URL] - Mengunduh file dari internet


==== Pencarian ====
45. find [direktori] -name "nama" - Mencari file berdasarkan nama
46. located [file] - Mencari file dengan menggunakan database
47. which [perintah] - Menampilkan lokasi dari perintah

==== Hal lain-lain ===
48. history - Menampilkan riwayat dari perintah
49. clear/CTRL + L - Membersihkan terminal
50. man [perintah] - Manual book utuk perintah.


