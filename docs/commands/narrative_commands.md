## Control Stage
Controls the stage on which character portraits are displayed.

Property | Type | Description
 --- | --- | ---
Display | Fungus.StageDisplayType | Display type
Stage | Fungus.Stage | Stage to display characters on
Replaced Stage | Fungus.Stage | Stage to swap with
Use Default Settings | System.Boolean | Use Default Settings
Fade Duration | System.Single | Fade Duration
Wait Until Finished | System.Boolean | Wait until the tween has finished before executing the next command

## Menu
Displays a button in a multiple choice menu

Property | Type | Description
 --- | --- | ---
Text | System.String | Text to display on the menu button
Description | System.String | Notes about the option text for other authors, localization, etc.
Target Block | Fungus.Block | Block to execute when this option is selected
Hide If Visited | System.Boolean | Hide this option if the target block has been executed previously
Set Menu Dialog | Fungus.MenuDialog | A custom Menu Dialog to use to display this menu. All subsequent Menu commands will use this dialog.

## Menu Timer
Displays a timer bar and executes a target block if the player fails to select a menu option in time.

Property | Type | Description
 --- | --- | ---
Duration | System.Single | Length of time to display the timer for
Target Block | Fungus.Block | Block to execute when the timer expires

## Portrait
Controls a character portrait. 

Property | Type | Description
 --- | --- | ---
Stage | Fungus.Stage | Stage to display portrait on
Display | Fungus.DisplayType | Display type
Character | Fungus.Character | Character to display
Replaced Character | Fungus.Character | Character to swap with
Portrait | UnityEngine.Sprite | Portrait to display
Offset | Fungus.PositionOffset | Move the portrait from/to this offset position
From Position | UnityEngine.RectTransform | Move the portrait from this position
To Position | UnityEngine.RectTransform | Move the portrait to this positoin
Facing | Fungus.FacingDirection | Direction character is facing
Use Default Settings | System.Boolean | Use Default Settings
Fade Duration | System.Single | Fade Duration
Move Speed | System.Single | Movement Speed
Shift Offset | UnityEngine.Vector2 | Shift Offset
Move | System.Boolean | Move
Shift Into Place | System.Boolean | Start from offset
Wait Until Finished | System.Boolean | Wait until the tween has finished before executing the next command

## Say
Writes text in a dialog box.

Property | Type | Description
 --- | --- | ---
Description | System.String | Notes about this story text for other authors, localization, etc.
Character | Fungus.Character | Character that is speaking
Portrait | UnityEngine.Sprite | Portrait that represents speaking character
Voice Over Clip | UnityEngine.AudioClip | Voiceover audio to play when writing the text
Show Always | System.Boolean | Always show this Say text when the command is executed multiple times
Show Count | System.Int32 | Number of times to show this Say text when the command is executed multiple times
Extend Previous | System.Boolean | Type this text in the previous dialog box.
Fade In | System.Boolean | Fade in this dialog box.
Fade Out | System.Boolean | Fade out this dialog box.
Wait For Click | System.Boolean | Wait for player to click before hiding the dialog and continuing. If false then the dialog will display and execution will continue immediately.
Set Say Dialog | Fungus.SayDialog | Sets the active Say dialog with a reference to a Say Dialog object in the scene. All story text will now display using this Say Dialog.

## Set Language
Set the active language for the scene. A Localization object with a localization file must be present in the scene.

Property | Type | Description
 --- | --- | ---
Language Code | System.String | Code of the language to set. e.g. ES, DE, JA

## Set Menu Dialog
Sets a custom menu dialog to use when displaying multiple choice menus

Property | Type | Description
 --- | --- | ---
Menu Dialog | Fungus.MenuDialog | The Menu Dialog to use for displaying menu buttons

## Set Say Dialog
Sets a custom say dialog to use when displaying story text

Property | Type | Description
 --- | --- | ---
Say Dialog | Fungus.SayDialog | The Say Dialog to use for displaying Say story text

