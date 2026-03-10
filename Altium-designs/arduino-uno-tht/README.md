# Arduino Uno THT Versiyonu

Bu proje, manuel montaj ve prototipleme süreçlerini kolaylaştırmak amacıyla tasarlanmış, Arduino Uno kartının through-hole (THT) bileşenlere sahip bir versiyonudur.

> **Not:** Bu kart, donanımsal bir kopya olarak tasarlanmıştır. Kart üzerinde kullanılan ATmega328P mikrodenetleyicisinin, harici bir Arduino kartı veya bootloader kullanılarak önceden programlanmış olması gerekmektedir. Bu karta doğrudan kod yüklemek mümkün değildir.

## Özellikler

- ATmega328P mikrodenetleyici (önceden programlanmış)
- Arduino Uno uyumlu pin dizilimi
- Kolay lehimleme için through-hole bileşenler
- USB - Seri haberleşme arayüzü
- 5V gerilim regülasyonu

## Tasarım Amaçları

- Mikrodenetleyici kart mimarisini öğrenmek
- PCB yönlendirme ve bileşen yerleşimi konusunda pratik yapmak
- Güç ve toprak hatlarının tasarım mantığını anlamak
- Through-hole tabanlı kart montajında uygulamalı beceri geliştirmek
- Kart üzerinde programlama özelliği bulunmayan, işlevsel bir Arduino uyumlu kart tasarlamak

## Kullanılan Araçlar

- Altium Designer
- ATmega328P veri sayfası
- Arduino Uno referans şematiği

## Görseller

![GPS veri okuma](PCB-Designs/Altium-designs/arduino-uno-tht/schematic-arduino-THT.jpeg)
![İlk Harita Goruntusu](images/ilk-harita-goruntusu.png)
![Yaris Pisti](images/yaris-pisti.png)
