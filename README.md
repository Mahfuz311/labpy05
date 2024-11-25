# labpy05

Nama: Mahfuz Fauzi

NIM: 312410412

Kelas: TI.24.A.3

# Program Input Nilai Mahasiswa

Program sederhana untuk mengelola data nilai mahasiswa menggunakan Python dengan struktur data Dictionary.

program sederhana yang akan menampilkan daftar nilai mahasiswa menggunakan `Dictionary`, Program ini mencakup menu pilihan untuk menambah data, mengubah data, menghapus data, menampilkan data, dan mencari data.

# Flowchart

<img src="https://github.com/Mahfuz311/labpy05/blob/main/labpy05/flowwchart.png">


# Tentang Program
Program ini memungkinkan pengguna untuk mengelola data nilai mahasiswa dengan cara memasukkan, mengubah, menghapus, mencari, dan menampilkan informasi terkait nilai Tugas, UTS, UAS, dan Nilai Akhir. Data disimpan dalam bentuk dictionary yang menggunakan NIM mahasiswa sebagai kunci, dan setiap entri berisi nama mahasiswa, nilai-nilai akademik, serta perhitungan Nilai Akhir.

Kode Program

![code nilai]

<img src="https://github.com/Mahfuz311/labpy05/blob/main/labpy05/Code%20.png">


### **Penjelasan Program**

**Struktur Program:**
- Program menggunakan `Dictionary` untuk menyimpan data mahasiswa, di mana key-nya adalah nama mahasiswa dan value-nya adalah sebuah dictionary yang berisi nilai tugas, UTS, UAS, dan nilai akhir.
- Terdapat menu interaktif yang memungkinkan pengguna untuk memilih berbagai aksi seperti menambah data, mengubah data, menghapus data, menampilkan data, dan mencari data.
- Program memanfaatkan `try-except` untuk menangani input yang tidak valid (misalnya jika pengguna memasukkan nilai yang bukan angka).
- Nilai akhir mahasiswa dihitung berdasarkan rumus yang diberikan:  
  \[
  \text{Nilai Akhir} = (Tugas \times 0.3) + (UTS \times 0.35) + (UAS \times 0.35)
  \]

# Hasil Program

<img src="https://github.com/Mahfuz311/labpy05/blob/main/labpy05/Hasil%20Program.png">


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
