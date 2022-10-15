local placeId = game.PlaceId
if placeId == 6152116144 then
    ProjectSlayer = true
elseif placeId == 2753915549 or placeId == 4442272183 or placeId == 7449423635 then
    BF = true
elseif placeId == 9790558424 then
    MP = true
end
if ProjectSlayer then
    loadstring(game:HttpGet("https://raw.githubusercontent.com/KUShakung/ProjectSljk/main/README.md"))()
elseif BF then
    loadstring(game:HttpGet("https://raw.githubusercontent.com/KUShakung/..../main/README.md"))()
elseif MP then
    loadstring(game:HttpGet("https://raw.githubusercontent.com/KUShakung/Master-pirate/main/README.md"))()
end
