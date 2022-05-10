--[[ 

THIS IS REALLY IMPORTANT IF YOU ARE GONNA USE SALVAGE ALL EXCEPT
If you type in e.g bat its gonna salvage everything because that item doesn't exist.

this is a list of items you can use

e.g putting in fists would salvage everything except ur hands

now heres the list of items

CAPITALS MATTER

fists
baseballBat
crowbar
yoyo
longsword
fireAxe
fryingPan
rapier
knife
cleaver
armingsword
greatsword
chainsaw
spear
shovel
metalBat
sledgehammer

There are more but im not sure what their name is since i never got to see their atcual name

--]]

spawn(function()
local msg = Instance.new("Message",workspace)
msg.Text = "Please Read the First 32 lines of the script tyty"
task.wait(6)
msg.Text = "Also No Miss Doesn't Work With All Weps (Doesn't Work With Any Of The Upgraded Weapons, Chainsaw, GreatSword, Fists, Rapier And Yoyo)"
task.wait(10)
msg:Destroy()
end)

local library = loadstring(game:HttpGet(('https://raw.githubusercontent.com/AikaV3rm/UiLib/master/Lib.lua')))()

function notif(text)
	game.StarterGui:SetCore("SendNotification", {
    Title = "This Script";
    Text = text;
    Icon = "rbxassetid://4452245157";
    Duration = 7;
    })
end

local w = library:CreateWindow("Madness combat game idfk haha poo") -- Creates the window

local b = w:CreateFolder("Main")
local v = w:CreateFolder("Parry Config")

b:Label("",{
    TextSize = 25; -- Self Explaining
    TextColor = Color3.fromRGB(255,255,255); -- Self Explaining
    BgColor = Color3.fromRGB(69,69,69); -- Self Explaining
    
})

