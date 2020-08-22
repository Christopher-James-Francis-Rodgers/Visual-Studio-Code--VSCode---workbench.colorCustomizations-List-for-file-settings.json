

# workbench.colorCustomizations--2020.08.22u0526.json





## Latest Version Of This File

The latest version of this 'workbench.colorCustomizations'
section for the settings.json file is on GitHub
repository page:

workbench.colorCustomizations-list-for-Visual-Studio-Code-file-settings.json--VS-VSCode

https:github.com/Christopher-James-Francis-Rodgers/workbench.colorCustomizations-list-for-Visual-Studio-Code-file-settings.json--VS-VSCode



## Replication Of visualstudio.com Page 'Theme Color' (2020.08.14)

This file is a replication, and re-ordering,
with some details added, of the visualstudio.com page:
'Theme Color':

https:code.visualstudio.com/api/references/theme-color

...as it existed on 2020.08.14, except that the eleven
deprecated (no longer supported) "Notification Colors"
are not included in this file; one misspelled key is
correctly spelled; one key that was renamed has its
new name being used; and two additional keys I discovered
have been added.





## Download The Latest Version Of This File

Download the latest version of this file
'workbench.colorCustomizations--yyyy.MM.dduHHmm.json" at

https:github.com/Christopher-James-Francis-Rodgers/workbench.colorCustomizations-list-for-Visual-Studio-Code-file-settings.json--VS-VSCode

by clicking on that page's upper-right green button
labeled "- Code -", and in the drop-down menu,
click "Download Zip".



### If You Are Not Seeing A Green Button Labeled "- Code -"

If you are not seeing a green button labeled "- Code -",
then your browser window is not wide enough. If after
widening your browser as far as you can, you still do not
see the green button labeled "- Code -", zoom-out to
make everything in your browser smaller by holding down
one of your two [Ctrl/Cmd] keyboard keys, and spin your
mouse wheel downward. Or, zoom-out by [Ctrl/Cmd]+[_/-].
You can zoom back in againg using [Ctrl/Cmd]+[+/=], or
you can reset the zoom level by [Ctrl/Cmd]+[)/0]





### Open The File settings.json In Visual Studio Code

The file settings.json should be located at:

(Windows) C:/Users/[YOUR_USERNAME]/AppData/Roaming/Code/User/settings.json

That file will have been automatically created if you
have made any 'settings' changes to VSCode after
installing VSCode.



### If The File settings.json Does Not Exist, Create One

If the file settings.json does not exist,
create one at the above stated location
by creating a blank text file in the folder 'User'.

Put an opening curly-brace on the first line...
"{" (without the double quotation marks);
leave the second line blank;
put a closing curly-brace on the third line...
"}" (without the double quotation marks);
then save it as "settings.json".



## Other settings.json Files

Please note that VSCode creates an additional
settings.json file for a workspace in the folder
.vscode for that workspace. If you want your color
settings to apply for all of your work in VSCode,
be sure to put them in the settings.json at the
above stated location.

An easy way to open the settings.json file from within
VSCode is the following, but I hesitate to recommend it
because under certain conditions in the past, which I
can not seem to replicate again, under which I must have
had VSCode open to a 'folder' or 'workspace', the
settings.json file which opened was not the global 'User'
settings.json file at
(Windows) C:/Users/[YOUR_USERNAME]/AppData/Roaming/Code/User/settings.json
but rather, was one in a .vscode folder, which explains
why the settings I had made previously seemed to have
disappeared, leading me to abandoning the use of VSCode
altogether. Anyway, to easily open settings.json:





## An Easy Way To Open settings.json In VSCode

Open the file settings.json file in Visual Studio Code
by first opening 'Settings' [Ctrl/Cmd]+[,]
Then click the top-right icon that displays
'Open Settings (JSON)' when you hover your mouse on it.
Note that 'that icon' only appears when the 'Settings'
have been opened first.





## Save Your Existing workbench.colorCustomizations Settings, If Any

It you alredy have any color theme key settings in the
settings.json file, listed under
'workbench.colorCustomizations',
put a copy of those keys in a temporary file for later
insertion back into settings.json.





## Delete The Section 'workbench.colorCustomizations'

Delete the section 'workbench.colorCustomizations' in
settings.json, including the closing curly-brace.





## 'Copy' This File's Contents, 'Paste' Into settings.json File

Open the file
'workbench.colorCustomizations--yyyy.MM.dduHHmm.json'.

'Select all' of this file's contents using the two-key
keyboard shortcut [Ctrl/Cmd]+[A]

Then 'Copy'. [Ctrl/Cmd]+[C]

Go to the bottom of the settings.json file,
and add a new line just above the final closing-brace "}".
Place your flashing cursor on that new line,
and 'Paste'. [Ctrl/Cmd]+[V]

'Save' the settings.json file now that you have modified it.
[Ctrl/Cmd]+[S]





## Your Former workbench.colorCustomizations Settings

