## Fade Screen
Draws a fullscreen texture over the scene to give a fade effect. Setting Target Alpha to 1 will obscure the screen, alpha 0 will reveal the screen. If no Fade Texture is provided then a default flat color texture is used.

Property | Type | Description
 --- | --- | ---
Duration | System.Single | Time for fade effect to complete
Target Alpha | System.Single | Current target alpha transparency value. The fade gradually adjusts the alpha to approach this target value.
Wait Until Finished | System.Boolean | Wait until the fade has finished before executing next command
Fade Color | UnityEngine.Color | Color to render fullscreen fade texture with when screen is obscured.
Fade Texture | UnityEngine.Texture2D | Optional texture to use when rendering the fullscreen fade effect.

## Fade To View
Fades the camera out and in again at a position specified by a View object.

Property | Type | Description
 --- | --- | ---
Duration | System.Single | Time for fade effect to complete
Fade Out | System.Boolean | Fade from fully visible to opaque at start of fade
Target View | Fungus.View | View to transition to when Fade is complete
Wait Until Finished | System.Boolean | Wait until the fade has finished before executing next command
Fade Color | UnityEngine.Color | Color to render fullscreen fade texture with when screen is obscured.
Fade Texture | UnityEngine.Texture2D | Optional texture to use when rendering the fullscreen fade effect.

## Move To View
Moves the camera to a location specified by a View object.

Property | Type | Description
 --- | --- | ---
Duration | System.Single | Time for move effect to complete
Target View | Fungus.View | View to transition to when move is complete
Wait Until Finished | System.Boolean | Wait until the fade has finished before executing next command

## Shake Camera
Applies a camera shake effect to the main camera.

Property | Type | Description
 --- | --- | ---
Duration | System.Single | Time for camera shake effect to complete
Amount | UnityEngine.Vector2 | Magnitude of shake effect in x & y axes
Wait Until Finished | System.Boolean | Wait until the shake effect has finished before executing next command

## Start Swipe
Activates swipe panning mode where the player can pan the camera within the area between viewA & viewB.

Property | Type | Description
 --- | --- | ---
View A | Fungus.View | Defines one extreme of the scrollable area that the player can pan around
View B | Fungus.View | Defines one extreme of the scrollable area that the player can pan around
Duration | System.Single | Time to move the camera to a valid starting position between the two views
Speed Multiplier | System.Single | Multiplier factor for speed of swipe pan

## Stop Swipe
Deactivates swipe panning mode.
