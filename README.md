# Bionik-TwitchGo-RobotModel

## About
This repository contains 3D models of the robot used in the TwitchGo project.

## File organization
The file organization has recently been changed. Currently on branch main there are three folders: step, stl and sldprt. Each contains files with the proper extention.
Step and sldprt folders both contain a subfolder called "Non-print models" with models of the motors, servo, bearing, ballcasters etc. In sldprt, this folder also contains an assembly of all parts (except wheels for now).

## Screws you will need
All holes are designed to accept screws and standoffs with the diameter of 3 mm. However, the head and length differs depending on the parts that need to be joined. To be specific, you will need:
- **For the roof**: 4 &#215 12 mm normal head bolts
- **For the circut board**: 4 &#215 male-female hexagonal standoffs with 13 mm body length and 5 mm screw length <u>and</u> 4 &#215 6 mm normal head bolts
- **To attach the main bracing to the ServoHolder element**: 5 &#215 12 mm normal head bolts
- **For the bumper**: 4 &#215 12 mm normal head bolts
- **For the scoop**: 4 &#215 16 mm <u>cone head</u> bolts

### Summary
Tables below present all screws you will need:
| Number | Length |
| :----: | :----: |
| 4      | 6      |
| 13     | 12     |
| 4      | 16     |

### Nuts
All aforementioned bolts (+ 4 for the battery and 4 for motors) will need nuts. This means 33 nuts in total. 17 of them will need to be implanted manually in the structure during the printing process.

Nuts to be implanted in MainBraicing:
![Alt text](<Zrzut ekranu 2023-11-25 130904.png>)

Nuts to be implanted in ServoHolder:
![Alt text](<Zrzut ekranu 2023-11-25 131046.png>)

## Assembly overview
The finished robot should look like this:
![Alt text](<Zrzut ekranu 2023-11-25 130742.png>)
![Alt text](<Zrzut ekranu 2023-11-25 130710.png>)
+ lego wheels used in previous versions.