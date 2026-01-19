```mermaid
flowchart TD
    A[Faktor Predisposisi] --> B1[Pemecahan eritrosit meningkat]
    A --> B2[Fungsi hati belum matang (enzim glukuronil transferase rendah)]
    A --> B3[Sirkulasi enterohepatik meningkat]

    B1 --> C1[Eritrosit pecah → Hemoglobin dilepas]
    C1 --> C2[Hemoglobin → Heme + Globin]
    C2 --> C3[Heme diubah menjadi Bilirubin Tidak Terkonjugasi (Indirek)]
    C3 --> C4[Bilirubin Indirek masuk ke hati → proses konjugasi belum sempurna]
    C4 --> C5[Penumpukan bilirubin tidak terkonjugasi dalam darah]
    C5 --> C6[Penumpukan di kulit & sklera → Timbul warna kuning (Ikterus)]

    C6 --> D{Klasifikasi}
    D --> D1[Ikterus Fisiologis<br/>Muncul >24 jam, kadar <15 mg/dL, bayi aktif]
    D --> D2[Ikterus Patologis<br/>Muncul <24 jam, kadar >15 mg/dL, bayi lesu]

    D1 --> E1[Observasi warna kulit & zona Kramer]
    D1 --> E2[Menyusui sering (8–12x/hari)]
    D1 --> E3[Edukasi ibu tanda bahaya]
    
    D2 --> F1[Periksa kadar bilirubin]
    D2 --> F2[Fototerapi / Rujuk ke fasilitas lanjutan]
    D2 --> F3[Monitor tanda ensefalopati bilirubin]

    E1 --> G1[Evaluasi & Outcome<br/>Kuning berkurang, bayi aktif, bilirubin <10 mg/dL]
    F1 --> G2[Outcome<br/>Kadar bilirubin menurun, bayi pulih, tanpa komplikasi]
