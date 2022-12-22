# Job-1-Embedded-System
Job 1 embedded system Dasar Pemrograman ESP32 untuk pemrosesan data input/output analog dan digital, 

Langkah Percobaan :

Instalasi Board ESP32 pada Arduino IDE

1. Buka Arduino IDE
2. Kemudian klik Menu File > Preferences
3. Pada kolom Additional ... yang ada dibawah, tambahkan link berikut
https://dl.espressif.com/dl/package_esp32_index.json
4. Klik menu Tools > Board: > Pilih Boards Manager ...
5. Pada kolom pencarian tulis ESP32 kemudian install dan tunggu sampai 
selesai.


**Percobaan a. GPIO**

Langkah Kerja :


Percobaan GPIO memiliki bentuk rangkaian sebagai berikut,

<img width="329" alt="gambar rangkaian GPIO" src="https://user-images.githubusercontent.com/121012286/208860130-da0b50c6-96f8-49ac-b55c-dc2267a953ec.png">

2. Buka program example blink, kemudian modifikasi dan buat agar LED dapat 
melakukan blink dengan interval 100ms, 1 detik, 2 detik dan 3 detik sekali. 
Setelah itu, buatlah program agar LED dapat blink 1 detik sekali 
menggunakan timer milis(). Dokumentasikan hasilnya.

3. Buatlah program seperti pada script di bawah ini untuk mengendalikan led 
menggunakan push button. Kemudian upload program tersebut pada ESP32
dan dokumentasikan hasilnya.

4. Tambahkan 1 LED dan 1 push button pada rangkaian, kemudian kembangkan 
program agar ketika push button ke-2 ditekan, LED akan melakukan blink 
setiap 500 ms sekali. Kemudian dokumentasikan hasilnya.

5. Tambahkan 3 LED dan 1 push button pada rangkaian, kemudian kembangkan 
program agar ketuka push button ke-3 ditekan, LED akan menyala menjadi 
running led (menyala bergantian dari kiri ke kanan). 


https://user-images.githubusercontent.com/121012286/208829230-064dfae6-e5a4-4ec6-8c55-43c83e729ba3.mp4


Ada 3 percobaan untuk GPIO yaitu menambah 1 LED dan 1 push button pada rangkaian, kemudian kembangkan 
program agar ketika push button ke-2 ditekan, LED akan melakukan blink 
setiap 500 ms sekali

Kemudian, Tambahkan 3 LED dan 1 push button pada rangkaian, kemudian kembangkan 
program agar ketuka push button ke-3 ditekan, LED akan menyala menjadi 
running led (menyala bergantian dari kiri ke kanan). 

HASIL PERCOBAAN

Percobaan 1


https://user-images.githubusercontent.com/121012286/208830086-4f464fb1-7957-4e57-a8ce-88728faf0c14.mp4


Dapat dilihat hasil dari percobaan di atas yaitu lampu LED pertama dapat menyala dengan blink 1 detik sekali

Percobaan 2


https://user-images.githubusercontent.com/121012286/208830150-3226351d-cb03-4c68-b0ac-314b29d4164b.mp4


Pada percobaan di atas, hasilnya yaitu lampu led dapat menyala dengan blink 500ms sekali

Percobaan 3 


https://user-images.githubusercontent.com/121012286/208830190-47a64d0d-d5e4-420c-9b70-3a2ff6eca53c.mp4


Pada percobaan di atas hasilnya yaitu ketiga lampu LED menyala secara berurutan (running) dari kiri ke kanan


**Percobaan b.PWM**

Langkah Kerja :

Buatlah script (sudah terlampir pada file) lalu diunggah dan amati hasilnya


Percobaan PWM memiliki rangkaian sebagai berikut,

<img width="368" alt="RAngkaian PWM" src="https://user-images.githubusercontent.com/121012286/208860370-d518d685-1e27-4fc9-9b88-fe533c6d613a.png">



Percobaan 1 

Pada percobaan PWM terdapat 3 LED, dan percobaan pertama dapat dilihat hasil dari percobaan ini adalah hanya 
1 LED yang menyala dari ketiga LED 

https://user-images.githubusercontent.com/121012286/208831901-34a8d5e1-6ca2-4792-9579-9ba3aebfe3cd.mp4


Percobaan 2

Pada percobaan kedua PWM terdapat 3 LED dan hasil dari percobaan kedua adalah ketiga lampu tersebut
menyala secara bersamaan dan looping.



https://user-images.githubusercontent.com/121012286/208832819-d0973037-fa9d-4f7b-ac26-b576aa18b4e6.mp4



**Percobaan c. ADC dan DAC**

Langkah Kerja :
1. Buatlah program seperti pada script berikut ini (sudah terlampir pada file)

2.Putar potensiometer secara perlahan agar mendapatkan nilai 0 hingga 4095 
pada tampilan serial monitor. Analisis apa yang terjadi dan dokumentasikan 
hasilnya.

3. Buatlah program seperti pada script berikut ini.Tambahkan LED pada GPIO 

4.Upload program, kemudian putar potensiometer dari nilai terendah hingga 
nilai tertinggi. Amati yang terjadi, analisis dan dokumentasikan hasilnya.

Percobaan ADC dan DAC memiliki rangkaian sebagai berikut,

<img width="416" alt="Rangkaian ADC DAC" src="https://user-images.githubusercontent.com/121012286/208860480-efdc27ac-3e8e-49dc-bbd8-a4959c084236.png">


Percobaan Pertama



https://user-images.githubusercontent.com/121012286/208833988-c52867d0-b8f9-4197-bd0d-e927b9159ea5.mp4


Pada percobaan di atas rangkaian tidak menggunakan lampu LED dan hanya menggunakan potensio, hasil dari percobaan di atas adalah
apabila kita memutar potensio ke kanan maka resistansi potensio akan meningkat dan hasil yang terpampang pada serial monitor
akan menunjukkan semakin tinggi angkanya.

Percobaan Kedua


https://user-images.githubusercontent.com/121012286/208833290-6b28b2e4-5fb7-4209-a19b-2291ad3dc8c1.mp4

Pada percobaan di atas menggunakan potensio dan sebuah lampu LED, hasil dari percobaan akan muncul pada serial monitor
Apabila diputar ke kanan resistansi potensio akan semakin besar dan semakin tinggi daya potensio maka lampu akan semakin redup.

