-- Credit: SG#6284
-- Version: X

-- Instances:

local RocatHub = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local MM2 = Instance.new("TextButton")
local NameFrame1 = Instance.new("Frame")
local NameFrame4 = Instance.new("Frame")
local NameFrame3 = Instance.new("Frame")
local NameFrame2 = Instance.new("Frame")
local HotScripts = Instance.new("TextLabel")
local GamesScripts = Instance.new("TextLabel")
local BloxFruit1 = Instance.new("TextButton")
local BloxFruit2 = Instance.new("TextButton")
local PetSimX = Instance.new("TextButton")
local AdoptMe = Instance.new("TextButton")
local DesSim = Instance.new("TextButton")
local SlapBattles = Instance.new("TextButton")
local MyRes = Instance.new("TextButton")
local BeeSwarm = Instance.new("TextButton")
local InfYield = Instance.new("TextButton")
local DarkDex = Instance.new("TextButton")
local NameFrame5 = Instance.new("Frame")
local ImageLabel = Instance.new("ImageLabel")
local Credit = Instance.new("TextLabel")
local RocatHubText = Instance.new("TextLabel")

--Properties:

RocatHub.Name = "RocatHub"
RocatHub.Parent = game.CoreGui
RocatHub.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Main.Name = "Main"
Main.Parent = RocatHub
Main.BackgroundColor3 = Color3.fromRGB(80, 80, 80)
Main.BorderSizePixel = 0
Main.Position = UDim2.new(0.278830975, 0, 0.142250508, 0)
Main.Size = UDim2.new(0.442338079, 0, 0.713375747, 0)

MM2.Name = "MM2"
MM2.Parent = Main
MM2.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
MM2.BorderSizePixel = 0
MM2.Position = UDim2.new(0.242857143, 0, 0.204750493, 0)
MM2.Size = UDim2.new(0.357142866, 0, 0.123256512, 0)
MM2.Font = Enum.Font.SourceSans
MM2.Text = "Murder Mystery 2"
MM2.TextColor3 = Color3.fromRGB(220, 220, 220)
MM2.TextScaled = true
MM2.TextSize = 14.000
MM2.TextWrapped = true
MM2.MouseButton1Down:connect(function()
	repeat wait() until game.Players.LocalPlayer.Character
	url = "https://raw.githubusercontent.com/xennyy/Xenny-Ware/main/loader.lua"
	loadstring(game:HttpGet(url))()
end)

NameFrame1.Name = "NameFrame1"
NameFrame1.Parent = Main
NameFrame1.BackgroundColor3 = Color3.fromRGB(65, 65, 65)
NameFrame1.Size = UDim2.new(1, 0, 0.121771231, 0)

NameFrame4.Name = "NameFrame4"
NameFrame4.Parent = Main
NameFrame4.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
NameFrame4.BorderColor3 = Color3.fromRGB(255, 255, 255)
NameFrame4.BorderSizePixel = 0
NameFrame4.Position = UDim2.new(0, 0, 0.945945442, 0)
NameFrame4.Size = UDim2.new(0.224999994, 0, 0.053802222, 0)

NameFrame3.Name = "NameFrame3"
NameFrame3.Parent = Main
NameFrame3.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
NameFrame3.BorderColor3 = Color3.fromRGB(255, 255, 255)
NameFrame3.BorderSizePixel = 0
NameFrame3.Position = UDim2.new(0, 0, 0.121771231, 0)
NameFrame3.Size = UDim2.new(0.224999994, 0, 0.848214567, 0)

NameFrame2.Name = "NameFrame2"
NameFrame2.Parent = Main
NameFrame2.BackgroundColor3 = Color3.fromRGB(65, 65, 65)
NameFrame2.BorderColor3 = Color3.fromRGB(255, 255, 255)
NameFrame2.BorderSizePixel = 0
NameFrame2.Position = UDim2.new(0, 0, 0.059040539, 0)
NameFrame2.Size = UDim2.new(1, 0, 0.0627306327, 0)

