# Simulasi Tata Surya Menggunakan Python

## Deskripsi

Proyek ini merupakan simulasi visual tata surya yang dikembangkan menggunakan Python dalam lingkungan Jupyter Notebook. Tujuan utama proyek ini adalah memvisualisasikan pergerakan planet mengelilingi Matahari melalui animasi dua dimensi sekaligus memperkenalkan penerapan konsep matematika dan pemrograman dalam simulasi ilmiah.

Seluruh simulasi dibangun menggunakan pendekatan numerik sederhana dengan memanfaatkan fungsi trigonometri untuk menghitung posisi setiap planet pada setiap langkah waktu. Meskipun model yang digunakan belum merepresentasikan dinamika tata surya secara fisik, proyek ini dirancang sebagai media pembelajaran untuk memahami dasar-dasar visualisasi data, animasi, serta simulasi komputasi.

Selain menghasilkan animasi yang interaktif, proyek ini juga menjadi sarana untuk mempelajari bagaimana sebuah permasalahan ilmiah dapat diterjemahkan ke dalam bentuk algoritma dan divisualisasikan menggunakan Python.

---

## Tujuan Proyek

Proyek ini dikembangkan dengan beberapa tujuan utama, yaitu:

- Mempelajari dasar-dasar simulasi komputasi menggunakan Python.
- Memahami penerapan fungsi trigonometri dalam menghitung posisi objek yang bergerak.
- Mengembangkan kemampuan membuat animasi menggunakan Matplotlib.
- Melatih penggunaan NumPy dalam pengolahan data numerik.
- Membangun pemahaman mengenai proses visualisasi fenomena astronomi secara sederhana.

---

## Teknologi yang Digunakan

Proyek ini dibangun menggunakan beberapa pustaka Python berikut.

- **Python 3**
- **NumPy**
- **Matplotlib**
- **IPython Display**
- **Jupyter Notebook**

Instalasi dependensi dapat dilakukan dengan perintah berikut.

```bash
pip install numpy matplotlib notebook
```

---

## Cara Menjalankan

1. Jalankan Jupyter Notebook atau JupyterLab.
2. Buka file `Simulasi_Tata_Surya.ipynb`.
3. Eksekusi seluruh sel secara berurutan.
4. Tunggu proses pembuatan animasi hingga selesai.
5. Animasi akan ditampilkan secara langsung pada notebook.

---

## Struktur Program

Notebook disusun secara modular agar setiap tahapan simulasi mudah dipahami, meliputi:

- Import library.
- Inisialisasi parameter simulasi.
- Pendefinisian data planet.
- Perhitungan posisi setiap planet.
- Pembuatan objek visualisasi.
- Animasi pergerakan planet.
- Rendering hasil simulasi.

---

## Metodologi

Posisi setiap planet dihitung menggunakan persamaan parametrik lingkaran dengan memanfaatkan fungsi sinus dan cosinus. Pada setiap frame animasi, koordinat planet diperbarui berdasarkan waktu simulasi sehingga menghasilkan ilusi gerak mengelilingi Matahari.

Pendekatan ini dipilih karena sederhana, mudah dipahami, dan sesuai untuk memperkenalkan konsep dasar simulasi komputasi. Parameter seperti jari-jari orbit, ukuran planet, serta kecepatan revolusi telah disederhanakan agar simulasi tetap ringan dijalankan tanpa mengurangi nilai edukatifnya.

Perlu dicatat bahwa proyek ini bukan merupakan simulator astronomi berpresisi tinggi. Fokus utama proyek adalah membangun pemahaman mengenai hubungan antara konsep matematika, algoritma, dan visualisasi menggunakan Python.

---

## Fitur

Simulasi yang dihasilkan memiliki beberapa fitur berikut.

- Visualisasi Matahari sebagai pusat tata surya.
- Delapan planet dengan warna yang berbeda.
- Animasi revolusi planet.
- Jejak lintasan (orbit trail) setiap planet.
- Label nama planet.
- Informasi waktu simulasi hingga ratusan juta tahun.
- Tampilan yang dioptimalkan untuk dijalankan di Jupyter Notebook.

---

## Hasil Pembelajaran

Melalui pengembangan proyek ini, beberapa kompetensi yang berhasil dipelajari antara lain:

- Penggunaan **NumPy** untuk komputasi numerik.
- Pembuatan visualisasi menggunakan **Matplotlib**.
- Implementasi animasi menggunakan **FuncAnimation**.
- Pemodelan gerak melingkar menggunakan fungsi trigonometri.
- Penyusunan kode Python yang terstruktur dalam bentuk notebook.
- Dasar-dasar pengembangan simulasi ilmiah berbasis Python.

---

## Pengembangan Selanjutnya

Masih terdapat berbagai peluang pengembangan agar simulasi menjadi lebih realistis maupun lebih kompleks, di antaranya:

- Mengimplementasikan orbit berbentuk elips berdasarkan Hukum Kepler.
- Menggunakan data astronomi aktual untuk ukuran, periode revolusi, dan jarak orbit.
- Menambahkan satelit alami pada setiap planet.
- Menambahkan asteroid belt dan objek langit lainnya.
- Mengimplementasikan simulasi gravitasi menggunakan pustaka **REBOUND**.
- Menambahkan fitur kontrol interaktif, seperti zoom, percepatan waktu, dan pemilihan planet.

---

## Kesimpulan

Proyek ini merupakan implementasi sederhana dari konsep simulasi komputasi menggunakan Python. Walaupun model yang digunakan masih bersifat edukatif dan belum mempertimbangkan interaksi gravitasi maupun data astronomi yang sebenarnya, proyek ini berhasil menunjukkan bagaimana konsep matematika dapat diterapkan untuk menghasilkan visualisasi yang informatif dan interaktif.

Bagi saya, proyek ini menjadi langkah awal dalam mempelajari scientific computing, visualisasi data, dan pemrograman berbasis simulasi. Selain meningkatkan pemahaman terhadap Python, proyek ini juga memberikan pengalaman dalam menerjemahkan konsep ilmiah menjadi sebuah aplikasi yang dapat diamati secara visual. Ke depannya, proyek ini akan terus dikembangkan dengan model fisika yang lebih akurat dan fitur yang lebih komprehensif sebagai bagian dari proses belajar di bidang komputasi dan robotika.
