local ScreenGui = Instance.new("ScreenGui")
local main = Instance.new("ImageLabel")
local UIGradient = Instance.new("UIGradient")
local Submit = Instance.new("TextButton")
local Imput = Instance.new("TextBox")
local PremiumOpen = Instance.new("TextButton")
local Close = Instance.new("TextButton")
local Roundify = Instance.new("ImageLabel")
local premiummain = Instance.new("ImageLabel")
local UIGradient_2 = Instance.new("UIGradient")
local PremiumSubmit = Instance.new("TextButton")
local PremiumImput = Instance.new("TextBox")
local PremiumClose = Instance.new("TextButton")
local Roundify_2 = Instance.new("ImageLabel")

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

main.Name = "main"
main.Parent = ScreenGui
main.AnchorPoint = Vector2.new(0.5, 0.5)
main.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
main.BackgroundTransparency = 1.000
main.Position = UDim2.new(0.499845535, 0, 0.619944692, 0)
main.Size = UDim2.new(0.423921257, 24, 0.364290088, 24)
main.Image = "rbxassetid://3570695787"
main.ScaleType = Enum.ScaleType.Slice
main.SliceCenter = Rect.new(100, 100, 100, 100)
main.SliceScale = 0.120

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 0, 0)), ColorSequenceKeypoint.new(0.50, Color3.fromRGB(255, 0, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 0, 0))}
UIGradient.Parent = main
Submit.Name = "Submit"
Submit.Parent = main
Submit.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Submit.BackgroundTransparency = 1.000
Submit.BorderSizePixel = 0
Submit.Position = UDim2.new(0.239500314, 0, 0.688054144, 0)
Submit.Size = UDim2.new(0, 436, 0, 65)
Submit.Font = Enum.Font.SourceSans
Submit.Text = "Login"
Submit.TextColor3 = Color3.fromRGB(0, 0, 0)
Submit.TextSize = 40.000

Imput.Name = "Imput"
Imput.Parent = main
Imput.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Imput.BackgroundTransparency = 1.000
Imput.BorderSizePixel = 0
Imput.Position = UDim2.new(0.239641532, 0, 0.347450197, 0)
Imput.Size = UDim2.new(0, 437, 0, 78)
Imput.Font = Enum.Font.SourceSans
Imput.PlaceholderColor3 = Color3.fromRGB(0, 0, 0)
Imput.PlaceholderText = "Key"
Imput.Text = ""
Imput.TextColor3 = Color3.fromRGB(0, 0, 0)
Imput.TextSize = 40.000

PremiumOpen.Name = "PremiumOpen"
PremiumOpen.Parent = main
PremiumOpen.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PremiumOpen.BackgroundTransparency = 1.000
PremiumOpen.Position = UDim2.new(0.380700648, 0, 0.0531891882, 0)
PremiumOpen.Size = UDim2.new(0, 200, 0, 50)
PremiumOpen.Font = Enum.Font.SourceSans
PremiumOpen.Text = "Premium Key"
PremiumOpen.TextColor3 = Color3.fromRGB(0, 0, 0)
PremiumOpen.TextSize = 40.000

Close.Name = "Close"
Close.Parent = main
Close.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Close.BackgroundTransparency = 1.000
Close.BorderSizePixel = 0
Close.Position = UDim2.new(0.948639154, 0, 0.0182017088, 0)
Close.Size = UDim2.new(0, 35, 0, 49)
Close.Font = Enum.Font.SourceSans
Close.Text = ""
Close.TextColor3 = Color3.fromRGB(0, 0, 0)
Close.TextSize = 14.000

Roundify.Name = "Roundify"
Roundify.Parent = Close
Roundify.AnchorPoint = Vector2.new(0.5, 0.5)
Roundify.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Roundify.BackgroundTransparency = 1.000
Roundify.Position = UDim2.new(0.426391602, 0, 0.59608531, 0)
Roundify.Size = UDim2.new(0.589722812, 24, 0.454064161, 24)
Roundify.Image = "http://www.roblox.com/asset/?id=2307116600"
Roundify.ScaleType = Enum.ScaleType.Slice
Roundify.SliceCenter = Rect.new(100, 100, 100, 100)
Roundify.SliceScale = 0.120

premiummain.Name = "premiummain"
premiummain.Parent = ScreenGui
premiummain.AnchorPoint = Vector2.new(0.5, 0.5)
premiummain.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
premiummain.BackgroundTransparency = 1.000
premiummain.Position = UDim2.new(0.499947906, 0, 0.212425411, 0)
premiummain.Size = UDim2.new(0.230729163, 24, 0.262004912, 24)
premiummain.Image = "rbxassetid://3570695787"
premiummain.Visible = false
premiummain.ScaleType = Enum.ScaleType.Slice
premiummain.SliceCenter = Rect.new(100, 100, 100, 100)
premiummain.SliceScale = 0.120

UIGradient_2.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 0, 0)), ColorSequenceKeypoint.new(0.30, Color3.fromRGB(255, 0, 0)), ColorSequenceKeypoint.new(0.70, Color3.fromRGB(255, 0, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 0, 0))}
UIGradient_2.Parent = premiummain

