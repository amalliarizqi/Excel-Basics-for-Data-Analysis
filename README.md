# Excel Basics for Data Analysis

Repository ini berisi proyek latihan analisis data menggunakan Microsoft Excel dari kursus *Excel Basics for Data Analysis* oleh IBM di Coursera.

Terdapat dua proyek yang dikerjakan, yaitu pembersihan data (*data cleaning*) dan analisis data menggunakan Excel.

## Project 1: Clean and Prepare the Data

### Dataset

Dataset yang digunakan dalam proyek ini adalah **Montgomery Fleet Equipment Inventory**.

Dataset ini berisi data inventaris peralatan armada Montgomery County. Dataset awal digunakan sebagai bahan latihan untuk proses pembersihan dan persiapan data sebelum analisis dilakukan.

**Dataset:** [Montgomery Fleet Equipment Inventory](https://github.com/amalliarizqi/Excel-Basics-for-Data-Analysis/blob/main/Montgomery_Fleet_Equipment_Inventory_FA_PART_1_START.csv)

### Tahapan Pembersihan Data

Proses pembersihan dan persiapan data meliputi beberapa tahapan berikut.

1. **Konversi Format File**  
   Mengubah file CSV menjadi format Excel (.xlsx) agar dapat diolah menggunakan Microsoft Excel.

2. **Penyesuaian Lebar Kolom**  
   Mengatur lebar kolom agar isi data terlihat dengan jelas.

3. **Menghapus Baris Kosong**  
   Menggunakan fitur Filter untuk menemukan dan menghapus baris kosong. Dengan memilih kolom Blanks lalu menghapus baris yang kosong yang ditampilkan.

4. **Menghapus Data Duplikat**  
   Mengidentifikasi dan menghapus catatan yang terduplikasi menggunakan Conditional Formatting atau Remove Duplicates.

5. **Memperbaiki Kesalahan Ejaan**  
   Memeriksa dan memperbaiki kesalahan ejaan pada data. Dengan memilih kolom yang tersedia dan menggguanakan spelling.

6. **Menghapus Spasi Ganda**  
   Menggunakan fitur Find and Replace untuk menghapus spasi ganda dalam data. Mengguanakan fungsi Trim jika terdapat spasi di awal dan diakhir dengan kolom bantuan.

7. **Merapikan Nama Departemen**  
   Menggunakan fitur Flash Fill untuk menggabungkan nama departemen yang terpisah ke dalam satu kolom, kemudian menghapus kolom yang tidak diperlukan.

Hasil https://github.com/amalliarizqi/Excel-Basics-for-Data-Analysis/blob/main/Montgomery_Fleet_Equipment_Inventory_FA_PART_1_END.xlsx

## Project 2: Analyze the Data

### Dataset

Proyek ini menggunakan dataset Montgomery Fleet Equipment Inventory untuk menganalisis data inventaris armada menggunakan Microsoft Excel.

**Dataset:** [Montgomery Fleet Equipment Inventory — Part 2 (XLSX)](https://github.com/amalliarizqi/Excel-Basics-for-Data-Analysis/blob/main/Montgomery_Fleet_Equipment_Inventory_FA_PART_2_START.xlsx)

### Tahapan Analisis Data

**1. Memformat Data sebagai Tabel**

Menggunakan fitur Format as Table untuk mengubah data menjadi tabel Excel agar lebih mudah dikelola dan dianalisis.

**2. Menghitung Statistik Data**

Menggunakan fitur AutoSum untuk menghitung nilai SUM, AVERAGE, MIN, MAX, dan COUNT pada kolom C.

**3. Membuat PivotTable Berdasarkan Departemen**

Membuat PivotTable yang menampilkan jumlah peralatan berdasarkan departemen.

**4. Mengurutkan Hasil PivotTable**

Mengurutkan jumlah peralatan dari nilai terbesar ke terkecil untuk mengetahui departemen dengan jumlah peralatan terbanyak.

**5. Membuat Dua PivotTable Tambahan**

Membuat dua lembar kerja tambahan, yaitu Pivot Table 2 dan Pivot Table 3, dengan struktur awal yang sama seperti Pivot Table 1.

**6. Menganalisis Data Berdasarkan Kelas Peralatan**

- **Pivot Table 2:** Menampilkan kelas peralatan di bawah departemen untuk melihat jumlah peralatan berdasarkan departemen dan kelas peralatan.
- **Pivot Table 3:** Menampilkan kelas peralatan di atas departemen untuk melihat jumlah peralatan berdasarkan kelas peralatan dan departemen.

**7. Menyimpan Hasil Akhir**

Menyimpan dan mengunduh workbook yang telah selesai dianalisis dalam format Excel (.xlsx).

Hasil Akhir
