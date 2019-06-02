# Liburan Semester 4 ke Semester 5 Ngapain aja?
Terkesan idealis, tapi ini yang ditargetkan jadi sebelum masuk kuliah lagi tanggal 12 Agustus 2019:
- Membangun Aplikasi yang dapat membantu siswa SMA dalam mencari jurusan yang sesuai minat mereka.
- Untuk fitur utama, terdapat 2, yakni fitur pencari jurusan yang memberi info jurusan secara mendetail dan bot yang bisa ditanya secara personal berupa rekomendasi jurusan apa yang diambil sesuai dengan data yang akan diambil dari pengguna.

Haha, ini mungkin gue mencoba dulu untuk mengepush sejauh mana target yang telah gue pasang selama ini. Yakni membangun aplikasi yang dapat membantu anak SMA untuk mencari jurusan yang tepat dan sesuai minat mereka. Jujur, ini adalah ide pas masa2 pengenalan departemen dan ini kemarin dapat juara satu untuk aplikasi terbaik.
Terus, kira-kira butuh apa aja ya?

## Hari ke-1: Belajar Flutter OOP
Tadi udah belajar OOP menggunakan Dart dan bisa dibilang cukup mudah tidak seperti saudaranya, yakni Java. OOP sendiri terdiri dari 4 prinsip, yakni:

1. Abstraction (Membagi potongan kode sesuai dengan perannya masing2 ke dalam class)
2. Encapsulation (Metode dan Atribut dibungkus dalam satu class dan atribut didalamnya tidak dapat diubah)
3. Inheritance (Metode dan Atribut dapat diturunkan ke subclass dari superclass)
4. Polymorphism (Subclass bisa mengubah metode atau atribut mereka sesuka hati)

Di Flutter, semua komponen di tampilan berupa widget dan dalam pembuatannya banyak menerapkan OOP untuk memudahkan pembacaan kode.

Sekarang, mau coba kembangin User Interfacenya, let's go!

## Hari ke-2: Belajar Asynchronous Programming dan Selesain materi / project Course Flutter di Appbrewery
![Asynchronous vs Synchronous](https://msl-network.readthedocs.io/en/latest/_images/sync_vs_async.png)

Untuk projek, tadi ngerjain yang ID Card dan 8 Ball. Karena udah punya pengalaman di Stateless dan Stateful Widget, untuk ngoding tidak ada masalah sehingga semuanya lancar. Namun, yang menjadi tantangan adalah ketika mempelajari mengenai keyword **Future**, **Async**, dan **Await**. Untuk ini, harus memahami yang namanya **Asynchronous Programming**. 
Untuk memahami ini, diberikan suatu permasalahan dimana ada tugas untuk menelepon klien dan mendapatkan respon sebanyak 100 orang dan waktu yang diberikan sedikit. Untuk menyelesaikan ini, ada 2 cara, yakni dengan menelpon lalu menunggu dengan respon dan diulangi lagi sebanyak 100 kali. Ini namanya **Synchronous Programming**, menyelesaikan satu tugas terlebih dahulu sebelum lanjut ke yang lain. Lalu, cara lain seperti berikut, seseorang menelpon dan saat menunggu respon dia menelpon kembali dan diulangi sebanyak 100 kali. Ini namanya **Asynchronous Programming**. Perbedaan signifikan terlihat ketika saat satu tugas sedang dilaksanakan, maka tugas lain akan dilaksanakan dulu lalu yang ditunggu tadi pun selesai.
