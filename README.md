# Căc

# Source :
```lua
    local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/SourceFullNightHub/nh-c-c/main/Source"))()
```

# Wait cl
```lua
    local Wait = library.subs.Wait
```

# Create Windows
```lua
local Window = library:CreateWindow({
    Name = "Night Hub - Kaitun",
    Themeable = {
    Info = ""
    }
})
```

# Create Tab
```lua
local tab1 = Window:CreateTab({
    Name = "Tab 1"
})
```

# Create Button
```lua
tab1:AddButton({
    Name = "Button",
    Callback = function()
        print("")
    end
})
```

# Create Toggle
```lua
tab1:AddToggle{
    Name = "Toggle",
    Flag = "Toggle",
    Value = false,
    Callback  = function(Value)
      print(Value)
    end
}
```

# Create Dropdown
```lua
tab1:AddDropdown({
    Name = "Dropdown",
    Flag = "Dropdown",
    List = {"1", "2", "3"},
    Value = "1",
    Callback = function(Value)
        print(Value)
    end
})
```

# Create Key Bind
```lua
  -- chx cs
```

# Create Label
```lua
local Label = tab1:AddLabel({
  Name = "Label",
  Flag = "Label"
})
```

# Create Sections
```lua
local MainSection = MainTab:CreateSection({
    Name = "Main",
    Side = "Left"
})
```
