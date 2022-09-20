# twinBASICDocs
## CommandButton Control
Command Buttons can be used to begin, interrupt, or end a process. To change the text that appears on the button, set the Caption property. Clicking on a button will raise the OnClick event.

---
### Methods
> - CreateBackbrush
> - CreateDeferredDispatchWrapper
> - CreateRootWindowElement
> - GetFontMetrics
> - Move
> - Refresh
> - ScheduleCallback
> - SetFocus
> - SubClassWindowElement

---
### Events
> - [Click](event_click.md)
> - [GotFocus](event_gotfocus.md)
> - [Initialize](event_initialize.md)
> - [KeyDown](event_keydown.md)
> - [KeyPress](event_keypress.md)
> - [KeyUp](event_keyup.md)
> - [LostFocus](event_lostfocus)
> - [MouseDown](event_mousedown)
> - [MouseMove](event_mousemove)
---

#### MouseUp
> **Parameters:** 
> - **Button**: Integer - the ASCII value of the key pressed.
> - **Shift**: Integer - the bitwise value representing all of the shifting keys pressed.
> - **X**: Integer - the number of pixels the mouse is from the left edge of the object's container
> - **Y**: Integer - the number of pixels the mouse is from the top edge of the object's container.
> 
> The MouseUp event fires when the mouse button is released and the mouse is over the object.

---
### Properties
#### Name
> **Data Type**: String
> 
> Every object must have a unique name. The name is used to reference the object in code.
#### Anchors
> **Data Type**: Boolean
> 
> There are four anchor properties, Left, Top, Right, and Bottom. Anchors the object to one or more of the container boundaries. For example, anchoring an object to the bottom and right will cause the object to remain the same distance from the bottom and right of the container as the container is resized.
#### Appearance
> **Data Type**: Appearance Integer Constant
> 
> Gets and sets the appearance of the object. There are two possible values, vbAppear3d and vbAppearFlat.
#### Backcolor
> **Data Type**: Long
> 
> Gets and sets the backcolor property which represents the color of the object's background. The background color can be set in the form property window or at runtime by using the RGB function. For example: object.backgroundcolor = rgb(255,0,0) will set the background color to red.
#### Caption
> **Data Type**: String
> 
> Gets and sets the caption text. The caption is the text that is displayed on the control
#### Dock
> **Data Type**: Data Type Integer Constant
> 
> Gets and sets Dock property. The object can be undocked, docked against any one container edge, or set to fill the entire container. There are six potential values for the Dock property: VBDockNone, VBDockLeft, VBDockTop, VBDockRight, VBDockBottom, and VBDockFill.
#### Enabled
> **Data Type**: Boolean
> 
> Gets and sets the Enabled property. The Enabled property enables or disables the object. Disabling the object keeps the object visible but disables it and usually turns it grey.
#### FontBold
> **Data Type**: Boolean
> 
> Gets and sets the font of the Caption to bold.
#### FontItalic
> **Data Type**: Boolean
> 
> Gets and sets the font of the Caption to italic.
#### FontName
> **Data Type**: String
> 
> Gets and sets the font of the Caption text.
#### FontSize
> **Data Type**: Single
> 
> Gets and sets the font size of the Caption text.
#### FontStrikethrough
> **Data Type**: Boolean
> 
> Gets and sets the strikethrough of the Caption text.
#### FontUnderline
> **Data Type**: Boolean
> 
> Gets and sets the underline of the Caption text.
#### Height
> **Data Type**: Double
> 
> Gets and sets the height, in pixels, of the object.
#### Left
> **Data Type**: Double
> 
> Gets and sets the left position of the object, relative to the container.
#### MousePointer
> **Data Type**: Mouse Pointer Integer Constant
> 
> MousePointerConstant property. Gets and sets the look of the mouse pointer when the mouse is over the object. Available values include: vbArrow, vbArrowHourglass, vbArrowQuestion, vbCrosshair, vbDefault, vbHand, vbHourglass, vbIbeam, vbIconPointer, vbNoDrop, and vbPerson. 
#### TabIndex
> **Data Type**: Long
> 
> Gets or sets the order in which each object receives focus when the tab key is pressed. 
#### TabStop
> **Data Type**: Boolean
> 
> Gets or sets the TabStop property, which causes the focus to stop on the control when the tab button is pressed and the object's TabIndex is the next in line. Setting this property to False will cause the object to be skipped when the tab key is pressed to move to the next object.
#### Tag
> **Data Type**: String
> 
> Gets or sets the tag property. The tag property can be used to store program specific data. It is not used by twinBASIC and is not visible to the end user.
#### Top
> **Data Type**: Double
> 
> Gets or sets the number of pixels from the top of the container the object should appear.
#### Visible
> **Data Type**: Boolean
> 
> Gets or sets the visible property. Setting the property to True will make the object appear on the screen. Setting it to false will force it to not be shown.
#### VisualStyles
> **Data Type**: Double
> 
#### Width
> **Data Type**: Double
> 
> Gets or sets the width of the object in pixels.
