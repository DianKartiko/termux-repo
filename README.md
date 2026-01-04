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
8. Press gg untuk langsung di atas.
9. Press `shift + g` untuk kebawah.
COMMAND MODE 

1. Press `:r <file>` untuk read file, bisa digunakan untuk menggabungkan kode seperti fitur github.
2. Press `:w <nama_file>` untuk write file, bisa digunakan untuk update kode yang digabungkan dan disimpan di nama file baru.
3. Press `! <command>` untuk menggunakan command lain tanpa membuka terminal tambahan.

==== Bagian 3 ====

Buffers

Seperti halnya text editor anggap saja kita bisa menggunakan beberapa command untuk berpindah tab

COMMAND

1. Press `:e <nama_file>` untuk berpindah ke buffer yang sesuai dengan namanya
2. Press `:bp` untuk buffer previous dimana kita akan berpindah di buffer sebelumnya
3. Press `:bn` untuk buffer next dimana aka berpindah di buffer selanjutnya

==== Bagian 4 ====

Visual Mode 

Terdapat mode baru yaitu adalah mode visual dimana kita bisa highlight kode atau text.

Copy : Highlight code dan press `y` untuk yank.
Paste : Tuju line yang ingin di paste, keluar dari visual mode dan press `p` untuk paste.

COMMMAND MODE 

Press `:'<,'>sort ui` untuk sorting text atau code setelah di highlight dengan visual mode
Press `:%s/<nama_variable>/<nama_ganti>/g` untuk replace nama variabel

==== Bagian 5 ====

Splitting Windows

COMMAND 

Press `split <nama_file>` atau `sp <nama_file>` Untuk menggunakan split windows.
Press `ww` untuk berpindah cursor
Press `vsplit <nama_file>`atau `vs <nama_file>` untuk vertical split.

==== Bagian 6 ====

Configuration

C0MMAND
Press `:set number` untuk memberi editing number line.
Press `:set nonumber` untuk menghilangkan editing number line.
Type `vim -o <nama_file> <nama_file>` untuk langsung masuk dengan split horizontal,
Type `vim -O <nama_file> <nama_file>` uuntuk langsung masuk dengan split vertikal.
CONFIG
Masuk dengan type `vim .vimrc` untuk configuration file. Masukkan configuration yang dibutuhkan disana.


