# sht11-proteus

example of humidity control in proteus

## requirements

1. proteus 
2. arduino ide

## components required

1. arduino uno
2. SHT10 (temprature humidity sensor)
3. LM016L (16X2 lcd screen)
4. 10WATT1K ( 1 kohm register )
5. DC motor
6. L293D (motor driver)

# circuit connection

## SHT 10 (temprature humidity sensor)

1. skt -> pin 8
2. data -> pin 7

## LM016L (16X2 lcd screen)

1. VSS -> GND
2. VDD -> 5v
3. VEE -> 1k register -> 5V (VDD wire)
4. RS -> pin 12
5. RW -> GND (VSS wire)
6. E -> pin 11
7. D4 -> pin 5
8. D5 -> pin 4
9. D6 -> pin 3
10. D7 -> pin 2

## L293D (motor driver)

1. vs -> external power source
2. vss -> external power source
3. EN -> VSS (VSS wire)
4. IN1 -> pin 10
5. IN2 -> pin 6
6. OUT1 -> MOTOR
7. OUT2 -> MOTOR
8. GND -> external ground
9. GND -> external ground

# thats it!, I hope you will get success :)
