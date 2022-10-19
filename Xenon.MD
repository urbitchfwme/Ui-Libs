# Xenon Ui Lib
Catto Ui Library but moddified by naypramx

## Loadstring
```lua
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/naypramx/Ui__Project/Script/XeNonUi", true))()
```
## Window
```lua
local Window = Library:CreateWindow("Window", Enum.KeyCode.RightControl)
```

## Watermark
```lua
Library:CreateWatermark("Example by Kyoto")
```

## Tabs
```lua
local Tab = Window:CreateTab("Tab")
```

## Sectors
```lua
local Sector = Tab:CreateSector("Sector", "left") -- // replace left wit right if u want it to be on right side of ui
```

## Labels
```lua
Sector:AddLabel("Text for Label")
```

## Buttons
```lua
Sector:AddButton("Button",function()
    print("Pressed")
end)
```

## Toggles
```lua
Sector:AddToggle("Toggle", false, function(state)
    print("Toggled")
end)
```

## Seperator
```lua
Sector:AddSeperator("Seperator")
```

## Slider
```lua
Sector:AddSlider("Slider",16,16,100,1,function(value)
    print("slider is on"..value.."")
end)
```

## Dropdown
```lua
Sector:AddDropdown("Drop Down",{"Option1", "Option2", "Option3"},"Option2",true,function(option)
    print(""..option.." chosen")
end)
```
