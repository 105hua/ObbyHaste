**NOTE:** This datapack is now *deprecated*, meaning that it will no longer receive updates. This pack is also unstable and may not work as intended in some scenarios, I do not recommend that you use it.

# ObbyHaste

ObbyHaste is a simple datapack that I have made for a Technical Server that I am currently hosting.
The datapack serves a single purpose, to make mining Obsidian in the End a lot less painful,
especially when it comes to removing the Obsidian Pillars.

## How does it work?

The datapack works by checking to see if the player is looking at Obsidian in the End Dimension on
each tick. If a given player meets these requirements, they are given one second of Haste 75, which,
in turn, makes mining Obsidian a lot easier. As the player is only given one second of the effect,
there is an extremely small time frame in which the effect can be used for another purpose, as it will
stop refreshing when the player looks away.

## Usage

Please bear in mind that the datapack uses Pack Format 6, as ObbyHaste was built to work on version
1.16.5 of the game. Feel free to change this by researching the relevant Pack Format for your
Minecraft version and modifying the `pack.mcmeta` file accordingly.

To use the datapack, simply download this repository and drop the obbyhaste folder into your chosen
worlds datapack folder and that should be it! It is also worth mentioning that you may not see the
particles and the effects status as you would with a normal Potion/Effect. This is intentional
behaviour and should not effect the packs functionality :)

## Known Issues

I am aware of an issue with the datapack in which the effect will not be applied unless the Obsidian
is more or less directly in front of the players view, most notably, looking straight up/down at the
aforementioned. I am aware of this issue and I will be working to resolve this issue as soon as time
allows me :)
