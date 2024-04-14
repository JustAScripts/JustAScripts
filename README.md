```lua
 local args = {
    [1] = 1
}

game:GetService("ReplicatedStorage").RemoteEvent.BuyEvent:FireServer(unpack(args))
```
