# Windows Command Shell


## Get running processes
https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/tasklist
```bat
rem Filter processes by name
tasklist /s HOST_NAME /fi "IMAGENAME eq PROCESS_NAME.exe"
```


## Terminate process
https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/taskkill
```bat
rem By process ID (PID)
taskkill /s HOST_NAME /pid 9999
rem By image name
taskkill /s HOST_NAME /im PROCESS_NAME.exe
```
