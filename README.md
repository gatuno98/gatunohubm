-- Gui to Lua
-- Version: 3.2

-- Instances:

local UILibrary = Instance.new("ScreenGui")
local gatunohub = Instance.new("Frame")
local TabFrame = Instance.new("Frame")
local SideLine = Instance.new("Frame")
local TabList = Instance.new("ScrollingFrame")
local SideLine_2 = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local TopbarFrame = Instance.new("Frame")
local ImageLabel = Instance.new("ImageLabel")
local UICorner_2 = Instance.new("UICorner")
local BottomFrame = Instance.new("Frame")
local Line = Instance.new("Frame")
local Title = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local FixCorner = Instance.new("Frame")
local TextButton = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local TextButton_2 = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local TextButton_3 = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local TextButton_4 = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local TextButton_5 = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local TextButton_6 = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local TextButton_7 = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local Frame = Instance.new("Frame")
local UICorner_11 = Instance.new("UICorner")
local ImageButton = Instance.new("ImageButton")
local UICorner_12 = Instance.new("UICorner")

--Properties:

UILibrary.Name = "UILibrary"
UILibrary.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
UILibrary.DisplayOrder = 100
UILibrary.ResetOnSpawn = false

gatunohub.Name = "gatunohub"
gatunohub.Parent = UILibrary
gatunohub.AnchorPoint = Vector2.new(0.5, 0.5)
gatunohub.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
gatunohub.BorderColor3 = Color3.fromRGB(0, 0, 0)
gatunohub.BorderSizePixel = 0
gatunohub.Position = UDim2.new(0.443479747, 0, 0.440890133, 0)
gatunohub.Size = UDim2.new(0, 609, 0, 406)

TabFrame.Name = "TabFrame"
TabFrame.Parent = gatunohub
TabFrame.BackgroundColor3 = Color3.fromRGB(15, 15, 15)
TabFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
TabFrame.BorderSizePixel = 0
TabFrame.Position = UDim2.new(-0.00199993886, 0, 0.0126316436, 0)
TabFrame.Size = UDim2.new(0.300000012, 0, 0.949999988, 0)

SideLine.Name = "SideLine"
SideLine.Parent = TabFrame
SideLine.AnchorPoint = Vector2.new(1, 0)
SideLine.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
SideLine.BorderColor3 = Color3.fromRGB(0, 0, 0)
SideLine.BorderSizePixel = 0
SideLine.LayoutOrder = 1
SideLine.Position = UDim2.new(0.999999881, 0, 0, 0)
SideLine.Size = UDim2.new(0, 1, 1, 0)
SideLine.ZIndex = 10

TabList.Name = "TabList"
TabList.Parent = TabFrame
TabList.Active = true
TabList.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TabList.BackgroundTransparency = 1.000
TabList.BorderColor3 = Color3.fromRGB(0, 0, 0)
TabList.BorderSizePixel = 0
TabList.Position = UDim2.new(0, 0, 0.0999999717, 0)
TabList.Size = UDim2.new(0.993807137, 0, 0.900000036, 0)
TabList.CanvasSize = UDim2.new(0, 0, 0, 0)
TabList.ScrollBarThickness = 0

SideLine_2.Name = "SideLine"
SideLine_2.Parent = TabFrame
SideLine_2.AnchorPoint = Vector2.new(1, 0)
SideLine_2.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
SideLine_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
SideLine_2.BorderSizePixel = 0
SideLine_2.Position = UDim2.new(1, 0, 0.100000001, 0)
SideLine_2.Size = UDim2.new(1, 0, 0, 1)

UICorner.Parent = TabFrame

TopbarFrame.Name = "TopbarFrame"
TopbarFrame.Parent = TabFrame
TopbarFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TopbarFrame.BackgroundTransparency = 1.000
TopbarFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
TopbarFrame.BorderSizePixel = 0
TopbarFrame.Size = UDim2.new(1, 0, 0.100000001, 0)

ImageLabel.Parent = TopbarFrame
ImageLabel.AnchorPoint = Vector2.new(0.5, 0.5)
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BackgroundTransparency = 1.000
ImageLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel.BorderSizePixel = 0
ImageLabel.Position = UDim2.new(0.453475654, 0, 0.342773557, 0)
ImageLabel.Size = UDim2.new(0.29392454, 0, 1.47001445, 0)
ImageLabel.Image = "rbxassetid://106702991471250"
ImageLabel.ScaleType = Enum.ScaleType.Fit

UICorner_2.Parent = gatunohub

BottomFrame.Name = "BottomFrame"
BottomFrame.Parent = gatunohub
BottomFrame.AnchorPoint = Vector2.new(0, 1)
BottomFrame.BackgroundColor3 = Color3.fromRGB(23, 23, 23)
BottomFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
BottomFrame.BorderSizePixel = 0
BottomFrame.Position = UDim2.new(0, 0, 1, 0)
BottomFrame.Size = UDim2.new(1, 0, 0.0500000007, 0)

Line.Name = "Line"
Line.Parent = BottomFrame
Line.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
Line.BorderColor3 = Color3.fromRGB(0, 0, 0)
Line.BorderSizePixel = 0
Line.Size = UDim2.new(1, 0, 0, 1)
Line.ZIndex = 10

Title.Name = "Title"
Title.Parent = BottomFrame
Title.Active = false
Title.AnchorPoint = Vector2.new(0.5, 0.5)
Title.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title.BackgroundTransparency = 1.000
Title.BorderColor3 = Color3.fromRGB(0, 0, 0)
Title.BorderSizePixel = 0
Title.Position = UDim2.new(0.511249959, 0, 0.499999136, 0)
Title.Selectable = false
Title.Size = UDim2.new(0.977500021, 0, 0.600000024, 0)
Title.Font = Enum.Font.Unknown
Title.Text = "gatuno-hub: https://discord.gg/Tb9BUFkF"
Title.TextColor3 = Color3.fromRGB(116, 116, 116)
Title.TextScaled = true
Title.TextSize = 14.000
Title.TextWrapped = true

UICorner_3.Parent = BottomFrame

FixCorner.Name = "FixCorner"
FixCorner.Parent = BottomFrame
FixCorner.BackgroundColor3 = Color3.fromRGB(23, 23, 23)
FixCorner.BorderColor3 = Color3.fromRGB(0, 0, 0)
FixCorner.BorderSizePixel = 0
FixCorner.Size = UDim2.new(1, 0, 0.200000003, 0)

TextButton.Parent = gatunohub
TextButton.BackgroundColor3 = Color3.fromRGB(181, 0, 3)
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.0114942528, 0, 0.14778325, 0)
TextButton.Size = UDim2.new(0, 138, 0, 29)
TextButton.Font = Enum.Font.FredokaOne
TextButton.Text = "esp-jogador"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextWrapped = true

UICorner_4.Parent = TextButton

TextButton_2.Parent = gatunohub
TextButton_2.BackgroundColor3 = Color3.fromRGB(181, 0, 3)
TextButton_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.BorderSizePixel = 0
TextButton_2.Position = UDim2.new(0.0114942528, 0, 0.258620679, 0)
TextButton_2.Size = UDim2.new(0, 138, 0, 29)
TextButton_2.Font = Enum.Font.FredokaOne
TextButton_2.Text = "esp-arma"
TextButton_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.TextScaled = true
TextButton_2.TextSize = 14.000
TextButton_2.TextWrapped = true

UICorner_5.Parent = TextButton_2

TextButton_3.Parent = gatunohub
TextButton_3.BackgroundColor3 = Color3.fromRGB(181, 0, 3)
TextButton_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.BorderSizePixel = 0
TextButton_3.Position = UDim2.new(0.0114942528, 0, 0.364532024, 0)
TextButton_3.Size = UDim2.new(0, 138, 0, 29)
TextButton_3.Font = Enum.Font.FredokaOne
TextButton_3.Text = "tp-arma"
TextButton_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_3.TextScaled = true
TextButton_3.TextSize = 14.000
TextButton_3.TextWrapped = true

UICorner_6.Parent = TextButton_3

TextButton_4.Parent = gatunohub
TextButton_4.BackgroundColor3 = Color3.fromRGB(181, 0, 3)
TextButton_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.BorderSizePixel = 0
TextButton_4.Position = UDim2.new(0.0114942528, 0, 0.485221684, 0)
TextButton_4.Size = UDim2.new(0, 138, 0, 29)
TextButton_4.Font = Enum.Font.FredokaOne
TextButton_4.Text = "aimbot"
TextButton_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_4.TextScaled = true
TextButton_4.TextSize = 14.000
TextButton_4.TextWrapped = true

UICorner_7.Parent = TextButton_4

