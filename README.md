
## Fitur Aplikasi

1. **Menampilkan Produk**  
   Menampilkan daftar produk dalam bentuk kartu pada halaman katalog.

2. **Menambahkan Produk**  
   Menambahkan produk baru ke dalam katalog.

3. **Mengedit Produk**  
   Mengubah informasi produk yang sudah tersimpan, seperti nama dan harga.

4. **Menghapus Produk**  
   Menghapus produk dari katalog dengan konfirmasi sebelum penghapusan.

5. **Validasi Input**  
   Memeriksa input agar data produk yang dimasukkan sesuai dengan ketentuan aplikasi.

6. **Penyimpanan Data**  
   Menggunakan SQLite sebagai database untuk menyimpan data produk.


## Tampilan Aplikasi

Berikut merupakan dokumentasi tampilan aplikasi Katalog Produk UPI Store.

### Halaman Katalog Produk

![Halaman Katalog Produk](katalog-produk.png)

## Cara Menjalankan Aplikasi

1. Download atau clone repository ini.
2. Ekstrak file project apabila masih berbentuk ZIP.
3. Buka Apache NetBeans IDE.
4. Pilih **File → Open Project**.
5. Pilih folder project `KatalogProduk`.
6. Tunggu hingga proses pemuatan dependency Maven selesai.
7. Klik kanan project, kemudian pilih **Clean and Build**.
8. Jalankan aplikasi melalui NetBeans.

Jika ingin menjalankan melalui Maven, gunakan goal berikut apabila konfigurasi project mendukungnya:

```bash
mvn javafx:run
```

## Tujuan Project

Project ini dibuat untuk menerapkan konsep pengembangan antarmuka grafis menggunakan JavaFX, termasuk penggunaan FXML, CSS, pengelolaan data produk, serta operasi tambah, tampil, edit, dan hapus data.

---

**Project:** Katalog Produk UPI Store  
**Mata Kuliah:** Pengantar JavaFX GUI – Level 3  
**Platform:** Desktop Application
