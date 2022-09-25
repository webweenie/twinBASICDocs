# twinBASICDocs - Constants #
trueBASIC has many built-in constants. Using constants, gives the developer a readable value that is easy to understand. Without constants, many properties would require integers to be used to represent the various states, making the code harder to write and understand later.

---

## <a id="appearanceconstants"></a>AppearanceConstants ##
> - vbAppear3d = 1
> - vbAppearFlat = 0
> 

## <a id="alignment"></a>Alignment Constants ##
> ### Align Property ###
> - vbAlignBottom = 2 - Align control to bottom of form
> - vbAlignLeft = 3 - Align control to left of form
> - vbAlignNone = 0 - Size and location set at design time or in code
> - vbAlignRight = 4 - Align control to right of form
> - vbAlignTop = 1 - Align control to top of form
>

> ### <a id="alignmentproperty"></a>Alignment Property Constants ###
> - vbLeftJustify = 0 - Left align data in the control
> - vbRightJustify = 1 - Right align data in the control
> - vbCenter = 2 - Center data in the control
>

## <a id="character"></a>Character Constants ###
> - vbBack = Chr(8) (Backspace character)
> - vbCr = Chr(13) (Carriage return character)
> - vbCrLf = Chr(13) + Chr(10) (Carriage return + linefeed combination)
> - vbLf = Chr(10) (Linefeed character)
> - vbNewLine = Platform-specific new line character
> - vbNullChar = Chr(0)
> - vbNullString = String with value 0, which is not the same as a zero-length string ("")
> - vbObjectError = -2147221504 (All user-defined error numbers should be greater than this value.)
> - vbTab = Chr(9) (Tab character)
>


## <a id="color"></a>Color Constants ##
> ### Colors ###
> - vbBlack = rgb(0, 0, 0)
> - vbRed = rgb(0, 0, 0)
> - vbGreen = rgb(0, 0, 0)
> - vbYellow = rgb(0, 0, 0)
> - vbBlue = rgb(0, 0, 255)
> - vbMagenta = rgb(255, 0, 255)
> - vbCyan - rgb(0, 255, 255)
> - vbWhite = rgb(255, 255, 255)
> 
> ### System Colors ###
> - vb3DDKShadow = 0x80000015 (Darkest shadow used in 3-D display elements)
> - vb3DHighlight = 0x80000014 (Highlight color used in 3-D display elements)
> - vb3DLight = 0x80000016 (Slightly darker than vb3DHighlight)
> - vbActiveBorder = 0x8000000A (Border color of an active window)
> - vbActiveTitleBar = 0x80000002 (Color of the title bar for an active window)
> - vbApplicationWorkspace = 0x8000000C (Background color of multiple-document interface (MDI) applications)
> - vbButtonFace = 0x8000000F (Color of the face of command buttons)
> - vbButtonShadow = 0x80000010 (Color of the edge of command buttons)
> - vbButtonText = 0x80000012 (Color of the text on command buttons)
> - vbDesktop = 0x80000001 (Color of the desktop)
> - vbGrayText = 0x80000011 (Color of disabled text)
> - vbHighlight = 0x8000000D (Color of the background of items selected in a control)
> - vbHighlightText = 0x8000000E (Color of the text for items selected in a control)
> - vbInactiveBorder = 0x8000000B (Color of the border of an inactive window)
> - vbInactiveCaptionText = 0x80000013 (Color of the text for an inactive caption)
> - vbInactiveTitleBar = 0x80000003 (Color of the title bar for an inactive window)
> - vbInfoBackground = 0x80000018 (Color of the background for ToolTips)
> - vbInfoText = 0x80000017 (Color of the text in ToolTips)
> - vbMenuBar = 0x80000004 (Color of the menu background)
> - vbMenuText = 0x80000007 (Color of the menu text)
> - vbScrollBars = 0x80000000 (Color of scroll bars)
> - vbTitleBarText = 0x80000009 (Color of text in caption, size box, and scroll arrow)
> - vbWindowBackground = 0x80000005 (Color of the window background)
> - vbWindowFrame = 0x80000006 (Color of the window frame)
> - vbWindowText = 0x80000008 (Color of text in a window)
>

## <a id="controltype"></a>ControlType Constants ##
> - vbListBoxCheckBox = 1
> - vbListBoxStandard = 0
>

