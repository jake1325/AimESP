# AimESP
## Credits
- [@Exunys](https://github.com/Exuny) Aimbot
- [@Blissful4992](https://github.com/Blissful4992) ESP

## Script
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/jake1325/AimESP/main/main/loader.lua"))()

-- // Aimbot Settings //
_G.AimbotEnabled = true
_G.TeamCheck = true -- If set to true then the script would only lock your aim at enemy team members.
_G.AimPart = "Head" -- Where the aimbot script would lock at.
_G.Sensitivity = 0 -- How many seconds it takes for the aimbot script to officially lock onto the target's aimpart.

-- // FOV Settings //
_G.CircleSides = 64 -- How many sides the FOV circle would have.
_G.CircleColor = Color3.fromRGB(255, 255, 255) -- (RGB) Color that the FOV circle would appear as.
_G.CircleTransparency = 0.7 -- Transparency of the circle.
_G.CircleRadius = 100 -- The radius of the circle / FOV.
_G.CircleFilled = false -- Determines whether or not the circle is filled.
_G.CircleVisible = true -- Determines whether or not the circle is visible.
_G.CircleThickness = 0 -- The thickness of the circle.
```
