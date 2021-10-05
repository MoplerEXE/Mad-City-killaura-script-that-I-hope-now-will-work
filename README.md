--[[Credits to Mopler#7791 . Please dont make linkvertise/other boost shit. If you want to add my script in your script/script gui then discuss me about this please. 
If someone want to suggest me something then add me.]]--
local plr = game.Players.LocalPlayer
local char = plr.Character
_G.rph = true
while _G.rph do
    Players = game:GetService("Players")
			pcall(function()
			for i, player in pairs(Players:GetPlayers()) do
local A_1 = "SHOTTY"
local A_2 = game:GetService("Workspace")[player.Name].Head
local Event = game:GetService("ReplicatedStorage").Event
Event:FireServer(A_1, A_2)
wait(0.3)
end
end)
wait(0.3)
end
