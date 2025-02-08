local UltimateTrollingGUI = Instance.new("ScreenGui")
local MainFrame = Instance.new("Frame")
local Title = Instance.new("TextLabel")
local FirstRelease = Instance.new("TextLabel")
local Close = Instance.new("TextButton")
local ScriptsAndStuff = Instance.new("Frame")
local WIP1 = Instance.new("TextButton")
local WIP2 = Instance.new("TextButton")
local R6 = Instance.new("TextButton")
local RS = Instance.new("TextButton")
local Username = Instance.new("TextBox")
local SearchCMD = Instance.new("TextBox")
local Development = Instance.new("TextLabel")
local Filter = Instance.new("TextButton")
local OpenFrame = Instance.new("Frame")
local Open = Instance.new("TextButton")
--Properties:
UltimateTrollingGUI.Name = "UltimateTrollingGUI"
UltimateTrollingGUI.Parent = game.CoreGui
UltimateTrollingGUI.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
 
MainFrame.Name = "MainFrame"
MainFrame.Parent = UltimateTrollingGUI
MainFrame.BackgroundColor3 = Color3.new(0.105882, 0.156863, 0.211765)
MainFrame.Active = true
MainFrame.Position = UDim2.new(0.1282617, 0, 0.0969153345, 0)
MainFrame.Size = UDim2.new(0, 276, 0, 395)
MainFrame.Visible = false
MainFrame.Style = Enum.FrameStyle.RobloxRound
MainFrame.Draggable = true
 
Title.Name = "Title"
Title.Parent = MainFrame
Title.BackgroundColor3 = Color3.new(1, 1, 1)
Title.BackgroundTransparency = 1
Title.Position = UDim2.new(0.085660629, 0, -0.0189382844, 0)
Title.Size = UDim2.new(0, 210, 0, 36)
Title.Font = Enum.Font.SourceSans
Title.Text = "Ultimate Trolling GUI"
Title.TextColor3 = Color3.new(1, 1, 1)
Title.TextSize = 22
Title.TextWrapped = true
 
FirstRelease.Name = "FirstRelease"
FirstRelease.Parent = MainFrame
FirstRelease.BackgroundColor3 = Color3.new(1, 1, 1)
FirstRelease.BackgroundTransparency = 1
FirstRelease.Position = UDim2.new(0.0911550075, 0, 0.0327278525, 0)
FirstRelease.Size = UDim2.new(0, 210, 0, 36)
FirstRelease.Font = Enum.Font.SourceSans
FirstRelease.Text = "(First release, will fix bugs soon!)"
FirstRelease.TextColor3 = Color3.new(1, 1, 1)
FirstRelease.TextSize = 11
FirstRelease.TextWrapped = true
 
Close.Name = "Close"
Close.Parent = MainFrame
Close.BackgroundColor3 = Color3.new(1, 0.0941177, 0)
Close.Position = UDim2.new(0.907788217, 0, -0.0227203351, 0)
Close.Size = UDim2.new(0, 31, 0, 31)
Close.Font = Enum.Font.SourceSans
Close.Text = "X"
Close.TextColor3 = Color3.new(1, 1, 1)
Close.TextSize = 14
Close.MouseButton1Click:connect(function()
	MainFrame.Visible = false
	wait(2)
	OpenFrame.Visible = true
end)
 
ScriptsAndStuff.Name = "ScriptsAndStuff"
ScriptsAndStuff.Parent = MainFrame
ScriptsAndStuff.BackgroundColor3 = Color3.new(0.129412, 0.203922, 0.278431)
ScriptsAndStuff.Position = UDim2.new(0.0156374946, 0, 0.539795578, 0)
ScriptsAndStuff.Size = UDim2.new(0, 251, 0, 176)
 
WIP1.Name = "WIP1"
WIP1.Parent = MainFrame
WIP1.BackgroundColor3 = Color3.new(0.141176, 0.211765, 0.286275)
WIP1.Position = UDim2.new(-0.00724637602, 0, 0.129919708, 0)
WIP1.Size = UDim2.new(0, 82, 0, 31)
WIP1.Font = Enum.Font.SourceSans
WIP1.Text = "WIP"
WIP1.TextColor3 = Color3.new(1, 1, 1)
WIP1.TextSize = 14
 
