# pemrograman_mobile2_UTS_RizalFahatrikNugraha_2355201145_23CNSA

jawaban teori:
1.Cubit
a.State management yang lebih sederhana.
b.Mengelola state dengan memanggil method yang secara langsung mengubah state lewat emit().
c.Tidak menggunakan event.
*.BLoC:
a.Pendekatan lebih terstruktur.
b.Menggunakan Event → BLoC → State.
c.Cocok untuk arsitektur yang butuh pemisahan logika bisnis lebih rapi dan kompleks.

2. Memisahkan model data, logika bisnis, dan UI penting karena:
Kode lebih rapi dan mudah dipahami — tiap bagian punya tugas jelas.
Mudah dipelihara — perubahan di satu bagian tidak merusak bagian lain.
Mudah diuji — logika bisnis bisa diuji tanpa UI.
Lebih scalable — struktur tetap teratur saat aplikasi membesar.
Mengurangi bug — karena tanggung jawab tiap lapisan jelas.
Intinya: pemisahan membuat aplikasi lebih terstruktur, mudah dikembangkan, dan lebih stabil.

3.* CartInitial
Fungsi:
Menandakan kondisi awal cart saat aplikasi baru dibuka — biasanya cart masih kosong dan belum ada proses apa pun.
*CartLoading
Fungsi:
Digunakan saat cart sedang diproses, misalnya ketika menambahkan item, menghapus item, atau menghitung total.
State ini membantu UI menampilkan indikator loading.
*CartLoaded
Fungsi:
Menampung data cart terbaru, seperti daftar produk dan total harga, setelah operasi berhasil dilakukan.
UI akan menampilkan isi cart berdasarkan state ini.
