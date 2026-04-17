LAPORAN PRAKTIKUM UTS MANAJEMEN KONFIGURASI
KELOMPOK 2

Anggota Kelompok:
1.	Muh. Nur Fathir Amiruddin (1521424017)
2.	Ardiansyah (1521424005)
3.	Irma Hangio (1521424009)
4.	Alya Cahayani Bilondatu (1521424013)
5.	Sitty Khasana Fadelia Kalapati (1521424016)
Mata Kuliah : Manajemen Konfigurasi 
Dosen Pengampu : Hanifah Mardlatillah, S.Kom, M.Kom 
1.	PEMBAGIAN TUGAS ANGGOTA :
A.	Muh. Nur Fathir Amiruddin : Sebagai Owner Dari Repository, Yang Bertanggung Jawab Untuk Mengatur Struktur Folder, Menambahkan Fitur Tombol Riset Sekaligus Menggabungkan Fitur Biodata Ke Main Juga Menyelesaikan Proses Penggabungan Yang Tertunda.
B.	Irma Hangio : Menambahkan Fitur Crud, Serta Memperbaiki Logika Pada Program, Bertanggung Jawab Pada Kesalahan Logika Pada Sistem, Menggabungkan Fitur Ke Main
C.	Alya Cahayani Bilondatu : Bertanggung Jawab Untuk Penambahan Fitur Baru Pada Sistem, Menambahkan Fitur Search, Menambahkan Fitur Localstorage, Bertanggung Jawab Untuk Penyempurnaan Tampilan Sistem.
D.	Sitty Khasana Fadelia Kalapati : Membuat Readme.Md, Juga Bertanggung Jawab Pada Readme.Md, Menambahkan Filter Jurusan Dan Memperbaiki Fitur Edit.
E.	Ardiansyah : Menambahkan Fitur Export JSON Export Feature Sebagai Backup Data Mahasiswa.



2.	ALUR KERJA GIT : 
A.	CLONING REPOSITORY : Setiap anggota kelompok melakukan repository ke laptop masing masing (Lokal).
B.	PENGGUNAAN BRANCH UTAMA (MAIN) : Repositori menggunakan branch main sebagai pusat kode utama yang stabil. Semua hasil akhir dari tugas masing-masing anggota tim pada akhirnya akan bermuara dan disatukan di branch ini.
C.	ISOLASI FITUR DENGAN BRANCH BARU : Untuk setiap penambahan fitur, perbaikan, atau pembaruan tampilan, anggota kelompok tidak langsung mengubah kode di main. Kami membuat branch baru yang spesifik dan terpisah. Hal ini dibuktikan dengan pembuatan berbagai branch seperti feature-reset, feature-sinkronisasitotaldata, feature-mengupdatetampilan, feature-menambahfiturbaru, dan menambah-fitur.
D.	PROSES COMMIT TERSTRUKTUR : Setiap anggota kelompok melakukan commit secara berkala pada branch masing-masing. Kami menggunakan pesan commit yang deskriptif untuk melacak riwayat perubahan secara jelas (contoh: feat: tambah filter jurusan dan perbaikan fitur edit, menambahkan fitur CRUD, menambahkan fitur localstorage, hingga update penyempurnaan tampilan tabel).
E.	PULL REQUEST (PR) DAN PENGGABUNGAN (MERGE) : Setelah sebuah fitur pada branch terpisah selesai dikerjakan, langkah selanjutnya adalah mengajukan Pull Request agar dapat diintegrasikan. Setelah dipastikan aman dan tidak ada konflik fatal, branch fitur tersebut digabungkan (merge) ke branch main. Bukti dari proses ini terlihat pada riwayat commit di main seperti "menyelesaikan penggabungan fitur biodata ke main" dan "merge: menyelesaikan sinkronisasi dengan repo remote"






3.	DOKUMENTASI TANGKAPAN LAYAR (SCREENSHOT) : 
A.	Branch Yang Digunakan
Screenshot ini menampilkan daftar branch yang tersedia pada repositori lokal. 
 
