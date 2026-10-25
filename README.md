# Sistem Manajemen Perpustakaan Kampus

Program berbasis Java yang dirancang untuk membantu pengelolaan perpustakaan kampus, mulai dari menampilkan kategori dan daftar buku, melihat data peminjaman, mengetahui lokasi penyimpanan buku, hingga mengelola riwayat transaksi dan antrean mahasiswa. Program ini dibuat sebagai implementasi enam struktur data dalam mata kuliah Pemrograman Berorientasi Objek.

---
## Tugas Pemrograman Java

- Mata Kuliah: Pemrograman Berorientasi Objek
- Dosen Pengampu: M. Ibadurrahman Arrasyid Supriyanto, M.Kom.
- Program Studi: Sistem Informasi
- Angkatan: 2025
- Kelompok: 27

---
## Anggota Kelompok 27

1. Selvi Bella Dwi Anita - [2509116053] - [Kelas B]
2. Nabila Salma Putri - [2509116053] - [Kelas B]
3. Daffa Rizqi Fadhillah - [2509116068] - [Kelas B]
4. Siti Nursinta - [2509116087] - [Kelas C]

---
## Struktur File Proyek

``` java
SistemManajemenPerpustakaan/
├── pom.xml                        # File konfigurasi utama Apache Maven (Library & Build)
└── src/                           # Folder utama Source Code
    └── main/
        └── java/
            └── com/
                └── mycompany/
                    └── sistemmanajemenperpustakaan/
                        └── SistemPerpustakaan.java  # File utama (Main Class) berisi 6 struktur data
├── README.md                      # Dokumentasi proyek 
```

---
## Fitur Program

1. Kategori Buku (Array 1D)

   Menampilkan daftar kategori buku, seperti Pemrograman, Matematika, Jaringan Komputer, dan Basis Data.

   <img width="352" height="282" alt="image" src="https://github.com/user-attachments/assets/4d2d9627-e18c-489b-a42f-c3259300981d" />

---
2. Pengelolaan Daftar Buku (ArrayList)

   Menampilkan, menambahkan, dan menghapus buku secara dinamis.

   ---
   - Tampilkan Buku

     <img width="358" height="416" alt="image" src="https://github.com/user-attachments/assets/59eea1d6-5e59-46c7-9347-dc525c14228d" />

   ---
   - Tambah Buku
  
     <img width="325" height="128" alt="image" src="https://github.com/user-attachments/assets/19f38e23-da54-44b2-92af-35d7fc2cda24" />

   ---
   - Hapus Buku

     <img width="301" height="257" alt="image" src="https://github.com/user-attachments/assets/b5572534-ba5f-42a6-93f7-58c63400b5fd" />

---
3. Data Peminjaman (Array 2D)

   Menyimpan dan menampilkan jumlah peminjaman buku berdasarkan kategori dan hari dalam satu minggu.

   <img width="668" height="307" alt="image" src="https://github.com/user-attachments/assets/d3a70d89-033c-4907-a475-7cc3aee867de" />

---
4. Lokasi Penyimpanan Buku (Array 3D)

   Menampilkan lokasi buku berdasarkan lantai, nomor rak, dan posisi buku.

   <img width="403" height="315" alt="image" src="https://github.com/user-attachments/assets/6e8ce424-f0d9-46e4-a053-6d1d558dac34" />

---
5. Riwayat Transaksi (Stack)

   Menyimpan riwayat transaksi dengan prinsip LIFO (Last In, First Out) serta menyediakan fitur melihat dan membatalkan transaksi terakhir.

   <img width="363" height="245" alt="image" src="https://github.com/user-attachments/assets/fe21e72f-2b06-456d-8405-8f40bc5964fb" />

---
6. Antrean Peminjaman (Queue)

   Mengelola antrean mahasiswa dengan prinsip FIFO (First In, First Out), sehingga mahasiswa yang datang lebih dahulu dilayani lebih dahulu.

   ---
   - Tambah Mahasiswa ke Antrean
  
     <img width="246" height="262" alt="image" src="https://github.com/user-attachments/assets/30cbfbf9-f46c-43f5-a554-536a7f606fe0" />
     
   ---
   - Lihat Antrean

     <img width="231" height="155" alt="image" src="https://github.com/user-attachments/assets/9ba4677f-09b6-44c8-866f-392024b9ca48" />
     
   ---
   - Proses Peminjaman
  
     <img width="307" height="575" alt="image" src="https://github.com/user-attachments/assets/4afe61d8-9ee2-48c9-a10e-4ff9380ddc2c" />

---
7. Keluar dari Program

   <img width="380" height="200" alt="image" src="https://github.com/user-attachments/assets/f05e0fcb-4245-41cd-917e-a4ee2df239bf" />
