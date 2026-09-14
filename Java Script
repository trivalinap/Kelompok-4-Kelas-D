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
