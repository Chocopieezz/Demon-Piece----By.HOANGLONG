-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Menu1 = Instance.new("Frame")
local UIGradient = Instance.new("UIGradient")
local Menuname = Instance.new("TextLabel")
local INY = Instance.new("TextButton")
local exit = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Menu1.Name = "Menu1"
Menu1.Parent = ScreenGui
Menu1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Menu1.BorderColor3 = Color3.fromRGB(0, 0, 0)
Menu1.BorderSizePixel = 0
Menu1.Position = UDim2.new(0.222696245, 0, 0.302729517, 0)
Menu1.Size = UDim2.new(0, 290, 0, 239)
Menu1.Active = true
Menu1.Visible = true

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(76, 76, 76)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(53, 53, 53))}
UIGradient.Rotation = 90
UIGradient.Parent = Menu1

Menuname.Name = "Menuname"
Menuname.Parent = Menu1
Menuname.BackgroundColor3 = Color3.fromRGB(29, 29, 29)
Menuname.BorderColor3 = Color3.fromRGB(255, 255, 255)
Menuname.BorderSizePixel = 0
Menuname.Size = UDim2.new(0, 290, 0, 50)
Menuname.Font = Enum.Font.SourceSansBold
Menuname.Text = "Flying Demon Piece - - BY.HOANGLONG"
Menuname.TextColor3 = Color3.fromRGB(194, 129, 0)
Menuname.TextSize = 19.000
Menuname.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Menuname.TextWrapped = true

INY.Name = "INY"
INY.Parent = Menu1
INY.BackgroundColor3 = Color3.fromRGB(85, 170, 255)
INY.BorderColor3 = Color3.fromRGB(0, 0, 0)
INY.BorderSizePixel = 0
INY.Position = UDim2.new(0.334482759, 0, 0.426778257, 0)
INY.Size = UDim2.new(0, 95, 0, 55)
INY.Font = Enum.Font.SourceSansBold
INY.Text = "ON"
INY.TextColor3 = Color3.fromRGB(0, 0, 0)
INY.TextSize = 30.000
INY.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
INY.TextStrokeTransparency = 0.000
INY.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://https://raw.githubusercontent.com/Chocopieezz/HOANGLONG/main/HOANGLONG.txt"))()
end)

exit.Name = "exit"
exit.Parent = Menu1
exit.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
exit.BorderColor3 = Color3.fromRGB(0, 0, 0)
exit.BorderSizePixel = 0
exit.Position = UDim2.new(0.872413695, 0, 0.88702929, 0)
exit.Size = UDim2.new(0, 37, 0, 27)
exit.Font = Enum.Font.SourceSansBold
exit.Text = "x"
exit.TextColor3 = Color3.fromRGB(0, 0, 0)
exit.TextSize = 30.000
exit.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
exit.TextStrokeTransparency = 0.000
exit.MouseButton1Down:Connect(function()
exit.Visible = true
end)
