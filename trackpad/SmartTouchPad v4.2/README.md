# SmartTouchPad v4.2

## Usage
Using the modified trackpad `Info.plist`

1. Extract the kext from the ZIP file.
2. Copy `ApplePS2SmartTouchPad_Info.plist` into `ApplePS2SmartTouchPad.kext/Contents/`.
3. Backup the old `Info.plist` by renaming it to `Info.bak.plist`.
4. Rename `ApplePS2SmartTouchPad_Info.plist` to `Info.plist`

Using the modified keyboard `Info.plist`

1. Extract the kext from the ZIP file.
2. Copy `ApplePS2Keyboard_Info.plist` into `ApplePS2SmartTouchPad.kext/Contents/PlugIns/ApplePS2Keyboard.kext/Contents/`.
3. Backup the old `Info.plist` by renaming it to `Info.bak.plist`.
4. Rename `ApplePS2Keyboard_Info.plist` to `Info.plist`

## Modifications
### ApplePS2SmartTouchPad
#### Swiping
Use 3 finger up/down swipes for Mission Control (4)
```
<key>3FingerSwipeDownAction</key>
<integer>4</integer>
<key>3FingerSwipeUpAction</key>
<integer>4</integer>
```
Use 4 finger up/down swipes for Mission Control (4)
```
<key>4FingerSwipeDownAction</key>
<integer>4</integer>
<key>4FingerSwipeUpAction</key>
<integer>4</integer>
```
Use 4 finger left/right swipes for space switching (6/7)
```
<key>4FingerSwipeLeftAction</key>
<integer>6</integer>
<key>4FingerSwipeRightAction</key>
<integer>7</integer>
```
### ApplePS2Keyboard
Switch Fn key mapping
```
<key>Fn keys Layout</key>
<string>ACER</string>
```

## References
### OS X Gesture Action Values
Taken from the [original thread](http://forum.osxlatitude.com/index.php?/topic/5966-details-about-the-smart-touchpad-driver-features/)
```
0 - To disable the gesture
1 - Applications Switch
2 - App close
3 - Launchpad
4 - Mission control
5 - Dashboard
6 - Left Space/Full Screen apps switch
7 - Right Space/Full Screen apps switch
8 - Application windows
9 - Minimize app
10 - Toggle Full screen Switch
11 - Backward 
12 - Forward 
13 - Desktop
14 - Notification center (keyboard shortcut)
15 - Show Properties/Info
16 - Hide/Show Dock
17 - Notification center (soft mode)
18 - Zoom reset (works in Photos, Browser etc., where it supports)
19 - Finder
20 - Force Quit
21 - Right click
22 - Middle click
23 - 34 as F13 - F24
```
