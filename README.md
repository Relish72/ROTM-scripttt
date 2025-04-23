--Tp To Object
local rootPart = game.Players.LocalPlayer.Character.HumanoidRootPart
rootPart.CFrame = Path.CFrame

--Tp to multiple objects
local rootPart = game.Players.LocalPlayer.Character.HumanoidRootPart
for i, v in pairs(path:GetChildren()) do
if v:IsA("PartName") then
rootPart.CFrame = v.CFrame
end
end

--Tp to CFrame
local rootPart = game.Players.LocalPlayer.Character.HumanoidRootPart
rootPart.CFrame = CFrame.new(CFrame)

game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 169
game.Players.LocalPlayer.Character.Humanoid.JumpPower = 420
