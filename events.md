# twinBASIC Docs - Events #
Event procedures are special subroutines that objects call automatically when a pre-defined action occurs. 

---

## <a id="afterlabeledit"></a>AfterLabelEdit ##
> ### Input Parameters ###
> 
>
> .
>

## <a id="beforecollapse"></a>BeforeCollapse ##
> ### Input Parameters ###
> 
>
> .
>

## <a id="beforeexpand"></a>BeforeExpand ##
> ### Input Parameters ###
> 
>
> .
>

## <a id="beforelabeledit"></a>BeforeLabelEdit ##
> ### Input Parameters ###
> 
>
> .
>

## <a id="change"></a>Change ##
> ### Input Parameters ###
> None
>
> .
>

## <a id="click"></a>Click ##
> ### Input Parameters ###
> None
>
> The Click event is raised when the object is clicked with the mouse or, in some instances, when the object has focus and the Enter key is pressed.
>

## <a id="collapse"></a>Collapse ##
> ### Input Parameters ###
> 
>
> .
>

## <a id="dblclick"></a>DblClick ##
> ### Input Parameters ###
> None
>
> The DblClick event is raised when the object is double-clicked with the mouse.
>

## <a id="dropdown"></a>DropDown ##
> ### Input Parameters ###
> None
>
> .
>

## <a id="expand"></a>Expand ##
> ### Input Parameters ###
> 
>
> .
>

## <a id="gotfocus"></a>GotFocus ##
> ### Input Parameters ###
> None
>
> The GotFocus event is raised when the object receives the focus. The object can get focus when it is clicked with the mouse, or by the user tabbing into the object. When an object has focus, it will receive input from the keyboard.
>

## <a id="initialize"></a>Initialize ##
> ### Input Parameters ###
> None
>
> The initialize event is raised when the object is initialized during the form load. This event is useful to populate the object with data or otherwise prepare it for the user.
>

## <a id="keydown"></a>KeyDown ##
> ### Input Parameters ###
> - **KeyCode**: Integer - the ASCII value of the key pressed.
> - **Shift**: Integer - the bitwise value representing all of the shifting keys pressed.
>
> The KeyDown event is the first of the key events to be raised and occurs when the key is pressed down. The KeyDown event passes in the KeyCode and the Shift state. The KeyCode represents the ASCII value of the key that was pressed. The Shift parameter represents which of the three "shift" keys were also pressed. The possible values of Shift are: 1 = Shift Key, 2 = CTRL key, and 4 = ALT key. Bitwise logic can be used to determine if more than one key was being pressed. The code below can be used to determine which shifting keys are pressed:
```vb
    Private Sub Object1_KeyDown(KeyCode As Integer, Shift As Integer) Handles Object1.KeyDown
        Dim bShift As Boolean = 1 And Shift
        Dim bAlt As Boolean = 2 And Shift
        Dim bCtrl As Boolean = 4 And Shift
        
        'Add logic here that uses the boolean values to suit your needs.
    End Sub
```
>

## <a id="keypress"></a>KeyPress ##
> ### Input Parameters ###
> - **KeyASCII**: Integer - the ASCII value of the key pressed.
>
> The KeyPress event is similar to the KeyDown, but it happens after the KeyDown event. The event passes in the ASCII value of the key pressed via the KeyASCII property. Setting this property to 0 (zero) within the keypress event will nullify the keypress and, effectively, ignore it.
>

## <a id="keyup"></a>KeyUp ##
> ### Input Parameters ###
> - **KeyCode**: Integer - the ASCII value of the key pressed.
> - **Shift**: Integer - the bitwise value representing all of the shifting keys pressed.
>
> The KeyUp event is the final key event to be raised and occurs when the user releases the key.
>

## <a id="lostfocus"></a>LostFocus ##
> ### Input Parameters ###
> None
>
> The LostFocus event is raised when the object loses focus. An object can lose focus when the user clicks the mouse on something else or uses the tab key to move the input selector.
>

## <a id="mousedown"></a>MouseDown ##
> ### Input Parameters ###
> - **Button**: Integer - the ASCII value of the key pressed.
> - **Shift**: Integer - the bitwise value representing all of the shifting keys pressed.
> - **X**: Integer - the number of pixels the mouse is from the left edge of the object's container
> - **Y**: Integer - the number of pixels the mouse is from the top edge of the object's container
>
> The MouseDown event is raised when the mouse button is pressed while over the object.

## <a id="mousemove"></a>MouseMove ##
> ### Input Parameters ###
> - **Button**: Integer - the ASCII value of the key pressed.
> - **Shift**: Integer - the bitwise value representing all of the shifting keys pressed.
> - **X**: Integer - the number of pixels the mouse is from the left edge of the object's container
> - **Y**: Integer - the number of pixels the mouse is from the top edge of the object's container
>
> The MouseMove event is raised when the mouse is moved over the object. The MouseMove event has several parameters that provide useful information to the event. The Button parameter is an integer value that represents which button was pressed. The possible values are 1 = Left button, 2 = Right button, and 4 = Center button. See the KeyDown event for information on using bitwise boolean logic to determine which buttons were pressed. The Shift parameter works the same way for the MouseMove as it does for the KeyPress. Again, see the KeyPress event for help determining which shifting keys are being pressed. The X and Y parameters provide the location of the mouse as it moves.
>

## <a id="mouseup"></a>MouseUp ##
> ### Input Parameters ###
> - **Button**: Integer - the ASCII value of the key pressed.
> - **Shift**: Integer - the bitwise value representing all of the shifting keys pressed.
> - **X**: Integer - the number of pixels the mouse is from the left edge of the object's container
> - **Y**: Integer - the number of pixels the mouse is from the top edge of the object's container
>
> The MouseUp event is raised when the mouse button is released and the mouse is over the object.
>

## <a id="nodecheck"></a>NodeCheck ##
> ### Input Parameters ###
> 
>
> .
>

## <a id="nodeclick"></a>NodeClick ##
> ### Input Parameters ###
> None
>
> .
>

## <a id="nodeselect"></a>NodeSelect ##
> ### Input Parameters ###
> None
>
> .
>

## <a id="paint"></a>Paint ##
> ### Input Parameters ###
> 
>
> .
>

## <a id="pathchange"></a>PathChange ##
> ### Input Parameters ###
> None
>
> .
>

## <a id="patternchange"></a>PatternChange ##
> ### Input Parameters ###
> None
>
> .
>

## <a id="resize"></a>Resize ##
> ### Input Parameters ###
> 
>
> .
>

## <a id="scroll"></a>Scroll ##
> ### Input Parameters ###
> 
>
> .
>

## <a id="timer"></a>Timer ##
> ### Input Parameters ###
> 
>
> .
>