# Connecting an external radio module СС1101 to Flipper Zero
This will help to increase the range of reception and transmission of the radio signal.

## What is needed to connect?
- External module CC1101 - 1 pc. Like [this](https://aliexpress.ru/item/1005002074380868.html), [this](https://aliexpress.ru/item/32853385011.html) or [this](https://aliexpress.ru/item/1005004166793032.html)
- Wires male-female - 7 pcs. For example, [like this](https://aliexpress.ru/item/32216818220.html).
- Installed [Unleashed Firmware](https://github.com/DarkFlippers/unleashed-firmware)

## How to connect an external module?
Just connect your module with female and male wires as shown in the pictures.
To switch to an external radio module, go to `menu -> Sub-GHz -> Radio Settings` and switch `Module` to `External`

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
