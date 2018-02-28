adb tcpip 5555

adb shell netcfg

adb connect 10.32.33.109:5555

adb devices

➜  wechat_jump_game git:(master) ✗ adb tcpip 5555

➜  wechat_jump_game git:(master) ✗ adb shell netcfg
wlan0    UP     10.4.5.166/22  0x00001043

➜  wechat_jump_game git:(master) ✗ adb connect 10.4.5.166:5555
connected to 10.4.5.166:5555

➜  wechat_jump_game git:(master) ✗ adb devices
List of devices attached
10.4.5.166:5555	unauthorized
Y2J5T17410000179	device
