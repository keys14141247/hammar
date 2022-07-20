	local plr = game.Players.LocalPlayer
				local savedbatpos = plr.Character.HumanoidRootPart.Position
				plr.Character.HumanoidRootPart.CFrame = CFrame.new(-903.6304931640625, 21.757530212402344, -296.4586486816406)
				wait(1)
				fireclickdetector(game.Workspace.Ignored.Shop['[SledgeHammer] - $350'].ClickDetector)
				fireclickdetector(game.Workspace.Ignored.Shop['[SledgeHammer] - $350'].ClickDetector)
				plr.Character.HumanoidRootPart.CFrame = CFrame.new(savedbatpos)
				plr.Character.HumanoidRootPart.CFrame = CFrame.new(savedbatpos)
				wait(2.5)
				pcall(function()
					for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
						if v.Name == '[SledgeHammer]' then
							v.Parent = game.Players.LocalPlayer.Character
						end
					end
				end)
				wait(.9)
				local plr = game.Players.LocalPlayer
				local pos = plr.Character.HumanoidRootPart.Position
				if not game.Players.LocalPlayer.Character:FindFirstChild("[SledgeHammer]") then
					plr.Character.HumanoidRootPart.CFrame = targetpos
					local cd = game:GetService("Workspace").Ignored.Shop["[SledgeHammer] - $350"]:FindFirstChild("ClickDetector")
					wait(.9)
					fireclickdetector(cd)
					wait(.4)
					game.Players.LocalPlayer.Backpack:FindFirstChild("[SledgeHammer]").Parent = plr.Character
					wait(.9)
					fireclickdetector(cd)
					wait(.4)
					game.Players.LocalPlayer.Backpack:FindFirstChild("[SledgeHammer]").Parent = plr.Character
					for i,v in pairs(plr.Character:GetChildren()) do
						if v.Name == '[SledgeHammer]' then
							v:GetChildren()[3]:Destroy()
						end
					end
					local sd = plr.Character:FindFirstChild("[SledgeHammer]")
					sd.Grip = CFrame.new(-2.4000001, -0.699999988, 0, 0, 1, -0, -1, 0, -0, 0, 0, 1)
					sd.GripForward = Vector3.new(0, 0, -1)
					sd.GripPos = Vector3.new(-2.4, -0.7, 0)
					sd.GripUp = Vector3.new(1, 0, 0)
					plr.Character.HumanoidRootPart.CFrame = CFrame.new(pos)
				end
				local sd = plr.Character:FindFirstChild("[SledgeHammer]")
				sd.Grip = CFrame.new(-2.4000001, -0.699999988, 0, 0, 1, -0, -1, 0, -0, 0, 0, 1)
				sd.GripForward = Vector3.new(0, -1, -0)
				sd.GripPos = Vector3.new(1.2111, 1.11114, 1.8111)
				sd.GripUp = Vector3.new(-500000, 404, 5000000)
				plr.Character.HumanoidRootPart.CFrame = CFrame.new(pos)
				
				
