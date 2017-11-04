# mobi_udev

udev rule creator for mobi_robot. 
## Creating udev rule
1. Run the udev creator:
```
$ rosrun mobi_udev mobi_udev.py
```

2. Copy the created udev rule to /etc/udev/rules.d/58-mobi.rules:
```
$ sudo cp 58-mobi.rules /etc/udev/rules.d/58-mobi.rules
```
