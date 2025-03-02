# Fluent
好用

## 引导库
```lua
local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()
local SaveManager = loadstring(game:HttpGet("https://raw.githubusercontent.com/dawid-scripts/Fluent/master/Addons/SaveManager.lua"))()
local InterfaceManager = loadstring(game:HttpGet("https://raw.githubusercontent.com/dawid-scripts/Fluent/master/Addons/InterfaceManager.lua"))()```

## 创建窗口
```lua
local Window = Fluent:CreateWindow({
    Title = "Fluent " .. Fluent.Version,--标题
    SubTitle = "by dawid",--小标题
    TabWidth = 160,
    Size = UDim2.fromOffset(580, 460),--窗口大小
    Acrylic = true, -- true=模糊 false=不模糊
    Theme = "Dark",窗口颜色
    MinimizeKey = Enum.KeyCode.LeftControl -- 当没有最小化键绑定时使用```

## 