TextButton_5.Parent = gatunohub
TextButton_5.BackgroundColor3 = Color3.fromRGB(181, 0, 3)
TextButton_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_5.BorderSizePixel = 0
TextButton_5.Position = UDim2.new(0.0114942528, 0, 0.603448272, 0)
TextButton_5.Size = UDim2.new(0, 138, 0, 29)
TextButton_5.Font = Enum.Font.FredokaOne
TextButton_5.Text = "coletar-moedas"
TextButton_5.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_5.TextScaled = true
TextButton_5.TextSize = 14.000
TextButton_5.TextWrapped = true

UICorner_8.Parent = TextButton_5

TextButton_6.Parent = gatunohub
TextButton_6.BackgroundColor3 = Color3.fromRGB(181, 0, 3)
TextButton_6.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_6.BorderSizePixel = 0
TextButton_6.Position = UDim2.new(0.0114942528, 0, 0.706896544, 0)
TextButton_6.Size = UDim2.new(0, 138, 0, 29)
TextButton_6.Font = Enum.Font.FredokaOne
TextButton_6.Text = "no-clip"
TextButton_6.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_6.TextScaled = true
TextButton_6.TextSize = 14.000
TextButton_6.TextWrapped = true

UICorner_9.Parent = TextButton_6

TextButton_7.Parent = gatunohub
TextButton_7.BackgroundColor3 = Color3.fromRGB(181, 0, 3)
TextButton_7.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_7.BorderSizePixel = 0
TextButton_7.Position = UDim2.new(0.0114942528, 0, 0.820197046, 0)
TextButton_7.Size = UDim2.new(0, 138, 0, 29)
TextButton_7.Font = Enum.Font.FredokaOne
TextButton_7.Text = "fly"
TextButton_7.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_7.TextScaled = true
TextButton_7.TextSize = 14.000
TextButton_7.TextWrapped = true

UICorner_10.Parent = TextButton_7

Frame.Parent = gatunohub
Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.318177879, 0, 0.0434528962, 0)
Frame.Size = UDim2.new(0, 407, 0, 359)

UICorner_11.Parent = Frame

ImageButton.Parent = UILibrary
ImageButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ImageButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageButton.BorderSizePixel = 0
ImageButton.Position = UDim2.new(0.0265392791, 0, 0.118219748, 0)
ImageButton.Size = UDim2.new(0, 84, 0, 78)
ImageButton.Image = "rbxassetid://106702991471250"

UICorner_12.Parent = ImageButton

-- Scripts:

local function XDEP_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	-- Script para botão que alterna cor ao clicar
	-- Coloque este script como LocalScript dentro do botão (TextButton ou ImageButton)
	
	local button = script.Parent -- O botão onde o script está
	local originalColor = button.BackgroundColor3 -- Salva a cor original
	local isGreen = false -- Controla se está verde ou não
	
	-- Função que executa quando o botão é clicado
	local function toggleColor()
		if isGreen then
			-- Se está verde, volta para a cor original
			button.BackgroundColor3 = originalColor
			isGreen = false
			print("Botão voltou para cor original")
		else
			-- Se não está verde, fica verde
			button.BackgroundColor3 = Color3.new(0, 1, 0) -- Verde puro
			isGreen = true
			print("Botão ficou verde")
		end
	end
	
	-- Conecta a função ao evento de clique
	button.MouseButton1Click:Connect(toggleColor)
end
coroutine.wrap(XDEP_fake_script)()
local function DZQJDNH_fake_script() -- TextButton.esp 
	local script = Instance.new('LocalScript', TextButton)

	-- ESP Script para Murder Mystery 2
	-- Coloque este script como LocalScript dentro do seu botão
	
	local button = script.Parent
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	local Workspace = game:GetService("Workspace")
	
	local player = Players.LocalPlayer
	local espEnabled = false
	local espConnections = {}
	local espLabels = {}
	
	-- Função para criar ESP label
	local function createESPLabel(targetPlayer)
		if not targetPlayer.Character or not targetPlayer.Character:FindFirstChild("Head") then
			return
		end
	
		local head = targetPlayer.Character.Head
	
		-- Criar BillboardGui
		local billboard = Instance.new("BillboardGui")
		billboard.Name = "ESP_" .. targetPlayer.Name
		billboard.Parent = head
		billboard.Size = UDim2.new(0, 200, 0, 50)
		billboard.StudsOffset = Vector3.new(0, 2, 0)
		billboard.AlwaysOnTop = true
	
		-- Criar TextLabel
		local label = Instance.new("TextLabel")
		label.Parent = billboard
		label.Size = UDim2.new(1, 0, 1, 0)
		label.BackgroundTransparency = 0.5
		label.BackgroundColor3 = Color3.new(0, 0, 0)
		label.BorderSizePixel = 2
		label.TextScaled = true
		label.Font = Enum.Font.SourceSansBold
		label.TextStrokeTransparency = 0
		label.TextStrokeColor3 = Color3.new(0, 0, 0)
	
		-- Detectar papel do jogador
		local role = "Inocente"
		local textColor = Color3.new(0, 1, 0) -- Verde para inocente
		local borderColor = Color3.new(0, 1, 0)
	
		-- Verificar se tem arma (Xerife)
		if targetPlayer.Backpack:FindFirstChild("Gun") or 
			(targetPlayer.Character and targetPlayer.Character:FindFirstChild("Gun")) then
			role = "Xerife"
			textColor = Color3.new(0, 0, 1) -- Azul
			borderColor = Color3.new(0, 0, 1)
		end
	
		-- Verificar se tem faca (Assassino)
		if targetPlayer.Backpack:FindFirstChild("Knife") or 
			(targetPlayer.Character and targetPlayer.Character:FindFirstChild("Knife")) then
			role = "Assassino"
			textColor = Color3.new(1, 0, 0) -- Vermelho
			borderColor = Color3.new(1, 0, 0)
		end
	
		-- Configurar texto e cores
		label.Text = targetPlayer.Name .. "\n[" .. role .. "]"
		label.TextColor3 = textColor
		label.BorderColor3 = borderColor
	
		-- Salvar referência
		espLabels[targetPlayer] = billboard
	
		return billboard
	end
	
	-- Função para atualizar ESP de um jogador
	local function updatePlayerESP(targetPlayer)
		if not targetPlayer.Character or not targetPlayer.Character:FindFirstChild("Head") then
			return
		end
	
		local billboard = espLabels[targetPlayer]
		if not billboard then
			return
		end
	
		local label = billboard:FindFirstChild("TextLabel")
		if not label then
			return
		end
	
		-- Detectar papel atual
		local role = "Inocente"
		local textColor = Color3.new(0, 1, 0) -- Verde
		local borderColor = Color3.new(0, 1, 0)
	
		-- Verificar Xerife (Gun)
		if targetPlayer.Backpack:FindFirstChild("Gun") or 
			(targetPlayer.Character and targetPlayer.Character:FindFirstChild("Gun")) then
			role = "Xerife"
			textColor = Color3.new(0, 0, 1) -- Azul
			borderColor = Color3.new(0, 0, 1)
		end
	
		-- Verificar Assassino (Knife)
		if targetPlayer.Backpack:FindFirstChild("Knife") or 
			(targetPlayer.Character and targetPlayer.Character:FindFirstChild("Knife")) then
			role = "Assassino"
			textColor = Color3.new(1, 0, 0) -- Vermelho
			borderColor = Color3.new(1, 0, 0)
		end
	
		-- Atualizar visual
		label.Text = targetPlayer.Name .. "\n[" .. role .. "]"
		label.TextColor3 = textColor
		label.BorderColor3 = borderColor
	end
	
	-- Função para remover ESP de um jogador
	local function removePlayerESP(targetPlayer)
		if espLabels[targetPlayer] then
			espLabels[targetPlayer]:Destroy()
			espLabels[targetPlayer] = nil
		end
	end
	
	-- Função para ativar ESP
	local function enableESP()
		espEnabled = true
	
		-- Criar ESP para todos os jogadores atuais
		for _, targetPlayer in pairs(Players:GetPlayers()) do
			if targetPlayer ~= player and targetPlayer.Character then
				createESPLabel(targetPlayer)
			end
		end
	
		-- Conexão para atualizar ESP constantemente
		espConnections.updateLoop = RunService.Heartbeat:Connect(function()
			for _, targetPlayer in pairs(Players:GetPlayers()) do
				if targetPlayer ~= player and espLabels[targetPlayer] then
					updatePlayerESP(targetPlayer)
				end
			end
		end)
	
		-- Conexão para novos jogadores
		espConnections.playerAdded = Players.PlayerAdded:Connect(function(targetPlayer)
			targetPlayer.CharacterAdded:Connect(function()
				wait(1) -- Espera carregar
				if espEnabled then
					createESPLabel(targetPlayer)
				end
			end)
		end)
	
		-- Conexão para jogadores saindo
		espConnections.playerRemoving = Players.PlayerRemoving:Connect(function(targetPlayer)
			removePlayerESP(targetPlayer)
		end)
	
		print("🟢 ESP Murder Mystery 2 ATIVADO!")
	end
	
	-- Função para desativar ESP
	local function disableESP()
		espEnabled = false
	
		-- Remover todos os ESPs
		for targetPlayer, billboard in pairs(espLabels) do
			billboard:Destroy()
		end
		espLabels = {}
	
		-- Desconectar eventos
		for _, connection in pairs(espConnections) do
			connection:Disconnect()
		end
		espConnections = {}
	
		print("🔴 ESP Murder Mystery 2 DESATIVADO!")
	end
	
	-- Função principal do botão
	local function toggleESP()
		if espEnabled then
			disableESP()
		else
			enableESP()
		end
	end
	
	-- Conectar ao clique do botão
	button.MouseButton1Click:Connect(function()
		toggleESP()
	end)
	
	print("✅ ESP Murder Mystery 2 configurado! Clique no botão para ativar/desativar.")