## <a id="date"></a>Date Constants ##
> ### Days of the week ###
> - vbSunday = 1
> - vbMonday = 2
> - vbTuesday = 3
> - vbWednesday = 4
> - vbThursday = 5
> - vbFriday = 6
> - vbSaturday = 7
> 
> ### FirstDayOfWeek Arguments ###
> - vbUseSystem = 0
> - Any of the days of the week constants can also be used
> 
> ### FirstDayOfYear Arguments ###
> - vbUseSystem
> - VbFirstJan1 = 1 (Default. Week 1 will be the week in which January 1 occurs.
> - vbFirstFourDays = 2	Week 1 will be the first week that has at least four days in the new year.)
> - vbFirstFullWeek = 3	(Week 1 will be the first full week of the year.)
>

## <a id="dateformat"></a>Date Format Constants ##
> - vbGeneralDate = 0 The display is determined by the system settings. If there is no fractional part only the date is displayed. If there is no integer part only the time is displayed
> - vbLongDate = 1 (Display only the date using the long date format defined in the computer's regional settings.)
> - vbShortDate = 2 (Display only the date using the short date format defined in the computer's regional settings.)
> - vbLongTime = 3 (Display only the time using the long time format defined in the computer's regional settings.)
> - vbShortTime = 4 (Display only the time using the short time format defined in the computer's regional settings.)
>

## <a id="drawmode"></a>DrawMode Constants ##
> - vbBlackness = 1
> - vbCopyPen = 13
> - vbInvert = 6
> - vbMaskNotPen = 3
> - vbMaskPen = 9
> - vbMaskPenNot = 5
> - vbMergeNotPen = 12
> - vbMergePen = 15
> - vbNop = 11
> - vbNotCopyPen = 4
>

## <a id="drawstyle"></a>DrawStyle Constants ##
> - vbDash = 1
> - vbDashDot = 3
> - vbDashDotDot = 4
> - vbDot = 2
> - vbInsideSolid = 6
> - vbInvisible = 5
> - vbSolid = 0
>

## <a id="keycode"></a>Key Code Constants ##
> ### General Key Codes ###
> - vbKeyBack = 0x8 (BACKSPACE key)
> - vbKeyCancel = 0x3 (CANCEL key)
> - vbKeyCapital = 0x14 (CAPS LOCK key)
> - vbKeyClear = 0xC (CLEAR key)
> - vbKeyControl = 0x11 (CTRL key)
> - vbKeyDelete = 0x2E (DELETE key)
> - vbKeyDown = 0x28 (DOWN ARROW key)
> - vbKeyEnd = 0x23 (END key)
> - vbKeyEscape = 0x1B (ESC key)
> - vbKeyExecute = 0x2B (EXECUTE key)
> - vbKeyHelp = 0x2F (HELP key)
> - vbKeyHome = 0x24 (HOME key)
> - vbKeyInsert = 0x2D (INSERT key)
> - vbKeyLButton = 0x1 (Left mouse button)
> - vbKeyLeft = 0x25 (LEFT ARROW key)
> - vbKeyMButton = 0x4 (Middle mouse button)
> - vbKeyMenu = 0x12 (MENU key)
> - vbKeyNumlock = 0x90 (NUM LOCK key)
> - vbKeyPageDown = 0x22 (PAGE DOWN key)
> - vbKeyPageUp = 0x21 (PAGE UP key)
> - vbKeyPause = 0x13 (PAUSE key)
> - vbKeyPrint = 0x2A (PRINT SCREEN key)
> - vbKeyRButton = 0x2 (Right mouse button)
> - vbKeyReturn = 0xD (ENTER key)
> - vbKeyRight = 0x27 (RIGHT ARROW key)
> - vbKeySelect = 0x29 (SELECT key)
> - vbKeyShift = 0x10 (SHIFT key)
> - vbKeySnapshot = 0x2C (SNAPSHOT key)
> - vbKeySpace = 0x20 (SPACEBAR key)
> - vbKeyTab = 0x9 (TAB key)
> - vbKeyUp = 0x26 (UP ARROW key)
>
> ### Alphanumeric Keys ###
> - vbKeyA = 65 (A key)
> - vbKeyB = 66 (B key)
> - vbKeyC = 67 (C key)
> - vbKeyD = 68 (D key)
> - vbKeyE = 69 (E key)
> - vbKeyF = 70 (F key)
> - vbKeyG = 71 (G key)
> - vbKeyH = 72 (H key)
> - vbKeyI = 73 (I key)
> - vbKeyJ = 74 (J key)
> - vbKeyK = 75 (K key)
> - vbKeyL = 76 (L key)
> - vbKeyM = 77 (M key)
> - vbKeyN = 78 (N key)
> - vbKeyO = 79 (O key)
> - vbKeyP = 80 (P key)
> - vbKeyQ = 81 (Q key)
> - vbKeyR = 82 (R key)
> - vbKeyS = 83 (S key)
> - vbKeyT = 84 (T key)
> - vbKeyU = 85 (U key)
> - vbKeyV = 86 (V key)
> - vbKeyW = 87 (W key)
> - vbKeyX = 88 (X key)
> - vbKeyY = 89 (Y key)
> - vbKeyZ = 90 (Z key)
> - vbKey0 = 48 (0 key)
> - vbKey1 = 49 (1 key)
> - vbKey2 = 50 (2 key)
> - vbKey3 = 51 (3 key)
> - vbKey4 = 52 (4 key)
> - vbKey5 = 53 (5 key)
> - vbKey6 = 54 (6 key)
> - vbKey7 = 55 (7 key)
> - vbKey8 = 56 (8 key)
> - vbKey9 = 57 (9 key)
>
> ### Function Keys ###
> - vbKeyF1 = 0x70 (F1 key)
> - vbKeyF2 = 0x71 (F2 key)
> - vbKeyF3 = 0x72 (F3 key)
> - vbKeyF4 = 0x73 (F4 key)
> - vbKeyF5 = 0x74 (F5 key)
> - vbKeyF6 = 0x75 (F6 key)
> - vbKeyF7 = 0x76 (F7 key)
> - vbKeyF8 = 0x77 (F8 key)
> - vbKeyF9 = 0x78 (F9 key)
> - vbKeyF10 = 0x79 (F10 key)
> - vbKeyF11 = 0x7A (F11 key)
> - vbKeyF12 = 0x7B (F12 key)
> - vbKeyF13 = 0x7C (F13 key)
> - vbKeyF14 = 0x7D (F14 key)
> - vbKeyF15 = 0x7E (F15 key)
> - vbKeyF16 = 0x7F (F16 key)
>
> ### Numberpad Keys ###
> - vbKeyNumpad0 = 0x60 (0 key)
> - vbKeyNumpad1 = 0x61 (1 key)
> - vbKeyNumpad2 = 0x62 (2 key)
> - vbKeyNumpad3 = 0x63 (3 key)
> - vbKeyNumpad4 = 0x64 (4 key)
> - vbKeyNumpad5 = 0x65 (5 key)
> - vbKeyNumpad6 = 0x66 (6 key)
> - vbKeyNumpad7 = 0x67 (7 key)
> - vbKeyNumpad8 = 0x68 (8 key)
> - vbKeyNumpad9 = 0x69 (9 key)
> - vbKeyMultiply = 0x6A (Multiplication (*) key)
> - vbKeyAdd = 0x6B (Plus (+) key)
> - vbKeySeparator = 0x6C (ENTER key)
> - vbKeySubtract = 0x6D (Minus (–) key)
> - vbKeyDecimal = 0x6E (Decimal Point (.) key)
> - vbKeyDivide = 0x6F (Division (/) key)
>

## <a id="keymask"></a>Keymask ##
> - vbAltMask = 1
> - vbCtrlMask = 2
> - vbShiftMask = 4
>

## <a id="dockmode"></a>DockMode Constants ##
> - vbDockBottom = 4
> - vbDockFill = 5
> - vbDockLeft = 1
> - vbDockNone = 0
> - vbDockRight = 3
> - vbDockTop = 2
>

## <a id="msgbox"></a>MsgBox Constants ##
> - vbAbortRetryIgnore = 2 (Abort, Retry, and Ignore buttons)
> - vbApplicationModal = 0 (Application modal message box (default))
> - vbCritical = 16 (Critical message)
> - vbDefaultButton1 = 0 (First button is default (default))
> - vbDefaultButton2 = 256 (Second button is default)
> - vbDefaultButton3 = 512 (Third button is default)
> - vbDefaultButton4 = 768 (Fourth button is default)
> - vbExclamation = 48 (Warning message)
> - vbInformation = 64 (Information message)
> - vbMsgBoxHelpButton = 16384 (Adds Help button to the message box)
> - vbMsgBoxRight = 524288 (Text is right aligned)
> - vbMsgBoxRtlReading = 1048576 (Specifies text should appear as right-to-left reading on Hebrew and Arabic systems)
> - VbMsgBoxSetForeground = 65536 (Specifies the message box window as the foreground window)
> - vbOKCancel = 1 (OK and Cancel buttons)
> - vbOKOnly = 0 (OK button only (default))
> - vbQuestion = 32 (Warning query)
> - vbRetryCancel = 5 (Retry and Cancel buttons)
> - vbSystemModal = 4096 (System modal message box)
> - vbYesNo = 4 (Yes and No buttons)
> - vbYesNoCancel = 3 (Yes, No, and Cancel buttons)
>

## <a id="msgboxreturn"></a>MsgBox Return Value Constants ##
> - vbAbort = 3 (Abort button was pressed)
> - vbCancel = 2 (Cancel button was pressed)
> - vbIgnore = 5 (Ignore button was pressed)
> - vbNo = 7 (No button was pressed)
> - vbOK = 1 (OK button was pressed)
> - vbRetry = 4 (Retry button was pressed)
> - vbYes = 6 (Yes button was pressed)
>

## <a id="mousepointer"></a>Mouse Pointer Constants ##
> - vbArrow = 1 (Normal arrow)
> - vbArrowHourglass = 13 (Arrow with hourglass)
> - vbArrowQuestion = 14 (Arrow with question mark)
> - vbCrosshair = 2 (Cross)
> - vbCustom = 99 (Custom icon specified by the MouseIcon property)
> - vbDefault = 0 (The operating decides what mouse pointer to use.)
> - vbHourglass = 11 (Hourglass)
> - vbIbeam = 3 (I-beam)
> - vbIconPointer = 4 (Icon)
> - vbNoDrop = 12 (No drop)
> - vbSizeAll = 15 (Size all)
> - vbSizeNESW = 6 (Size NE, SW)
> - vbSizeNS = 7 (Size N, S)
> - vbSizeNWSE = 8 (Size NW, SE)
> - vbSizePointer = 5 (Size)
> - vbSizeWE = 9 (Size W, E)
> - vbUpArrow = 10 (Up arrow)
>

## <a id="prborientation"></a>PrbOrientation Constants ##
> - PrbOrientationHorizontal = 0
> - PrbOrientationVertical = 1
>

## <a id="prbscrolling"></a>PrbScrolling Constants ##
> - PrbScrollingMarquee = 2
> - PrbScrollingSmooth = 1
> - PrbScrollingStandard = 0
>

## <a id="prbstate"></a>PrbState Constants ##
> - PrbStateError = 2
> - PrbStateNormal = 1
> - PrbStatePaused = 3
>

## <a id="scrollbarconstants"></a>ScrollBar Constants ##
> - vbBoth = 3
> - vbHorizontal = 1
> - vbSBNone = 0
> - vbVertical = 2
>

## <a id="shapeconstants"></a>Shape Constants ##
> - ShapeArrowDown = 10
> - ShapeArrowLeft = 7
> - ShapeArrowRight = 8
> - ShapeArrowUp = 9
> - ShapeCircle = 3
> - ShapeOval = 2
> - ShapeRectangle = 0
> - ShapeRoundedRectangle = 4
> - ShapeRoundedSquare = 5
> - ShapeSquare = 1
> - ShapeStar = 6
>

## <a id="specialfolder"></a>SpecialFolder Constants ##
> - SystemFolder = 1 (The System defined in the operating system.)
> - TemporaryFolder = 2 (The Temp defined in the operating system.)
> - WindowsFolder = 0 (The Windows folder defined in the operating system.)
>

## <a id="multiselect"></a>MultiSelect Constants ##
> - vbMultiSelectExtended - 2
> - vbMultiSelectNone - 0
> - vbMultiSelectSimple - 1
>

## <a id="tristate"></a>Tristate Constants ##
> - vbFalse = 0
> - vbTrue = -1
> - vbUseDefault = -2
>

## <a id="vartype"></a>VarType Constants ##
> - vbArray - 8192 (Array)
> - vbBoolean - 11 (Boolean)
> - vbByte - 17 (Byte)
> - vbCurrency - 6 (Currency)
> - vbDataObject - 13 (Data access object)
> - vbDate - 7 (Date)
> - vbDecimal - 14 (Decimal)
> - vbDouble - 5 (Double-precision floating-point number)
> - vbEmpty - 0 (Uninitialized (default))
> - vbError - 10 (Error)
> - vbInteger - 2 (Integer)
> - vbLong - 3 (Long integer)
> - vbNull - 1 (Contains no valid data)
> - vbObject - 9 (Object)
> - vbSingle - 4 (Single-precision floating-point number)
> - vbString - 8 (String)
> - vbUserDefinedType - 36 (Variants that contain user-defined types)
> - vbVariant - 12 (Variant (used only for arrays of variants))
>
