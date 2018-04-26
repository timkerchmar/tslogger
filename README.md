# TSLogger

See standard output on Windows and Android. Tested on Windows, Android, OSX, iOS.
 
## Usage

Include TSLogger.h and call this method as early as possible:

```
TSRedirectStandardOutput();
```

printf/cout will now appear in your logcat or in a console window on Windows.

## TODO

Windows could use OutputDebugString and Visual Studio. I had performance issues with heavy logging until I switched to using a console window.