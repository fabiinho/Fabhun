-- # FAB HUN

local library = loadstring(game.HttpGet(game, "https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/0x"))()

local w1 = library:Window("Nikkilis Sab stealing") -- Text

w1:Button(
    "Desync gui (Also copy key)",
    function()
local key = "MUTAGEN_discord.gg/6CfpjUhHXd"
setclipboard(key)
loadstring(game:HttpGet("https://raw.githubusercontent.com/kingdos227/-/refs/heads/main/⃝.lua"))()
--DESYNC
    end
) -- Text, Callback

w1:Button(
    "Lemon hub",
    function()
loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/c4281c3937ebd537cb9e860182e41141.lua"))()
--LEMON
    end
) -- Text, Callback

w1:Button(
    "Launch 10m hop",
    function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/rexzysab/stealabrainrot/refs/heads/main/main.lua"))()
--HOP
    end
) -- Text, Callback

w1:Button(
    "UCT hub",
    function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/UCT-hub/main/refs/heads/main/stealabrainrot"))() 
    end
) -- Text, Callback

w1:Button(
    "Nameless Hub",
    function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/ily123950/Vulkan/refs/heads/main/Tr"))()
    end
) -- Text, Callback

w1:Button(
    "Chilli hub",
    function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/tienkhanh1/spicy/main/Chilli.lua"))()
    end
) -- Text, Callback


w1:Button(
    "Destroy GUI",
    function()
        for i, v in pairs(game.CoreGui:GetChildren()) do
            if v:FindFirstChild("Top") then
                v:Destroy()
            end
        end
    end
) -- Text, Callback



w1:Label("Nik simple hub") -- Text


local AkaliNotif = loadstring(game:HttpGet("https://raw.githubusercontent.com/CheatUserzz/RobloxOpenSourceScripts/refs/heads/main/TsNotificactionSource.lua"))();
local Notify = AkaliNotif.Notify;

wait(1);

Notify({
Description = "pegue esse script diretamente do ttk, @fab.dh";
Title = "Script executado";
Duration = 5;
});

