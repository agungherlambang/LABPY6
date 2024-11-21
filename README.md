# LABPY6
# NAMA: AGUNG HERLAMBANG
# NIM: 312410296
# KELAS: TI.24.A4
## Program Pengelolaan Data Mahasiswa
![gambar](https://github.com/user-attachments/assets/442240d4-2793-4d3d-9a40-f1cf0b8a9fda)

# penjelasan programm

## Perhitungan Nilai Akhir
Nilai akhir pelajar dihitung berdasarkan bobot sebagai berikut:
* Tugas: 30%
* UTS: 35%
* UAS: 35%.

## Komponen Program

### 1. sruktur data 
Data siswa disimpan dalam daftar bernama data_list, yang berisi elemen kamus. Setiap kamus mewakili satu pelajar dengan format berikut:

```pyhton
{
    'Nama': 'Nama Mahasiswa',
    'NIM': 'NIM Mahasiswa',
    'Tugas': 80.0,  # Nilai Tugas
    'UTS': 75.0,    # Nilai UTS
    'UAS': 85.0,    # Nilai UAS
    'Nilai Akhir': 81.5  # Hasil perhitungan nilai akhir
}
````
### 2. Fungsi-Fungsi Utama
### oi_final_grade(tugas, uts, uas)

Fungsi ini menghitung nilai akhir siswa berdasarkan bobot masing-masing:
* Tugas: 30%
* UTS: 35%
* UAS: 35%.

```pyhton
def oi_final_grade(tugas, uts, uas):
    return (tugas * 0.30) + (uts * 0.35) + (uas * 0.35)

