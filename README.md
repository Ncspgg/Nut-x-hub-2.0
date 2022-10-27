local VLib = loadstring(game:HttpGet("https://raw.githubusercontent.com/vep1032/VepStuff/main/VL"))()

local s = VLib:Window("Nut x HUB 2.0", "All map", "N")

-- main

local ss = s:Tab("Main")

ss:Button("Infinite Yield",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)

ss:Button("CMD-X",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/CMD-X/CMD-X/master/Source",true))()
end)


ss:Slider("WalkSpeed",16,100,70,function(t)
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = (t)
end)

ss:Button("Jump Power",function()
    game.Players.LocalPlayer.Character.Humanoid.JumpPower = 150
end)

ss:Button("FPS boost",function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/Ncspgg/Fps-boost-v2/main/README.md'),true))()
end)

ss:Button("Free cam(shift+f9)",function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/ncsp555gg/Freecam/main/README.md'),true))()
end)

ss:Button("RTX",function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/ncsp555gg/RTX/main/README.md'),true))()
end)

-- Blox fruits

local ss = s:Tab("Blox fruits")


ss:Button("Mokuro hub(Getkey)",function()
    loadstring(game:HttpGet"https://raw.githubusercontent.com/xQuartyx/DonateMe/main/ScriptLoader")()
end)

ss:Button("Hulk u hub",function()
    loadstring(game:HttpGet"https://raw.githubusercontent.com/HULKUexe/-FreeUScript-/main/3GAME")()
end)

ss:Button("Hoho Hub(Get Key)",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/main/Loading_UI'))()
end)

ss:Button("Thunder Z Hub(Get Key)",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/ThunderZ-05/HUB/main/Script"))()
end)

ss:Button("Ripper Hub",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/hajibeza/RIPPER-HUB/main/RIPPERHUBV2.lua%22))()
end)


-- King legacy

local ss = s:Tab("King legacy")


ss:Button("Strike hub",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Strikehubv2z/StormSKz/main/All_in_one"))()
end)


ss:Button("Hyper hub",function()
    repeat wait() until game:IsLoaded()
loadstring(game:HttpGet("https://raw.githubusercontent.com/DookDekDEE/Hyper/main/script.lua"))()
end)


ss:Button("Hulk u hub",function()
    loadstring(game:HttpGet"https://raw.githubusercontent.com/HULKUexe/-FreeUScript-/main/3GAME")()
end)

-- The mimic

local ss = s:Tab("The mimic")


ss:Button("KTollT",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/KTollT/KTollT/main/README.md'))()
end)

-- Bed wars

local ss = s:Tab("Bed wars")


ss:Button("Vape V4",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/7GrandDadPGN/VapeV4ForRoblox/main/NewMainScript.lua", true))()
end)


-- Murder Myster2

local ss = s:Tab("Murder mystery2")

ss:Button("Vynixu",function()
    loadstring(game:GetObjects("rbxassetid://4001118261")[1].Source)()
end)

ss:Button("Eclipse Hub",function()
    getgenv().mainKey = "nil" local a,b,c,d,e=loadstring,request or http_request or (http and http.request) or (syn and syn.request),assert,tostring,"https://api.eclipsehub.xyz/auth"c(a and b,"Executor not Supported")a(b({Url=e.."\?\107e\121\61"..d(mainKey),Headers={["User-Agent"]="Eclipse"}}).Body)()
end)



-- All star

local ss = s:Tab("All star")

ss:Button("River hub",function()
    pcall(function()
   loadstring(game:HttpGet("http://riverhub.xyz/" .. tostring(game.PlaceId) .. ".lua"))()
end)
end)

-- Driving Empire

local ss = s:Tab("Driving  Empire")

ss:Button("Windy Ware 3.2.0",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/WindyKung/WindyWare/main/MainScript/DrivingEmpire.lua"))()
end)


-- Airplane Simulator

local ss = s:Tab("Airplane Simulator")

ss:Button("Airplane",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Marco8642/science/main/airplane%20simulator", true))()
end)

-- Pet simulator X

local ss = s:Tab("Pet simulator X")

ss:Button("Crimson Hub",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/TirSANX/CrimsonHUB/main/C_Loader%27))();
end)

ss:Button("ShinyTool",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/XLinestX/ShinyTool_Key/main/Loader.lua%22))()
end)

-- Pls Donate

local ss = s:Tab("Pls Donate")

ss:Button("Fake Donate",function()
    loadstring(game:HttpGet(("https://raw.githubusercontent.com/o5u3/PLS-Donate/main/Fake-Donate.lua%22)))()
end)
