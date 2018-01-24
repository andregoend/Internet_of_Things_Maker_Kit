# [ENGLISH] Project 3: Proximity Indicator
Measuring distance can be done through a lot of methods. One of the most common method to be used is using the reflection of light. In this project you will learn how to use phototransistor to detect an object and get the rough estimation of object's distance. The system in this project will detect the presence of an object. If the object is getting closer, LED will blink faster. On the contrary, if the object is getting further, LED will blink slower.



### In this project you will need:
* ESP8266 (1),
* I/O Expansion Shield (1),
* LED Module (1),
* Buzzer Module (1),
* IR Sensor (1).

### Assemble the modules following these steps:
1. Plug the I/O Expansion Shield to the top of ESP8266,
2. Plug the LED Module to the header on the I/O Expansion Shield labelled **7**,
3. Plug the Buzzer Module to the header on the I/O Expansion Shield labelled **5**,
4. Plug the IR Sensor to the header on the I/O Expansion Shield labelled **ADC**,
5. Upload the [Proximity_Indicator](/03_Proximity_Indicator/Proximity_Indicator) code into ESP8266.

Once you turn on the ESP8266, it will enter calibration mode for about 3 seconds. Cover the IR Sensor with the desired object which will be tracked to determine the highest brightness, and uncover the IR Sensor to determine the lowest brightness.
If there are no mistakes, LED Module should blink faster as the object gets near. On the contrary, LED Module should blink slower as the objects gets further.

# [BAHASA INDONESIA] Proyek 3: Proximity Indicator
Pengukuran jarak dapat dilakukan dengan banyak cara, dimana salah satu metode yang digunakan adalah memanfaatkan sifat pantulan cahaya. Proyek ini bertujuan untuk mendemonstrasikan penggunaan sensor cahaya, yaitu phototransistor dengan ESP8266. Sistem pada proyek ini akan mendeteksi keberadaan dari suatu obyek. Apabila obyek semakin mendekat maka LED akan berkedip semakin cepat. Sebaliknya, apabila obyek semakin menjauh, maka kedipan LED akan semakin lambat.



### Modul-modul yang dibutuhkan pada proyek ini:
* ESP8266 (1),
* I/O Expansion Shield (1),
* LED Module (1),
* Buzzer Module (1),
* IR Sensor (1).

### Hubungkan modul-modul di atas mengikuti langkah-langkah di bawah ini:
1. Pasang I/O Expansion Shield di atas ESP8266,
2. Hubungkan LED Module ke header I/O Expansion Shield yang berlabel **7**,
3. Hubungkan Buzzer Module ke header I/O Expansion Shield yang berlabel **5**,
4. Hubungkan IR Sensor ke header I/O Expansion Shield yang berlabel **ADC**,
5. Upload kode program [Proximity_Indicator](/03_Proximity_Indicator/Proximity_Indicator) ke ESP8266.

Pada saat ESP8266 dinyalakan, ESP8266 akan memasuki proses kalibrasi selama kurang lebih 3 detik. Tutupi IR Sensor dengan obyek yang hendak dideteksi untuk mendapatkan nilai kecerahan tertinggi, dan hilangkan halangan dari IR Sensor untuk mendapatkan nilai kecerahan terendah.
Apabila tidak terdapat kesalahan, maka LED Module akan berkedip semakin cepat saat obyek yang dideteksi semakin mendekat. Sebaliknya, LED Module akan berkedip semakin lambat saat obyek yang dideteksi semakin menjauh.
