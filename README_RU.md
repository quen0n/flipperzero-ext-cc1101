# Подключение внешнего радиомодуля СС1101 к Flipper Zero
Это поможет увеличить дальность приёма и передачи радиосигнала.

## Что понадобится для подключения?
- Внешний модуль СС1101 - 1 шт. Например, [такой](https://aliexpress.ru/item/1005002074380868.html), [такой](https://aliexpress.ru/item/32853385011.html) или [такой](https://aliexpress.ru/item/1005004166793032.html). Ссылки не проверены и приведены для примера.
- Провода мама-папа - 7 шт. Например, [вот эти](https://aliexpress.ru/item/32216818220.html).
- Установленная прошивка [Unleashed Firmware](https://github.com/DarkFlippers/unleashed-firmware)

## Как подключить внешний модуль?
Просто подключите ваш модуль проводами мама-папа как показано на рисунках.


| Flipper Zero  | СС1101        |
| ------------- |:-------------:| 
| 2 | MOSI | 
| 3 | MISO | 
| 4 | CS | 
| 5 | SCK | 
| 6 | GD0 | 
| 9 | VCC | 
| 11 | GND | 

![cc1101 blue](https://user-images.githubusercontent.com/10090793/216717733-8b48daef-86a9-4fe4-bd9a-96350c835e3f.png)
![cc1101 green](https://user-images.githubusercontent.com/10090793/216717931-77b1c72a-8bd6-481e-acf1-243eaf63ffb7.png)
![cc1101 blue 8](https://user-images.githubusercontent.com/10090793/216718023-d1e4aef2-6626-4ad2-b9b9-afedd2c5255a.png)

