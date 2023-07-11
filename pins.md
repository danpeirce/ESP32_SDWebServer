# ESP32-S2 to microSD Breakout Board Wiring

| Pin breakout | microSD | SPI  | BREAKOUT BOARD CN0023 | Description (for breakout)                                                                  | ESP32-S2 | PIN ESP32-S2 |
|--------------|---------|------|-----------------------|---------------------------------------------------------------------------------------------|----------|--------------|
| 1            | DAT2    | X    |                       | Suggested 50K pullup on unused input                                                        |          |              |
| 2            | CD/DAT3 | CS   | CS                    |                                                                                             | SS       | 34           |
| 3            | CMD     | DI   | DI                    |                                                                                             | MOSI     | 35           |
| 4            | VDD     | VDD  | VDD                   | 3.3 VDC                                                                                     | VDD      | 3V3          |
| 5            | CLK     | SCLK | SCLK                  |                                                                                             | SCK      | 36           |
| 6            | VSS     | VSS  | VSS                   | GROUND                                                                                      | VSS      | G            |
| 7            | DAT0    | D0   | D0                    |                                                                                             | MOSO     | 37           |
| 8            | DAT1    | X    |                       | Suggested 50K pullup on unused input                                                        |          |              |
| 9            |         |      | /SW                   | Switch that indicates a card is inserted. Connects to SW_GND when card inserted. Not using. |          |              |
| 10           |         |      | SW_GND                | Connect to system ground                                                                    |          |              |