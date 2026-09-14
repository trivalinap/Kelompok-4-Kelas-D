PROGRAM GRADEMATE (Student Calculator) 

        ulang = "ya" DO
        // Input nilai dari pengguna
        BACA Tugas
        BACA Quiz
        BACA UTS
        BACA UAS

        // Validasi rentang nilai (0 - 100)
        IF (Tugas < 0 OR Tugas > 100 OR Quiz < 0 OR Quiz > 100 OR UTS < 0 OR UTS > 100 OR UAS < 0 OR UAS > 100) THEN
            TAMPILKAN "Error: Semua nilai harus berada di rentang 0 - 100!"
        ELSE
            // Hitung nilai akhir berdasarkan bobot
            NilaiAkhir = (Tugas * 0.2) + (Quiz * 0.2) + (UTS * 0.3) + (UAS * 0.3)

            // Penentuan Grade
            IF NilaiAkhir >= 80 THEN
                grade = "A"
            ELSE IF NilaiAkhir >= 70 THEN
                grade = "B"
            ELSE IF NilaiAkhir >= 60 THEN
                grade = "C"
            ELSE IF NilaiAkhir >= 50 THEN
                grade = "D"
            ELSE
                grade = "E"
            ENDIF

            // Tampilkan hasil
            TAMPILKAN "Nilai Akhir: " + NilaiAkhir
            TAMPILKAN "Grade: " + grade
        ENDIF

        // Konfirmasi perulangan
        BACA ulang
    ENDWHILE
END