PremiumSubmit.Name = "PremiumSubmit"
PremiumSubmit.Parent = premiummain
PremiumSubmit.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PremiumSubmit.BackgroundTransparency = 1.000
PremiumSubmit.Position = UDim2.new(0.284796566, 0, 0.605134428, 0)
PremiumSubmit.Size = UDim2.new(0, 200, 0, 64)
PremiumSubmit.Font = Enum.Font.SourceSans
PremiumSubmit.Text = "Login"
PremiumSubmit.TextColor3 = Color3.fromRGB(0, 0, 0)
PremiumSubmit.TextSize = 40.000

PremiumImput.Name = "PremiumImput"
PremiumImput.Parent = premiummain
PremiumImput.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PremiumImput.BackgroundTransparency = 1.000
PremiumImput.Position = UDim2.new(0.192719489, 0, 0.11483781, 0)
PremiumImput.Size = UDim2.new(0, 287, 0, 62)
PremiumImput.Font = Enum.Font.SourceSans
PremiumImput.PlaceholderColor3 = Color3.fromRGB(0, 0, 0)
PremiumImput.PlaceholderText = "Premium Key"
PremiumImput.Text = ""
PremiumImput.TextColor3 = Color3.fromRGB(0, 0, 0)
PremiumImput.TextSize = 40.000

PremiumClose.Name = "PremiumClose"
PremiumClose.Parent = premiummain
PremiumClose.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PremiumClose.BackgroundTransparency = 1.000
PremiumClose.BorderSizePixel = 0
PremiumClose.Position = UDim2.new(0.895074844, 0, 0, 0)
PremiumClose.Size = UDim2.new(0, 49, 0, 50)
PremiumClose.Font = Enum.Font.SourceSans
PremiumClose.TextColor3 = Color3.fromRGB(0, 0, 0)
PremiumClose.TextSize = 14.000
PremiumClose.TextTransparency = 1.000

Roundify_2.Name = "Roundify"
Roundify_2.Parent = PremiumClose
Roundify_2.AnchorPoint = Vector2.new(0.5, 0.5)
Roundify_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Roundify_2.BackgroundTransparency = 1.000
Roundify_2.Position = UDim2.new(0.5, 0, 0.500000179, 0)
Roundify_2.Size = UDim2.new(0.510204077, 24, 0.52000016, 24)
Roundify_2.Image = "http://www.roblox.com/asset/?id=2307116600"
Roundify_2.ScaleType = Enum.ScaleType.Slice
Roundify_2.SliceCenter = Rect.new(100, 100, 100, 100)
Roundify_2.SliceScale = 0.120





















































































































































































































































































































































































Submit.MouseButton1Down:connect(function()
if Imput.Text == "TheNormalKeyIsNotSoGoodLikePremiumKeyButItsNormalXD" or
   game.Players.LucaMichael06.Character then
main.Visible = false
premiummain.Visible = false
wait(0.4)
getgenv().LoadGui = false;
loadstring(game:HttpGet("https://raw.githubusercontent.com/LucaMichael06/Luca/main/README.md" ))()
wait(1)
getgenv().LoadGui = true;
end
end)
Submit.MouseButton1Down:connect(function()
game.Players.Kev2345671:Kick("UR BLACKLISTED")
end)
Submit.MouseButton1Down:connect(function()
game.Players.Kinderpopo:Kick("UR BLACKLISTED")
end)
Submit.MouseButton1Down:connect(function()
if game.Players.Kev2345671.Character then
main.Visible = false
premiummain.Visible = false
getgenv().LoadGui = false;
wait(0.4)
loadstring(game:HttpGet("https://raw.githubusercontent.com/LucaMichael06/Luca/main/README.md" ))()
wait(1)
getgenv().LoadGui = true;
end
end)
Close.MouseButton1Down:connect(function()
premiummain.Visible = false
main.Visible = false
end)
PremiumClose.MouseButton1Down:connect(function()
premiummain.Visible = false
end)
PremiumSubmit.MouseButton1Down:connect(function()
if PremiumImput.Text == "PremiumKeyIsBetterThenNormalButItsPremiumXD" or
   game.Players.LucaMichael06.Character then
main.Visible = false
premiummain.Visible = false
getgenv().LoadGui = false;
wait(0.4)
loadstring(game:HttpGet("https://raw.githubusercontent.com/LucaMichael06/Luca/main/README.md" ))()
wait(1)
getgenv().LoadGui = true;
end
end)
PremiumSubmit.MouseButton1Down:connect(function()
game.Players.Kinderpopo:Kick("UR BLACKLISTED")
end)
PremiumSubmit.MouseButton1Down:connect(function()
if game.Players.Kev2345671.Character then
main.Visible = false
premiummain.Visible = false
getgenv().LoadGui = false;
wait(0.4)
loadstring(game:HttpGet("https://raw.githubusercontent.com/LucaMichael06/Luca/main/README.md" ))()
wait(1)
getgenv().LoadGui = true;
end
end)
PremiumOpen.MouseButton1Down:connect(function()
premiummain.Visible = true;
end)
