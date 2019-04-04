# sht11-proteus

example of humidity control in proteus

## components required

1. arduino uno
2. SHT10 (temprature humidity sensor)
3. LM016L (16X2 lcd screen)
4. 10WATT1K ( 1 kohm register )

# circuit connection

## SHT 10 (temprature humidity sensor)

skt -> pin 8
data -> pin 7

## LM016L (16X2 lcd screen)

VSS -> GND
VDD -> 5v
VEE -> 1k register -> 5V (VDD wire)
RS -> pin 12
RW -> GND (VSS wire)
E -> pin 11
D4 -> pin 5
D5 -> pin 4
D6 -> pin 3
D7 -> pin 2
