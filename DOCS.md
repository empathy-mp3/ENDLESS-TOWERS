# ENDLESS TOWERS: a roguelike async

most roguelikes nowadays have a few key features:
- if you die, you start over from the beginning.
- each run is randomly generated.
- there are upgrades that persist between each run, and you grow stronger after each one.

this async has all of those properties!
- death link is on, and if anyone dies, the run (the whole async) will end and we'll have to start over.
- (it's a randomizer so it's normally generated randomly)
- some items will persist between runs, and the async will grow easier each time, as more things are unlocked.

## how does this work?

- once a `death_link` is triggered, we will restart the entire async. (and go onto our next run)
- however, there will be ways to make it much easier (such as additional lives, permanent upgrades, etc.)
- all games that finish will stay finished (so they are a form of permanent upgrades themselves, since they'll release at the start of each run)
- release AUTO, collect AUTO, remaining OFF (you're supposed to release them anyway, so...)
- hint cost: 100% (this can be lowered)
- we'll keep doing runs until everyone has finished!
- there's a shop that's refreshed roughly every day that we can spend our money in. (money and shop items persist between runs)
- there's a vault with several lockers you can find keys to. each locker is numbered, and you can only unlock as many lockers as the *largest amount of keys you're found in one run.* items in lockers stay the same each run, and they stay open between runs.

## rules

- add the phrase `endlesstowers` to your submission so i can search for it
- submit up to 4 worlds !!! including manuals and unsupported !!! (submit the apworlds if manual or unsupported)
- submit all games in one yaml
- list 5 [minor progression]/useful items per world and say what the slot name is for them
- separately, list 3 major progression items per world and say what the slot name is for them
- optionally, list 1 filler item per world that that can be duplicated infinitely (money, pokeballs, one-time helpful items, etc.)
- `death_link` must be enabled, though options that mitigate it or change handling are perfectly acceptable.
- please don't play a roguelike (as ironic as that is). death is inevitable in roguelikes (especially in archipelago), and games where death is inevitable are not suited for this async.
- bring only games that you're fairly confident in doing with few deaths. you don't have to be confident enough to be deathless (since there'll be a lot of ways to make it so much easier). if you're playing celeste 64 with 30 `death_link_amnesty`, be confident enough that you could get every check with only 45 or so deaths.
- i recommend having a lot of random settings! each run should be different from before, should it not?
- plando is fine, but don't plando the items that you list with your game. (i'm plandoing those)
- feel free to priority location and the like, just don't go too crazy with it, alright? feel free to priority location any TOWER related locations, like I'll be doing!
- just play whenever you can. a tracker or check-in of an async like this doesn't really make much sense (since cheesetracker is tied to archipelago rooms)
- just know that this is a bit of a commitment. i have frankly no idea how long this will last.
- if a deathlink is triggered, ping me! if it's the last life, and i'm not available, let everyone know that it's time to stop the async! i'll try to get the next run going quickly!
- if anything is sent to The Shop or The Vault, also ping me!