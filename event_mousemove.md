# MouseMove Event #
## Input Parameters ##
- **Button**: Integer - the ASCII value of the key pressed.
- **Shift**: Integer - the bitwise value representing all of the shifting keys pressed.
- **X**: Integer - the number of pixels the mouse is from the left edge of the object's container
- **Y**: Integer - the number of pixels the mouse is from the top edge of the object's container
## Return value ##
None
## Description ##
The MouseMove event fires when the mouse is moved over the object. The MouseMove event has several parameters that provide useful information to the event. The Button parameter is an integer value that represents which button was pressed. The possible values are 1 = Left button, 2 = Right button, and 4 = Center button. See the KeyDown event for information on using bitwise boolean logic to determine which buttons were pressed. The Shift parameter works the same way for the MouseMove as it does for the KeyPress. Again, see the KeyPress event for help determining which shifting keys are being pressed. The X and Y parameters provide the location of the mouse as it moves.