end
coroutine.wrap(DZQJDNH_fake_script)()
local function HINSUYK_fake_script() -- TextButton_2.LocalScript 
	local script = Instance.new('LocalScript', TextButton_2)

	-- Script para botão que alterna cor ao clicar
	-- Coloque este script como LocalScript dentro do botão (TextButton ou ImageButton)
	
	local button = script.Parent -- O botão onde o script está
	local originalColor = button.BackgroundColor3 -- Salva a cor original
	local isGreen = false -- Controla se está verde ou não
	
	-- Função que executa quando o botão é clicado
	local function toggleColor()
		if isGreen then
			-- Se está verde, volta para a cor original
			button.BackgroundColor3 = originalColor
			isGreen = false
			print("Botão voltou para cor original")
		else
			-- Se não está verde, fica verde
			button.BackgroundColor3 = Color3.new(0, 1, 0) -- Verde puro
			isGreen = true
			print("Botão ficou verde")
		end
	end
	
	-- Conecta a função ao evento de clique
	button.MouseButton1Click:Connect(toggleColor)
end
coroutine.wrap(HINSUYK_fake_script)()
local function COHQAH_fake_script() -- TextButton_2.esp-arma 
	local script = Instance.new('LocalScript', TextButton_2)

	-- ESP Script para Armas Dropadas - Murder Mystery 2
	-- Coloque este script como LocalScript dentro do seu botão
	
	local button = script.Parent
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	local Workspace = game:GetService("Workspace")
	
	local player = Players.LocalPlayer
	local weaponESPEnabled = false
	local weaponESPConnections = {}
	local weaponESPLabels = {}
	
	-- Lista de nomes de armas do MM2
	local weaponNames = {
		"Gun", "Revolver", "Knife", "GunDrop", "KnifeDrop"
	}
	
	-- Função para verificar se é uma arma dropada
	local function isDroppedWeapon(object)
		-- Verifica se o nome contém palavras de armas
		for _, weaponName in pairs(weaponNames) do
			if string.find(object.Name:lower(), weaponName:lower()) then
				-- Verifica se não está no backpack ou equipado em um jogador
				local isWithPlayer = false
	
				-- Verifica se está no backpack de algum jogador
				for _, plr in pairs(Players:GetPlayers()) do
					if plr.Backpack:FindFirstChild(object.Name) then
						isWithPlayer = true
						break
					end
					-- Verifica se está equipado no personagem
					if plr.Character and plr.Character:FindFirstChild(object.Name) then
						isWithPlayer = true
						break
					end
				end
	
				-- Se não está com nenhum jogador, é uma arma dropada
				if not isWithPlayer then
					return true, weaponName
				end
			end
		end
		return false, nil
	end
	
	-- Função para criar ESP de arma
	local function createWeaponESP(weapon, weaponType)
		if not weapon:FindFirstChild("Handle") and not weapon.PrimaryPart then
			return
		end
	
		local targetPart = weapon:FindFirstChild("Handle") or weapon.PrimaryPart or weapon:FindFirstChildOfClass("Part")
		if not targetPart then
			return
		end
	
		-- Criar BillboardGui
		local billboard = Instance.new("BillboardGui")
		billboard.Name = "WeaponESP_" .. weapon.Name
		billboard.Parent = targetPart
		billboard.Size = UDim2.new(0, 150, 0, 40)
		billboard.StudsOffset = Vector3.new(0, 3, 0)
		billboard.AlwaysOnTop = true
	
		-- Criar TextLabel
		local label = Instance.new("TextLabel")
		label.Parent = billboard
		label.Size = UDim2.new(1, 0, 1, 0)
		label.BackgroundTransparency = 0.3
		label.BackgroundColor3 = Color3.new(0, 0, 0)
		label.BorderSizePixel = 2
		label.BorderColor3 = Color3.new(0, 0, 1) -- Azul
		label.TextScaled = true
		label.Font = Enum.Font.SourceSansBold
		label.TextStrokeTransparency = 0
		label.TextStrokeColor3 = Color3.new(0, 0, 0)
		label.TextColor3 = Color3.new(0, 0, 1) -- Azul
	
		-- Determinar tipo de arma para o texto
		local displayName = "Arma"
		if string.find(weapon.Name:lower(), "gun") or string.find(weapon.Name:lower(), "revolver") then
			displayName = "🔫 Gun"
		elseif string.find(weapon.Name:lower(), "knife") then
			displayName = "🔪 Knife"
		end
	
		label.Text = displayName .. "\n[Dropada]"
	
		-- Criar highlight para maior visibilidade
		local highlight = Instance.new("SelectionBox")
		highlight.Parent = targetPart
		highlight.Adornee = targetPart
		highlight.Color3 = Color3.new(0, 0, 1) -- Azul
		highlight.LineThickness = 0.2
		highlight.Transparency = 0.5
	
		-- Salvar referências
		weaponESPLabels[weapon] = {
			billboard = billboard,
			highlight = highlight
		}
	
		print("🔵 ESP criado para arma: " .. weapon.Name)
	end
	
	-- Função para remover ESP de arma
	local function removeWeaponESP(weapon)
		if weaponESPLabels[weapon] then
			if weaponESPLabels[weapon].billboard then
				weaponESPLabels[weapon].billboard:Destroy()
			end
			if weaponESPLabels[weapon].highlight then
				weaponESPLabels[weapon].highlight:Destroy()
			end
			weaponESPLabels[weapon] = nil
			print("🔴 ESP removido da arma: " .. weapon.Name)
		end
	end
	
	-- Função para escanear armas no workspace
	local function scanForWeapons()
		for _, object in pairs(Workspace:GetDescendants()) do
			if object:IsA("Model") or object:IsA("Tool") then
				local isWeapon, weaponType = isDroppedWeapon(object)
				if isWeapon and not weaponESPLabels[object] then
					createWeaponESP(object, weaponType)
				end
			end
		end
	end
	
	-- Função para ativar ESP de armas
	local function enableWeaponESP()
		weaponESPEnabled = true
	
		-- Scan inicial
		scanForWeapons()
	
		-- Conexão para scan contínuo
		weaponESPConnections.scanLoop = RunService.Heartbeat:Connect(function()
			-- Remove ESPs de armas que não existem mais ou foram pegas
			for weapon, espData in pairs(weaponESPLabels) do
				if not weapon.Parent or weapon.Parent == nil then
					removeWeaponESP(weapon)
				else
					-- Verifica se a arma ainda está dropada
					local isWeapon, _ = isDroppedWeapon(weapon)
					if not isWeapon then
						removeWeaponESP(weapon)
					end
				end
			end
	
			-- Scan por novas armas (a cada 2 segundos para performance)
			if tick() % 2 < 0.1 then
				scanForWeapons()
			end
		end)
	
		-- Conexão para novos objetos adicionados
		weaponESPConnections.childAdded = Workspace.DescendantAdded:Connect(function(object)
			if weaponESPEnabled then
				wait(0.1) -- Pequeno delay para garantir que o objeto carregou
				if object:IsA("Model") or object:IsA("Tool") then
					local isWeapon, weaponType = isDroppedWeapon(object)
					if isWeapon then
						createWeaponESP(object, weaponType)
					end
				end
			end
		end)
	
		print("🟢 ESP de Armas Dropadas ATIVADO!")
	end
	
	-- Função para desativar ESP de armas
	local function disableWeaponESP()
		weaponESPEnabled = false
	
		-- Remover todos os ESPs
		for weapon, espData in pairs(weaponESPLabels) do
			removeWeaponESP(weapon)
		end
		weaponESPLabels = {}
	
		-- Desconectar eventos
		for _, connection in pairs(weaponESPConnections) do
			connection:Disconnect()
		end
		weaponESPConnections = {}
	
		print("🔴 ESP de Armas Dropadas DESATIVADO!")
	end
	
	-- Função principal do botão
	local function toggleWeaponESP()
		if weaponESPEnabled then
			disableWeaponESP()
		else
			enableWeaponESP()
		end
	end
	
	-- Conectar ao clique do botão
	button.MouseButton1Click:Connect(function()
		toggleWeaponESP()
	end)
	
	print("✅ ESP de Armas Dropadas configurado! Clique no botão para ativar/desativar.")