HotScripts.Name = "HotScripts"
HotScripts.Parent = Main
HotScripts.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
HotScripts.BorderSizePixel = 0
HotScripts.Position = UDim2.new(0, 0, 0.119047649, 0)
HotScripts.Size = UDim2.new(0.223214284, 0, 0.142250478, 0)
HotScripts.Font = Enum.Font.SourceSans
HotScripts.Text = "Hot scripts"
HotScripts.TextColor3 = Color3.fromRGB(255, 255, 255)
HotScripts.TextScaled = true
HotScripts.TextSize = 14.000
HotScripts.TextWrapped = true

GamesScripts.Name = "GamesScripts"
GamesScripts.Parent = Main
GamesScripts.BackgroundColor3 = Color3.fromRGB(80, 80, 80)
GamesScripts.BorderSizePixel = 0
GamesScripts.Position = UDim2.new(0.242857084, 0, 0.133445248, 0)
GamesScripts.Size = UDim2.new(0.207162589, 0, 0.0695617348, 0)
GamesScripts.Font = Enum.Font.SourceSans
GamesScripts.Text = "Games scripts"
GamesScripts.TextColor3 = Color3.fromRGB(255, 255, 255)
GamesScripts.TextScaled = true
GamesScripts.TextSize = 14.000
GamesScripts.TextWrapped = true

BloxFruit1.Name = "BloxFruit1"
BloxFruit1.Parent = Main
BloxFruit1.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
BloxFruit1.BorderSizePixel = 0
BloxFruit1.Position = UDim2.new(0.623214304, 0, 0.204750493, 0)
BloxFruit1.Size = UDim2.new(0.357142866, 0, 0.123256512, 0)
BloxFruit1.Font = Enum.Font.SourceSans
BloxFruit1.Text = "Blox Fruit (Fruit Rain)"
BloxFruit1.TextColor3 = Color3.fromRGB(220, 220, 220)
BloxFruit1.TextScaled = true
BloxFruit1.TextSize = 14.000
BloxFruit1.TextWrapped = true
BloxFruit1.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/UCsB5xC3", true))()
end)

BloxFruit2.Name = "BloxFruit2"
BloxFruit2.Parent = Main
BloxFruit2.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
BloxFruit2.BorderSizePixel = 0
BloxFruit2.Position = UDim2.new(0.242857143, 0, 0.359512419, 0)
BloxFruit2.Size = UDim2.new(0.357142866, 0, 0.123256512, 0)
BloxFruit2.Font = Enum.Font.SourceSans
BloxFruit2.Text = "Blox Fruit OP"
BloxFruit2.TextColor3 = Color3.fromRGB(220, 220, 220)
BloxFruit2.TextScaled = true
BloxFruit2.TextSize = 14.000
BloxFruit2.TextWrapped = true
BloxFruit2.MouseButton1Down:connect(function()
	loadstring(game:HttpGet"https://raw.githubusercontent.com/xDepressionx/Free-Script/main/AllScript.lua")()
end)

PetSimX.Name = "PetSimX"
PetSimX.Parent = Main
PetSimX.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
PetSimX.BorderSizePixel = 0
PetSimX.Position = UDim2.new(0.623214304, 0, 0.677964807, 0)
PetSimX.Size = UDim2.new(0.357142866, 0, 0.123256512, 0)
PetSimX.Font = Enum.Font.SourceSans
PetSimX.Text = "Pet Simulator X OP"
PetSimX.TextColor3 = Color3.fromRGB(220, 220, 220)
PetSimX.TextScaled = true
PetSimX.TextSize = 14.000
PetSimX.TextWrapped = true
PetSimX.MouseButton1Down:connect(function()
	loadstring(game:HttpGet"https://raw.githubusercontent.com/xDepressionx/Free-Script/main/AllScript.lua")()
end)

