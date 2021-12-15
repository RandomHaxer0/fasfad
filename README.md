local library = loadstring(game:HttpGet(('https://raw.githubusercontent.com/AikaV3rm/UiLib/master/Lib.lua')))()

local f
f = hookmetamethod(game.Players.LocalPlayer,"__namecall", function(...)
    if getnamecallmethod() == "Kick" then
        return
    end
    return f(...)
end) --- this doesnt do shit but im not removing


local w = library:CreateWindow("Transfurify remaster") -- Creates the window

local v = w:CreateFolder("Stuff")
local b = w:CreateFolder("Misc")

b:Label("Transfurify Remaster Scripts",{
    TextSize = 25; -- Self Explaining
    TextColor = Color3.fromRGB(255,255,255); -- Self Explaining
    BgColor = Color3.fromRGB(69,69,69); -- Self Explaining
    
}) 

b:Button("Anti Grab Method",function()
    _G.fuu = true
    while _G.fuu do wait(1)
    local UserInputService = game:GetService("UserInputService")
local RunService = game:GetService("RunService")
local gui = game.Players.LocalPlayer.PlayerGui.Escape.TextButton
local screenGui = gui.Parent
screenGui.IgnoreGuiInset = true
mouseLocation = UserInputService:GetMouseLocation()
gui.Position = UDim2.fromOffset(mouseLocation.X, mouseLocation.Y)
local function moveGuiToMouse()
	mouseLocation = UserInputService:GetMouseLocation()
	gui.Position = UDim2.fromOffset(mouseLocation.X, mouseLocation.Y)
end
 
RunService:BindToRenderStep("moveGuiToMouse", 1, moveGuiToMouse)
end
end)

b:Label("Use AutoClicker",{
    TextSize = 25; -- Self Explaining
    TextColor = Color3.fromRGB(255,255,255); -- Self Explaining
    BgColor = Color3.fromRGB(69,69,69); -- Self Explaining
    
})

b:Button("Auto Clicker",function()
    getgenv().Settings = {
    ["Auto Click Keybind"] = "V", -- Use an UpperCase letter or KeyCode Enum. Ex: Enum.KeyCode.Semicolon
    ["Lock Mouse Position Keybind"] = "B",
    ["Right Click"] = false,
    ["GUI"] = true, -- A drawing gui that tells you what is going on with the autoclicker.
    ["Delay"] = 0 -- 0 for RenderStepped, other numbers go to regular wait timings.
}
loadstring(game:HttpGet("https://raw.githubusercontent.com/BimbusCoder/Script/main/Auto%20Clicker.lua"))()
end)

b:Label("KeyBind V",{
    TextSize = 25; -- Self Explaining
    TextColor = Color3.fromRGB(255,255,255); -- Self Explaining
    BgColor = Color3.fromRGB(69,69,69); -- Self Explaining
    
})

b:Button("Anti Furry",function()
    _G.on = true
while _G.on do wait()
    pcall(function()
    if game.Players.LocalPlayer.PlayerGui.Overlay.Enabled == true then
    pos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
game.Players.LocalPlayer.Character.Humanoid.Health = 0
wait(6.2)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(pos) + Vector3.new(0,3,0)

end
end)
end
end)

b:Button("Anti Cum Puddles 2",function()
_G.ong = true
while _G.ong do wait(0.5)
    pcall(function()
for i,v in pairs(game.Workspace.Terrain:GetChildren()) do
    
	v.Parent = game.ServerStorage
   
end
end)
end
end)

b:Label("Bit Of Lag",{
    TextSize = 25; -- Self Explaining
    TextColor = Color3.fromRGB(255,255,255); -- Self Explaining
    BgColor = Color3.fromRGB(69,69,69); -- Self Explaining
    
})

b:Button("Anti Cum Puddles 3",function()
    for i,v in pairs(game.Workspace.Scripted.TransformBrick:GetChildren()) do
    
        
	v.Parent = game.ServerStorage
	
	
end
end)

