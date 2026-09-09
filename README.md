# Laporan Praktikum Perintah Dasar Linux

1. **`mkdir SKU`**
   Membuat direktori (folder) baru bernama `SKU`.

2. **`cd SKU`**
   Pindah dan masuk ke dalam direktori `SKU`.

3. **`pwd`**
   Menampilkan lokasi/jalur lengkap direktori kerja saat ini (`/home/righhh/SKU`).

4. **`ls`**
   Menampilkan daftar berkas dan folder yang ada di direktori saat ini.

5. **`ls -l`**
   Menampilkan daftar berkas secara rinci (izin akses, jumlah link, pemilik, grup, ukuran, dan waktu modifikasi).

6. **`ls -a`**
   Menampilkan seluruh berkas dan folder, termasuk berkas tersembunyi (*hidden files*).

7. **`touch latihan.txt`**
   Membuat berkas teks kosong baru bernama `latihan.txt`.

8. **`cat latihan.txt`**
   Menampilkan seluruh isi teks dari berkas `latihan.txt` ke layar terminal.

9. **`nano latihan.txt`**
   Membuka berkas `latihan.txt` menggunakan editor teks Nano.

10. **`vim latihan.txt`**
    Membuka berkas `latihan.txt` menggunakan editor teks Vim.

11. **`:q`**
    Perintah internal Vim untuk keluar dari mode editor.

12. **`touch file1.txt`**
    Membuat berkas kosong baru bernama `file1.txt`.

13. **`cp file1.txt file2.txt`**
    Menyalin berkas `file1.txt` dan menyimpannya sebagai berkas baru bernama `file2.txt`.

14. **`mkdir folderA`**
    Membuat direktori baru bernama `folderA`.

15. **`cp -r folderA folderB`**
    Menyalin direktori `folderA` beserta seluruh isinya ke dalam direktori baru `folderB` secara rekursif.

16. **`mv file2.txt file2_rename.txt`**
    Mengubah nama berkas `file2.txt` menjadi `file2_rename.txt`.

17. **`touch hapus.txt`**
    Membuat berkas baru bernama `hapus.txt`.

18. **`rm hapus.txt`**
    Menghapus berkas `hapus.txt`.

19. **`mkdir folder_contoh`**
    Membuat direktori baru bernama `folder_contoh`.

20. **`rm -r folder_contoh`**
    Menghapus direktori `folder_contoh` beserta seluruh isinya secara rekursif.

21. **`mkdir folder_kosong`**
    Membuat direktori bernama `folder_kosong`.

22. **`rmdir folder_kosong`**
    Menghapus direktori kosong bernama `folder_kosong`.

23. **`echo "Tugas Sistem Operasi" >> latihan.txt`**
    Menambahkan teks *"Tugas Sistem Operasi"* ke baris paling akhir di dalam berkas `latihan.txt`.

24. **`grep "Tugas" latihan.txt`**
    Mencari dan menampilkan baris yang mengandung kata *"Tugas"* di dalam berkas `latihan.txt`.

25. **`find . -name "latihan.txt"`**
    Mencari lokasi berkas bernama `"latihan.txt"` di dalam direktori saat ini dan sub-direktorinya.

26. **`man ls`**
    Membuka buku panduan/manual resmi untuk mempelajari cara penggunaan perintah `ls`.

27. **`history`**
    Menampilkan daftar riwayat perintah yang pernah diketikkan pada terminal.

28. **`history -d 1-35`**
    Menghapus baris riwayat perintah dari urutan nomor 1 sampai 35.

29. **`whoami`**
    Menampilkan nama pengguna (*username*) yang sedang aktif digunakan pada sesi terminal (`righhh`).

30. **`date`**
    Menampilkan informasi hari, tanggal, waktu, zona waktu, dan tahun sistem saat ini.

31. **`uptime`**
    Menampilkan durasi sistem operasi telah menyala serta beban rata-rata sistem (*load average*).

