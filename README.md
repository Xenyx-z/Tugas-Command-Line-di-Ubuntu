# Tugas-Command-Line-di-Ubuntu

1. `pwd`
   Menampilkan path direktori tempat kamu berada saat ini (Print Working Directory).

2. `whoami`
   Menampilkan nama user yang sedang login.

3. `id`
   Menampilkan UID (user ID), GID (group ID), dan daftar grup yang diikuti user.

4. `groups`
   Menampilkan daftar grup yang menjadi anggota user aktif.

5. `last`
   Menampilkan riwayat login user dari database wtmp, siapa login kapan dan dari terminal mana.

6. `hostname`
   Menampilkan nama komputer (hostname) di jaringan.

7. `hostname -I`
   Menampilkan alamat IP komputer (IPv4 dan IPv6).

8. `uname -a`
   Menampilkan semua info kernel: nama sistem, versi kernel, arsitektur, dsb.

9. `lsb_release -a`
   Menampilkan detail distribusi Linux: nama, versi, codename.

10. `uptime`
    Menampilkan berapa lama sistem sudah menyala, jumlah user aktif, dan load average CPU.

11. `date`
    Menampilkan tanggal dan waktu sistem saat ini.

12. `cal`
    Menampilkan kalender bulan berjalan dalam format teks.

13. `env`
    Menampilkan seluruh environment variable yang aktif di shell (PATH, HOME, SHELL, dll).

14. `printenv PATH`
    Menampilkan nilai satu environment variable tertentu, dalam contoh ini variabel `PATH`.

15. `dir`
    Menampilkan isi direktori — fungsinya mirip `ls`.

16. `ls`
    Menampilkan daftar file dan folder di direktori aktif.

17. `ls -l`
    Menampilkan daftar file dalam format panjang (permission, owner, ukuran, tanggal modifikasi).

18. `ls -la`
    Sama seperti `ls -l`, tetapi juga menampilkan file/folder tersembunyi (diawali titik).

19. `cd nama_folder`
    Berpindah ke direktori dengan nama yang disebutkan.

20. `cd ..`
    Berpindah ke satu tingkat direktori di atasnya (parent directory).

21. `cd /`
    Berpindah ke direktori root sistem.

22. `cd ~`
    Berpindah ke direktori home user (`/home/nama_user`).

23. `mkdir tes`
    Membuat folder baru bernama `tes`.

24. `touch stg.txt`
    Membuat file kosong baru bernama `stg.txt`, atau memperbarui timestamp jika file sudah ada.

25. `rm stg.txt`
    Menghapus file `stg.txt`.

26. `rm -r tes`
    Menghapus folder `tes` beserta seluruh isinya secara rekursif.

27. `rmdir Kuliah`
    Menghapus folder `Kuliah`, hanya berhasil jika folder tersebut kosong.

28. `cp -r Syakieb Kuliah`
    Menyalin folder `Syakieb` beserta isinya ke folder `Kuliah`.

29. `mv Syakieb MOVE`
    Memindahkan atau mengganti nama folder `Syakieb` menjadi `MOVE`.

30. `cat file.txt`
    Menampilkan seluruh isi file teks langsung di terminal.

31. `wc file.txt`
    Menghitung jumlah baris, kata, dan karakter dalam file.

32. `grep "saya" file.txt`
    Mencari dan menampilkan baris yang mengandung kata `"saya"` di dalam file.

33. `grep -i "syakieb" file.txt`
    Sama seperti `grep`, tetapi opsi `-i` membuat pencarian tidak peka huruf besar/kecil (case-insensitive).

34. `which ls`
    Menampilkan path lokasi executable dari command `ls` (misalnya `/usr/bin/ls`).

35. `which python`
    Menampilkan path lokasi executable `python` jika terinstal dan ada di `PATH`.

36. `whereis python3`
    Menampilkan lokasi terkait `python3`, seperti binary, source, dan halaman manual.

37. `locate file.txt`
    Mencari file bernama `file.txt` menggunakan database index.

38. `sudo apt remove rhythmbox`
    Menghapus (uninstall) aplikasi Rhythmbox dari sistem dengan hak akses admin.

39. `sudo apt install vlc`
    Menginstal aplikasi VLC Media Player.

40. `sudo apt install wtmpdb`
    Menginstal paket `wtmpdb`, yang menyediakan command `last` untuk melihat riwayat login.

41. `sudo apt install net-tools`
    Menginstal paket alat jaringan klasik seperti `netstat`, `ifconfig`, dan lain-lain.

42. `sudo apt install plocate`
    Menginstal `plocate`, penyedia command `locate` untuk pencarian file dengan cepat.

43. `dpkg -l`
    Menampilkan daftar seluruh paket yang sudah terinstal di sistem beserta versinya.

44. `free -h`
    Menampilkan penggunaan RAM dan swap dalam format yang mudah dibaca (human-readable, misalnya GB/MB).

45. `df -h`
    Menampilkan kapasitas dan penggunaan disk dari semua partisi yang ter-mount.

46. `du -sh Documents`
    Menampilkan total ukuran folder `Documents` dalam format ringkas (summary, human-readable).

47. `ps`
    Menampilkan proses yang berjalan pada sesi terminal aktif saat ini.

48. `ps aux`
    Menampilkan semua proses yang berjalan di sistem dari semua user, lengkap dengan penggunaan CPU dan memory.

49. `top`
    Menampilkan monitor proses secara real-time, termasuk penggunaan CPU, RAM, dan proses yang paling aktif.

50. `htop`
    Versi interaktif dari `top` yang lebih mudah dibaca dan dinavigasi.

51. `killall firefox`
    Menghentikan semua proses yang bernama `firefox`.

52. `nslookup google.com`
    Menampilkan hasil resolusi DNS dari domain `google.com` ke alamat IP-nya.

53. `ip addr`
    Menampilkan konfigurasi alamat IP dari semua interface jaringan di sistem.

54. `ip route`
    Menampilkan tabel routing jaringan, termasuk gateway default.

55. `ping google.com`
    Mengirim paket data ke `google.com` untuk menguji konektivitas dan latensi jaringan.

56. `curl example.cm`
    Mengambil dan menampilkan konten dari URL langsung di terminal.

57. `netstat -tulpn`
    Menampilkan daftar port yang sedang listening beserta proses yang menggunakannya. Membutuhkan paket `net-tools`.

58. `traceroute`
    Menampilkan jalur (hop-by-hop) yang dilalui paket data menuju server tujuan, berguna untuk diagnosis jaringan.

59. `echo "HELLO"`
    Menampilkan teks yang diketik langsung ke layar terminal.

60. `man ls`
    Membuka halaman manual (dokumentasi) dari command `ls`.

61. `history`
    Menampilkan daftar riwayat command yang pernah diketik di terminal.

62. `history -c`
    Menghapus riwayat command yang tersimpan dalam history sesi shell saat ini.

63. `sudo shutdown now`
    Mematikan sistem segera dengan hak akses admin.