AdoptMe.Name = "AdoptMe"
AdoptMe.Parent = Main
AdoptMe.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
AdoptMe.BorderSizePixel = 0
AdoptMe.Position = UDim2.new(0.242857143, 0, 0.677964807, 0)
AdoptMe.Size = UDim2.new(0.357142866, 0, 0.123256512, 0)
AdoptMe.Font = Enum.Font.SourceSans
AdoptMe.Text = "Adopt Me OP"
AdoptMe.TextColor3 = Color3.fromRGB(220, 220, 220)
AdoptMe.TextScaled = true
AdoptMe.TextSize = 14.000
AdoptMe.TextWrapped = true
AdoptMe.MouseButton1Down:connect(function()
	getgenv().mainKey = "nil"

	local a,b,c,d,e=loadstring,request or http_request or (http and http.request) or (syn and syn.request),assert,tostring,"https://api.eclipsehub.xyz/auth"c(a and b,"Executor not Supported")a(b({Url=e.."\?\107e\121\61"..d(mainKey),Headers={["User-Agent"]="Eclipse"}}).Body)()
end)

DesSim.Name = "DesSim"
DesSim.Parent = Main
DesSim.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
DesSim.BorderSizePixel = 0
DesSim.Position = UDim2.new(0.623214304, 0, 0.514274359, 0)
DesSim.Size = UDim2.new(0.357142866, 0, 0.123256512, 0)
DesSim.Font = Enum.Font.SourceSans
DesSim.Text = "Destruction Simulator OP"
DesSim.TextColor3 = Color3.fromRGB(220, 220, 220)
DesSim.TextScaled = true
DesSim.TextSize = 14.000
DesSim.TextWrapped = true
DesSim.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/FadeRemix/RND-Games/main/DestructionSim.lua"))()
end)

SlapBattles.Name = "SlapBattles"
SlapBattles.Parent = Main
SlapBattles.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
SlapBattles.BorderSizePixel = 0
SlapBattles.Position = UDim2.new(0.242857143, 0, 0.514274359, 0)
SlapBattles.Size = UDim2.new(0.357142866, 0, 0.123256512, 0)
SlapBattles.Font = Enum.Font.SourceSans
SlapBattles.Text = "Slap Battles OP"
SlapBattles.TextColor3 = Color3.fromRGB(220, 220, 220)
SlapBattles.TextScaled = true
SlapBattles.TextSize = 14.000
SlapBattles.TextWrapped = true
SlapBattles.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/dizyhvh/slap_battles_gui/main/0.lua"))()
end)

MyRes.Name = "MyRes"
MyRes.Parent = Main
MyRes.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
MyRes.BorderSizePixel = 0
MyRes.Position = UDim2.new(0.623214304, 0, 0.359512419, 0)
MyRes.Size = UDim2.new(0.357142866, 0, 0.123256512, 0)
MyRes.Font = Enum.Font.SourceSans
MyRes.Text = "My Restaurant OP"
MyRes.TextColor3 = Color3.fromRGB(220, 220, 220)
MyRes.TextScaled = true
MyRes.TextSize = 14.000
MyRes.TextWrapped = true
MyRes.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("http://void-scripts.com/Scripts/myRest.lua"))() 
end)

BeeSwarm.Name = "BeeSwarm"
BeeSwarm.Parent = Main
BeeSwarm.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
BeeSwarm.BorderSizePixel = 0
BeeSwarm.Position = UDim2.new(0.242857158, 0, 0.844631493, 0)
BeeSwarm.Size = UDim2.new(0.357142866, 0, 0.123256512, 0)
BeeSwarm.Font = Enum.Font.SourceSans
BeeSwarm.Text = "Bee Swarm Simulator OP"
BeeSwarm.TextColor3 = Color3.fromRGB(220, 220, 220)
BeeSwarm.TextScaled = true
BeeSwarm.TextSize = 14.000
BeeSwarm.TextWrapped = true
BeeSwarm.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/NukeVsCity/TheALLHACKLoader/main/NukeLoader"))()
end)

