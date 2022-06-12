-- Epik Game Hub By Prototype RBLX

game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("Proto's Hub Loaded" ,"All")

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local Page2 = Instance.new("Frame")
local Arsenal = Instance.new("TextButton")
local MM2 = Instance.new("TextButton")
local BlloxFruits = Instance.new("TextButton")
local AnimeFight = Instance.new("TextButton")
local Toh = Instance.new("TextButton")
local PetSimX = Instance.new("TextButton")
local NavalWarfare = Instance.new("TextButton")
local Doomspire = Instance.new("TextButton")
local WeaponFighting = Instance.new("TextButton")
local SonicSpeed = Instance.new("TextButton")
local BedWars = Instance.new("TextButton")
local Clickersim = Instance.new("TextButton")
local TextLabel_2 = Instance.new("TextLabel")
local Page1Button = Instance.new("TextButton")
local Page2Button = Instance.new("TextButton")
local Close = Instance.new("TextButton")
local Page1 = Instance.new("Frame")
local PizzaPlace = Instance.new("TextButton")
local BeeSwarm = Instance.new("TextButton")
local Jailbreak = Instance.new("TextButton")
local FleeTheFacility = Instance.new("TextButton")
local BuildABoat = Instance.new("TextButton")
local Giant = Instance.new("TextButton")
local Lt2 = Instance.new("TextButton")
local Paintball = Instance.new("TextButton")
local TextLabel_3 = Instance.new("TextLabel")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ResetOnSpawn = false

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 127)
Frame.Position = UDim2.new(0.260797232, 0, 0.30265075, 0)
Frame.Size = UDim2.new(0, 400, 0, 242)
Frame.Active = true
Frame.Draggable = true

Page2.Name = "Page2"
Page2.Parent = Frame
Page2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Page2.BorderColor3 = Color3.fromRGB(255, 0, 0)
Page2.Position = UDim2.new(0.024278868, 0, 0.125496477, 0)
Page2.Size = UDim2.new(0, 378, 0, 211)

Arsenal.Name = "Arsenal"
Arsenal.Parent = Frame
Arsenal.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Arsenal.Position = UDim2.new(0.0551948026, 0, 0.161818027, 0)
Arsenal.Size = UDim2.new(0, 79, 0, 35)
Arsenal.Font = Enum.Font.SourceSans
Arsenal.Text = "Arsenal"
Arsenal.TextColor3 = Color3.fromRGB(0, 0, 0)
Arsenal.TextSize = 14.000
Arsenal.MouseButton1Down:connect(function()
	function getplrsname() for i,v in pairs(game:GetChildren()) do if v.ClassName == "Players" then return v.Name end end end local players = getplrsname() local plr = game[players].LocalPlayer coroutine.resume(coroutine.create(function() while wait(1) do coroutine.resume(coroutine.create(function() for _,v in pairs(game[players]:GetPlayers()) do if v.Name ~= plr.Name and v.Character then v.Character.RightUpperLeg.CanCollide = false v.Character.RightUpperLeg.Transparency = 75 v.Character.RightUpperLeg.Size = Vector3.new(21,21,21) v.Character.LeftUpperLeg.CanCollide = false v.Character.LeftUpperLeg.Transparency = 75 v.Character.LeftUpperLeg.Size = Vector3.new(21,21,21) v.Character.HeadHB.CanCollide = false v.Character.HeadHB.Transparency = 75 v.Character.HeadHB.Size = Vector3.new(21,21,21) v.Character.HumanoidRootPart.CanCollide = false v.Character.HumanoidRootPart.Transparency = 75 v.Character.HumanoidRootPart.Size = Vector3.new(21,21,21) end end end)) end end))
end)

MM2.Name = "MM2"
MM2.Parent = Frame
MM2.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
MM2.Position = UDim2.new(0.0551947989, 0, 0.376420975, 0)
MM2.Size = UDim2.new(0, 79, 0, 35)
MM2.Font = Enum.Font.SourceSans
MM2.Text = "Mm2 (PC)"
MM2.TextColor3 = Color3.fromRGB(0, 0, 0)
MM2.TextSize = 14.000
MM2.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(("https://pastebin.com/raw/MTYiYkZQ"), true))()
end)

