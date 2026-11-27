MATRA ARSIP – Software Quality Assurance Testing

Deskripsi Project

Project ini merupakan kegiatan Software Quality Assurance (SQA) untuk melakukan pengujian kualitas website **MATRA ARSIP**.

Pengujian dilakukan menggunakan metode **Black Box Testing**, yaitu pengujian perangkat lunak yang berfokus pada fungsi sistem berdasarkan input dan output tanpa memeriksa struktur internal kode program.

Pengujian dilaksanakan melalui dua pendekatan, yaitu Manual Testing yang dilakukan secara langsung oleh tester dan Automation Testing menggunakan Selenium WebDriver.

Website yang diuji: 
https://matraarsip.co.id/

Tujuan Pengujian

1. Memastikan seluruh fitur website berjalan sesuai dengan kebutuhan dan fungsinya.
2. Mengidentifikasi kesalahan atau bug pada website.
3. Memastikan kesesuaian antara hasil aktual dengan hasil yang diharapkan.
4. Mendokumentasikan proses dan hasil pengujian berdasarkan standar dokumentasi pengujian perangkat lunak.
5. Melakukan pengujian fungsional secara manual dan otomatis.
6. Meningkatkan kualitas dan keandalan website MATRA ARSIP.

Ruang Lingkup Pengujian

Pengujian difokuskan pada akses **Public / Guest (pengunjung umum)** tanpa melakukan pengujian login pelanggan maupun administrator.

Fitur yang menjadi ruang lingkup pengujian meliputi:

- Halaman Home.
- Navigasi website.
- Halaman About.
- Informasi Visi dan Misi.
- Informasi layanan penyimpanan arsip.
- Informasi layanan pemeliharaan arsip.
- Informasi layanan pemusnahan arsip.
- Tombol dan tautan.
- Tampilan website pada desktop dan mobile.

Metode Pengujian

Project ini menggunakan metode **Black Box Testing**, yaitu metode pengujian perangkat lunak yang berfokus pada pengujian fungsionalitas sistem berdasarkan input dan output tanpa melihat struktur internal kode program.

Pengujian dilakukan melalui dua pendekatan:

1. Manual Testing

Manual Testing merupakan proses pengujian yang dilakukan secara langsung oleh tester dengan menjalankan fitur-fitur website berdasarkan test scenario dan test case yang telah dibuat.

Tahapan pengujian:

1. Membuka website melalui browser.
2. Menjalankan fitur sesuai test case.
3. Memberikan input atau melakukan interaksi pada website.
4. Mengamati output atau respons sistem.
5. Membandingkan hasil aktual dengan expected result.
6. Mencatat status pengujian (Pass/Fail).
7. Mendokumentasikan bug apabila ditemukan.

2. Automation Testing

Automation Testing merupakan proses pengujian yang dilakukan secara otomatis menggunakan **Selenium WebDriver** dengan tetap menerapkan metode Black Box Testing.

Selenium digunakan untuk menjalankan interaksi dengan elemen website melalui script otomatis dan memeriksa hasil yang diberikan oleh sistem.

Tahapan pengujian:

1. Menyiapkan Selenium WebDriver dan browser.
2. Membuat script automation berdasarkan test case.
3. Menjalankan website melalui browser yang dikendalikan Selenium.
4. Melakukan interaksi otomatis pada fitur website.
5. Memeriksa respons dan output sistem.
6. Membandingkan hasil aktual dengan expected result.
7. Mendokumentasikan hasil pengujian otomatis.

Ringkasan Metode Pengujian

| Aspek | Manual Testing | Automation Testing |
|---|---|---|
| Metode | Black Box Testing | Black Box Testing |
| Pelaksanaan | Manual oleh tester | Otomatis menggunakan script |
| Tools | Web Browser | Selenium WebDriver |
| Dasar Pengujian | Test Scenario & Test Case | Test Case |
| Hasil Pengujian | Pass / Fail | Pass / Fail |

Standar ISO yang Digunakan

Project ini mengacu pada standar internasional berikut:

| Standar | Keterangan |
|---|---|
| ISO/IEC 25010:2023 | Software Product Quality Model |
| ISO/IEC 25002:2024 | Quality Model Overview |
| ISO/IEC/IEEE 29119-3:2021 | Test Documentation |
| ISO/IEC/IEEE 29119-4:2021 | Test Techniques |

Standar tersebut digunakan sebagai referensi dalam memahami kualitas perangkat lunak, teknik pengujian, dan penyusunan dokumentasi pengujian.

Anggota Tim dan Pembagian Tugas

Berikut merupakan pembagian tugas anggota tim dalam kegiatan Software Quality Assurance:

| No. | Nama | Tanggung Jawab |
|---|---|---|
| 1 | Habib | Test Plan & Manual Testing |
| 2 | Silvi | Test Scenario & Test Case |
| 3 | Wildan | Bug Report & Test Result |
| 4 | Dwi | Test Automation & RTM (Selenium) |

