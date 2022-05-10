repeat
           wait()
   if game:GetService("Players").LocalPlayer.PlayerGui:FindFirstChild("Camera_Bob") then
       game:GetService("Players").LocalPlayer.PlayerGui:FindFirstChild("Camera_Bob"):Destroy()
   end
   until not game:GetService("Players").LocalPlayer.PlayerGui:FindFirstChild("Camera_Bob")
