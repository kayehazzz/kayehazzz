_G.Team = "Marines"
_G.FpsBoost = true
_G.Webhook = "https://discord.com/api/webhooks/1130840491588603904/6IvNB82iuPx5Qvr-7GCY0jv9UVPSj-Or0jbhQbC6_5s8Y5DvywvKJB8kSgTik9GEniE0"

getgenv().Chatkill = {
    "", "", "",
    ""
}
getgenv().Region_Hop = {
    ["Enable"] = true, -- true/false
    ["Region"] = "Singapore"
    --[[Singapore, United States, Germany, Japan, France, Australia, etc
        - Singapore is the best choice for Asia
    ]]
}
_G.Setting = {
    ["Start Hunting"] = true, -- Bro wtf don't turn it off
    ["Ken Haki"] = true,
    ["WhiteScreen"] = false,
    ["FruitStuff"] = true, -- Auto Buy and Store Fruits
    ["Run"] = 3500, -- As the name, you'll run when the health below ...
    ["MaxHealth"] = 5000,
    ["Time&Bounty Counter"] = true,
    ["Click Delay"] = 0.5,
    ["SkipPlayerWhenBeingLowHealth"] = true,
    ["Check"] = {
        ["V4 Players"] = false,
        ["Portal Users"] = false,
        ["Buddha Users"] = false
    },
    ["Melee"] = {
        ["Enable"] = true,
        ["Z"] = {["Enable"] = true, ["HoldTime"] = 1.5},
        ["X"] = {["Enable"] = true, ["HoldTime"] = 0},
        ["C"] = {["Enable"] = true, ["HoldTime"] = 0}
    },
    ["Fruit"] = {
        ["Enable"] = true,
        ["Z"] = {["Enable"] = true, ["HoldTime"] = 1.5},
        ["X"] = {["Enable"] = true, ["HoldTime"] = 0},
        ["C"] = {["Enable"] = true, ["HoldTime"] = 0},
        ["V"] = {["Enable"] = true, ["HoldTime"] = 0}
    },
    ["Sword"] = {
        ["Enable"] = false,
        ["Z"] = {["Enable"] = true, ["HoldTime"] = 0},
        ["X"] = {["Enable"] = true, ["HoldTime"] = 0},
    },
    ["Gun"] = {
        ["Enable"] = true,
        ["GunMode"] = false,
        ["Z"] = {["Enable"] = true, ["HoldTime"] = 0},
        ["X"] = {["Enable"] = true, ["HoldTime"] = 0},
    }
}

repeat wait() until game:IsLoaded()
