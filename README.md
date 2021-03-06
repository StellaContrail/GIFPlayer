<div align="center"><img alt="GIFPlayer logo: Frames with Play button" src="images/icon.ico"></div>

# GIFPlayer

A GIF player that allows for **FAST** frame-by-frame playback, built-in C#.
It provides intuitive graphical UI to allow users to easily manipulate.
Multiple features are available; autoplay, frame-by-frame adjustment, save a frame as a file, seek bar, real-time frame state, and more.

<div align="center"><img alt="screenshot" src="images/sample.png"></div>

## Animated Demo
<div align="center"><img alt="screenshot" src="images/animation.gif"></div>

## Downloading
### On Windows

The latest release of the GIFPlayer binary is located only in GitHub.
```.NET Framework 4.6.1``` is required to launch the program.

### On other platforms

GIFPlayer is **not currently supported on other platforms**, as the fundamental features mainly rely on the .NET Framework.
However, it is possible to implement with .NET Core, which has compatibility with other platforms like Linux, and Mac.
Pull requests are more than welcome.

## Keybindings

| Key              | Action                                         |
| ---------------- | ---------------------------------------------- |
| Ctrl+S           | Save the present frame as a single image file  |
| Ctrl+Space       | Play / Pause                                   |
| Ctrl+Right arrow | Next frame                                     |
| Ctrl+Left arrow  | Previous frame                                 |
| Ctrl+Up arrow    | Speed up the playback rate by x2, x4, x8...    |
| Ctrl+Down arrow  | Speed down the playback rate by x0.5, x0.25... |

## Future updates
* Associate file extension

## Dependencies
* .NET Framework
* MetroFramework
