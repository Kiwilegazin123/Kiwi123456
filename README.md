--carregar biblioteca
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()

--window
local Window = Library.CreateLib("kiwi", "Ocean")

--tabs
local Tab = Window:NewTab("brookhaven")

--section
local Section = Tab:NewSection("créditos: kiwi")

--botões
Section:NewButton("redz hub", "brookhaven", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/REDzHUB/main/REDzHUB"))()
    print("Clicked")
end)

Section:NewButton("nameles adm", "brookhaven", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/FilteringEnabled/NamelessAdmin/main/Source"))()
    print("Clicked")
end)

Section:NewButton("ghost hub", "Brookhaven", function() loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/GhostHub'))()
    print("Clicked")
end)

Section:NewButton("fling tool", "brookhaven", function() loadstring(game:HttpGet(('https://pastefy.app/'..'aV9OfBP4'..'/raw'),true))()
    print("Clicked")
end)



local Tab = Window:NewTab("blox fruit")

local Section = Tab:NewSection("créditos:kiwi")

Section:NewButton("redz hub", "Blox fruit", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/BloxFruits/main/redz9999"))()
    print("Clicked")
end)

Section:NewButton("auto farm", "Blox fruit", function() loadstring(game:HttpGet("https://github.com/PNguyen0199/Script/raw/main/Trash_Auto_Chest.lua"))()

    print("Clicked")
end)

Section:NewButton("ninja hub", "blox fruit", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/Xero2409/NinjaHub/main/ninjahub.lua"))()

    print("Clicked")
end)

Section:NewButton("script para pegar leviatã", "blox fruit", function() loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/3b2169cf53bc6104dabe8e19562e5cc2.lua"))()

    print("Clicked")
end)

Section:NewButton("kaitun pega tudo do jogo", "Blox fruit", function() loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/fdd0ae7172de98d90a108b718d0110eb.lua"))()
    print("Clicked")
end)
