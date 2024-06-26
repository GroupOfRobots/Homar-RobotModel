# Bionik-TwitchGo-RobotModel

## About
This repository contains 3D models of the robot used in the TwitchGo project.

## File organization
The file organization has recently been changed. Currently on branch main there are three folders: step, stl and sldprt. Each contains files with the proper extention.
Step and sldprt folders both contain a subfolder called "Non-print models" with models of the motors, servo, bearing, ballcasters etc. In sldprt, this folder also contains an assembly of all parts (except wheels for now).
All three folders also contain a 'tests' subfolder which is intended for smaller prototype models that are not a finished part of the robot.

## Screws you will need
All holes are designed to accept screws and standoffs with the diameter of 3 mm. However, the head and length differs depending on the parts that need to be joined. To be specific, you will need:
- **For the roof**: 4 × 12 mm <ins>cone head</ins> bolts
- **For the circut board**: 4 × male-female hexagonal standoffs with 13 mm body length and 5 mm screw length <ins>and</ins> 4 × 6 mm normal head bolts
- **To attach the main bracing to the ServoHolder element**: 5 × 12 mm normal head bolts
- **For the bumper**: 4 × 12 mm normal head bolts
- **For the scoop**: 4 × 16 mm <ins>cone head</ins> bolts

### Summary
Tables below present all screws you will need:
| Number | Length | Cone head bolt? |
| :----: | :----: |      :---:      |
| 4      | 6      | No              |
| 9      | 12     | No              |
| 4      | 12     | Yes             |
| 4      | 16     | Yes             |

### Nuts
All aforementioned bolts (+ 4 for the battery and 4 for motors) will need nuts. This means 29 nuts in total. 17 of them will need to be implanted manually in the structure during the printing process.

Nuts to be implanted in MainBraicing:
![Alt text](<Zrzut ekranu 2023-11-25 130904.png>)

Nuts to be implanted in ServoHolder:
![Alt text](<Zrzut ekranu 2023-11-25 131046.png>)

## Assembly overview
The finished robot should look like this:
![Alt text](<Zrzut ekranu 2023-11-25 164746.png>)
![Alt text](<Zrzut ekranu 2023-11-25 164702.png>)
and lego wheels used in previous versions which are for now not included i the assembly.