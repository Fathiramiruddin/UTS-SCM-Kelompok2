kelompok 2:
1. Muh. Nur Fathir Amiruddin
2. Ardiansyah
3. Irma Hangio
4. Alya Cahayani Bilondatu
5. Sitty Khasanah Fadelia Kalapati

Deskripsi Aplikasi

Aplikasi web statis berbasis browser untuk mengelola data biodata mahasiswa. Seluruh logika berjalan di sisi klien (client-side) tanpa memerlukan server atau database eksternal. Data disimpan secara persisten menggunakan localStorage sehingga tetap ada meskipun browser ditutup dan dibuka kembali. Dibangun dengan teknologi web dasar: HTML5, CSS3, dan JavaScript murni.

Fitur Utama
1. Input & Simpan Data
Pengguna dapat menambahkan data mahasiswa berupa Nama, NIM (hanya angka), dan Jurusan (pilihan: TRPL, TI, SI). Data disimpan ke localStorage browser dan otomatis diurutkan secara alfabetis berdasarkan nama.
2. Validasi Data

NIM wajib berupa angka; jika tidak, muncul peringatan.
NIM yang sudah terdaftar tidak bisa diinput ulang (mencegah duplikasi).

3. Tampilkan & Filter Data

Data ditampilkan dalam tabel dengan nomor urut, nama, NIM, jurusan, dan aksi.
Tersedia fitur pencarian real-time berdasarkan nama atau NIM.
Tersedia filter berdasarkan jurusan.
Menampilkan jumlah total data yang tampil.

4. Edit & Hapus Data

Setiap baris tabel memiliki tombol Edit (mengisi ulang form) dan Hapus (dengan konfirmasi).
Tersedia tombol Hapus Semua untuk mengosongkan seluruh data.

5. Export CSV
Data dapat diekspor ke file .csv yang bisa dibuka di Excel atau aplikasi spreadsheet lainnya.
6. Dark Mode
Terdapat tombol toggle 🌙 untuk beralih ke tampilan gelap (dark mode).

