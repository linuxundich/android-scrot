android-scrot
=============

Take screenshot from your android phone by adb

# Syntax

android-scrot will save a screenshot of your phone to the current directory

```
$ android-scrot
android_12-02-2014_11-17-43.png saved
$ android-scrot your-app
your-app_12-02-2014_11-18-04.png saved
```

# Dependencies

To get the screenshots from your phone you need to install adb from the android sdk. In Ubuntu you'll get that command by the android-tools-adb package, other distributions should ship similar packages. Optional is imagemagick to rotate the screenshot according to the orientation of the phone
