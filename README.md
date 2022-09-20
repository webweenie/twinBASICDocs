# twinBASICDocs
## CommandButton Control
Command Buttons can be used to begin, interrupt, or end a process. To change the text that appears on the button, set the Caption property. Clicking on a button will raise the OnClick event.

---
### Methods
#### CreateBackbrush
#### CreateDeferredDispatchWrapper
#### CreateRootWindowElement
#### GetFontMetrics
#### Move
#### Refresh
#### ScheduleCallback
#### SetFocus
#### SubClassWindowElement

---
### Events
#### Click
> The Click event is thrown when the user "clicks" on the object. A click can be registered by clicking with the mouse button, or by selecting the object and pressing the enter key.
#### GotFocus
> The GotFocus event is thrown when the object receives the focus. The object can get focus by being clicked with the mouse, or by the user tabbing into the object.
#### Initialize
> The initialize event is thrown when the object is initialized during the form load. This event can be used to populate the object with data or otherwise prepare it for the user.
#### KeyDown
> **Parameters:** 
>- **KeyCode**: the ASCII value of the key pressed.
>- **Shift**: the bitwise value representing all of the shifting keys pressed.
>The KeyDown event is the first of the key events to fire and occurs when the key is pressed down. The KeyDown event passes in the KeyCode and the Shift state. The KeyCode represents the ASCII value of the key that was pressed. The Shift parameter represents which of the three "shift" keys were also pressed. The possible values of Shift are: 1 = Shift Key, 2 = CTRL key, and 4 = ALT key. Bitwise logic can be used to determine if more than one key was being pressed. The code below can be used to determine which shifting keys are pressed:
```vb
    Private Sub Object1_KeyDown(KeyCode As Integer, Shift As Integer) Handles Object1.KeyDown
        Dim bShift As Boolean
        Dim bAlt As Boolean
        Dim bCtrl As Boolean
        
        bShift = 1 And Shift
        bAlt = 2 And Shift
        bCtrl = 4 And Shift
        
        'Add logic here that uses the boolean values to suit your needs.
    End Sub
```
#### KeyPress
**Parameters:** 
- **KeyASCII**: Integer - the ASCII value of the key pressed.
> The KeyPress event is similar to the KeyDown, but it happens after the KeyDown event. The event passes in the ASCII value of the key pressed via the KeyASCII property. Setting this property to 0 (zero) within the keypress event will nullify the keypress and, effectively, ignore it. 
#### KeyUp
**Parameters:** 
- **KeyCode**: Integer - the ASCII value of the key pressed.
- **Shift**: Integer - the bitwise value representing all of the shifting keys pressed.
> The KeyUp event is the final key event to trigger and occurs when the user releases the key.
#### LostFocus
> The LostFocus event fires when the object loses focus. This can happen when the user clicks on another object with the mouse, or presses the tab key and moves the focus to the next object.
#### MouseDown
**Parameters:** 
- **Button**: Integer - the ASCII value of the key pressed.
- **Shift**: Integer - the bitwise value representing all of the shifting keys pressed.
- **X**: Integer - the number of pixels the mouse is from the left edge of the object's container
- **Y**: Integer - the number of pixels the mouse is from the top edge of the object's container
> The MouseDown event fires when the mouse button is pressed while over the object.
#### MouseMove
**Parameters:** 
- **Button**: Integer - the ASCII value of the key pressed.
- **Shift**: Integer - the bitwise value representing all of the shifting keys pressed.
- **X**: Integer - the number of pixels the mouse is from the left edge of the object's container
- **Y**: Integer - the number of pixels the mouse is from the top edge of the object's container
> The MouseMove event fires when the mouse is moved over the object. The MouseMove event has several parameters that provide useful information to the event. The Button parameter is an integer value that represents which button was pressed. The possible values are 1 = Left button, 2 = Right button, and 4 = Center button. See the KeyDown event for information on using bitwise boolean logic to determine which buttons were pressed. The Shift parameter works the same way for the MouseMove as it does for the KeyPress. Again, see the KeyPress event for help determining which shifting keys are being pressed. The X and Y parameters provide the location of the mouse as it moves.
#### MouseUp
**Parameters:** 
- **Button**: Integer - the ASCII value of the key pressed.
- **Shift**: Integer - the bitwise value representing all of the shifting keys pressed.
- **X**: Integer - the number of pixels the mouse is from the left edge of the object's container
- **Y**: Integer - the number of pixels the mouse is from the top edge of the object's container
> The MouseUp event fires when the mouse button is released and the mouse is over the object.

