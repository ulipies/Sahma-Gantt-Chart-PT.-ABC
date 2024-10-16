```mermaid
gantt
    title Gantt Chart Proyek Pelatihan Capacity Building
    dateFormat  YYYY-MM-DD
    section Persiapan
    Analisis Kebutuhan           :a1, 2023-09-01, 7d
    Desain Kurikulum             :a2, after a1, 5d
    Pengembangan Materi          :a3, after a2, 10d
    Persiapan Logistik           :a4, after a3, 5d
    section Pelaksanaan
    Pelatihan Hari 1             :b1, 2023-12-01, 1d
    Pelatihan Hari 2             :b2, after b1, 1d
    Pelatihan Hari 3             :b3, after b2, 1d
    section Evaluasi
    Pengumpulan Feedback         :c1, after b3, 2d
    Analisis Hasil               :c2, after c1, 3d
    Penyusunan Laporan           :c3, after c2, 5d
    section Milestone
    Pengunggahan Proposal        :milestone, 2023-09-30, 0d
