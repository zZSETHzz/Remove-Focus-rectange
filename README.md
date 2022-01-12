# Remove-Focus-rectange
Remove the focus rectangle from the desktop

Custom .dll file to remove the focus rectangle (as seen here: shorturl.at/yJKZ6) from the windows desktop.


Install instructions:

Copy .dll file to "C:\Windows\SysWOW64"
Open Administrator CMD or Terminal
Navigate to the required folder using the command 'cd C:\Windows\SysWOW64'
Run the command 'regsvr32 RemoveFR.dll'
Restart computer

To uninstall:

Open Administrator CMD or Terminal
Navigate to the required folder using the command 'cd C:\Windows\SysWOW64'
Run the command 'regsvr32 /u RemoveFR.dll
Restart computer.
