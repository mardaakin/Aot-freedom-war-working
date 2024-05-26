local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
   Name = "Skibidi Slicers Gui",
   LoadingTitle = "Wat a sigma",
   LoadingSubtitle = "by Arda",
   ConfigurationSaving = {
      Enabled = true,
      FolderName = nil, -- Create a custom folder for your hub/game
      FileName = "Big Hub"
   },
   Discord = {
      Enabled = false,
      Invite = "noinvitelink", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ABCD would be ABCD
      RememberJoins = true -- Set this to false to make them join the discord every time they load it up
   },
   KeySystem = false, -- Set this to true to use our key system
   KeySettings = {
      Title = "Untitled",
      Subtitle = "Key System",
      Note = "No method of obtaining the key is provided",
      FileName = "Key", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
      SaveKey = true, -- The user's key will be saved, but if you change the key, they will be unable to use your script
      GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = {"Hello"} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
   }
})

local Tab = Window:CreateTab("Gas and Blades", 4483362458) -- Title, Image
local Section = Tab:CreateSection("The rizzlers")

local Button = Tab:CreateButton({
   Name = "Blades(Infinity)",
   Callback = function()
   while true do
game.Workspace.ashleyschafy.Humanoid.Gear.Blades.Value = 8
wait(1)
end
   end,
})

local Button = Tab:CreateButton({
   Name = "Gas(Infinity)",
   Callback = function()
   while true do
game.Workspace.ashleyschafy.Humanoid.Gear.Upgrades.GasEfficiency.Value = 0
wait(1)
end
   end,
})

local Button = Tab:CreateButton({
   Name = "God",
   Callback = function()
   while true do
game.Workspace.ashleyschafy.Humanoid.God.Value = true
wait(1)
end
   end,
})

local Button = Tab:CreateButton({
   Name = "ESP",
   Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/Lucasfin000/SpaceHub/main/UESP'))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Infınıty Yield",
   Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Dex Explorer",
   Callback = function()
--[[
	WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
]]
loadstring(game:HttpGet('https://ithinkimandrew.site/scripts/tools/dark-dex.lua'))()
   end,
})

local Tab = Window:CreateTab("Skills", 4483362458) -- Title, Image
local Section = Tab:CreateSection("Erm what the sigma")

local Button = Tab:CreateButton({
   Name = "Impulse",
   Callback = function()
   while true do
game.Workspace.ashleyschafy.Humanoid.Gear.Skills.Impulse.Value = true
wait(1)
end
   end,
})

local Button = Tab:CreateButton({
   Name = "Dodge",
   Callback = function()
   while true do
game.Workspace.ashleyschafy.Humanoid.Gear.Skills.Dodge.Value = true
wait(1)
end
   end,
})

local Button = Tab:CreateButton({
   Name = "Arm Cut",
   Callback = function()
   while true do
game.Workspace.ashleyschafy.Humanoid.Gear.Skills.Counter.Value = true
wait(1)
end
   end,
})

local Button = Tab:CreateButton({
   Name = "Blade Throw",
   Callback = function()
   while true do
game.Workspace.ashleyschafy.Humanoid.Gear.Skills.BladeThrow.Value = true
wait(1)
end
   end,
})

local Button = Tab:CreateButton({
   Name = "Super Jump",
   Callback = function()
   while true do
game.Workspace.ashleyschafy.Humanoid.Gear.Skills.SuperJump.Value = true
wait(1)
end
   end,
})

local Button = Tab:CreateButton({
   Name = "Hand Cut",
   Callback = function()
   while true do
game.Workspace.ashleyschafy.Humanoid.Gear.Skills.HandCut.Value = true
wait(1)
end
   end,
})

local Button = Tab:CreateButton({
   Name = "Handcut 2",
   Callback = function()
   while true do
game.Workspace.ashleyschafy.Humanoid.Gear.Skills.HandCutMk2.Value = true
wait(1)
end
   end,
})
