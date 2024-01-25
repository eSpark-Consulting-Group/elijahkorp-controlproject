# Project Description
This project will hold progress and development of the Control Project

## Project Requirements
### Schematic Design
1. 12 hour clock (HH:MM AM/PM). Real time clock (RTC) with battery backup.
2. 5V PCB operating power with MicroUSB connection to power the board
3. 2 relays (1 for pump, 1 for lights) both rated for 120V 10A.
4. 5 buttons (mounted on enclosure not pcb) (LCD indicator button; 3 white; 2 red)
    - Button "+" (white led on while setting times)
    - Button "-" (white led on while setting times)
    - Set button (white led on while setting times)
    - Override Lights button (red led on while override is on)
    - Override Pump button (red led on while override is on)
5. 16x2 lcd screen with flexible cable ribbon. Mounted on enclosure not PCB. Client is open to options but the LCD should be suitable for the enclosure.
6. Arduino compatible controller
7. Hard wire connection for pump/lights to relay (screw terminals)
8. 120V Power input receptacle for relays (IEC-A-3)

### PCB Design
1. Design should be done for the PCB considering the enclosure details shared below
2. Dimensions Height < 1.3inches, width < 2.75 inches, length<6.25

#### Important Links
* [Enclosure Link]([url](https://www.mcmaster.com/7301K13/)https://www.mcmaster.com/7301K13/)
* [LCD 16 x 2]([url](https://focuslcds.com/product/16x2-stn-character-lcd-c162exbsyly6wt)https://focuslcds.com/product/16x2-stn-character-lcd-c162exbsyly6wt)
* [Push Button Latching Red]([url](https://www.sparkfun.com/products/11971)https://www.sparkfun.com/products/11971)
* [Push Button Latching White]([url](https://www.sparkfun.com/products/11975)https://www.sparkfun.com/products/11975)
* [IEC-A-3]([url](https://www.digikey.com/en/products/detail/adam-tech/IEC-A-3/9832397)https://www.digikey.com/en/products/detail/adam-tech/IEC-A-3/9832397)
* [AC-C13]([url](https://eu.mouser.com/ProductDetail/CUI-Devices/AC-C13-NA?qs=WyjlAZoYn53BZzqbWMmk0A%3D%3D)https://eu.mouser.com/ProductDetail/CUI-Devices/AC-C13-NA?qs=WyjlAZoYn53BZzqbWMmk0A%3D%3D)

## Unit Testing v1.0
### Number of Assmebled Board received: 2 Boards
### Number of Bare Boards received: Nil
### Details of peripherals received:  
- White LED Button: Qty 6  
- Red LED Button: Qty 3
- AC Power Socket: Qty 2
- Coin Cell CR2032: Qty 5
- Network Cable: Qty 3
- LCD Module: Qty 2  

| S.No       | Status (working / faulty) | Remarks (Cause of fault) | Location (PK / Client) | Board Images (front / back / peripherals) |
| ----------- | ----------- |-------------| --- | --- |
| 1      | Working |  | PK | [Board Images](https://drive.google.com/drive/folders/1tmLhA86AJ5KZKhvcY31eBResxszXIj_W?usp=sharing) |
