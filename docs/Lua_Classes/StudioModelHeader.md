# StudioModelHeader

The StudioModelHeader object contains information about a studio models hitbox sets and bones.

## Methods

### GetName()

Returns the name of the model.

### GetHitboxSet( index:integer )

Returns a [StudioHitboxSet](../Lua_Classes/StudioHitboxSet.md) object by the entities hitbox set index. This can be retrieved from m_nHitBoxSet netvar.

### GetAllHitboxSets()

Returns a table of all [StudioHitboxSet](../Lua_Classes/StudioHitboxSet.md) objects for the model.


## Examples

```lua title="Enumerate all hitboxes"

```

