D_Kelompok_4

## Testing  GradeMath

**Test Case 1: Menghitung Nilai Akhir dan Grade (Happy Path - Grade A)**

Input:

• Tugas = 85

• Quiz = 80

• UTS = 80

• UAS = 85

Expected Output:
• Nilai Akhir: 82.5

• Grade: A

• Status Keluar Loop: Menunggu konfirmasi user ("ya/tidak")

Actual Output:
• Nilai Akhir: 82.5

• Grade: A

**Status: PASS**

---

**Test Case 2: Validasi Batas Input Nilai (Negative Case)**

Input:

• Tugas = -10 (Nilai tidak valid)

• Quiz = 80

• UTS = 75

• UAS = 90

Expected Output:

• Pesan Alert: "Error: Semua nilai harus berada di rentang 0 - 100!"

Actual Output:

• Pesan Alert: "Error: Semua nilai harus berada di rentang 0 - 100!"

**Status: PASS**

---

**Test Case 3: Menghentikan Perulangan Program (Loop Control)**

Input:

• Input Nilai = (Semua input valid)

• Prompt Keluar Loop = "tidak"

Expected Output:

• Program berhenti dan tidak memunculkan prompt pengisian nilai lagi.

Actual Output:

• Program berhenti.

**Status: PASS**
