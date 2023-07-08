local Library = loadstring(Game:HttpGet("https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/wizard"))()

local PhantomForcesWindow = Library:NewWindow("V4 Hub")

local KillingCheats = PhantomForcesWindow:NewSection("Race V4")

KillingCheats:CreateButton("Đền Thờ", function()
Game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(28286.35546875, 14895.3017578125, 102.62469482421875)
end)

local trial = PhantomForcesWindow:NewSection("Auto Trials")

trial:CreateButton("Auto Angel Trial", function()         game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Workspace.Map.SkyTrial.Model.FinishPart.CFrame
end)

trial:CreateButton("Auto Rabbit Trial", function()         game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Map.MinkTrial.Ceiling.CFrame * CFrame.new(0,-5,0)
end)

trial:CreateButton("Auto Cyborg Trial", function()        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,300,0)
end)
