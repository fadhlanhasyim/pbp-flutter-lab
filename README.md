# Proyek Flutter PBP

Pemrograman Berbasis Platform (CSGE602022) - diselenggarakan oleh Fakultas Ilmu Komputer Universitas Indonesia, Semester Ganjil 2022/2023

Nama: Fadhlan Hasyim

NPM: 2106652215

Kelas: PBP F

Kode Asdos: BYN

## Pendahuluan

Repositori ini digunakan sebagai wadah untuk mengumpulkan tugas Proyek Flutter PBP.

## Jawaban Pertanyaan

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