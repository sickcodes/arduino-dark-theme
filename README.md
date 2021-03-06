# Arduino Dark Theme (Black)

Arduino Dark Mode - A very dark theme for the Arduino IDE on Windows, Linux, and macOS.

Download: [https://github.com/sickcodes/arduino-dark-theme](https://github.com/sickcodes/arduino-dark-theme)

![Arduino Dark Mode Black Theme](/arduino-dark-theme-black.png)

> This project is a direct fork of [@konrad91](https://github.com/konrad91)'s [https://github.com/konrad91/OneDarkArduino/](https://github.com/konrad91/OneDarkArduino/)

> Inspired by One Dark Pro for VSCode by binaryify: https://binaryify.github.io/OneDark-Pro/#/. Based on work done by Jeff Thompson: https://create.arduino.cc/projecthub/rahulkhanna/dark-theme-for-arduino-ide-17c001?ref=search&ref_id=theme&offset=0


The following is credited to https://github.com/jeffThompson/DarkArduinoTheme 

### INSTALLATION  

* Mac users should look in `~/Applications/Arduino.app/Contents/Java/lib` and replace the `theme` folder inside (making a copy of the original in case want to revert back).  
* Windows is located in `C:\Program Files (x86)\Arduino\lib`.  
* Linux will be in `/usr/share/arduino/lib/`

### LINUX INSTALLATION

This moves your old `theme` to `theme.bak`

```bash
# install
sudo bash ./linux-install.sh

# uninstall
sudo bash ./linux-uninstall.sh
```

### MACOS INSTALLATION

This moves your old `theme` to `theme.bak`

```bash
# install
sudo bash ./mac-install.sh

# uninstall
sudo bash ./mac-uninstall.sh
```

### DARK ICONS

![Arduino Dark Mode Black Theme About Logo](/bitmaps/about@2x.png)

![Arduino Dark Mode Black Theme Icon](/bitmaps/arduino.png)

# Linux
`sudo cp ./bitmaps/* /usr/share/arduino/lib/`

# Mac
`sudo cp ./bitmaps/* ~/Applications/Arduino.app/Contents/Java/lib/`

### CREATING YOUR OWN MODS
The newest version of the Arduino IDE makes creating custom themes trickier: you now need to edit the `theme.txt` file, an XML file inside the `syntax` folder, and the button files. Unfortunately, not all items in the `theme.txt` file actually work, so if you can't get an item to change, try another one of the files.

\- \- \-

Released under [Creative Commons BY-NC-SA license](http://creativecommons.org/licenses/by-nc-sa/3.0/) - feel free to use but [please let me know](http://www.jeffreythompson.org).
