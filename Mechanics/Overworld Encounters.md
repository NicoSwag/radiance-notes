The game will focus a lot on wild encounters. Here is how they currently work:

Each generic Pokemon object event picks from a pool. The pool is made up by a variety of Pokemon (each with a spawning chance) and a level range. In the overworld, interacting with a wild pokemon or being spotted by it (up to two tiles away) starts a battle[^1]. 

Wild Pokemon respawn when they get far away, but the range for the despawning and respawning is further than what it'd be in vanilla[^2]

Wild Pokemon have preset spawn points, but since they move a bit before coming in on the screen it's not super noticeable. I'd argue this is probably the best solution.

Currently, Pokemon might spot the players while they're turning away, and begin a battle while facing the wrong direction. This might be a bug with the vanilla wandering movement type, but it should probably be addressed.

When a repel is active, wild Pokemon don't spot the player, but encounters can still be started by manually interacting with the Pokemon[^3].

The only wild double battles will be scripted.


[^1]: Eventually, I would like to implement encounters starting on touch, as well as Pokemon turning around to randomly try and spot you (like the spinner trainers when you run).

[^2]: Need to make sure this doesn't break anything.

[^3]: Technically it also happens with lures, but there are no lures in the game so tough luck.
