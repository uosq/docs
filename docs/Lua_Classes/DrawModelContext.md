# DrawModelContext

Represents the context in which a model is being drawn in the DrawModel callback.

## Methods

### GetEntity()

Returns entity linked to the drawn model, can be nil.

### GetModelName()

Returns the name of the model being drawn.

### ForcedMaterialOverride( mat: Material )

Replace material used to draw the model. Material can be found or created via materials. API

### DrawExtraPass()

Redraws the model. Can be used to achieve various effects with different materials.

### StudioSetColorModulation( r: number, g: number, b: number )

Sets the color modulation of the model via StudioRender. Only works for models rendered using STUDIO_RENDER flag.

### StudioSetAlphaModulation( alpha: number )

Sets the alpha modulation of the model via StudioRender. Only works for models rendered using STUDIO_RENDER flag.

### SetColorModulation( r: number, g: number, b: number )

Sets the color modulation of the model via RenderView.

`r`, `g` and `b` have a range of [0, 1].

### SetAlphaModulation( alpha: number )

Sets the alpha modulation of the model via RenderView.

The `alpha` parameter has a range of [0, 1]

### DepthRange( start: number, end: number )

Sets the depth range of the scene. Useful for drawing models in the background or other various effects. Should be reset to the default (0,1) when done.

### SuppressEngineLighting( bool: boolean )

Suppresses the engine lighting when drawing the model.

### Execute()

Draw the model immediately in the current state. Can be called multiple times. A model will be always drawn even without calling Execute, so calling it 1 time will result in 2 Execute calls, calling this 0 times will result in 1 Execute call. The use case for this is stacking material force overrides for example.

### IsDrawingAntiAim()

Returns true if anti aim indicator model is being drawn.

### IsDrawingBackTrack()

Returns true if backtrack indicator model is being drawn.

### IsDrawingGlow()

Returns true if glow model is being drawn.


## Examples

``` lua title="Draw all player models using AmmoBox material"
local ammoboxMaterial = materials.Find( "models/items/ammo_box2" )

local function onDrawModel( drawModelContext )
    local entity = drawModelContext:GetEntity()

    if entity:GetClass() == "CTFPlayer" then
        drawModelContext:ForcedMaterialOverride( ammoboxMaterial )
    end
end
 
callbacks.Register("DrawModel", "hook123", onDrawModel) 
```

``` lua title="Change LocalPlayer color"

---@param context DrawModelContext
local function OnDrawModel( context )
	local localPlayer = context:GetEntity()
	if localPlayer == nil or localPlayer:GetIndex() ~= client.GetLocalPlayerIndex() then
		return
	end

	context:SetColorModulation(1.0, 0.0, 0.0)
end

callbacks.Register("DrawModel", "colorModExample", OnDrawModel)
```