Detail Tanggung Jawab

1. Habib – Test Plan & Manual Testing

Bertanggung jawab dalam menyusun perencanaan pengujian dan melaksanakan pengujian manual.

Tugas:
- Menyusun dokumen Test Plan.
- Menentukan tujuan dan ruang lingkup pengujian.
- Menentukan strategi pengujian.
- Menentukan lingkungan pengujian.
- Melaksanakan pengujian manual menggunakan Black Box Testing.
- Mendokumentasikan hasil pengujian manual.

2. Silvi – Test Scenario & Test Case

Bertanggung jawab dalam menyusun skenario dan kasus pengujian berdasarkan fitur website.

Tugas:
- Mengidentifikasi fitur yang akan diuji.
- Menyusun Test Scenario.
- Membuat Test Case.
- Menentukan langkah-langkah pengujian.
- Menentukan Expected Result.
- Memastikan test case mencakup kebutuhan fungsional website.

3. Wildan – Bug Report & Test Result

Bertanggung jawab dalam mendokumentasikan kesalahan sistem dan hasil pengujian.

Tugas:
- Mengidentifikasi bug yang ditemukan selama pengujian.
- Menyusun Bug Report.
- Mendokumentasikan langkah reproduksi bug.
- Menentukan tingkat prioritas bug.
- Menyusun Test Result.
- Membuat rekapitulasi hasil pengujian.

4. Dwi – Test Automation & RTM (Selenium)

Bertanggung jawab dalam melaksanakan pengujian otomatis dan menyusun Requirement Traceability Matrix.

Tugas:
- Menyiapkan Selenium WebDriver.
- Membuat script Automation Testing.
- Menjalankan pengujian otomatis menggunakan Selenium.
- Melakukan validasi hasil pengujian berdasarkan expected result.
- Mendokumentasikan hasil Automation Testing.
- Menyusun Requirement Traceability Matrix (RTM).
- Memastikan kebutuhan pengujian terhubung dengan test scenario dan test case.

Tools yang Digunakan

Berikut merupakan tools yang digunakan dalam proses pengujian:

| Tools | Kegunaan |
|---|---|
| GitHub | Penyimpanan kode dan dokumentasi project |
| Selenium WebDriver | Menjalankan Automation Testing |
| Web Browser | Media untuk melakukan pengujian website |
| Microsoft Excel / Google Sheets | Membuat dokumentasi Test Plan, Test Case, Bug Report, Test Result, dan RTM |
| Visual Studio Code | Membuat dan mengelola script Automation Testing |

Dokumentasi Project

Dokumentasi pengujian dalam project ini terdiri dari:

| No. | Dokumentasi | Penanggung Jawab |
|---|---|---|
| 1 | Test Plan | Habib |
| 2 | Manual Testing | Habib |
| 3 | Test Scenario | Silvi |
| 4 | Test Case | Silvi |
| 5 | Bug Report | Wildan |
| 6 | Test Result | Wildan |
| 7 | Automation Testing (Selenium) | Dwi |
| 8 | Requirement Traceability Matrix (RTM) | Dwi |

Status Hasil Pengujian

Hasil pengujian akan dicatat berdasarkan status berikut:

| Status | Keterangan |
|---|---|
| PASS | Fitur berjalan sesuai dengan hasil yang diharapkan |
| FAIL | Fitur tidak berjalan sesuai dengan hasil yang diharapkan |
| NOT TESTED | Fitur belum dilakukan pengujian |
| BLOCKED | Pengujian tidak dapat dilanjutkan karena terdapat kendala |

Hasil pengujian manual dan otomatis akan didokumentasikan untuk mengetahui kesesuaian fungsi website terhadap kebutuhan yang telah ditentukan.

Kesimpulan

Kegiatan Software Quality Assurance pada website MATRA ARSIP dilakukan untuk memastikan bahwa setiap fitur berjalan sesuai dengan fungsinya.

Pengujian menggunakan metode Black Box Testing melalui dua pendekatan, yaitu Manual Testing dan Automation Testing menggunakan Selenium WebDriver.

Melalui proses pengujian ini, diharapkan kesalahan pada website dapat diidentifikasi dan didokumentasikan sehingga dapat menjadi bahan evaluasi untuk meningkatkan kualitas serta keandalan website MATRA ARSIP.

--

Project Team

Software Quality Assurance – MATRA ARSIP

- Habib – Test Plan & Manual Testing
- Silvi – Test Scenario & Test Case
- Wildan – Bug Report & Test Result
- Dwi – Test Automation & RTM (Selenium)

Testing Method: Black Box Testing  
Testing Approach: Manual Testing & Automation Testing  
Automation Tool: Selenium WebDriver  
Documentation Reference: ISO/IEC 25010, ISO/IEC 25002, ISO/IEC/IEEE 29119