end
coroutine.wrap(COHQAH_fake_script)()
local function TBKQQZ_fake_script() -- TextButton_3.LocalScript 
	local script = Instance.new('LocalScript', TextButton_3)

	-- Script para botão que alterna cor ao clicar
	-- Coloque este script como LocalScript dentro do botão (TextButton ou ImageButton)
	
	local button = script.Parent -- O botão onde o script está
	local originalColor = button.BackgroundColor3 -- Salva a cor original
	local isGreen = false -- Controla se está verde ou não
	
	-- Função que executa quando o botão é clicado
	local function toggleColor()
		if isGreen then
			-- Se está verde, volta para a cor original
			button.BackgroundColor3 = originalColor
			isGreen = false
			print("Botão voltou para cor original")
		else
			-- Se não está verde, fica verde
			button.BackgroundColor3 = Color3.new(0, 1, 0) -- Verde puro
			isGreen = true
			print("Botão ficou verde")
		end
	end
	
	-- Conecta a função ao evento de clique
	button.MouseButton1Click:Connect(toggleColor)
end
coroutine.wrap(TBKQQZ_fake_script)()
local function DZQZST_fake_script() -- TextButton_3.tp-arma 
	local script = Instance.new('LocalScript', TextButton_3)

	-- Script de Teleport para Armas Dropadas - Murder Mystery 2
	-- Coloque este script como LocalScript dentro do seu botão
	
	local button = script.Parent
	local Players = game:GetService("Players")
	local UserInputService = game:GetService("UserInputService")
	local RunService = game:GetService("RunService")
	local Workspace = game:GetService("Workspace")
	
	local player = Players.LocalPlayer
	local weaponTPEnabled = false
	local weaponConnections = {}
	
	-- Lista de nomes de armas do MM2
	local weaponNames = {
		"Gun", "Revolver", "Knife", "GunDrop", "KnifeDrop"
	}
	
	-- Função para verificar se é uma arma dropada
	local function isDroppedWeapon(object)
		-- Verifica se o nome contém palavras de armas
		for _, weaponName in pairs(weaponNames) do
			if string.find(object.Name:lower(), weaponName:lower()) then
				-- Verifica se não está no backpack ou equipado em um jogador
				local isWithPlayer = false
	
				-- Verifica se está no backpack de algum jogador
				for _, plr in pairs(Players:GetPlayers()) do
					if plr.Backpack:FindFirstChild(object.Name) then
						isWithPlayer = true
						break
					end
					-- Verifica se está equipado no personagem
					if plr.Character and plr.Character:FindFirstChild(object.Name) then
						isWithPlayer = true
						break
					end
				end
	
				-- Se não está com nenhum jogador, é uma arma dropada
				if not isWithPlayer then
					return true
				end
			end
		end
		return false
	end
	
	-- Função para encontrar armas dropadas
	local function findDroppedWeapons()
		local droppedWeapons = {}
	
		for _, object in pairs(Workspace:GetDescendants()) do
			if (object:IsA("Model") or object:IsA("Tool")) and isDroppedWeapon(object) then
				local targetPart = object:FindFirstChild("Handle") or object.PrimaryPart or object:FindFirstChildOfClass("Part")
				if targetPart then
					table.insert(droppedWeapons, {
						weapon = object,
						part = targetPart,
						position = targetPart.Position
					})
				end
			end
		end
	
		return droppedWeapons
	end
	
	-- Função para encontrar a arma mais próxima
	local function findClosestWeapon()
		if not player.Character or not player.Character:FindFirstChild("HumanoidRootPart") then
			return nil
		end
	
		local playerPosition = player.Character.HumanoidRootPart.Position
		local droppedWeapons = findDroppedWeapons()
	
		if #droppedWeapons == 0 then
			return nil
		end
	
		-- Encontrar a arma mais próxima
		local closestWeapon = nil
		local closestDistance = math.huge
	
		for _, weaponData in pairs(droppedWeapons) do
			local distance = (playerPosition - weaponData.position).Magnitude
			if distance < closestDistance then
				closestDistance = distance
				closestWeapon = weaponData
			end
		end
	
		return closestWeapon
	end
	
	-- Função para teleportar para uma posição
	local function teleportTo(position)
		if not player.Character or not player.Character:FindFirstChild("HumanoidRootPart") then
			print("❌ Personagem não encontrado!")
			return false
		end
	
		-- Teleporta um pouco acima da arma para não bugar
		local teleportPosition = position + Vector3.new(0, 3, 0)
		player.Character.HumanoidRootPart.CFrame = CFrame.new(teleportPosition)
	
		return true
	end
	
	-- Função para teleportar para arma mais próxima
	local function teleportToClosestWeapon()
		local weaponData = findClosestWeapon()
	
		if not weaponData then
			print("❌ Nenhuma arma dropada encontrada!")
			return
		end
	
		local success = teleportTo(weaponData.position)
		if success then
			local weaponType = "Arma"
			if string.find(weaponData.weapon.Name:lower(), "gun") or string.find(weaponData.weapon.Name:lower(), "revolver") then
				weaponType = "Gun 🔫"
			elseif string.find(weaponData.weapon.Name:lower(), "knife") then
				weaponType = "Knife 🔪"
			end
	
			print("✅ Teleportado para " .. weaponType .. "!")
		end
	end
	
	-- Função para lidar com cliques em armas
	local function onWeaponClicked(weapon, targetPart)
		if not weaponTPEnabled then
			return
		end
	
		if not isDroppedWeapon(weapon) then
			print("❌ Esta arma não está dropada!")
			return
		end
	
		local success = teleportTo(targetPart.Position)
		if success then
			local weaponType = "Arma"
			if string.find(weapon.Name:lower(), "gun") or string.find(weapon.Name:lower(), "revolver") then
				weaponType = "Gun 🔫"
			elseif string.find(weapon.Name:lower(), "knife") then
				weaponType = "Knife 🔪"
			end
	
			print("✅ Teleportado para " .. weaponType .. " (clique)!")
		end
	end
	
	-- Função para configurar cliques em armas
	local function setupWeaponClicks()
		for _, object in pairs(Workspace:GetDescendants()) do
			if (object:IsA("Model") or object:IsA("Tool")) and isDroppedWeapon(object) then
				local targetPart = object:FindFirstChild("Handle") or object.PrimaryPart or object:FindFirstChildOfClass("Part")
				if targetPart and targetPart:IsA("BasePart") then
					local clickDetector = targetPart:FindFirstChild("ClickDetector")
					if not clickDetector then
						clickDetector = Instance.new("ClickDetector")
						clickDetector.Parent = targetPart
						clickDetector.MaxActivationDistance = 50
					end
	
					clickDetector.MouseClick:Connect(function()
						onWeaponClicked(object, targetPart)
					end)
				end
			end
		end
	end
	
	-- Função para ativar teleport de armas
	local function enableWeaponTP()
		weaponTPEnabled = true
	
		-- Configurar cliques iniciais
		setupWeaponClicks()
	
		-- Conexão para tecla E (teleport para mais próxima)
		weaponConnections.keyPress = UserInputService.InputBegan:Connect(function(input, gameProcessed)
			if gameProcessed then return end
	
			if weaponTPEnabled and input.KeyCode == Enum.KeyCode.E then
				teleportToClosestWeapon()
			end
		end)
	
		-- Conexão para novas armas que aparecem
		weaponConnections.childAdded = Workspace.DescendantAdded:Connect(function(object)
			if weaponTPEnabled then
				wait(0.1)
				if (object:IsA("Model") or object:IsA("Tool")) and isDroppedWeapon(object) then
					local targetPart = object:FindFirstChild("Handle") or object.PrimaryPart or object:FindFirstChildOfClass("Part")
					if targetPart and targetPart:IsA("BasePart") then
						local clickDetector = Instance.new("ClickDetector")
						clickDetector.Parent = targetPart
						clickDetector.MaxActivationDistance = 50
	
						clickDetector.MouseClick:Connect(function()
							onWeaponClicked(object, targetPart)
						end)
					end
				end
			end
		end)
	
		print("🟢 TELEPORT PARA ARMAS ATIVADO!")
		print("💡 Pressione E para teleportar para a arma mais próxima")
		print("💡 Ou clique diretamente na arma que quer")
	end
	
	-- Função para desativar teleport de armas
	local function disableWeaponTP()
		weaponTPEnabled = false
	
		-- Desconectar eventos
		for _, connection in pairs(weaponConnections) do
			connection:Disconnect()
		end
		weaponConnections = {}
	
		print("🔴 TELEPORT PARA ARMAS DESATIVADO!")
	end
	
	-- Função principal do botão
	local function toggleWeaponTP()
		if weaponTPEnabled then
			disableWeaponTP()
		else
			enableWeaponTP()
		end
	end
	
	-- Conectar ao clique do botão
	button.MouseButton1Click:Connect(function()
		toggleWeaponTP()
	end)
	
	print("✅ Teleport para Armas Dropadas configurado!")
	print("🎯 Clique no botão para ativar/desativar")
