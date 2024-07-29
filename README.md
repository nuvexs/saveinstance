# Loadstring

```lua
-- Documentation here https://luau.github.io/UniversalSynSaveInstance/api/SynSaveInstance
local Params = {
 RepoURL = "https://raw.githubusercontent.com/luau/SynSaveInstance/main/",
 SSI = "saveinstance",
}
local synsaveinstance = loadstring(game:HttpGet(Params.RepoURL .. Params.SSI .. ".luau", true), Params.SSI)()
local Options = {} 
synsaveinstance(Options)
```

# saveinstance

Or shortly USSI, a project aimed at resurrecting saveinstance function from Synapse X Source 2019 & Other Executor Source leaks :trollface:.
Reason: Many Executors fail miserably at providing good user experience when it comes to tinkering with saving instances.
