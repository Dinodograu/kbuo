-- se _G.HOHO_RAN então retornar fim
-- _G.HOHO_RAN = verdadeiro
-- a maioria dos executores emite
para Índice, Valor em próximo, depurar fazer
    se não getgenv()[Índice] então
        getgenv()[Índice] = Valor
    fim
fim

repita wait() até game:IsLoaded() e game.Players.LocalPlayer

Nome do Executor local = identifyexecutor()

getgenv().bit = bit32 -- Problema com Cubix e Awp :)

se ExecutorName:find("Swift") então -- não me pergunte, não sei por que funciona :D?
	tarefa.spawn(função()
	    loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/main/HohoHub.lua'))()
	fim)
	espere(2.5)
	para i, v em pares(game.CoreGui:GetChildren()) faça
	    se v.Nome:find("Hoho") então
	        v:Destruir()
	    fim
	fim
elseif ExecutorName:find("Seli") então -- Seliware
	rgenv local = getrenv()
	renv local = getrawmetatable(rgenv).__index
	para i,v em seguida, renv do
		rgenv[i] = v
	fim
fim

-- cloneref
-- local a=Instance.new("Part")para b,c em pares(getreg())faça se type(c)=="table"e#c então se rawget(c,"__mode")=="kvs"então para d,e em pares(c)faça se e==a então getgenv().InstanceList=c;quebrar fim fim fim fim fim;local f={}função f.invalidate(g)se não for InstanceList então retorne fim;para b,c em pares(InstanceList)faça se c==g então InstanceList[b]=nil;retorne g fim fim fim;se não for cloneref então getgenv().cloneref=f.invalidate fim
-- requer
-- se clonefunction e getrenv e getidentity e setidentity então local a=clonefunction(getrenv().require)getgenv().require=function(...)local b=getidentity()setidentity(1)local c=a(...)setidentity(b)return c fim fim

notificação local = loadstring(game:HttpGet("https://raw.githubusercontent.com/acsu123/HOHO_H/main/Notification.lua"))()

se _G.HohoVersion == "v3" ou _G["Fumo Blox Fruit - HoHo Hub Kaitun V3"] ou _G["HoHo Hub Auto Bounty V3"] ou _G["HoHo Fruits Collector"] ou _G.HOHO_PVP_UI ou _G.HOHO_SERVER_ID então
	-- retornar loadstring(jogo:HttpGet("https://raw.githubusercontent.com/acsu123/HohoV2/Free/BloxFruitFreeV3.lua"))()
fim

