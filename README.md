# Mini Programming Project
Tugas Kelompok Logika Pemograman 

## 1. Group Information 
**Kelas:** D
**Kelompok:** 4

## Group Members
|No.| Nama | NIM | Role |
| --- | --- | --- |--- |
| 1.| Trivalin Prabowo | 260312127 | Project Coordinator |
| 2.| Timothy Prawira Sirait | 2610312106 | JavaScript |
| 3.| Muhammad Fadhil Ramadhan | 2610312135 | --- | 
| 4.| Patricks Fabio Rongrong | 2610312121 | --- |
| 5.| Rasyad Kurniawan Syahputra | 2610312132| Flowchart |

---

## 2. GradeMate (Student Calculator)
Kalkulator untuk membantu nilai mahasiswa.

---

## 3. Project Description 
Alat bantu mahasiswa untuk menghitung kalkulasi akumulasi nilai akhir mahasiswa berdasarkan nilai harian ( Tugas dan Kuis ) hingga nilai ujian (ATS & AAS) secara cepat dan akurat.

---

## 4. Objective 
Project ini dirancang dengan menerapkan konsep konspe pemograman :
1. Loops
2. Variable
3. Data Types
4. Operator
5. Conditional Statement
6. Arithmetic & Comparison Operators
7. JavaScript

---

## 5. Input 
- Nilai Tugas (skala 0–100)
- Nilai Quiz (skala 0–100)
- Nilai UTS (skala 0–100)
- Nilai UAS (skala 0–100)
- Konfirmasi ulangi program (`ya` / `tidak`)

---

## 6. Process
- **Validasi Input**: Memeriksa apakah setiap nilai yang dimasukkan berada dalam rentang `0` sampai `100`. Jika di luar rentang, program menampilkan pesan peringatan error.
- **Kalkulasi Nilai Akhir**: Menghitung akumulasi nilai berdasarkan bobot masing-masing komponen:
  $$\text{Nilai Akhir} = (20\% \times \text{Tugas}) + (20\% \times \text{Quiz}) + (30\% \times \text{UTS}) + (30\% \times \text{UAS})$$
- **Konversi Grade**: Menentukan huruf mutu/grade berdasarkan nilai akhir:
   if (NilaiAkhir >= 80) {
      grade = "A";
    } else if (NilaiAkhir >= 70) {
      grade = "B";
    } else if (NilaiAkhir >= 60) {
      grade = "C";
    } else if (NilaiAkhir >= 50) {
      grade = "D";
    } else {
      grade = "E";
- **Perulangan (Looping)**: Mengecek input konfirmasi dari pengguna untuk menentukan apakah proses perhitungan diulang kembali.

---

## 7. Ouput 
- Pesan peringatan (Error) jika nilai tidak valid (x <=0 atau x >=100).
- Hasil perhitungan Nilai Akhir dan Grade mahasiswa (ditampilkan via `alert`)

---

## 8. Algorithm 
Link Pseudocode
 [pseudocode Kelompok 4](./Pseudocode%20kelompokk%204.txt)

---

## 9. Flowchart 
Flowchart kami dibuat dengan aplikasi Flowgorithm
File : [Diagram Flowgarithm](./flowgarithm%20kelompok%204.fprg)

---

## 10. JavaScript Implementation
Implementasi JavaScript dalam program kami tersedia melalui file berikut :
[Script.js](./Script.js)

---

## 11. Testing 
masukin sini juga filenya 


