# VLib UI Library
v1.0.0

# Loadstring:
> To implement the UI, you need this code inside a executor.
```
local VLib = loadstring(game:HttpGet("https://pastebin.com/raw/Mb49kKTP"))()
```

# Creating the UI:
> To create the ui, you use this code below the previous code, make sure theres spacing for organization.
```
MAINTTL = "Title" 

local win = VLib:Window("Subtitle", Color3.fromRGB(196, 40, 28))
```
> you can customize the "Title" and "Subtitle" parts to display whatever is to your liking.

# Creating Tabs:

```
local Tab = win:Tab("Tab")
```

# Creating Buttons:

```
Tab:Button("Button",function()

end)
```

# Creating Toggles:

```
Tab:Toggle("Toggle",function(t)

end)
```

# Creating Dropdown:

```
Tab:Dropdown("Dropdown",{"Dropdown1", "Dropdown2", "Dropdown3", "Dropdown4", "Dropdown4"},function(SelectedOption)

end)
```

# Creating Labels:

```
Tab:Label("Label")
```

# Destroy The Library:
```
game.CoreGui["Library"]:Destroy()
```

# Thanks Message
> Thanks for using VLib UI Library,
**I didnt make any of this shit. I noticed the creator of the library didnt wanna upload it so I uploaded it myself**

> Discord; l0ckerV5


***no theres no section also dont fucking dm me about adding sections, i didnt even make it dipshit***