-- _G.HOHO_AD = {
-- [1] = {link="https://gcdnb.pbrd.co/images/AVitm37MSdIY.png", exp=tick()+9999, read = "https://discord.gg/CWvQUcfr25"},
-- }
lista local = {
	--Adote-me
	[383310974] = "loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HohoV2/refs/heads/Free/AdoptMe.lua'))()",
	
	--VÁ PESCAR
	[6764180126] = "loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HohoV2/refs/heads/Free/GOFISHING.lua'))()",
	
	--Peixe
	[5750914919] = "loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HohoV2/refs/heads/Free/Fisch.lua'))()",
	
	--Pet Catchers
	[5686465822] = "loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HohoV2/Free/PetCatchers.lua'))()",
	
	--Batalhas de tapa
	[2380077519] = "loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HohoV2/Free/SlapBattles.lua'))()",
	
	--RNG do Sol
	[5361032378] = "loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HohoV2/Free/SolRNG.lua'))()",
	
	--Os campos de batalha mais fortes
	[3808081382] = "loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HohoV2/Free/TheStrongestBattleground.lua'))()",
	
	--PORTAS
	[2440500124] = "loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HohoV2/Free/Doors.lua'))()",
	
	--BOLA DE LÂMINA
	[4777817887] = "loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HohoV2/Free/BladeBall.lua'))()",
	
	--SIMULADOR FERROVIÁRIO HONKAI STAR
	[5477548919] = "loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HohoV2/Free/HonkaiStarRailSimulator.lua'))()",
	
	--Guerras de Cama
	[2619619496] = "loadstring(game:HttpGet('https://raw.githubusercontent.com/acsu123/GAME/main/bedwar.txt'))()",

	--Campo de Batalha Elementar
	[224422602] = "loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/SCRIPTS/elementBattlegr.lua'))()",

	--Legado do Rei
	[1451439645] = "loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HohoV2/Free/KingLegacyFree.lua'))()",

	--Fruta Blox
	[994732206] = "loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HohoV2/main/BloxFruit/BloxFruitTEST_ONLY.lua'))()",

	--Simulador de animais de estimação X
	[2316994223] = "loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HohoV2/Free/PetSimXFree.lua'))()",

	--Ataque Zumbi
	[504035427]="loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/SCRIPTS/ZombieAtack.lua'))()",

	--Duas peças
	[5303541547]="loadstring(jogo:HttpGet('https://raw.githubusercontent.com/AlongNgu/alonebruh/main/twoPiecehoho.lua'))()",

	--Missão de Masmorra
	[848145103]="loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/Paid/DunegonQuest.lua'))()",

	--Terras comerciais
	[92096286]="loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/SCRIPTS/TradeLands.lua'))()",

	--Simulador de lutadores de anime
	[2324662457]="loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/SCRIPTS/anime%20fighters%20simulator.lua'))()",

	--Arsenal
	[111958650]="loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/SCRIPTS/Arsenal.lua'))()",

	--Amansar
	[1318971886]="loadstring(jogo:HttpGet('https://pastebin.com/raw/xUGJt9Ry', true))()",

	--Torre do Inferno
	[703124385]="loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/SCRIPTS/TowerOfHell.lua'))()",

	--uma peça do steve
	[741590026]="loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/SCRIPTS/SteveOnePiece.lua'))()",

	--Mistério de Assassinato 2
	[66654135]="loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/GAME/main/muder%20mys..2.txt'))()",

	--Sobrevivência gigante!
	[1342991001]="loadstring(jogo:HttpGet('https://pastebin.com/raw/zABEESgr', true))()",

	--Viagem de campo Z
	[1701332290]="loadstring(jogo:HttpGet('https://pastebin.com/raw/aY7Z3Nd3', true))()",

	--Cidade Louca
	[498490399]="loadstring(jogo:HttpGet('https://pastebin.com/raw/EwnNCfin', verdadeiro))()",

	--vn pedaço
	[1493595237]="loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/SCRIPTS/vn%20Piece%20script-obfuscated.lua', verdadeiro))()",
	
	--Ro Fruta
	[3904583189]="loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HohoV2/Free/RoFruitFree.lua', verdadeiro))()",

	--Colete todos os animais de estimação
	[3359505957]="loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HohoV2/Free/CollectAllPetsFree.lua', verdadeiro))()",
	
	--GPO
	[648454481]="loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HohoV2/Free/GPOFree.lua', verdadeiro))()",

	--Simulador de Defesa de Anime
	[4205109410]="loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HohoV2/Free/AnimeDefenseSimulatorFree.lua', verdadeiro))()",

	--Simulador de Alma de Anime
	[4098816381]="loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HohoV2/Free/AnimeSoulSimulatorFree.lua', verdadeiro))()",
}
-- lista localPre = {
-- --SIMULADOR FERROVIÁRIO HONKAI STAR
-- [5477548919] = "loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HohoV2/Free/HonkaiStarRailSimulator.lua'))()",
	
-- --Guerras de Cama
-- [2619619496] = "loadstring(game:HttpGet('https://raw.githubusercontent.com/acsu123/GAME/main/bedwar.txt'))()",

-- --Campo de Batalha Elementar
-- [224422602] = "loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/SCRIPTS/elementBattlegr.lua'))()",

-- --Legado do Rei
-- [1451439645] = "loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HohoV2/Pre/KingLegacyPre.lua'))()",

-- --Fruta Blox
-- [994732206] = "loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HohoV2/main/BloxFruit/BloxFruitTEST_ONLY.lua'))()",

-- --Simulador de animais de estimação X
-- [2316994223] = "loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HohoV2/Free/PetSimXFree.lua'))()",

-- --Ataque Zumbi
-- [504035427]="loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/SCRIPTS/ZombieAtack.lua'))()",

-- --Duas peças
-- [5303541547]="loadstring(jogo:HttpGet('https://raw.githubusercontent.com/AlongNgu/alonebruh/main/twoPiecehoho.lua'))()",

-- --Missão de Masmorra
-- [848145103]="loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/Paid/DunegonQuest.lua'))()",

-- --Terras comerciais
-- [92096286]="loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/SCRIPTS/TradeLands.lua'))()",

-- --Simulador de Lutadores de Anime
-- [2324662457]="loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/SCRIPTS/anime%20fighters%20simulator.lua'))()",

-- --Arsenal
-- [111958650]="loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/SCRIPTS/Arsenal.lua'))()",

-- --Amansar
-- [1318971886]="loadstring(jogo:HttpGet('https://pastebin.com/raw/xUGJt9Ry', true))()",

-- --Torre do Inferno
-- [703124385]="loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/SCRIPTS/TowerOfHell.lua'))()",

-- --uma peça do steve
-- [741590026]="loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/SCRIPTS/SteveOnePiece.lua'))()",

-- --Mistério de Assassinato 2
-- [66654135]="loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/GAME/main/muder%20mys..2.txt'))()",

-- --Sobrevivência gigante!
-- [1342991001]="loadstring(jogo:HttpGet('https://pastebin.com/raw/zABEESgr', true))()",

-- --Viagem de campo Z
-- [1701332290]="loadstring(jogo:HttpGet('https://pastebin.com/raw/aY7Z3Nd3', true))()",

-- --Cidade Louca
-- [498490399]="loadstring(jogo:HttpGet('https://pastebin.com/raw/EwnNCfin', verdadeiro))()",

-- --vn pedaço
-- [1493595237]="loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/SCRIPTS/vn%20Piece%20script-obfuscated.lua', true))()",
	
-- --Ro Fruta
-- [3904583189]="loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HohoV2/Pre/RoFruitPre.lua', verdadeiro))()",
	
-- --Colete todos os animais de estimação
-- [3359505957]="loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HohoV2/Pre/CollectAllPetsPre.lua', verdadeiro))()",
	
-- --GPO
-- [648454481]="loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HohoV2/Pre/GPOPre.lua', true))()",

-- --Simulador de Defesa de Anime
-- [4205109410]="loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HohoV2/Pre/AnimeDefenseSimulatorPre.lua', true))()",
	
-- --Simulador de Alma de Anime
-- [4098816381]="loadstring(jogo:HttpGet('https://raw.githubusercontent.com/acsu123/HohoV2/Pre/AnimeSoulSimulatorPre.lua', true))()",
-- }
-- _G.GameSupport = {"Pet Simulator X","GPO - Grand Piece Online","Blox Fruit","King Legacy","Anime Soul Simulator","Anime Defense Simulator","Ro Fruit","Colete todos os animais de estimação","Torre do Inferno","Invasão","Arsenal","Mad City","Viet Nam Piece","Field Trip Z","Giant Survival!","Murder Mystery 2","Steve's One Piece","Anime Fighters Simulator","Tradelands","Dungeon Quest","Two Piece"}
_G.HoHoLoaded = verdadeiro
-- _G.MY_KEY_IS = "Sem_Chave"
-- gerar(função()
-- função local CoreGuiAdd(a)local b,c=pcall(function()a.Parent=gethui()end)se c então warn("falha ao adicionar",a.Name,"ao gethui!")local b,c=pcall(function()a.Parent=game.CoreGui end)se c então a.DisplayOrder=100000;a.ResetOnSpawn=false;a.Parent=game.Players.LocalPlayer:WaitForChild("PlayerGui")warn("falha ao adicionar",a.Name,"ao coregui!")end end end

-- função local CreateGroupAds()
-- Grupos de anúncios locais = {}
-- ADS local = Instance.new("ScreenGui")
-- local Voltar = Instance.new("Quadro")
-- Rótulo local = Instance.new("TextLabel")
-- UIStroke local = Instância.new("UIStroke")
-- Fechar local = Instance.new("TextButton")
-- local UIStroke_1 = Instância.new("UIStroke")
-- local Interno = Instance.new("Quadro")
-- local UIGridLayout = Instance.new("UIGridLayout")
-- UIPadding local = Instância.new("UIPadding")
    
-- ADS.Nome = "ADS"
-- ADS.ZIndexBehavior = Enum.ZIndexBehavior.Irmão
-- CoreGuiAdd(ADS)
    
-- Voltar.BorderSizePixel = 0
-- Voltar.BackgroundColor3 = Cor3.fromRGB(80, 80, 80)
-- Voltar.Tamanho = UDim2.novo(0,9, 0, 0,5, 0)
-- Voltar.BorderColor3 = Cor3.fromRGB(0, 0, 0)
-- Voltar.Nome = "Voltar"
-- Voltar.Posição = UDim2.new(0, 0, 0.62406, 0)
-- Voltar.Pai = ADS
    
-- Label.TextWrapped = verdadeiro
-- Rótulo.BorderSizePixel = 0
-- Label.TextScaled = verdadeiro
-- Rótulo.BackgroundColor3 = Cor3.fromRGB(0, 255, 255)
-- Label.FontFace = Font.new("rbxasset://fonts/families/HighwayGothic.json", Enum.FontWeight.Regular, Enum.FontStyle.Normal)
-- Rótulo.Posição = UDim2.new(0, 0, -0.0666667, 0)
-- Rótulo.Nome = "Rótulo"
-- Rótulo.TamanhoDoTexto = 14
-- Rótulo.Tamanho = UDim2.new(1, 0, 0.07, 0)
-- Rótulo.ZIndex = 2
-- Label.TextColor3 = Color3.fromRGB(0, 0, 0)
-- Rótulo.BorderColor3 = Cor3.fromRGB(0, 0, 0)
-- Label.Text = "HOHO ADS (entre em contato com discrod.gg/hohohub) (fechamento automático em 60s)"
-- Label.Parent = Voltar
    
-- UIStroke.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
-- UIStroke.Parent = Rótulo
    
-- Fechar.TextWrapped = verdadeiro
-- Fechar.ZIndex = 2
-- Fechar.BorderSizePixel = 0
-- Fechar.TextScaled = verdadeiro
-- Fechar.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
-- Fechar.Posição = UDim2.new(0,961977, 0, -0,0666667, 0)
-- Fechar.FontFace = Font.new("rbxasset://fonts/families/SourceSansPro.json", Enum.FontWeight.Regular, Enum.FontStyle.Normal)
-- Fechar.Nome = "Fechar"
-- Fechar.TextSize = 14
-- Fechar.Tamanho = UDim2.novo(0,03, 0, 0,1, 0)
-- Fechar.TextColor3 = Color3.fromRGB(255, 255, 255)
-- Fechar.BorderColor3 = Cor3.fromRGB(255, 0, 0)
-- Fechar.Texto = "X"
-- Fechar.Parent = Voltar
    
-- UIStroke_1.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
-- UIStroke_1.Parent = Fechar
    
-- Inner.BorderSizePixel = 0
-- Inner.BackgroundColor3 = Cor3.fromRGB(255, 255, 255)
-- Inner.Size = UDim2.new(1, 0, 0, 0.5)
-- Inner.BorderColor3 = Cor3.fromRGB(0, 0, 0)
-- Inner.BackgroundTransparency = 1
-- Inner.Name = "Interno"
-- Inner.Parent = Voltar
    
-- UIGridLayout.SortOrder = Enum.SortOrder.LayoutOrder
-- UIGridLayout.CellSize = UDim2.new(0, 250, 0, 250)
-- UIGridLayout.Parent = Interno
    
-- UIPadding.PaddingLeft = UDim.new(0,025, 0)
-- UIPadding.Parent = Interno
        
-- Fechar.MouseButton1Click:Conectar(função()
-- jogo.Debris:AddItem(ADS, 0)
-- fim)
        
-- jogo.Debris:AddItem(ADS, 60)
        
-- função GroupAds:CreateAds(Imagem, Link)
-- ImageButton local = Instance.new("ImageButton")
-- ImageButton.Parent = Interno
-- ImageButton.BackgroundColor3 = Cor3.fromRGB(255, 255, 255)
-- ImageButton.BorderColor3 = Cor3.fromRGB(0, 0, 0)
-- ImageButton.BorderSizePixel = 0
-- ImageButton.Size = UDim2.new(0, 100, 0, 100)
-- ImageButton.Image = Imagem
-- ImageButton.HoverImage = "http://www.roblox.com/asset/?id=3229099135"
            
-- ImageButton.MouseButton1Click:Conectar(função()
-- jogo:GetService("StarterGui"):SetCore("SendNotification",{
-- Título = "HOHO ADS", -- Obrigatório
-- Texto = "Anúncios copiados para sua área de transferência!",
-- Ícone = Imagem
-- })
-- definirárea de transferência(Link)
-- fim)
-- fim
        
-- retornar GroupAds
-- fim
    
-- função local GetImage(nome, url)
-- caminho local = nome .. ".png"
-- se não for isfile(caminho) então
-- conteúdo local = jogo:HttpGet(url)
-- writefile(caminho, conteúdo)
-- fim
-- retornar getcustomasset(caminho)
-- fim
    
-- -- local GroupADS = CreateGroupAds()
-- -- GroupADS:CreateAds(GetImage("accbloxnet", "https://i.imgur.com/4fhvSM3.png"), "https://accblox.net/")
-- -- GroupADS:CreateAds(GetImage("hohodiscord", "https://i.imgur.com/e2fdiZD.png"), "https://discord.gg/hohohub")
-- fim)

notify.New("Este não é um anúncio de bug, apenas uma notificação para alguém que não sabe!", 30)
notify.New("Se o script não carregar, tente usar VPN ou ALTERAR EXECUTOR!", 30)

se lista[jogo.GameId] ~= nulo então
	loadstring(lista[tonumber(jogo.GameId)])()
outro
	notify.New("Este jogo não é suportado pelo hohohub :(", 60)
	notify.New("Por favor, junte-se ao discord.gg/hohohub para verificar qual jogo é suportado por nós!", 60)
fim
- se _G["HoHo Hub Auto Bounty V3"] ou _G["Fumo Blox Fruit - HoHo Hub Kaitun V3"] então retorne final
caminho local = "wait(5);loadstring(game:HttpGet('https://raw.githubusercontent.com/acsu123/HohoV2/main/ScriptLoad.lua'))()"
-- se getgenv().Key então
-- caminho = "getgenv().Chave = '"..getgenv().Chave.."'\n"..caminho
-- fim
-- local queueteleport = syn e syn.queue_on_teleport ou queue_on_teleport ou fluxus e fluxus.queue_on_teleport
-- queueteleport(caminho)
