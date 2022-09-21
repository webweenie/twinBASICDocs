# Click Event #
## Input Parameters ##
None
## Return value ##
None
## Description ##
The Click event is fired when the user "clicks" on the object. A click can be registered by clicking with the mouse button, or by selecting the object and pressing the enter key.

---

# GotFocus Event #
## Input Parameters ##
None
## Return value ##
None
## Description ##
The GotFocus event fires when the object receives the focus. The object can get focus by being clicked with the mouse, or by the user tabbing into the object. 
When an object has focus, it will receive input from the keyboard.

---

# Initialize Event #
## Input Parameters ##
None
## Return value ##
None
## Description ##
The initialize event fires when the object is initialized during the form load. This event can be used to populate the object with data or
otherwise prepare it for the user.

---

# KeyDown Event #
## Input Parameters ##
- **KeyCode**: the ASCII value of the key pressed.
- **Shift**: the bitwise value representing all of the shifting keys pressed.
## Return value ##
None
## Description ##
The KeyDown event is the first of the key events to fire and occurs when the key is pressed down. The KeyDown event passes in the KeyCode and the Shift state. The KeyCode represents the ASCII value of the key that was pressed. The Shift parameter represents which of the three "shift" keys were also pressed. The possible values of Shift are: 1 = Shift Key, 2 = CTRL key, and 4 = ALT key. Bitwise logic can be used to determine if more than one key was being pressed. The code below can be used to determine which shifting keys are pressed:
```vb
    Private Sub Object1_KeyDown(KeyCode As Integer, Shift As Integer) Handles Object1.KeyDown
        Dim bShift As Boolean = 1 And Shift
        Dim bAlt As Boolean = 2 And Shift
        Dim bCtrl As Boolean = 4 And Shift
        
        'Add logic here that uses the boolean values to suit your needs.
    End Sub
```

---

# KeyPress Event #
## Input Parameters ##
- **KeyASCII**: Integer - the ASCII value of the key pressed.
## Return value ##
None
## Description ##
The KeyPress event is similar to the KeyDown, but it happens after the KeyDown event. The event passes in the ASCII value of the key pressed via the KeyASCII property. Setting this property to 0 (zero) within the keypress event will nullify the keypress and, effectively, ignore it. 

---

# KeyUp Event #
## Input Parameters ##
- **KeyCode**: Integer - the ASCII value of the key pressed.
- **Shift**: Integer - the bitwise value representing all of the shifting keys pressed.
## Return value ##
None
## Description ##
The KeyUp event is the final key event to trigger and occurs when the user releases the key.

---

# LostFocus Event #
## Input Parameters ##
None
## Return value ##
None
## Description ##
The LostFocus event fires when the object loses focus. This can happen when the user clicks on another object with the mouse, or presses the tab key and moves the focus to the next object.

---

# MouseDown Event #
## Input Parameters ##
- **Button**: Integer - the ASCII value of the key pressed.
- **Shift**: Integer - the bitwise value representing all of the shifting keys pressed.
- **X**: Integer - the number of pixels the mouse is from the left edge of the object's container
- **Y**: Integer - the number of pixels the mouse is from the top edge of the object's container
## Return value ##
None
## Description ##
The MouseDown event fires when the mouse button is pressed while over the object.

---

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

---

# MouseUp Event #
## Input Parameters ##
- **Button**: Integer - the ASCII value of the key pressed.
- **Shift**: Integer - the bitwise value representing all of the shifting keys pressed.
- **X**: Integer - the number of pixels the mouse is from the left edge of the object's container
- **Y**: Integer - the number of pixels the mouse is from the top edge of the object's container
## Return value ##
None
## Description ##
The MouseUp event fires when the mouse button is released and the mouse is over the object.

---

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

---

# MouseUp Event #
## Input Parameters ##
- **Button**: Integer - the ASCII value of the key pressed.
- **Shift**: Integer - the bitwise value representing all of the shifting keys pressed.
- **X**: Integer - the number of pixels the mouse is from the left edge of the object's container
- **Y**: Integer - the number of pixels the mouse is from the top edge of the object's container
## Return value ##
None
## Description ##
The MouseUp event fires when the mouse button is released and the mouse is over the object.