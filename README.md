local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "Nimdas Scripthub", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

--[[
Name = <string> - The name of the UI.
HidePremium = <bool> - Whether or not the user details shows Premium status or not.
SaveConfig = <bool> - Toggles the config saving in the UI.
ConfigFolder = <string> - The name of the folder where the configs are saved.
IntroEnabled = <bool> - Whether or not to show the intro animation.
IntroText = <string> - Text to show in the intro animation.
IntroIcon = <string> - URL to the image you want to use in the intro animation.
Icon = <string> - URL to the image you want displayed on the window.
CloseCallback = <function> - Function to execute when the window is closed.
]]

local Section = Tab:AddSection({
	Name = "Universal 🌌"
})

--[[
Name = <string> - The name of the section.
]]

local Tab = Window:MakeTab({
	Name = "Universal",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]

Tab:AddButton({
	Name = "Fly ✈️",
	Callback = function()
loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\40\39\104\116\116\112\115\58\47\47\103\105\115\116\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\109\101\111\122\111\110\101\89\84\47\98\102\48\51\55\100\102\102\57\102\48\97\55\48\48\49\55\51\48\52\100\100\100\54\55\102\100\99\100\51\55\48\47\114\97\119\47\101\49\52\101\55\52\102\52\50\53\98\48\54\48\100\102\53\50\51\51\52\51\99\102\51\48\98\55\56\55\48\55\52\101\98\51\99\53\100\50\47\97\114\99\101\117\115\37\50\53\50\48\120\37\50\53\50\48\102\108\121\37\50\53\50\48\50\37\50\53\50\48\111\98\102\108\117\99\97\116\111\114\39\41\44\116\114\117\101\41\41\40\41\10\10")()
      		print("button pressed")
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Godmode (buggy) ",
	Callback = function()
local player = game.Players.LocalPlayer
 
if player.Character then
 
if player.Character:FindFirstChild("Humanoid") then
 
player.Character.Humanoid.Name = "1"
 
end
 
local l = player.Character["1"]:Clone()
 
l.Parent = player.Character
 
l.Name = "Humanoid"; wait(0.1)
 
player.Character["1"]:Destroy()
 
workspace.CurrentCamera.CameraSubject = player.Character.Humanoid
 
player.Character.Animate.Disabled = true; wait(0.1)
 
player.Character.Animate.Disabled = false
 
end
 
print("finished.")
      		print("button pressed")
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Walk On Walls 🧱",
	Callback = function()
loadstring(game:HttpGet("https://pastebin.com/raw/zXk4Rq2r"))()
      		print("button pressed")
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Infinite Yield ♾️",
	Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
      		print("button pressed")
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({ Name = "Rewind time ⏰", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/0Ben1/fe./main/L"))() print("button pressed") end
})

--[[ Name = - The name of the button. Callback = - The function of the button. ]]

local Tab = Window:MakeTab({ Name = "Tab 3", Icon = "rbxassetid://7734058599", PremiumOnly = false })

local Section = Tab:AddSection({ Name = "Strongest Battlesgrounds 💪" })

--[[ Name = - The name of the section. ]]

Tab:AddButton({ Name = "KadeHub ☠️", Callback = function() --[[ WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk! ]] ----<< LOADER >> ----- if getgenv().KadeHubLoaded ~= true then getgenv().KadeHubLoaded = true loadstring(game:HttpGet("https://raw.githubusercontent.com/skibiditoiletfan2007/Work/main/latest.lua"))() else game.StarterGui:SetCore("SendNotification", { Title = "KadeHub"; Text = "KadeHub is already executed!"; Icon = "rbxassetid://17893547380"; Duration = 15; }) end print("button pressed") end
})

--[[ Name = - The name of the button. Callback = - The function of the button. ]]

Tab:AddButton({ Name = "Phantasm Hub 👻", Callback = function() getgenv().ToggleKeybind = Enum.KeyCode.RightControl getgenv().FreeEmotesTab = true -- if you want free emotes turn this to true

--// https://discord.gg/bntsEjwnA5 (you should join forreal real....)

loadstring(game:HttpGet("https://raw.githubusercontent.com/ATrainz/main/main/Phantasm-Loader.lua"))() print("button pressed") end
})

--[[ Name = - The name of the button. Callback = - The function of the button. ]]

local Tab = Window:MakeTab({ Name = "Tab 4", Icon = "rbxassetid://7733964808", PremiumOnly = false })

local Section = Tab:AddSection({ Name = "Pet simulator 99 😺🐶" })

--[[ Name = - The name of the section. ]]

Tab:AddButton({ Name = "Redz Hub 🍒", Callback = function() --[[ WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk! ]] loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/PetSimulator99/main/redz9999.lua"))() print("button pressed") end
})

--[[ Name = - The name of the button. Callback = - The function of the button. ]]

Tab:AddButton({ Name = "Halloween Special (limited)", Callback = function() loadstring(game:HttpGet("https://rawscripts.net/raw/Pet-Simulator-99!-Cheat-Menu-17428"))() print("button pressed") end
})

--[[ Name = - The name of the button. Callback = - The function of the button. ]]

local Tab = Window:MakeTab({ Name = "Tab 5", Icon = "rbxassetid://7733955664", PremiumOnly = false })

local Section = Tab:AddSection({ Name = "slap battles 👏" })

--[[ Name = - The name of the section. ]]

Tab:AddButton({ Name = "Giang hub 🙏", Callback = function() --[[ WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk! ]] loadstring(game:HttpGet("https://raw.githubusercontent.com/Giangplay/Slap_Battles/main/Slap_Battles.lua"))() print("button pressed") end
})

--[[ Name = - The name of the button. Callback = - The function of the button. ]]

Tab:AddButton({ Name = "Kykyryz0B hub", Callback = function() --[[ WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk! ]] loadstring(game:HttpGet("https://raw.githubusercontent.com/KykyryzoB/KykyryzoB-Hub-SB/main/KykryzoB.lua"))() print("button pressed") end
})

--[[ Name = - The name of the button. Callback = - The function of the button. ]]

Tab:AddButton({ Name = "Voxul Hub 🟣 (SR only)", Callback = function() --[[ WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk! ]] loadstring(game:HttpGet('https://raw.githubusercontent.com/Voxul/VoxulHub/main/loader.lua'))() print("button pressed") end
})

--[[ Name = - The name of the button. Callback = - The function of the button. ]]

local Tab = Window:MakeTab({ Name = "Tab 6", Icon = "rbxassetid://4483345998", PremiumOnly = false })

local Section = Tab:AddSection({ Name = "Blade ball 🏀" })

--[[ Name = - The name of the section. ]]

Tab:AddButton({ Name = "Zyphrantis Hub 🥓!", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/bankboi001fr/bankboi001fr/refs/heads/main/Loader",true))() print("button pressed") end
})

--[[ Name = - The name of the button. Callback = - The function of the button. ]]

Tab:AddButton({ Name = "plutonium Hub🌅 (Random Scripts just search)", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/PawsThePaw/Plutonium.AA/main/Plutonium.Loader.lua", true))() print("button pressed") end
})

--[[ Name = - The name of the button. Callback = - The function of the button. ]]

local Tab = Window:MakeTab({ Name = "Tab 7", Icon = "rbxassetid://7734058345", PremiumOnly = false })

local Section = Tab:AddSection({ Name = "Mm2 🔪" })

--[[ Name = - The name of the section. ]]

Tab:AddButton({ Name = "Highlight hub 🐈‍⬛ (hlvipcomingsoon)", Callback = function() --[[ WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk! ]] loadstring(game:HttpGet("https://raw.githubusercontent.com/ThatSick/HighlightMM2/main/Main"))() print("button pressed") end
})

--[[ Name = - The name of the button. Callback = - The function of the button. ]]

Tab:AddButton({ Name = "XXX , I meant... Xhub ♥️", Callback = function()

loadstring(game:HttpGet("https://raw.githubusercontent.com/Au0yX/Community/main/XhubMM2"))() print("button pressed") end
})

--[[ Name = - The name of the button. Callback = - The function of the button. ]]

local Tab = Window:MakeTab({ Name = "Tab 8", Icon = "rbxassetid://7743872929", PremiumOnly = false })

--[[ Name = - The name of the tab. Icon = - The icon of the tab. PremiumOnly = - Makes the tab accessible to Sirus Premium users only. ]]

local Section = Tab:AddSection({ Name = "Blox fruits 🍑" })

--[[ Name = - The name of the section. ]]

Tab:AddButton({ Name = "Azure Hub 🔵", Callback = function() loadstring(game:HttpGet("https://scriptblox.com/raw/Blox-Fruits-w-azure-hub-10114"))() print("button pressed") end
})

--[[ Name = - The name of the button. Callback = - The function of the button. ]] Tab:AddButton({ Name = "Redz Hub 🍒 (Blox fruit)", Callback = function() loadstring(game:HttpGet("https://rawscripts.net/raw/Blox-Fruits-RedzHub-No-Key-Autofarm-17214"))() print("button pressed") end
})