b:Toggle("RageMode Auto-Parry",function(bool)
     spawn(function()
        if bool3 then
            _G.ragemodeautoparry = true
            notif("RageMode Auto-Parry On")
        else
            _G.ragemodeautoparry = false
            notif("RageMode Auto-Parry Off")
        end

while _G.ragemodeautoparry do task.wait()
pcall(function()
    for i,v in pairs(game:GetService("Workspace").characters:GetDescendants()) do 
        
        local weapon3 = nil
        
        if v.Name == "canAttack" and v.Value == false then
            
        local reqwepfromman = require(v.Parent.Parent.stat).S1
        
        if reqwepfromman.blockBreak == 4 then
            
        else
            
        if v.Parent.Parent.Parent:IsA("Model") and v.Parent.Parent.Parent.Humanoid then
            if v.Parent.Parent.Parent.Name == game.Players.LocalPlayer.Character.Name then
                
            else    
        
        
    local lp = game.Players.LocalPlayer
    local character = v.Parent.Parent.Parent
    local charactername = v.Parent.Parent.Parent.Name
    
        
        if (lp.Character and lp.Character:FindFirstChild("Head") and character:FindFirstChild("Head")) then
            local mag = (character.Head.Position - lp.Character.Head.Position).Magnitude
                  if mag < 13  then
                      
        if game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool") then
            weapon3 = game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool")
        end    
        
        if weapon3.values.canAttack.Value == true then
            
        local fucker = math.random(1,2)
        
        if fucker == 1 then
        
local ohString1 = "Block"
local ohBoolean2 = true

weapon3.Start:FireServer(ohString1, ohBoolean2)
for i,v in pairs(game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool"):GetDescendants()) do
    if v.Name == "B1" then
		local animation = Instance.new("Animation")
		animation.AnimationId = v.AnimationId
		animTrack = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(animation)
		animTrack:Play()
		task.wait(0.2)
		animTrack:Destroy()
		local animation2 = Instance.new("Animation")
		animation2.AnimationId = v.Parent.B2.AnimationId
		animTrack2 = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(animation2)
		animTrack2:Play()
		task.wait(0.5)
		animTrack2:Stop()
    end
end
task.wait(0.2)
    if weapon3:FindFirstChild("shovelHandle"):FindFirstChild("blockSpark") or weapon3:FindFirstChild("baseballBat"):FindFirstChild("blockSpark") or weapon3:FindFirstChild("longhandle"):FindFirstChild("blockSpark") or weapon3:FindFirstChild("snailshield"):FindFirstChild("blockSpark") or weapon3:FindFirstChild("katanaHandle"):FindFirstChild("blockSpark") then
        task.wait(1.6)
    else
        task.wait(0.5)
    end
else
    
task.wait(0.5)    


end    
end   
end
end
end
end
end
end
end
end)
end
end)
end)

b:Toggle("Kinda-Legit Auto-Parry",function(bool2)
     spawn(function()
        if bool3 then
            _G.kindalegitautoparry = true
            notif("Kinda-Legit Auto-Parry On")
        else
            _G.kindalegitautoparry = false
            notif("Kinda-Legit Auto-Parry Off")
        end

while _G.kindalegitautoparry do task.wait()
pcall(function()
    for i,v in pairs(game:GetService("Workspace").characters:GetDescendants()) do 
        
        local weapon3 = nil
        
        if v.Name == "canAttack" and v.Value == false then
            
        local reqwepfromman = require(v.Parent.Parent.stat).S1
        
        if reqwepfromman.blockBreak == 4 then
            
        else
            
        if v.Parent.Parent.Parent:IsA("Model") and v.Parent.Parent.Parent.Humanoid then
            if v.Parent.Parent.Parent.Name == game.Players.LocalPlayer.Character.Name then
                
            else    
        
        
    local lp = game.Players.LocalPlayer
    local character = v.Parent.Parent.Parent
    local charactername = v.Parent.Parent.Parent.Name
    
        
        if (lp.Character and lp.Character:FindFirstChild("Head") and character:FindFirstChild("Head")) then
            local mag = (character.Head.Position - lp.Character.Head.Position).Magnitude
                  if mag < 13  then
                      
        if game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool") then
            weapon3 = game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool")
        end    
        
        if weapon3.values.canAttack.Value == true then
        
local ohString1 = "Block"
local ohBoolean2 = true

weapon3.Start:FireServer(ohString1, ohBoolean2)
for i,v in pairs(game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool"):GetDescendants()) do
    if v.Name == "B1" then
		local animation = Instance.new("Animation")
		animation.AnimationId = v.AnimationId
		animTrack = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(animation)
		animTrack:Play()
		task.wait(0.2)
		animTrack:Destroy()
		local animation2 = Instance.new("Animation")
		animation2.AnimationId = v.Parent.B2.AnimationId
		animTrack2 = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(animation2)
		animTrack2:Play()
		task.wait(0.5)
		animTrack2:Stop()
    end
end
task.wait(0.2)
    if weapon3:FindFirstChild("shovelHandle"):FindFirstChild("blockSpark") or weapon3:FindFirstChild("baseballBat"):FindFirstChild("blockSpark") or weapon3:FindFirstChild("longhandle"):FindFirstChild("blockSpark") or weapon3:FindFirstChild("snailshield"):FindFirstChild("blockSpark") or weapon3:FindFirstChild("katanaHandle"):FindFirstChild("blockSpark") then
        task.wait(1.6)
    else
        task.wait(0.5)
    end
else
    
task.wait(0.5)    


end   
end
end
end
end
end
end
end
end)
end
end)
end)

b:Toggle("Legit Auto-Parry",function(bool3)
     spawn(function()
        if bool3 then
            _G.legitautoparry = true
            notif("Legit Auto-Parry On")
        else
            _G.legitautoparry = false
            notif("Legit Auto-Parry Off")
        end

while _G.legitautoparry do task.wait()
pcall(function()
    for i,v in pairs(game:GetService("Workspace").characters:GetDescendants()) do 
        
        local weapon3 = nil
        
        if v.Name == "canAttack" and v.Value == false then
            
        local reqwepfromman = require(v.Parent.Parent.stat).S1
        
        if reqwepfromman.blockBreak == 4 then
            
        else
            
        if v.Parent.Parent.Parent:IsA("Model") and v.Parent.Parent.Parent.Humanoid then
            if v.Parent.Parent.Parent.Name == game.Players.LocalPlayer.Character.Name then
                
            else    
        
        
    local lp = game.Players.LocalPlayer
    local character = v.Parent.Parent.Parent
    local charactername = v.Parent.Parent.Parent.Name
    
        
        if (lp.Character and lp.Character:FindFirstChild("Head") and character:FindFirstChild("Head")) then
            local mag = (character.Head.Position - lp.Character.Head.Position).Magnitude
                  if mag < 13  then
                      
        if game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool") then
            weapon3 = game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool")
        end    
        
        if weapon3.values.canAttack.Value == true then
            
        local fucker = math.random(1,2)
        
        if fucker == 1 then
        
local ohString1 = "Block"
local ohBoolean2 = true

weapon3.Start:FireServer(ohString1, ohBoolean2)
for i,v in pairs(game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool"):GetDescendants()) do
    if v.Name == "B1" then
		local animation = Instance.new("Animation")
		animation.AnimationId = v.AnimationId
		animTrack = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(animation)
		animTrack:Play()
		task.wait(0.2)
		animTrack:Destroy()
		local animation2 = Instance.new("Animation")
		animation2.AnimationId = v.Parent.B2.AnimationId
		animTrack2 = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(animation2)
		animTrack2:Play()
		task.wait(0.5)
		animTrack2:Stop()
    end
end
task.wait(0.2)
    if weapon3:FindFirstChild("shovelHandle"):FindFirstChild("blockSpark") or weapon3:FindFirstChild("baseballBat"):FindFirstChild("blockSpark") or weapon3:FindFirstChild("longhandle"):FindFirstChild("blockSpark") or weapon3:FindFirstChild("snailshield"):FindFirstChild("blockSpark") or weapon3:FindFirstChild("katanaHandle"):FindFirstChild("blockSpark") then
        task.wait(1.6)
    else
        task.wait(0.5)
    end
else
    
task.wait(0.5)    

end    
end   
end
end
end
end
end
end
end
end)
end
end)
end)

b:Toggle("Allways Headshots",function(bool5)
    spawn(function()
        if bool5 then
            _G.iallowthen4 = true
            notif("Allways Headshots On")
        else
            _G.iallowthen4 = false
            notif("Allways Headshots Off")
        end

local mt = getrawmetatable(game)
make_writeable(mt)

local namecall = mt.__namecall
mt.__namecall = newcclosure(function(self, ...)
    local method = getnamecallmethod()
    local args = {...}

    if method == "FireServer" and tostring(self) == "Hit" then
        if _G.iallowthen4 then
        args[1][1]=args[1][2].Head
        return self.FireServer(self, unpack(args))
        end    
end
    return namecall(self, table.unpack(args))
end)
end)
end)

b:Toggle("Anti Stamina Usage",function(bool4)
    spawn(function()
        if bool4 then
            _G.modification = true
            notif("Anti Stamina Usage On")
        else
            _G.modification = false
            notif("Anti Stamina Usage Off")
        end
        
while _G.modification do task.wait(0.1)
pcall(function()    

        for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
            if v:IsA("Tool") then
    
                local req = require(v.stat)
    
                for i,v in next, req do
                    req.staminaUsage = -9e9
                    req.blockDefense = 9e9
                end
                
            end
        end
    
end)    
end
end)
end)

b:Toggle("Anti Slow",function(bool7)
    spawn(function()
        if bool7 then
            _G.antislow = true
            notif("Anti Slow On")
        else
            _G.antislow = false
            notif("Anti Slow Off")
        end
        
while _G.antislow do task.wait(0.1)
    pcall(function()
        for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
            if v:IsA("Tool") then
                
                if require(v.stat).S1 then
                    _G.S1ex = true
                else
                    _G.S1ex = false
                end    
                
                if require(v.stat).S2 then
                    _G.S2ex = true
                else
                    _G.S2ex = false
                end    
                
                if require(v.stat).S3 then
                    _G.S3ex = true
                else
                    _G.S3ex = false
                end    
                
                if _G.S1ex then
    
                local req = require(v.stat).S1
    
                for i,v in next, req do
                    req.slowdown = 0
                end
                
                end
                
                if _G.S2ex then
                    
                local req = require(v.stat).S2
    
                for i,v in next, req do
                    req.slowdown = 0
                end
                
                end
                
                if _G.S3ex then
                    
                local req = require(v.stat).S2
    
                for i,v in next, req do
                    req.slowdown = 0
                end
                
                end    
                
            end
        end
    end)
end
end)
end)

b:Toggle("Inf Stamina",function(bool6)
    spawn(function()
        if bool6 then
            _G.infstamina = true
            notif("Inf Stamina On")
        else
            _G.infstamina = false
            notif("Inf Stamina Off")
        end    
        
while _G.infstamina do task.wait()
    
local ohNumber1 = math.huge

game:GetService("ReplicatedStorage").events.changeStamina2:Fire(ohNumber1)

end
end)
end)

b:Toggle("No Miss",function(bool9)
    spawn(function()
       if bool9 then
           _G.nomiss = true
           notif("No Miss On")
           
                      for i,v in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
                if v:IsA("Tool") then
                   if require(game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool"):FindFirstChild("stat")).S1 then
                        
                        local nofucky = require(game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool"):FindFirstChild("stat")).S1
                        
                        nofucky.animSpeed = math.huge
                        
                        end
                        
                        if require(game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool"):FindFirstChild("stat")).S2 then
                            
                        local nofucky2 = require(game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool"):FindFirstChild("stat")).S2
                        
                        nofucky2.animSpeed = math.huge
                        
                        end                            
                          
                        if require(game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool"):FindFirstChild("stat")).S3 then
                        
                        local nofucky3 = require(game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool"):FindFirstChild("stat")).S3
                        
                        nofucky3.animSpeed = math.huge
                        
                        end 
                    end
                end
                    
            for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
                if v:IsA("Tool") then
                     if require(game.Players.LocalPlayer.Backpack:FindFirstChildWhichIsA("Tool"):FindFirstChild("stat")).S1 then
                        
                        local nofucky = require(game.Players.LocalPlayer.Backpack:FindFirstChildWhichIsA("Tool"):FindFirstChild("stat")).S1
                        
                        nofucky.animSpeed = math.huge
                        
                        end
                        
                        if require(game.Players.LocalPlayer.Backpack:FindFirstChildWhichIsA("Tool"):FindFirstChild("stat")).S2 then
                            
                        local nofucky2 = require(game.Players.LocalPlayer.Backpack:FindFirstChildWhichIsA("Tool"):FindFirstChild("stat")).S2
                        
                        nofucky2.animSpeed = math.huge
                        
                        end                            
                          
                        if require(game.Players.LocalPlayer.Backpack:FindFirstChildWhichIsA("Tool"):FindFirstChild("stat")).S3 then
                        
                        local nofucky3 = require(game.Players.LocalPlayer.Backpack:FindFirstChildWhichIsA("Tool"):FindFirstChild("stat")).S3
                        
                        nofucky3.animSpeed = math.huge
                        
                        end                    
                    end 
                end
           
       else
            _G.nomiss = false
            notif("No Miss Off")
            
            for i,v in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
                if v:IsA("Tool") then
                   if require(game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool"):FindFirstChild("stat")).S1 then
                        
                        local nofucky = require(game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool"):FindFirstChild("stat")).S1
                        
                        nofucky.animSpeed = 1
                        
                        end
                        
                        if require(game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool"):FindFirstChild("stat")).S2 then
                            
                        local nofucky2 = require(game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool"):FindFirstChild("stat")).S2
                        
                        nofucky2.animSpeed = 1
                        
                        end                            
                          
                        if require(game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool"):FindFirstChild("stat")).S3 then
                        
                        local nofucky3 = require(game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool"):FindFirstChild("stat")).S3
                        
                        nofucky3.animSpeed = 1
                        
                        end 
                    end
                end
                    
            for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
                if v:IsA("Tool") then
                     if require(game.Players.LocalPlayer.Backpack:FindFirstChildWhichIsA("Tool"):FindFirstChild("stat")).S1 then
                        
                        local nofucky = require(game.Players.LocalPlayer.Backpack:FindFirstChildWhichIsA("Tool"):FindFirstChild("stat")).S1
                        
                        nofucky.animSpeed = 1
                        
                        end
                        
                        if require(game.Players.LocalPlayer.Backpack:FindFirstChildWhichIsA("Tool"):FindFirstChild("stat")).S2 then
                            
                        local nofucky2 = require(game.Players.LocalPlayer.Backpack:FindFirstChildWhichIsA("Tool"):FindFirstChild("stat")).S2
                        
                        nofucky2.animSpeed = 1
                        
                        end                            
                          
                        if require(game.Players.LocalPlayer.Backpack:FindFirstChildWhichIsA("Tool"):FindFirstChild("stat")).S3 then
                        
                        local nofucky3 = require(game.Players.LocalPlayer.Backpack:FindFirstChildWhichIsA("Tool"):FindFirstChild("stat")).S3
                        
                        nofucky3.animSpeed = 1
                        
                        end                    
                    end 
                end
            
            
       end
    
        
    -- ty MojaveMF#2577 for the sussy ball :0
    
    if workspace:FindFirstChild("Part") then
        workspace:FindFirstChild("Part"):Destroy()
    end    
    
    local runservice
              
     local radius = 35 -- Games with decent anti cheat require lowers ones games with non can be as big as you want

    local players = game:GetService("Players")
    local plr = players.LocalPlayer

    local c = Instance.new("Part")
    c.Shape = "Ball"
    c.CanCollide = false
    c.Transparency = 0.7
    c.Color = Color3.fromRGB(255, 0, 4)
    c.Material = Enum.Material.ForceField
    c.CastShadow = false
c.Parent = game.Workspace
c.CanQuery = false
c.Size = Vector3.new(radius,radius,radius)

    c.Touched:Connect(function(hit)
        
        
        if players:GetPlayerFromCharacter(hit.Parent) == game.Players.LocalPlayer then

        elseif players:GetPlayerFromCharacter(hit.Parent) then
            if hit.Parent.Humanoid.Health == 0 then
                
          else
            local stepped
            stepped = game:GetService("RunService").Heartbeat:Connect(function()
                    if game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool") then
                        
                        if require(game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool"):FindFirstChild("stat")).S1 then
                        
                        local nofucky = require(game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool"):FindFirstChild("stat")).S1
                        
                        nofucky.animSpeed = math.huge
                        
                        end
                        
                        if require(game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool"):FindFirstChild("stat")).S2 then
                            
                        local nofucky2 = require(game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool"):FindFirstChild("stat")).S2
                        
                        nofucky2.animSpeed = math.huge
                        
                        end                            
                          
                        if require(game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool"):FindFirstChild("stat")).S3 then
                        
                        local nofucky3 = require(game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool"):FindFirstChild("stat")).S3
                        
                        nofucky3.animSpeed = math.huge
                        
                        end                            
                        
                        if game.Players.LocalPlayer.Character:FindFirstChild("katana") then
                            game.Players.LocalPlayer.Character:FindFirstChild("katana"):FindFirstChild("katanaHandle").Position = hit.Parent:WaitForChild("HumanoidRootPart").Position
                            game.Players.LocalPlayer.Character:FindFirstChild("katana"):FindFirstChild("katanaHandle").CanCollide = false
                        elseif not game.Players.LocalPlayer.Character:FindFirstChild("katana") then
                        if game.Players.LocalPlayer.Character:FindFirstChild("fireAxe") then
                            game.Players.LocalPlayer.Character:FindFirstChild("fireAxe"):FindFirstChild("wood").Position = hit.Parent:WaitForChild("HumanoidRootPart").Position
                            game.Players.LocalPlayer.Character:FindFirstChild("fireAxe"):FindFirstChild("wood").CanCollide = false
                        elseif not game.Players.LocalPlayer.Character:FindFirstChild("fireAxe") then
                        if game.Players.LocalPlayer.Character:FindFirstChild("longsword") then
                            game.Players.LocalPlayer.Character:FindFirstChild("longsword"):FindFirstChild("longhandle").Position = hit.Parent:WaitForChild("HumanoidRootPart").Position
                            game.Players.LocalPlayer.Character:FindFirstChild("longsword"):FindFirstChild("longhandle").CanCollide = false
                        elseif not game.Players.LocalPlayer.Character:FindFirstChild("longsword") then
                        if game.Players.LocalPlayer.Character:FindFirstChild("baseballBat") then
                            game.Players.LocalPlayer.Character:FindFirstChild("baseballBat"):FindFirstChild("baseballBat").Position = hit.Parent:WaitForChild("HumanoidRootPart").Position
                        elseif not game.Players.LocalPlayer.Character:FindFirstChild("baseballBat") then
                        if game.Players.LocalPlayer.Character:FindFirstChild("fists")then
                            game.Players.LocalPlayer.Character:FindFirstChild("fists"):FindFirstChild("Left").Position = hit.Parent:WaitForChild("HumanoidRootPart").Position
                            game.Players.LocalPlayer.Character:FindFirstChild("fists"):FindFirstChild("Right").Position = hit.Parent:WaitForChild("HumanoidRootPart").Position
                            game.Players.LocalPlayer.Character:FindFirstChild("fists"):FindFirstChild("Left").CanCollide = false
                            game.Players.LocalPlayer.Character:FindFirstChild("fists"):FindFirstChild("Right").CanCollide = false
                        elseif not game.Players.LocalPlayer.Character:FindFirstChild("fists") then
                        if game.Players.LocalPlayer.Character:FindFirstChild("fryingPan") then
                            game.Players.LocalPlayer.Character:FindFirstChild("fryingPan"):FindFirstChild("fryingPanHandle").Position = hit.Parent:WaitForChild("HumanoidRootPart").Position
                            game.Players.LocalPlayer.Character:FindFirstChild("fryingPan"):FindFirstChild("fryingPanHandle").CanCollide = false
                        elseif not game.Players.LocalPlayer.Character:FindFirstChild("fryingPan") then
                        if game.Players.LocalPlayer.Character:FindFirstChild("shovel") then
                            game.Players.LocalPlayer.Character:FindFirstChild("shovel"):FindFirstChild("shovelHandle").Position = hit.Parent:WaitForChild("HumanoidRootPart").Position
                            game.Players.LocalPlayer.Character:FindFirstChild("shovel"):FindFirstChild("shovelHandle").CanCollide = false
                        elseif not game.Players.LocalPlayer.Character:FindFirstChild("shovel") then  
                        if game.Players.LocalPlayer.Character:FindFirstChild("armingsword") then
                            game.Players.LocalPlayer.Character:FindFirstChild("armingsword"):FindFirstChild("armingshandle").Position = hit.Parent:WaitForChild("HumanoidRootPart").Position
                            game.Players.LocalPlayer.Character:FindFirstChild("armingsword"):FindFirstChild("snailshield").Position = hit.Parent:WaitForChild("HumanoidRootPart").Position
                            game.Players.LocalPlayer.Character:FindFirstChild("armingsword"):FindFirstChild("armingshandle").CanCollide = false
                            game.Players.LocalPlayer.Character:FindFirstChild("armingsword"):FindFirstChild("snailshield").CanCollide = false
                        elseif not game.Players.LocalPlayer.Character:FindFirstChild("armingsword") then
                        if game.Players.LocalPlayer.Character:FindFirstChild("spear") then
                            game.Players.LocalPlayer.Character:FindFirstChild("spear"):FindFirstChild("spearHandle").Position = hit.Parent:WaitForChild("HumanoidRootPart").Position
                            game.Players.LocalPlayer.Character:FindFirstChild("spear"):FindFirstChild("spearHandle").CanCollide = false
                        elseif not game.Players.LocalPlayer.Character:FindFirstChild("spear") then
                        if game.Players.LocalPlayer.Character:FindFirstChild("crowbar") then
                            game.Players.LocalPlayer.Character:FindFirstChild("crowbar"):FindFirstChild("shovelHandle").Position = hit.Parent:WaitForChild("HumanoidRootPart").Position
                            game.Players.LocalPlayer.Character:FindFirstChild("crowbar"):FindFirstChild("shovelHandle").CanCollide = false
                        elseif not game.Players.LocalPlayer.Character:FindFirstChild("crowbar") then 
                        if game.Players.LocalPlayer.Character:FindFirstChild("cleaver") then
                            game.Players.LocalPlayer.Character:FindFirstChild("cleaver"):FindFirstChild("cleaverHandle").Position = hit.Parent:WaitForChild("HumanoidRootPart").Position
                            game.Players.LocalPlayer.Character:FindFirstChild("cleaver"):FindFirstChild("cleaverHandle").CanCollide = false
                        elseif not game.Players.LocalPlayer.Character:FindFirstChild("cleaver") then
                        if game.Players.LocalPlayer.Character:FindFirstChild("knife") then
                            game.Players.LocalPlayer.Character:FindFirstChild("knife"):FindFirstChild("london").Position = hit.Parent:WaitForChild("HumanoidRootPart").Position
                            game.Players.LocalPlayer.Character:FindFirstChild("knife"):FindFirstChild("london").CanCollide = false
                        end
                        end
                        end
                        end
                        end
                        end
                        end
                        end
                        end
                        end
                        end
                        end
                        end
                            
                            
            if hit.Parent.Humanoid.Died or wait(3) then
                stepped:Disconnect()
            end
            end)
            end
        end
    
end)

runservice = game:GetService("RunService").RenderStepped:Connect(function()
    pcall(function()
        if _G.nomiss then
            c.CFrame = game.Players.LocalPlayer.Character.Torso.CFrame
        else
            runservice:Disconnect()
            workspace:FindFirstChild("Part"):Destroy()
        end
    end)
end)
end)
end)

b:Toggle("Kill Say",function(bool8)
    spawn(function()
        if bool8 then
            _G.killsay = true
            notif("Kill Say On")
        else
            _G.killsay = false
            notif("Kill Say Off")
        end
 
local Value = game:GetService("Players").LocalPlayer.playerData.Kills
local thing

thing = Value.Changed:Connect(function()
if _G.killsay then
local killsaywords = {
    "L bozo",
    "Ez",
    "Stop being garbage",
    "Dayum",
    "Free kill"
}

game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer(killsaywords[math.random(#killsaywords)], "All")
else
    thing:Disconnect()
end
end)  
end)
end)

b:Toggle("Auto Respawn",function(bool10)
    spawn(function()
        if bool10 then
            _G.autorespawn = true
            notif("Auto Respawn On")
        else
            _G.autorespawn = false
            notif("Auto Respawn Off")
        end

while _G.autorespawn do task.wait()
    pcall(function()
        game:GetService("ReplicatedStorage").events.respawnRequest:InvokeServer()
    end)
end
end)
end)

b:Box("Salvage All Except","string",function(item)
    
    if item == "" then 
    
    else    
    
    if item == "sledgehammer" or item == "metalBat" or item == "baseballBat" or item == "fireAxe" or item == "greatsword" or item == "chainsaw" or item == "spear" or item == "cleaver" or item == "fryingPan" or item == "armingsword" or item == "fists" or item == "rapier" or item == "knife" or item == "crowbar" or item == "yoyo" or item == "shovel" or item == "longsword" then

    for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
        if v:IsA("Tool") then
            v.Parent = game.Players.LocalPlayer.Backpack
        end
    end
    
    task.wait(0.1)

    local realpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position

    for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
        if v:IsA("Tool") then
        if v.Name == item then
        
        else


game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-11.6017, 101.75, -58.0946)
task.wait(0.2)
local ohString1 = ""..v.Name..""
local ohString2 = "Salvage"
local ohInstance3 = workspace.map.workbench.workbenchMain

game:GetService("ReplicatedStorage").events.purchaseRequest:FireServer(ohString1, ohString2, ohInstance3)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(302.946, 81.7, 202.482)
task.wait(0.2)
local ohString1 = ""..v.Name..""
local ohString2 = "Salvage"
local ohInstance3 = workspace.map.workbench.workbenchMain

game:GetService("ReplicatedStorage").events.purchaseRequest:FireServer(ohString1, ohString2, ohInstance3)

end
end
end
task.wait(0.5)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(realpos)
game:GetService("Workspace").map.workbench2.Name = "workbench"
else

end    
end
end)

b:Button("List Of Items",function()
    function s(word)
        print(word)
    end
    
    s("Capitals Matter")
    s("")
    s("")
    s("baseballBat")
    s("fists")
    s("shovel")
    s("rapier")
    s("longsword")
    s("greatsword")
    s("chainsaw")
    s("knife")
    s("fryingPan")
    s("armingsword")
    s("spear")
    s("yoyo")
    s("cleaver")
    s("crowbar")
    s("metalBat")
    s("sledgehammer")
    s("")
    s("")
    s("There are more but im not sure what their name is since i never got to see their atcual name")
    notif("Press F9 To Check Console (Where The Items Were Printed Out)")
end)    

notif("Reworked Auto Parry (Should work atleast 25% better now also fake blocks (didnt test if they are FE)), Auto Respawn")