WIP2.Name = "WIP2"
WIP2.Parent = MainFrame
WIP2.BackgroundColor3 = Color3.new(0.141176, 0.211765, 0.286275)
WIP2.Position = UDim2.new(-0.00724637602, 0, 0.250262082, 0)
WIP2.Size = UDim2.new(0, 82, 0, 31)
WIP2.Font = Enum.Font.SourceSans
WIP2.Text = "WIP"
WIP2.TextColor3 = Color3.new(1, 1, 1)
WIP2.TextSize = 14
 
R6.Name = "R6"
R6.Parent = MainFrame
R6.BackgroundColor3 = Color3.new(0.141176, 0.211765, 0.286275)
R6.Position = UDim2.new(0.373713493, 0, 0.131895497, 0)
R6.Size = UDim2.new(0, 24, 0, 31)
R6.Font = Enum.Font.SourceSans
R6.Text = "R6"
R6.TextColor3 = Color3.new(1, 1, 1)
R6.TextSize = 14
 
RS.Name = "RS"
RS.Parent = MainFrame
RS.BackgroundColor3 = Color3.new(0.141176, 0.211765, 0.286275)
RS.Position = UDim2.new(0.373713493, 0, 0.249547601, 0)
RS.Size = UDim2.new(0, 24, 0, 31)
RS.Font = Enum.Font.SourceSans
RS.Text = "RS"
RS.TextColor3 = Color3.new(1, 1, 1)
RS.TextSize = 14
 
Username.Name = "Username"
Username.Parent = MainFrame
Username.BackgroundColor3 = Color3.new(1, 1, 1)
Username.Position = UDim2.new(0.520478904, 0, 0.132788524, 0)
Username.Size = UDim2.new(0, 122, 0, 32)
Username.Font = Enum.Font.SourceSans
Username.Text = "Username"
Username.TextColor3 = Color3.new(0, 0, 0)
Username.TextSize = 17
 
SearchCMD.Name = "SearchCMD"
SearchCMD.Parent = MainFrame
SearchCMD.BackgroundColor3 = Color3.new(1, 1, 1)
SearchCMD.Position = UDim2.new(0.520478904, 0, 0.247909009, 0)
SearchCMD.Size = UDim2.new(0, 122, 0, 32)
SearchCMD.Font = Enum.Font.SourceSans
SearchCMD.Text = "Search CMD"
SearchCMD.TextColor3 = Color3.new(0, 0, 0)
SearchCMD.TextSize = 17
 
Development.Name = "Development"
Development.Parent = MainFrame
Development.BackgroundColor3 = Color3.new(0, 0.764706, 0.0117647)
Development.Position = UDim2.new(0, -2, 0, 133)
Development.Size = UDim2.new(0, 258, 0, 35)
Development.Font = Enum.Font.SourceSans
Development.Text = "Development by Drahazar and Pristh"
Development.TextColor3 = Color3.new(0.901961, 0.901961, 0.901961)
Development.TextSize = 18
 
Filter.Name = "Filter"
Filter.Parent = MainFrame
Filter.BackgroundColor3 = Color3.new(0.141176, 0.211765, 0.286275)
Filter.Position = UDim2.new(0.00392001681, 0, 0.442813635, 0)
Filter.Size = UDim2.new(0, 255, 0, 29)
Filter.Font = Enum.Font.SourceSans
Filter.Text = "Filter: Commands"
Filter.TextColor3 = Color3.new(1, 1, 1)
Filter.TextSize = 20
 
OpenFrame.Name = "OpenFrame"
OpenFrame.Parent = UltimateTrollingGUI
OpenFrame.BackgroundColor3 = Color3.new(1, 1, 1)
OpenFrame.Position = UDim2.new(0, 0, 0.784090698, 0)
OpenFrame.Size = UDim2.new(0, 153, 0, 33)
 
Open.Name = "Open"
Open.Parent = OpenFrame
Open.BackgroundColor3 = Color3.new(1, 1, 1)
Open.Size = UDim2.new(0, 153, 0, 33)
Open.Font = Enum.Font.SourceSans
Open.Text = "Purchase Ultimate Trolling GUI"
Open.TextColor3 = Color3.new(0, 0, 0)
Open.TextSize = 14
Open.MouseButton1Click:connect(function()
	OpenFrame.Visible = false
	wait(2)
	MainFrame.Visible = true
end)
