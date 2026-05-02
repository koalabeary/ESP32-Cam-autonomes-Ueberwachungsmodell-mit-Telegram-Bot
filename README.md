# ESP32-Cam-autonomes-Ueberwachungsmodell-mit-Telegram-Bot
Dieser Code ist für ein ESP32-Cam Modell gedacht, den ich mit einem Infrarot Bewegungssensor ausgestattet habe, damit bei jeder registrierten Erkennung eines Menschen des Sensors die Kamera des ESP32 auslöst und dem User das Bild per Telegram ChatBot schickt.
Ich habe bei Arduino IDE das AI Thinker ESP32 Cam Modell ausgewählt, das Grundgerüst des Codes, also die Kommunikation zwischen dem ESP32 und dem Telegram Bot habe ich aus diesem Tutorial : 
https://randomnerdtutorials.com/telegram-esp32-cam-photo-arduino/#more-98951

erweitert habe ich das Tutorial mit dem PIR Sensor und verschiedenen Betriebsmodi, wie "/silent" , "/alarmed" , was bedeutet, dass bei einer Erkennung eines Menschen entweder ein Alarmton ertönt oder das System stumm die Bilder an den User weiterleitet. Die Kommentare auf deutsch habe ich abgeändert oder eingefügt. 
