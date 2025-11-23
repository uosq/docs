# EventInfo 

Represents an event when a temporary entity got created. Contains some useful information about the temporary entity that are not a part of the entity itself

## Fields

Fields are modifiable.

### classId

integer

### fireDelay

number

### flags

integer

### data

string (raw bytes)

## Examples

``` lua title="Print the data field"
callbacks.Register("ProcessTempEntities", function (entEvtTable)
    for ent, eventInfo in pairs(entEvtTable) do
        if ent:GetNetworkName() == "CTETFParticleEffect" then
            print(eventInfo.data)
        end
    end
end)
```
