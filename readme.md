
Work
.\ddcset.exe --id  "LG QHD(DisplayPort)" setvcp 60 17
.\ddcset.exe --id  "Generic PnP Monitor" setvcp 60 15

Home
.\ddcset.exe --id  "LG QHD(DisplayPort)" setvcp 60 15
.\ddcset.exe --id  "Generic PnP Monitor" setvcp 60 11

LG
0x0f: DisplayPort 1 = Home 15
0x10: DisplayPort 2
0x11: HDMI 1       
0x12: HDMI 2        = Work 17

Dell
0x0f: DisplayPort 1 = Work 15
0x10: DisplayPort 2
0x11: HDMI 1        = Home 11
0x12: HDMI 2


WM_DEVICECHANGE ?