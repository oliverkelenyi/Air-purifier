# Air-purifier
This is a DIY air purifier. It purifies the air with 2 HEPA and activated carbon combined filters and with the power of 2 x 120 mm fans. I made this because I don't want to die from 3D printing odors.

After you make it, you just have to plug in the built-in USB or a USB-C cable and turn on the power button, and it will work!

1. What you have to do is: 3D print the main structure from PLA and the other smaller parts from TPU95A.
2. Buy these:

## Bill of materials

| Reference | Qty | Value | Footprint | Manufacturer | MPN | LCSC Part | Unit Price (HUF) | Unit Price ($) | Total Price (HUF) | Total Price ($) | Supplier Link |
| --- | ---: | --- | --- | --- | --- | --- | ---: | ---: | ---: | ---: | --- |
| Air filter | 2 | Filters | ELIZ EF 100 | ELIZ | ELICV022 | — | 1 720 | 5.42 | 3 440 | 10.84 | https://www.alza.hu/eliz-ef100-d5468641.htm?evt=ac&pos=1&ste=com&sqid=Algolia_eb58aee0dc5128bff6cf9fa |
| Voltage regulator | 1 | 12 V fixed voltage regulator, 78H12A | TO-3 | HESTORE Hungary Kft | 100.364.87 | — | — | — | — | — | https://www.hestore.hu/prod_10036487.html |
| Diode | 2 | Diode | 1N5408 | HESTORE Hungary Kft | 100.000.53 | C36138 | 61.40 | 0.19 | 155.96 | 0.36 | https://www.hestore.hu/prod_10000053.html |
| Switch | 1 | Switch | KCD11-2P | HESTORE Hungary Kft | 100.479.80 | C5884412 | 140 | 0.44 | 177.8 | 0.56 | https://www.hestore.hu/prod_10047980.html |
| USB-C | 1 | USB-C power cable | PWR-USB-C-BK | HESTORE Hungary Kft | 100.475.72 | — | 272 | 0.86 | 345.44 | 1.09 | https://www.hestore.hu/prod_10047572.html |
| Limiter | 1 | 100nF 50V ceramic capacitor | Y5V, 5 mm | HESTORE Hungary Kft | 10026066 | — | 11 | 0.04 | 11 | 0.04 | https://www.hestore.hu/prod_10026066.html |
| 120mm fan | 2 | Fan | 120mm PC fan | used is enough, price can change | used is enough, price can change | used is enough, price can change | used is enough, price can change | used is enough, price can change | used is enough, price can change | used is enough, price can change | — |
| USB cable | 1 | USB cable | USB cable | used is enough, price can change | used is enough, price can change | used is enough, price can change | used is enough, price can change | used is enough, price can change | used is enough, price can change | used is enough, price can change | — |

<img width="1468" height="566" alt="Képernyőkép 2026-09-14 172557" src="https://github.com/user-attachments/assets/a07965e3-04b2-4582-aa54-b1043e13196c" />

3. The holes on the side from top to bottom: 1.swich, 2.USB-C, 3.USB cable. Follow the assembly as shown in the linked video. (For HC reviewer: I didn't get the money yet to buy the components to make the video.)

<img width="994" height="864" alt="Képernyőkép 2026-09-10 224122" src="https://github.com/user-attachments/assets/84df1f8d-7436-4301-ba31-241c76cc85b6" />

Schematic:

<img width="1125" height="761" alt="Képernyőkép 2026-09-15 152926" src="https://github.com/user-attachments/assets/6542af1f-475f-4bce-9f6c-137bb539fa3d" />

The voltage regulator is a 78H12A fixed 12 V regulator. Connect it according to the datasheet and provide suitable heat dissipation. Make sure the input voltage is high enough for the regulator to maintain a stable 12 V output.

The assembled 3D model (white: PLA, black: TPU95A):

<img width="741" height="836" alt="Képernyőkép 2026-09-14 211439" src="https://github.com/user-attachments/assets/c48c9610-96fd-4194-a5b9-965c20b32097" />
