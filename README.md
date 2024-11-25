# labpy05

Nama: Mahfuz Fauzi

NIM: 312410412

Kelas: TI.24.A.3

# Program Input Nilai Mahasiswa

Program sederhana untuk mengelola data nilai mahasiswa menggunakan Python dengan struktur data Dictionary.

program sederhana yang akan menampilkan daftar nilai mahasiswa menggunakan `Dictionary`, Program ini mencakup menu pilihan untuk menambah data, mengubah data, menghapus data, menampilkan data, dan mencari data.

# Tentang Program
Program ini memungkinkan pengguna untuk mengelola data nilai mahasiswa dengan cara memasukkan, mengubah, menghapus, mencari, dan menampilkan informasi terkait nilai Tugas, UTS, UAS, dan Nilai Akhir. Data disimpan dalam bentuk dictionary yang menggunakan NIM mahasiswa sebagai kunci, dan setiap entri berisi nama mahasiswa, nilai-nilai akademik, serta perhitungan Nilai Akhir.

Kode Program

![code nilai] (https://github-production-user-asset-6210df.s3.amazonaws.com/185802900/389189262-09f2b53f-c170-4971-9312-4a69d25f8091.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20241125%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20241125T090431Z&X-Amz-Expires=300&X-Amz-Signature=dacc98d0c05031f8972ea889a97eff1e3f0809f8e75fb326d327f166304ab85b&X-Amz-SignedHeaders=host)


### **Penjelasan Program**

**Struktur Program:**
- Program menggunakan `Dictionary` untuk menyimpan data mahasiswa, di mana key-nya adalah nama mahasiswa dan value-nya adalah sebuah dictionary yang berisi nilai tugas, UTS, UAS, dan nilai akhir.
- Terdapat menu interaktif yang memungkinkan pengguna untuk memilih berbagai aksi seperti menambah data, mengubah data, menghapus data, menampilkan data, dan mencari data.
- Program memanfaatkan `try-except` untuk menangani input yang tidak valid (misalnya jika pengguna memasukkan nilai yang bukan angka).
- Nilai akhir mahasiswa dihitung berdasarkan rumus yang diberikan:  
  \[
  \text{Nilai Akhir} = (Tugas \times 0.3) + (UTS \times 0.35) + (UAS \times 0.35)
  \]

**Fungsi-fungsi dalam Program:**
1. **`tambah_data()`**: Menambahkan data mahasiswa baru, termasuk nilai tugas, UTS, UAS, dan menghitung nilai akhir.
2. **`ubah_data()`**: Memungkinkan pengguna untuk memperbarui nilai mahasiswa berdasarkan nama.
3. **`hapus_data()`**: Menghapus data mahasiswa berdasarkan nama.
4. **`tampilkan_data()`**: Menampilkan seluruh data mahasiswa yang ada.
5. **`cari_data()`**: Mencari data mahasiswa berdasarkan nama.

### 4. **README.md**

```markdown
# Program Daftar Nilai Mahasiswa

## Deskripsi Program
Program ini digunakan untuk mengelola daftar nilai mahasiswa. Program memungkinkan pengguna untuk:
1. Menambah data mahasiswa.
2. Mengubah data mahasiswa.
3. Menghapus data mahasiswa.
4. Menampilkan seluruh data mahasiswa.
5. Mencari data mahasiswa berdasarkan nama.

## Alur Program
1. Program akan meminta pengguna memilih salah satu menu yang tersedia.
2. Pengguna dapat memilih untuk menambah, mengubah, menghapus, menampilkan, atau mencari data mahasiswa.
3. Nilai akhir dihitung dengan rumus:  
   \[
   \text{Nilai Akhir} = (Tugas \times 0.3) + (UTS \times 0.35) + (UAS \times 0.35)
   \]
4. Program akan menampilkan data sesuai dengan pilihan pengguna.

## Cara Menjalankan
1. Jalankan program dengan Python 3.x.
2. Pilih menu yang sesuai dengan memasukkan abjad (L, T, U, H, C, K).

## Teknologi yang Digunakan
- Python 3.x
- Dictionary untuk penyimpanan data

## Penulis
Program ini dibuat oleh [Mahfuz Fauzi].
```

# Selesai.
