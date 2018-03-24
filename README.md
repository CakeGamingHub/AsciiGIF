# AsciiGif : Library used to create text-based gif-lites

# How to Use:

# Creating an AsciiGif

For the following example, an AsciiGif with name Gif, frame rate 10 fps, and frames being ':)' and ';)' shall be created
```python
from asciigif import *
Gif = AsciiGif([":)", ";)"], 10)
```

# Drawing an AsciiGif

This example assumes an AsciiGif called Gif has already been created, and the Gif shall be drawn for 25 iterations.
```
Gif.Draw(25)
```

# Full Function List

`SetClearCommand(ClearCommand)`
Sets the command used to clear the screen before drawing a frame to the screen.
By default, set to `"os.system('cls')"`

`Draw(Iterations)`
Draws the Gif to the screen

`DrawLogic()`
Internal function, draws a single iteration of a Gif, equivalent to `Draw(1)`