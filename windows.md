## POWER MANAGEMENT
* reboot force `shutdown /r /f /t 0 `


## NETWORK

### IP 
* show all IPv4 addresses `ipconfig /all | findstr IPv4 `  

### MAC
* Show mac addresses on network interfaces  `mac /v`

### Control
* turn off windows firewall `netsh advfirewall set allprofiles state off`

## processes

### Kill 

* by name `taskkill /f /im "editor.exe`, can be used `*` eg. `taskkill /f /im "*staff*.exe`
* by pid  first `tasklist | findstr proces_name` then  `taskkill /f /pid 1234`