InfYield.Name = "InfYield"
InfYield.Parent = Main
InfYield.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
InfYield.BorderSizePixel = 0
InfYield.Position = UDim2.new(0.0142857153, 0, 0.282131433, 0)
InfYield.Size = UDim2.new(0.192857146, 0, 0.123256512, 0)
InfYield.Font = Enum.Font.SourceSans
InfYield.Text = "Inf Yield"
InfYield.TextColor3 = Color3.fromRGB(220, 220, 220)
InfYield.TextScaled = true
InfYield.TextSize = 14.000
InfYield.TextWrapped = true
InfYield.MouseButton1Down:connect(function()
	local GUI = Instance.new("ScreenGui")
	local OpenFrame = Instance.new("Frame")
	local OpenButton = Instance.new("TextButton")
	local OpenBeautyFrame = Instance.new("Frame")
	local MainFrame = Instance.new("Frame")
	local MainFrameBeautyA = Instance.new("Frame")
	local CloseButton = Instance.new("TextButton")
	local EXPLOIT1 = Instance.new("TextButton")
	local MainFrameCenterBeautyA = Instance.new("Frame")
	local MainFrameCenterBeautyA_2 = Instance.new("Frame")
	local EXPLOIT5 = Instance.new("TextButton")
	local EXPLOIT9 = Instance.new("TextButton")
	local EXPLOIT6 = Instance.new("TextButton")
	local EXPLOIT7 = Instance.new("TextButton")
	local EXPLOIT8 = Instance.new("TextButton")
	local EXPLOIT10 = Instance.new("TextButton")
	local EXPLOIT11 = Instance.new("TextButton")
	local EXPLOIT12 = Instance.new("TextButton")
	local EXPLOIT2 = Instance.new("TextButton")
	local EXPLOIT3 = Instance.new("TextButton")
	local EXPLOIT4 = Instance.new("TextButton")
	local MainFrameBeautyB = Instance.new("Frame")

	GUI.Name = "GUI"
	GUI.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

	OpenFrame.Name = "OpenFrame"
	OpenFrame.Parent = GUI
	OpenFrame.Active = true
	OpenFrame.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
	OpenFrame.BorderSizePixel = 0
	OpenFrame.Position = UDim2.new(0, 0, 0.629155695, 0)
	OpenFrame.Size = UDim2.new(0, 72, 0, 27)

	OpenButton.Name = "OpenButton"
	OpenButton.Parent = OpenFrame
	OpenButton.BackgroundColor3 = Color3.fromRGB(170, 170, 127)
	OpenButton.BackgroundTransparency = 1.000
	OpenButton.BorderSizePixel = 0
	OpenButton.Position = UDim2.new(0.0305736773, 0, 0.116329789, 0)
	OpenButton.Size = UDim2.new(0, 66, 0, 20)
	OpenButton.Font = Enum.Font.Cartoon
	OpenButton.Text = "Open"
	OpenButton.TextColor3 = Color3.fromRGB(255, 255, 255)
	OpenButton.TextScaled = true
	OpenButton.TextSize = 14.000
	OpenButton.TextWrapped = true
	OpenButton.MouseButton1Down:connect(function()
		MainFrame.Visible = true
		OpenFrame.Visible = false
		MainFrameBeautyA.Visible = true
		MainFrameBeautyB.Visible = true
		MainFrameCenterBeautyA_2.Visible = true
		MainFrameCenterBeautyA.Visible = true
	end)

	OpenBeautyFrame.Name = "OpenBeautyFrame"
	OpenBeautyFrame.Parent = OpenFrame
	OpenBeautyFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	OpenBeautyFrame.BorderSizePixel = 0
	OpenBeautyFrame.Position = UDim2.new(0.988907099, 0, -0.148148149, 0)
	OpenBeautyFrame.Size = UDim2.new(0, 3, 0, 33)

	MainFrame.Name = "MainFrame"
	MainFrame.Parent = GUI
	MainFrame.Active = true
	MainFrame.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
	MainFrame.BorderSizePixel = 0
	MainFrame.Position = UDim2.new(0.30754894, 0, 0.235294133, 0)
	MainFrame.Size = UDim2.new(0, 412, 0, 263)
	MainFrame.Visible = false
	MainFrame.Draggable = true

	MainFrameBeautyA.Name = "MainFrameBeautyA"
	MainFrameBeautyA.Parent = MainFrame
	MainFrameBeautyA.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
	MainFrameBeautyA.BorderSizePixel = 0
	MainFrameBeautyA.Size = UDim2.new(0, 412, 0, 22)
	MainFrameBeautyA.Visible = false

	CloseButton.Name = "CloseButton"
	CloseButton.Parent = MainFrameBeautyA
	CloseButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	CloseButton.BackgroundTransparency = 1.000
	CloseButton.BorderSizePixel = 0
	CloseButton.Position = UDim2.new(0.905339777, 0, 0, 0)
	CloseButton.Size = UDim2.new(0, 39, 0, 22)
	CloseButton.Font = Enum.Font.Cartoon
	CloseButton.Text = "Close"
	CloseButton.TextColor3 = Color3.fromRGB(255, 0, 0)
	CloseButton.TextScaled = true
	CloseButton.TextSize = 14.000
	CloseButton.TextWrapped = true
	CloseButton.MouseButton1Down:connect(function()
		OpenFrame.Visible = true
		MainFrame.Visible = false
		MainFrameBeautyA.Visible = false
		MainFrameBeautyB.Visible = false
		MainFrameCenterBeautyA_2.Visible = false
		MainFrameCenterBeautyA.Visible = false
	end)

	EXPLOIT1.Name = "EXPLOIT1"
	EXPLOIT1.Parent = MainFrame
	EXPLOIT1.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
	EXPLOIT1.BorderSizePixel = 0
	EXPLOIT1.Position = UDim2.new(0.024271844, 0, 0.129277572, 0)
	EXPLOIT1.Size = UDim2.new(0, 92, 0, 32)
	EXPLOIT1.Font = Enum.Font.Cartoon
	EXPLOIT1.Text = "My Other GUI"
	EXPLOIT1.TextColor3 = Color3.fromRGB(255, 255, 255)
	EXPLOIT1.TextScaled = true
	EXPLOIT1.TextSize = 14.000
	EXPLOIT1.TextWrapped = true
	EXPLOIT1.MouseButton1Down:connect(function()
		loadstring(game:HttpGet(('https://pastebin.com/raw/HCsqYzwa'),true))()
	end)

	MainFrameCenterBeautyA.Name = "MainFrameCenterBeautyA"
	MainFrameCenterBeautyA.Parent = MainFrame
	MainFrameCenterBeautyA.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
	MainFrameCenterBeautyA.BorderSizePixel = 0
	MainFrameCenterBeautyA.Position = UDim2.new(0.288834959, 0, 0.129277572, 0)
	MainFrameCenterBeautyA.Size = UDim2.new(0, 8, 0, 185)
	MainFrameCenterBeautyA.Visible = false

	MainFrameCenterBeautyA_2.Name = "MainFrameCenterBeautyA"
	MainFrameCenterBeautyA_2.Parent = MainFrame
	MainFrameCenterBeautyA_2.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
	MainFrameCenterBeautyA_2.BorderSizePixel = 0
	MainFrameCenterBeautyA_2.Position = UDim2.new(0.699029148, 0, 0.129277557, 0)
	MainFrameCenterBeautyA_2.Size = UDim2.new(0, 8, 0, 185)
	MainFrameCenterBeautyA_2.Visible = false

	EXPLOIT5.Name = "EXPLOIT5"
	EXPLOIT5.Parent = MainFrame
	EXPLOIT5.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
	EXPLOIT5.BorderSizePixel = 0
	EXPLOIT5.Position = UDim2.new(0.388349503, 0, 0.129277572, 0)
	EXPLOIT5.Size = UDim2.new(0, 92, 0, 32)
	EXPLOIT5.Font = Enum.Font.Cartoon
	EXPLOIT5.Text = "JailTabs"
	EXPLOIT5.TextColor3 = Color3.fromRGB(255, 255, 255)
	EXPLOIT5.TextScaled = true
	EXPLOIT5.TextSize = 14.000
	EXPLOIT5.TextWrapped = true
	EXPLOIT5.MouseButton1Down:connect(function()
		loadstring(game:HttpGet(('https://pastebin.com/raw/aV6LcSGf'),true))()
	end)

	EXPLOIT9.Name = "EXPLOIT9"
	EXPLOIT9.Parent = MainFrame
	EXPLOIT9.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
	EXPLOIT9.BorderSizePixel = 0
	EXPLOIT9.Position = UDim2.new(0.75242722, 0, 0.129277572, 0)
	EXPLOIT9.Size = UDim2.new(0, 92, 0, 32)
	EXPLOIT9.Font = Enum.Font.Cartoon
	EXPLOIT9.Text = "Counter Pepsi"
	EXPLOIT9.TextColor3 = Color3.fromRGB(255, 255, 255)
	EXPLOIT9.TextScaled = true
	EXPLOIT9.TextSize = 14.000
	EXPLOIT9.TextWrapped = true
	EXPLOIT9.MouseButton1Down:connect(function()
		loadstring(game:HttpGet(('https://pastebin.com/raw/cWTJj3aZ'),true))()
	end)

	EXPLOIT6.Name = "EXPLOIT6"
	EXPLOIT6.Parent = MainFrame
	EXPLOIT6.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
	EXPLOIT6.BorderSizePixel = 0
	EXPLOIT6.Position = UDim2.new(0.388349503, 0, 0.323193908, 0)
	EXPLOIT6.Size = UDim2.new(0, 92, 0, 32)
	EXPLOIT6.Font = Enum.Font.Cartoon
	EXPLOIT6.Text = "PsyHub"
	EXPLOIT6.TextColor3 = Color3.fromRGB(255, 255, 255)
	EXPLOIT6.TextScaled = true
	EXPLOIT6.TextSize = 14.000
	EXPLOIT6.TextWrapped = true
	EXPLOIT6.MouseButton1Down:connect(function()
		loadstring(game:GetObjects("rbxassetid://3014051754")[1].Source)()
	end)

	EXPLOIT7.Name = "EXPLOIT7"
	EXPLOIT7.Parent = MainFrame
	EXPLOIT7.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
	EXPLOIT7.BorderSizePixel = 0
	EXPLOIT7.Position = UDim2.new(0.388349503, 0, 0.520912528, 0)
	EXPLOIT7.Size = UDim2.new(0, 92, 0, 32)
	EXPLOIT7.Font = Enum.Font.Cartoon
	EXPLOIT7.Text = "IY FE"
	EXPLOIT7.TextColor3 = Color3.fromRGB(255, 255, 255)
	EXPLOIT7.TextScaled = true
	EXPLOIT7.TextSize = 14.000
	EXPLOIT7.TextWrapped = true
	EXPLOIT7.MouseButton1Down:connect(function()
		loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
	end)

	EXPLOIT8.Name = "EXPLOIT8"
	EXPLOIT8.Parent = MainFrame
	EXPLOIT8.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
	EXPLOIT8.BorderSizePixel = 0
	EXPLOIT8.Position = UDim2.new(0.388349503, 0, 0.711026609, 0)
	EXPLOIT8.Size = UDim2.new(0, 92, 0, 32)
	EXPLOIT8.Font = Enum.Font.Cartoon
	EXPLOIT8.Text = "Arsenal Kill All"
	EXPLOIT8.TextColor3 = Color3.fromRGB(255, 255, 255)
	EXPLOIT8.TextScaled = true
	EXPLOIT8.TextSize = 14.000
	EXPLOIT8.TextWrapped = true
	EXPLOIT8.MouseButton1Down:connect(function()
		print("Script made by FramzDev#8283")
		local c = workspace.CurrentCamera
		local lplr = game.Players.LocalPlayer

		function a(p)
			if p and p.Character then
				pcall(function()
					local t = p.Character.PrimaryPart.CFrame * Vector3.new(0, -0.25, 0)
					c.CFrame = CFrame.new(c.Focus.p, t) * CFrame.new(0, 0, 0.5)
				end)
			end
		end
		for i=1,10 do
			for _,v in pairs(game.Players:GetPlayers()) do
				pcall(function()
					for i=1,15 do
						lplr.Character.HumanoidRootPart.CFrame = v.Character.HumanoidRootPart.CFrame - v.Character.HumanoidRootPart.CFrame.LookVector*4
						a(v)
						wait()
					end
				end)
			end
		end
	end)

	EXPLOIT10.Name = "EXPLOIT10"
	EXPLOIT10.Parent = MainFrame
	EXPLOIT10.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
	EXPLOIT10.BorderSizePixel = 0
	EXPLOIT10.Position = UDim2.new(0.75242722, 0, 0.323193908, 0)
	EXPLOIT10.Size = UDim2.new(0, 92, 0, 32)
	EXPLOIT10.Font = Enum.Font.Cartoon
	EXPLOIT10.Text = "Reviz Admin"
	EXPLOIT10.TextColor3 = Color3.fromRGB(255, 255, 255)
	EXPLOIT10.TextScaled = true
	EXPLOIT10.TextSize = 14.000
	EXPLOIT10.TextWrapped = true
	EXPLOIT10.MouseButton1Down:connect(function()
		loadstring(game:HttpGet(('https://pastebin.com/raw/KNUzQPYS'),true))()
	end)

	EXPLOIT11.Name = "EXPLOIT11"
	EXPLOIT11.Parent = MainFrame
	EXPLOIT11.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
	EXPLOIT11.BorderSizePixel = 0
	EXPLOIT11.Position = UDim2.new(0.75242722, 0, 0.520912528, 0)
	EXPLOIT11.Size = UDim2.new(0, 92, 0, 32)
	EXPLOIT11.Font = Enum.Font.Cartoon
	EXPLOIT11.Text = "FE GUI"
	EXPLOIT11.TextColor3 = Color3.fromRGB(255, 255, 255)
	EXPLOIT11.TextScaled = true
	EXPLOIT11.TextSize = 14.000
	EXPLOIT11.TextWrapped = true
	EXPLOIT11.MouseButton1Down:connect(function()
		loadstring(game:HttpGet(('https://pastebin.com/raw/yQaWHmZA'),true))()
	end)

	EXPLOIT12.Name = "EXPLOIT12"
	EXPLOIT12.Parent = MainFrame
	EXPLOIT12.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
	EXPLOIT12.BorderSizePixel = 0
	EXPLOIT12.Position = UDim2.new(0.75242722, 0, 0.711026609, 0)
	EXPLOIT12.Size = UDim2.new(0, 92, 0, 32)
	EXPLOIT12.Font = Enum.Font.Cartoon
	EXPLOIT12.Text = "FE Troll Animations"
	EXPLOIT12.TextColor3 = Color3.fromRGB(255, 255, 255)
	EXPLOIT12.TextScaled = true
	EXPLOIT12.TextSize = 14.000
	EXPLOIT12.TextWrapped = true
	EXPLOIT12.MouseButton1Down:connect(function()
		loadstring(game:HttpGet(('https://pastebin.com/raw/35ze0RJb'),true))()
	end)

	EXPLOIT2.Name = "EXPLOIT2"
	EXPLOIT2.Parent = MainFrame
	EXPLOIT2.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
	EXPLOIT2.BorderSizePixel = 0
	EXPLOIT2.Position = UDim2.new(0.024271844, 0, 0.323193908, 0)
	EXPLOIT2.Size = UDim2.new(0, 92, 0, 32)
	EXPLOIT2.Font = Enum.Font.Cartoon
	EXPLOIT2.Text = "Fe Invis Kill"
	EXPLOIT2.TextColor3 = Color3.fromRGB(255, 255, 255)
	EXPLOIT2.TextScaled = true
	EXPLOIT2.TextSize = 14.000
	EXPLOIT2.TextWrapped = true
	EXPLOIT2.MouseButton1Down:connect(function()
		loadstring(game:HttpGet(('https://pastebin.com/raw/Lpn5rUDp'),true))()
	end)

	EXPLOIT3.Name = "EXPLOIT3"
	EXPLOIT3.Parent = MainFrame
	EXPLOIT3.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
	EXPLOIT3.BorderSizePixel = 0
	EXPLOIT3.Position = UDim2.new(0.024271844, 0, 0.520912528, 0)
	EXPLOIT3.Size = UDim2.new(0, 92, 0, 32)
	EXPLOIT3.Font = Enum.Font.Cartoon
	EXPLOIT3.Text = "Vybe CMD Bar"
	EXPLOIT3.TextColor3 = Color3.fromRGB(255, 255, 255)
	EXPLOIT3.TextScaled = true
	EXPLOIT3.TextSize = 14.000
	EXPLOIT3.TextWrapped = true
	EXPLOIT3.MouseButton1Down:connect(function()
		loadstring(game:HttpGet(('https://pastebin.com/raw/NN5P4nQE'),true))()
	end)

	EXPLOIT4.Name = "EXPLOIT4"
	EXPLOIT4.Parent = MainFrame
	EXPLOIT4.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
	EXPLOIT4.BorderSizePixel = 0
	EXPLOIT4.Position = UDim2.new(0.024271844, 0, 0.711026609, 0)
	EXPLOIT4.Size = UDim2.new(0, 92, 0, 32)
	EXPLOIT4.Font = Enum.Font.Cartoon
	EXPLOIT4.Text = "JB Autorob"
	EXPLOIT4.TextColor3 = Color3.fromRGB(255, 255, 255)
	EXPLOIT4.TextScaled = true
	EXPLOIT4.TextSize = 14.000
	EXPLOIT4.TextWrapped = true
	EXPLOIT4.MouseButton1Down:connect(function()
		loadstring(game:GetObjects("rbxassetid://1461971147")[1].Source)()
	end)

	MainFrameBeautyB.Name = "MainFrameBeautyB"
	MainFrameBeautyB.Parent = MainFrame
	MainFrameBeautyB.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
	MainFrameBeautyB.BorderSizePixel = 0
	MainFrameBeautyB.Position = UDim2.new(0, 0, 0.916349828, 0)
	MainFrameBeautyB.Size = UDim2.new(0, 412, 0, 22)
	MainFrameBeautyB.Visible = false
end)

