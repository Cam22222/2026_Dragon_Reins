# 2026_Dragon_Reins
Repo for the Hackbots custom driver controller

### Dragon Reins (Driver) Specs
- TMR Joystick with single button x2
- Razer Mechanical Switches Green Clicky Switch Gen-3
- Rasberry Pi Pico 2

## Left Stick
| TMR Joystick Pin | Wire Color | Rasberry Pi Pico 2 Pin |
| ----------------- | --------------- | ----------------- |
| 1 | Black | GND |
| 2 | Red | VCC |
| 4 | Blue | A1 |
| 6 | Yellow | A0 |
| 9 | Orange | 6 |
| 10 | White | GND |

## Right Stick
| TMR Joystick Pin | Wire Color | Rasberry Pi Pico 2 Pin |
| ----------------- | --------------- | ----------------- |
| 1 | Black | GND  - Right | 
| 2 | Red | VCC |
| 4 | Blue | A3 |
| 6 | Yellow | A2 |
| 9 | Orange | 16 |
| 10 | White | GND - Left Bottom |

## Button Switches
| Button Pin | Wire Color | Rasberry Pi Pico 2 Pin |
| ----------- | ------ | ------- |
| GND Left-Bottom | Left and Right common | White |
| 5 | Left trigger | Green |
| 3 | Right trigger | Green |
