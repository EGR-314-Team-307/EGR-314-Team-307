# Component Selection

## Motor
FIT0492-B


$11.90

![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/156955314/6c857586-6925-407b-90ce-849e6142946f)

| Pros                                           | Cons                                             |
|------------------------------------------------|--------------------------------------------------|
| Datasheet     | More expensive than alternative options      |
| High Torque                   |  |
| 12V           |                    |
| Decent Supply from Digikey        |                            |
| High quality and performance         


Rationale:
This motor was selected primarily for its higher torque output. It is one of the more expensive options and requires a separate 12V power rail, however, the torque was of higher priority.

## Motor Driver
IFX9201SGAUMA1


$4.00

![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/156955314/b26c9aee-ac05-4806-9a77-5eb1991cbf39)

| Pros                                           | Cons                                             |
|------------------------------------------------|--------------------------------------------------|
| Higher current output of 6A per channel     | More expensive than alternative options      |
| Optimal temperature range                   |  |
| Includes Datasheet           |                    |
| Higher Supply Voltage        |                            |

Rationale:
This motor driver was selected for its compatibility with the chosen motor. It is also more expensive than other options found, but the compatibility was of greater importance.

## Switching Voltage Regulator
LM25085QMYX/NOPB

$2.38

![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/156955314/d99d0ba9-f987-4c8d-868b-a6baa99783b1)


| Pros                                           | Cons                                             |
|------------------------------------------------|--------------------------------------------------|
| Includes Datasheet     | Support circuitry required      |
| Adjustable output voltage                   | Multiple resistors, capacitors, and inductors |
|  Typical application circuit to follow         |                    |
| Supply voltage between 4.5V and 42V        |                            |

Rationale:
This voltage regulator was selected due to the supporting circuitry for a typical application being relatively simpler than the other options. Adjusting the circuitry to output 3.3V also appeared straightforward, with multiple equations provided and all of the components required available as surface mount options.

## Light Sensor
SENSOR OPT AMBIENT 4CHIPLED


$1.20

![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/156955314/06b560dd-659e-45a5-ab1b-9158c3f684cf)

| Pros                                           | Cons                                             |
|------------------------------------------------|--------------------------------------------------|
| 2.4V-3.6V    | Weight not included     |
| Inexpensive                   |  |
| Wide Temperature Range        |                    |
| Includes Datasheet       |                            |

Rationale: 
This sensor was selected due to its smaller number of pins for an easier soldering experience, the communication via I2C, and the wide operating temperature range. It was also less expensive than other options.

## Heat Sensor
ZTP-148SRC1


$1.97

![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/156955314/4029b698-6089-4951-9b92-ad0cbe879ca1)

| Pros                                           | Cons                                             |
|------------------------------------------------|--------------------------------------------------|
| Cost Effective     | 4 pin output      |
| Includes Datasheet                  | Non surface mount |
| Analog Output          |                    |
| Working Temperature -20°C ~ 100°C        |                            |
| Long distance         

Rationale:
This heat sensor was selected for its range of operating temperatures and ability to detect changes in heat at longer distances. This would assist in getting a better direction when detecting a fire.

## Battery
EN22


$2.61

![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/156955314/70c055f0-398e-4db0-9058-c90d0bd07800)

| Pros                                           | Cons                                             |
|------------------------------------------------|--------------------------------------------------|
| Includes Datasheet    | Non rechargeable     |
| 9V                   |  |
| Inexpensive        |                    |

Rationale:
This battery was selected with the input voltage requirements for the voltage regulator in mind. It can provide an appropriate voltage level for the regulator to step down to 3.3V.