DarkDex.Name = "DarkDex"
DarkDex.Parent = Main
DarkDex.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
DarkDex.BorderSizePixel = 0
DarkDex.Position = UDim2.new(0.0142857153, 0, 0.436893344, 0)
DarkDex.Size = UDim2.new(0.192857146, 0, 0.123256512, 0)
DarkDex.Font = Enum.Font.SourceSans
DarkDex.Text = "DarkDex"
DarkDex.TextColor3 = Color3.fromRGB(220, 220, 220)
DarkDex.TextScaled = true
DarkDex.TextSize = 14.000
DarkDex.TextWrapped = true
DarkDex.MouseButton1Down:connect(function()
	loadstring(game:GetObjects("rbxassetid://418957341")[1].Source)()
end)

NameFrame5.Name = "NameFrame5"
NameFrame5.Parent = Main
NameFrame5.BackgroundColor3 = Color3.fromRGB(177, 177, 177)
NameFrame5.BorderColor3 = Color3.fromRGB(255, 255, 255)
NameFrame5.BorderSizePixel = 0
NameFrame5.Position = UDim2.new(0, 0, 0.844631433, 0)
NameFrame5.Size = UDim2.new(0.224999994, 0, 0.155116141, 0)

ImageLabel.Parent = NameFrame5
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.Size = UDim2.new(0.404762387, 0, 0.997716427, 0)
ImageLabel.Image = "http://www.roblox.com/asset/?id=9309242202"

