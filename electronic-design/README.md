
TODO: Add images for electrical design in the sections below

TODO: Add all design data in the subfolders (Exxx)

TODO: Add editable lists

## E01 PCB

Schematic, PCB layout, 3D model, real photo

## E02 Wiring diagram

Schematic, real photo

## E03 Devices: sensors, actuators

Editable list: type, purpose/position, vendor link

## E04 Electrical components

Editable list: type, purpose/position, vendor link

## E05 Connectors

Editable list: type, purpose/position, vendor link

## E06 Cables

Editable list: type, length, purpose/position, vendor link



## E07 Wiring

Order list:
10. Brown wire, 1.5 mm2: Reichelt/H07VK 1,5-10BR
11. Blue wire, 1.5 mm2: Reichelt/H07VK 1,5-10BL
12. Green-yellow wire, 1.5 mm2: Reichelt/H07VK 1,5-10GG
13. Wire set, 0.25 mm2: Conrad/2201407
14. Cable 6 x 0.25 mm2: Conrad/486478
15. Cable 4 x 0.14 mm2: Reichelt/LIYCY 04-25
16. Compensation wire: Conrad/121329
17. Network cable: Conrad/2521890
18. Fan extenstion cable: Conrad/976188
19. Wire 0.34 mm2 set: Eckstein/SF11367

20. Blank ferrule, 1.5 mm2: Conrad/2870591
21. Receptable 4.75 mm: Reichelt/FSH-M1 4.75
22. Insulation sleeve (from set): Reichelt/QUAD 1908C181
23. Ring cable lug M6: Reichelt/RK-B-6
24. Ring cable lug M4: Reichelt/VT RK-B-4
25. Insulated ferrule set: Conrad/2870580
26. Heat shrink tube set: Conrad/2583933


| Part  | Name                   | Amount | Wire                        | Length      | Ends                                                 |
|-------|------------------------|--------|-----------------------------|-------------|------------------------------------------------------|
| E07S1 | SSR box/phase          | 2      | 10: brown, 1.5 mm2          | 75 mm       | 20: blank ferrule / 20: blank ferrule                |
| E07S2 | SSR box/neutral        | 1      | 11: blue, 1.5 mm2           | 200 mm      | 20: blank ferrule / 20: blank ferrule                |
| E07S3 | SSR box/ground         | 1      | 12: green-yellow, 1.5 mm2   | 150 mm      | 20: blank ferrule / 20: blank ferrule                |
| E07S4 | SSR box/supply/phase   | 1      | 10: brown, 1.5 mm2          | 250 mm      | 20: blank ferrule / 21: receptacle + 22: sleeve      |
| E07S5 | SSR box/supply/neutral | 1      | 11: blue, 1.5 mm2           | 250 mm      | 20: blank ferrule / 21: receptacle + 22: sleeve      |
| E07S6 | SSR box/supply/ground  | 1      | 12: green-yellow, 1.5 mm2   | 250 mm      | 20: blank ferrule / 23: cable lug                    |
| E07S7 | supply/ground/top      | 1      | 12: green-yellow, 1.5 mm2   | 250 mm      | 23: cable lug / 24: cable lug                        |
| E07S8 | supply/ground/back     | 1      | 12: green-yellow, 1.5 mm2   | 150 mm      | 23: cable lug / 21: receptacle + 22: sleeve          |
| E07S9 | SSR box/signal         | 1      | 13: brown+grey, 0.25 mm2    | 210 mm      | 25: isolated ferrule / 25: isolated ferrule          |
|-------|------------------------|--------|-----------------------------|-------------|------------------------------------------------------|
| E07M1 | Motors/inside          | 1      | 14: 6 x 0.25 mm2, no shield | 200 mm      | solder + 26: heat shrink tube / 25: isolated ferrule |
| E07M2 | Motors/outside         | 1      | 14: 6 x 0.25 mm2            | 800 mm      | solder / solder + 26: heat shrink tube               |
| E07P1 | PT/inside              | 1      | 15: 4 x 0.14 mm2, no shield | 280 mm      | solder + 26: heat shrink tube / 25: isolated ferrule |
| E07T1 | TC/inside              | 2      | 16: 2 x 0.14 mm2            | 300 mm      | none / 25: isolated ferrule                          |
| E07W1 | Weight/inside          | 1      | 15: 4 x 0.14 mm2, no shield | 300 mm      | solder + 26: heat shrink tube / 25: isolated ferrule |
| E07W2 | Weight/outside         | 1      | 15: 4 x 0.14 mm2            | 1100 mm     | solder / solder + 26: heat shrink tube               |
| E07B1 | Sensor box/inside      | 1      | 17: 8 x 0.14 mm2, no shield | 280 mm      | solder + 26: heat shrink tube / 25: isolated ferrule |
| E07B2 | Sensor box/outside     | 1      | 17: 8 x 0.14 mm2            | 900 mm      | none / 25: isolated ferrule                          |
| E07F1 | Fan/inside             | 1      | 18: 3 x 0.14 mm2            | 150 mm      | none / 25: isolated ferrule                          |
| E07Z1 | Zummer/inside          | 1      | 19: 2 x 0.34 mm2, solid     | 50 mm       | none / solder + 26: heat shrink tube                 |
| E07I2 | IR sensor/outside      | 1      | 19: 4 x 0.34 mm2, solid     | 100 mm      | none / solder + 26: heat shrink tube                 |
| E07L2 | LED/outside            | 1      | 19: 2 x 0.34 mm2, solid     | 400 mm      | none / solder + 26: heat shrink tube                 |
| E07R1 | RPi/5V                 | 1      | 19: 2 x 0.34 mm2, solid     | 45 mm       | none / none                                          |
| E07R2 | RPi/3.3V               | 1      | 19: 1 x 0.34 mm2, solid     | 30 mm       | none / none                                          |
