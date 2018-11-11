# Rubber-Ducky_Disable_W10-Defender_Technician-Edition
A quickly script for Rubber Ducky to disable w10 defender on large scale

![Alt text](https://raw.githubusercontent.com/JonnyBanana/Rubber-Ducky_Disable_W10-Defender_Technician-Edition/master/img/main_win10.png "SnapChat_Leak_2018-by-Jonny-Banana")

In my activities as a technician I have to format many computers during the month, and as many refuse to buy the license I have to use a lot of crack (although I do not recommend every time, but the money they pull at the time ...).
Since the windows 10 defenses are slightly improved compared to the previous ones (even if it is still punctured like a colander ...), I had the need to write a quick rubber ducky script that would disable Windows Defender on windows 10 platforms (the more installed system in our time).
I have also added an additional script that reports UAC and windows defender to the recommended settings.
The Scripts are two: Killer and Healer, the first disables and the second of course rehabilitates everything.

<h2>Killer</h2>

DELAY 2000</BR>
REM  first disable UAC</BR>
CONTROL ESCAPE</BR>
DELAY 200</BR>
STRING uac </BR>
DELAY 200</BR>
ENTER</BR>
DELAY 200</BR>
DOWNARROW</BR>
DELAY 200</BR>
DOWNARROW</BR>
DELAY 200</BR>
DOWNARROW</BR>
DELAY 200</BR>
TAB</BR>
DELAY 200</BR>
ENTER</BR>
DELAY 200</BR>
LEFT</BR>
DELAY 200</BR>
ENTER</BR>
DELAY 200</BR>
REM it's time to disable the fuckin' defender....</BR>
CONTROL ESCAPE</BR>
DELAY 200</BR>
STRING virus pro</BR>
DELAY 200</BR>
ENTER</BR>
DELAY 200</BR>
TAB</BR>
DELAY 200</BR>
TAB</BR>
DELAY 200</BR>
TAB</BR>
DELAY 200</BR>
TAB</BR>
DELAY 200</BR>
ENTER</BR>
DELAY 200</BR>
SPACE</BR>
DELAY 200</BR>
TAB</BR>
DELAY 200</BR>
SPACE</BR>
DELAY 200</BR>
TAB</BR>
DELAY 200</BR>
TAB</BR>
DELAY 200</BR>
SPACE</BR>

<h2>Healer</h2>

DELAY 2000</BR>
REM first enable the fuckin' defender....</BR>
CONTROL ESCAPE</BR>
DELAY 200</BR>
STRING virus pro</BR>
DELAY 200</BR>
ENTER</BR>
DELAY 200</BR>
TAB</BR>
DELAY 200</BR>
TAB</BR>
DELAY 200</BR>
TAB</BR>
DELAY 200</BR>
ENTER</BR>
DELAY 200</BR>
SPACE</BR>
DELAY 200</BR>
TAB</BR>
DELAY 200</BR>
TAB</BR>
DELAY 200</BR>
SPACE</BR>
DELAY 200</BR>
TAB</BR>
DELAY 200</BR>
TAB</BR>
DELAY 200</BR>
TAB</BR>
DELAY 200</BR>
SPACE</BR>
DELAY 200</BR>
REM alt f4 close the window</BR>
ALT F4</BR>
REM it's time to enable UAC</BR>
CONTROL ESCAPE</BR>
DELAY 200</BR>
STRING uac </BR>
DELAY 200</BR>
ENTER</BR>
DELAY 200</BR>
TAB</BR>
DELAY 200</BR>
UPARROW</BR>
DELAY 200</BR>
UPARROW</BR>
DELAY 200</BR>
TAB</BR>
DELAY 200</BR>
ENTER</BR>

