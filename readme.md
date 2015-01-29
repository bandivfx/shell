# Terminal Cheatsheet

| Perintah                  | Fungsi                                                                           | Contoh                                |
| :-----------------------: | -------------------------------------------------------------------------------- | :-----------------------------------: |
| date                      | Menampilkan tanggal sekarang.                                                    | date                                  |
| cal                       | Menampilkan kalender.                                                            | cal                                   |
| df                        | Menampilkan penggunaan disk drives.                                              | df                                    |
| free                      | Menampilkan penggunaan memory.                                                   | free                                  |
| exit                      | Keluar dari terminal.                                                            | exit                                  |
| pwd                       | Menampilkan direcktori saat ini.                                                 | pwd                                   |
| ls                        | Menampilkan daftar file pada direktori.                                          | ls                                    |
| cd                        | Pindah direktori.                                                                | cd ~                                  |
| file                      | Menampilkan tipe suatu file.                                                     | type file.txt                         |
| less                      | Menampilkan konten suatu file.                                                   | less file.txt                         |
| cp                        | Menyalin suatu file atau direktori (cp -R).                                      | cp file.txt                           |
| mkdir                     | Membuat direktori baru.                                                          | mkdir folder                          |
| mv                        | Memindahkan suatu file atau direktori.                                           | mv folder folder_baru                 |
| rm                        | Menghapus suatu file atau direktori (rm -R).                                     | rm file.txt                           |
| type                      | Menampilkan tipe perintah.                                                       | type cd                               |
| which                     | Menampilkan letak file executable.                                               | which mv                              |
| help                      | Menampilkan bantuan                                                              | help cd                               |
| man                       | Menampilkan manual suatu perintah.                                               | man ls                                |
| apropos                   | Menampilkan daftar perintah yang sesuai berdasarkan manual.                      | apropos "remove files"                |
| whatis                    | Menampilkan deskripsi perintah dalam satu baris.                                 | whatis ls                             |
| info                      | Menampilkan halaman info perintah.                                               | info ls                               |
| alias                     | Membuat alias untuk perintah.                                                    | alias susu="sudo su"                  |
| unalias                   | Menghapus alias perintah.                                                        | unalias susu                          |
| cat                       | Menyatukan isi file dan menampilkan pada output standar.                         | cat file.txt                          |
| sort                      | Mengurutkan baris file text.                                                     | sort file.txt                         |
| uniq                      | Melaporkan atau menghapus garis yang berulang.                                   | uniq file.txt                         |
| wc                        | Menampilkan jumlah baris, jumlah kata dan ukuran file (dalam byte).              | wc file.txt                           |
| grep                      | Menampilkan baris yang cocok dengan pattern.                                     | ls &#124; grep heru                   |
| head                      | Menampilkan 10 baris pertama suatu file.                                         | head file.txt                         |
| tail                      | Menampilkan 10 baris terakhir suatu file.                                        | tail file.txt                         |
| tee                       | Mengambil output dari perintah kemudian memasukkan ke file.                      | ls &#124; tee file.txt                |
| echo                      | Menampilkan teks pada terminal.                                                  | echo "tes"                            |
| clear                     | Membersihkan layar terminal.                                                     | clear                                 |
| history                   | Menampilkan history perintah.                                                    | history                               |
| id                        | Menampilkan ID dari user dan group.                                              | id                                    |
| chmod                     | Merubah permission suatu file atau direktori.                                    | chmod 755 file.txt                    |
| umask                     | Set default permission.                                                          | umask 0000                            |
| su                        | Rubah sebagai root (super user).                                                 | su                                    |
| sudo                      | Menjalankan perintah sebagai root (super user).                                  | sudo chmod 777 file.txt               |
| chown                     | Rubah pemilik suatu file.                                                        | chown heru file.txt                   |
| chgrp                     | Rubah pemilik grup.                                                              | chgrp admin file.txt                  |
| passwd                    | Rubah password user.                                                             | passwd                                |
| ps                        | Menampilkan snapshot dari proses saat ini.                                       | ps                                    |
| pstree                    | Menampilkan snapshot dari proses saat ini dalam bentuk tree view.                | pstree                                |
| top                       | Menampilkan proses yang sedang berjalan.                                         | pos                                   |
| jobs                      | Menampilkan proses yang dijalankan dari terminal.                                | jobs                                  |
| bg                        | Memindahkan proses ke background.                                                | bg %1                                 |
| fg                        | Memindahkan proses ke foreground.                                                | fg %1                                 |
| kill                      | Menghentikan proses berdasarkan PID.                                             | kill 12345                            |
| killall                   | Menghentikan semua proses berdasarkan pattern.                                   | killall git                           |
| vmstat                    | Menampilkan system resource (memory, swap dan disk I/O).                         | vmstat                                |