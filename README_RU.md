# Подключение внешнего радиомодуля СС1101 к Flipper Zero
Это поможет увеличить дальность приёма и передачи радиосигнала.

## Что понадобится для подключения?
- Внешний модуль СС1101 - 1 шт. Например, [такой](https://aliexpress.ru/item/1005002074380868.html), [такой](https://aliexpress.ru/item/32853385011.html) или [такой](https://aliexpress.ru/item/1005004166793032.html). Ссылки не проверены и приведены для примера.
- Провода мама-папа - 7 шт. Например, [вот эти](https://aliexpress.ru/item/32216818220.html).
- Установленная официальная прошивка или [Unleashed Firmware](https://github.com/DarkFlippers/unleashed-firmware)

## Как подключить внешний модуль?
Просто подключите ваш модуль проводами мама-папа как показано на рисунках.
Для переключения на внешний радиомодуль перейдите в `меню -> Sub-GHz -> Radio Settings` и выберите `Module -> External`

| Flipper Zero  | СС1101        |
| ------------- |:-------------:| 
| 2 | MOSI | 
| 3 | MISO | 
| 4 | CS | 
| 5 | SCK | 
| 6 | GD0 | 
| 9 | VCC | 
| 11 | GND | 

![cc1101 blue](https://user-images.githubusercontent.com/10090793/216795803-31a787c6-a19b-4368-8fcb-68438207683b.png)
![cc1101 green](https://user-images.githubusercontent.com/10090793/216795805-93b9b2ee-085f-4f46-858c-2efcdfff2e2a.png)
![cc1101 blue 8](https://user-images.githubusercontent.com/10090793/216795737-65926863-372f-437b-8269-5b20ffd60751.png)

## Что делать, если я не умею подключать радиомодули?
Купите готовый модуль!  
В Росссии, Казахстане, Беларуси, Армении, Грузии и СНГ: [Flipper Market](https://flipper.market)  
В Европе и всему миру: [Flipper Accessories Store](https://www.tindie.com/products/flipmodules/flipper-zero-external-cc1101-module/)  
В США: [Rabbit-Labs](https://www.tindie.com/stores/tehrabbitt/items/)  
![image](https://github.com/quen0n/flipperzero-ext-cc1101/assets/10090793/c4742bf7-41c2-46e2-b931-50648d50372b)  
