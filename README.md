repeat wait() until game:IsLoaded()
loadstring(game:HttpGet("https://raw.githubusercontent.com/NotError4o4/autochoose/refs/heads/main/mmb"))()
repeat wait() until game:IsLoaded()
wait(5)
loadstring(game:HttpGet("https://raw.githubusercontent.com/heasenpa/BEll_farm/refs/heads/main/Menu", true))()
repeat wait() until game:IsLoaded()
wait(5)
loadstring(game:HttpGet("https://raw.githubusercontent.com/batusz/main/roblox/__Anti__Afk__Script__", true))()
local targetFPS = 10
while task.wait(2) do
    if setfpscap then
        setfpscap(targetFPS)
    elseif setfpscap2 then
        setfpscap2(targetFPS)
    end
end