BlloxFruits.Name = "Bllox Fruits"
BlloxFruits.Parent = Frame
BlloxFruits.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
BlloxFruits.Position = UDim2.new(0.0551948026, 0, 0.597644985, 0)
BlloxFruits.Size = UDim2.new(0, 79, 0, 35)
BlloxFruits.Font = Enum.Font.SourceSans
BlloxFruits.Text = "Blox Fruits"
BlloxFruits.TextColor3 = Color3.fromRGB(0, 0, 0)
BlloxFruits.TextSize = 14.000
BlloxFruits.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/ArceusXHub/AV2022/main/README.md", true))()
end)

AnimeFight.Name = "AnimeFight"
AnimeFight.Parent = Frame
AnimeFight.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
AnimeFight.Position = UDim2.new(0.685064971, 0, 0.156867564, 0)
AnimeFight.Size = UDim2.new(0, 79, 0, 35)
AnimeFight.Font = Enum.Font.SourceSans
AnimeFight.Text = "Anime Fighters"
AnimeFight.TextColor3 = Color3.fromRGB(0, 0, 0)
AnimeFight.TextSize = 14.000
AnimeFight.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/DookDekDEE/AFS/main/script.lua"))()
end)

Toh.Name = "Tower Of Hell"
Toh.Parent = Frame
Toh.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Toh.Position = UDim2.new(0.685064971, 0, 0.37230581, 0)
Toh.Size = UDim2.new(0, 79, 0, 35)
Toh.Font = Enum.Font.SourceSans
Toh.Text = "Tower Of Hell"
Toh.TextColor3 = Color3.fromRGB(0, 0, 0)
Toh.TextSize = 14.000
Toh.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/TwomadJR/nto/main/admiin"))()
end)

PetSimX.Name = "Pet Sim X"
PetSimX.Parent = Frame
PetSimX.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
PetSimX.Position = UDim2.new(0.685064971, 0, 0.593529761, 0)
PetSimX.Size = UDim2.new(0, 79, 0, 35)
PetSimX.Font = Enum.Font.SourceSans
PetSimX.Text = "Pet Simulator X"
PetSimX.TextColor3 = Color3.fromRGB(0, 0, 0)
PetSimX.TextSize = 14.000
PetSimX.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Wind596/VoidHub/main/WiningDediy", true))()
end)

NavalWarfare.Name = "Naval Warfare"
NavalWarfare.Parent = Frame
NavalWarfare.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
NavalWarfare.Position = UDim2.new(0.348902613, 0, 0.159440309, 0)
NavalWarfare.Size = UDim2.new(0, 92, 0, 35)
NavalWarfare.Font = Enum.Font.SourceSans
NavalWarfare.Text = "Naval Warafare"
NavalWarfare.TextColor3 = Color3.fromRGB(0, 0, 0)
NavalWarfare.TextSize = 14.000
NavalWarfare.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://pastebin.com/raw/vCkw6SF7'))()
end)

Doomspire.Name = "Doomspire"
Doomspire.Parent = Frame
Doomspire.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Doomspire.Position = UDim2.new(0.348902613, 0, 0.374018908, 0)
Doomspire.Size = UDim2.new(0, 92, 0, 35)
Doomspire.Font = Enum.Font.SourceSans
Doomspire.Text = "Doomspire"
Doomspire.TextColor3 = Color3.fromRGB(0, 0, 0)
Doomspire.TextSize = 14.000
Doomspire.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/WyqZ5CXE"))()
end)

WeaponFighting.Name = "WeaponFighting"
WeaponFighting.Parent = Frame
WeaponFighting.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
WeaponFighting.Position = UDim2.new(0.3437168, 0, 0.595499694, 0)
WeaponFighting.Size = UDim2.new(0, 93, 0, 35)
WeaponFighting.Font = Enum.Font.SourceSans
WeaponFighting.Text = "Weapon Fighting"
WeaponFighting.TextColor3 = Color3.fromRGB(0, 0, 0)
WeaponFighting.TextSize = 14.000
WeaponFighting.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://rawscripts.net/raw/loader_1038"))()
end)

