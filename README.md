# Simulasi-IoT Cisco Packet Tracert Kelompok 4
Selamat datang di repositori Simulasi IoT Smart Home! Proyek ini adalah simulasi sistem Smart Home berbasis IoT (Internet of Things) menggunakan Cisco Packet Tracer. Dalam simulasi ini, berbagai perangkat di seperti SBC-PT, lampu, pintu garasi, pintu, dan Montiom Sensor dapat diatur dan dikendalikan melalui sebuah aplikasi berbasis web yang terhubung ke jaringan rumah.
Tujuan utama projek ini adalah untuk mempelajari bagaimana perangkat IoT berkomunikasi dalam jaringan lokal, serta bagaimana kita dapat mengontrol dan memonitor perangkat-perangkat tersebut secara otomatis menggunakan teknologi jaringan.

Simulasi di bagi menjadi 3 yaitu:
1. Analog Led
2. Smart Home Digital
3. Smart Home IoT
   
Teknologi yang Digunakan
- Cisco Packet Tracer: Digunakan untuk mensimulasikan jaringan perangkat IoT di rumah pintar.
- IoT Devices: Berbagai perangkat IoT seperti SBC-PT, Montion Sensor, lampu dan Garage door.
- Protokol: Protokol komunikasi seperti MQTT atau HTTP digunakan untuk komunikasi antar perangkat.
- Pemrograman: Beberapa perangkat mungkin membutuhkan pemrograman menggunakan Python.

Langkah-langkah Menjalankan Simulasi
1. Unduh dan Install Cisco Packet Tracer jika belum memiliki.
   Link software: https://www.nesabamedia.com/download-cisco-packet-tracer/ 
2. Clone repositori ini:
   git clone https://github.com/irvan878/Simulasi-IoT
4. Buka file .pkt di Cisco Packet Tracer pada masing-masing folder.
5. Jalankan masing-masing simulasi dan lihat bagaimana perangkat Smart Home berfungsi.

-------------------------------------------------------------------------------------------------------------------------------
TOPOLOGI
- Analog Led
  Sistem ini menggunakan perangkat analog untuk mengontrol dan memantau perangkat output seperti LED. Sistem analog lebih sederhana dan tidak terhubung dengan internet atau perangkat lain dalam jaringan.
  Device :
  1. SBC-PT
  2. Rocker Switch
  3. Led
  Input seperti saklar rocker (rocker switch) digunakan untuk memberikan sinyal on/off, yang kemudian diproses oleh SBC (Single-Board Computer) dan dihubungkan ke LED sebagai output.
  ![image](https://github.com/user-attachments/assets/f8b8db82-7e7d-426a-9862-8d40d3dbeadb)

- Smart Home Digital
  Simuasi sistem digital ini, perangkat seperti sensor gerak dan pintu garasi dikendalikan dan dipantau secara otomatis. Semua perangkat terhubung dengan SBC yang mengatur logika dan proses secara lokal, tanpa melibatkan komunikasi
  nirkabel atau Internet.
