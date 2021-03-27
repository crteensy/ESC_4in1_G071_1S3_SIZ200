# ESC_4in1_G071_1S3_SIZ200

## UNTESTED
The G071+NCP81161 combo was successfully tested (with PSMN1R8-30MLHX though).

## Important: mounting
The PCB is quite crowded around the mounting holes:
- Do not use M3 metal hardware.
- You can use M3 plastic with slim (5mm outer diameter) standoffs
- You can also use M2 with rubber grommets

## Description
KiCad project for a 20mm 4in1 ESC
- 4 layers for prototyping
- no part smaller than 0402
- 1-3 S
- should be abe to handle 15 A continuous
- STM32G071
- NCP81161 gate drivers
- SIZ200
- 0m5 current sense shunt with INA186A2
- 5V reg: TPS630701; max 2A (VBat = 5 V)

![3D view top](https://github.com/crteensy/ESC_4in1_G071_1S3_SIZ200/blob/main/ESC_4in1_G071_1S3_SIZ200_3dview.png)

![3D view bottom](https://github.com/crteensy/ESC_4in1_G071_1S3_SIZ200/blob/main/ESC_4in1_G071_1S3_SIZ200_3dview_bot.png)
