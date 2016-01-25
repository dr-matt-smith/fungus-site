## Fade Sprite
Fades a sprite to a target color over a period of time.

Property | Type | Description
 --- | --- | ---
Sprite Renderer | UnityEngine.SpriteRenderer | Sprite object to be faded
Duration | System.Single | Length of time to perform the fade
Target Color | UnityEngine.Color | Target color to fade to. To only fade transparency level, set the color to white and set the alpha to required transparency.
Wait Until Finished | System.Boolean | Wait until the fade has finished before executing the next command

## Set Clickable 2D
Sets a Clickable2D component to be clickable / non-clickable.

Property | Type | Description
 --- | --- | ---
Target Clickable2 D | Fungus.Clickable2D | Reference to Clickable2D component on a gameobject
Active State | Fungus.BooleanData | Set to true to enable the component

## Set Collider
Sets all collider (2d or 3d) components on the target objects to be active / inactive

Property | Type | Description
 --- | --- | ---
Target Objects | System.Collections.Generic.List`1[UnityEngine.GameObject] | A list of gameobjects containing collider components to be set active / inactive
Target Tag | System.String | All objects with this tag will have their collider set active / inactive
Active State | Fungus.BooleanData | Set to true to enable the collider components

## Set Draggable 2D
Sets a Draggable2D component to be draggable / non-draggable.

Property | Type | Description
 --- | --- | ---
Target Draggable2 D | Fungus.Draggable2D | Reference to Draggable2D component on a gameobject
Active State | Fungus.BooleanData | Set to true to enable the component

## Set Mouse Cursor
Sets the mouse cursor sprite.

Property | Type | Description
 --- | --- | ---
Cursor Texture | UnityEngine.Texture2D | Texture to use for cursor. Will use default mouse cursor if no sprite is specified
Hot Spot | UnityEngine.Vector2 | The offset from the top left of the texture to use as the target point

## Set Sorting Layer
Sets the Renderer sorting layer of every child of a game object. Applies to all Renderers (including mesh, skinned mesh, and sprite).

Property | Type | Description
 --- | --- | ---
Target Object | UnityEngine.GameObject | Root Object that will have the Sorting Layer set. Any children will also be affected
Sorting Layer | System.String | The New Layer Name to apply

## Set Sprite Order
Controls the render order of sprites by setting the Order In Layer property of a list of sprites.

Property | Type | Description
 --- | --- | ---
Target Sprites | System.Collections.Generic.List`1[UnityEngine.SpriteRenderer] | List of sprites to set the order in layer property on
Order In Layer | Fungus.IntegerData | The order in layer value to set on the target sprites

## Show Sprite
Makes a sprite visible / invisible by setting the color alpha.

Property | Type | Description
 --- | --- | ---
Sprite Renderer | UnityEngine.SpriteRenderer | Sprite object to be made visible / invisible
Visible | System.Boolean | Make the sprite visible or invisible

