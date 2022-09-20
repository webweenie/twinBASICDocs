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
