# Simulasi Tata Surya Menggunakan Python

## Deskripsi

Proyek ini berisi simulasi sederhana tata surya yang dibuat menggunakan Python di Jupyter Notebook. Simulasi menampilkan Matahari dan delapan planet yang bergerak mengelilinginya dalam lintasan berbentuk lingkaran.

Proyek ini dibuat sebagai latihan untuk mempelajari dasar animasi menggunakan Matplotlib, penggunaan NumPy, serta penerapan fungsi trigonometri dalam pemrograman.

---

## Library yang Digunakan

Program ini menggunakan beberapa library berikut:

* NumPy
* Matplotlib
* IPython Display

Jika belum terpasang, jalankan perintah berikut:

```bash
pip install numpy matplotlib notebook
```

---

## Cara Menjalankan

1. Buka Jupyter Notebook atau JupyterLab.
2. Buka file `Simulasi_Tata_Surya.ipynb`.
3. Jalankan semua cell dari atas ke bawah.
4. Tunggu beberapa saat hingga animasi selesai diproses.
5. Animasi akan muncul di bagian bawah notebook.

---

## Isi Program

Program dibagi menjadi beberapa bagian agar lebih mudah dipahami.

* Import library.
* Menentukan parameter simulasi.
* Menyimpan data planet.
* Menghitung posisi setiap planet.
* Membuat tampilan animasi.
* Menjalankan animasi.

---

## Cara Kerja

Posisi setiap planet dihitung menggunakan koordinat kartesius dengan bantuan fungsi sinus dan cosinus.

Setiap frame akan menghitung posisi baru planet, kemudian posisi tersebut digambar kembali sehingga menghasilkan animasi pergerakan.

Karena simulasi ini dibuat untuk latihan, ukuran planet, jarak orbit, dan jumlah putaran tidak menggunakan data astronomi yang sebenarnya. Nilai-nilai tersebut disederhanakan agar animasi lebih mudah dipahami dan tetap ringan dijalankan.

---

## Hasil

Animasi menampilkan:

* Matahari di pusat tata surya.
* Delapan planet dengan warna yang berbeda.
* Jejak lintasan setiap planet.
* Nama setiap planet.
* Informasi waktu simulasi hingga 230 juta tahun.

---

## Pengembangan

Program ini masih dapat dikembangkan, misalnya dengan:

* menggunakan orbit berbentuk elips,
* menambahkan satelit alami,
* menggunakan data astronomi yang lebih akurat,
* menambahkan latar belakang bintang,
* menggunakan library REBOUND untuk simulasi gravitasi.

---

## Penutup

Melalui proyek ini saya belajar menggunakan NumPy untuk mengolah data, Matplotlib untuk membuat visualisasi, serta memahami bagaimana konsep matematika seperti sinus dan cosinus dapat digunakan untuk membuat simulasi gerak planet secara sederhana.
