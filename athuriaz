while true do wait(0)
    
    pcall(function() 
        for i, v in pairs(game.Players:GetPlayers()) do
		if v ~= game.Players.LocalPlayer then 
            local args = {
                [1] = game:GetService("Players").LocalPlayer.Character.AWM,
                [2] = {
                    ["p"] = Vector3.new(-281.4503173828125, 4574.97412109375, -2086.21240234375),
                    ["pid"] = 1,
                    ["part"] = game:GetService("Players")[v.Name].Character.Head,
                    ["d"] = 21.2694091796875,
                    ["maxDist"] = 21.264816284179688,
                    ["h"] = game:GetService("Players")[v.Name].Character.Humanoid,
                    ["m"] = Enum.Material.Plastic,
                    ["sid"] = 2,
                    ["t"] = 0.8949427503925736,
                    ["n"] = Vector3.new(-0.9315371513366699, 0.03282869607210159, -0.36216142773628235)
                }
            }
            
            game:GetService("ReplicatedStorage").WeaponsSystem.Network.WeaponHit:FireServer(unpack(args))

		end	
	end       
    end) 
end
