-- Gui to Lua
-- Version: 3.2

-- Instances:

local uimuder = Instance.new("ScreenGui")
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

uimuder.Name = "ui-muder"
uimuder.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
uimuder.DisplayOrder = 100
uimuder.ResetOnSpawn = false

gatunohub.Name = "gatunohub"
gatunohub.Parent = uimuder
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
TextButton.BackgroundColor3 = Color3.fromRGB(217, 0, 4)
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
TextButton_2.BackgroundColor3 = Color3.fromRGB(217, 0, 4)
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
TextButton_3.BackgroundColor3 = Color3.fromRGB(217, 0, 4)
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
TextButton_4.BackgroundColor3 = Color3.fromRGB(217, 0, 4)
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
TextButton_5.BackgroundColor3 = Color3.fromRGB(217, 0, 4)
TextButton_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_5.BorderSizePixel = 0
TextButton_5.Position = UDim2.new(0.0114942528, 0, 0.603448272, 0)
TextButton_5.Size = UDim2.new(0, 138, 0, 29)
TextButton_5.Font = Enum.Font.FredokaOne
TextButton_5.Text = "coletar doce"
TextButton_5.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_5.TextScaled = true
TextButton_5.TextSize = 14.000
TextButton_5.TextWrapped = true

UICorner_8.Parent = TextButton_5

TextButton_6.Parent = gatunohub
TextButton_6.BackgroundColor3 = Color3.fromRGB(217, 0, 4)
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
TextButton_7.BackgroundColor3 = Color3.fromRGB(217, 0, 4)
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

ImageButton.Parent = uimuder
ImageButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ImageButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageButton.BorderSizePixel = 0
ImageButton.Position = UDim2.new(0.0265392791, 0, 0.118219748, 0)
ImageButton.Size = UDim2.new(0, 84, 0, 78)
ImageButton.Image = "rbxassetid://106702991471250"

UICorner_12.Parent = ImageButton

-- Scripts:

