# <a id="anchors"></a>Anchors Property #
## Data Type ##
String
## Description ##
There are four anchor properties, Left, Top, Right, and Bottom. Anchors the object to one or more of the container boundaries. For example, anchoring an object to the bottom and right will cause the object to remain the same distance from the bottom and right of the container as the container is resized.

---

# <a id="appearance"></a>Appearance Property #
## Data Type ##
[AppearanceConstants](constants_enumerations.md)
## Description ##
Gets and sets the appearance of the object. There are two possible values, vbAppear3d and vbAppearFlat.

---

# <a id="backcolor"></a>Backcolor Property #
## Data Type ##
Long
## Description ##
Gets and sets the backcolor property which represents the color of the object's background. The background color can be set in the form property window or at runtime by using the RGB function. For example: object.backgroundcolor = rgb(255,0,0) will set the background color to red.

---

# <a id="caption"></a>Caption Property #
## Data Type ##
String
## Description ##
Gets and sets the caption text. The caption is the text that is displayed on the control

---

# <a id="dock"></a>Dock Property #
## Data Type ##
[DockModeConstants](constants_enumerations.md#DockModeConstants)
## Description ##
Gets and sets Dock property. The object can be undocked, docked against any one container edge, or set to fill the entire container. There are six potential values for the Dock property: VBDockNone, VBDockLeft, VBDockTop, VBDockRight, VBDockBottom, and VBDockFill.

---

# <a id="enabled"></a>Enabled Property #
## Data Type ##
Boolean
## Description ##
Gets and sets the Enabled property. The Enabled property enables or disables the object. Disabling the object keeps the object visible but disables it and usually turns it grey.

---

# <a id="fontbold"></a>FontBold Property #
## Data Type ##
Boolean
## Description ##
Gets and sets the font of the object to bold.

---

# <a id="fontitalic"></a>FontItalic Property #
## Data Type ##
Boolean
## Description ##
Gets and sets the font of the object to italic.

---

# <a id="fontname"></a>FontName Property #
## Data Type ##
String
## Description ##
Gets and sets the font of the object text.

---

# <a id="fontsize"></a>FontSize Property #
## Data Type ##
Single
## Description ##
Gets and sets the font size of the Caption text.

---

# <a id="fontstrikethrough"></a>FontStrikethrough Property #
## Data Type ##
Boolean
## Description ##
Gets and sets the strikethrough of the object text.

---

# <a id="fontunderline"></a>FontUnderline Property #
## Data Type ##
Boolean
## Description ##
Gets and sets the underline of the object text.

---

# <a id="height"></a>Height Property #
## Data Type ##
Double
## Description ##
Gets and sets the height, in pixels, of the object.

---

# <a id="left"></a>Left Property #
## Data Type ##
Double
## Description ##
Gets and sets the left position of the object, relative to the container.

---

# <a id="mousepointer"></a>MousePointer Property #
## Data Type ##
[MousePointerConstants](constants_enumerations.md#MousePointerConstants)
## Description ##
MousePointerConstant property. Gets and sets the look of the mouse pointer when the mouse is over the object.

---

# <a id="name"></a>Name Property #
## Data Type ##
String
## Description ##

---

# <a id="tabindex"></a>TabIndex Property #
## Data Type ##
Long
## Description ##
Gets or sets the order in which each object receives focus when the tab key is pressed. 

---

# <a id="tabstop"></a>TabStop Property #
## Data Type ##
Boolean
## Description ##
Gets or sets the TabStop property, which causes the focus to stop on the control when the tab button is pressed and the object's TabIndex is the next in line. Setting this property to False will cause the object to be skipped when the tab key is pressed to move to the next object.

---

# <a id="tag"></a>Tag Property #
## Data Type ##
String
## Description ##
Gets or sets the tag property. The tag property can be used to store program specific data. It is not used by twinBASIC and is not visible to the end user.

---

# <a id="top"></a>Top Property #
## Data Type ##
Double
## Description ##
Gets or sets the number of pixels from the top of the container the object should appear.

---

# <a id="visible"></a>Visible Property #
## Data Type ##
Boolean
## Description ##
Gets or sets the visible property. Setting the property to True will make the object appear on the screen. Setting it to false will force it to not be shown.

---

# <a id="visualstyles"></a>VisualStyles Property #
## Data Type ##
Double
## Description ##
Indicates whether the control will be drawn reflecting the current Windows OS theme.

__We probably need an image example on that one.__

---

# <a id="width"></a>Width Property #
## Data Type ##
Double
## Description ##
Gets or sets the width of the object in pixels.
