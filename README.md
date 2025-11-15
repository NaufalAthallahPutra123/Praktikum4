# Praktikum4

## Flowchart
          ┌──────────────────────┐
          │   Mulai Program      │
          └──────────┬───────────┘
                     │
          ┌──────────▼───────────┐
          │ Input Nama, NIM,      │
          │ Nilai Tugas, UTS, UAS │
          └──────────┬───────────┘
                     │
          ┌──────────▼───────────┐
          │ Hitung Nilai Akhir   │
          │ (0.30*T + 0.35*U +   │
          │  0.35*UA)            │
          └──────────┬───────────┘
                     │
          ┌──────────▼───────────┐
          │ Simpan data ke list  │
          └──────────┬───────────┘
                     │
          ┌──────────▼───────────┐
          │ Tambah data (y/t)?   │
          └───────┬─────┬────────┘
                  │     │
                y │     │ t
                  │     │
        ┌─────────▼     ▼────────┐
        │ Kembali input data      │
        │ (loop ulang)            │
        └─────────┬──────────────┘
                  │
      ┌───────────▼───────────────┐
      │ Tampilkan seluruh data     │
      └───────────┬───────────────┘
                  │
      ┌───────────▼───────────────┐
      │       Selesai              │
      └────────────────────────────┘

## Penjelasan
Program Input Data Mahasiswa (Python)

Program ini dibuat untuk memenuhi tugas praktikum: menambahkan data mahasiswa ke dalam sebuah list menggunakan perulangan, lalu menampilkan data dalam bentuk tabel.

Fitur Program

Meminta input data mahasiswa berupa:

Nama

NIM

Nilai Tugas

Nilai UTS

Nilai UAS

Menghitung nilai akhir berdasarkan bobot:

Tugas: 30%

UTS: 35%

UAS: 35%

Menyimpan data ke dalam list.

Menampilkan pertanyaan:

Tambah data (y/t)?


Jika user memilih t, program menampilkan tabel seluruh data mahasiswa.

## Tampilan Program
### Input
<img width="1920" height="1080" alt="ss1" src="https://github.com/user-attachments/assets/9230e9ec-130b-49b6-8819-8288ab56aa0c" />

### Output
<img width="1920" height="1080" alt="ss2" src="https://github.com/user-attachments/assets/7164f746-c95e-4a82-9b83-6ed8c255cb5f" />



