# Click Event #
## Input Parameters ##
- **KeyASCII**: Integer - the ASCII value of the key pressed.
## Return value ##
None
## Description ##
The KeyPress event is similar to the KeyDown, but it happens after the KeyDown event. The event passes in the ASCII value of the key pressed via the KeyASCII property. Setting this property to 0 (zero) within the keypress event will nullify the keypress and, effectively, ignore it. 
