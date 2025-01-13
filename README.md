local replicated_storage = game:GetService("ReplicatedStorage");

game:GetService("RunService").RenderStepped:Connect(function()
    replicated_storage.packages.Net["RE/DailyReward/Claim"]:FireServer();
end)
