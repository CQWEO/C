local library = loadstring(game:GetObjects("rbxassetid://7657867786")[1].Source)()
local Wait = library.subs.Wait -- Only returns if the GUI has not been terminated. For 'while Wait() do' loops

local PepsisWorld = library:CreateWindow({
Name = "YOU HUB",
Themeable = {
Info = "Discord Server: Rechedmcvn"
}
})

local GeneralTab = PepsisWorld:CreateTab({
Name = "Main"
})
local FarmingSection = GeneralTab:CreateSection({
Name = "ESP"
})
FarmingSection:AddToggle({
Name = "Door",
Flag = "FarmingSection_EXPGrinder"
})
FarmingSection:AddToggle({
Name = "Key",
Flag = "FarmingSection_TrickSpammer",
Keybind = Enter,
Callback = Key
})
FarmingSection:AddToggle({
Name = "Hiding Spot",
Flag = "FarmingSection_TrickSpammer",
Keybind = Esp,
Callback = Wardrobe
})
FarmingSection:AddToggle({
Name = "Entity",
Flag = "FarmingSection_TrickSpammer",
Keybind = Enter,
Callback = Door
})FarmingSection:AddToggle({
Name = "Locker",
Flag = "FarmingSection_TrickSpammer",
Keybind = Enter,
Callback = Door
})FarmingSection:AddToggle({
Name = "Book",
Flag = "FarmingSection_TrickSpammer",
Keybind = Enter,
Callback = Door
})FarmingSection:AddToggle({
Name = "Breaker",
Flag = "FarmingSection_TrickSpammer",
Keybind = Enter,
Callback = Door
})FarmingSection:AddToggle({
Name = "Item",
Flag = "FarmingSection_TrickSpammer",
Keybind = Enter,
Callback = Door
})
local FarmingSection = GeneralTab:CreateSection({
Name = "Misc"
})
FarmingSection:AddToggle({
Name = "No Screech",
Flag = "FarmingSection_TrickSpammer",
Keybind = Enter,
Callback = function()
    for i,v in pairs(game:GetService("ReplicatedStorage").Entities.Screech:destroy()
            for i,v in pairs(game:GetService("ReplicatedStorage").Entities.Screech:destroy()
               end 
           end)
       end 
   end 
end 
})
FarmingSection:AddToggle({
Name = "No Halt",
Flag = "FarmingSection_TrickSpammer",
Keybind = Enter,
Callback = Door
})
FarmingSection:AddToggle({
Name = "No Eyes",
Flag = "FarmingSection_TrickSpammer",
Keybind = Enter,
Callback = Door
})
FarmingSection:AddToggle({
Name = "No Pating",
Flag = "FarmingSection_TrickSpammer",
Keybind = Enter,
Callback = Door
})
FarmingSection:AddToggle({
Name = "LockPart Dupe Door",
Flag = "FarmingSection_TrickSpammer",
Keybind = Enter,
Callback = Door
})
FarmingSection:AddToggle({
Name = "No Void",
Flag = "FarmingSection_TrickSpammer",
Keybind = Enter,
Callback = Door
})
FarmingSection:AddToggle({
Name = "No Glitch",
Flag = "FarmingSection_TrickSpammer",
Keybind = Enter,
Callback = Door
})
FarmingSection:AddToggle({
Name = "No Timothy Jumpcare",
Flag = "FarmingSection_TrickSpammer",
Keybind = Enter,
Callback = Door
})
FarmingSection:AddToggle({
Name = "No Seek Trigger Collision",
Flag = "FarmingSection_TrickSpammer",
Keybind = Enter,
Callback = Door
})