end
coroutine.wrap(DZQZST_fake_script)()
local function ZVZMD_fake_script() -- TextButton_4.LocalScript 
	local script = Instance.new('LocalScript', TextButton_4)

	-- Script para botão que alterna cor ao clicar
	-- Coloque este script como LocalScript dentro do botão (TextButton ou ImageButton)
	
	local button = script.Parent -- O botão onde o script está
	local originalColor = button.BackgroundColor3 -- Salva a cor original
	local isGreen = false -- Controla se está verde ou não
	
	-- Função que executa quando o botão é clicado
	local function toggleColor()
		if isGreen then
			-- Se está verde, volta para a cor original
			button.BackgroundColor3 = originalColor
			isGreen = false
			print("Botão voltou para cor original")
		else
			-- Se não está verde, fica verde
			button.BackgroundColor3 = Color3.new(0, 1, 0) -- Verde puro
			isGreen = true
			print("Botão ficou verde")
		end
	end
	
	-- Conecta a função ao evento de clique
	button.MouseButton1Click:Connect(toggleColor)
end
coroutine.wrap(ZVZMD_fake_script)()
local function WCXGQBU_fake_script() -- TextButton_4.aimbot 
	local script = Instance.new('LocalScript', TextButton_4)

	-- Aimbot para Assassino - Murder Mystery 2
	-- Coloque este script como LocalScript dentro do seu botão
	
	local button = script.Parent
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	local UserInputService = game:GetService("UserInputService")
	local Camera = workspace.CurrentCamera
	local GuiService = game:GetService("GuiService")
	
	local player = Players.LocalPlayer
	local mouse = player:GetMouse()
	
	-- Configurações do Aimbot
	local aimbotEnabled = false
	local aimbotConnections = {}
	local fovCircle = nil
	
	-- Configurações
	local FOV_SIZE = 100 -- Tamanho do FOV em pixels
	local SMOOTH_FACTOR = 0.2 -- Suavidade do aimbot (0.1 = muito suave, 1 = instantâneo)
	local TARGET_PART = "Head" -- Parte do corpo para mirar
	
	-- Função para criar círculo do FOV
	local function createFOVCircle()
		local screenGui = player.PlayerGui:FindFirstChild("AimbotGUI")
		if not screenGui then
			screenGui = Instance.new("ScreenGui")
			screenGui.Name = "AimbotGUI"
			screenGui.Parent = player.PlayerGui
			screenGui.ResetOnSpawn = false
		end
	
		-- Remover círculo anterior se existir
		if fovCircle then
			fovCircle:Destroy()
		end
	
		-- Criar novo círculo
		fovCircle = Instance.new("Frame")
		fovCircle.Name = "FOVCircle"
		fovCircle.Parent = screenGui
		fovCircle.Size = UDim2.new(0, FOV_SIZE * 2, 0, FOV_SIZE * 2)
		fovCircle.Position = UDim2.new(0.5, -FOV_SIZE, 0.5, -FOV_SIZE)
		fovCircle.BackgroundTransparency = 1
		fovCircle.BorderSizePixel = 0
	
		-- Criar UICorner para fazer círculo
		local corner = Instance.new("UICorner")
		corner.CornerRadius = UDim.new(0.5, 0)
		corner.Parent = fovCircle
	
		-- Criar UIStroke para a borda vermelha
		local stroke = Instance.new("UIStroke")
		stroke.Color = Color3.new(1, 0, 0) -- Vermelho
		stroke.Thickness = 2
		stroke.Transparency = 0.3
		stroke.Parent = fovCircle
	
		print("🔴 Círculo FOV criado!")
	end
	
	-- Função para remover círculo do FOV
	local function removeFOVCircle()
		if fovCircle then
			fovCircle:Destroy()
			fovCircle = nil
		end
	
		local screenGui = player.PlayerGui:FindFirstChild("AimbotGUI")
		if screenGui then
			screenGui:Destroy()
		end
	
		print("❌ Círculo FOV removido!")
	end
	
	-- Função para verificar se jogador é assassino
	local function isAssassin(targetPlayer)
		if not targetPlayer or targetPlayer == player then
			return false
		end
	
		-- Verificar se tem faca (Knife)
		if targetPlayer.Backpack:FindFirstChild("Knife") or 
			(targetPlayer.Character and targetPlayer.Character:FindFirstChild("Knife")) then
			return true
		end
	
		return false
	end
	
	-- Função para encontrar o assassino
	local function findAssassin()
		for _, targetPlayer in pairs(Players:GetPlayers()) do
			if isAssassin(targetPlayer) and targetPlayer.Character and targetPlayer.Character:FindFirstChild(TARGET_PART) then
				return targetPlayer
			end
		end
		return nil
	end
	
	-- Função para verificar se o alvo está dentro do FOV
	local function isInFOV(targetPosition)
		local screenPoint = Camera:WorldToScreenPoint(targetPosition)
		local screenCenter = Vector2.new(Camera.ViewportSize.X / 2, Camera.ViewportSize.Y / 2)
		local distance = (Vector2.new(screenPoint.X, screenPoint.Y) - screenCenter).Magnitude
	
		return distance <= FOV_SIZE
	end
	
	-- Função para obter a posição do alvo na tela
	local function getTargetScreenPosition(targetPart)
		local targetPosition = targetPart.Position
		local screenPoint = Camera:WorldToScreenPoint(targetPosition)
		return Vector2.new(screenPoint.X, screenPoint.Y), screenPoint.Z > 0
	end
	
	-- Função principal do aimbot
	local function aimbot()
		if not aimbotEnabled then
			return
		end
	
		local assassin = findAssassin()
		if not assassin or not assassin.Character then
			return
		end
	
		local targetPart = assassin.Character:FindFirstChild(TARGET_PART)
		if not targetPart then
			return
		end
	
		-- Verificar se está dentro do FOV
		if not isInFOV(targetPart.Position) then
			return
		end
	
		-- Obter posição na tela
		local targetScreenPos, onScreen = getTargetScreenPosition(targetPart)
		if not onScreen then
			return
		end
	
		-- Calcular diferença entre posição atual do mouse e alvo
		local mousePos = Vector2.new(mouse.X, mouse.Y)
		local difference = targetScreenPos - mousePos
	
		-- Aplicar suavização
		local smoothedDifference = difference * SMOOTH_FACTOR
	
		-- Mover o mouse suavemente
		local newX = mousePos.X + smoothedDifference.X
		local newY = mousePos.Y + smoothedDifference.Y
	
		-- Aplicar movimento (simula movimento do mouse)
		mousemoverel(smoothedDifference.X, smoothedDifference.Y)
	end
	
	-- Função para ativar aimbot
	local function enableAimbot()
		aimbotEnabled = true
	
		-- Criar círculo FOV
		createFOVCircle()
	
		-- Conexão principal do aimbot
		aimbotConnections.aimLoop = RunService.Heartbeat:Connect(function()
			aimbot()
		end)
	
		-- Atualizar posição do FOV com o mouse
		aimbotConnections.fovUpdate = RunService.Heartbeat:Connect(function()
			if fovCircle then
				local mousePos = UserInputService:GetMouseLocation()
				fovCircle.Position = UDim2.new(0, mousePos.X - FOV_SIZE, 0, mousePos.Y - FOV_SIZE)
			end
		end)
	
		print("🟢 AIMBOT ATIVADO!")
		print("🎯 Mirando apenas no assassino")
		print("🔴 Círculo vermelho = FOV do aimbot")
	end
	
	-- Função para desativar aimbot
	local function disableAimbot()
		aimbotEnabled = false
	
		-- Remover círculo FOV
		removeFOVCircle()
	
		-- Desconectar todas as conexões
		for _, connection in pairs(aimbotConnections) do
			connection:Disconnect()
		end
		aimbotConnections = {}
	
		print("🔴 AIMBOT DESATIVADO!")
	end
	
	-- Função principal do botão
	local function toggleAimbot()
		if aimbotEnabled then
			disableAimbot()
		else
			enableAimbot()
		end
	end
	
	-- Conectar ao clique do botão
	button.MouseButton1Click:Connect(function()
		toggleAimbot()
	end)
	
	-- Função para mousemoverel (compatibilidade)
	local function mousemoverel(x, y)
		local currentPos = UserInputService:GetMouseLocation()
		local newPos = currentPos + Vector2.new(x, y)
	
		-- Tentar mover usando diferentes métodos
		pcall(function()
			mouse.X = newPos.X
			mouse.Y = newPos.Y
		end)
	end
	
	print("✅ Aimbot para Assassino configurado!")
	print("🎯 Clique no botão para ativar/desativar")
	print("⚙️ FOV: " .. FOV_SIZE .. " pixels")
	print("⚙️ Suavidade: " .. SMOOTH_FACTOR)
