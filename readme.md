[中文说明](readme_CN.md)

Inspired by [V0-Adafruit-Y_Rails](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/QuackProfit/V0-Adafruit-Y_Rails)

Printing
Default voron settings
No supports needed

### Picture
![图片](Picture/IMG_6871.jpg)
![图片](Picture/IMG_6873.jpg)
![图片](Picture/Bom.png)
### [Video](3D/V0_NeoPixel_SticksB.avi)

### BOM
|NO.	|Category	|Part Name	|Qty	|Remark
|--|--|--|--|--|
|1	|Electronics	|[NeoPixel Stick](https://item.taobao.com/item.htm?spm=a1z09.2.0.0.7ca02e8djWSvge&id=623844944291&_u=dkh2792dc2)	|X1	|59*10.5mm
|2	|Fasteners|M3x6BHCS		|X6	|
|3	|Fasteners|M3 Nut		|X6	|
|4	|Fasteners|20awg		|1.5m	|

## Config
Inspired by SB led
#### Copy below config to your <Printer.cfg>，you must need to check the “pin:” in "neopixel_leds.cfg"
```ini
[include neopixel_leds.cfg]
## LEDs Config
```