32. **`uname -a`**
    Menampilkan rincian informasi sistem operasi, *hostname*, versi kernel Linux, dan arsitektur mesin.

33. **`df -a`**
    Menampilkan laporan penggunaan ruang penyimpanan (*disk space*) pada seluruh sistem berkas.

34. **`du -h`**
    Menampilkan estimasi ukuran penggunaan ruang penyimpanan folder atau berkas dalam format yang mudah dibaca (*human-readable*).

35. **`chmod 755 latihan.txt`**
    Mengubah izin akses berkas `latihan.txt` menjadi `755` (*read, write, execute* untuk owner; *read, execute* untuk grup dan lainnya).

36. **`sudo chown $USER latihan.txt`**
    Mengubah hak kepemilikan berkas `latihan.txt` menjadi milik pengguna aktif saat ini menggunakan hak akses administrator (*super user*).

37. **`ps`**
    Menampilkan daftar proses yang sedang berjalan pada sesi terminal aktif saat ini.

38. **`ps aux`**
    Menampilkan seluruh proses yang sedang berjalan di dalam sistem secara rinci dari semua pengguna.

39. **`top`**
    Membuka antarmuka pemantauan proses dan penggunaan sumber daya sistem (CPU & RAM) secara *real-time*.

40. **`tar -czvf folderA.tar.gz folderA`**
    Mengompresi direktori `folderA` menjadi berkas arsip berformat `.tar.gz`.

41. **`tar -xzvf folderA.tar.gz`**
    Mengekstrak kembali isi dari berkas arsip `folderA.tar.gz`.

42. **`zip -r folderA.zip folderA`**
    Mengompresi direktori `folderA` beserta seluruh sub-foldernya menjadi berkas arsip berformat `.zip`.

43. **`unzip folderA.zip`**
    Mengekstrak isi dari berkas arsip `folderA.zip`.

44. **`wget https://www.google.com -O test.html`**
    Mengunduh halaman web dari Google dan menyimpannya sebagai berkas `test.html`.

45. **`curl https://www.google.com`**
    Mengambil dan menampilkan kode sumber HTML dari situs Google langsung di layar terminal.

46. **`sudo apt install curl`**
    Mengunduh dan menginstal aplikasi `curl` menggunakan manajer paket APT.

47. **`ping -c 4 google.com`**
    Mengirimkan 4 paket tes konektivitas (*ICMP Echo Request*) ke `google.com` untuk mengecek status jaringan.

48. **`ip addr`**
    Menampilkan konfigurasi antarmuka jaringan (*network interfaces*) beserta alamat IP perangkat.

49. **`sudo apt update`**
    Memperbarui daftar pustaka paket (*repository database*) sistem ke versi terbaru.

50. **`sudo apt upgrade`**
    Meng-upgrade seluruh paket dan aplikasi yang terinstal di sistem ke versi terbaru.

51. **`sudo apt install tree`**
    Mengunduh dan menginstal aplikasi `tree` untuk menampilkan struktur direktori.

52. **`apt list --installed`**
    Menampilkan daftar seluruh paket dan aplikasi yang telah terpasang di sistem operasi.

53. **`head latihan.txt`**
    Menampilkan 10 baris pertama dari berkas `latihan.txt`.

54. **`tail latihan.txt`**
    Menampilkan 10 baris terakhir dari berkas `latihan.txt`.

55. **`wc latihan.txt`**
    Menghitung jumlah baris, kata, dan karakter (*word count*) yang ada di dalam berkas `latihan.txt`.

56. **`sort latihan.txt`**
    Memilah dan mengurutkan baris-baris teks di dalam berkas `latihan.txt` secara alfabetis.

57. **`fastfetch`**
    Menampilkan logo sistem operasi beserta ringkasan informasi spesifikasi perangkat keras dan perangkat lunak secara visual.

58. **`exit`**
    Mengakhiri dan menutup sesi terminal yang aktif.
