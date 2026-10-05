# Nabila-Pertiwi-Putri_09011382530165_Tugas-1.

# 1) Buatlah laporan proses instalasi di komputer mahasiswa dan tampilkan screenshoot-nya.
Jawab :
1. Tujuan : Melakukan instalasi sistem operasi Linux Ubuntu 14.04 LTS menggunakan aplikasi virtualisasi VirtualBox sesuai dengan langkah-langkah pada modul praktikum.

2. Alat dan Bahan :
- Laptop
- VirtualBoc
- ISO Ubuntu 14.04 LTS

3. Langkah-Langkah Instalasi
- Membuat virtual machine baru menggunakanVirtualBox, kemudian menentukan spesifikasi VM berupa RAM 2048 MB, prosesor 2, dan hard disk size 20 GB serta menggunakan ISO Ubuntu 14.04 LTS.
<img width="1359" height="858" alt="gmbr 1" src="https://github.com/user-attachments/assets/99d0e8c9-f86b-42fd-9b4d-305b74e54a10" />

- Menjalankan virtual machine dan memulai instalasi dengan memilih Install Ubuntu, kemudian memeriksa persiapan instalasi dan melanjutkan proses.
- Pada pilihan jenis instalasi, memilih sesuatu yang lain (something else) agar partisi hard disk dapat diatur secara manual.
  <img width="739" height="559" alt="gmbr 2" src="https://github.com/user-attachments/assets/2ca285c9-8dda-4791-9d5a-145aec4a89e6" />

- Membuat tabel partisi baru, kemudian membuat partisi swap sebesar 1023 MB dan memilih Ruang swap sebagai penggunaannya.

  <img width="544" height="339" alt="Screenshot 2026-10-05 091204" src="https://github.com/user-attachments/assets/2c740185-6100-4cee-8c17-59b842013dc1" />

- Membuat partisi /home sebesar 5291 MB menggunakan sistem berkas Ext4 dengan titik kait /home.
  <img width="458" height="372" alt="Screenshot 2026-10-05 091521" src="https://github.com/user-attachments/assets/4b8eca84-ee74-4a84-a0f2-534c003d0032" />

- Membuat partisi / (root) menggunakan sisa ruang hard disk, dengan sistem berkas Ext4 dan titik kait /.
  <img width="458" height="342" alt="Screenshot 2026-10-05 091541" src="https://github.com/user-attachments/assets/6f274743-4e8b-4c57-ae6c-c71d20be7d38" />
  <img width="1303" height="1085" alt="gmbr 6" src="https://github.com/user-attachments/assets/c9a1e2b5-94f4-41fb-bf08-74d11e7548a7" />

- Memilih pasang sekarang, kemudian mengatur zona waktu yaitu Jakarta, susunan papan ketik, serta mengisi nama pengguna dan kata sandi.
  <img width="1414" height="1211" alt="gmbr 7" src="https://github.com/user-attachments/assets/aa7ee97d-5cfa-4362-a36b-03224c7e8022" />
  <img width="1465" height="786" alt="gmbr 8" src="https://github.com/user-attachments/assets/c169c33f-e56e-430e-948c-456cd779b564" />

- Menunggu proses instalasi hingga selesai, kemudian memilih Restart Now dan masuk ke sistem operasi 
Ubuntu 14.04 menggunakan username dan sandi yang telah dibuat.

# 2) Analisislah pada gambar kenapa saat instalasi perlu “/” pada opsi Mount Point ?
Jawab : Mount Point / (root) perlu dipilih karena / adalah direktori utama dalam sistem operasi Linux. Semua komponen penting sistem berada di dalam direktori ini, sehingga partisi yang dipasang pada / menjadi 
lokasi utama untuk menyimpan file-file sistem Ubuntu. Saat instalasi, partisi / juga menjadi tempat sistem dipasang dan dijalankan. Tanpa Mount Point /, sistem Linux tidak memiliki titik utama untuk memasang 
sistemnya. Oleh karena itu, pada modul praktikum partisi untuk / dibuat dengan format ext4 Journal System dan digunakan sebagai root. Kesimpulannya, / dipilih sebagai Mount Point karena berfungsi sebagai 
lokasi utama untuk penyimpanan dan eksekusi sistem operasi Linux.

# 3) Berikan penjelasan tentang ext4, ext3, swap, ntfs, fat32, btrfs !
Jawab : 
- Ext4 : sistem berkas yang banyak dipakai di Linux untuk mengatur dan menyimpan file serta data. Dalam praktikum, Ext4 digunakan untuk partisi /home dan / (root).
- Ext3 : versi sebelumnya dari Ext4 yang juga dipakai di Linux untuk manajemen penyimpanan file dan data.
- Swap : ruang penyimpanan yang dipakai sebagai tambahan ketika memori utama (RAM) tidak cukup. 
Jadi, ketika penggunaan RAM sedang tinggi, sebagian data dapat dipindahkan sementara ke ruang swap supaya sistem tetap dapat berjalan. 
- NTFS: sistem berkas yang umum di Windows dan digunakan untuk mengatur file serta folder pada media penyimpanan.
- FAT32 : sistem berkas Linux yang kompatibel dengan banyak perangkat dan sistem operasi, sehingga sering dipakai pada media seperti flashdisk.
- BTRFS : sistem berkas Linux yang menawarkan fitur manajemen penyimpanan yang lebih modern untuk membantu pengaturan data dan penggunaan ruang penyimpanan.

  
  