end
coroutine.wrap(WCXGQBU_fake_script)()
local function LSIB_fake_script() -- TextButton_5.LocalScript 
	local script = Instance.new('LocalScript', TextButton_5)

	-- Script para botão que alterna cor ao clicar
	-- Coloque este script como LocalScript dentro do botão (TextButton ou ImageButton)
	
	local button = script.Parent -- O botão onde o script está
	local originalColor = button.BackgroundColor3 -- Salva a cor original
	local isGreen = false -- Controla se está verde ou não
	
	-- Função que executa quando o botão é clicado
	local function toggleColor()
		if isGreen then
			-- Se está verde, volta para a cor original
			button.BackgroundColor3 = originalColor
			isGreen = false
			print("Botão voltou para cor original")
		else
			-- Se não está verde, fica verde
			button.BackgroundColor3 = Color3.new(0, 1, 0) -- Verde puro
			isGreen = true
			print("Botão ficou verde")
		end
	end
	
	-- Conecta a função ao evento de clique
	button.MouseButton1Click:Connect(toggleColor)
end
coroutine.wrap(LSIB_fake_script)()
local function IMBTUMQ_fake_script() -- TextButton_5.coletarmoedas 
	local script = Instance.new('LocalScript', TextButton_5)

	-- Script Coletor de Moedas Automático - Murder Mystery 2
	-- Coloque este script como LocalScript dentro do seu botão
	
	local button = script.Parent
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	local TweenService = game:GetService("TweenService")
	local Workspace = game:GetService("Workspace")
	
	local player = Players.LocalPlayer
	local coinCollectorEnabled = false
	local collectorConnections = {}
	local isCollecting = false
	local coinsCollected = 0
	
	-- Configurações
	local COLLECTION_SPEED = 50 -- Velocidade de movimento para as moedas
	local COLLECTION_DISTANCE = 100 -- Distância máxima para detectar moedas
	local COLLECTION_DELAY = 0.1 -- Delay entre coletas (para não sobrecarregar)
	
	-- Função para encontrar todas as moedas no mapa
	local function findCoins()
		local coins = {}
	
		-- Procurar por moedas em diferentes locais possíveis
		local searchPaths = {
			Workspace:FindFirstChild("Debris"),
			Workspace:FindFirstChild("Coins"),
			Workspace:FindFirstChild("CoinContainer"),
			Workspace
		}
	
		for _, searchPath in pairs(searchPaths) do
			if searchPath then
				for _, object in pairs(searchPath:GetDescendants()) do
					-- Verificar se é uma moeda (diferentes nomes possíveis)
					if object.Name:lower():find("coin") or 
						object.Name:lower():find("cash") or
						object.Name:lower():find("money") or
						(object:IsA("Part") and object.BrickColor.Name == "Bright yellow") or
						(object:IsA("MeshPart") and object.MeshId:find("coin")) then
	
						-- Verificar se tem as propriedades de uma moeda
						if object:IsA("BasePart") and object.CanCollide == false then
							table.insert(coins, object)
						end
					end
				end
			end
		end
	
		-- Busca alternativa por objetos amarelos pequenos (moedas típicas)
		for _, object in pairs(Workspace:GetDescendants()) do
			if object:IsA("BasePart") and 
				object.Size.X < 5 and object.Size.Y < 5 and object.Size.Z < 5 and
				(object.BrickColor.Name == "Bright yellow" or 
					object.BrickColor.Name == "New Yeller" or
					object.Color == Color3.new(1, 1, 0)) and
				object.CanCollide == false then
	
				-- Evitar duplicatas
				local isDuplicate = false
				for _, coin in pairs(coins) do
					if coin == object then
						isDuplicate = true
						break
					end
				end
	
				if not isDuplicate then
					table.insert(coins, object)
				end
			end
		end
	
		return coins
	end
	
	-- Função para calcular distância até uma moeda
	local function getDistanceToCoin(coin)
		if not player.Character or not player.Character:FindFirstChild("HumanoidRootPart") then
			return math.huge
		end
	
		local playerPosition = player.Character.HumanoidRootPart.Position
		local coinPosition = coin.Position
	
		return (playerPosition - coinPosition).Magnitude
	end
	
	-- Função para encontrar a moeda mais próxima
	local function findClosestCoin()
		local coins = findCoins()
		local closestCoin = nil
		local closestDistance = math.huge
	
		for _, coin in pairs(coins) do
			if coin.Parent then -- Verificar se ainda existe
				local distance = getDistanceToCoin(coin)
				if distance < COLLECTION_DISTANCE and distance < closestDistance then
					closestDistance = distance
					closestCoin = coin
				end
			end
		end
	
		return closestCoin, closestDistance
	end
	
	-- Função para teleportar para uma moeda
	local function teleportToCoin(coin)
		if not player.Character or not player.Character:FindFirstChild("HumanoidRootPart") then
			return false
		end
	
		if not coin or not coin.Parent then
			return false
		end
	
		-- Teleportar para a posição da moeda
		local coinPosition = coin.Position
		local teleportPosition = coinPosition + Vector3.new(0, 2, 0) -- Um pouco acima para não bugar
	
		player.Character.HumanoidRootPart.CFrame = CFrame.new(teleportPosition)
	
		return true
	end
	
	-- Função principal de coleta
	local function collectCoins()
		if not coinCollectorEnabled or isCollecting then
			return
		end
	
		isCollecting = true
	
		-- Encontrar moeda mais próxima
		local closestCoin, distance = findClosestCoin()
	
		if closestCoin then
			-- Teleportar para a moeda
			local success = teleportToCoin(closestCoin)
	
			if success then
				coinsCollected = coinsCollected + 1
				print("💰 Coletando moeda " .. coinsCollected .. " - Distância: " .. math.floor(distance) .. " studs")
	
				-- Pequeno delay para garantir que a moeda seja coletada
				wait(COLLECTION_DELAY)
	
				-- Verificar se a moeda ainda existe (foi coletada)
				if not closestCoin.Parent then
					print("✅ Moeda coletada com sucesso!")
				end
			else
				print("❌ Falha ao teleportar para moeda")
			end
		else
			print("🔍 Nenhuma moeda encontrada no raio de " .. COLLECTION_DISTANCE .. " studs")
		end
	
		isCollecting = false
	end
	
	-- Função para ativar coletor de moedas
	local function enableCoinCollector()
		coinCollectorEnabled = true
		coinsCollected = 0
	
		-- Conexão principal do coletor
		collectorConnections.collectLoop = RunService.Heartbeat:Connect(function()
			if coinCollectorEnabled and not isCollecting then
				collectCoins()
			end
		end)
	
		-- Mostrar quantas moedas foram encontradas inicialmente
		local initialCoins = findCoins()
		print("🟢 COLETOR DE MOEDAS ATIVADO!")
		print("💰 Moedas detectadas no mapa: " .. #initialCoins)
		print("🎯 Raio de coleta: " .. COLLECTION_DISTANCE .. " studs")
	end
	
	-- Função para desativar coletor de moedas
	local function disableCoinCollector()
		coinCollectorEnabled = false
		isCollecting = false
	
		-- Desconectar todas as conexões
		for _, connection in pairs(collectorConnections) do
			connection:Disconnect()
		end
		collectorConnections = {}
	
		print("🔴 COLETOR DE MOEDAS DESATIVADO!")
		print("📊 Total de moedas coletadas: " .. coinsCollected)
	end
	
	-- Função principal do botão
	local function toggleCoinCollector()
		if coinCollectorEnabled then
			disableCoinCollector()
		else
			enableCoinCollector()
		end
	end
	
	-- Conectar ao clique do botão
	button.MouseButton1Click:Connect(function()
		toggleCoinCollector()
	end)
	
	print("✅ Coletor de Moedas Automático configurado!")
	print("💰 Clique no botão para iniciar/parar a coleta")
	print("⚙️ Configurações:")
	print("   - Velocidade: " .. COLLECTION_SPEED)
	print("   - Raio: " .. COLLECTION_DISTANCE .. " studs")
	print("   - Delay: " .. COLLECTION_DELAY .. "s")
end
coroutine.wrap(IMBTUMQ_fake_script)()
local function MIAFJS_fake_script() -- TextButton_6.LocalScript 
	local script = Instance.new('LocalScript', TextButton_6)

	-- Script para botão que alterna cor ao clicar
	-- Coloque este script como LocalScript dentro do botão (TextButton ou ImageButton)
	
	local button = script.Parent -- O botão onde o script está
	local originalColor = button.BackgroundColor3 -- Salva a cor original
	local isGreen = false -- Controla se está verde ou não
	
	-- Função que executa quando o botão é clicado
	local function toggleColor()
		if isGreen then
			-- Se está verde, volta para a cor original
			button.BackgroundColor3 = originalColor
			isGreen = false
			print("Botão voltou para cor original")
		else
			-- Se não está verde, fica verde
			button.BackgroundColor3 = Color3.new(0, 1, 0) -- Verde puro
			isGreen = true
			print("Botão ficou verde")
		end
	end
	
	-- Conecta a função ao evento de clique
	button.MouseButton1Click:Connect(toggleColor)
end
coroutine.wrap(MIAFJS_fake_script)()
local function EMPLWU_fake_script() -- TextButton_6.noclip 
	local script = Instance.new('LocalScript', TextButton_6)

	-- Serviços
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	
	-- Variáveis
	local player = Players.LocalPlayer
	local character = player.Character or player.CharacterAdded:Wait()
	local noclipAtivo = false
	
	-- Função para ativar/desativar noclip
	local function toggleNoclip()
		noclipAtivo = not noclipAtivo
	
		if noclipAtivo then
			RunService:BindToRenderStep("Noclip", Enum.RenderPriority.Character.Value, function()
				local char = player.Character
				if char then
					for _, part in pairs(char:GetDescendants()) do
						if part:IsA("BasePart") and part.CanCollide == true then
							part.CanCollide = false
						end
					end
				end
			end)
		else
			RunService:UnbindFromRenderStep("Noclip")
			local char = player.Character
			if char then
				for _, part in pairs(char:GetDescendants()) do
					if part:IsA("BasePart") then
						part.CanCollide = true
					end
				end
			end
		end
	end
	
	-- Conectando ao botão (o script deve estar DENTRO do botão)
	script.Parent.MouseButton1Click:Connect(toggleNoclip)
	
end
coroutine.wrap(EMPLWU_fake_script)()
local function FFPPQS_fake_script() -- TextButton_7.LocalScript 
	local script = Instance.new('LocalScript', TextButton_7)

	-- Script para botão que alterna cor ao clicar
	-- Coloque este script como LocalScript dentro do botão (TextButton ou ImageButton)
	
	local button = script.Parent -- O botão onde o script está
	local originalColor = button.BackgroundColor3 -- Salva a cor original
	local isGreen = false -- Controla se está verde ou não
	
	-- Função que executa quando o botão é clicado
	local function toggleColor()
		if isGreen then
			-- Se está verde, volta para a cor original
			button.BackgroundColor3 = originalColor
			isGreen = false
			print("Botão voltou para cor original")
		else
			-- Se não está verde, fica verde
			button.BackgroundColor3 = Color3.new(0, 1, 0) -- Verde puro
			isGreen = true
			print("Botão ficou verde")
		end
	end
	
	-- Conecta a função ao evento de clique
	button.MouseButton1Click:Connect(toggleColor)
end
coroutine.wrap(FFPPQS_fake_script)()
local function GRTKY_fake_script() -- TextButton_7.fly 
	local script = Instance.new('LocalScript', TextButton_7)

	-- Serviços
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	local UIS = game:GetService("UserInputService")
	
	-- Variáveis principais
	local player = Players.LocalPlayer
	local character = player.Character or player.CharacterAdded:Wait()
	local humanoidRootPart = character:WaitForChild("HumanoidRootPart")
	local camera = workspace.CurrentCamera
	
	-- Fly vars
	local flying = false
	local flySpeed = 50
	local bodyGyro, bodyVelocity
	
	-- Teclas pressionadas
	local keys = {W = false, A = false, S = false, D = false}
	
	-- Função para movimentar durante o Fly
	local function updateMovement()
		if not flying then return end
	
		local moveDir = Vector3.zero
	
		if UIS.KeyboardEnabled then
			if keys.W then moveDir += camera.CFrame.LookVector end
			if keys.S then moveDir -= camera.CFrame.LookVector end
			if keys.A then moveDir -= camera.CFrame.RightVector end
			if keys.D then moveDir += camera.CFrame.RightVector end
		elseif UIS.TouchEnabled then
			moveDir = humanoidRootPart.CFrame:VectorToWorldSpace(UIS:GetDeviceAcceleration())
		end
	
		if moveDir.Magnitude > 0 then
			bodyVelocity.Velocity = moveDir.Unit * flySpeed
		else
			bodyVelocity.Velocity = Vector3.zero
		end
	
		bodyGyro.CFrame = CFrame.new(humanoidRootPart.Position, humanoidRootPart.Position + camera.CFrame.LookVector)
	end
	
	-- Ativar/Desativar Fly
	local function toggleFly()
		flying = not flying
	
		if flying then
			bodyGyro = Instance.new("BodyGyro")
			bodyGyro.P = 9e4
			bodyGyro.MaxTorque = Vector3.new(9e9, 9e9, 9e9)
			bodyGyro.CFrame = humanoidRootPart.CFrame
			bodyGyro.Parent = humanoidRootPart
	
			bodyVelocity = Instance.new("BodyVelocity")
			bodyVelocity.Velocity = Vector3.zero
			bodyVelocity.MaxForce = Vector3.new(9e9, 9e9, 9e9)
			bodyVelocity.Parent = humanoidRootPart
	
			RunService:BindToRenderStep("FlyMovement", Enum.RenderPriority.Input.Value, updateMovement)
		else
			RunService:UnbindFromRenderStep("FlyMovement")
			if bodyGyro then bodyGyro:Destroy() end
			if bodyVelocity then bodyVelocity:Destroy() end
		end
	end
	
	-- Conexões de teclado (PC)
	UIS.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.Keyboard then
			local key = input.KeyCode.Name
			if keys[key] ~= nil then
				keys[key] = true
			end
		end
	end)
	
	UIS.InputEnded:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.Keyboard then
			local key = input.KeyCode.Name
			if keys[key] ~= nil then
				keys[key] = false
			end
		end
	end)
	
	-- Conectar ao botão (este script deve estar DENTRO do botão!)
	script.Parent.MouseButton1Click:Connect(toggleFly)
	
