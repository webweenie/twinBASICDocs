# twinBASICDocs - Properties #
A property is an attribute of an object. Objects, such as controls, can have any number of attributes which can be set by using the appropriate property. For example, the TextBox control has a Text property that allows the TextBox to be populated.

Properties are accessed using dot notation, as shown in the example below, which sets the text property of the Text1 object to the string, Hello World!:
```vb
Text1.text = "Hello World!"
```

Properties can also be used on the other side of the equal sign. For example, the contents of a TextBox can be loaded into a variable for further processing:
```vb
Dim strMyText as String = Text1.text
```

## <a id="alignment"></a>Alignment ##
> ### Data Type ###
> xxx
> ### Description ###
> xxx
> 

## <a id="anchors"></a>Anchors Property ##
> ### Data Type ###
> String
> ### Description ###
> There are four anchor properties, Left, Top, Right, and Bottom. Anchors the object to one or more of the container boundaries. For example, anchoring an object to the bottom and right will cause the object to remain the same distance from the bottom and right of the container as the container is resized.
> 

## <a id="appearance"></a>Appearance Property ##
> ### Data Type ###
> [AppearanceConstants](constants_enumerations.md)
> ### Description ###
> Gets and sets the appearance of the object. There are two possible values, vbAppear3d and vbAppearFlat.
> 

## <a id="archive"></a>Archive Property ##
> ### Data Type ###
> Boolean
> ### Description ###
> xxx
> 

## <a id="autoredraw"></a>AutoRedraw Property ##
> ### Data Type ###
> Boolean
> ### Description ###
> xxx
> 

## <a id="backcolor"></a>Backcolor Property ##
> ### Data Type ###
> Long
> ### Description ###
> Gets and sets the backcolor property which represents the color of the object's background. The background color can be set in the form property window or at runtime by using the RGB function. For example: object.backgroundcolor = rgb(255,0,0) will set the background color to red.
> 

## <a id="backstyle"></a>Backstyle Property ##
> ### Data Type ###
> Long
> ### Description ###
> xxx
> 

## <a id="bordercolor"></a>BorderColor Property ##
> ### Data Type ###
> Long
> ### Description ###
> xxx
> 

## <a id="borderstyle"></a>BorderStyle Property ##
> ### Data Type ###
> xxx
> ### Description ###
> xxx
> 

## <a id="borderwidth"></a>BorderWidth Property ##
> ### Data Type ###
> Long
> ### Description ###
> xxx
> 

## <a id="caption"></a>Caption Property ##
> ### Data Type ###
> String
> ### Description ###
> Gets and sets the caption text. The caption is the text that is displayed on the control
> 

## <a id="checkboxes"></a>Checkboxes Property ##
> ### Data Type ###
> xxx
> ### Description ###
> xxx
> 

## <a id="clipcontrols"></a>ClipControls Property ##
> ### Data Type ###
> Boolean
> ### Description ###
> xxx
> 

## <a id="columns"></a>Columns Property ##
> ### Data Type ###
> Long
> ### Description ###
> xxx
> 

## <a id="controlbox"></a>ControlBox Property ##
> ### Data Type ###
> String
> ### Description ###
> Gets and sets the caption text. The caption is the text that is displayed on the control
> 

