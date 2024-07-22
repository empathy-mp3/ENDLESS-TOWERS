shops have 5 items, and are restocked daily
- one is always a permanent +1 life (1, 3, 5, 7, 9...) 1 stock
- one is halved hint cost (1, 4, 7, 13, 21, 35). the hint costs themselves go: (100, 50, 25, 12.5, 6.25, 3.125, 1.5625) 1 stock
- two are major progression items (4, +1 per finished player) 1 stock each
- two are useful/minor progression items (2, +0.5 per finished player, rounded up) 1 stock
  - should a slot lose all possible stock, it will be replaced with one of the following:
    - temp life refills: (1, +2 cost per additional one purchased per run) 3 stock
    - temp filler item: (1, +1 cost per additional of that particular filler item purchased per run) 3 stock
- reroll is (6, +3 cost per reroll per day)
- send X random traps is (X = 6 + uses) cash is (+1 cash, +0.2 cash per use, rounded down)

# current status

current lives: 1/1
current hint cost: 100%
lockers unlocked: 0
cash total: 0
purchased permanent shop items: 0
finished players: 0

updated (insert relative discord timestamp)

# the shop

should any Cold Hard Cash be sent to The Shop, we may make some purchases!
the shop resets roughly every day (if i have the time to reset it), but we may reroll it to reset it early.
all items are permanent, unless specified otherwise.

current Cold Hard Cash: 0

here are the wares!

`+1 additional life` (1 cost) ~ 1 in stock
`halved hint cost` (1 cost) ~ 1 in stock
`totk.mp3's Ultrahand` (4 cost) ~ 1 in stock
`tunic.mp3's Progressive Sword` (4 cost) ~ 1 in stock
`inscryption.mp3's Conduit Upgrade` (2 cost) ~ 1 in stock
`hollow.mp3's Shaman_Stone` (2 cost) ~ 1 in stock

other impermanent things:

`reroll & restock` (6 cost)
`send 6 random traps` (+1 Cold Hard Cash) ~ 1 in stock

updated (insert relative discord timestamp)

# secret notes on current status of async

current lives: 1/1
current hint cost: 100%
lockers unlocked: 0
cash total: 0
cash acquired this run: 0
[send traps] uses: 0
finished players (0):
- currently none

# submission items

| slot             | shop prog 1          | shop prog 2     | vault prog           | filler                    | trap          |
| ---------------- | -------------------- | --------------- | -------------------- | ------------------------- | ------------- |
| hollow.mp3       | Desolate_Dive        | Lumafly_Lantern | Mothwing_Cloak       | Geo_Chest-Watcher_Knights |               |
| inscryption.mp3  | Hammer               | Explode Bot     | 49er                 |                           | Ring the Bell |
| Deathclaw99SM64  | Climb                | Long Jump       | Wing Cap             |                           |               |
| Deathclaw99Terra | Post-Golem           | Post-Skeletron  | Hardmode             |                           |               |
| Deathclaw99OOT   | Megaton Hammer       | Hover Boots     | Progressive Hookshot | Rupees (200)              |               |
| SylskoTunic      | Pages 24-25 (Prayer) | Hero's Laurels  | Magic Orb            | Money x100                | Fool Trap     |
| SynRogue         | Celestial_Sash       | Water_Mask      | Security_Keycard_B   |                           |               |
| SynRegret        | Progessive_Dots      | Shapers         | Black/White_Squares  | Speed_Boost               |               |

| slot             | vault useful 1     | vault useful 2     | vault useful 3        | shop useful 1        | shop useful 2                  |
| ---------------- | ------------------ | ------------------ | --------------------- | -------------------- | ------------------------------ |
| hollow.mp3       | Quick_Slash        | Hiveblood          | Steady_Body           | Heavy_Blow           | Shaman_Stone                   |
| inscryption.mp3  | Automaton          | Bolthound          | Energy Bot            | Buff Conduit         | Mummy Lord                     |
| Deathclaw99SM64  | Metal Cap          | Power Star         | Power Star            | Power Star           | Power Star                     |
| Deathclaw99Terra | Post-Goblin Army   | Reward: Lava Charm | Reward: Obsidian Rose | Reward: Magic Quiver | Reward: Lavaproof Fishing Line |
| Deathclaw99OOT   | Progressive Wallet | Zora Tunic         | Hylian Shield         | Goron Tunic          | Deku Shield                    |
| SylskoTunic      | Muffling Bell      | Gun                | Magic Wand            | Anklet               | Magic Dagger                   |
| SynRogue         | Talaria_Attachment | Eternal_Coat       | Bombardment           | Eternal_Crown        | Shattered_Orb                  |
| SynRegret        | Functioning_Brain  | Boat               | Puzzle_Skip           | Puzzle_Skip          | Puzzle_Skip                    |

# vault notes

  49er
Quick_Slash
Energy Bot
Bolthound
  Mothwing_Cloak
Hiveblood
Automaton
Steady_Body

# plando example

```
  plando_items:
    - item:
        Desolate_Dive: 1
      location: hollow.mp3's Desolate_Dive
      world: The Shop
      force: true
    - item:
        Lumafly_Lantern: 1
      location: hollow.mp3's Lumafly_Lantern
      world: The Shop
      force: true
    - item:
        Shaman_Stone: 1
      location: hollow.mp3's Shaman_Stone
      world: The Shop
      force: true
    - item:
        Heavy_Blow: 1
      location: hollow.mp3's Heavy_Blow
      world: The Shop
      force: true
    - item:
        Quick_Slash: 1
      location: Locker 2
      world: The Vault
      force: true
    - item:
        Mothwing_Cloak: 1
      location: Locker 5
      world: The Vault
      force: true
    - item:
        Hiveblood: 1
      location: Locker 6
      world: The Vault
      force: true
    - item:
        Steady_Body: 1
      location: Locker 8
      world: The Vault
      force: true
```