end
coroutine.wrap(GRTKY_fake_script)()
local function MONB_fake_script() -- Frame.LocalScript 
	local script = Instance.new('LocalScript', Frame)

	-- Script de Monitoramento para seu Frame existente
	-- Coloque este script como LocalScript dentro do seu Frame
	
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	local Stats = game:GetService("Stats")
	
	local frame = script.Parent -- Seu frame existente
	local player = Players.LocalPlayer
	
	-- Label do Ping (centralizado)
	local pingLabel = Instance.new("TextLabel")
	pingLabel.Name = "PingLabel"
	pingLabel.Parent = frame
	pingLabel.Size = UDim2.new(1, -10, 0, 30)
	pingLabel.Position = UDim2.new(0, 5, 0, 10)
	pingLabel.BackgroundTransparency = 1
	pingLabel.Text = "🌐 Ping: Carregando..."
	pingLabel.TextColor3 = Color3.new(0, 1, 0)
	pingLabel.TextScaled = true
	pingLabel.TextXAlignment = Enum.TextXAlignment.Center
	pingLabel.Font = Enum.Font.SourceSansBold
	
	-- Label do FPS (centralizado)
	local fpsLabel = Instance.new("TextLabel")
	fpsLabel.Name = "FpsLabel"
	fpsLabel.Parent = frame
	fpsLabel.Size = UDim2.new(1, -10, 0, 30)
	fpsLabel.Position = UDim2.new(0, 5, 0, 50)
	fpsLabel.BackgroundTransparency = 1
	fpsLabel.Text = "⚡ FPS: Carregando..."
	fpsLabel.TextColor3 = Color3.new(0, 1, 0)
	fpsLabel.TextScaled = true
	fpsLabel.TextXAlignment = Enum.TextXAlignment.Center
	fpsLabel.Font = Enum.Font.SourceSansBold
	
	-- Label da Quantidade de Players (centralizado)
	local playersCountLabel = Instance.new("TextLabel")
	playersCountLabel.Name = "PlayersCountLabel"
	playersCountLabel.Parent = frame
	playersCountLabel.Size = UDim2.new(1, -10, 0, 30)
	playersCountLabel.Position = UDim2.new(0, 5, 0, 90)
	playersCountLabel.BackgroundTransparency = 1
	playersCountLabel.Text = "👥 Players: Carregando..."
	playersCountLabel.TextColor3 = Color3.new(0, 1, 0)
	playersCountLabel.TextScaled = true
	playersCountLabel.TextXAlignment = Enum.TextXAlignment.Center
	playersCountLabel.Font = Enum.Font.SourceSansBold
	
	-- Título da Lista de Players (centralizado)
	local playersTitle = Instance.new("TextLabel")
	playersTitle.Name = "PlayersTitle"
	playersTitle.Parent = frame
	playersTitle.Size = UDim2.new(1, -10, 0, 25)
	playersTitle.Position = UDim2.new(0, 5, 0, 130)
	playersTitle.BackgroundTransparency = 1
	playersTitle.Text = "📋 Lista de Jogadores"
	playersTitle.TextColor3 = Color3.new(0, 1, 0)
	playersTitle.TextScaled = true
	playersTitle.TextXAlignment = Enum.TextXAlignment.Center
	playersTitle.Font = Enum.Font.SourceSansBold
	
	-- ScrollingFrame para Lista de Players (se adapta ao frame)
	local playersFrame = Instance.new("ScrollingFrame")
	playersFrame.Name = "PlayersFrame"
	playersFrame.Parent = frame
	playersFrame.Size = UDim2.new(1, -20, 1, -170) -- Se adapta ao tamanho restante do frame
	playersFrame.Position = UDim2.new(0, 10, 0, 160)
	playersFrame.BackgroundTransparency = 1
	playersFrame.BorderSizePixel = 0
	playersFrame.ScrollBarThickness = 8
	playersFrame.ScrollBarImageColor3 = Color3.new(1, 1, 1)
	
	-- Variáveis para FPS
	local frameCount = 0
	local lastTime = tick()
	local currentFPS = 0
	
	-- Função para determinar qualidade do ping
	local function getPingQuality(ping)
		if ping < 50 then
			return "🟢 Excelente", Color3.new(0, 1, 0)
		elseif ping < 100 then
			return "🟡 Boa", Color3.new(1, 1, 0)
		elseif ping < 150 then
			return "🟠 Jogável", Color3.new(1, 0.5, 0)
		elseif ping < 300 then
			return "🔴 Ruim", Color3.new(1, 0, 0)
		else
			return "⚫ Extrema", Color3.new(0.5, 0, 0.5)
		end
	end
	
	-- Função para atualizar lista de players
	local function updatePlayersList()
		-- Limpa lista atual
		for _, child in pairs(playersFrame:GetChildren()) do
			if child:IsA("TextLabel") then
				child:Destroy()
			end
		end
	
		-- Adiciona players atuais
		local playersList = Players:GetPlayers()
		for i, plr in pairs(playersList) do
			local playerLabel = Instance.new("TextLabel")
			playerLabel.Name = "Player_" .. i
			playerLabel.Parent = playersFrame
			playerLabel.Size = UDim2.new(1, -10, 0, 25)
			playerLabel.Position = UDim2.new(0, 5, 0, (i-1) * 30)
			playerLabel.BackgroundTransparency = 1
			playerLabel.Text = "• " .. plr.Name .. (plr == player and " (Você)" or "")
			playerLabel.TextColor3 = Color3.new(0, 1, 0) -- Verde para todos
			playerLabel.TextScaled = true
			playerLabel.TextXAlignment = Enum.TextXAlignment.Center -- Centralizado
			playerLabel.Font = Enum.Font.SourceSans
		end
	
		-- Atualiza tamanho do canvas
		playersFrame.CanvasSize = UDim2.new(0, 0, 0, #playersList * 30)
	end
	
	-- Função principal de atualização
	local function updateStats()
		-- Atualizar FPS
		frameCount = frameCount + 1
		local currentTime = tick()
		if currentTime - lastTime >= 1 then
			currentFPS = math.floor(frameCount / (currentTime - lastTime))
			frameCount = 0
			lastTime = currentTime
		end
	
		-- Atualizar Ping
		local ping = math.floor(player:GetNetworkPing() * 1000)
		local pingQuality, pingColor = getPingQuality(ping)
	
		-- Atualizar Labels (centralizados)
		pingLabel.Text = "🌐 Ping: " .. ping .. "ms (" .. pingQuality .. ")"
		pingLabel.TextColor3 = Color3.new(0, 1, 0) -- Verde sempre
	
		fpsLabel.Text = "⚡ FPS: " .. currentFPS
		fpsLabel.TextColor3 = Color3.new(0, 1, 0) -- Verde sempre
	
		playersCountLabel.Text = "👥 Players: " .. #Players:GetPlayers() .. "/" .. Players.MaxPlayers
	end
	
	-- Eventos
	Players.PlayerAdded:Connect(function(plr)
		updatePlayersList()
		print("🔵 " .. plr.Name .. " entrou no jogo!")
	end)
	
	Players.PlayerRemoving:Connect(function(plr)
		print("🔴 " .. plr.Name .. " saiu do jogo!")
		wait(0.1) -- Pequeno delay para garantir que o player foi removido
		updatePlayersList()
	end)
	
	-- Conexões de atualização
	RunService.Heartbeat:Connect(updateStats)
	
	-- Atualizar lista inicial
	wait(1) -- Espera um pouco para carregar tudo
	updatePlayersList()
	
	print("✅ Monitor do servidor iniciado no seu frame!")
end
coroutine.wrap(MONB_fake_script)()
local function ESIQB_fake_script() -- gatunohub.LocalScript 
	local script = Instance.new('LocalScript', gatunohub)

	local UIS = game:GetService("UserInputService")
	local RunService = game:GetService("RunService")
	
	local frame = script.Parent
	local dragging
	local dragInput
	local dragStart
	local startPos
	
	local function update(input)
		local delta = input.Position - dragStart
		frame.Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y)
	end
	
	frame.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
			dragging = true
			dragStart = input.Position
			startPos = frame.Position
	
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	frame.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			dragInput = input
		end
	end)
	
	RunService.RenderStepped:Connect(function()
		if dragging and dragInput then
			update(dragInput)
		end
	end)
	
