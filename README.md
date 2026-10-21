# Fibonacci\_Clock\_by\_SimLED

Fibonacci Clock DIY ESP32 Project

Verwendung & Voraussetzungen (Usage & Requirements)
Damit die Flutter-App und die Web-Oberfläche einwandfrei mit der Fibonacci-Uhr funktionieren, sind folgende Voraussetzungen zu beachten:

Firmware-Voraussetzung:

Neue Uhren / Ersteinrichtung: Auf dem ESP32 muss die aktuelle Firmware FibonacciClock_SimLED_FINAL_V1_1_1.bin geflasht werden.

Bestehende Uhren: Es muss zwingend das aktuelle OTA-Update über die Web-Oberfläche eingespielt werden: OTA-Update_FibonacciClock_SimLED_FINAL_V1_1_1.bin. Nur mit dieser Version ist die vollständige API- und Sprachsynchronisation (DE, EN, TR, ES, AR) gewährleistet.

Steuerung nach Betriebssystem:

Android: Du kannst entweder die beigelegte APK-Datei (FibonacciClock-v1.0.apk) installieren (hierfür muss auf dem Smartphone einmalig „Installation aus unbekannten Quellen zulassen“ aktiviert werden) oder alternativ die Web-UI im Browser nutzen.

iOS (iPhone/iPad): Da es für iOS keine APK gibt, erfolgt die Steuerung und Konfiguration hier ganz komfortabel direkt über die Web-UI der Uhr im Safari-Browser (über [http://fibonacci-clock.local](http://fibonacci-clock.local) oder die IP-Adresse).