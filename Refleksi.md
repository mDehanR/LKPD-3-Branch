Refleksi
1. Mengapa branch diperlukan? 
Branch diperlukan untuk menciptakan lingkungan kerja yang terlindungi dari kode utama. Dengan adanya branch, kita dapat menulis kode, menambahkan fitur, bereksperimen, atau memperbaiki error secara bebas tanpa khawatir akan merusak atau mengganggu kode sumber utama yang sudah berjalan dengan baik dan stabil.

2. Apa keuntungan bekerja pada branch dibanding langsung di main?
-Keamanan Kode: Jika membuat kesalahan yang fatal saat memodifikasi kode, branch main akan tetap aman dan tidak ikut rusak.

-Kolaborasi yang Rapi: Jika bekerja dalam tim, setiap anggota dapat mengerjakan bagian yang berbeda-beda di branch masing-masing secara bersamaan tanpa saling menimpa pekerjaan satu sama lain.

-Ulasan dan Pengujian (Review & Testing): Kode yang ditulis di branch terpisah bisa diuji coba terlebih dahulu. Jika sudah dipastikan berhasil dan tidak ada bug, barulah kode tersebut digabungkan (merge) ke main.

3. Kapan sebaiknya membuat branch baru?
-Saat ingin mengembangkan fitur baru (misalnya: membuat halaman profil, menambahkan fitur login, dsb).

-Saat perlu memperbaiki bug atau error pada sistem (bugfix).

-Saat ingin melakukan eksperimen kode, seperti mencoba desain UI yang berbeda atau mencoba algoritma baru yang belum pasti akan diimplementasikan secara permanen.