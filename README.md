# Mini Programming Project
Tugas Kelompok Logika Pemograman 

## 1. Group Information 
**Kelas:** D
**Kelompok:** 4

## Group Members
|No.| Nama | NIM | Role |
| --- | --- | --- |--- |
| 1.| Trivalin Prabowo | 260312127 | --- |
| 2.| Timothy Prawira Sirait | 2610312106 | JavaScript |
| 3.| Muhammad Fadhil Ramadhan | 2610312135 | --- | 
| 4.| Patricks Fabio Rongrong | 2610312121 | --- |
| 5.| Rasyad Kurniawan Syahputra | 2610312132| ---|

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

## 8. ALgorithm 
Link Pseudocode

[pseudocode.md](./pseudocode.md) 
ini draft pseudocode ya belum tentu fix

---

## 9. Flowchart 
sama masukin kesini juga 

---

## 10. JavaScript Implementation
```javascript
let ulang = "ya";

while (ulang.toLowerCase() === "ya") {
  let Tugas = Number(prompt("Masukkan Nilai Tugas:"));
  let Quiz = Number(prompt("Masukkan Nilai Quiz:"));
  let UTS = Number(prompt("Masukkan Nilai UTS:"));
  let UAS = Number(prompt("Masukkan Nilai UAS:"));

  if (Tugas < 0 || Tugas > 100 || Quiz < 0 || Quiz > 100 || UTS < 0 || UTS > 100 || UAS < 0 || UAS > 100) {
    alert("Error: Semua nilai harus berada di rentang 0 - 100!");
  } else {
    let NilaiAkhir = (Tugas * 0.2) + (Quiz * 0.2) + (UTS * 0.3) + (UAS * 0.3);
    let grade;

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
    }
    alert("Nilai Akhir: " + NilaiAkhir + "\nGrade: " + grade);
  }
  ulang = prompt("Apakah ingin menghitung nilai mahasiswa lain? (ya/tidak)");
}
```
---

## 11. Testing 
masukin sini juga filenya 