local function MYHLH_fake_script() -- TextButton.LocalScript 
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
coroutine.wrap(MYHLH_fake_script)()
local function IOHURFX_fake_script() -- TextButton.esp 
	local script = Instance.new('LocalScript', TextButton)

	-- ESP Script para Murder Mystery 2 - Versão Limpa
	-- Coloque este script como LocalScript dentro do seu botão
	
	local button = script.Parent
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	local Workspace = game:GetService("Workspace")
	
	local player = Players.LocalPlayer
	local espEnabled = false
	local espConnections = {}
	local espLabels = {}
	
	-- Função para criar ESP label limpo
	local function createESPLabel(targetPlayer)
		if not targetPlayer.Character or not targetPlayer.Character:FindFirstChild("Head") then
			return
		end
	
		local head = targetPlayer.Character.Head
	
		-- Criar BillboardGui
		local billboard = Instance.new("BillboardGui")
		billboard.Name = "ESP_" .. targetPlayer.Name
		billboard.Parent = head
		billboard.Size = UDim2.new(0, 150, 0, 30)
		billboard.StudsOffset = Vector3.new(0, 2.5, 0)
		billboard.AlwaysOnTop = true
	
		-- Criar TextLabel sem fundo
		local label = Instance.new("TextLabel")
		label.Parent = billboard
		label.Size = UDim2.new(1, 0, 1, 0)
		label.BackgroundTransparency = 1 -- Totalmente transparente
		label.BorderSizePixel = 0 -- Remove borda
		label.TextScaled = true
		label.Font = Enum.Font.GothamBold
		label.TextStrokeTransparency = 0
		label.TextStrokeColor3 = Color3.new(0, 0, 0) -- Contorno preto para legibilidade
	
		-- Detectar papel do jogador
		local role = "Inocente"
		local textColor = Color3.new(0, 1, 0) -- Verde para inocente
	
		-- Verificar se tem arma (Xerife)
		if targetPlayer.Backpack:FindFirstChild("Gun") or 
			(targetPlayer.Character and targetPlayer.Character:FindFirstChild("Gun")) then
			role = "Xerife"
			textColor = Color3.new(0, 0.7, 1) -- Azul claro
		end
	
		-- Verificar se tem faca (Assassino)
		if targetPlayer.Backpack:FindFirstChild("Knife") or 
			(targetPlayer.Character and targetPlayer.Character:FindFirstChild("Knife")) then
			role = "Assassino"
			textColor = Color3.new(1, 0, 0) -- Vermelho
		end
	
		-- Configurar apenas o nome com a cor do papel
		label.Text = targetPlayer.Name .. " [" .. role .. "]"
		label.TextColor3 = textColor
	
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
	
		-- Verificar Xerife (Gun)
		if targetPlayer.Backpack:FindFirstChild("Gun") or 
			(targetPlayer.Character and targetPlayer.Character:FindFirstChild("Gun")) then
			role = "Xerife"
			textColor = Color3.new(0, 0.7, 1) -- Azul claro
		end
	
		-- Verificar Assassino (Knife)
		if targetPlayer.Backpack:FindFirstChild("Knife") or 
			(targetPlayer.Character and targetPlayer.Character:FindFirstChild("Knife")) then
			role = "Assassino"
			textColor = Color3.new(1, 0, 0) -- Vermelho
		end
	
		-- Atualizar visual
		label.Text = targetPlayer.Name .. " [" .. role .. "]"
		label.TextColor3 = textColor
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
coroutine.wrap(IOHURFX_fake_script)()
local function TTJXIHK_fake_script() -- TextButton_2.LocalScript 
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
coroutine.wrap(TTJXIHK_fake_script)()
local function WIWR_fake_script() -- TextButton_2.esp-arma 
	local script = Instance.new('LocalScript', TextButton_2)

	-- Murder Mystery 2 - ESP de Armas Dropadas
	-- Script para mostrar ESP apenas de armas dropadas no chão (não com jogadores)
	
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	local Workspace = game:GetService("Workspace")
	local Camera = Workspace.CurrentCamera
	
	local player = Players.LocalPlayer
	
	-- Variáveis de controle
	local espEnabled = false
	local espObjects = {}
	local connection
	
	-- Lista de nomes de armas comuns no MM2
	local weaponNames = {
		"knife", "gun", "revolver", "pistol", "blade", "sword", "dagger",
		"classicknife", "classicgun", "sheriff", "murderer", "weapon"
	}
	
	-- Função para verificar se um item é uma arma
	local function isWeapon(item)
		if not item or not item:IsA("Tool") then return false end
	
		local itemName = item.Name:lower()
	
		-- Verifica pelos nomes comuns de armas
		for _, weaponName in pairs(weaponNames) do
			if itemName:find(weaponName) then
				return true
			end
		end
	
		-- Verifica se tem Handle (característico de ferramentas/armas)
		if item:FindFirstChild("Handle") then
			return true
		end
	
		return false
	end
	
	-- Função para verificar se a arma está dropada (não com um jogador)
	local function isWeaponDropped(weapon)
		if not weapon or not weapon.Parent then return false end
	
		-- Verifica se a arma não está na mochila ou equipada em um jogador
		local parent = weapon.Parent
	
		-- Se estiver em um personagem ou mochila de jogador, não está dropada
		for _, player in pairs(Players:GetPlayers()) do
			if player.Character == parent or player:FindFirstChild("Backpack") == parent then
				return false
			end
		end
	
		-- Se chegou até aqui, a arma está dropada no workspace
		return parent == Workspace or parent.Parent == Workspace
	end
	
	-- Função para criar ESP visual
	local function createESP(weapon)
		if not weapon:FindFirstChild("Handle") then return nil end
	
		local handle = weapon:FindFirstChild("Handle")
	
		-- Cria o highlight (contorno)
		local highlight = Instance.new("Highlight")
		highlight.Name = "WeaponESP"
		highlight.Adornee = handle
		highlight.FillColor = Color3.fromRGB(255, 255, 0) -- Amarelo
		highlight.OutlineColor = Color3.fromRGB(255, 215, 0) -- Amarelo mais escuro
		highlight.FillTransparency = 0.5
		highlight.OutlineTransparency = 0
		highlight.Parent = handle
	
		-- Cria BillboardGui para mostrar nome e distância
		local billboardGui = Instance.new("BillboardGui")
		billboardGui.Name = "WeaponNameESP"
		billboardGui.Adornee = handle
		billboardGui.Size = UDim2.new(0, 200, 0, 50)
		billboardGui.StudsOffset = Vector3.new(0, 2, 0)
		billboardGui.AlwaysOnTop = true
		billboardGui.Parent = handle
	
		-- Frame de fundo
		local frame = Instance.new("Frame")
		frame.Size = UDim2.new(1, 0, 1, 0)
		frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		frame.BackgroundTransparency = 0.3
		frame.BorderSizePixel = 0
		frame.Parent = billboardGui
	
		-- Adiciona cantos arredondados
		local corner = Instance.new("UICorner")
		corner.CornerRadius = UDim.new(0, 5)
		corner.Parent = frame
	
		-- Texto do nome da arma
		local nameLabel = Instance.new("TextLabel")
		nameLabel.Size = UDim2.new(1, 0, 0.6, 0)
		nameLabel.Position = UDim2.new(0, 0, 0, 0)
		nameLabel.BackgroundTransparency = 1
		nameLabel.Text = weapon.Name
		nameLabel.TextColor3 = Color3.fromRGB(255, 255, 0) -- Amarelo
		nameLabel.TextScaled = true
		nameLabel.Font = Enum.Font.GothamBold
		nameLabel.Parent = frame
	
		-- Texto da distância
		local distanceLabel = Instance.new("TextLabel")
		distanceLabel.Size = UDim2.new(1, 0, 0.4, 0)
		distanceLabel.Position = UDim2.new(0, 0, 0.6, 0)
		distanceLabel.BackgroundTransparency = 1
		distanceLabel.Text = "0m"
		distanceLabel.TextColor3 = Color3.fromRGB(255, 255, 255) -- Branco
		distanceLabel.TextScaled = true
		distanceLabel.Font = Enum.Font.Gotham
		distanceLabel.Parent = frame
	
		return {
			weapon = weapon,
			highlight = highlight,
			billboard = billboardGui,
			distanceLabel = distanceLabel,
			handle = handle
		}
	end
	
	-- Função para atualizar distâncias
	local function updateDistances()
		if not player.Character or not player.Character:FindFirstChild("HumanoidRootPart") then
			return
		end
	
		local playerPosition = player.Character.HumanoidRootPart.Position
	
		for _, espData in pairs(espObjects) do
			if espData.weapon and espData.weapon.Parent and espData.handle and espData.handle.Parent then
				local distance = (espData.handle.Position - playerPosition).Magnitude
				espData.distanceLabel.Text = math.floor(distance) .. "m"
			end
		end
	end
	
	-- Função para encontrar todas as armas dropadas
	local function findDroppedWeapons()
		local droppedWeapons = {}
	
		-- Procura no Workspace
		for _, obj in pairs(Workspace:GetDescendants()) do
			if isWeapon(obj) and isWeaponDropped(obj) then
				table.insert(droppedWeapons, obj)
			end
		end
	
		return droppedWeapons
	end
	
	-- Função para remover ESP de uma arma específica
	local function removeESP(weapon)
		for i, espData in pairs(espObjects) do
			if espData.weapon == weapon then
				if espData.highlight and espData.highlight.Parent then
					espData.highlight:Destroy()
				end
				if espData.billboard and espData.billboard.Parent then
					espData.billboard:Destroy()
				end
				table.remove(espObjects, i)
				break
			end
		end
	end
	
	-- Função para limpar todos os ESPs
	local function clearAllESP()
		for _, espData in pairs(espObjects) do
			if espData.highlight and espData.highlight.Parent then
				espData.highlight:Destroy()
			end
			if espData.billboard and espData.billboard.Parent then
				espData.billboard:Destroy()
			end
		end
		espObjects = {}
	end
	
	-- Função para atualizar ESPs
	local function updateESP()
		if not espEnabled then return end
	
		-- Remove ESPs de armas que não existem mais ou foram pegas
		for i = #espObjects, 1, -1 do
			local espData = espObjects[i]
			if not espData.weapon or not espData.weapon.Parent or not isWeaponDropped(espData.weapon) then
				removeESP(espData.weapon)
			end
		end
	
		-- Adiciona ESP para novas armas dropadas
		local droppedWeapons = findDroppedWeapons()
		for _, weapon in pairs(droppedWeapons) do
			-- Verifica se já tem ESP
			local hasESP = false
			for _, espData in pairs(espObjects) do
				if espData.weapon == weapon then
					hasESP = true
					break
				end
			end
	
			-- Cria ESP se não tiver
			if not hasESP then
				local espData = createESP(weapon)
				if espData then
					table.insert(espObjects, espData)
					print("ESP adicionado para: " .. weapon.Name)
				end
			end
		end
	
		-- Atualiza distâncias
		updateDistances()
	end
	
	-- Função para ativar ESP
	local function enableESP()
		if espEnabled then return end
	
		espEnabled = true
		print("ESP de armas dropadas ativado!")
	
		-- Atualização contínua
		connection = RunService.Heartbeat:Connect(function()
			updateESP()
		end)
	
		-- Atualização inicial
		updateESP()
	end
	
	-- Função para desativar ESP
	local function disableESP()
		if not espEnabled then return end
	
		espEnabled = false
		print("ESP de armas dropadas desativado!")
	
		-- Para a atualização
		if connection then
			connection:Disconnect()
			connection = nil
		end
	
		-- Remove todos os ESPs
		clearAllESP()
	end
	
	-- Função para alternar ESP
	local function toggleESP()
		if espEnabled then
			disableESP()
		else
			enableESP()
		end
	end
	
	-- Limpa ESPs quando o jogador sai
	Players.PlayerRemoving:Connect(function(leavingPlayer)
		if leavingPlayer == player then
			clearAllESP()
		end
	end)
	
	print("Script ESP de armas dropadas carregado!")
	print("Use toggleESP() para ligar/desligar")
	print("Cor: Amarelo - Mostra apenas armas no chão")
	
	-- Retorna as funções para uso externo
	return {
		toggle = toggleESP,
		enable = enableESP,
		disable = disableESP,
		isEnabled = function() return espEnabled end,
		clear = clearAllESP
	}
