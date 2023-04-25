# CFAP104212Dx-0154 Demonstration Code

This is Arduino sample code for the CFAP104212Dx-0154 family of displays. These displays are 1-bit flexible ePapers and operate on both 3 and 4 Wire SPI. For quick and easy interfacing with the display, the [CFA10084 ePaper Adapter Board](https://www.crystalfontz.com/product/cfa10084-epaper-adapter-board) is recommended.

## Connection Guide
```
//  ARD      | Port  | Adapter pin |  Function - SPI                          |
//-----------+-------+-------------+------------------------------------------+
// 3.3V      |       |  01         |  POWER 3.3V                              |
// GND       |       |  02         |  GROUND                                  |
//-----------+-------+-------------+------------------------------------------+
// D3        | PORTD |  08         |  Busy                            (BSY)   |
// D4        | PORTD |  07         |  Reset                           (RST)   |
// D5        | PORTD |  06         |  Data/Command                    (DC)    |
// D10       | PORTB |  05         |  Chip Select                     (CS)    |
// D11       | PORTB |  04         |  Master Out Slave In             (MOSI)  |
// D13       | PORTB |  03         |  Serial Clock                    (SCK)   |
//-----------+-------+-------------+------------------------------------------+
```

## Display Information
Here are links to our active displays:\
[CFAP104212D1-0213](https://www.crystalfontz.com/product/cfap104212d10213-104x212-flexible-epaper-epd-display)

For more inforamtion about other ePaper offerings, please see our full list [here](https://www.crystalfontz.com/c/epaper-displays/519).