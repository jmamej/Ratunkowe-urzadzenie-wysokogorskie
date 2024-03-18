# Ratunkowe urządzenie wysokogórskie
### Alpine Rescue Device

## V0.1

### Główne komponenty

- ESP32
- GPS NEO-6M
- Pololu AltIMU-10 v5
- DS18B20
- LED RGB


### Zasada działania

Urządzenie wysyłające dane o lokalizacji (GPS) oraz wysokości n.p.m. (AltIMU) poprzez wbudowany moduł Wi-Fi (ESP32) na platformę IoT (ThingSpeak), celem ich przechowania/ wyświetlania.
Urządzenie posiada możliwość wysyłania sygnału SOS na platformę ThingSpeak manualnie poprzez wybranie odpowiedniego programu z menu lub automatycznie - nagły spadek wysokości, turbulętny odczyt z żyroskopu.

<br/>

ARD version 0.1 - 3D render |  ARD version 0.1
:--------------------------:|:--------------------------:
<img width="450" src="https://github.com/jmamej/Ratunkowe-urz-dzenie-wysokog-rskie/assets/57408600/aac01761-9426-45da-ab41-1c46455caa40.png">  |  <img width="450" src="https://github.com/jmamej/Ratunkowe-urz-dzenie-wysokog-rskie/assets/57408600/0e0b083e-8297-46c1-be6e-4844c771a8f9.png">


<img width="600" src="https://github.com/jmamej/Ratunkowe-urz-dzenie-wysokog-rskie/assets/57408600/7d8a5d90-2a50-45e2-9384-a9c3c813a3b5.png">

*schemat PCB*


![ARD_IOT](https://github.com/jmamej/Ratunkowe-urz-dzenie-wysokog-rskie/assets/57408600/2a2d6b4a-b51b-4a3d-9a2b-0c6b8e665243)

*wizualizacja danych wysłanych na platformę IoT ThingSpeak*

<br/>
<br/>

## V0.2

### Główne komponenty

- ESP32
- AD8232 EKG
- Przewody i elektrody EKG
- DS18B20
- OLED SSD1306
- Karta microSD
- PWM 2 x MOS AOD41


### Zasada działania
Rozszerzenie wersji 0.1 o moduł EKG, czujnik temperatury ciała, kartę SD (czarna skrzynka), wyświetlacz OLED.  Rozszerzenia pozwalają śledzić stan fizyczny wspinacza i informować w przypadku przekroczenia wartości nominalnych pulsu/ temperatury.

<br/>

ARD version 0.2 - 3D render |  ARD version 0.2
:--------------------------:|:--------------------------:
<img width="450" src="https://github.com/jmamej/Ratunkowe-urz-dzenie-wysokog-rskie/assets/57408600/feb80d2a-b7dc-4294-aef6-2ab4bdd0df96.png">  |  <img width="450" src="https://github.com/jmamej/Ratunkowe-urz-dzenie-wysokog-rskie/assets/57408600/dde83962-862b-4606-8c86-739afba8ce28.png">


ARD components and case |  ARD components front |  ARD components back
:--------------------------:|:--------------------------:|:--------------------------:
<img width="500" src="https://github.com/jmamej/Ratunkowe-urzadzenie-wysokogorskie/assets/57408600/938b12c9-3bfc-486e-af26-5c398a597669.png"> | <img width="500" src="https://github.com/jmamej/Ratunkowe-urzadzenie-wysokogorskie/assets/57408600/a6366867-2f3a-4c6e-b171-6d181ad5846e.png"> | <img width="400" src="https://github.com/jmamej/Ratunkowe-urzadzenie-wysokogorskie/assets/57408600/4d410275-cbc0-450f-b790-f4c50bbe25fa.png">


AD8232 Heart Rate Monitor   |  ECG lead wires   |  ECG electrodes
:--------------------------:|:--------------------------:|:--------------------------:
<img width="200" src="https://github.com/jmamej/Ratunkowe-urz-dzenie-wysokog-rskie/assets/57408600/b1ebc765-ba28-4305-ac09-71a3e7f7cb0b.png">  |  <img width="400" src="https://github.com/jmamej/Ratunkowe-urz-dzenie-wysokog-rskie/assets/57408600/61ccc786-7f68-4b6b-b23e-9417dedf9efa.png"> | <img width="250" src="https://github.com/jmamej/Ratunkowe-urz-dzenie-wysokog-rskie/assets/57408600/2eced98b-e6c9-4039-9739-93e0251b2370.png">


![Master PCB_pcb_2](https://github.com/jmamej/Ratunkowe-urzadzenie-wysokogorskie/assets/57408600/9c0fc78f-ef99-4217-9e3e-d382d3b75bae)

*schemat PCB*

![image](https://github.com/jmamej/Ratunkowe-urzadzenie-wysokogorskie/assets/57408600/dd6b5397-05a5-4a34-8438-bd315ffb2cd6)

*wizualizacja odczytów modułu EKG*


<img width="500" src="https://github.com/jmamej/Ratunkowe-urzadzenie-wysokogorskie/assets/57408600/8e3b6bc5-b7a9-4d92-9385-6479f7b96a48.png">

*ARD i elektrody EKG*


|   main menu   |   displayed: altitude   |   displayed: battery level   |   menu heating   |
|---------|---------|---------|---------|
<img width="500" src="https://github.com/jmamej/Ratunkowe-urzadzenie-wysokogorskie/assets/57408600/c21abf43-5479-470d-a244-05eec15b422d.png"> | <img width="500" src="https://github.com/jmamej/Ratunkowe-urzadzenie-wysokogorskie/assets/57408600/43e2afec-e93d-43ed-bcdb-a04a67090e1c.png"> | <img width="500" src="https://github.com/jmamej/Ratunkowe-urzadzenie-wysokogorskie/assets/57408600/4dbb09eb-e5c2-4a76-913e-67f356c5acf0.png"> | <img width="500" src="https://github.com/jmamej/Ratunkowe-urzadzenie-wysokogorskie/assets/57408600/944a1311-36f1-4f09-b951-aaa669076298.png"> |


