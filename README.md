# MyFriendApp
Aplikasi MyFriendApp adalah aplikasi yang dapat menyimpan data teman dan menampilkannya dalam tampilan list.

Pada aplikasi MyFriendApp memuat:
- [x] Penyimpanan data (database) lokal, yaitu Room
- [x] Komponen view yaitu FloatingActionButton dan RecyclerView
- [x] Penggunaan Fragment

# Penyimpanan Data
Penyimpanan data digunakan untuk menyimpan data teman antara lain, nama, jenis kelamin, nomor telepon, email, dan alamat menggunakan database lokal (Room) dengan menggunakan Data Class. Pada aplikasi MyFriendApp, data class digunakan untuk menampung data diri teman yang kemudian akan ditampilkan dalam tampilan list pada RecyclerView. Untuk menampilkan data dalam tampilan list pada RecyclerView, dibutuhkan sebuah class RecyclerView Adapter.

# Floating Action Button
Floating Action Button (FAB) adalah komponen View dari Material Design berupa Button Floating (mengambang) berbentuk lingkaran. Floating Action Button terdapat pada Android Design Support Library, Floating Action Button pada aplikasi android, berbentuk lingkaran dan akan terlihat seakan mengambang pada Layout atau Activity. Floating Action Button digunakan sebagai indikator utama pada sebuah aplikasi.

# Fragment
Fragment adalah class yang pada umumnya digunakan untuk kebutuhan menampilkan lebih dari satu fitur pada satu halaman. Dengan menggunakan fragment kita dapat membuat banyak tampilan tanpa berpindah-pindah activity. Selain itu kita juga dapat memakai satu fragment dalam banyak Activity sekaligus.

Fragment biasanya dibuat sebagai bagian dari suatu antarmuka. Sebuah fragment harus berada di dalam sebuah activity, mereka tidak dapat berjalan sendiri tanpa adanya activity tempat mereka menempel. Fragment dapat dipakai berulang kali didalam activity. Penggunaan Komponen View dan Logic Berulang Kali pada Fragment dapat dipakai untuk menampilkan data atau melakukan event tertentu dibeberapa activity berbeda. 

# Tampilan awal belum ada data yang ditambahkan
Pada tampilan awal, masih belum ada data yang tersimpan maka hanya terdapat halaman kosong, untuk menambahkan data teman klik tombol "+" pada pojok kanan bawah.

![WhatsApp Image 2020-10-23 at 18 11 41](https://user-images.githubusercontent.com/60589822/96999442-5a89f880-155f-11eb-9158-f067a4ac57db.jpeg)

# Tampilan form pengisian data teman
Setelah menekan tombol "+", maka akan terdapat tampilan form untuk menambahkan teman. Jika data telah diisi seluruhnya tekan simpan.

![WhatsApp Image 2020-10-23 at 18 11 43 (1)](https://user-images.githubusercontent.com/60589822/96999486-6a094180-155f-11eb-8984-ee3ed5f6a3b4.jpeg)

# Tampilan peringatan jika form kosong
Jika terdapat format yang kosong, maka akan muncul peringatan pada format yang belum terisi. Data berhasil tersimpan jika form terisi seluruhnya.

![WhatsApp Image 2020-10-23 at 18 11 42](https://user-images.githubusercontent.com/60589822/96999509-742b4000-155f-11eb-97c3-0a727ec64df1.jpeg)

# Tampilan list data teman
Setelah menekan tombol simpan, jika data berhasil tersimpan maka akan muncul list data yang baru ditambahkan.

![WhatsApp Image 2020-10-23 at 18 11 43](https://user-images.githubusercontent.com/60589822/96999378-434b0b00-155f-11eb-8a2a-0dae61f45e9f.jpeg)
