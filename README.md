#  gp-weedrun designed by GunniP
This is a ps-methrun remake into a weed run it is currently built to give you items from the weed script boii-weed https://tebex.boii.dev/package/4823131 you can change the items through the config.lua if you wish to change case items i recommend downloading https://github.com/iplocator/ps-methrun and configuring the script from there


# Add to qb-core
Items to add to qb-core>shared>items.lua
```
["securitycase"] =        {["name"] = "securitycase",       ["label"] = "Security Case",        ["weight"] = 1000, ["type"] = "item", ["image"] = "securitycase.png", ["unique"] = true, ["useable"] = false, ['shouldClose'] = false, ["combinable"] = nil, ["description"] = "Security case with a timer lock"},
["casekey"] =             {["name"] = "casekey",            ["label"] = "Case Key",             ["weight"] = 0, ["type"] = "item", ["image"] = "key1.png", ["unique"] = true, ["useable"] = false, ['shouldClose'] =
false, ["combinable"] = nil, ["description"] = "Key for a case"},

```


# Dependencies
* Memory Game - https://github.com/NathanERP/memorygame_2
* qb-target - https://github.com/BerkieBb/qb-target
* boii-weed - https://tebex.boii.dev/package/4823131