SonicSpeed.Name = "SonicSpeed"
SonicSpeed.Parent = Frame
SonicSpeed.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
SonicSpeed.Position = UDim2.new(0.0584415793, 0, 0.81575197, 0)
SonicSpeed.Size = UDim2.new(0, 79, 0, 35)
SonicSpeed.Font = Enum.Font.SourceSans
SonicSpeed.Text = "Sonic Speed"
SonicSpeed.TextColor3 = Color3.fromRGB(0, 0, 0)
SonicSpeed.TextSize = 14.000
SonicSpeed.MouseButton1Down:connect(function()
	getgenv().Time_Between_Each_ServerHop = 999999999999999999 -- This Is The Time You Will Rejoin
loadstring(game:HttpGet"https://gitlab.com/L1ZOT/test-project/-/raw/main/Sonic-Speed-Simulator-AutoEXC")()
end)

BedWars.Name = "Bed Wars"
BedWars.Parent = Frame
BedWars.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
BedWars.Position = UDim2.new(0.678571463, 0, 0.81575197, 0)
BedWars.Size = UDim2.new(0, 79, 0, 35)
BedWars.Font = Enum.Font.SourceSans
BedWars.Text = "Bed Wars"
BedWars.TextColor3 = Color3.fromRGB(0, 0, 0)
BedWars.TextSize = 14.000
BedWars.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/dorukqpx/Xrayon/main/xrayonv2.lua", true))()
end)

Clickersim.Name = "Clickersim"
Clickersim.Parent = Frame
Clickersim.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Clickersim.Position = UDim2.new(0.3437168, 0, 0.813606679, 0)
Clickersim.Size = UDim2.new(0, 93, 0, 35)
Clickersim.Font = Enum.Font.SourceSans
Clickersim.Text = "Clicker Simulator"
Clickersim.TextColor3 = Color3.fromRGB(0, 0, 0)
Clickersim.TextSize = 14.000
Clickersim.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Kederal/script.gg/main/loader.lua"))()
end)


TextLabel_2.Parent = Frame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Position = UDim2.new(-0.0993756652, 0, 0.00269398093, 0)
TextLabel_2.Size = UDim2.new(0, 255, 0, 32)
TextLabel_2.Font = Enum.Font.Oswald
TextLabel_2.Text = "Proto's Hub"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 0, 0)
TextLabel_2.TextSize = 43.000

Page1Button.Name = "Page1 Button"
Page1Button.Parent = Frame
Page1Button.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Page1Button.Position = UDim2.new(0.463304609, 0, 0.0203290582, 0)
Page1Button.Size = UDim2.new(0, 62, 0, 23)
Page1Button.Font = Enum.Font.Roboto
Page1Button.Text = "Page 1"
Page1Button.TextColor3 = Color3.fromRGB(0, 0, 0)
Page1Button.TextSize = 14.000

Page2Button.Name = "Page2 Button"
Page2Button.Parent = Frame
Page2Button.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Page2Button.Position = UDim2.new(0.61830461, 0, 0.0203290582, 0)
Page2Button.Size = UDim2.new(0, 62, 0, 23)
Page2Button.Font = Enum.Font.Roboto
Page2Button.Text = "Page 2"
Page2Button.TextColor3 = Color3.fromRGB(0, 0, 0)
Page2Button.TextSize = 14.000

Close.Name = "Close"
Close.Parent = Frame
Close.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Close.Position = UDim2.new(0.805192232, 0, -0.00147169828, 0)
Close.Size = UDim2.new(0, 78, 0, 22)
Close.Font = Enum.Font.Roboto
Close.Text = "Destroy GUI"
Close.TextColor3 = Color3.fromRGB(0, 0, 0)
Close.TextSize = 14.000

Page1.Name = "Page1"
Page1.Parent = Frame
Page1.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Page1.BorderColor3 = Color3.fromRGB(255, 0, 0)
Page1.Position = UDim2.new(0.0260723829, 0, 0.127044082, 0)
Page1.Size = UDim2.new(0, 378, 0, 210)