Credit.Name = "Credit"
Credit.Parent = Main
Credit.BackgroundColor3 = Color3.fromRGB(177, 177, 177)
Credit.BorderSizePixel = 0
Credit.Position = UDim2.new(0.0910715386, 0, 0.844631433, 0)
Credit.Size = UDim2.new(0.132142752, 0, 0.15476194, 0)
Credit.Font = Enum.Font.TitilliumWeb
Credit.Text = "SG#6284"
Credit.TextColor3 = Color3.fromRGB(54, 54, 54)
Credit.TextScaled = true
Credit.TextSize = 14.000
Credit.TextWrapped = true

RocatHubText.Name = "RocatHubText"
RocatHubText.Parent = Main
RocatHubText.BackgroundColor3 = Color3.fromRGB(65, 65, 65)
RocatHubText.BorderSizePixel = 0
RocatHubText.Position = UDim2.new(0.0125197275, 0, -0.000606673188, 0)
RocatHubText.Size = UDim2.new(0.373214275, 0, 0.122023821, 0)
RocatHubText.Font = Enum.Font.SourceSans
RocatHubText.Text = "Rocat's Exploit"
RocatHubText.TextColor3 = Color3.fromRGB(255, 255, 255)
RocatHubText.TextScaled = true
RocatHubText.TextSize = 14.000
RocatHubText.TextWrapped = true
