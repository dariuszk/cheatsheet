## reboot 
`shutdown /r /f /t 0 `


## NETWORK

### IP 
`ipconfig /all | findstr IPv4 `  - all ip addresses 

### MAC
`mac /v`

## processes

### Kill 

* by name `taskkill /f /im "editor.exe` 
* by pid  `first tasklist | findstr proces_name`  `taskkill /f /pid 1234`