PizzaPlace.Name = "Pizza Place"
PizzaPlace.Parent = Page1
PizzaPlace.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
PizzaPlace.BorderColor3 = Color3.fromRGB(0, 0, 0)
PizzaPlace.Position = UDim2.new(0.0289501157, 0, 0.180240095, 0)
PizzaPlace.Size = UDim2.new(0, 98, 0, 40)
PizzaPlace.Font = Enum.Font.SourceSans
PizzaPlace.Text = "OP Hotel Elephant"
PizzaPlace.TextColor3 = Color3.fromRGB(0, 0, 0)
PizzaPlace.TextSize = 14.000
PizzaPlace.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/Teemsploit/Epic-roblox-hack/main/HotelElephantFuckerV2'))()
end)

BeeSwarm.Name = "Bee Swarm"
BeeSwarm.Parent = Page1
BeeSwarm.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
BeeSwarm.BorderColor3 = Color3.fromRGB(0, 0, 0)
BeeSwarm.Position = UDim2.new(0.700907826, 0, 0.180240095, 0)
BeeSwarm.Size = UDim2.new(0, 98, 0, 40)
BeeSwarm.Font = Enum.Font.SourceSans
BeeSwarm.Text = "Bee Swarm"
BeeSwarm.TextColor3 = Color3.fromRGB(0, 0, 0)
BeeSwarm.TextSize = 14.000
BeeSwarm.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Historia00012/HISTORIAHUB/main/BSS%20FREE"))()
end)

Jailbreak.Name = "Jailbreak"
Jailbreak.Parent = Page1
Jailbreak.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Jailbreak.BorderColor3 = Color3.fromRGB(0, 0, 0)
Jailbreak.Position = UDim2.new(0.362283438, 0, 0.180240095, 0)
Jailbreak.Size = UDim2.new(0, 98, 0, 40)
Jailbreak.Font = Enum.Font.SourceSans
Jailbreak.Text = "Jailbreak"
Jailbreak.TextColor3 = Color3.fromRGB(0, 0, 0)
Jailbreak.TextSize = 14.000
Jailbreak.MouseButton1Down:connect(function()
	loadstring(game:GetObjects("rbxassetid://3762448307")[1].Source)()
end)

FleeTheFacility.Name = "FleeTheFacility"
FleeTheFacility.Parent = Page1
FleeTheFacility.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
FleeTheFacility.BorderColor3 = Color3.fromRGB(0, 0, 0)
FleeTheFacility.Position = UDim2.new(0.362283438, 0, 0.470716268, 0)
FleeTheFacility.Size = UDim2.new(0, 98, 0, 40)
FleeTheFacility.Font = Enum.Font.SourceSans
FleeTheFacility.Text = "Flee The Facility"
FleeTheFacility.TextColor3 = Color3.fromRGB(0, 0, 0)
FleeTheFacility.TextSize = 14.000
FleeTheFacility.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Drifty96/ftfgui/main/ftfgui", true))()
end)

BuildABoat.Name = "BuildABoat"
BuildABoat.Parent = Page1
BuildABoat.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
BuildABoat.BorderColor3 = Color3.fromRGB(0, 0, 0)
BuildABoat.Position = UDim2.new(0.0263046026, 0, 0.475478172, 0)
BuildABoat.Size = UDim2.new(0, 98, 0, 40)
BuildABoat.Font = Enum.Font.SourceSans
BuildABoat.Text = "OP Buld A Boat"
BuildABoat.TextColor3 = Color3.fromRGB(0, 0, 0)
BuildABoat.TextSize = 14.000
BuildABoat.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/StenDirt/Trash-Game/main/Script.lua"))()
end)

Giant.Name = "Giant"
Giant.Parent = Page1
Giant.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Giant.BorderColor3 = Color3.fromRGB(0, 0, 0)
Giant.Position = UDim2.new(0.698262274, 0, 0.465954363, 0)
Giant.Size = UDim2.new(0, 98, 0, 40)
Giant.Font = Enum.Font.SourceSans
Giant.Text = "Giant Survival"
Giant.TextColor3 = Color3.fromRGB(0, 0, 0)
Giant.TextSize = 14.000
Giant.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/radjahfromdiscord/giantsurvival/master/gui"))()
end)