end
coroutine.wrap(ESIQB_fake_script)()
local function KXOYQ_fake_script() -- ImageButton.LocalScript 
	local script = Instance.new('LocalScript', ImageButton)

	-- Script para ImageButton controlar um Frame existente
	-- Coloque este script como LocalScript dentro do ImageButton
	
	local imageButton = script.Parent -- ImageButton onde o script está
	
	-- CONFIGURE AQUI: Caminho para seu frame existente
	-- Exemplo: se seu frame está em StarterGui > ScreenGui > MeuFrame
	-- Coloque: local targetFrame = script.Parent.Parent.MeuFrame
	-- Ou se está em PlayerGui: local targetFrame = Players.LocalPlayer.PlayerGui.ScreenGui.MeuFrame
	
	local Players = game:GetService("Players")
	local player = Players.LocalPlayer
	
	-- MUDE ESTA LINHA para o caminho do seu frame:
	local targetFrame = script.Parent.Parent.gatunohub -- <-- COLOQUE O NOME DO SEU FRAME AQUI
	
	-- Variável para controlar se está aberto ou fechado
	local isOpen = true -- Começa como true se seu frame já está visível, ou false se está escondido
	
	-- Função para alternar visibilidade do frame
	local function toggleFrame()
		if targetFrame then
			if isOpen then
				-- Esconder o frame
				targetFrame.Visible = false
				isOpen = false
				print("🔴 Frame escondido!")
			else
				-- Mostrar o frame
				targetFrame.Visible = true
				isOpen = true
				print("🟢 Frame mostrado!")
			end
		else
			warn("❌ Frame não encontrado! Verifique o caminho em 'targetFrame'")
		end
	end
	
	-- Conectar o clique do ImageButton
	imageButton.MouseButton1Click:Connect(function()
		toggleFrame()
	end)
	
	print("✅ ImageButton configurado para controlar frame existente!")
end
coroutine.wrap(KXOYQ_fake_script)()
local function FSVXL_fake_script() -- ImageButton.LocalScript 
	local script = Instance.new('LocalScript', ImageButton)

	local UIS = game:GetService("UserInputService")
	local RunService = game:GetService("RunService")
	
	local button = script.Parent
	local dragging
	local dragInput
	local dragStart
	local startPos
	
	local function update(input)
		local delta = input.Position - dragStart
		button.Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y)
	end
	
	button.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
			dragging = true
			dragStart = input.Position
			startPos = button.Position
	
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	button.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			dragInput = input
		end
	end)
	
	RunService.RenderStepped:Connect(function()
		if dragging and dragInput then
			update(dragInput)
		end
	end)
	
end
coroutine.wrap(FSVXL_fake_script)()
