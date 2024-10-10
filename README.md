getgenv().config = {
    ["Team"] = "Pirates", -- Pirates/Marines
    ["FPS Boost"] = false,
    ["LocalPlayer"] = {
        ["Ken Haki"] = true,
        ["Invisible"] = true,
        ["Click Delay"] = 0.1,
        ["Panic Mode"] = { -- automatically runs when health below "Run" and returns to kill player when above "Max"
            ["Skip Player"] = true, -- skip to the next player then ^
            ["Run"] = 3500,
            ["Max"] = 5000,
        }
    },

    ["settings"] = {
        ["Cam Farm"] = true,
        ["White Screen"] = false,
        ["Region_Hop"] = {
            ["Enabled"] = true, -- true/false
            ["Value"] = "Singapore"
            --[[Singapore, United States, Germany, Japan, France, Australia, etc
                - Singapore, Oregon are the best choices for Asia
            ]]
        },
        ["Webhook"] = {
            ["Enabled"] = true,
            ["URL"] = {
                [""] = "", -- Your webhook url
            }
        },
        ["Chatkill"] = {
            ["Enabled"] = false,
            ["Text"] = {
                ""
            }
        },
        ["FPS Locker"] = {
            ["Enabled"] = false,
            ["Value"] = 45
        },
        ["Bounty Lock"] = {
            ["Enabled"] = false, -- Auto kick if 30m
            ["Value"] = 30000000
        },
        ["Ignore"] = { -- will ignore hunting type of users below
            ["Fruit"] = {["Enabled"] = true,
                ["List"] = {
                    "Portal-Portal",
                    "Kitsune-Kitsune"
                }
            },
            ['V4'] = {["Enabled"] = true,
                ["List"] = {
                    -- [Fishman, Mink, Cyborg, Ghoul, Skypiea]
                    "Skypiea"
                }
            },
        },
        ["Stats"] = {
            ["Auto Reset Stat If Doesnt Match"] = false,
            ["Points"] = "Sword" --[[
                Demon Fruit, Sword, Gun
            ]]
        },
    },

    ["Skills"] = {
        ["Melee"] = {
            ["Time"] = 2.5,
            ["Enabled"] = true,
            ["Z"] = {["Enabled"] = true, ["HoldTime"] = 1},
            ["X"] = {["Enabled"] = true, ["HoldTime"] = 0},
            ["C"] = {["Enabled"] = true, ["HoldTime"] = 0}
        },
        ["Fruit"] = {
            ["Time"] = 1.75,
            ["Enabled"] = true,
            ["Z"] = {["Enabled"] = true, ["HoldTime"] = 0},
            ["X"] = {["Enabled"] = true, ["HoldTime"] = 0},
            ["C"] = {["Enabled"] = true, ["HoldTime"] = 0},
            ["V"] = {["Enabled"] = true, ["HoldTime"] = 0},
            ["F"] = {["Enabled"] = true, ["HoldTime"] = 0}
        },
        ["Sword"] = {
            ["Time"] = 1.75,
            ["Enabled"] = false,
            ["Z"] = {["Enabled"] = true, ["HoldTime"] = 0},
            ["X"] = {["Enabled"] = true, ["HoldTime"] = 0},
        },
        ["Gun"] = {
            ["Time"] = 1,
            ["Enabled"] = true,
            ["GunMode"] = false,
            ["Z"] = {["Enabled"] = true, ["HoldTime"] = 0},
            ["X"] = {["Enabled"] = true, ["HoldTime"] = 0},
        }
    }
};
