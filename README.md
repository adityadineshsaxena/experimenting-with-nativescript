# NativeScript

Nativescript is a way to write native android/ios/windows apps in Javascript. This is my attempt to understand the framework and get better at using it.

# Genymotion Configuration - Android

1. Verify that you have installed Genymotion.
2. Verify that you have installed the AppBuilder command-line interface.
3. On Windows and Linux systems, verify that you have added the Genymotion installation directory to the PATH environment variable.
4. On OS X systems, verify that you have added the following paths to the PATH environment variable.
```
/Applications/Genymotion.app/Contents/MacOS/
/Applications/Genymotion Shell.app/Contents/MacOS/
```

5. Find out the devices in Genymotion by typing `genyshell -c "devices list"`

6. Find out the name of the device you want to run Genymotion on. `tns run android --emulator --geny <Name>`

That's it. The emulation is as easy as that.
