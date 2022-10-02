local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Time Hub", "Synapse")

local Tab = Window:NewTab("Script Map")
local Section = Tab:NewSection("Script")
Section:NewButton("Time", "Mokuro hub", function()
    loadstring(game:HttpGet"https://raw.githubusercontent.com/xDepressionx/Free-Script/main/AllScript.lua")()
end)

Section:NewButton("Verdant moon", "hub", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/pattingbabies/pattingbabies/main/verdantmoon"))()
end)

Section:NewButton("BedWar", "VAPE V4", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/7GrandDadPGN/VapeV4ForRoblox/main/NewMainScript.lua", true))()
end)
local Tab = Window:NewTab("Coming soon")
local Section = Tab:NewSection("No Script")
