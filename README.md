# Advanced Programming 

**Nama**: Wahyu Hidayat  
**NPM**: 2206081894  
**Kelas**: Advanced Programming B

## Tutorial 5

### Before
`/all-student`
<img width="1325" alt="all-student before" src="https://github.com/wahyuhiddayat/exercise-profiling/assets/119432989/64a3c67a-1a04-4314-9795-6787984e6eef">

`/all-student-name`
<img width="1325" alt="all-student-name before" src="https://github.com/wahyuhiddayat/exercise-profiling/assets/119432989/f46be76d-562e-475b-9ae7-6c776ba53603">

`/highest-gpa`
<img width="1322" alt="highest-gpa before" src="https://github.com/wahyuhiddayat/exercise-profiling/assets/119432989/934084e5-9a0d-4a34-981b-6db57b020813">

### After
`/all-student`
<img width="1282" alt="all-student after" src="https://github.com/wahyuhiddayat/exercise-profiling/assets/119432989/624a8901-62f3-4a73-8dd1-9e3c3d0ad4a9">

`/all-student-name`
<img width="1286" alt="all-student-name after" src="https://github.com/wahyuhiddayat/exercise-profiling/assets/119432989/5d7c2789-b48e-40d8-b4fa-ab34a2cf6a32">

`/highest-gpa`
<img width="1283" alt="highest-gpa after" src="https://github.com/wahyuhiddayat/exercise-profiling/assets/119432989/b4bbddc0-1d6c-40b1-b860-7c9cc4061e06">


### Reflection 

1. What is the difference between the approach of performance testing with JMeter and profiling with IntelliJ Profiler in the context of optimizing application performance?
   
   JMeter lebih cocok untuk pengujian skala besar dan simulasi beban kerja untuk menguji kinerja aplikasi dari sisi pengguna dan menentukan batas-batas kapasitas sistem.
   
   IntelliJ Profiler lebih fokus pada analisis internal aplikasi untuk mengidentifikasi dan memperbaiki masalah kinerja spesifik pada kode atau konfigurasi aplikasi.
   

2. How does the profiling process help you in identifying and understanding the weak points in your application?

    - Menunjukkan bagian kode yang paling banyak menggunakan CPU, yang bisa mengindikasikan loop yang tidak efisien atau pemrosesan yang berlebihan.
    - Mengidentifikasi kebocoran memori dan objek yang menggunakan banyak memori, membantu mengoptimalkan penggunaan memori.
    - Menyoroti operasi input/output yang lambat atau tidak efisien, seperti akses disk atau jaringan yang bisa memperlambat aplikasi.
    - Menganalisis waktu respons aplikasi untuk permintaan tertentu, membantu menemukan proses atau query yang memperlambat sistem.

3. Do you think IntelliJ Profiler is effective in assisting you to analyze and identify bottlenecks in your application code?

   Ya, IntelliJ Profiler efektif dalam membantu menganalisis dan mengidentifikasi bottleneck dalam kode aplikasi karena menyediakan insight mendalam tentang penggunaan sumber daya seperti CPU, memori, dan I/O, serta memungkinkan pengembang untuk menemukan secara spesifik bagian kode yang perlu dioptimalkan.

4. What are the main challenges you face when conducting performance testing and profiling, and how do you overcome these challenges?

   Masalah utama yang saya hadapi dalam melakukan pengujian kinerja dan profilisasi adalah saya tidak terbiasa dengan Java SpringBoot dan saya harus memastikan bahwa hal yang saya lakukan tidak mengubah fungsionalitas kode. Saya dapat menyelesaikan masalah ini berkat bantuan beberapa dokumen dan website seperti stackoverflow.

5. What are the main benefits you gain from using IntelliJ Profiler for profiling your application code?

   - Memudahkan pengidentifikasian bagian kode yang menyebabkan masalah kinerja, seperti penggunaan CPU dan memori yang tinggi.
   - Menyediakan wawasan tentang penggunaan memori, termasuk kebocoran memori, yang membantu dalam optimisasi memori.
   - Dengan mengetahui secara spesifik di mana masalah kinerja berada, waktu yang dibutuhkan untuk debugging dan optimisasi bisa berkurang signifikan.
   - Sebagai bagian dari IntelliJ IDEA, Profiler terintegrasi dengan alat pengembangan lainnya, memudahkan penggunaan dan akses ke fitur profilisasi tanpa meninggalkan IDE.

6. How do you handle situations where the results from profiling with IntelliJ Profiler are not entirely consistent with findings from performance testing using JMeter?

    Melakukan pengujian ulang, menggunakan alat yang lain, meninjau metrik yang berbeda.

7. What strategies do you implement in optimizing application code after analyzing results from performance testing and profiling? How do you ensure the changes you make do not affect the application's functionality?

    - Identifikasi area kritis dan fokus pada bagian kode yang paling banyak mengkonsumsi sumber daya atau yang paling mempengaruhi waktu respons.
    - Refaktorisasi kode dengan mengubah kode untuk membuatnya lebih efisien.

   Untuk memastikan perubahan tidak mempengaruhi fungsi saya menjalankan tes unit dan tes integrasi untuk memastikan bahwa logika program masih berfungsi seperti yang diharapkan setelah membuat perubahan. Tes ini harus mencakup semua kasus penggunaan dan edge cases.
