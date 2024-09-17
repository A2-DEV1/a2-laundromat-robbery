# a2-laundromat-robbery

# Requires 

- [qb-core](https://github.com/qbcore-framework/qb-core)
- [interact](https://github.com/darktrovx/interact)
- [ox_lib](https://github.com/overextended/ox_lib)


# Installation

drop this [a2-laundromat-robbery] folder in your server files 

Paste This code in interact\shared\settings

```lua
CreateThread(function()
        exports.interact:AddInteraction({
            coords = vector3(161.99, -1481.0, 29.14),
            distance = 4, -- optional
            interactDst = 2, -- optional
            options = {
                {
                    type = "client",
                    event = 'a2-script:client:attemptUnlockDoors',
                    label = "Hacking",
                    params = {},
                },
            }
        })
    end),
--vector3(163.95, -1497.94, 29.24)
    CreateThread(function()
        exports.interact:AddInteraction({
            coords = vector3(165.8, -1497.1, 29.58),
            distance = 2, -- optional
            interactDst = 1, -- optional
            options = {
                {
                    type = "client",
                    event = 'a2-script:client:attemptUnlockDoors222',
                    label = "Hacking",
                    params = {},
                },
            }
        })
    end),

    CreateThread(function()
        exports.interact:AddInteraction({
            coords = vector3(164.07, -1498.15, 29.24),
            distance = 2, -- optional
            interactDst = 1, -- optional
            options = {
                {
                    type = "client",
                    event = 'a2-laundromat:server:roblaundromat1234',
                    label = "Open The Door",
                    params = {},
                },
            }
        })
    end),

    CreateThread(function()
        exports.interact:AddInteraction({
            coords = vector3(171.11, -1501.82, 29.27),
            distance = 4, -- optional
            interactDst = 1, -- optional
            options = {
                {
                    type = "client",
                    event = 'a2-laundromat:server:roblaundromat',
                    label = "Rob",
                    params = {},
                },
            }
        })
    end),

    CreateThread(function()
        exports.interact:AddInteraction({
            coords = vector3(171.62, -1501.36, 29.27),
            distance = 4, -- optional
            interactDst = 1, -- optional
            options = {
                {
                    type = "client",
                    event = 'a2-laundromat:server:roblaundromat1',
                    label = "Rob",
                    params = {},
                },
            }
        })
    end),

    CreateThread(function()
        exports.interact:AddInteraction({
            coords = vector3(172.11, -1500.84, 29.27),
            distance = 4, -- optional
            interactDst = 1, -- optional
            options = {
                {
                    type = "client",
                    event = 'a2-laundromat:server:roblaundromat2',
                    label = "Rob",
                    params = {},
                },
            }
        })
    end),

    CreateThread(function()
        exports.interact:AddInteraction({
            coords = vector3(172.64, -1500.36, 29.28),
            distance = 4, -- optional
            interactDst = 1, -- optional
            options = {
                {
                    type = "client",
                    event = 'a2-laundromat:server:roblaundromat3',
                    label = "Rob",
                    params = {},
                },
            }
        })
    end),

    CreateThread(function()
        exports.interact:AddInteraction({
            coords = vector3(173.18, -1499.89, 29.28),
            distance = 4, -- optional
            interactDst = 1, -- optional
            options = {
                {
                    type = "client",
                    event = 'a2-laundromat:server:roblaundromat4',
                    label = "Rob",
                    params = {},
                },
            }
        })
    end),

    CreateThread(function()
        exports.interact:AddInteraction({
            coords = vector3(173.75, -1499.27, 29.28),
            distance = 4, -- optional
            interactDst = 1, -- optional
            options = {
                {
                    type = "client",
                    event = 'a2-laundromat:server:roblaundromat5',
                    label = "Rob",
                    params = {},
                },
            }
        })
    end),

    CreateThread(function()
        exports.interact:AddInteraction({
            coords = vector3(171.82, -1502.56, 29.26),
            distance = 4, -- optional
            interactDst = 1, -- optional
            options = {
                {
                    type = "client",
                    event = 'a2-laundromat:server:roblaundromat6',
                    label = "Rob",
                    params = {},
                },
            }
        })
    end),

    CreateThread(function()
        exports.interact:AddInteraction({
            coords = vector3(172.31, -1502.06, 29.26),
            distance = 4, -- optional
            interactDst = 1, -- optional
            options = {
                {
                    type = "client",
                    event = 'a2-laundromat:server:roblaundromat7',
                    label = "Rob",
                    params = {},
                },
            }
        })
    end),

    CreateThread(function()
        exports.interact:AddInteraction({
            coords = vector3(172.95, -1501.5, 29.26),
            distance = 4, -- optional
            interactDst = 1, -- optional
            options = {
                {
                    type = "client",
                    event = 'a2-laundromat:server:roblaundromat8',
                    label = "Rob",
                    params = {},
                },
            }
        })
    end),

    CreateThread(function()
        exports.interact:AddInteraction({
            coords = vector3(173.37, -1500.93, 29.27),
            distance = 4, -- optional
            interactDst = 1, -- optional
            options = {
                {
                    type = "client",
                    event = 'a2-laundromat:server:roblaundromat9',
                    label = "Rob",
                    params = {},
                },
            }
        })
    end),

    CreateThread(function()
        exports.interact:AddInteraction({
            coords = vector3(173.97, -1500.47, 29.27),
            distance = 4, -- optional
            interactDst = 1, -- optional
            options = {
                {
                    type = "client",
                    event = 'a2-laundromat:server:roblaundromat10',
                    label = "Rob",
                    params = {},
                },
            }
        })
    end),

    CreateThread(function()
        exports.interact:AddInteraction({
            coords = vector3(174.57, -1499.95, 29.27),
            distance = 4, -- optional
            interactDst = 1, -- optional
            options = {
                {
                    type = "client",
                    event = 'a2-laundromat:server:roblaundromat11',
                    label = "Rob",
                    params = {},
                },
            }
        })
    end),

    CreateThread(function()
        exports.interact:AddInteraction({
            coords = vector3(161.71, -1491.04, 28.80),
            distance = 7, -- optional
            interactDst = 1, -- optional
            options = {
                {
                    type = "client",
                    event = 'a2-laundromat:server:roblaundromat13',
                    label = "Rob Drawer",
                    params = {},
                },
            }
        })
    end),
```

# Items

**Add this item in your shared items**


``` lua 

---laundromat
['moneyroll'] 		 				 = {['name'] = 'moneyroll', 						['label'] = 'Cash Roll', 					["weight"] = 1, 	    ['type'] = 'item', 		['image'] = 'money-roll.png', 				['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Cash Roll'},
['coin'] 		 				 = {['name'] = 'coin', 						['label'] = 'Coin', 					["weight"] = 1, 	    ['type'] = 'item', 		['image'] = 'coin.png', 				['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Coin'},
["laptop"] 		 	 	 	 = {["name"] = "laptop",           			["label"] = "Laptop",	 		["weight"] = 100, 		["type"] = "item", 		["image"] = "laptop.png", 			["unique"] = false, 	["useable"] = false, 	["shouldClose"] = false,   ["combinable"] = nil, ["description"] = ""},

```


# Images

**add this Images in your-inventory\html\images**


![coin](https://github.com/user-attachments/assets/27fa4c70-161e-4050-970f-b5330f384223)
![laptop](https://github.com/user-attachments/assets/75b0cf7a-9e0a-44ee-81f5-8dad9a600e30)
![money-roll](https://github.com/user-attachments/assets/bffdbed9-3475-4323-8c3e-e3cf49c6f54e)
