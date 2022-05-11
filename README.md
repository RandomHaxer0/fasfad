local weapontable = {"fists","baseballBat","knife","shovel","fryingPan","cleaver","fireAxe","armingsword","crowbar","spear","katana","longsword","rapier","yoyo","pencil","metalBat","sledgehammer","chainsaw","greatsword"}
local equiptable = {"fists","baseballBat","knife","shovel","fryingPan","cleaver","fireAxe","armingsword","crowbar","spear","katana","longsword","rapier","yoyo","pencil"}

spawn(function()
local msg = Instance.new("Message",workspace)
msg.Text = "No Miss Doesn't Work With All Weps (Doesn't Work With Any Of The Upgraded Weapons, Chainsaw, GreatSword, Fists, Rapier And Yoyo Cuz Im A Lazy Fuck Haha!)"
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

local w = library:CreateWindow("Madness combat game") -- Creates the window

local b = w:CreateFolder("Main")

b:Label("",{
    TextSize = 25; -- Self Explaining
    TextColor = Color3.fromRGB(255,255,255); -- Self Explaining
    BgColor = Color3.fromRGB(69,69,69); -- Self Explaining
    
})

b:Toggle("RageMode Auto-Parry",function(bool)
     spawn(function()
        if bool then
            _G.rageautoparry = true
            notif("RageMode Auto-Parry On")
        else
            _G.rageautoparry = false
            notif("RageMode Auto-Parry Off")
        end

while _G.rageautoparry do task.wait()
pcall(function()
    for i,v in pairs(game:GetService("Workspace").characters:GetDescendants()) do 
        
        local weapon1 = nil
        
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
            weapon1 = game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool")
        end    
        
        if weapon1.values.canAttack.Value == true then
            
local ohString1 = "Block"
local ohBoolean2 = true

weapon1.Start:FireServer(ohString1, ohBoolean2)

task.wait(1.4)

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
        if bool2 then
            _G.kindalegitautoparry = true
            notif("Kinda Legit Auto-Parry On")
        else
            _G.kindalegitautoparry = false
            notif("Kinda Legit Auto-Parry Off")
        end

while _G.kindalegitautoparry do task.wait()
pcall(function()
    for i,v in pairs(game:GetService("Workspace").characters:GetDescendants()) do 
        
        local weapon2 = nil
        
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
            weapon2 = game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool")
        end    
        
        if weapon2.values.canAttack.Value == true then
            
local ohString1 = "Block"
local ohBoolean2 = true

weapon2.Start:FireServer(ohString1, ohBoolean2)
keypress(0x51)
task.wait()
keyrelease(0x51)

task.wait(1.4)

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
keypress(0x51)
task.wait()
keyrelease(0x51)

task.wait(1.4)

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
            for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
            if v:IsA("Tool") then
    
                local req = require(v.stat)
    
                for i,v in next, req do
                    req.staminaUsage = 5
                    req.blockDefense = 4
                end
                
            end
        end
        end
        
while _G.modification do task.wait(0.1)
pcall(function()    

        for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
            if v:IsA("Tool") then
    
                local req = require(v.stat)
    
                for i,v in next, req do
                    req.staminaUsage = -9e9
                    req.blockDefense = 4
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
                    
                local req = require(v.stat)
                
                for i,v in next, req do
                    req.bSlowdown = 0.5
                end
    
                local req2 = require(v.stat).S1
    
                for i,v in next, req2 do
                    req2.slowdown = 0.1
                    req2.hardSlow = false
                end
                
                end
                
                if _G.S2ex then
                    
                local req3 = require(v.stat).S2
    
                for i,v in next, req3 do
                    req3.slowdown = 0.1
                    req3.hardSlow = false
                end
                
                end
                
                if _G.S3ex then
                    
                local req4 = require(v.stat).S2
    
                for i,v in next, req4 do
                    req4.slowdown = 0.1
                    req4.hardSlow = false
                end
                
                end    
                
            end
        end
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
                    
                local req = require(v.stat)
                
                for i,v in next, req do
                    req.bSlowdown = 0
                end
    
                local req2 = require(v.stat).S1
    
                for i,v in next, req2 do
                    req2.slowdown = 0
                    req2.hardSlow = false
                end
                
                end
                
                if _G.S2ex then
                    
                local req3 = require(v.stat).S2
    
                for i,v in next, req3 do
                    req3.slowdown = 0
                    req3.hardSlow = false
                end
                
                end
                
                if _G.S3ex then
                    
                local req4 = require(v.stat).S2
    
                for i,v in next, req4 do
                    req4.slowdown = 0
                    req4.hardSlow = false
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

b:Box("Equip Weapon","string",function(string500)
    spawn(function()
    if not _G.firsttimer23 then
        local fia = Instance.new("Message",workspace)
        fia.Text = "Make sure you run this on death screen or menu or inventory menu"
        task.wait(5)
        fia:Destroy()
        _G.firsttimer23 = true
    end
    end)
    
    if string500 == "" then
    
    else
        
    for i,v in pairs(equiptable) do
        if string500 == v then
            local ohString1 = ""..string500..""
            local ohString2 = "Equip"
            
            game:GetService("ReplicatedStorage").events.purchaseRequest:FireServer(ohString1, ohString2)
        else

        end
    end
    
    notif("If the item exists or unlocked then you will get it on respawn.")
    
end

end)

b:Button("Item List(Equip)",function()
    function s(word)
        print(word)
    end
    
    s("Capitals Matter")
    s("Equip Item List")
    s("")
    s("")
    for i,v in pairs(equiptable) do
        print(i,v)
    end    
    s("")
    s("")
    notif("Press F9 To Check Console (Where The Items Were Printed Out)")
end) 

b:Box("Scrap All Except","string",function(item)
    
    if item == "" then 
    
    else    
    
    for i,v in pairs(weapontable) do
    
    if item == v then

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
end
end)

b:Button("Scrap All Except Main",function()

    for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
        if v:IsA("Tool") then
            v.Parent = game.Players.LocalPlayer.Backpack
        end
    end
    
    task.wait(0.1)

    local realpos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position

    for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
        if v:IsA("Tool") then
        if v.Name == ""..game:GetService("Players").LocalPlayer.playerData.equipment.melee.Value.."" then
        
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
end)

b:Button("Item List(Scrap)",function()
    function s(word)
        print(word)
    end
    
    s("Capitals Matter")
    s("Scrap Item list")
    s("")
    s("")
    for i,v in pairs(weapontable) do
        print(i,v)
    end
    s("")
    s("")
    s("There are more but im not sure what their name is since i never got to see their atcual name")
    notif("Press F9 To Check Console (Where The Items Were Printed Out)")
end) 

b:Button("HitBox Expander",function()
    if _G.allreadyhitbox then
        notif("Allready executed press the insert button if u accidently hid the ui.")
    else
        _G.allreadyhitbox = true
        loadstring(game:HttpGet("http://gameovers.net/Scripts/Free/HitboxExpander/main.lua", true))()
    end
end)  
        
notif("Auto Respawn, Equip Item, Item List(Equip), HitBox Expander (not mine i forgor who made it, works 50% ig)")
