local RS
local LeftLeg
local RightLeg
local LeftFoot
local RightFoot
local Distance = 0
local DistanceTackle = 0
local DistanceReach = 0
local DistancePass = 0
local DistanceWalk = 0
local DistanceSide = 0
local DistanceJump = 0
local SaveDelay = 0
local Heartbeat
local HumanoidDied
local TouchedBallLoop
local RunStepped2
local RunStepBall
local AddBallA
local TouchedGKBallBox

local Player = game.Players.LocalPlayer
local RootPart = Player.Character.HumanoidRootPart


local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "werzaazizhubv1", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

--Tabs
 
local aTab = Window:MakeTab({
	Name = "Main",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Tab = Window:MakeTab({
	Name = "GUI(s)",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

-- Paragraphs

aTab:AddParagraph("How to Enable AntiCheat?","Press the AntiCheat Button. 1 time")

--Buttons

aTab:AddButton({
	Name = "AntiCheat",
	Callback = function()
      		loadstring(game:HttpGet("https://freenote.biz/raw/vyzuuBLBkX"))()
  	end    
})

aTab:AddButton({
	Name = "Purple Sky",
	Callback = function()
      		local skybox = Instance.new("Sky")
skybox.Parent = game.Lighting
skybox.SkyboxBk = "http://www.roblox.com/asset/?id=159454299"
skybox.SkyboxDn = "http://www.roblox.com/asset/?id=159454296"
skybox.SkyboxFt = "http://www.roblox.com/asset/?id=159454293"
skybox.SkyboxLf = "http://www.roblox.com/asset/?id=159454286"
skybox.SkyboxRt = "http://www.roblox.com/asset/?id=159454300"
skybox.SkyboxUp = "http://www.roblox.com/asset/?id=159454288"
skybox.StarCount = 5000
  	end    
})

aTab:AddButton({
	Name = "Night Sky",
	Callback = function()
	    getgenv().farmer = true
	    while wait() do
	    if getgenv().farmer == true then
	    game.Lighting.TimeOfDay = "00:00:00"
	    end
	    end
    end
})

-- buttons 2

Tab:AddButton({
	Name = "Reach GUI!",
	Callback = function()
      		OrionLib:MakeNotification({
	Name = "Loading...",
	Content = "Please wait loading may take some seconds...",
	Image = "rbxassetid://4483345998",
	Time = 3
})

loadstring(game:HttpGet("https://raw.githubusercontent.com/cnd00idjehdil1dhw8w9wowjeie9r00ro9djfjx/xiodidhd9dodjdifijdidodo/main/Rh"))()
  	end    
})

Tab:AddButton({
	Name = "React GUI!",
	Callback = function()
      		OrionLib:MakeNotification({
	Name = "Loading...",
	Content = "Please wait loading may take some seconds...",
	Image = "rbxassetid://4483345998",
	Time = 3
})

loadstring(game:HttpGet("https://raw.githubusercontent.com/cnd00idjehdil1dhw8w9wowjeie9r00ro9djfjx/xiodidhd9dodjdifijdidodo/main/Rt"))()
  	end    
})

Tab:AddButton({
	Name = "Cracks GUI!(OP)",
	Callback = function()
      		OrionLib:MakeNotification({
	Name = "Loading...",
	Content = "Please wait loading may take some seconds...",
	Image = "rbxassetid://4483345998",
	Time = 3
})

loadstring(game:HttpGet("https://raw.githubusercontent.com/cnd00idjehdil1dhw8w9wowjeie9r00ro9djfjx/xiodidhd9dodjdifijdidodo/main/cracc"))()
  	end    
})

Tab:AddButton({
	Name = "Striker GUI!",
	Callback = function()
      		OrionLib:MakeNotification({
	Name = "Loading...",
	Content = "Please wait loading may take some seconds...",
	Image = "rbxassetid://4483345998",
	Time = 3
})

loadstring(game:HttpGet("https://raw.githubusercontent.com/cnd00idjehdil1dhw8w9wowjeie9r00ro9djfjx/xiodidhd9dodjdifijdidodo/main/st"))()
  	end    
})

Tab:AddButton({
	Name = "GoalKeeper GUI!",
	Callback = function()
      		OrionLib:MakeNotification({
	Name = "Loading...",
	Content = "Please wait loading may take some seconds...",
	Image = "rbxassetid://4483345998",
	Time = 3
})

loadstring(game:HttpGet("https://raw.githubusercontent.com/cnd00idjehdil1dhw8w9wowjeie9r00ro9djfjx/xiodidhd9dodjdifijdidodo/main/gkkmmm"))()
  	end    
})

Tab:AddButton({
	Name = "Ball Mods GUI!",
	Callback = function()
      		OrionLib:MakeNotification({
	Name = "Loading...",
	Content = "Please wait loading may take some seconds...",
	Image = "rbxassetid://4483345998",
	Time = 3
})

loadstring(game:HttpGet("https://raw.githubusercontent.com/cnd00idjehdil1dhw8w9wowjeie9r00ro9djfjx/xiodidhd9dodjdifijdidodo/main/BAII"))()
  	end    
})

Tab:AddButton({
	Name = "Super Kicks GUI!",
	Callback = function()
      		OrionLib:MakeNotification({
	Name = "Loading...",
	Content = "Please wait loading may take some seconds...",
	Image = "rbxassetid://4483345998",
	Time = 3
})

loadstring(game:HttpGet("https://raw.githubusercontent.com/cnd00idjehdil1dhw8w9wowjeie9r00ro9djfjx/xiodidhd9dodjdifijdidodo/main/sk"))()
  	end    
})

Tab:AddButton({
	Name = "Ping And Level Changer GUI!",
	Callback = function()
      		OrionLib:MakeNotification({
	Name = "Loading...",
	Content = "Please wait loading may take some seconds...",
	Image = "rbxassetid://4483345998",
	Time = 3
})

loadstring(game:HttpGet("https://pastebin.com/raw/M4naWpyt"))()
  	end    
})

Tab:AddButton({
	Name = "LocalPlayer GUI!",
	Callback = function()
      		OrionLib:MakeNotification({
	Name = "Loading...",
	Content = "Please wait loading may take some seconds...",
	Image = "rbxassetid://4483345998",
	Time = 3
})

loadstring(game:HttpGet("https://raw.githubusercontent.com/cnd00idjehdil1dhw8w9wowjeie9r00ro9djfjx/xiodidhd9dodjdifijdidodo/main/local"))()
  	end    
})

Tab:AddButton({
	Name = "Miscellaneous GUI!",
	Callback = function()
      		OrionLib:MakeNotification({
	Name = "Loading...",
	Content = "Please wait loading may take some seconds...",
	Image = "rbxassetid://4483345998",
	Time = 3
})

loadstring(game:HttpGet("https://raw.githubusercontent.com/cnd00idjehdil1dhw8w9wowjeie9r00ro9djfjx/xiodidhd9dodjdifijdidodo/main/mis"))()
  	end    
})

Tab:AddButton({
	Name = "Kill GUI!",
	Callback = function()
      		OrionLib:MakeNotification({
	Name = "Loading...",
	Content = "Please wait loading may take some seconds...",
	Image = "rbxassetid://4483345998",
	Time = 3
})

loadstring(game:HttpGet("https://raw.githubusercontent.com/cnd00idjehdil1dhw8w9wowjeie9r00ro9djfjx/xiodidhd9dodjdifijdidodo/main/murder"))()
  	end    
})

Tab:AddButton({
	Name = "Powers GUI!",
	Callback = function()
      		OrionLib:MakeNotification({
	Name = "Loading...",
	Content = "Please wait loading may take some seconds...",
	Image = "rbxassetid://4483345998",
	Time = 3
})

loadstring(game:HttpGet("https://raw.githubusercontent.com/cnd00idjehdil1dhw8w9wowjeie9r00ro9djfjx/xiodidhd9dodjdifijdidodo/main/pw"))()
  	end    
})
