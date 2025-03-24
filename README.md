# RespringApp
Simple app that just resprings the device on app launch for stock iOS 16.0-18.3(.1?)

This is basically an modified PosterBoard.app with an different bundle id and the "LSLaunchDLabel" in the info.plist set to com.apple.SpringBoard, also removed some flags that caused the app be be hidden on the homescreen.

Treat this as a cool PoC. doesn't really have much use on stock iOS.

Known Issue:
- long respring times on my iPhone 12 on iOS 18.3, not sure why but your milage may vary.