end
coroutine.wrap(WIWR_fake_script)()
local function IMDXQ_fake_script() -- TextButton_3.LocalScript 
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
coroutine.wrap(IMDXQ_fake_script)()
local function XOAMVPQ_fake_script() -- TextButton_3.tp-arma 
	local script = Instance.new('LocalScript', TextButton_3)

	-- Murder Mystery 2 - Teleporte para Último com Arma
	-- Script para teleportar até o último jogador que segurou uma arma
	
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	local Workspace = game:GetService("Workspace")
	
	local player = Players.LocalPlayer
	local character = player.Character or player.CharacterAdded:Wait()
	local rootPart = character:WaitForChild("HumanoidRootPart")
	
	-- Variáveis de controle
	local isTracking = false
	local lastWeaponHolder = nil
	local connection
	local weaponConnections = {}
	
	-- Lista de nomes de armas comuns no MM2
	local weaponNames = {
		"Knife", "Gun", "Revolver", "Pistol", "Blade", "Sword", "Dagger",
		"ClassicKnife", "ClassicGun", "Sheriff", "Murderer", "Weapon"
	}
	
	-- Função para verificar se um item é uma arma
	local function isWeapon(item)
		if not item or not item:IsA("Tool") then return false end
	
		local itemName = item.Name:lower()
	
		-- Verifica pelos nomes comuns de armas
		for _, weaponName in pairs(weaponNames) do
			if itemName:find(weaponName:lower()) then
				return true
			end
		end
	
		-- Verifica se tem características de arma (Handle, etc.)
		if item:FindFirstChild("Handle") then
			local handle = item:FindFirstChild("Handle")
			-- Verifica se tem sons típicos de armas
			if handle:FindFirstChildOfClass("Sound") then
				return true
			end
		end
	
		return false
	end
	
	-- Função para monitorar armas de um jogador específico
	local function monitorPlayerWeapons(targetPlayer)
		if not targetPlayer or not targetPlayer.Character then return end
	
		local character = targetPlayer.Character
		local backpack = targetPlayer:FindFirstChild("Backpack")
	
		-- Monitora ferramentas no personagem
		local function checkCharacterTools()
			for _, item in pairs(character:GetChildren()) do
				if isWeapon(item) then
					lastWeaponHolder = targetPlayer
					print(targetPlayer.Name .. " está segurando: " .. item.Name)
				end
			end
		end
	
		-- Monitora ferramentas na mochila quando equipadas
		local function onToolAdded(tool)
			if isWeapon(tool) then
				-- Monitora quando a ferramenta é equipada
				tool.Equipped:Connect(function()
					lastWeaponHolder = targetPlayer
					print(targetPlayer.Name .. " equipou: " .. tool.Name)
				end)
			end
		end
	
		-- Conecta aos eventos
		if character then
			character.ChildAdded:Connect(function(child)
				if isWeapon(child) then
					lastWeaponHolder = targetPlayer
					print(targetPlayer.Name .. " pegou: " .. child.Name)
				end
			end)
	
			-- Verifica ferramentas já existentes
			checkCharacterTools()
		end
	
		if backpack then
			backpack.ChildAdded:Connect(onToolAdded)
	
			-- Verifica ferramentas já existentes na mochila
			for _, tool in pairs(backpack:GetChildren()) do
				onToolAdded(tool)
			end
		end
	end
	
	-- Função para teleportar até o último jogador com arma
	local function teleportToWeaponHolder()
		if not lastWeaponHolder or not lastWeaponHolder.Character then
			print("Nenhum jogador com arma encontrado!")
			return
		end
	
		local targetCharacter = lastWeaponHolder.Character
		local targetRootPart = targetCharacter:FindFirstChild("HumanoidRootPart")
	
		if not targetRootPart then
			print("Não foi possível encontrar o jogador: " .. lastWeaponHolder.Name)
			return
		end
	
		-- Atualiza referência do nosso personagem
		character = player.Character
		if not character then return end
		rootPart = character:FindFirstChild("HumanoidRootPart")
		if not rootPart then return end
	
		-- Teleporta para uma posição próxima ao jogador
		local offset = Vector3.new(
			math.random(-5, 5), -- Posição aleatória ao redor
			2, -- Ligeiramente acima
			math.random(-5, 5)
		)
	
		rootPart.CFrame = targetRootPart.CFrame + offset
		print("Teleportado para: " .. lastWeaponHolder.Name)
	end
	
	-- Função para iniciar o rastreamento
	local function startTracking()
		if isTracking then return end
	
		isTracking = true
		lastWeaponHolder = nil
		print("Iniciando rastreamento de armas...")
	
		-- Monitora todos os jogadores atuais
		for _, targetPlayer in pairs(Players:GetPlayers()) do
			if targetPlayer ~= player then
				monitorPlayerWeapons(targetPlayer)
			end
		end
	
		-- Monitora novos jogadores que entram
		weaponConnections.playerAdded = Players.PlayerAdded:Connect(function(newPlayer)
			if isTracking and newPlayer ~= player then
				-- Espera o personagem carregar
				newPlayer.CharacterAdded:Connect(function()
					wait(1) -- Pequena espera para garantir que tudo carregou
					monitorPlayerWeapons(newPlayer)
				end)
			end
		end)
	
		-- Monitora quando jogadores recriam personagens
		weaponConnections.characterAdded = {}
		for _, targetPlayer in pairs(Players:GetPlayers()) do
			if targetPlayer ~= player then
				weaponConnections.characterAdded[targetPlayer] = targetPlayer.CharacterAdded:Connect(function()
					if isTracking then
						wait(1)
						monitorPlayerWeapons(targetPlayer)
					end
				end)
			end
		end
	
		-- Loop principal para teleporte contínuo (opcional)
		connection = RunService.Heartbeat:Connect(function()
			if isTracking and lastWeaponHolder then
				-- Teleporta automaticamente a cada 2 segundos (ajuste conforme necessário)
				-- Remova esta parte se quiser teleporte manual apenas
				wait(2)
				if isTracking then
					teleportToWeaponHolder()
				end
			end
		end)
	end
	
	-- Função para parar o rastreamento
	local function stopTracking()
		if not isTracking then return end
	
		isTracking = false
		lastWeaponHolder = nil
		print("Parando rastreamento de armas...")
	
		-- Desconecta todos os eventos
		if connection then
			connection:Disconnect()
			connection = nil
		end
	
		for eventName, conn in pairs(weaponConnections) do
			if typeof(conn) == "RBXScriptConnection" then
				conn:Disconnect()
			elseif typeof(conn) == "table" then
				for _, subConn in pairs(conn) do
					if typeof(subConn) == "RBXScriptConnection" then
						subConn:Disconnect()
					end
				end
			end
		end
	
		weaponConnections = {}
	end
	
	-- Função para alternar o rastreamento
	local function toggleTracking()
		if isTracking then
			stopTracking()
		else
			startTracking()
		end
	end
	
	-- Função para teleporte manual
	local function manualTeleport()
		if lastWeaponHolder then
			teleportToWeaponHolder()
		else
			print("Nenhum jogador com arma foi detectado ainda!")
		end
	end
	
	-- Reconecta quando o jogador spawna novamente
	player.CharacterAdded:Connect(function(newCharacter)
		character = newCharacter
		rootPart = character:WaitForChild("HumanoidRootPart")
	end)
	
	print("Script de rastreamento de armas carregado!")
	print("Use toggleTracking() para ligar/desligar o rastreamento")
	print("Use manualTeleport() para teleportar manualmente")
	print("Último jogador com arma: " .. (lastWeaponHolder and lastWeaponHolder.Name or "Nenhum"))
	
	-- Retorna as funções para uso externo
	return {
		toggle = toggleTracking,
		start = startTracking,
		stop = stopTracking,
		teleport = manualTeleport,
		isActive = function() return isTracking end,
		getLastHolder = function() return lastWeaponHolder end
	}