B.	Proses Merge
Screenshot ini memperlihatkan proses penggabungan (merge) feature branch ke branch main, melalui Git Bash maupun GitHub. 
1.	Melakukan merge dari branch menambahan-fungsi ke branch main.
 
 
 
 
 
 
 
2.	Melakukan merge dari branch feature-MengupdateTampilan ke branch main.
 
 
 
3.	Melakukan merge dari branch feature-Sinkronisasitotaldata ke branch main.
 
4.	Hasil Merge
 
Gambar di atas merupakan tangkapan layar dari tab Pull Requests pada repository GitHub. Tampilan ini membuktikan bahwa penggabungan kode (merge) dari masing-masing anggota tim dilakukan melalui mekanisme yang terkontrol dan tidak dilakukan secara sembarangan. Berdasarkan gambar di atas, dapat diuraikan beberapa poin berikut:
a.	Pull Request Aktif (1 Open): Terdapat satu pengajuan integrasi kode yang sedang berjalan dengan judul "mengupdate table lebih rapi + ada efek hover". Pengajuan ini dibuat oleh kolaborator tim (Alya). Status Open berarti perubahan kode dari branch fitur tersebut sedang diajukan dan menunggu proses peninjauan (code review) atau persetujuan sebelum akhirnya digabungkan ke branch utama (main).
b.	Riwayat Pull Request (1 Closed): Terdapat keterangan 1 Closed yang menandakan bahwa sebelumnya tim telah berhasil memproses dan menyelesaikan satu Pull Request lain (baik itu sudah berhasil di-merge ke branch utama atau ditutup).
c.	Validasi Kolaborasi: Adanya label Collaborator pada identitas pengaju mempertegas bahwa repository ini dikerjakan secara berkelompok dengan pembagian tugas masing-masing.


C.	Git Log
  
Gambar di atas menampilkan hasil eksekusi perintah git log yang membuktikan bahwa riwayat perubahan kode telah terekam secara sistematis. Informasi utama yang dapat dilihat dari log ini meliputi:
1.	Commit Hash (ID): Kode identitas unik (contoh: c2f16be...) untuk melacak setiap iterasi perubahan.
2.	Posisi & Sinkronisasi: Keterangan (HEAD -> main, origin/main...) menunjukkan bahwa posisi saat ini berada di branch main dan kode di komputer lokal sudah tersinkronisasi dengan repositori GitHub.
3.	Author & Date: Mencatat identitas pengembang dan waktu spesifik saat commit dilakukan.
4.	Commit Message: Deskripsi singkat mengenai apa yang dikerjakan pada commit tersebut (contoh: "menambahkan tombol reset untuk mengosongkan form biodata 


D.	Branch Yang Digunakan

 
Pengembangan proyek ini menerapkan metode percabangan (branching) untuk mengisolasi pengerjaan setiap fitur agar tidak mengganggu stabilitas kode utama. Berdasarkan daftar branch pada repository, struktur yang digunakan meliputi:
1.	Branch Utama (main) : Berfungsi sebagai branch pusat yang menampung versi kode final, stabil, dan siap digunakan.
2.	Branch Fitur (Feature Branches): Anggota tim membuat branch terpisah dari main untuk mengerjakan tugas spesifik secara paralel. Contoh branch yang digunakan antara lain feature-reset, feature-sinkronisasitotaldata, feature-mengupdatetampilan, dan feature-menambahfiturbaru.
Penggunaan branch yang terpisah ini membuktikan bahwa tim menerapkan kolaborasi kode yang terstruktur, di mana pengerjaan satu fitur tidak akan merusak fitur lain yang sedang dikerjakan.
E. Kendala yang Dialami 
Kendala yang dialami itu adalah waktu awal membuat file index.html dan style.css, kami lupa untuk membuat folder src dan folder docs, sehingganya kami nanti sadar itu ketika file index.html dan style.css telah terbuat, akhirnya kami membuat folder src dan memindahkan file tersebut ke folder src.
Kendala lain yang di alami yaitu, adanya miss komunikasi antara anggota sehingganya kami kewalahan karena struktur pembagian tugas yang sedikit acak, juga struktur alur pengerjaan git yang sedikit acak 