If you had any workbench.colorCustomizations "Property
Key": "Value" pairs that you were already using,
copy them out of the temporary file you created earlier,
and put them as a set at the bottom of this file,
about 20-lines up from the bottom, where you see:
[Insert formerly used workbench.colorCustomizations
settings below here...

Then (after you save the settings.json file)
they will take immediate effect, and you can,
at your leisure, transfer the hexidecimal values
from your previous keys into the full listing
that includes the headings, keys, and descriptions,
and follow further below here.





## How To Fix 'Comments Are Not Allowed In JSON Files'

To view this file in Visual Studio Code (VSCode) without
warnings about comments not being allowed in json files,
in the 'Status Bar' at the bottom of the VSCode program
window, and on the right-hand side of the Status Bar,
click on "JSON", and in the pop-up context menu,
click "JSON with Comments".

Now every time you reopen settings.json it will be set as
'JSON with Comments'.

Other JSON files that you open with VSCode, and
subsequently set as 'JSON with Comments', will have to be
reset as 'JSON with Comments' each time you reopen them,
sadly.





## The 471 Keys

The visualstudio.com page 'Theme Colors'
has 480 keys, but 11 of them are deprecated
'Notification' keys which I am ignoring,
and so that leaves 469 keys.



### 469 Keys From visualstudio.com

Of those remaining 469 keys on visualstudion.com,
one was misspelled, and one has been deprecated,
and has been given a new name.



### One Misspelled Key On visualstudio.com

"notebook.cellToolbarSeperator"
is misspelled on visualstudio.com,
and I have renamed it to
"notebook.cellToolbarSeparator"



### One Renamed Key On visualstudio.com

"editorActiveLineNumber.foreground"
on visualstudio.com is deprecated,
and has now been renamed to
"editorLineNumber.activeForeground"



### 2 Additional Keys I Have Discovered By Chance

- editor.onTypeRenameBackground
- notebook.symbolHighlightBackground

My list of 471 keys also includes two additional keys
that I discovered when I cross-referenced the
469 keys from visuslstudio.com against the keys
that are revealed after I set my theme to
'Dark+ (Default Dark)', then opened the
Command Palette [Ctrl/Cmd][Shift]+[P],
and then typed-in/clicked: "Developer: Generate Color
Theme From Current Settings"

I do wonder if additional keys exist which
I have not stumbled across.



## 3 Of 471 Keys Have No Description When Hovered Upon

When a key is un-commented in the file settings.json,
and it is hovered upon by the mouse pointer,
a brief pop-up description is displayed.

Note that if multiple uncommented instances
of the same key exist in the settings.json file,
only the last instance displays the description.

These three keys from the visualstudio.com page,
however, do not display a description when
hovered upon:

- activityBar.dropBackground
- notebook.focusedCellShadow
- panel.dropBackground

I do not know what the implications are of the lack
of a hovered description, and I have not established
whether or not those three keys are valid or not.



## Keys You Put In settings.json Take Precedence

When you put "Property Key": "Value" color settings
into the settings.json file, they override the colors
of your active theme.

They do Not, however, have any control over
the syntax/ semantic colorization of your code.





## Syntax/ Semantic Colors Of Your Code

The 471 keys color settings do not affect the
multi-color variation of the numbers, symbols,
and words of your code.

Those variations are based on the syntax, or semantics
of the numbers, symbols, and words.

Your code's varying text colorization is determined
by Syntax/ Semantic rules set forth by the Theme
you are using. Those Theme rules may themselves then
be overridden by extensions you have installed
that attend to that syntax/semantic colorizing.

If and when I become inclined to address semantic/ syntax
coloring, I will start with re-watching the video:

(YouTube:) "VS Code Change Any Tag Color. Edit Custom
Syntax Colors (No extension)"

https:www.youtube.com/watch?v=Su-cNLe0dgw





## I Recommend The Extension 'Color Vision'

That extension puts a big box with a color sample
in front of each color declaration, even when the
color declaration is commented-out.





## Keys Use A Hexadecimal Format

Hexadecimal color notations supported:
#rgb, #rgba, #rrggbb, #rrggbbaa.
Upper-case is allowed, but I never use it:
#RGB, #RGBA, #RRGGBB and #RRGGBBAA.

Hexadecimal values must be...
(0-9, a-f, A-F)



## Alpha-Value - Opacity

The "a" of the color format "#rgba"
(or the "aa" of "#rrggbbaa")
is the 'Alpha-Value',
which is the level of 'Opacity',
and which means its level of visibility.

If the optional alpha-value is omitted,
then the alpha-value defaults to "f", or "ff",
which is fully opaque (visibility), and no transparency.

If an alpha-value is set to "0", or "00",
the color will be fully transparent, and will not be seen,
which is true for all color declarations, not just
background colors.

As another example, the 'bf' of "#000000bf" will render
'black' with 75% opacity (visibility), and 25% transparency.



## Opacity Alpha-Values Too High, or Omitted
## For Background Colors May Conflict

The alpha-value is optional, in that the color will work
if the alpha-value is omitted, but the alpha-value
should always be used for background colors which target
text characters that will at times also targeted
by additional background color settings.

An example of that is when a search result
('Find/Replace' result) is displaying a distinct
background color, and then you 'select' a portion
of that 'Find/Replace' text.

Then the text you have selected is being targeted by the
background color of both the 'search result' declaration,
and the 'selection' declaration.

When one, or both of those background color values
has its opacity (visibility) alpha-value
set too high (too close to 'f' or 'ff'),
or if the alpha-value is omitted by you,
(which then sets the opacity to its default of
'fully-on',) you risk having one of the two background
colors obscuring the other.





## Applying a New Color Setting: 'Save' and/or 'Reload'

After you change a color setting, you will need to,
at a minimum, 'Save' the settings.json file to see the
effects of your efforts. Save: [Ctrl/Cmd]+[S]

For some settings, you will have to 'Reload'
Visual Studio Code for the new setting to take effect.





## I Recommend the Extension 'Reload'

While it is true that you can 'reload' VSCode
by shutting down VSCode, and restarting it,
I have found that the easiest way is by installing
the extension "Reload". All that that extension does is
put a button labeled 'Reload' in the bottom right of the
VSCode program window, in the 'status bar', which,
when clicked, reloads VSCode for you.

Then, after VSCode shuts down, it automatically restarts,
and everything is put back as it was before the 'Reload'.

The 'Reload' keyboard shortcut that comes built-in to
VSCode [Ctrl/Cmd]+[R] was not working for me, so I am
happy, happy to have the extension 'Reload'. Nice, nice,
very nice.





## Redundant "Property Key" Declarations

When a Property Key is repeated in the file
settings.json, it will yield a 'warning' to that
effect, but the last occurrence will take affect.

Each valid Property Key in the settings.json file that is
not commented out, when hovered upon, will give you
a brief pop-up description. If a Property Key is repeated,
the pop-up description will only display
when you hover on the last occurrence of it.





## Your Former workbench.colorCustomizations Settings

If you had any workbench.colorCustomizations "Property
Key": "Value" pairs that you were already using, you
can put them as a set at the bottom of this file,
about 20-lines up from the bottom, where you see:
[Insert formerly used workbench.colorCustomizations
settings below here...

Then (after you save the settings.json file)
they will take immediate effect, and you can,
at your leisure, transfer the hexidecimal values
from your previous keys into the full listing above.





## Extension Colors

The following information is quoted from the bottom
of the visualstudio.com 'Theme Colors' page. If it
has any meaning to you, then that is more than it has
for me as yet.

[Quote]
Color ids can also be contributed by extensions through the
'color contribution point'
[https:code.visualstudio.com/api/references/contribution-points#contributes.colors]

These colors also appear when using code complete in the
workbench.colorCustomizations settings and the color
theme definition file. Users can see what colors an
extension defines in the 'extension contributions'
[https:code.visualstudio.com/docs/editor/extension-gallery#_extension-details]
tab.
[End: Quote]


//
"workbench.colorCustom._02_Headings_Only": {
  // (This is a Collapsible Section)
  //
  //
  //
  // Headings (a to z)
  //
  // This list is just a referrence. It lists in order
  // the headings which follow in the next section,
  // so that, if I want to, I can quickly scan it
  // in the event that I am trying to guess where a 
  // setting might be hiding from me.
  //
  //
  //
  // Activity Bar
  //
  // Badge
  //
  // Bracket and Brace Matching Pair
  //
  // Breadcrumb
  //
  // Button - Control Buttons
  //
  // Checkbox Widget
  //
  // CodeLens - Editor Pane
  //
  // Contrast Border
  //
  // Current Line - Editor Pane
  //
  // Cursor - Editor Pane
  //
  // Debug
  //
  // Debug Exception Widget
  //
  // Debug Icons
  //
  // Diff Editor
  //
  // Dropdown Control
  //
  // Editor Pane - Background and Foreground
  //
  // Errors, Descriptions, Information, and Warnings
  //
  // Extensions Badge and Buttons
  //
  // Find/Replace - Editor Pane
  //
  // Focus Border
  //
  // Folding - Editor Pane
  //
  // Foreground Defaults
  //
  // Git
  //
  // Group Header and Tabs
  //
  // Gutter - Editor Pane
  //
  // Hover Highlight - Editor Pane
  //
  // Image Preview
  //
  // Indent Guide - Editor Pane
  //
  // Input Control
  //
  // Lightbulb - Editor Pane
  //
  // Line Number - Editor Pane
  //
  // Link - Editor Pane
  //
  // List and Tree
  //
  // Marker - Editor Pane
  //
  // Menu Bar
  //
  // Merge Conflict
  //
  // Minimap
  //
  // Notebook
  //
  // Notification
  //
  // Panel
  //
  // Peek View
  //
  // Progress Bar
  //
  // Quick Picker
  //
  // Range Highlight - Editor Pane
  //
  // Rename onType
  //
  // Rulers - Editor Pane (Vertical)
  //
  // Scrollbar Control
  //
  // Scrollbar Overview Ruler - Editor Pane
  //
  // Search Editor - Editor Pane
  //
  // Selection
  //
  // Settings Editor
  //
  // Side Bar
  //
  // Snippet
  //
  // Source Control
  //
  // Status Bar
  //
  // Symbol Highlight - Editor Pane
  //
  // Symbol Icons
  //
  // Tabs (See: 'Group Header and Tabs')
  //
  // Terminal (Integrated)
  //
  // Text
  //
  // Title Bar
  //
  // Unused Source Code - Editor Pane
  //
  // Welcome Page
  //
  // White Space - Editor Pane
  //
  // Widget
  //
  // Window Border
  //
  // Word Highlight - Editor Pane
  //
  //
  //
  //
  //
},
// End: "workbench.colorCustom._02_myHeadings"
//
//
//
"workbench.colorCustomizations": {
  // (This is a Collapsible Section)
  //
  //
  //
  // The 471 Active Color Theme Key Settings:
  // Headings, Keys, and Descriptions
  //
  //
  //
  //
  //
  // Pre-set As Red
  //
  // Each of the 471 keys below have been pre-set to the
  // color red, so that if you uncomment the line for 
  // a key, and then save this file, you can immediately
  // identify which elemenst that key affects by seeing
  // which elements have turned red.
  // 
  //
  //
  //
  //
  //
  // Activity Bar
  //
  // The Activity Bar is the vertical column of icons,
  // which by default is on the far left-hand side of the
  // VSCode program window, but which can also be hidden,
  // or can be moved to the far-right of the program window.
  //
  // Each Activity Bar icon at the top, when clicked,
  // toggles the 'Sidebar' on and off for that icon.
  //
  // Each Activity Bar icon at the bottom, when clicked,
  // opens a Context Menu for that icon.
  //
  //
  // Show 'Activity Bar' When Hidden
  //
  // To 'show' the Activity Bar when it is 'hidden',
  // click the main-menu item "View" > "Appearance"
  // > "Show Activity Bar". That puts a check-mark
  // in front of 'Show Activity Bar'.
  //
  //
  // Close 'Side Bar' When 'Activity Bar' Is Hidden
  //
  // Note that if the Side Bar is showing when you toggle
  // the Activity Bar 'off', the Side Bar remains open.
  //
  // To close the Side Bar when the Activity Bar is hidden,
  // do one of the following:
  // - [Ctrl/Cmd]+[B], to toggle the Side Bar on/off.
  // - Right-click the Side Bar's title-bar, and
  // click "Hide Side Bar".
  // - main-menu: "View" > "Appearance"
  // > "Show Side Bar".
  // That will toggle 'off' the check-mark in front
  // of 'Show Side Bar'.
  //
  //
  //
  // "activityBar.activeBackground": "#660000ff",
  // Activity Bar background color
  // for the active element.
  //
  // "activityBar.activeBorder": "#bb0000",
  // Activity Bar active indicator border color.
  //
  // "activityBar.activeFocusBorder": "#bb0000",
  // Activity bar focus border color for the active item.
  //
  // "activityBar.background": "#660000ff",
  // Activity Bar background color.
  //
  // "activityBar.border": "#bb0000",
  // Activity Bar border color with the Side Bar.
  //
  // "activityBar.dropBackground": "#660000ff",
  // Drag and drop feedback color for the Activity Bar items.
  // No hover description.
  //
  // "activityBar.dropBorder": "#bb0000",
  // Drag and drop feedback color for the activity bar items.
  // The activity bar shows on the far left or right,
  // and the five icons at the top are allowed to have their
  // ordering changed by dragging/dropping them up and down.
  //
  // "activityBar.foreground": "#ff0000",
  // Activity Bar foreground color
  // (for example used for the icons).
  //
  // "activityBar.inactiveForeground": "#ff0000",
  // Activity Bar item foreground color when it is inactive.
  //
  // "activityBarBadge.background": "#660000ff",
  // Activity notification badge background color.
  //
  // "activityBarBadge.foreground": "#ff0000",
  // Activity notification badge foreground color.
  //
  //
  //
  //
  //
  // Badge
  //
  // Badges are small information labels, for example,
  // search results count.
  //
  //
  //
  // "badge.background": "#660000ff",
  // Badge background color.
  //
  // "badge.foreground": "#ff0000",
  // Badge foreground color.
  //
  //
  //
  //
  //
  // Bracket and Brace Matching Pair
  //
  // Curly-braces "{}", and Square-brackets "[]"
  // come in pairs, and can contain many lines
  // of code between the 'opening' one, and the
  // 'closing' one. Curly-braces often contain
  // nested pairs of curly-braces and
  // square-brackets.
  //
  // To help you keep track of which opening
  // brace or bracket goes with which closing one,
  // if you click on one, its partner will become
  // highlighted.
  //
  // Also, a box can be automatically drawn that
  // connects the 'opening' brace or bracket with
  // its 'closing' one.
  //
  // I recommend the extension 'Bracket Pair Colorizer 2',
  // which alternates the color of a nested pair so that
  // it is easier to distinguish from its parent.
  // And it draws a bow which color matches its containing
  // braces or brackets.
  //
  //
  //
  // "editorBracketMatch.background": "#660000ff",
  // Background color behind matching brackets.
  //
  // "editorBracketMatch.border": "#bb0000",
  // Color for matching brackets box.
  //
  //
  //
  //
  //
  // Breadcrumb
  //
  // The breadcrumb navigation path is along the top
  // of the editor page for each 'group' of files, and
  // is just under the group's 'tabs'.
  //
  //
  //
  // "breadcrumb.activeSelectionForeground": "#ff0000",
  // Color of selected breadcrumb items.
  //
  // "breadcrumb.background": "#660000ff",
  // Background color of breadcrumb items.
  //
  // "breadcrumb.focusForeground": "#ff0000",
  // Color of focused breadcrumb items.
  //
  // "breadcrumb.foreground": "#ff0000",
  // Color of breadcrumb items.
  //
  // "breadcrumbPicker.background": "#660000ff",
  // Background color of breadcrumb item picker.
  //
  //
  //
  //
  //
  // Button - Control Buttons
  //
  // Buttons: For example, see the 'Open Folder' button,
  // and the 'Clone Repository' button, both of which are
  // in the 'Side Bar' that opens with the 'Activity Bar'
  // icon "Source Control".
  //
  // In the 'Side Bar' that opens with the 'Activity Bar'
  // icon "Run", the button "Run and Debug" is disabled
  // when no folder is opened, and that button's background
  // color and foreground (text) color are different than
  // buttons that are not disabled.
  //
  //
  //
  // "button.background": "#660000ff",
  // Button background color.
  //
  // "button.foreground": "#ff0000",
  // Button foreground color.
  //
  // "button.hoverBackground": "#660000ff",
  // Button background color when hovering.
  //
  // "button.secondaryBackground": "#660000ff",
  // Secondary button background color.
  //
  // "button.secondaryForeground": "#ff0000",
  // Secondary button foreground color.
  //
  // "button.secondaryHoverBackground": "#660000ff",
  // Secondary button background color when hovering.
  //
  //
  //
  //
  //
  // Checkbox Widget
  //
  //
  //
  // "checkbox.background": "#660000ff",
  // Background color of checkbox widget.
  //
  // "checkbox.border": "#bb0000",
  // Border color of checkbox widget.
  //
  // "checkbox.foreground": "#ff0000",
  // Foreground color of checkbox widget.
  //
  //
  //
  //
  //
  // CodeLens - Editor Pane
  //
  //
  //
  // "editorCodeLens.foreground": "#ff0000",
  // Foreground color of an editor CodeLens.
  //
  //
  //
  //
  //
  // Contrast Border
  //
  // The Contrast Borders add an additional border
  // around some UI (non-terminal) items.
  //
  //
  //
  // "contrastActiveBorder": "#bb0000",
  // - Dotted border around inactive left-column
  // 'Activity bar' ('Side bar') items when hovered;
  // and a solid border when 'active'.
  // - Dotted border just inside inactive Editor Pane Tabs,
  // upon hover; and a solid border when 'active'.
  //
  // "contrastBorder": "#bb0000",
  // - The border of the drop-down 'Find/Replace' box
  // in the Editor Pane.
  // - A separator in the Tab area for each Editor Pane group.
  // The separator is to the right of the Tabs,
  // and to the left of the upper-right icons.
  // - The bottom-border of the breadcrumbs,
  // which is also the upper-border of the editing area.
  // - The vertical border between the Activity Bar (or the
  // Side Bar, when open), and the adjacent Editor Pane.
  //
  //
  //
  //
  //
  // Current Line - Editor Pane
  //
  // The current line is typically shown as either
  // background highlight, or with a border (not both).
  //
  //
  //
  // "editor.lineHighlightBackground": "#660000ff",
  // Background color for the highlight of line
  // at the cursor position.
  //
  // "editor.lineHighlightBorder": "#bb0000",
  // Background color for the border around the line
  // at the cursor position.
  //
  //
  //
  //
  //
  // Cursor - Editor Pane
  //
  // (See also: 'Current Line - Editor Pane')
  //
  //
  //
  // "editorCursor.background": "#660000ff",
  // The background color of the editor cursor.
  // Allows customizing the color of a character
  // overlapped by a block cursor.
  //
  // "editorCursor.foreground": "#ff0000",
  // Color of the editor cursor.
  //
  //
  //
  //
  //
  // Debug
  //
  // (See also: 'Debug Exception Widget', and 'Debug Icons')
  //
  // Debugging can be done via the activity bar item 'Run'
  // [Ctrl/Cmd][Shift]+[D].
  //
  //
  //
  // "debugTokenExpression.boolean": "#ff0000",
  // Foreground color for booleans in debug views
  //
  // "debugTokenExpression.error": "#ff0000",
  // Foreground color for expression errors
  // in debug views
  //
  // "debugTokenExpression.name": "#ff0000",
  // Foreground color for the token names shown
  // in debug views (ie. the Variables or Watch view)
  //
  // "debugTokenExpression.number": "#ff0000",
  // Foreground color for numbers in debug views
  //
  // "debugTokenExpression.string": "#ff0000",
  // Foreground color for strings in debug views
  //
  // "debugTokenExpression.value": "#ff0000",
  // Foreground color for the token values shown
  // in debug views
  //
  // "debugToolBar.background": "#660000ff",
  // Debug toolbar background color.
  //
  // "debugToolBar.border": "#bb0000",
  // Debug toolbar border color.
  //
  // "debugView.exceptionLabelBackground": "#660000ff",
  // Background color for a label shown
  // in the CALL STACK view when the debugger breaks
  // on an exception
  //
  // "debugView.exceptionLabelForeground": "#ff0000",
  // Foreground color for a label shown
  // in the CALL STACK view when the debugger breaks
  // on an exception
  //
  // "debugView.stateLabelBackground": "#660000ff",
  // Background color for a label in the
  // CALL STACK view showing the current session's
  // or thread's state
  //
  // "debugView.stateLabelForeground": "#ff0000",
  // Foreground color for a label in the
  // CALL STACK view showing the current session's
  // or thread's state
  //
  // "debugView.valueChangedHighlight": "#660000ff",
  // Color used to highlight value changes
  // in the debug views (ie. in the Variables view)
  //
  // "editor.focusedStackFrameHighlightBackground": "#660000ff",
  // Background color of the focused stack frame highlight
  // in the editor.
  //
  // "editor.stackFrameHighlightBackground": "#660000ff",
  // Background color of the top stack frame highlight
  // in the editor.
  //
  //
  //
  //
  //
  // Debug Exception Widget
  //
  // The Debug Exception widget is a peek view that shows
  // in the editor when debug stops at an exception.
  //
  //
  //
  // "debugExceptionWidget.background": "#660000ff",
  // Exception widget background color.
  //
  // "debugExceptionWidget.border": "#bb0000",
  // Exception widget border color.
  //
  //
  //
  //
  //
  // Debug Icons
  //
  //
  //
  // "debugConsole.errorForeground": "#ff0000",
  // Foreground color for error messages
  // in debug REPL console.
  //
  // "debugConsole.infoForeground": "#ff0000",
  // Foreground color for info messages
  // in debug REPL console.
  //
  // "debugConsole.sourceForeground": "#ff0000",
  // Foreground color for source filenames
  // in debug REPL console.
  //
  // "debugConsole.warningForeground": "#ff0000",
  // Foreground color for warning messages
  // in debug REPL console.
  //
  // "debugConsoleInputIcon.foreground": "#ff0000",
  // Foreground color for debug console input marker icon.
  //
  // "debugIcon.breakpointCurrentStackframeForeground": "#ff0000",
  // Icon color for the current breakpoint stack frame.
  //
  // "debugIcon.breakpointDisabledForeground": "#ff0000",
  // Icon color for disabled breakpoints.
  //
  // "debugIcon.breakpointForeground": "#ff0000",
  // Icon color for breakpoints.
  //
  // "debugIcon.breakpointStackframeForeground": "#ff0000",
  // Icon color for all breakpoint stack frames.
  //
  // "debugIcon.breakpointUnverifiedForeground": "#ff0000",
  // Icon color for unverified breakpoints.
  //
  // "debugIcon.continueForeground": "#ff0000",
  // Debug toolbar icon for continue.
  //
  // "debugIcon.disconnectForeground": "#ff0000",
  // Debug toolbar icon for disconnect.
  //
  // "debugIcon.pauseForeground": "#ff0000",
  // Debug toolbar icon for pause.
  //
  // "debugIcon.restartForeground": "#ff0000",
  // Debug toolbar icon for restart.
  //
  // "debugIcon.startForeground": "#ff0000",
  // Debug toolbar icon for start debugging.
  //
  // "debugIcon.stepBackForeground": "#ff0000",
  // Debug toolbar icon for step back.
  //
  // "debugIcon.stepIntoForeground": "#ff0000",
  // Debug toolbar icon for step into.
  //
  // "debugIcon.stepOutForeground": "#ff0000",
  // Debug toolbar icon for step over.
  //
  // "debugIcon.stepOverForeground": "#ff0000",
  // Debug toolbar icon for step over.
  //
  // "debugIcon.stopForeground": "#ff0000",
  // Debug toolbar icon for stop.
  //
  //
  //
  //
  //
  // Diff Editor
  //
  // For coloring inserted and removed text, use either
  // a background or a border color but not both.
  //
  //
  //
  // "diffEditor.border": "#bb0000",
  // Border color between the two text editors.
  //
  // "diffEditor.diagonalFill": "#ff0000",
  // Color of the diff editor's diagonal fill.
  // The diagonal fill is used in side-by-side diff views.
  //
  // "diffEditor.insertedTextBackground": "#660000ff",
  // Background color for text that got inserted. The color
  // must be sufficiently transparent (not too opaque)
  // so as to not hide underlying background decorations.
  //
  // "diffEditor.insertedTextBorder": "#bb0000",
  // Outline color for the text that got inserted.
  //
  // "diffEditor.removedTextBackground": "#660000ff",
  // Background color for text that got removed. The color
  // must be sufficiently transparent (not too opaque)
  // so as to not hide underlying background decorations.
  //
  // "diffEditor.removedTextBorder": "#bb0000",
  // Outline color for text that got removed.
  //
  //
  //
  //
  //
  // Dropdown Control
  //
  // A set of colors for all Dropdown widgets such as
  // in the Integrated Terminal or the Output panel.
  // Note that the Dropdown control
  // is not used on macOS currently.
  //
  //
  //
  // "dropdown.background": "#660000ff",
  // Dropdown background.
  //
  // "dropdown.border": "#bb0000",
  // Dropdown border.
  //
  // "dropdown.foreground": "#ff0000",
  // Dropdown foreground.
  //
  // "dropdown.listBackground": "#660000ff",
  // Dropdown list background.
  //
  //
  //
  //
  //
  // Editor Pane - Background and Foreground
  //
  // The following editor colors are used within the editor panes
  // where your code is placed, but they do not relate
  // to syntax or semantic highlighting.
  //
  // The token colors used for syntax or semantic highlighting
  // are based on the language grammar installed, and are
  // defined by the Color Theme. You can customize the syntax
  // or semantic colors with the 'editor.tokenColorCustomizations'
  // settings. See 'Customizing a Color Theme'...
  // https://code.visualstudio.com/docs/getstarted/themes#_customizing-a-color-theme
  // ...for details on updating a Color Theme,
  // and the available token types.
  //
  //
  //
  // "editor.background": "#660000ff",
  // Editor background color.
  //
  // "editor.foreground": "#ff0000",
  // Editor default foreground color.
  //
  // "editorPane.background": "#660000ff",
  // Background color of the editor pane visible on the left
  // and right side of the centered editor layout.
  //
  //
  //
  //
  //
  // Errors, Descriptions, Information, and Warnings
  //
  // (See also: 'Editor Marker', which shows when navigating
  // to errors and warnings in the editor.)
  //
  //
  //
  // "descriptionForeground": "#ff0000",
  // Foreground color for description text
  // providing additional information, for example
  // for a label.
  //
  // "editorError.border": "#bb0000",
  // Border color of error boxes in the editor.
  //
  // "editorError.foreground": "#ff0000",
  // Foreground color of error squiggles
  // in the Editor Panes.
  //
  // "editorHint.border": "#bb0000",
  // Border color of hint boxes
  // in the Editor Panes.
  //
  // "editorHint.foreground": "#ff0000",
  // Foreground color of hints
  // in the Editor Panes.
  //
  // "editorInfo.border": "#bb0000",
  // Border color of info boxes
  // in the Editor Panes.
  //
  // "editorInfo.foreground": "#ff0000",
  // Foreground color of info squiggles
  // in the Editor Panes.
  //
  // "editorWarning.border": "#bb0000",
  // Border color of warning boxes
  // in the Editor Panes.
  //
  // "editorWarning.foreground": "#ff0000",
  // Foreground color of warning squiggles
  // in the Editor Panes.
  //
  // "errorForeground": "#ff0000",
  // Overall foreground color for error messages
  // that are not related to the code in the Editor Panes.
  // This color is only used if it is not overridden
  // by another component.
  //
  // "problemsErrorIcon.foreground": "#ff0000",
  // The color used for the problems error icon.
  //
  // "problemsInfoIcon.foreground": "#ff0000",
  // The color used for the problems info icon.
  //
  // "problemsWarningIcon.foreground": "#ff0000",
  // The color used for the problems warning icon.
  //
  //
  //
  //
  //
  // Extensions Badge and Buttons
  //
  //
  //
  // "extensionBadge.remoteBackground": "#660000ff",
  // Background color for the remote badge
  // in the extensions view.
  //
  // "extensionBadge.remoteForeground": "#ff0000",
  // Foreground color for the remote badge
  // in the extensions view.
  //
  // "extensionButton.prominentBackground": "#660000ff",
  // Extension view button background color.
  //
  // "extensionButton.prominentForeground": "#ff0000",
  // Extension view button foreground color
  // (for example Install button).
  //
  // "extensionButton.prominentHoverBackground": "#660000ff",
  // Extension view button background hover color.
  //
  //
  //
  //
  //
  // Find/Replace - Editor Pane
  //
  // Find colors depend on the current find string
  // in the Find/Replace dialog.
  //
  //
  //
  // "editor.findMatchBackground": "#660000ff",
  // Color of the current search match.
  //
  // "editor.findMatchBorder": "#bb0000",
  // Border color of the current search match.
  //
  // "editor.findMatchHighlightBackground": "#660000ff",
  // Color of the other search matches. The color
  // must sufficiently transparent (not too opaque)
  // so as to not hide underlying background decorations.
  //
  // "editor.findMatchHighlightBorder": "#bb0000",
  // Border color of the other search matches.
  //
  // "editor.findRangeHighlightBackground": "#660000ff",
  // Color the range limiting the search
  // (Enable 'Find in Selection' in the find widget).
  // The color must be sufficiently transparent (not too opaque)
  // so as to not hide underlying background decorations.
  //
  // "editor.findRangeHighlightBorder": "#bb0000",
  // Border color the range limiting the search
  // (Enable 'Find in Selection' in the find widget).
  //
  //
  //
  //
  //
  // Focus Border
  //
  // "focusBorder": "#bb0000",
  // Overall border color for focused elements.
  // This color is only used if not overridden by
  // another component.
  //
  //
  //
  //
  //
  //
  // Folding - Editor Pane
  //
  //
  //
  // "editor.foldBackground": "#660000ff",
  // Background color for folded ranges. The color must be
  // sufficiently transparent (not too opaque) so as to
  // not hide underlying background decorations.
  //
  //
  //
  //
  //
  // Group Header and Tabs
  //
  // Editor Groups are the containers of editors.
  // There can be many editor groups.
  // A Tab is the container of an editor.
  // Multiple Tabs can be opened in one editor group.
  //
  //
  //
  // "editorGroup.border": "#bb0000",
  // Color to separate multiple editor groups from each other.
  //
  // "editorGroup.dropBackground": "#660000ff",
  // Background color when dragging editors around.
  //
  // "editorGroup.emptyBackground": "#660000ff",
  // Background color of an empty editor group.
  //
  // "editorGroup.focusedEmptyBorder": "#bb0000",
  // Border color of an empty editor group that is focused.
  //
  // "editorGroupHeader.border": "#bb0000",
  // Border color between editor group header,
  // and editor (below breadrcumbs if enabled).
  //
  // "editorGroupHeader.noTabsBackground": "#660000ff",
  // Background color of the editor group title header
  // when Tabs are disabled. The Tabs are disabled
  // when you have changed the default setting from 'true'
  // to: "workbench.editor.showTabs": false,
  //
  // "editorGroupHeader.tabsBackground": "#660000ff",
  // Background color of the Tabs container.
  //
  // "editorGroupHeader.tabsBorder": "#bb0000",
  // Border color below the editor tabs control
  // when tabs are enabled.
  //
  // "tab.activeBackground": "#660000ff",
  // Active Tab background color in an active group.
  //
  // "tab.activeBorder": "#bb0000",
  // Bottom border for the active tab.
  // Bottom-border only of the active tab
  // in the active group. I prefer this color to
  // closely match the editor pane color (black),
  // and have the active tab BG color match the
  // editor pane which has current focus.
  //
  // "tab.activeBorderTop": "#bb0000",
  // Top border for the active tab.
  // Top-border only of the active tab
  // in the active group only.
  //
  // "tab.activeForeground": "#ff0000",
  // Active Tab foreground color in an active group.
  //
  // "tab.activeModifiedBorder": "#bb0000",
  // Border on the top of modified (dirty) active tabs
  // in an active group.
  //
  // "tab.border": "#bb0000",
  // Border to separate Tabs from each other.
  //
  // "tab.hoverBackground": "#660000ff",
  // Tab background color when hovering
  // Any hovered tab in active group,
  // background.
  //
  // "tab.hoverBorder": "#bb0000",
  // Border to highlight tabs when hovering
  // Any hovered tab in active group,
  // bottom border only.
  //
  // "tab.hoverForeground": "#ff0000",
  // Tab foreground color when hovering
  // Any hovered tab in the active group,
  // including the active tab.
  //
  // "tab.inactiveBackground": "#660000ff",
  // Inactive Tab background color.
  //
  // "tab.inactiveForeground": "#ff0000",
  // Inactive Tab foreground color
  // in an active group.
  //
  // "tab.inactiveModifiedBorder": "#bb0000",
  // Border on the top of modified (dirty) inactive tabs
  // in an active group.
  //
  // "tab.unfocusedActiveBackground": "#660000ff",
  // Active Tab background color in an inactive editor group.
  // Unfocused means Not in active group.
  //
  // "tab.unfocusedActiveBorder": "#bb0000",
  // Bottom border for the active tab
  // in an inactive editor group.
  // Unfocused means Not in active group.
  //
  // "tab.unfocusedActiveBorderTop": "#bb0000",
  // Top border for the active tab
  // in an inactive editor group
  // Unfocused means Not in active group.
  //
  // "tab.unfocusedActiveForeground": "#ff0000",
  // Active tab foreground color
  // in an inactive editor group.
  // Unfocused means Not in active group.
  //
  // "tab.unfocusedActiveModifiedBorder": "#bb0000",
  // Border on the top of modified (dirty) active tabs
  // in an unfocused group.
  // Unfocused means Not in active group.
  //
  // "tab.unfocusedHoverBackground": "#660000ff",
  // Tab background color in an unfocused group
  // when hovering
  // Unfocused means Not in active group.
  //
  // "tab.unfocusedHoverBorder": "#bb0000",
  // Border to highlight tabs in an unfocused group
  // when hovering
  // Unfocused means Not in active group.
  //
  // "tab.unfocusedHoverForeground": "#ff0000",
  // Tab foreground color in an unfocused group
  // when hovering
  // Unfocused means Not in active group.
  //
  // "tab.unfocusedInactiveBackground": "#660000ff",
  // Inactive Tab background color
  // in an unfocused group
  // Unfocused means Not in active group.
  //
  // "tab.unfocusedInactiveForeground": "#ff0000",
  // Inactive tab foreground color
  // in an inactive editor group.
  // Unfocused means Not in active group.
  //
  // "tab.unfocusedInactiveModifiedBorder": "#bb0000",
  // Border on the top of modified (dirty) inactive tabs
  // in an unfocused group.
  // Unfocused means Not in active group.
  //
  //
  //
  //
  //
  // Foreground Defaults
  //
  //
  //
  // "foreground": "#ff0000",
  // Default foreground color when not overridden
  // by a component.
  //
  // "icon.foreground": "#ff0000",
  // Default foreground color for icons in the workbench,
  // when not overridden by a component.
  //
  //
  //
  //
  //
  // Git
  //
  //
  //
  // "gitDecoration.addedResourceForeground": "#ff0000",
  // Color for added Git resources. Used for file labels
  // and the SCM viewlet.
  //
  // "gitDecoration.conflictingResourceForeground": "#ff0000",
  // Color for conflicting Git resources. Used for file labels
  // and the SCM viewlet.
  //
  // "gitDecoration.deletedResourceForeground": "#ff0000",
  // Color for deleted Git resources. Used for file labels
  // and the SCM viewlet.
  //
  // "gitDecoration.ignoredResourceForeground": "#ff0000",
  // Color for ignored Git resources. Used for file labels
  // and the SCM viewlet.
  //
  // "gitDecoration.modifiedResourceForeground": "#ff0000",
  // Color for modified Git resources. Used for file labels
  // and the SCM viewlet.
  //
  // "gitDecoration.submoduleResourceForeground": "#ff0000",
  // Color for submodule resources.
  //
  // "gitDecoration.untrackedResourceForeground": "#ff0000",
  // Color for untracked Git resources. Used for file labels
  // and the SCM viewlet.
  //
  //
  //
  //
  //
  // Gutter - Editor Pane
  //
  // The gutter contains the glyph margins,
  // and the line numbers:
  //
  //
  //
  // "editorGutter.addedBackground": "#660000ff",
  // Editor gutter background color for lines that are added.
  //
  // "editorGutter.background": "#660000ff",
  // Background color of the editor gutter. The gutter
  // contains the glyph margins and the line numbers.
  //
  // "editorGutter.commentRangeForeground": "#ff0000",
  // Editor gutter decoration color for commenting ranges.
  //
  // "editorGutter.deletedBackground": "#660000ff",
  // Editor gutter background color for lines that are deleted.
  //
  // "editorGutter.foldingControlForeground": "#ff0000",
  // Color of the folding control in the editor gutter.
  //
  // "editorGutter.modifiedBackground": "#660000ff",
  // Editor gutter background color for lines that are modified.
  //
  //
  //
  //
  //
  // Hover Highlight - Editor Pane
  //
  // The hover highlight color is shown behind the symbol
  // for which a hover is shown.
  //
  //
  //
  // "editor.hoverHighlightBackground": "#660000ff",
  // Highlight below the word for which a hover is shown.
  // The color must be sufficiently transparent (not too opaque)
  // so as to not hide underlying background decorations.
  //
  //
  //
  //
  //
  // Image Preview
  //
  //
  //
  // "imagePreview.border": "#bb0000",
  // Border color for image in image preview.
  //
  //
  //
  //
  //
  // Indent Guide - Editor Pane
  //
  // To see the editor indent guides,
  // set "editor.renderIndentGuides": "true".
  //
  //
  //
  // "editorIndentGuide.activeBackground": "#660000ff",
  // Color of the active editor indentation guide.
  //
  // "editorIndentGuide.background": "#660000ff",
  // Color of the editor indentation guides.
  //
  //
  //
  //
  //
  // Input Control
  //
  // Colors for input controls such as in the Search view,
  // or the Find/Replace dialog.
  //
  //
  //
  // "input.background": "#660000ff",
  // Input box background.
  //
  // "input.border": "#bb0000",
  // Input box border.
  //
  // "input.foreground": "#ff0000",
  // Input box foreground.
  //
  // "input.placeholderForeground": "#ff0000",
  // Input box foreground color for placeholder text.
  //
  // "inputOption.activeBackground": "#660000ff",
  // Background color of activated options in input fields.
  //
  // "inputOption.activeBorder": "#bb0000",
  // Border color of activated options in input fields.
  //
  // "inputOption.activeForeground": "#ff0000",
  // Foreground color of activated options in input fields.
  //
  // "inputValidation.errorBackground": "#660000ff",
  // Input validation background color for error severity.
  //
  // "inputValidation.errorBorder": "#bb0000",
  // Input validation border color for error severity.
  //
  // "inputValidation.errorForeground": "#ff0000",
  // Input validation foreground color for error severity.
  //
  // "inputValidation.infoBackground": "#660000ff",
  // Input validation background color for information severity.
  //
  // "inputValidation.infoBorder": "#bb0000",
  // Input validation border color for information severity.
  //
  // "inputValidation.infoForeground": "#ff0000",
  // Input validation foreground color for information severity.
  //
  // "inputValidation.warningBackground": "#660000ff",
  // Input validation background color for information warning.
  //
  // "inputValidation.warningBorder": "#bb0000",
  // Input validation border color for warning severity.
  //
  // "inputValidation.warningForeground": "#ff0000",
  // Input validation foreground color for warning severity.
  //
  //
  //
  //
  //
  // Lightbulb - Editor Pane
  //
  //
  //
  // "editorLightBulb.foreground": "#ff0000",
  // The color used for the lightbulb actions icon.
  //
  // "editorLightBulbAutoFix.foreground": "#ff0000",
  // The color used for the lightbulb auto fix actions icon.
  //
  //
  //
  //
  //
  // Line Number - Editor Pane
  //
  //
  //
  // "editorLineNumber.activeForeground": "#ff0000",
  // Color of the active editor line number.
  //
  // "editorLineNumber.foreground": "#ff0000",
  // Color of editor line numbers.
  //
  //
  //
  //
  //
  // Link - Editor Pane
  //
  // The link color is visible when clicking on a link.
  //
  //
  //
  // "editorLink.activeForeground": "#ff0000",
  // Color of active links.
  //
  //
  //
  //
  //
  // List and Tree
  //
  // Colors for list and trees like the File Explorer.
  // An active list/tree has keyboard focus,
  // an inactive does not.
  //
  //
  //
  // "list.activeSelectionBackground": "#660000ff",
  // List/Tree background color for the selected item
  // when the list/tree is active.
  //
  // "list.activeSelectionForeground": "#ff0000",
  // List/Tree foreground color for the selected item
  // when the list/tree is active.
  //
  // "list.deemphasizedForeground": "#ff0000",
  // List/Tree foreground color for items that are deemphasized.
  //
  // "list.dropBackground": "#660000ff",
  // List/Tree drag and drop background when moving items
  // around using the mouse.
  //
  // "list.errorForeground": "#ff0000",
  // Foreground color of list items containing errors.
  //
  // "list.filterMatchBackground": "#660000ff",
  // Background color of the filtered matches in lists and trees.
  //
  // "list.filterMatchBorder": "#bb0000",
  // Border color of the filtered matches in lists and trees.
  //
  // "list.focusBackground": "#660000ff",
  // List/Tree background color for the focused item
  // when the list/tree is active.
  //
  // "list.focusForeground": "#ff0000",
  // List/Tree foreground color for the focused item
  // when the list/tree is active. An 'active' list/tree
  // has keyboard focus, but an 'inactive' one does not.
  //
  // "list.highlightForeground": "#ff0000",
  // List/Tree foreground color of the match highlights
  // when searching inside the list/tree.
  //
  // "list.hoverBackground": "#660000ff",
  // List/Tree background when hovering
  // over items using the mouse.
  //
  // "list.hoverForeground": "#ff0000",
  // List/Tree foreground when hovering
  // over items using the mouse.
  //
  // "list.inactiveFocusBackground": "#660000ff",
  // List background color for the focused item
  // when the list is inactive. An active list has
  // keyboard focus, but an inactive list does not.
  // Currently only supported in lists.
  //
  // "list.inactiveSelectionBackground": "#660000ff",
  // List/Tree background color for the selected item
  // when the list/tree is inactive.
  //
  // "list.inactiveSelectionForeground": "#ff0000",
  // List/Tree foreground color for the selected item
  // when the list/tree is inactive. An active list/tree
  // has keyboard focus, an inactive does not.
  //
  // "list.invalidItemForeground": "#ff0000",
  // List/Tree foreground color for invalid items,
  // for example an unresolved root in explorer.
  //
  // "list.warningForeground": "#ff0000",
  // Foreground color of list items containing warnings.
  //
  // "listFilterWidget.background": "#660000ff",
  // List/Tree Filter background color of typed text
  // when searching inside the list/tree.
  //
  // "listFilterWidget.noMatchesOutline": "#bb0000",
  // List/Tree Filter Widget's outline color when no match
  // is found of typed text when searching inside the list/tree.
  //
  // "listFilterWidget.outline": "#bb0000",
  // List/Tree Filter Widget's outline color of typed text
  // when searching inside the list/tree.
  //
  // "tree.indentGuidesStroke": "#ff0000",
  // Tree Widget's stroke color for indent guides.
  //
  //
  //
  //
  //
  // Marker - Editor Pane
  //
  // (See also: 'Errors, Descriptions, Information, and Warnings')
  //
  // The editor marker view shows when navigating
  // to errors and warnings in the editor
  // (Go to Next Error or Warning command).
  //
  //
  //
  // "editorMarkerNavigation.background": "#660000ff",
  // Editor marker navigation widget background.
  //
  // "editorMarkerNavigationError.background": "#660000ff",
  // Editor marker navigation widget error color.
  //
  // "editorMarkerNavigationInfo.background": "#660000ff",
  // Editor marker navigation widget info color.
  //
  // "editorMarkerNavigationWarning.background": "#660000ff",
  // Editor marker navigation widget warning color.
  //
  //
  //
  //
  //
  // Menu Bar
  //
  //
  //
  // "menu.background": "#660000ff",
  // Background color of menu items.
  //
  // "menu.border": "#bb0000",
  // Border color of menus.
  //
  // "menu.foreground": "#ff0000",
  // Foreground color of menu items.
  //
  // "menu.selectionBackground": "#660000ff",
  // Background color of the selected menu item
  // in menus.
  //
  // "menu.selectionBorder": "#bb0000",
  // Border color of the selected menu item
  // in menus.
  //
  // "menu.selectionForeground": "#ff0000",
  // Foreground color of the selected menu item
  // in menus.
  //
  // "menu.separatorBackground": "#660000ff",
  // Color of a separator menu item in menus.
  //
  // "menubar.selectionBackground": "#660000ff",
  // Background color of the selected menu item
  // in the menubar.
  //
  // "menubar.selectionBorder": "#bb0000",
  // Border color of the selected menu item in
  // the menubar.
  //
  // "menubar.selectionForeground": "#ff0000",
  // Foreground color of the selected menu item
  // in the menubar.
  //
  //
  //
  //
  //
  // Merge Conflict
  //
  // Merge conflict decorations are shown
  // when the editor contains special diff ranges.
  //
  //
  //
  // "editorOverviewRuler.commonContentForeground": "#ff0000",
  // Common ancestor overview ruler foreground
  // for inline merge conflicts.
  //
  // "editorOverviewRuler.currentContentForeground": "#ff0000",
  // Current overview ruler foreground
  // for inline merge conflicts.
  //
  // "editorOverviewRuler.incomingContentForeground": "#ff0000",
  // Incoming overview ruler foreground
  // for inline merge conflicts.
  //
  // "merge.border": "#bb0000",
  // Border color on headers and the splitter
  // in inline merge conflicts.
  //
  // "merge.commonContentBackground": "#660000ff",
  // Common ancestor content background in inline merge-conflicts.
  // The color must be sufficiently transparent (not too opaque)
  // so as to not hide underlying background decorations.
  //
  // "merge.commonHeaderBackground": "#660000ff",
  // Common ancestor header background in inline merge-conflicts.
  // The color must be sufficiently transparent (not too opaque)
  // so as to not hide underlying background decorations.
  //
  // "merge.currentContentBackground": "#660000ff",
  // Current content background in inline merge conflicts.
  // The color must be sufficiently transparent (not too opaque)
  // so as to not hide underlying background decorations.
  //
  // "merge.currentHeaderBackground": "#660000ff",
  // Current header background in inline merge conflicts.
  // The color must be sufficiently transparent (not too opaque)
  // so as to not hide underlying background decorations.
  //
  // "merge.incomingContentBackground": "#660000ff",
  // Incoming content background in inline merge conflicts.
  // The color must be sufficiently transparent (not too opaque)
  // so as to not hide underlying background decorations.
  //
  // "merge.incomingHeaderBackground": "#660000ff",
  // Incoming header background in inline merge conflicts.
  // The color must be sufficiently transparent (not too opaque)
  // so as to not hide underlying background decorations.
  //
  //
  //
  //
  //
  // Minimap
  //
  // The Minimap shows a minified version of the current file.
  //
  //
  //
  // "minimap.background": "#660000ff",
  // Minimap background color.
  //
  // "minimap.errorHighlight": "#660000ff",
  // Highlight color for errors within the editor.
  //
  // "minimap.findMatchHighlight": "#660000ff",
  // Highlight color for matches from search within files.
  //
  // "minimap.selectionHighlight": "#660000ff",
  // Highlight color for the editor selection.
  //
  // "minimap.warningHighlight": "#660000ff",
  // Highlight color for warnings within the editor.
  //
  // "minimapGutter.addedBackground": "#660000ff",
  // Minimap gutter color for added content.
  //
  // "minimapGutter.deletedBackground": "#660000ff",
  // Minimap gutter color for deleted content.
  //
  // "minimapGutter.modifiedBackground": "#660000ff",
  // Minimap gutter color for modified content.
  //
  // "minimapSlider.activeBackground": "#660000ff",
  // Minimap slider background color when clicked on.
  //
  // "minimapSlider.background": "#660000ff",
  // Minimap slider background color.
  //
  // "minimapSlider.hoverBackground": "#660000ff",
  // Minimap slider background color when hovering.
  //
  //
  //
  //
  //
  // Notebook
  //
  //
  //
  // "notebook.cellBorderColor": "#bb0000",
  // The border color for notebook cells.
  //
  // "notebook.cellHoverBackground": "#660000ff",
  // The background color of a cell when the cell is hovered.
  //
  // "notebook.cellInsertionIndicator": "#ff0000",
  // The color of the notebook cell insertion indicator.
  //
  // "notebook.cellStatusBarItemHoverBackground": "#660000ff",
  // The background color of notebook cell status bar items.
  //
  // "notebook.cellToolbarSeparator": "#bb0000",
  // The color of the separator in the cell bottom toolbar
  //
  // "notebook.focusedCellBackground": "#660000ff",
  // The background color of a cell when the cell is focused.
  //
  // "notebook.focusedCellBorder": "#bb0000",
  // The color of the cell's top and bottom border
  // when the cell is focused.
  //
  // "notebook.focusedCellShadow": "#bb0000",
  // The color of the cell shadow
  // when cells are focused.
  // No hover description.
  //
  // "notebook.focusedEditorBorder": "#bb0000",
  // The color of the notebook cell editor border.
  //
  // "notebook.outputContainerBackgroundColor": "#660000ff",
  // The Color of the notebook output container background.
  //
  // "notebook.symbolHighlightBackground": "#660000ff",
  // (Not on visualstudio.com 'Theme Color' page)
  //
  // "notebookScrollbarSlider.activeBackground": "#660000ff",
  // Notebook scrollbar slider background color
  // when clicked on.
  //
  // "notebookScrollbarSlider.background": "#660000ff",
  // Notebook scrollbar slider background color.
  //
  // "notebookScrollbarSlider.hoverBackground": "#660000ff",
  // Notebook scrollbar slider background color
  // when hovering.
  //
  // "notebookStatusErrorIcon.foreground": "#ff0000",
  // The error icon color of notebook cells
  // in the cell status bar.
  //
  // "notebookStatusRunningIcon.foreground": "#ff0000",
  // The running icon color of notebook cells
  // in the cell status bar.
  //
  // "notebookStatusSuccessIcon.foreground": "#ff0000",
  // The error icon color of notebook cells
  // in the cell status bar.
  //
  //
  //
  //
  //
  // Notification
  //
  // The 'Notification colors' in file
  // 'workbench.colorCustomizations--yyyy.MM.dduHHmm.txt'
  // only apply for Visual Studio Code versions
  // 1.21 (February 2018), and higher. If you are targeting
  // VSCode versions before the 1.21 release, those old
  // no-longer supported 'notification colors' are listed
  // online under the heading "Notification colors",
  // and underneath the latest notification color listings, at...
  // https://code.visualstudio.com/api/references/theme-color#notification-colors
  //
  // Notification toasts slide up from the bottom-right
  // of the workbench.
  //
  // Once opened in the Notification Center,
  // they are displayed in a list with a header.
  //
  //
  //
  // "notificationCenter.border": "#bb0000",
  // Notification Center border color.
  //
  // "notificationCenterHeader.background": "#660000ff",
  // Notification Center header background color.
  //
  // "notificationCenterHeader.foreground": "#ff0000",
  // Notification Center header foreground color.
  //
  // "notificationLink.foreground": "#ff0000",
  // Notification links foreground color.
  //
  // "notifications.background": "#660000ff",
  // Notification background color.
  //
  // "notifications.border": "#bb0000",
  // Notification border color separating from
  // other notifications in the Notification Center.
  //
  // "notifications.foreground": "#ff0000",
  // Notification foreground color.
  //
  // "notificationsErrorIcon.foreground": "#ff0000",
  // The color used for the notification error icon.
  //
  // "notificationsInfoIcon.foreground": "#ff0000",
  // The color used for the notification info icon.
  //
  // "notificationsWarningIcon.foreground": "#ff0000",
  // The color used for the notification warning icon.
  //
  // "notificationToast.border": "#bb0000",
  // Notification toast border color.
  //
  //
  //
  //
  //
  // Panel
  //
  // Panels are shown below the editor area and contain views
  // like Output and Integrated Terminal.
  //
  //
  //
  // "panel.background": "#660000ff",
  // Panel background color.
  //
  // "panel.border": "#bb0000",
  // Panel border color to separate the panel from the editor.
  //
  // "panel.dropBackground": "#660000ff",
  // Drag and drop feedback color for the panel title items.
  // The color should have transparency so that
  // the panel entries can still shine through.
  // No hover description.
  //
  // "panel.dropBorder": "#bb0000",
  // Drag and drop feedback color for the panel titles.
  // Panels are shown below the editor area and contain views
  // like output and integrated terminal.
  //
  // "panelInput.border": "#bb0000",
  // Input box border for inputs in the panel.
  //
  // "panelSection.border": "#bb0000",
  // Panel section border color used when multiple views
  // are stacked horizontally in the panel. Panels are
  // shown below the editor area and contain views like
  // output and integrated terminal.
  //
  // "panelSection.dropBackground": "#660000ff",
  // Drag and drop feedback color for the panel sections.
  // The color should have transparency so that
  // the panel sections can still shine through.
  // Panels are shown below the editor area and contain views
  // like output and integrated terminal.
  //
  // "panelSectionHeader.background": "#660000ff",
  // Panel section header background color. Panels are shown
  // below the editor area and contain views like output and
  // integrated terminal.
  //
  // "panelSectionHeader.border": "#bb0000",
  // Panel section header border color used when multiple views
  // are stacked vertically in the panel. Panels are
  // shown below the editor area and contain views like
  // output and integrated terminal.
  //
  // "panelSectionHeader.foreground": "#ff0000",
  // Panel section header foreground color. Panels are shown
  // below the editor area and contain views like output and
  // integrated terminal.
  //
  // "panelTitle.activeBorder": "#bb0000",
  // Border color for the active panel title.
  //
  // "panelTitle.activeForeground": "#ff0000",
  // Title color for the active panel.
  //
  // "panelTitle.inactiveForeground": "#ff0000",
  // Title color for the inactive panel.
  //
  //
  //
  //
  //
  // Peek View
  //
  // Peek views are used to show references and declarations
  // as a view inside the editor.
  //
  //
  //
  // "peekView.border": "#bb0000",
  // Color of the peek view borders and arrow.
  //
  // "peekViewEditor.background": "#660000ff",
  // Background color of the peek view editor.
  //
  // "peekViewEditor.matchHighlightBackground": "#660000ff",
  // Match highlight color in the peek view editor.
  //
  // "peekViewEditor.matchHighlightBorder": "#bb0000",
  // Match highlight border color
  // in the peek view editor.
  //
  // "peekViewEditorGutter.background": "#660000ff",
  // Background color of the gutter
  // in the peek view editor.
  //
  // "peekViewResult.background": "#660000ff",
  // Background color of the peek view result list.
  //
  // "peekViewResult.fileForeground": "#ff0000",
  // Foreground color for file nodes
  // in the peek view result list.
  //
  // "peekViewResult.lineForeground": "#ff0000",
  // Foreground color for line nodes
  // in the peek view result list.
  //
  // "peekViewResult.matchHighlightBackground": "#660000ff",
  // Match highlight color
  // in the peek view result list.
  //
  // "peekViewResult.selectionBackground": "#660000ff",
  // Background color of the selected entry
  // in the peek view result list.
  //
  // "peekViewResult.selectionForeground": "#ff0000",
  // Foreground color of the selected entry
  // in the peek view result list.
  //
  // "peekViewTitle.background": "#660000ff",
  // Background color of the
  // peek view title area.
  //
  // "peekViewTitleDescription.foreground": "#ff0000",
  // Color of the peek view title info.
  //
  // "peekViewTitleLabel.foreground": "#ff0000",
  // Color of the peek view title.
  //
  //
  //
  //
  //
  // Progress Bar
  //
  //
  //
  // "progressBar.background": "#660000ff",
  // Background color of the progress bar shown
  // for long running operations.
  //
  //
  //
  //
  //
  // Quick Picker
  //
  //
  //
  // "pickerGroup.border": "#bb0000",
  // Quick picker (Quick Open) color
  // for grouping borders.
  //
  // "pickerGroup.foreground": "#ff0000",
  // Quick picker (Quick Open) color
  // for grouping labels.
  //
  // "quickInput.background": "#660000ff",
  // Quick input background color. The quick input widget
  // is the container for views like the color theme picker.
  //
  // "quickInput.foreground": "#ff0000",
  // Quick input foreground color. The quick input widget
  // is the container for views like the color theme picker.
  //
  // "quickInputTitle.background": "#660000ff",
  // Quick picker title background color. The
  // quick picker widget is the container for pickers
  // like the Command Palette.
  //
  //
  //
  //
  //
  // Range Highlight - Editor Pane
  //
  // The range highlight is visible when selecting
  // a search result.
  //
  //
  //
  // "editor.rangeHighlightBackground": "#660000ff",
  // Background color of highlighted ranges, used by Quick Open,
  // Symbol in File and Find features. The color must be
  // sufficiently transparent (not too opaque) so as to
  // not hide underlying background decorations.
  //
  // "editor.rangeHighlightBorder": "#bb0000",
  // Background color of the border around highlighted ranges.
  //
  //
  //
  //
  //
  // Rename On Type
  //
  // 'renameOnType' is intended for HTML and XML tags.
  //
  // See: Synced Regions
  // https://code.visualstudio.com/updates/v1_44#_synced-regions
  //
  // 'renameOnType' is meant to be an improvement on
  // 'HTML Mirror Cursor'.
  // https://code.visualstudio.com/updates/v1_41#_html-mirror-cursor
  //
  // html.mirrorCursorOnMatchingTag
  //
  // Set the 'editor.renameOnType' setting to true,
  // if you dare.
  // (The default is false.)
  //
  //
  //
  // "editor.onTypeRenameBackground": "#660000ff",
  //
  //
  //
  //
  //
  // Rulers - Editor Pane (Vertical)
  //
  // Rulers are optional vertical lines in each Editor Pane
  // drawn along the right-side edge of specified columns.
  //
  // By default, no rulers are drawn, and no rulers will appear
  // if the "editor.rulers" array [] is empty.
  //
  // To see editor rulers, use: "editor.rulers": [],
  //
  // Three-rulers example: "editor.rulers": [40,52,64],
  //
  // After that declaration is auto-formatted, it turns into...
  //
  // / "editor.rulers": [
  // / 40,
  // / 52,
  // / 64
  // / ],
  //
  //
  //
  // "editorRuler.foreground": "#ff0000",
  // Color of the vertical editor ruler(s).
  //
  //
  //
  //
  //
  // Scrollbar Control
  //
  //
  //
  // "scrollbar.shadow": "#bb0000",
  // Scrollbar slider shadow to indicate that the view
  // is scrolled.
  //
  // "scrollbarSlider.activeBackground": "#660000ff",
  // Scrollbar slider background color when clicked on.
  //
  // "scrollbarSlider.background": "#660000ff",
  // Scrollbar slider background color.
  //
  // "scrollbarSlider.hoverBackground": "#660000ff",
  // Scrollbar slider background color when hovering.
  //
  //
  //
  //
  //
  // Scrollbar Overview Ruler - Editor Pane
  //
  // This ruler is located beneath the scroll bar
  // on the right edge of the editor, and gives an
  // overview of the decorations in the editor.
  //
  //
  //
  // "editorOverviewRuler.addedForeground": "#ff0000",
  // Overview ruler marker color for added content.
  //
  // "editorOverviewRuler.background": "#660000ff",
  // Background color of the editor overview ruler.
  // Only used when the minimap is enabled and placed
  // on the right side of the editor.
  //
  // "editorOverviewRuler.border": "#bb0000",
  // Color of the overview ruler border.
  //
  // "editorOverviewRuler.bracketMatchForeground": "#ff0000",
  // Overview ruler marker color for matching brackets.
  //
  // "editorOverviewRuler.deletedForeground": "#ff0000",
  // Overview ruler marker color for deleted content.
  //
  // "editorOverviewRuler.errorForeground": "#ff0000",
  // Overview ruler marker color for errors.
  //
  // "editorOverviewRuler.findMatchForeground": "#ff0000",
  // Overview ruler marker color for find matches. The color
  // must be sufficiently transparent (not too opaque)
  // so as to not hide underlying background decorations.
  //
  // "editorOverviewRuler.infoForeground": "#ff0000",
  // Overview ruler marker color for infos.
  //
  // "editorOverviewRuler.modifiedForeground": "#ff0000",
  // Overview ruler marker color for modified content.
  //
  // "editorOverviewRuler.rangeHighlightForeground": "#ff0000",
  // Overview ruler marker color for highlighted ranges,
  // like by the Quick Open, Symbol in File and Find features.
  // The color must be sufficiently transparent (not too opaque)
  // so as to not hide underlying background decorations.
  //
  // "editorOverviewRuler.selectionHighlightForeground": "#ff0000",
  // Overview ruler marker color for selection highlights.
  // The color must be sufficiently transparent (not too opaque)
  // so as to not hide underlying background decorations.
  //
  // "editorOverviewRuler.warningForeground": "#ff0000",
  // Overview ruler marker color for warnings.
  //
  // "editorOverviewRuler.wordHighlightForeground": "#ff0000",
  // Overview ruler marker color for symbol highlights.
  // The color must be sufficiently transparent (not too opaque)
  // so as to not hide underlying background decorations.
  //
  // "editorOverviewRuler.wordHighlightStrongForeground": "#ff0000",
  // Overview ruler marker color for write-access symbol highlights.
  // The color must be sufficiently transparent (not too opaque)
  // so as to not hide underlying background decorations.
  //
  //
  //
  //
  //
  // Search Editor - Editor Pane
  //
  // Search Editor colors highlight results in a Search Editor.
  // This can be configured separately from other find matches
  // in order to better differentiate between different classes
  // of match in the same editor.
  //
  //
  //
  // "searchEditor.findMatchBackground": "#660000ff",
  // Color of the editor's results.
  //
  // "searchEditor.findMatchBorder": "#bb0000",
  // Border color of the editor's results.
  //
  // "searchEditor.textInputBorder": "#bb0000",
  // Search editor text input box border.
  //
  //
  //
  //
  //
  // Selection
  //
  // Selection colors become visible when you are selecting
  // one or more text characters.
  //
  // The first five settings below relate to code text
  // in the Editor Panes, and the last setting is for
  // all the other selectable text fields throughout the
  // VSCode program.
  //
  // For Editor Pane text selections, in addition to the
  // the selection being highlighted, all other regions
  // with the same content are also highlighted
  // within the same file.
  //
  //
  //
  // "editor.inactiveSelectionBackground": "#660000ff",
  // Color of the selection in an inactive editor.
  // The color must be sufficiently transparent (not too opaque)
  // so as to not hide underlying background decorations.
  //
  // "editor.selectionBackground": "#660000ff",
  // Color of the editor selection.
  //
  // "editor.selectionForeground": "#ff0000",
  // Color of the selected text for high contrast.
  //
  // "editor.selectionHighlightBackground": "#660000ff",
  // Color for regions with the same content as the selection.
  // The color must be sufficiently transparent (not too opaque)
  // so as to not hide underlying background decorations.
  //
  // "editor.selectionHighlightBorder": "#bb0000",
  // Border color for the region in which the cursor resides;
  // or for the text area you subsequently select.
  // Also, the border color of any region matching
  // the cursor's region; or any text area matching
  // the text area you have selected.
  //
  // "selection.background": "#660000ff",
  // Background color of text you select within input fields,
  // and text areas that are not part of the Editor Pane code.
  // For example, input fields in the Settings, the
  // Find/Replace text-area, or within a Search box
  // text area.
  // (2)
  // Non-Editor Pane text you select within text input
  // areas. Eg: Within the Find/Replace text-areas.
  // Pure black is my prefered color choice for the
  // highest possible contrast when in the process of
  // carefully selecting text characters.
  //
  //
  //
  //
  //
  // Settings Editor
  //
  // These colors are for the Graphical User Interface (GUI)
  // 'Settings' editor which can be opened with [Ctrl/Cmd]+[,]
  // or can be opened from:
  // Main-menu "File" > "Preferences" > "Settings".
  //
  //
  //
  // "settings.checkboxBackground": "#660000ff",
  // Checkbox background.
  //
  // "settings.checkboxBorder": "#bb0000",
  // Checkbox border.
  //
  // "settings.checkboxForeground": "#ff0000",
  // Checkbox foreground.
  //
  // "settings.dropdownBackground": "#660000ff",
  // Dropdown background.
  //
  // "settings.dropdownBorder": "#bb0000",
  // Dropdown border.
  //
  // "settings.dropdownForeground": "#ff0000",
  // Dropdown foreground.
  //
  // "settings.dropdownListBorder": "#bb0000",
  // Dropdown list border.
  //
  // "settings.headerForeground": "#ff0000",
  // The foreground color for a section header
  // or active title.
  //
  // "settings.modifiedItemIndicator": "#ff0000",
  // The line that indicates a modified setting.
  //
  // "settings.numberInputBackground": "#660000ff",
  // Number input box background.
  //
  // "settings.numberInputBorder": "#bb0000",
  // Number input box border.
  // (2)
  // [Ctrl/Cmd]+[,] Settings: Border around some inactive
  // number input-area boxes. Eg: Search for "font size".
  //
  // "settings.numberInputForeground": "#ff0000",
  // Number input box foreground.
  //
  // "settings.textInputBackground": "#660000ff",
  // Text input box background.
  //
  // "settings.textInputBorder": "#bb0000",
  // Text input box border.
  // [Ctrl/Cmd]+[,] Settings: Border around some inactive
  // text input-area boxes. Eg: Search for "Editor: font
  // family".
  //
  // "settings.textInputForeground": "#ff0000",
  // Text input box foreground.
  //
  //
  //
  //
  //
  // Side Bar
  //
  // The Side Bar contains views like the Explorer and Search.
  //
  //
  //
  // "sideBar.background": "#660000ff",
  // Side Bar background color.
  //
  // "sideBar.border": "#bb0000",
  // Side Bar border color on the side separating the editor.
  // Vertical border separating the side bar from the
  // Editor Panes.
  //
  // "sideBar.dropBackground": "#660000ff",
  // Drag and drop feedback color for the side bar sections.
  // The color should have transparency so that
  // the side bar sections can still shine through.
  //
  // "sideBar.foreground": "#ff0000",
  // Side Bar foreground color. The Side Bar is the container
  // for views like Explorer and Search.
  // The side bar open/closes via the activity bar
  // icons. Icons color, and text color for alot of the
  // informational text, and text color for non-active
  // items.
  //
  // "sideBarSectionHeader.background": "#660000ff",
  // Side Bar section header background color.
  //
  // "sideBarSectionHeader.border": "#bb0000",
  // Side bar section header border color.
  // Eg: Activity bar item "Folders": Border above the second,
  // and subsequent main headers.
  //
  // "sideBarSectionHeader.foreground": "#ff0000",
  // Side Bar section header foreground color.
  // Eg: Activity bar item "Folders": Main headers.
  //
  // "sideBarTitle.foreground": "#ff0000",
  // Side Bar title foreground color.
  //
  //
  //
  //
  //
  // Snippet
  //
  //
  //
  // "editor.snippetFinalTabstopHighlightBackground": "#660000ff",
  // Highlight background color of the final tabstop
  // of a snippet.
  //
  // "editor.snippetFinalTabstopHighlightBorder": "#bb0000",
  // Highlight border color of the final tabstop
  // of a snippet.
  //
  // "editor.snippetTabstopHighlightBackground": "#660000ff",
  // Highlight background color of a snippet tabstop.
  //
  // "editor.snippetTabstopHighlightBorder": "#bb0000",
  // Highlight border color of a snippet tabstop.
  //
  //
  //
  //
  //
  // Source Control
  //
  //
  //
  // "scm.providerBorder": "#bb0000",
  // SCM Provider separator border.
  //
  //
  //
  //
  //
  // Status Bar
  //
  // The Status Bar is shown in the bottom of the workbench.
  //
  // Prominent items stand out from other Status Bar entries
  // to indicate importance.
  // One example is the Toggle Tab Key Moves Focus command
  // change mode indicator.
  //
  //
  //
  // "statusBar.background": "#660000ff",
  // Standard Status Bar background color.
  //
  // "statusBar.border": "#bb0000",
  // Status Bar border color separating the Status Bar
  // and editor.
  //
  // "statusBar.debuggingBackground": "#660000ff",
  // Status Bar background color when a program
  // is being debugged.
  //
  // "statusBar.debuggingBorder": "#bb0000",
  // Status Bar border color separating the Status Bar
  // and editor when a program is being debugged.
  //
  // "statusBar.debuggingForeground": "#ff0000",
  // Status Bar foreground color when a program
  // is being debugged.
  //
  // "statusBar.foreground": "#ff0000",
  // Status Bar foreground color.
  //
  // "statusBar.noFolderBackground": "#660000ff",
  // Status Bar background color when no folder is opened.
  //
  // "statusBar.noFolderBorder": "#bb0000",
  // Status Bar border color separating the Status Bar
  // and editor when no folder is opened.
  // Top border of status bar (all along the bottom
  // of the VSCode program window). I do Not know
  // what the 'noFolder' condition is. Currently the
  // status bar in Not filled up with items.
  //
  // "statusBar.noFolderForeground": "#ff0000",
  // Status Bar foreground color when no folder is opened.
  //
  // "statusBarItem.activeBackground": "#660000ff",
  // Status Bar item background color when clicking.
  //
  // "statusBarItem.hoverBackground": "#660000ff",
  // Status Bar item background color when hovering.
  //
  // "statusBarItem.prominentBackground": "#660000ff",
  // Status Bar prominent items background color.
  //
  // "statusBarItem.prominentForeground": "#ff0000",
  // Status Bar prominent items foreground color.
  //
  // "statusBarItem.prominentHoverBackground": "#660000ff",
  // Status Bar prominent items background color
  // when hovering.
  //
  // "statusBarItem.remoteBackground": "#660000ff",
  // Background color for the remote indicator
  // on the status bar.
  //
  // "statusBarItem.remoteForeground": "#ff0000",
  // Foreground color for the remote indicator
  // on the status bar.
  //
  //
  //
  //
  //
  // Symbol Highlight - Editor Pane
  //
  // The symbol highlight is visible when navigating
  // to a symbol via a command such as Go to Definition.
  //
  //
  //
  // "editor.symbolHighlightBackground": "#660000ff",
  // Background color of highlighted symbol. The color must be
  // sufficiently transparent (not too opaque) so as to
  // not hide underlying background decorations.
  //
  // "editor.symbolHighlightBorder": "#bb0000",
  // Background color of the border around highlighted symbols.
  //
  //
  //
  //
  //
  // Symbol Icons
  //
  // Symbol icons appear in the: Left-column Activity-bar's
  // 'Folders'-button 'Outline view'-button at the bottom;
  // and in the 'breadcrumb navigation';
  // and in the 'suggest widget'.
  //
  //
  //
  // "symbolIcon.arrayForeground": "#ff0000",
  // The foreground color for array symbols.
  //
  // "symbolIcon.booleanForeground": "#ff0000",
  // The foreground color for boolean symbols.
  //
  // "symbolIcon.classForeground": "#ff0000",
  // The foreground color for class symbols.
  //
  // "symbolIcon.colorForeground": "#ff0000",
  // The foreground color for color symbols.
  //
  // "symbolIcon.constantForeground": "#ff0000",
  // The foreground color for constant symbols.
  //
  // "symbolIcon.constructorForeground": "#ff0000",
  // The foreground color for constructor symbols.
  //
  // "symbolIcon.enumeratorForeground": "#ff0000",
  // The foreground color for enumerator symbols.
  //
  // "symbolIcon.enumeratorMemberForeground": "#ff0000",
  // The foreground color for enumerator member symbols.
  //
  // "symbolIcon.eventForeground": "#ff0000",
  // The foreground color for event symbols.
  //
  // "symbolIcon.fieldForeground": "#ff0000",
  // The foreground color for field symbols.
  //
  // "symbolIcon.fileForeground": "#ff0000",
  // The foreground color for file symbols.
  //
  // "symbolIcon.folderForeground": "#ff0000",
  // The foreground color for folder symbols.
  //
  // "symbolIcon.functionForeground": "#ff0000",
  // The foreground color for function symbols.
  //
  // "symbolIcon.interfaceForeground": "#ff0000",
  // The foreground color for interface symbols.
  //
  // "symbolIcon.keyForeground": "#ff0000",
  // The foreground color for key symbols.
  //
  // "symbolIcon.keywordForeground": "#ff0000",
  // The foreground color for keyword symbols.
  //
  // "symbolIcon.methodForeground": "#ff0000",
  // The foreground color for method symbols.
  //
  // "symbolIcon.moduleForeground": "#ff0000",
  // The foreground color for module symbols.
  //
  // "symbolIcon.namespaceForeground": "#ff0000",
  // The foreground color for namespace symbols.
  //
  // "symbolIcon.nullForeground": "#ff0000",
  // The foreground color for null symbols.
  //
  // "symbolIcon.numberForeground": "#ff0000",
  // The foreground color for number symbols.
  //
  // "symbolIcon.objectForeground": "#ff0000",
  // The foreground color for object symbols.
  //
  // "symbolIcon.operatorForeground": "#ff0000",
  // The foreground color for operator symbols.
  //
  // "symbolIcon.packageForeground": "#ff0000",
  // The foreground color for package symbols.
  //
  // "symbolIcon.propertyForeground": "#ff0000",
  // The foreground color for property symbols.
  //
  // "symbolIcon.referenceForeground": "#ff0000",
  // The foreground color for reference symbols.
  //
  // "symbolIcon.snippetForeground": "#ff0000",
  // The foreground color for snippet symbols.
  //
  // "symbolIcon.stringForeground": "#ff0000",
  // The foreground color for string symbols.
  //
  // "symbolIcon.structForeground": "#ff0000",
  // The foreground color for struct symbols.
  //
  // "symbolIcon.textForeground": "#ff0000",
  // The foreground color for text symbols.
  //
  // "symbolIcon.typeParameterForeground": "#ff0000",
  // The foreground color for type parameter symbols.
  //
  // "symbolIcon.unitForeground": "#ff0000",
  // The foreground color for unit symbols.
  //
  // "symbolIcon.variableForeground": "#ff0000",
  // The foreground color for variable symbols.
  //
  //
  //
  //
  //
  // Tabs (See: 'Group Header and Tabs')
  //
  //
  //
  //
  //
  // Terminal (Integrated)
  //
  //
  //
  // "terminal.ansiBlack": "#ff0000",
  // 'Black' ANSI color in the terminal.
  //
  // "terminal.ansiBlue": "#ff0000",
  // 'Blue' ANSI color in the terminal.
  //
  // "terminal.ansiBrightBlack": "#ff0000",
  // 'BrightBlack' ANSI color in the terminal.
  //
  // "terminal.ansiBrightBlue": "#ff0000",
  // 'BrightBlue' ANSI color in the terminal.
  //
  // "terminal.ansiBrightCyan": "#ff0000",
  // 'BrightCyan' ANSI color in the terminal.
  //
  // "terminal.ansiBrightGreen": "#ff0000",
  // 'BrightGreen' ANSI color in the terminal.
  //
  // "terminal.ansiBrightMagenta": "#ff0000",
  // 'BrightMagenta' ANSI color in the terminal.
  //
  // "terminal.ansiBrightRed": "#ff0000",
  // 'BrightRed' ANSI color in the terminal.
  //
  // "terminal.ansiBrightWhite": "#ff0000",
  // 'BrightWhite' ANSI color in the terminal.
  //
  // "terminal.ansiBrightYellow": "#ff0000",
  // 'BrightYellow' ANSI color in the terminal.
  //
  // "terminal.ansiCyan": "#ff0000",
  // 'Cyan' ANSI color in the terminal.
  //
  // "terminal.ansiGreen": "#ff0000",
  // 'Green' ANSI color in the terminal.
  //
  // "terminal.ansiMagenta": "#ff0000",
  // 'Magenta' ANSI color in the terminal.
  //
  // "terminal.ansiRed": "#ff0000",
  // 'Red' ANSI color in the terminal.
  //
  // "terminal.ansiWhite": "#ff0000",
  // 'White' ANSI color in the terminal.
  //
  // "terminal.ansiYellow": "#ff0000",
  // 'Yellow' ANSI color in the terminal.
  //
  // "terminal.background": "#660000ff",
  // The background of the Integrated Terminal's viewport.
  //
  // "terminal.border": "#bb0000",
  // The color of the border that separates split panes
  // within the terminal. This defaults to panel.border.
  //
  // "terminal.foreground": "#ff0000",
  // The default foreground color
  // of the Integrated Terminal.
  //
  // "terminal.selectionBackground": "#660000ff",
  // The selection background color of the terminal.
  //
  // "terminalCursor.background": "#660000ff",
  // The background color of the terminal cursor.
  // Allows customizing the color of a character
  // overlapped by a block cursor.
  //
  // "terminalCursor.foreground": "#ff0000",
  // The foreground color of the terminal cursor.
  //
  //
  //
  //
  //
  // Text
  //
  // Colors inside a text document,
  // such as the welcome page.
  //
  //
  //
  // "textBlockQuote.background": "#660000ff",
  // Background color for block quotes in text.
  //
  // "textBlockQuote.border": "#bb0000",
  // Border color for block quotes in text.
  //
  // "textCodeBlock.background": "#660000ff",
  // Background color for code blocks in text.
  //
  // "textLink.activeForeground": "#ff0000",
  // Foreground color for links in text when clicked on,
  // and on mouse hover.
  //
  // "textLink.foreground": "#ff0000",
  // Foreground color for links in text.
  //
  // "textPreformat.foreground": "#ff0000",
  // Foreground color for preformatted text segments.
  //
  // "textSeparator.foreground": "#ff0000",
  // Color for text separators.
  //
  //
  //
  //
  //
  // Title Bar
  //
  //
  //
  // "titleBar.activeBackground": "#660000ff",
  // Title Bar background when the window is active.
  //
  // "titleBar.activeForeground": "#ff0000",
  // Title Bar foreground when the window is active.
  //
  // "titleBar.border": "#bb0000",
  // Title bar border color.
  //
  // "titleBar.inactiveBackground": "#660000ff",
  // Title Bar background when the window is inactive.
  //
  // "titleBar.inactiveForeground": "#ff0000",
  // Title Bar foreground when the window is inactive.
  //
  //
  //
  //
  //
  // Unused Source Code - Editor Pane
  //
  //
  //
  // "editorUnnecessaryCode.border": "#bb0000",
  // Border color of unnecessary (unused) source code
  // in the editor.
  //
  // "editorUnnecessaryCode.opacity": "#ff0000",
  // Opacity of unnecessary (unused) source code in the editor.
  // For example, the 'c0' of "#000000c0" will render the code
  // with 75% opacity. For high contrast themes,
  // use the "editorUnnecessaryCode.border" theme color
  // to underline unnecessary code instead of fading it out.
  //
  //
  //
  //
  //
  // Welcome Page
  //
  // The welcome page is accessed via:
  // Main-menu "Help" > "Welcome".
  //
  //
  //
  // "walkThrough.embeddedEditorBackground": "#660000ff",
  // Background color for the embedded editors
  // on the Interactive Playground.
  //
  // "welcomePage.background": "#660000ff",
  // Background color for the Welcome page.
  //
  // "welcomePage.buttonBackground": "#660000ff",
  // Background color for the buttons on the Welcome page.
  //
  // "welcomePage.buttonHoverBackground": "#660000ff",
  // Hover background color for the buttons
  // on the Welcome page.
  //
  //
  //
  //
  //
  // White Space - Editor Pane
  //
  // The white space characters display according to
  // the setting for "editor.renderWhitespace". The
  // default is "selection", with the other three
  // possibilities being "all", "boundary", or "none."
  //
  //
  //
  // "editorWhitespace.foreground": "#ff0000",
  // Color of whitespace characters in the editor.
  //
  //
  //
  //
  //
  // Widget
  //
  // (See also: 'Dropdown Control')
  //
  // The editor Widget is shown in front of the editor content.
  // Examples are the Find/Replace dialog, the suggestion widget,
  // and the editor hover.
  //
  //
  //
  // "editorHoverWidget.background": "#660000ff",
  // Background color of the editor hover.
  //
  // "editorHoverWidget.border": "#bb0000",
  // Border color of the editor hover.
  //
  // "editorHoverWidget.foreground": "#ff0000",
  // Foreground color of the editor hover.
  //
  // "editorHoverWidget.statusBarBackground": "#660000ff",
  // Background color of the editor hover status bar.
  //
  // "editorSuggestWidget.background": "#660000ff",
  // Background color of the suggestion widget.
  //
  // "editorSuggestWidget.border": "#bb0000",
  // Border color of the suggestion widget.
  //
  // "editorSuggestWidget.foreground": "#ff0000",
  // Foreground color of the suggestion widget.
  //
  // "editorSuggestWidget.highlightForeground": "#ff0000",
  // Color of the match highlights in the suggestion widget.
  //
  // "editorSuggestWidget.selectedBackground": "#660000ff",
  // Background color of the selected entry
  // in the suggestion widget.
  //
  // "editorWidget.background": "#660000ff",
  // Background color of editor widgets, such as Find/Replace.
  //
  // "editorWidget.border": "#bb0000",
  // Border color of the editor widget unless the widget
  // does not contain a border or defines its own border color.
  //
  // "editorWidget.foreground": "#ff0000",
  // Foreground color of editor widgets, such as find/replace.
  //
  // "editorWidget.resizeBorder": "#bb0000",
  // Border color of the resize bar of editor widgets.
  // The color is only used if the widget chooses to have
  // a resize border and if the color is not overridden
  // by a widget.
  //
  // "widget.shadow": "#bb0000",
  // Shadow color of widgets such as Find/Replace
  // inside the editor.
  //
  //
  //
  //
  //
  // Window Border
  //
  // The theme colors for VS Code window border.
  //
  //
  //
  // "window.activeBorder": "#bb0000",
  // Border color for the active (focused) window.
  //
  // "window.inactiveBorder": "#bb0000",
  // Border color for the inactive (unfocused) windows.
  //
  //
  //
  //
  //
  // Word Highlight - Editor Pane
  //
  // Word highlight colors are visible when the cursor
  // is inside a symbol or a word. Depending on the
  // language support available for the file type,
  // all matching references and declarations are highlighted,
  // and read and write accesses get different colors.
  // If document symbol language support is not available,
  // this falls back to word highlighting.
  //
  //
  //
  // "editor.wordHighlightBackground": "#660000ff",
  // Background color of a symbol during read-access,
  // for example when reading a variable. The color
  // must sufficiently transparent (not too opaque)
  // so as to not hide underlying background decorations.
  //
  // "editor.wordHighlightBorder": "#bb0000",
  // Border color of a symbol during read-access,
  // for example when reading a variable.
  //
  // "editor.wordHighlightStrongBackground": "#660000ff",
  // Background color of a symbol during write-access,
  // for example when writing to a variable.
  // The color must be sufficiently transparent (not too opaque)
  // so as to not hide underlying background decorations.
  //
  // "editor.wordHighlightStrongBorder": "#bb0000",
  // Border color of a symbol during write-access,
  // for example when writing to a variable.
  //
  //
  //
  //
  //
  //
  //
  // [Insert formerly used workbench.colorCustomizations
  // settings below here, as a temporary aid to incorporating
  // them into the list just above here.
  // You can alphabetize your old settings, if you want to,
  // by pasting them into the top box on page
  // http://www.mynikko.com/tools/tool_stringcounter.html
  // Then, remove the checkmark from "Display counter",
  // and then click the button "Sort by alphabetical order".
  // Copy the new alphabetized ordering out of
  // the lower box.]
  //
  //
  //
  //
  //
  "z1._null_and_void.last_setting_without_trailing_comma": ""
  // The line above serves to eliminate the need to
  // worry about removing the trailing-comma from the
  // last of the above used settings, before
  // this block of code is closed with the following
  // closing-curly brace.
},
// End: workbench.colorCustomizations
//
//
//