end
coroutine.wrap(XOAMVPQ_fake_script)()
local function GRKZL_fake_script() -- TextButton_4.LocalScript 
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
coroutine.wrap(GRKZL_fake_script)()
local function ZZZGAT_fake_script() -- TextButton_4.aimbot 
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
coroutine.wrap(ZZZGAT_fake_script)()
local function HMKR_fake_script() -- TextButton_5.LocalScript 
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
coroutine.wrap(HMKR_fake_script)()
local function XLUJMEW_fake_script() -- TextButton_5.coletardoce 
	local script = Instance.new('LocalScript', TextButton_5)

	-- Murder Mystery 2 - Coletor de Doces
	-- Script para coletar automaticamente todos os doces do mapa
	
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	local TweenService = game:GetService("TweenService")
	local Workspace = game:GetService("Workspace")
	
	local player = Players.LocalPlayer
	local character = player.Character or player.CharacterAdded:Wait()
	local humanoid = character:WaitForChild("Humanoid")
	local rootPart = character:WaitForChild("HumanoidRootPart")
	
	-- Variáveis de controle
	local isCollecting = false
	local connection
	local currentTween
	
	-- Função para encontrar todos os doces no mapa
	local function findCandies()
		local candies = {}
	
		-- Procura por doces em diferentes locais possíveis
		local possibleParents = {
			Workspace,
			Workspace:FindFirstChild("Normal"),
			Workspace:FindFirstChild("Lobby"),
			Workspace:FindFirstChild("Map")
		}
	
		for _, parent in pairs(possibleParents) do
			if parent then
				-- Procura por objetos que podem ser doces
				for _, obj in pairs(parent:GetDescendants()) do
					if obj:IsA("Part") or obj:IsA("MeshPart") then
						-- Verifica se é um doce pelos nomes comuns
						local name = obj.Name:lower()
						if name:find("candy") or name:find("coin") or name:find("collectible") or 
							name:find("pickup") or obj:FindFirstChild("ClickDetector") then
							-- Verifica se tem ClickDetector (indicativo de item coletável)
							if obj:FindFirstChild("ClickDetector") then
								table.insert(candies, obj)
							end
						end
					end
				end
			end
		end
	
		return candies
	end
	
	-- Função para mover o jogador até um doce
	local function moveToCandy(candy)
		if not candy or not candy.Parent then
			return false
		end
	
		local targetPosition = candy.Position
		local currentPosition = rootPart.Position
	
		-- Calcula a distância
		local distance = (targetPosition - currentPosition).Magnitude
	
		-- Se já está perto o suficiente, coleta diretamente
		if distance < 5 then
			local clickDetector = candy:FindFirstChild("ClickDetector")
			if clickDetector then
				fireclickdetector(clickDetector)
			end
			return true
		end
	
		-- Move o jogador até o doce usando Tween
		local tweenInfo = TweenInfo.new(
			distance / 50, -- Velocidade baseada na distância
			Enum.EasingStyle.Linear,
			Enum.EasingDirection.InOut,
			0,
			false,
			0
		)
	
		currentTween = TweenService:Create(
			rootPart,
			tweenInfo,
			{Position = targetPosition + Vector3.new(0, 2, 0)} -- Slight offset acima do doce
		)
	
		currentTween:Play()
	
		-- Espera o tween terminar
		currentTween.Completed:Wait()
	
		-- Tenta coletar o doce
		wait(0.1)
		local clickDetector = candy:FindFirstChild("ClickDetector")
		if clickDetector and candy.Parent then
			fireclickdetector(clickDetector)
		end
	
		return true
	end
	
	-- Função principal de coleta
	local function collectAllCandies()
		if not isCollecting then return end
	
		-- Atualiza referências do personagem
		character = player.Character
		if not character then return end
	
		humanoid = character:FindFirstChild("Humanoid")
		rootPart = character:FindFirstChild("HumanoidRootPart")
	
		if not humanoid or not rootPart then return end
	
		-- Encontra todos os doces
		local candies = findCandies()
	
		print("Encontrados " .. #candies .. " doces no mapa!")
	
		-- Coleta cada doce
		for i, candy in pairs(candies) do
			if not isCollecting then break end
	
			if candy and candy.Parent then
				print("Coletando doce " .. i .. "/" .. #candies)
				moveToCandy(candy)
				wait(0.5) -- Pequena pausa entre coletas
			end
		end
	
		if isCollecting then
			print("Coleta de doces concluída!")
		end
	end
	
	-- Função para iniciar a coleta
	function startCollecting()
		if isCollecting then return end
	
		isCollecting = true
		print("Iniciando coleta de doces...")
	
		-- Inicia a coleta em uma corrotina
		spawn(function()
			collectAllCandies()
		end)
	end
	
	-- Função para parar a coleta
	function stopCollecting()
		if not isCollecting then return end
	
		isCollecting = false
		print("Parando coleta de doces...")
	
		-- Para o tween atual se existir
		if currentTween then
			currentTween:Cancel()
			currentTween = nil
		end
	end
	
	-- Função para alternar entre ligar/desligar
	function toggleCollecting()
		if isCollecting then
			stopCollecting()
		else
			startCollecting()
		end
	end
	
	-- Reconecta quando o jogador spawna novamente
	player.CharacterAdded:Connect(function(newCharacter)
		character = newCharacter
		humanoid = character:WaitForChild("Humanoid")
		rootPart = character:WaitForChild("HumanoidRootPart")
	end)
	
	print("Script de coleta de doces carregado!")
	print("Use toggleCollecting() para ligar/desligar")
	print("Use startCollecting() para iniciar")
	print("Use stopCollecting() para parar")
	
	-- Retorna as funções para uso externo
	return {
		toggle = toggleCollecting,
		start = startCollecting,
		stop = stopCollecting,
		isActive = function() return isCollecting end
	}
end
coroutine.wrap(XLUJMEW_fake_script)()
local function VLTVZB_fake_script() -- TextButton_6.LocalScript 
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
coroutine.wrap(VLTVZB_fake_script)()
local function UVKTLMS_fake_script() -- TextButton_6.noclip 
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
coroutine.wrap(UVKTLMS_fake_script)()
local function UWMPYFV_fake_script() -- TextButton_7.LocalScript 
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
coroutine.wrap(UWMPYFV_fake_script)()
local function NGIN_fake_script() -- TextButton_7.fly 
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
coroutine.wrap(NGIN_fake_script)()
local function ZQKRPOY_fake_script() -- Frame.LocalScript 
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
coroutine.wrap(ZQKRPOY_fake_script)()
local function JZXJCKW_fake_script() -- gatunohub.LocalScript 
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
coroutine.wrap(JZXJCKW_fake_script)()
local function MGHK_fake_script() -- ImageButton.LocalScript 
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
coroutine.wrap(MGHK_fake_script)()
local function HITZEVU_fake_script() -- ImageButton.LocalScript 
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
coroutine.wrap(HITZEVU_fake_script)()
