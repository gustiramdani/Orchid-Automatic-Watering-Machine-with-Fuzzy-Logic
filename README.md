# Orchid Automatic Watering Machine with Fuzzy Logic

Sebuah sistem irigasi tetes cerdas untuk penyiraman pupuk pada tanaman anggrek, yang ditenagai sepenuhnya oleh energi surya dan dikontrol menggunakan teknologi IoT dengan pendekatan Logika Fuzzy.

📌 Latar Belakang
Petani tanaman hias, khususnya anggrek, seringkali menghadapi tantangan dalam memberikan penyiraman dan pemupukan yang presisi dan konsisten. Metode manual sangat bergantung pada tenaga manusia dan seringkali tidak efisien. Di sisi lain, kemajuan teknologi Internet of Things (IoT) menawarkan solusi untuk pertanian cerdas (Smart Farming) yang dapat meningkatkan produktivitas dan efisiensi. Proyek ini dikembangkan untuk menjawab tantangan tersebut dengan menciptakan sistem irigasi tetes yang otomatis, cerdas, dan ramah lingkungan untuk budidaya anggrek.

✨ Fitur Utama
1. Irigasi Tetes Otomatis: Menggunakan metode irigasi tetes yang sangat efisien dalam penggunaan air dan pupuk.
2. Tenaga Surya Mandiri: Sistem sepenuhnya ditenagai oleh panel surya dan aki, membuatnya hemat energi dan ramah lingkungan.
3. Kontrol Cerdas dengan Logika Fuzzy: Durasi dan jadwal penyiraman tidak hanya berdasarkan waktu, tetapi diatur secara cerdas menggunakan Logika Fuzzy untuk menginterpretasikan data kondisi tanaman.
4. Pemantauan Kapasitas Pupuk: Dilengkapi sensor ultrasonik untuk memantau level pupuk di dalam tangki secara real-time.
5. Pengisian Pupuk Otomatis: Pompa air akan otomatis mengisi ulang tangki utama ketika sensor mendeteksi level pupuk rendah.
6. Kontrol dan Monitoring Jarak Jauh: Pengguna dapat memantau kondisi dan mengontrol sistem (seperti mengatur jadwal atau mengaktifkan pompa) melalui aplikasi Blynk.

💡 Konsep Inti: Logika Fuzzy
Keunikan utama dari sistem ini adalah penggunaan Logika Fuzzy. Berbeda dengan logika biner (0 atau 1, hidup atau mati), Logika Fuzzy memungkinkan sistem untuk menangani ketidakpastian dan membuat keputusan yang lebih "manusiawi".Dalam proyek ini, Logika Fuzzy digunakan untuk:
- Menginterpretasikan data yang diinformasikan oleh mitra (misalnya, kondisi spesifik tanaman anggrek).
- Menganalisis data dari sensor untuk menghasilkan keputusan durasi penyiraman yang optimal dan responsif.
- Meningkatkan efisiensi proses penyiraman dengan memberikan perlakuan yang lebih pintar dan sesuai kebutuhan tanaman, bukan sekadar jadwal tetap.
- Simulasi sistem menggunakan MATLAB menunjukkan bahwa pendekatan ini secara konsisten mampu mengatur durasi penyiraman sesuai kebutuhan tanaman anggrek.

⚙️ Cara Kerja Sistem
-> Sumber Energi: Panel surya 60W mengisi daya aki yang menjadi sumber listrik utama untuk seluruh komponen.
-> Monitoring Level Pupuk: Sensor ultrasonik yang terpasang di tutup tandon memantau ketinggian cairan pupuk.
-> Konektivitas IoT: Modul ESP8266 menghubungkan sistem ke jaringan WiFi, mengirim data sensor ke aplikasi Blynk.
-> Jadwal & Logika Kontrol: Sistem menjalankan penyiraman pupuk secara otomatis sesuai jadwal yang telah ditentukan melalui aplikasi. Logika Fuzzy membantu menentukan durasi penyiraman yang paling tepat.
-> Proses Penyiraman: Pada waktu yang ditentukan, selenoid valve akan terbuka dan menyalurkan pupuk ke tanaman melalui sistem irigasi tetes.
-> Pengisian Ulang Otomatis: Jika sensor ultrasonik mendeteksi level pupuk di tandon rendah, sistem akan otomatis mengaktifkan pompa air untuk mengisi ulang tandon.

🛠️ Tumpukan Teknologi (Tech Stack)
Perangkat Keras (Hardware)
- Sumber Energi: Panel Surya, Aki Baterai 
- Mikrokontroler: ESP8266, ESP32 
- Sensor: Sensor Ultrasonik 
- Aktuator: Pompa Air, Solenoid Valve , Relay Red 5V 
- Modul Tambahan: Real Time Clock (RTC) , Shield ESP32 
- Lainnya: Box Panel, Drum Air, Pipa Paralon, Breadboard, Kabel Jumper 

Perangkat Lunak & Platform (Software & Platforms)
- Firmware: Arduino IDE (dengan bahasa C) 
- Platform IoT: Blynk 
- Analisis & Simulasi: MATLAB (untuk simulasi Logika Fuzzy)

🎨 Desain & Implementasi

<img width="1920" height="629" alt="3" src="https://github.com/user-attachments/assets/3832b977-e45b-49d5-a8a2-9a9ca290708e" />
<img width="1920" height="629" alt="6" src="https://github.com/user-attachments/assets/33f2de20-c074-4dca-aefd-b1d340bef921" />
<img width="1920" height="629" alt="5" src="https://github.com/user-attachments/assets/1baf895e-5ff2-4e10-9b6b-dc4d8035112a" />
<img width="1920" height="629" alt="4" src="https://github.com/user-attachments/assets/c2f26a5b-0770-4d0a-9914-b22c8b0d3b4d" />


👨‍💻 Tim Pengembang

1. Gusti Ramdani (Ketua Tim) 
2. Vina Puspitasari (Anggota) 
3. Zidan Febrian Indra Putra (Anggota) 
4. Muhammad Zikri Abdillah (Anggota)
5. Fajri Haykal Rahman (Anggota)
6. Muhammad Ifan Al Aziz (Anggota)
7. Cindy Ardhita Claudia Manurung (Anggota)
8. Zaki Rafi Athallah (Anggota)
