# UserMessage

Received as the only argument in DispatchUserMessage callback.

## Reading

Reading starts at the beginning of the message (curBit = 0). Each call to Read*() advances the read cursor by the number of bits read. Reading past the end of the message will cause an error.

## Writing

Writing to the BitBuffer changes the actual message contents, so you can modify what you're receiving. 

### GetID()

Returns the ID of the message. You can get the list here: [TF2 User Messages](https://wiki.alliedmods.net/User_messages).

### GetBitBuffer()

Returns the [BitBuffer](../Lua_Classes/BitBuffer.md) object that contains the message data.

## Example

``` lua title="Print chat messages from players"
local function myCoolMessageHook(msg)

    if msg:GetID() == SayText2 then 
        local bf = msg:GetBitBuffer()

        bf:SetCurBit(16)-- skip 2 bytes of not useful data (author, bWantsToChat)

        local chatType = bf:ReadString(256)
        local playerName = bf:ReadString(256)
        local message = bf:ReadString(256)

        print("Player " .. playerName .. " said " .. message)
    end
    
end

callbacks.Register("DispatchUserMessage", myCoolMessageHook)
```
