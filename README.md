Belajar Vim di Termux

===== Bagian 1 =====
Vim Introduction, mempelajari mode vim dan juga basic command.

1. Vim memiliki beberapa mode, yang saat ini diketahui ada 2 yaitu mode normal dan insert.
2. Untuk mengakses vim, perlu mengetikkan perintah `vim <file>` atau `vim <dir>`.
3. Untuk keluar vim ketik `:q`.
4. Untuk masuk insert mode ketik `i`.
5. Keluar insert mode press `esc`.
6. Untuk menyimpan perubahan text atau kode pencet `wq` untuk write and quit.
7. Untuk undo atau membatalkan perubahan ketik `:u`.


===== Bagian 2 =====
Explore normal mode and command mode.

NORMAL MODE

1. Press X untuk menghapus setiap karakter.
2. Press U untuk undo setiap karakter yang dihapus.
3. Press DD untuk menghapus satu baris kode atau text.
4. Press H untuk arrow left.
5. Press J untuk arrow down.
6. Press K untuk arrow up.
7. Press L untuk arrow right.

COMMAND MODE 

1. Press `:r <file>` untuk read file, bisa digunakan untuk menggabungkan kode seperti fitur github.
2. Press `:w <nama_file>` untuk write file, bisa digunakan untuk update kode yang digabungkan dan disimpan di nama file baru.
3. Press `! <command>` untuk menggunakan command lain tanpa membuka terminal tambahan.
