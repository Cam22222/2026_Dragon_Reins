# 2026_Dragon_Reins
Repo for the Hackbots custom driver controller

### Dragon Reins (Driver) Specs
- TMR Joystick with single button x2
- Razer Mechanical Switches Green Clicky Switch Gen-3
- Rasberry Pi Pico 2


## Left Stick
| TMR Joystick Pin | Wire Color | Rasberry Pi Pico 2 Pin |
| ----------------- | --------------- | ----------------- |
| 1 | Black | GND - Left Under GP9 |
| 2 | Blue | OUT |
| 3 | Red | VCC |
| 4 | Red | VCC |
| 5 | Blue | OUT |
| 6 | Black | GND - Left Under GP13|

## Right Stick
| TMR Joystick Pin | Wire Color | Rasberry Pi Pico 2 Pin |
| ----------------- | --------------- | ----------------- |
| 1 | Black | GND - Right Under GP22 | 
| 2 | Blue | OUT |
| 3 | Red | VCC |
| 4 | Red | VCC |
| 5 | Blue | OUT |
| 6 | Black | GND - Right Under GP18|

## Button Switches
| Button Pin | Wire Color | Rasberry Pi Pico 2 Pin |
| ----------- | ------ | ------- |
| GND Left-Bottom | Left and Right common | White |
| 5 | Left trigger | Green |
| 3 | Right trigger | Green |
