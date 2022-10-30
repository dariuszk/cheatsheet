## NETWORK

### IP addres v4 for all interfaces 
* v4 : `ip addr | grep "inet "`
* v6 : `ip addr | grep "inet6 "`


### vnc

* Problem with capslock on client but not on host 
 `python -c 'from ctypes import *; X11 = cdll.LoadLibrary("libX11.so.6"); display = X11.XOpenDisplay(None); X11.XkbLockModifiers(display, c_uint(0x0100), c_uint(2), c_uint(0)); X11.XCloseDisplay(display)'`  