---
### Properties
#### Name
**Data Type**: String
> Every object must have a unique name. The name is used to reference the object in code.
#### Anchors
**Data Type**: Boolean
> There are four anchor properties, Left, Top, Right, and Bottom. Anchors the object to one or more of the container boundaries. For example, anchoring an object to the bottom and right will cause the object to remain the same distance from the bottom and right of the container as the container is resized.
#### Appearance
**Data Type**: Appearance Integer Constant
> Gets and sets the appearance of the object. There are two possible values, vbAppear3d and vbAppearFlat.
#### Backcolor
**Data Type**: Long
> Gets and sets the backcolor property which represents the color of the object's background. The background color can be set in the form property window or at runtime by using the RGB function. For example: object.backgroundcolor = rgb(255,0,0) will set the background color to red.
#### Caption
**Data Type**: String
> Gets and sets the caption text. The caption is the text that is displayed on the control
#### Dock
**Data Type**: Data Type Integer Constant
> Gets and sets Dock property. The object can be undocked, docked against any one container edge, or set to fill the entire container. There are six potential values for the Dock property: VBDockNone, VBDockLeft, VBDockTop, VBDockRight, VBDockBottom, and VBDockFill.
#### Enabled
**Data Type**: Boolean
> Gets and sets the Enabled property. The Enabled property enables or disables the object. Disabling the object keeps the object visible but disables it and usually turns it grey.
#### FontBold
**Data Type**: Boolean
> Gets and sets the font of the Caption to bold.
#### FontItalic
**Data Type**: Boolean
> Gets and sets the font of the Caption to italic.
#### FontName
**Data Type**: String
> Gets and sets the font of the Caption text.
#### FontSize
**Data Type**: Single
> Gets and sets the font size of the Caption text.
#### FontStrikethrough
**Data Type**: Boolean
> Gets and sets the strikethrough of the Caption text.
#### FontUnderline
**Data Type**: Boolean
> Gets and sets the underline of the Caption text.
#### Height
**Data Type**: Double
> Gets and sets the height, in pixels, of the object.
#### Left
**Data Type**: Double
> Gets and sets the left position of the object, relative to the container.
#### MousePointer
**Data Type**: Mouse Pointer Integer Constant
> MousePointerConstant property. Gets and sets the look of the mouse pointer when the mouse is over the object. Available values include: vbArrow, vbArrowHourglass, vbArrowQuestion, vbCrosshair, vbDefault, vbHand, vbHourglass, vbIbeam, vbIconPointer, vbNoDrop, and vbPerson. 
#### TabIndex
**Data Type**: Long
> Gets or sets the order in which each object receives focus when the tab key is pressed. 
#### TabStop
**Data Type**: Boolean
> Gets or sets the TabStop property, which causes the focus to stop on the control when the tab button is pressed and the object's TabIndex is the next in line. Setting this property to False will cause the object to be skipped when the tab key is pressed to move to the next object.
#### Tag
**Data Type**: String
> Gets or sets the tag property. The tag property can be used to store program specific data. It is not used by twinBASIC and is not visible to the end user.
#### Top
**Data Type**: Double
> Gets or sets the number of pixels from the top of the container the object should appear.
#### Visible
**Data Type**: Boolean
> Gets or sets the visible property. Setting the property to True will make the object appear on the screen. Setting it to false will force it to not be shown.
#### VisualStyles
**Data Type**: Double
#### Width
**Data Type**: Double
> Gets or sets the width of the object in pixels.
