# labpy02
# Latihan 1 Membuat program menentukan nilai akhir
![Screenshot (27)](https://github.com/user-attachments/assets/d73f1625-3fd2-43a1-9dda-ddac48f9b791)

Input Data:
 - Kode ini meminta pengguna untuk memasukkan nilai tugas, UTS (Ujian Tengah Semester), dan UAS (Ujian Akhir Semester).
   
Penentuan Keterangan Lulus atau Tidak:
 - Jika nilai akhir lebih dari 60, maka keterangan akan menjadi "LULUS", jika tidak akan menjadi "TIDAK LULUS".

Penentuan Nilai Huruf:
 -  Nilai huruf diberikan berdasarkan rentang nilai akhir:
A jika lebih dari 80 B jika lebih dari 70 C jika lebih dari 50 D jika lebih dari 40 E jika di bawah atau sama dengan 40

# Latihan 2 Membuat program menampilkan status gaji karyawan
![Screenshot (28)](https://github.com/user-attachments/assets/89742012-afac-42fa-b66e-dddca947c168)

Input Data:
 - Kode ini meminta pengguna untuk memasukkan gaji, status keluarga, dan kepemilikan rumah. Variabel gaji menyimpan nilai gaji sebagai integer. Variabel berkeluarga akan bernilai True jika pengguna memasukkan "Y" (sudah berkeluarga) dan False jika "T". Variabel punya_rumah akan bernilai True jika pengguna memasukkan "Y" (punya rumah) dan False jika "T".

Pengecekan Gaji:
 - Jika gaji lebih dari 3.000.000, maka program akan mencetak "Gaji sudah di atas UMR". Jika tidak, program akan langsung mencetak "Gaji belum UMR" pada bagian else.

Pengecekan Status Keluarga: 
 - Jika berkeluarga bernilai True, program akan menampilkan "Wajib ikutan asuransi dan menabung untuk pensiun". Jika berkeluarga bernilai False, program akan menampilkan "Tidak perlu ikutan asuransi". Pengecekan

Kepemilikan Rumah:
 - Jika punya_rumah bernilai True, program akan menampilkan "Wajib bayar pajak rumah". Jika punya_rumah bernilai False, program akan menampilkan "Tidak wajib bayar pajak rumah".

Gaji di Bawah UMR: 
 - Jika gaji tidak lebih dari 3.000.000, program akan langsung menampilkan "Gaji belum UMR" tanpa melakukan pengecekan tambahan.

Hasil Program: 
 - Pada contoh output di sisi kanan gambar, jika gaji 80.000.000, status berkeluarga "T", dan punya rumah "Y": Program menampilkan bahwa gaji di atas UMR. Menampilkan bahwa pengguna Tidak perlu ikutan asuransi
Tidak wajib bayar pajak rumah

# Latihan 3 Penggunaan kondisi or program membandingkan 3 input bilangan, apabila penjumlahan 2 bilangan hasilnya sama dengan bilangan lainnya, maka cetak pernyataan "BENAR"
![Screenshot (30)](https://github.com/user-attachments/assets/b220d617-0301-4f0b-b588-1726fd332a79)

Input Data:
 - Kode ini meminta pengguna untuk memasukkan tiga bilangan: a, b, dan c. Input dari pengguna dikonversi ke tipe int agar dapat digunakan dalam operasi aritmatika.

Pengecekan Kondisi:
 - Kode ini mengecek apakah salah satu dari tiga bilangan (a, b, atau c) dapat merupakan hasil penjumlahan dari dua bilangan lainnya. Pada contoh output di sebelah kanan gambar: Jika a = 30, b = 20, dan c = 10, maka ada kondisi yang terpenuhi, sehingga hasilnya adalah "BENAR".

# Latihan 3 Kasus 1 pemesanan tiket bioskop

program ini dijalankan untuk menghitung total harga tiket bioskop. Program ini meminta input dari user untuk tipe tiket (reguler atau VIP) dan status member (memiliki kartu member atau tidak).

Berikut adalah langkah-langkah program:

Mendefinisikan harga tiket:
 - harga_tiket_reguler: Harga tiket reguler didefinisikan sebesar 50000 harga_tiket_vip: Harga tiket VIP didefinisikan sebesar 100000 diskon_member: Besar diskon untuk member didefinisikan sebesar 0.20 (20%)

Meminta input dari user:
 - Program meminta user untuk memasukkan tipe tiket (reguler/vip) dan menyimpannya ke dalam variabel tipe_tiket. Program meminta user untuk memasukkan status member (ya/tidak) dan menyimpannya ke dalam variabel status_member. Kedua input dari user diubah menjadi huruf kecil menggunakan fungsi lower().

 Menghitung harga tiket berdasarkan tipe:
  - Program memeriksa nilai tipe_tiket: Jika tipe_tiket adalah "reguler", maka harga_tiket diset menjadi harga_tiket_reguler. Jika tipe_tiket adalah "vip", maka harga_tiket diset menjadi harga_tiket_vip. Jika tipe_tiket bukan "reguler" atau "vip", maka program menampilkan pesan "Tipe tiket tidak valid" dan keluar dari program.

Mengecek status member untuk diskon: 
 - Program memeriksa nilai status_member: Jika status_member adalah "ya", maka total_harga dihitung dengan rumus harga_tiket * (1 - diskon_member), yang memberikan diskon kepada member. Jika status_member bukan "ya", maka total_harga diset sama dengan harga_tiket tanpa diskon.

 Menampilkan total harga yang harus dibayar:
  - Program menampilkan total harga yang harus dibayar dengan format "Total harga yang harus dibayar: Rp(total_harga)" menggunakan fungsi print().
    



