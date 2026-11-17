# Aplikasi Pencatat Film

## Deskripsi
Aplikasi Pencatat Film merupakan aplikasi GUI sederhana berbasis Java Swing yang digunakan untuk mencatat daftar film. Pengguna dapat memasukkan judul film, memilih genre, memberikan rating, serta menambah dan menghapus film dari daftar.

## Komponen Utama GUI

### 1. Top-level Container Class
**JFrame**

JFrame digunakan sebagai jendela utama aplikasi. Pada program ini, JFrame mengatur judul aplikasi, ukuran jendela, posisi tampilan, dan operasi ketika jendela ditutup.

### 2. Intermediate Container Class
**JPanel**

JPanel digunakan sebagai wadah untuk mengelompokkan komponen GUI. Program ini menggunakan dua JPanel, yaitu:
- `panel`: Menampung seluruh komponen utama aplikasi.
- `panelInput`: Menampung komponen input judul, genre, rating, dan tombol.

### 3. Atomic Component Class
Komponen yang digunakan dalam aplikasi:
- `JTextField`: Digunakan untuk memasukkan judul film.
- `JButton`: Digunakan untuk menambah dan menghapus film.
- `JComboBox`: Digunakan untuk memilih genre dan rating film.
- `JLabel`: Digunakan untuk menampilkan keterangan dan status aplikasi.
- `JList`: Digunakan untuk menampilkan daftar film yang telah ditambahkan.
- `JScrollPane`: Digunakan untuk memberikan fitur scroll pada daftar film.

### 4. Layout Classes
Program ini menggunakan dua jenis layout:

- **BorderLayout**: Mengatur posisi komponen menjadi bagian NORTH, CENTER, dan SOUTH. Panel input berada di bagian atas, daftar film di tengah, dan status aplikasi di bawah.
- **GridLayout**: Mengatur komponen input dalam bentuk 4 baris dan 2 kolom agar tersusun rapi.

### 5. Event Listener
Program ini menggunakan dua Event Listener:

- **ActionListener**: Digunakan untuk menangani aksi tombol Tambah Film dan Hapus Film melalui method `actionPerformed()`.
- **ItemListener**: Digunakan untuk menangani perubahan pilihan genre dan rating melalui method `itemStateChanged()`.

Kedua interface tersebut diimplementasikan menggunakan `@Override` pada method masing-masing.

## Fitur Aplikasi
1. Memasukkan judul film.
2. Memilih genre film.
3. Memilih rating film dari 1 sampai 5.
4. Menambahkan film ke dalam daftar.
5. Menghapus film yang dipilih.
6. Menampilkan informasi status ketika pengguna melakukan aktivitas.

## Screenshot Aplikasi

![Screenshot Aplikasi Pencatat Film](screenshots/tampilanAwal.jpg)
![Screenshot Aplikasi Pencatat Film](screenshots/daftarFilm.jpg.jpg)
