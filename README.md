# Proyek Flutter PBP

Pemrograman Berbasis Platform (CSGE602022) - diselenggarakan oleh Fakultas Ilmu Komputer Universitas Indonesia, Semester Ganjil 2022/2023

Nama: Fadhlan Hasyim

NPM: 2106652215

Kelas: PBP F

Kode Asdos: BYN

## Pendahuluan

Repositori ini digunakan sebagai wadah untuk mengumpulkan tugas Proyek Flutter PBP.

## Jawaban Pertanyaan Tugas 7

#### Pertanyaan 1: Jelaskan apa yang dimaksud dengan stateless widget dan stateful widget dan jelaskan perbedaan dari keduanya.

**Jawab:**

Stateless widget adalah widget yang tidak pernah berubah sepanjang masa pakainya. Di sisi lain, Stateful widget adalah widget yang bersifat dinamis sehingga dapat berubah-ubah statenya.

Perbedaannya, stateless widget bersifat immutable, statis, tidak bergantuk pada perubahan data, dan tidak memiliki state, sedangkan stateful widget bersifat mutable, dinamis, memiliki internal state, dan dapat di-update.

#### Pertanyaan 2: Sebutkan widget apa saja yang kamu pakai di proyek kali ini dan jelaskan fungsinya!

**Jawab:**

FloatingActionButton: berfungsi sebagai tombol plus dan minus.
Container: berfungsi menampung widget di dalamnya.
Align: berfungsi untuk memberikan alignment pada widget di dalamnya.
Row: berfungsi untuk menempatkan widget secara horizontal.
Icon: berfungsi untuk memberikan icon.
Center: berfungsi untuk menempatkan widget di tengah.
Text: berfungsi untuk menampilkan teks.
Column: berfungsi untuk menampilkan widget secara vertikal.
AppBar: berfungsi sebagai appbar pada aplikasi.
Scaffold: berfungsi untuk memberikan struktur app
MaterialApp: berfungsi ketika ingin menggunakan material design

#### Pertanyaan 3: Apa fungsi dari setState()? Jelaskan variabel apa saja yang dapat terdampak dengan fungsi tersebut.

**Jawab:**

setState digunakan untuk me-rebuild widget tree. setState berfungsi untuk memberitahu bahwa terdapat perubahan internal state yang mungkin mempengaruhi tampilan pengguna. Pada tugas 7, variabel yang terdampak fungsi setState adalag _counter.

#### Pertanyaan 4:  Jelaskan perbedaan antara const dengan final.

**Jawab:**

Perbedaan mendasar mengenai const dan final adalah nilai variabel const harus sudah diketahui saat compile time, sedangkan nilai variabel final harus sudah diketahui saat runtime.

#### Pertanyaan 5:  Jelaskan bagaimana cara kamu mengimplementasikan checklist di atas.

**Jawab:**

1. Membuat flutter app dengan perintah `flutter create counter_7`
2. Membuat button untuk mengurangi counter
3. Membuat function untuk mengurangi counter
4. Menghubungkan antara button dan function untuk mengurangi counter
5. Mengganti teks yang ditampilkan sesuai counter (Ganjil/Genap)
7. Memberikan kondisional agar button "kurang" dapat hilang saat counter = 0
8. Selesai!

## Jawaban Pertanyaan Tugas 8

#### Pertanyaan 1: Jelaskan perbedaan Navigator.push dan Navigator.pushReplacement.

**Jawab:**

Navigator.push akan menambahkan page pada top of stack saja, sedangkan Navigator.pushReplacement akan menghapus top of stack saat ini, lalu menambahkan page pada top of stack.

#### Pertanyaan 2: Sebutkan widget apa saja yang kamu pakai di proyek kali ini dan jelaskan fungsinya.

**Jawab:**

