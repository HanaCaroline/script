# script
Script Roblox Leaderstats

game.Players.PlayerAdded:Connect(function(player)
 local leaderstats = Instance.new("Folder")
 leaderstats.Name = "Leaderstats"
 Leaderstats.Parent = player

 local cash = Instance.new("IntValue")
 cash.Name = "Cash"
 cash.Value = 0
 cash.Parent = leaderstats
