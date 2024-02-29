# Microcontroller Selection


|                                  | PIC Option 1 | PIC Option 2 | PIC Option 3 |
|----------------------------------|--------------|--------------|--------------|
| Part Number                      | PIC18F14Q40  | PIC16F18855  | PIC24FJ32GP202 |
| Production Unit Cost             | $1.23        | $1.56        | $1.29        |
| Supply Voltage Range             | 1.8V-5.5V    | 1.8V-5.5V    | 2.0V-3.6V    |
| Absolute Maximum Current for entire IC | 350mA  | 250 mA       | 150 mA       |
| Maximum GPIO Pin Current (Source/Sink) | +/- 50mA | +/- 50 mA | +/-18 mA |
| 8-bit or 16-bit Architecture    | 8-bit        | 8-bit        | 16-bit       |
| Available IC Packages / Footprints | 20-Pin PDIP, 20-Pin SOIC, 20-Pin SSOP | 28-pin (S)PDIP, SOIC, SSOP, QFN (6x6), UQFN(4x4) | 28-Pin QFN, UQFN 28-Pin SOIC, SSOP, 36-Pin UQFN, 48-Pin UQFN, TQFP |
| Supports External Interrupts?   | Yes          | Yes          | Yes          |
| In-System Programming Capability and Type | No     | Yes, Serial | Yes, Serial |
| Works with MPLAB® X Integrated Development Environment (IDE)? | Yes | Yes | Yes |
| Works with Microchip Code Configurator? | Yes | Yes (?) | Yes |


|                           | PIC Option 1 | PIC Option 2 | PIC Option 3 |
|---------------------------|--------------|--------------|--------------|
| How many GPIO Pins?       | 6+           | 18           | 25           |
| Built-in ADC? How many?   | 1+           | 1            | 24           |
| Built-in Hardware PWM?    | 1+           | 3            | 2            |
| Built-in I2C? SPI? How many? | 1+SPI, 1+I2C | 2 SPI, 1 I2C | 2 SPI, 2 I2C |
| Built-in UART? How many?  | 2+UART       | 3 USART      | 0 UART, 1 USART (?) |

#### Overall Pros

1. PIC Option 1: 3UART, Multiple PWMs
2. PIC Option 2: Multiple ADCs, 2 SPI and 2 I2C, 2 PWM, A lot of options for pins
3. PIC Option 3: Multiple ADCs, 2 SPI and 2 I2C, 5 PWM, A lot of options for pins

#### Overall Cons

1. PIC Option 1: Few ADCs, Less I2C
2. PIC Option 2: More pins to solder, Expensive dev board, A lot of options for pins
3. PIC Option 3: More pins to solder, Expensive dev board, A lot of options for pins

#### Ranking

1. PIC Option 3
2. PIC Option 1
3. PIC Option 2

### Final Microcontroller Choice: PIC24FJ32GP202
