# Jobsheet-2

PROTOKOL KOMUNIKASI DAN SENSOR
TUJUAN
1) Mahasiswa dapat memahami cara kerja protokol komunikasi yang terdapat pada ESP32, seperti UART, I2C, OneWire, SPI.
2) Mahasiswa dapat menggunakan protokol komunikasi data seperti UART, I2C, OneWire, dan SPI untuk mengakses sensor.
3) Mahasiswa dapat memanfaatkan transducer sensor dan actuator untuk membuat sebuah perangkat IoT.

ALAT DAN BAHAN
1) ESP32
2) Servo
3) Breadboard
4) Kabel jumper
5) Sensor DHT 11, RFID
6) LED (5) dan Push Button (3)
7) Resistor 330,1K, 10K Ohm (3)

TEORI SINGKAT
ESP32 adalah nama dari mikrokontroler yang dirancang oleh perusahaan yang berbasis di Shanghai, China yakni Espressif Systems. ESP32 menawarkan solusi jaringan WiFi dan BLE. ESP32 menggunakan prosesor dual core yang berjalan di instruksi Xtensa LX16. Selain itu, ESP32 telah mendukung protokol komunikasi seperti I2C, UART dan SPI.

A. ESP32 Capacitive Touch Sensor
1. Hubungkan kabel jumper Male-to-Female pada Pin D4 ESP32 buka Arduino IDE dan upload script program berikut ke ESP32.Buka serial monitor untuk melihat raw data ubah tampilan serial monitor menjadi Serial Plotter pada menu Tools > Serial Plotter sentuh ujung kabel jumper dan amati yang terjadi, kemudian dokumentasikan 
hasilnya.


https://user-images.githubusercontent.com/121847212/210311533-b1d809f9-4a75-49c2-9fa3-8b2584ae44ec.mp4


2. Buatlah program agar LED menyala ketika sensor disentuh, dan LED akan mati ketika sensor tidak disentuh.


https://user-images.githubusercontent.com/121847212/210311621-854f64c1-ca30-4b0b-a36e-ba662438bdcf.mp4


3.Buatlah program agar ketika sensor disentuh, LED menyala Blink.


https://user-images.githubusercontent.com/121847212/210311698-ed7b1ee3-76b2-46ef-8086-fdfccc74d425.mp4

4.Buatlah program agar ketika LED menyala, maka pada Serial Monitor akan menampilkan angka yang akan bertambah setiap kali sensor disentuh.


https://user-images.githubusercontent.com/121847212/210311868-2891dfc2-5831-4b20-9b81-2e4c153caeae.mp4


5.Tambahkan 2 LED sehingga pada rangkaian terdapat 3 LED. Buatlah program agar ketika sensor disentuh, LED menyala menjadi running LED. Nyala running LED tersebut adalah bergerak dari kiri ke kanan, kemudian kanan ke kiri secara kontinyu.


https://user-images.githubusercontent.com/121847212/210311964-6fc0cb11-7291-4acd-8a78-bdf1b266befc.mp4

B. Mengakses Sensor DHT 11 (Single Wire / BUS)
1. Buatlah program agar ketika suhu rungan mencapai 30 derajat celcius, maka ESP32 akan menyalakan LED Merah dan buzzer secara beep (blink). Apabila suhu dibawah 30 derajat, ESP32 akan mematikan buzzer dan menyalakan LED berbentuk running LED seperti pada Percobaan A. Kemudian dokumentasikan hasilnya.


https://user-images.githubusercontent.com/121847212/210312387-5618b1f2-adf6-418b-89b8-b28dbed1bd26.mp4

C. Mengakses Sensor RFID (SPI Communication)
1.
