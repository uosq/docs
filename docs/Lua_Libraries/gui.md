# gui

## Functions

### GetValue( msg:string )

Get current value of a setting

### SetValue( msg:string, index:integer )

Set current Integer value of a setting

### SetValue( msg:string, msg:string )

Set current Text value of a setting

### IsMenuOpen()

Returns true if lmaobox menu is open.


## Examples

```lua title="Set aimbot settings"
gui.SetValue("aim bot", 1);
gui.SetValue("aim method", "silent");

local aim_method = gui.GetValue("aim method");
print( aim_method ) -- prints 'silent'
```

```lua title="Get current aimbot fov"
local aim_fov = gui.GetValue("aim fov");
print( aim_fov )
```

```lua title="Change ESP color for blue team"
gui.SetValue("blue team color", 0xcaffffff)
```