# Cloth-Mask-Vending-Machine-Assembly-
Dalam proyek akhir ini, kami Kelompok BeagleBoneBlack dari kelas SBK - 02 Program Studi Teknik Komputer Departemen Teknik Elektro Fakultas Teknik Universitas Indonesia berusaha untuk menerapkan beberapa topik kuliah terkait, seperti The 8051 Microcontroller &amp; Hardware Connection, 8051 Assembly Language Programming, Jump, Loop and Call Instructions, I/O Port Programming, 8051 Addressing Modes, Arithmetic &amp; Logic Instructions, Timer Programming, serta Serial Programming [2]. Input dari mesin vending machine ini adalah nomor NPM pembeli masker yang akan dimasukkan oleh pembeli dengan Matrix Keypad. Untuk outputnya, vending machine ini memiliki 3 buah perangkat keras output, yaitu 16X2 LCD, LED Dot Matrix, dan Servo Motor. 16X2 LCD dan LED Dot Matrix akan menampilkan informasi apakah pembeli berhasil mendapatkan masker kain atau tidak. Sementara itu, Servo Motor akan menggerakan masker kain, sehingga masker tersebut bisa diperoleh dan digunakan oleh pembeli dari vending machine tersebut untuk mencegah penularan virus COVID-19. Langkah-langkah pembelian masker kain dengan vending machine ini adalah sebagai berikut. Pertama, pembeli akan memasukkan NPM dengan menggunakan Matrix Keypad. Input pembeli tersebut akan diperiksa dan dicocokkan dengan data yang ada di dalam RAM. Jika input yang dimasukkan oleh pembeli sama dengan data yang ada di dalam RAM, maka Servo Motor motor akan digerakkan dan masker akan diterima oleh pembeli. Selain itu, terdapat juga  tulisan yang menandakan bahwa masker berhasil diperoleh pada 16X2 LCD serta simbol O pada LED Dot Matrix. Jika input yang dimasukkan oleh pembeli tidak sama dengan data yang ada di dalam RAM, maka akan terdapat tulisan yang menandakan bahwa input pembeli salah pada 16X2 LCD serta simbol X pada LED Dot Matrix.
