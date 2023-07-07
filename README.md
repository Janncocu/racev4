local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "Race Hub", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

local Tab = Window:MakeTab({
	Name = "Main",
	Icon = "rbxassetid://13981076835",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Made By Jann"
})

Tab:AddButton({
	Name = "Teleport To Timple Of Time",
	Callback = function()
Game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(28286.35546875, 14895.3017578125, 102.62469482421875)
  	end    
})

local Section = Tab:AddSection({
	Name = "Auto Trials"
})

Tab:AddButton({
	Name = "Auto Complete Angel Trial",
	Callback = function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Workspace.Map.SkyTrial.Model.FinishPart.CFrame
  	end    
})

Tab:AddButton({
	Name = "Auto Complete Rabbit Trial",
	Callback = function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Map.MinkTrial.Ceiling.CFrame * CFrame.new(0,-5,0)
  	end    
})

Tab:AddButton({
   Name = "Auto Complete Cyborg Trial",
   Callback = function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,300,0)
   end
})

local Section = Tab:AddSection({
	Name = "Comming"
})
