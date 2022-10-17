# Yun Ui Lib

## Loading the Lib
```lua
loadstring(game:HttpGet('https://pastebin.com/raw/xRzmhAzz'))()
local Library = initLibrary()
local Window = Library:Load({name = "NIGGER", sizeX = 425, sizeY = 512, color = Color3.fromRGB(255, 255, 255)})
```

## Creating Tabs
```lua
local Tab = Window:Tab("Name")
```

## Creating Sections
```lua
local Section = Tab:Section{name = "Name", column = 1}
```

## Creating Toggles
```lua
Section:Toggle {
    Name = "Name",
    flag = "bool", 
    callback = function(state)
        -- // action
    end
}
```

## Creating Sliders
```lua
    Section:Slider {
    Name = "Name",
    Default = 50,
    Min = 100,
    Max = 250,
    Decimals = 1,
    Flag = "bool",
    callback = function(value)
        
    end
}
```

## Creating Dropdowns
```lua
Aimingsec1:dropdown {
    name = "Aim",
    content = {"Option 1", "Option 2", "Option 3", "Option 4", "Option 5"}
    multichoice = true, -- true is multi dropdown false is regular dropdown
    callback = function(option)
        
    end
}
```
