# Pertemuan 10 - String dan Pengolahan Teks

- **Nama:** Lina Mulyana Ismail
- **NIM:** 2225250145
- **Mata Kuliah:** Algoritma dan Pemrograman (S1 Pendidikan Matematika FKIP Untirta)

## Tujuan
Mengolah dan menormalisasi data teks dengan string Python secara modular menggunakan fungsi.

## Struktur Program
- Folder `latihan/`: Berisi skrip latihan dasar string (01 sampai 06).
- Folder `tugas/`: Berisi program utama `normalisasi_data_mahasiswa.py`.

## Cara Menjalankan Program
python3 tugas/normalisasi_data_mahasiswa.py

## Test Case
| Input Nama | Input Kode | Hasil Utama (Nama | Kode | Inisial) | Status |
| :--- | :--- | :--- | :--- |
| `aan hendrayana` | `pmat a 2026` | `Aan Hendrayana \| PMAT-A-2026 \| AH` | Lulus |
| `fATHIYYAH MUTHMAINNAH` | `kelas b` | `Fathiyyah Muthmainnah \| KELAS-B \| FM` | Lulus |
| `BUDI` | `pmtk 01` | `Budi \| PMTK-01 \| B` | Lulus |
| `siti nur aisyah` | `kelas c` | `Siti Nur Aisyah \| KELAS-C \| SNA` | Lulus |

## Refleksi
- **Pemahaman:** Karakter string bersifat *immutable*, sehingga pembersihan teks memerlukan pembuatan string baru menggunakan method seperti `strip()`, `title()`, `split()`, dan `join()`.
- **Kendala/Perbaikan:** Spasi berlebih di tengah nama dapat diatasi dengan menggabungkan method `split()` dan `join()` secara tepat.