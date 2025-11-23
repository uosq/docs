# StringCmd

Represents a string command.

## Methods

### Get()

Used to get the command string itself.

### Set( string:command )

Set the command string.

## Examples

``` lua title="Prevent user from using 'status'"

local function onStringCmd( stringCmd )
    
    if stringCmd:Get() == "status" then
        stringCmd:Set( "echo No status for you!" )
    end
end

callbacks.Register( "SendStringCmd", "hook", onStringCmd )
```