b:Label("Anti Lizard",{
    TextSize = 25; -- Self Explaining
    TextColor = Color3.fromRGB(255,255,255); -- Self Explaining
    BgColor = Color3.fromRGB(69,69,69); -- Self Explaining
    
})

b:Label("Destroy Gui",{
    TextSize = 25; -- Self Explaining
    TextColor = Color3.fromRGB(255,255,255); -- Self Explaining
    BgColor = Color3.fromRGB(69,69,69); -- Self Explaining
    
})

b:DestroyGui()

v:Label("Other Stuff",{
    TextSize = 25; -- Self Explaining
    TextColor = Color3.fromRGB(255,255,255); -- Self Explaining
    BgColor = Color3.fromRGB(69,69,69); -- Self Explaining
    
})

v:Button("Infect Aura On",function()
    _G.ongh = true
while _G.ongh do wait(0.5)

for i,v in pairs(game.Players:GetChildren()) do
    if v then
        local v = v.Character
        
        local ohInstance1 = v.Head
        local ohTable2 = {
	["Position"] = v.Head.Position
}

game:GetService("ReplicatedStorage").Remote.Weapon.Use:FireServer(ohInstance1, ohTable2)
end
end
end
end)

v:Button("Infect Aura Off",function()
    _G.ongh = false
end)

v:Button("Loop Speed",function()
    if _G.fff == true then
        print("allready executed")
        return
    else
        _G.fff = true
        
    game:GetService("RunService").RenderStepped:Connect(function()
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 33
end)
end
end)

v:Label("Cant Turn Off",{
    TextSize = 25; -- Self Explaining
    TextColor = Color3.fromRGB(255,255,255); -- Self Explaining
    BgColor = Color3.fromRGB(69,69,69); -- Self Explaining
    
})

v:Button("Anti Stun",function()
    game:GetService("RunService").RenderStepped:Connect(function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.Anchored = false
    end)
    end)

v:Label("Also Cant Turn Off",{
    TextSize = 25; -- Self Explaining
    TextColor = Color3.fromRGB(255,255,255); -- Self Explaining
    BgColor = Color3.fromRGB(69,69,69); -- Self Explaining
    
})

v:Button("Radio Chat",function()
game:GetService("RunService").RenderStepped:Connect(function()
game:GetService("Workspace").Scripted.Radio.Radio.Part.CFrame = CFrame.new(game.Players.LocalPlayer.Character.HumanoidRootPart.Position)
end)
end)

v:Label("Also Cant Turn Off",{
    TextSize = 25; -- Self Explaining
    TextColor = Color3.fromRGB(255,255,255); -- Self Explaining
    BgColor = Color3.fromRGB(69,69,69); -- Self Explaining
    
})

v:Button("Fire All CDetectors",function()
    local Tab={}
for i,v in next, workspace:GetDescendants()  do
    if v:IsA'ClickDetector' then
        table.insert(Tab,v)
    end
end
local plr=game:GetService'Players'.LocalPlayer
spawn(function()
    local UIS=game:GetService'UserInputService'
    UIS.InputBegan:Connect(function(Key)
        if Key.KeyCode==Enum.KeyCode.X and not UIS:GetFocusedTextBox() then
            for i,v in next,Tab do
                if v:IsA'ClickDetector' then
                    print'Fired!'
                    if fireclickdetector then fireclickdetector(v) end
                end
            end
        end
    end)
end)
end)

v:Label("KeyBind X",{
    TextSize = 25; -- Self Explaining
    TextColor = Color3.fromRGB(255,255,255); -- Self Explaining
    BgColor = Color3.fromRGB(69,69,69); -- Self Explaining
    
})

v:Label("Destroy Gui",{
    TextSize = 25; -- Self Explaining
    TextColor = Color3.fromRGB(255,255,255); -- Self Explaining
    BgColor = Color3.fromRGB(69,69,69); -- Self Explaining
    
})

v:DestroyGui()