Lt2.Name = "Lt2"
Lt2.Parent = Page1
Lt2.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Lt2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Lt2.Position = UDim2.new(0.200907782, 0, 0.756430566, 0)
Lt2.Size = UDim2.new(0, 98, 0, 40)
Lt2.Font = Enum.Font.SourceSans
Lt2.Text = "Lumber Tycoon"
Lt2.TextColor3 = Color3.fromRGB(0, 0, 0)
Lt2.TextSize = 14.000
Lt2.MouseButton1Down:connect(function()
	loadstring(game:HttpGet"https://pastebin.com/raw/25abQ0nC")()
end)

Paintball.Name = "Paintball"
Paintball.Parent = Page1
Paintball.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Paintball.BorderColor3 = Color3.fromRGB(0, 0, 0)
Paintball.Position = UDim2.new(0.539532125, 0, 0.751668632, 0)
Paintball.Size = UDim2.new(0, 98, 0, 40)
Paintball.Font = Enum.Font.SourceSans
Paintball.Text = "Big Paintball"
Paintball.TextColor3 = Color3.fromRGB(0, 0, 0)
Paintball.TextSize = 14.000
Paintball.MouseButton1Down:connect(function()
	getgenv().Enabled = true
loadstring(game:HttpGet("https://raw.githubusercontent.com/WetCheezit/Releases/main/Big-Paintball/KillAll.lua"))()
end)

TextLabel_3.Parent = Page1
TextLabel_3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextLabel_3.Position = UDim2.new(0.262548625, 0, 0.016621327, 0)
TextLabel_3.Size = UDim2.new(0, 176, 0, 30)
TextLabel_3.Font = Enum.Font.Sarpanch
TextLabel_3.Text = "Scripts"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 0, 0)
TextLabel_3.TextSize = 14.000

-- Scripts:

local function JHEMTWJ_fake_script() -- TextLabel_2.Script 
	local script = Instance.new('Script', TextLabel_2)

	local text = script.Parent
	local add = 10
	wait(1)
	local k = 1
	while k <= 255 do
		text.TextColor3 = Color3.new(k/255,0/255,0/255)
		k = k + add
		wait()
	end
	while true do
		k = 1
		while k <= 255 do
			text.TextColor3 = Color3.new(255/255,k/255,0/255)
			k = k + add
			wait()
		end
		k = 1
		while k <= 255 do
			text.TextColor3 = Color3.new(255/255 - k/255,255/255,0/255)
			k = k + add
			wait()
		end
		k = 1
		while k <= 255 do
			text.TextColor3 = Color3.new(0/255,255/255,k/255)
			k = k + add
			wait()
		end
		k = 1
		while k <= 255 do
			text.TextColor3 = Color3.new(0/255,255/255 - k/255,255/255)
			k = k + add
			wait()
		end
		k = 1
		while k <= 255 do
			text.TextColor3 = Color3.new(k/255,0/255,255/255)
			k = k + add
			wait()
		end
		k = 1
		while k <= 255 do
			text.TextColor3 = Color3.new(255/255,0/255,255/255 - k/255)
			k = k + add
			wait()
		end
		while k <= 255 do
			text.TextColor3 = Color3.new(255/255 - k/255,0/255,0/255)
			k = k + add
			wait()
		end
	end
end
coroutine.wrap(JHEMTWJ_fake_script)()
local function DTCNADB_fake_script() -- Page1Button.LocalScript 
	local script = Instance.new('LocalScript', Page1Button)

	script.Parent.MouseButton1Down:connect(function()
		script.Parent.Parent.Page1.Visible = true
		script.Parent.Parent.Page2.Visible = false
	
	end)
	
end
coroutine.wrap(DTCNADB_fake_script)()
local function YIVLG_fake_script() -- Page2Button.LocalScript 
	local script = Instance.new('LocalScript', Page2Button)

	script.Parent.MouseButton1Down:connect(function()
		script.Parent.Parent.Page2.Visible = true
		script.Parent.Parent.Page1.Visible = false
	
	end)
end
coroutine.wrap(YIVLG_fake_script)()
local function DHVQ_fake_script() -- Close.LocalScript 
	local script = Instance.new('LocalScript', Close)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Visible = false
	end)
end
coroutine.wrap(DHVQ_fake_script)()