## <a id="dock"></a>Dock Property ##
> ### Data Type ###
> [DockModeConstants](constants_enumerations.md#DockModeConstants)
> ### Description ###
> Gets and sets Dock property. The object can be undocked, docked against any one container edge, or set to fill the entire container. There are six potential values for the Dock property: VBDockNone, VBDockLeft, VBDockTop, VBDockRight, VBDockBottom, and VBDockFill.
> 

## <a id="drawmode"></a>DrawMode Property ##
> ### Data Type ###
> DrawModeConstants
> ### Description ###
> xxx
> 

## <a id="drawstyle"></a>DrawStyle Property ##
> ### Data Type ###
> DrawModeConstants
> ### Description ###
> xxx
> 

## <a id="drawwidth"></a>DrawWidth Property ##
> ### Data Type ###
> Long
> ### Description ###
> xxx
> 

## <a id="enabled"></a>Enabled Property ##
> ### Data Type ###
> Boolean
> ### Description ###
> Gets and sets the Enabled property. The Enabled property enables or disables the object. Disabling the object keeps the object visible but disables it and usually turns it grey.
> 

## <a id="fillcolor"></a>FillColor Property ##
> ### Data Type ###
> Long
> ### Description ###
> xxx
> 

## <a id="fillstyle"></a>FillStyle Property ##
> ### Data Type ###
> Long
> ### Description ###
> xxx
> 

## <a id="fontbold"></a>FontBold Property ##
> ### Data Type ###
> Boolean
> ### Description ###
> Gets and sets the font of the object to bold.
> 

## <a id="fontitalic"></a>FontItalic Property ##
> ### Data Type ###
> Boolean
> ### Description ###
> Gets and sets the font of the object to italic.
> 

## <a id="fontname"></a>FontName Property ##
> ### Data Type ###
> String
> ### Description ###
> Gets and sets the font of the object text.
> 

## <a id="fontsize"></a>FontSize Property ##
> ### Data Type ###
> Single
> ### Description ###
> Gets and sets the font size of the Caption text.
> 

## <a id="fontstrikethrough"></a>FontStrikethrough Property ##
> ### Data Type ###
> Boolean
> ### Description ###
> Gets and sets the strikethrough of the object text.
> 

## <a id="fonttransparent"></a>FontTransparent Property ##
> ### Data Type ###
> Boolean
> ### Description ###
> xxx
> 

## <a id="fontunderline"></a>FontUnderline Property ##
> ### Data Type ###
> Boolean
> ### Description ###
> Gets and sets the underline of the object text.
> 

## <a id="forecolor"></a>Forecolor Property ##
> ### Data Type ###
> xxx
> ### Description ###
> xxx
> 

## <a id="fullrowselect"></a>FullRowSelect Property ##
> ### Data Type ###
> xxx
> ### Description ###
> xxx
> 

## <a id="hasdc"></a>HasDC Property ##
> ### Data Type ###
> boolean
> ### Description ###
> xxx
> 

## <a id="height"></a>Height Property ##
> ### Data Type ###
> Double
> ### Description ###
> Gets and sets the height, in pixels, of the object.
> 

## <a id="hidden"></a>Hidden Property ##
> ### Data Type ###
> Boolean
> ### Description ###
> xxx
> 

## <a id="hideselection"></a>Hideselection Property ##
> ### Data Type ###
> Boolean
> ### Description ###
> xxx
> 

## <a id="hottracking"></a>HotTracking Property ##
> ### Data Type ###
> xxx
> ### Description ###
> xxx
> 

## <a id="indentation"></a>Indentation Property ##
> ### Data Type ###
> Boolean
> ### Description ###
> xxx
> 

## <a id="integralheight"></a>IntegralHeight Property ##
> ### Data Type ###
> Boolean
> ### Description ###
> xxx
> 

## <a id="interval"></a>Interval Property ##
> ### Data Type ###
> Long
> ### Description ###
> xxx
> 

## <a id="itemdata"></a>ItemData Property ##
> ### Data Type ###
> Long
> ### Description ###
> xxx
> 

## <a id="labeledit"></a>LabelEdit Property ##
> ### Data Type ###
> Boolean
> ### Description ###
> xxx
> 

## <a id="largechange"></a>LargeChange Property ##
> ### Data Type ###
> Long
> ### Description ###
> xxx
> 

## <a id="left"></a>Left Property ##
> ### Data Type ###
> Double
> ### Description ###
> Gets and sets the left position of the object, relative to the container.
> 

## <a id="linestyle"></a>LineStyle Property ##
> ### Data Type ###
> Boolean
> ### Description ###
> xxx
> 

## <a id="list"></a>List Property ##
> ### Data Type ###
> String
> ### Description ###
> xxx
> 

## <a id="locked"></a>Locked Property ##
> ### Data Type ###
> Boolean
> ### Description ###
> xxx
> 

## <a id="marqueeanimation"></a>MarqueeAnimation Property ##
> ### Data Type ###
> Boolean
> ### Description ###
> xxx
> 

## <a id="marqueespeed"></a>MarqueeSpeed Property ##
> ### Data Type ###
> Long
> ### Description ###
> xxx
> 

## <a id="max"></a>Max Property ##
> ### Data Type ###
> Long
> ### Description ###
> xxx
> 

## <a id="maxlength"></a>MaxLength Property ##
> ### Data Type ###
> Long
> ### Description ###
> xxx
> 

## <a id="maxcheckboxsize"></a>MaxCheckboxDize Property ##
> ### Data Type ###
> Long
> ### Description ###
> xxx
> 

## <a id="min"></a>Min Property ##
> ### Data Type ###
> Long
> ### Description ###
> xxx
> 

## <a id="mousepointer"></a>MousePointer Property ##
> ### Data Type ###
> [MousePointerConstants](constants_enumerations.md#MousePointerConstants)
> ### Description ###
> MousePointerConstant property. Gets and sets the look of the mouse pointer when the mouse is over the object.
> 

## <a id="multiline"></a>MultiLine Property ##
> ### Data Type ###
> Boolean
> ### Description ###
> xxx
> 

## <a id="multiselect"></a>MultiSelect Property ##
> ### Data Type ###
> MultiSelect
> ### Description ###
> xxx
> 

## <a id="pathseparator"></a>PathSeparator Property ##
> ### Data Type ###
> Boolean
> ### Description ###
> xxx
> 

## <a id="name"></a>Name Property ##
> ### Data Type ###
> String
> ### Description ###
> 

## <a id="normal"></a>Normal Property ##
> ### Data Type ###
> Boolean
> ### Description ###
> 

## <a id="orientation"></a>Orientation Property ##
> ### Data Type ###
> PrbOrientation
> ### Description ###
> 

## <a id="passwordchar"></a>PasswordChar Property ##
> ### Data Type ###
> String
> ### Description ###
> 

## <a id="pattern"></a>Pattern Property ##
> ### Data Type ###
> String
> ### Description ###
> 

## <a id="picture"></a>Picture Property ##
> ### Data Type ###
> StdPicture
> ### Description ###
> 

## <a id="readonly"></a>ReadOnly Property ##
> ### Data Type ###
> Boolean
> ### Description ###
> 

## <a id="roundedcornersize"></a>RoundedCornerSize Property ##
> ### Data Type ###
> Boolean
> ### Description ###
> 

## <a id="scroll"></a>Scroll Property ##
> ### Data Type ###
> Boolean
> ### Description ###
> xxx
> 

## <a id="scrollbars"></a>Scrollbars Property ##
> ### Data Type ###
> PrbScrolling
> ### Description ###
> 

## <a id="scrolling"></a>Scrolling Property ##
> ### Data Type ###
> PrbScrolling
> ### Description ###
> 

## <a id="shape"></a>Shape Property ##
> ### Data Type ###
> Shape
> ### Description ###
> 

## <a id="singlesel"></a>SingleSel Property ##
> ### Data Type ###
> xxx
> ### Description ###
> xxx
> 

## <a id="smallchange"></a>SmallChange Property ##
> ### Data Type ###
> Long
> ### Description ###
> xxx
> 

## <a id="smoothreverse"></a>SmoothReverse Property ##
> ### Data Type ###
> Boolean
> ### Description ###
> xxx
> 

## <a id="sorted"></a>Sorted Property ##
> ### Data Type ###
> String
> ### Description ###
> xxx
> 

## <a id="sortorder"></a>SortOrder Property ##
> ### Data Type ###
> xxx
> ### Description ###
> xxx
> 

## <a id="sorttype"></a>SortType Property ##
> ### Data Type ###
> xxx
> ### Description ###
> xxx
> 

## <a id="state"></a>State Property ##
> ### Data Type ###
> PrbState
> ### Description ###
> xxx
> 

## <a id="step"></a>Step Property ##
> ### Data Type ###
> Long
> ### Description ###
> xxx
> 

## <a id="style"></a>Stretch Property ##
> ### Data Type ###
> Controltype
> ### Description ###
> xxx
> 

## <a id="style"></a>Style Property ##
> ### Data Type ###
> String
> ### Description ###
> xxx
> 

## <a id="tabindex"></a>TabIndex Property ##
> ### Data Type ###
> Long
> ### Description ###
> Gets or sets the order in which each object receives focus when the tab key is pressed. 
> 

## <a id="tabstop"></a>TabStop Property ##
> ### Data Type ###
> Boolean
> ### Description ###
> Gets or sets the TabStop property, which causes the focus to stop on the control when the tab button is pressed and the object's TabIndex is the next in line. Setting this property to False will cause the object to be skipped when the tab key is pressed to move to the next object.
> 

## <a id="tag"></a>Tag Property ##
> ### Data Type ###
> String
> ### Description ###
> Gets or sets the tag property. The tag property can be used to store program specific data. It is not used by twinBASIC and is not visible to the end user.
> 

## <a id="text"></a>Text Property ##
> ### Data Type ###
> String
> ### Description ###
> 

## <a id="top"></a>Top Property ##
> ### Data Type ###
> Double
> ### Description ###
> Gets or sets the number of pixels from the top of the container the object should appear.
> 

## <a id="usemnemonic"></a>UseMnemonic Property ##
> ### Data Type ###
> Boolean
> ### Description ###
> xxx
> 

## <a id="variationa"></a>VariationA Property ##
> ### Data Type ###
> Long
> ### Description ###
> xxx
> 

## <a id="variationb"></a>VariationB Property ##
> ### Data Type ###
> Long
> ### Description ###
> xxx
> 

## <a id="variationc"></a>VariationC Property ##
> ### Data Type ###
> Long
> ### Description ###
> xxx
> 

## <a id="value"></a>Value Property ##
> ### Data Type ###
> xxx
> ### Description ###
> xxx
> 

## <a id="visible"></a>Visible Property ##
> ### Data Type ###
> Boolean
> ### Description ###
> Gets or sets the visible property. Setting the property to True will make the object appear on the screen. Setting it to false will force it to not be shown.
> 

## <a id="visualstyles"></a>VisualStyles Property ##
> ### Data Type ###
> Double
> ### Description ###
> Indicates whether the control will be drawn reflecting the current Windows OS theme.
> 
> __We probably need an image example on that one.__
> 

## <a id="wheelscrollevent"></a>WheelScrollEvent Property ##
> ### Data Type ###
> Boolean
> ### Description ###
> 
> 

## <a id="width"></a>Width Property ##
> ### Data Type ###
> Double
> ### Description ###
> Gets or sets the width of the object in pixels.
> 

## <a id="x1"></a>X1 Property ##
> ### Data Type ###
> Double
> ### Description ###
> xxx.
> 

## <a id="x2"></a>X2 Property ##
> ### Data Type ###
> Double
> ### Description ###
> xxx.
> 

## <a id="y1"></a>Y1 Property ##
> ### Data Type ###
> Double
> ### Description ###
> xxx.
> 

## <a id="y2"></a>Y2 Property ##
> ### Data Type ###
> Double
> ### Description ###
> xxx.
> 