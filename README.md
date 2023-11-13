# pycolors
This repository provides ANSI color codes for styling text in the terminal. The color codes can be used to change text color, background color, and apply additional styles such as bold, underline, and blinking.

### Example Usage

```python
from pycolors import *

print(BB + "This is blue text with bold" + W)
print(BG_G + "This is text with a green background" + W)
print(UNDERLINE + "This text is underlined" + W)
