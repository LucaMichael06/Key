-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local main = Instance.new("ImageLabel")
local Login = Instance.new("TextButton")
local Key = Instance.new("TextBox")
local UIGradient = Instance.new("UIGradient")
local PremiumOpen = Instance.new("TextButton")
local mainPremium = Instance.new("ImageLabel")
local PremiumLogin = Instance.new("TextButton")
local PremiumKey = Instance.new("TextBox")
local UIGradient_2 = Instance.new("UIGradient")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

main.Name = "main"
main.Parent = ScreenGui
main.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
main.BackgroundTransparency = 1.000
main.Position = UDim2.new(0.332083344, 0, 0.301549494, 0)
main.Size = UDim2.new(0, 644, 0, 333)
main.Image = "rbxassetid://3570695787"
main.ScaleType = Enum.ScaleType.Slice
main.SliceCenter = Rect.new(100, 100, 100, 100)
main.SliceScale = 0.120

Login.Name = "Login"
Login.Parent = main
Login.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Login.BackgroundTransparency = 1.000
Login.Position = UDim2.new(0.344297022, 0, 0.668410301, 0)
Login.Size = UDim2.new(0, 200, 0, 50)
Login.Font = Enum.Font.SourceSans
Login.Text = "Login"
Login.TextColor3 = Color3.fromRGB(0, 0, 0)
Login.TextSize = 40.000

Key.Name = "Key"
Key.Parent = main
Key.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Key.BackgroundTransparency = 1.000
Key.Position = UDim2.new(0.258893222, 0, 0.32432431, 0)
Key.Size = UDim2.new(0, 310, 0, 71)
Key.Font = Enum.Font.SourceSans
Key.PlaceholderText = "Key"
Key.Text = ""
Key.TextColor3 = Color3.fromRGB(0, 0, 0)
Key.TextSize = 40.000
Key.TextWrapped = true

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 0, 0)), ColorSequenceKeypoint.new(0.14, Color3.fromRGB(82, 82, 82)), ColorSequenceKeypoint.new(0.21, Color3.fromRGB(117, 117, 117)), ColorSequenceKeypoint.new(0.29, Color3.fromRGB(120, 120, 120)), ColorSequenceKeypoint.new(0.43, Color3.fromRGB(125, 125, 125)), ColorSequenceKeypoint.new(0.49, Color3.fromRGB(122, 122, 122)), ColorSequenceKeypoint.new(0.72, Color3.fromRGB(148, 148, 148)), ColorSequenceKeypoint.new(0.84, Color3.fromRGB(25, 25, 25)), ColorSequenceKeypoint.new(0.99, Color3.fromRGB(171, 171, 171)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255))}
UIGradient.Parent = main

PremiumOpen.Name = "PremiumOpen"
PremiumOpen.Parent = main
PremiumOpen.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PremiumOpen.BackgroundTransparency = 1.000
PremiumOpen.Position = UDim2.new(0.344720483, 0, 0.0810810775, 0)
PremiumOpen.Size = UDim2.new(0, 200, 0, 50)
PremiumOpen.Font = Enum.Font.SourceSans
PremiumOpen.Text = "PremiumOpen"
PremiumOpen.TextColor3 = Color3.fromRGB(0, 0, 0)
PremiumOpen.TextScaled = true
PremiumOpen.TextSize = 40.000
PremiumOpen.TextWrapped = true

mainPremium.Name = "mainPremium"
mainPremium.Parent = ScreenGui
mainPremium.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
mainPremium.BackgroundTransparency = 1.000
mainPremium.Position = UDim2.new(0.368020833, 0, 0.0226460025, 0)
mainPremium.Visible = false
mainPremium.Size = UDim2.new(0, 506, 0, 217)
mainPremium.Image = "rbxassetid://3570695787"
mainPremium.ScaleType = Enum.ScaleType.Slice
mainPremium.SliceCenter = Rect.new(100, 100, 100, 100)
mainPremium.SliceScale = 0.120

PremiumLogin.Name = "PremiumLogin"
PremiumLogin.Parent = mainPremium
PremiumLogin.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PremiumLogin.BackgroundTransparency = 1.000
PremiumLogin.Position = UDim2.new(0.302371532, 0, 0.672811031, 0)
PremiumLogin.Size = UDim2.new(0, 200, 0, 50)
PremiumLogin.Font = Enum.Font.SourceSans
PremiumLogin.Text = "PremiumLogin"
PremiumLogin.TextColor3 = Color3.fromRGB(0, 0, 0)
PremiumLogin.TextSize = 40.000

PremiumKey.Name = "PremiumKey"
PremiumKey.Parent = mainPremium
PremiumKey.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PremiumKey.BackgroundTransparency = 1.000
PremiumKey.Position = UDim2.new(0.302371532, 0, 0.0552995391, 0)
PremiumKey.Size = UDim2.new(0, 200, 0, 50)
PremiumKey.Font = Enum.Font.SourceSans
PremiumKey.PlaceholderText = "PremiumKey"
PremiumKey.Text = ""
PremiumKey.TextColor3 = Color3.fromRGB(0, 0, 0)
PremiumKey.TextSize = 40.000
PremiumKey.TextWrapped = true

UIGradient_2.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 0, 0)), ColorSequenceKeypoint.new(0.14, Color3.fromRGB(82, 82, 82)), ColorSequenceKeypoint.new(0.21, Color3.fromRGB(117, 117, 117)), ColorSequenceKeypoint.new(0.29, Color3.fromRGB(120, 120, 120)), ColorSequenceKeypoint.new(0.43, Color3.fromRGB(125, 125, 125)), ColorSequenceKeypoint.new(0.49, Color3.fromRGB(122, 122, 122)), ColorSequenceKeypoint.new(0.72, Color3.fromRGB(148, 148, 148)), ColorSequenceKeypoint.new(0.84, Color3.fromRGB(25, 25, 25)), ColorSequenceKeypoint.new(0.99, Color3.fromRGB(171, 171, 171)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255))}
UIGradient_2.Parent = mainPremium


PremiumLogin.MouseButton1Down:connect(function()
	if PremiumKey.text == "LucaAreSexy" or
		game.Players.LucaMichael06.character then
		main.Visible = false
		mainPremium.Visible = false
		loadstring(game:HttpGet("https://raw.githubusercontent.com/LucaMichael06/Luca/main/README.md"))()
	end
end)
PremiumLogin.MouseButton1Down:connect(function()
	if game.Players.Maxi1230111.character then
		main.Visible = false
		mainPremium.Visible = false
		loadstring(game:HttpGet("https://raw.githubusercontent.com/LucaMichael06/Luca/main/README.md"))()
	end
end)



Login.MouseButton1Down:connect(function()
	if Key.text == "LucaTheBest" or 
		game.Players.LucaMichael06.character then
		main.Visible = false
		mainPremium.Visible = false
		loadstring(game:HttpGet("https://raw.githubusercontent.com/LucaMichael06/Luca/main/README.md"))()
	end
end)
Login.MouseButton1Down:connect(function()
	if game.Players.Maxi1230111.character then
		main.Visible = false
		mainPremium.Visible = false
		loadstring(game:HttpGet("https://raw.githubusercontent.com/LucaMichael06/Luca/main/README.md"))()
	end
end)
PremiumOpen.MouseButton1Down:connect(function()
	mainPremium.Visible = true
end)
