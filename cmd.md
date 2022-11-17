**# Turn off windows firewall**<br>
`netsh advfirewall set allprofiles state off`<br>
<br>
**# Shutdown and go to the BIOS**<br>
`shutdown /r /fw /f /t 0`<br>
<br>
**# Get information about the process with PID**<br>
`wmic process where "ProcessID=<pid>" get /format:list`<br>
<br>
**# List TCP connections with PIDs**<br>
`netstat -fon`<br>
**# Convert mkv to mp4 using ffmpeg**<br>
ffmpeg -i file.mkv -codec copy file.mp4
