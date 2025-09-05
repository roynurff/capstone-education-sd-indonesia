📊 Analisis Kelayakan Pendidikan SD di Indonesia

📌 Project Overview

Pendidikan dasar (SD) merupakan fondasi penting dalam membentuk karakter, kemampuan berpikir kritis, rasa empati, dan kepedulian sosial siswa. Kualitas pendidikan di tingkat SD akan sangat menentukan perkembangan pendidikan di jenjang berikutnya serta berkontribusi pada pembangunan sumber daya manusia Indonesia.
Proyek ini menganalisis data kelayakan pendidikan SD di Indonesia menggunakan clustering dan dukungan AI untuk menemukan pola, kelemahan, serta rekomendasi kebijakan.

📂 Dataset

1. Nama File: kelayakan-pendidikan-indonesia.csv

2. Sumber: Dataset publik (telah disiapkan untuk analisis)

3. Link: [Dataset Repository](https://www.kaggle.com/datasets/puanbeningpastika/dataset-pendidikan-sd-indonesia-2023-2024)

🔎 Analysis Process

1. Data Preparation

   a. Pembersihan data & pengecekan missing values.

   b. Pembuatan fitur baru:

   - Siswa_per_Sekolah

   - Persen_KepsekdanGuru_S1

   - Persen_Putus_Sekolah

   - Persen_Mengulang

2. Clustering

   a. Menggunakan KMeans untuk mengelompokkan provinsi berdasarkan kualitas pendidikan SD.

   b. Hasil klasifikasi menghasilkan 3 cluster utama.

3. AI Summarization

   a. Menggunakan IBM Granite 3.3-2B-Instruct (via LM Studio) untuk melakukan summarization, insight extraction, dan rekomendasi strategis.

📈 Insight & Findings
1. Cluster 1 – Provinsi Berpotensi Tinggi

   a. Kualitas guru relatif tinggi.

   b. Infrastruktur sekolah relatif baik.

   c. Rasio siswa per sekolah masih dalam batas wajar.

2. Cluster 0 – Provinsi Perlu Fokus Perhatian

   a. Rasio siswa lebih tinggi, mengindikasikan beban sekolah.

   b. Persentase guru S1 lebih rendah dibanding Cluster 1.

   c. Infrastruktur sekolah masih belum merata.

3. Cluster 2 – Provinsi dengan Data Terbatas

   a. Keterbatasan data membuat evaluasi detail sulit dilakukan.

   b. Perlu investasi dalam pengumpulan data serta monitoring.

✅ Conclusion & Recommendations

1. Cluster 1: Pertahankan kualitas guru & terus investasi pada infrastruktur.

2. Cluster 0: Fokus pada pelatihan guru, peningkatan kualitas infrastruktur, dan penurunan rasio siswa per sekolah.

3. Cluster 2: Perkuat sistem data pendidikan dan monitoring kualitas sekolah dasar.

4. Secara Umum:

   a. Implementasi evaluasi berkala berbasis data.

   b. Mendorong pemerataan distribusi guru berkualitas di seluruh Indonesia.

   c. Tingkatkan program pengembangan kapasitas guru dan kepsek.

🤖 AI Support Explanation

AI berperan dalam proyek ini untuk:

1. Summarization & Insight Extraction: Menggunakan IBM Granite 3.3-2B-Instruct di LM Studio untuk merangkum hasil clustering.

2. Recommendation Generation: Memberikan saran berbasis data mengenai perbaikan kualitas pendidikan dasar.

3. Support Decision Making: Memperkuat analisis kuantitatif dengan interpretasi kualitatif yang lebih bermakna.
