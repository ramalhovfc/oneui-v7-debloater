# One UI 7.x system debloater
This is a debloating script for Samsung devices using One UI 7.x.
It doesn't uninstall apps but disables them so if you find any feature missing you can revert it by using

```bash
  adb shell pm enable <package-name>
```

Use at your own risk

## Windows
Double click the bat file

## Ubuntu
Install [Android Debug Bridge (adb)](https://developer.android.com/studio/command-line/adb):

```bash
  sudo apt install adb
```

Rename *oneui-debloater.cmd* to *oneui-debloater.sh* and run it:

```bash
  bash './oneui-debloater.sh'
```