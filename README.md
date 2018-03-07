# XTouchDownRecorder
X-Plane 10/11 aircraft landing touch down flight recorder

it is used for aircraft landing data analysis

it supports Windows, Mac, Linux x64 only

## Blog on Mar 2018 ##

after almost six months working on X-Plane 11  with different aircraft, I realize that X-Plane dataref output G force value and Fpm value is appliabe only to in-flight, not for touching down. then I decide to re-calucate Fpm value by my own, and skip G force value in the next release.


## feature ##

* touch ground times
* landing fpm, pitch, G force
* max fpm,pitch, G force around landing
* landing log will be automatically written to log file TouchDownRecorderLog.txt
* automatically pop up after landing
* button/key assignment

## maintain website ##

https://forums.x-plane.org/index.php?/files/file/39630-touchdownrecorder/

## Joystick button/key assignment ##

assign button/key to cpuwolf/XTouchDownRecorder/Toggle TouchDownRecorder Chart

![TouchDownRecorder](TouchDownRecorder_cmd.jpg)

![TouchDownRecorder](TouchDownRecorder_xp10_command.jpg)

## Screenshot on X-Plane 11 ##

![TouchDownRecorder](TouchDownRecorder.jpg)
![TouchDownRecorder](TouchDownRecorder_replay.jpg)

## Screenshot on X-Plane 10 ##

![TouchDownRecorder](TouchDownRecorder_xp10.jpg)
![TouchDownRecorder](TouchDownRecorder_xp10_menu.jpg)

## How to Look into it ##

![TouchDownRecorder](TouchDownRecorder_manual.jpg)

## Thanks to leecbaker ##

this project starts with

https://github.com/leecbaker/xplane_sdk