Container: berfungsi menampung widget di dalamnya.
Align: berfungsi untuk memberikan alignment pada widget di dalamnya.
Row: berfungsi untuk menempatkan widget secara horizontal.
Icon: berfungsi untuk memberikan icon.
Center: berfungsi untuk menempatkan widget di tengah.
Text: berfungsi untuk menampilkan teks.
Column: berfungsi untuk menampilkan widget secara vertikal.
AppBar: berfungsi sebagai appbar pada aplikasi.
Scaffold: berfungsi untuk memberikan struktur app.
MaterialApp: berfungsi ketika ingin menggunakan material design.
IconButton: berfungsi sebagai sebuah tombol yang berwujud icon.
ListView.builder: berfungsi untuk menampilkan list of children yang scrollable.
DropdownButton2: berfungsi sebagai sebuah dropdown (pub.dev).
SizedBox: berfungsi untuk memberikan jarak.
SingleChildScrollView: berfungsi untuk memberikan fungsionalitas scrollable terhadap child-nya.
Expanded: berfungsi untuk menampung widget dengan sifat expand-nya.
TextFormField: berfungsi sebagai form.

#### Pertanyaan 3: Sebutkan jenis-jenis event yang ada pada Flutter (contoh: onPressed).

**Jawab:**

1. onPressed
2. onSaved
3. onChanged
4. onClick
5. onLongPress
6. onHover
7. onFocusChange
8. onTap
9. dan masih banyak lagi :D

#### Pertanyaan 4:  Jelaskan bagaimana cara kerja Navigator dalam "mengganti" halaman dari aplikasi Flutter.

**Jawab:**

Navigator bekerja menggunakan prinsip stack. Halaman yang akan dimuat akan di-push pada top of stack, sedangkan jika ingin berpindah ke halaman sebelumnya, Navigator akan melakukan pop pada stack, sehingga page yang saat ini dilihat akan dihapus dari stack dan tampilan pengguna akan berganti ke halaman sebelumnya.

#### Pertanyaan 5:  Jelaskan bagaimana cara kamu mengimplementasikan checklist di atas.

**Jawab:**

1. Melakukan refactor widget drawer.
2. Membuat routing pada widget drawer.
3. Membuat halaman tambah_budget beserta form-nya.
4. Membuat model budget.
5. Membuat global variabel untuk menampung instances of budget.
7. Membuat halaman data_budget untuk menampilkan list budget.
8. Selesai!

## Jawaban Pertanyaan Tugas 9

#### Pertanyaan 1: Apakah bisa kita melakukan pengambilan data JSON tanpa membuat model terlebih dahulu? Jika iya, apakah hal tersebut lebih baik daripada membuat model sebelum melakukan pengambilan data JSON?

**Jawab:**



#### Pertanyaan 2: Sebutkan widget apa saja yang kamu pakai di proyek kali ini dan jelaskan fungsinya.

**Jawab:**

Container: berfungsi menampung widget di dalamnya.
Align: berfungsi untuk memberikan alignment pada widget di dalamnya.
Row: berfungsi untuk menempatkan widget secara horizontal.
Icon: berfungsi untuk memberikan icon.
Center: berfungsi untuk menempatkan widget di tengah.
Text: berfungsi untuk menampilkan teks.
Column: berfungsi untuk menampilkan widget secara vertikal.
AppBar: berfungsi sebagai appbar pada aplikasi.
Scaffold: berfungsi untuk memberikan struktur app.
MaterialApp: berfungsi ketika ingin menggunakan material design.
IconButton: berfungsi sebagai sebuah tombol yang berwujud icon.
ListView.builder: berfungsi untuk menampilkan list of children yang scrollable.
DropdownButton2: berfungsi sebagai sebuah dropdown (pub.dev).
SizedBox: berfungsi untuk memberikan jarak.
SingleChildScrollView: berfungsi untuk memberikan fungsionalitas scrollable terhadap child-nya.
Expanded: berfungsi untuk menampung widget dengan sifat expand-nya.
TextFormField: berfungsi sebagai form.

#### Pertanyaan 3: Jelaskan mekanisme pengambilan data dari json hingga dapat ditampilkan pada Flutter.

**Jawab:**

1. onPressed
2. onSaved
3. onChanged
4. onClick
5. onLongPress
6. onHover
7. onFocusChange
8. onTap
9. dan masih banyak lagi :D

#### Pertanyaan 4:  Jelaskan bagaimana cara kamu mengimplementasikan checklist di atas.

**Jawab:**

1. Melakukan refactor widget drawer.
2. Membuat routing pada widget drawer.
3. Membuat halaman tambah_budget beserta form-nya.
4. Membuat model budget.
5. Membuat global variabel untuk menampung instances of budget.
7. Membuat halaman data_budget untuk menampilkan list budget.
8. Selesai!