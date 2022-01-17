# mc-worth
hosting for the Minecraft worth.yml file usable with EssentialsX plugin and others
~editing is done via a [google doc sheet](https://docs.google.com/spreadsheets/d/1tmtnwctj-IX8_PXGhj87w_ewZYvSXB9fF8CAqP4JElA/edit?usp=sharing) for the use of formulas.~

I am now using LibreOffice to edit the formulas as Google likes to mess things up.  The .ods file is part of the repo and uploaded as I make commits.  the google sheet is still there if you want to view or copy it.

License: (short version) Do what you want with it, a large part of the content is not mine anyway.  Share what you add, pull requests will be accepted most of the time.  Fork it if you want, but please submit pull requests if you add any significant changes.

Please note this is and will always be a work in progress, this list should be used as a "base" for your server economy.  Note that server economies change over time and modifications to this list by you should be performed as needed.

create issues for requested updates please

comments welcome

I have decided to use the value of coal / 8 for any crafting recipe that requires smelting, to simply the process.

The point of this repo is to retain a publicly available listibng of values for in game minecraft items, usable by plugins and mods for Economy systems in Minecraft.


- I do not intend on making items insanely high priced
- I do intend to build crafted item prices based on the sum of their parts
- I am using formulas to determine pricing based off crafting recipes and tracking any arbitrarily valued items in an issue.
- The base of this list is someone else's 1.15 list I borrowed 2 years ago and do not have the name of the original owner, I found it on reddit, it has lots of bad values, I have not fixed all of them. (example I just noticed, birch log = 10, birch plank = 3.3, birch slab = 1.3, stick = 0.5, and a wooden shovel = 2.0... definitely needs fixing)
- I am starting with this list as I have already added a little over half of the 1.16 items
- The list is alphabetically sorted, yes categories would be nice; however as minecraft seems to have been adjusting item names over the last year and some change, keeping it alphabetical keeps most of the related items together anyway, and makes it easier to find a single item without guessing how someone else decided to categorize it (besides searching ;)


I have discovered 2 very helpful repo's for maintaining this repo moving forward
1. [Redwolf Program's minecraft-lists](https://github.com/RedwolfPrograms/minecraft-lists)
   1. he is extracting the items and blocks out of the jar file, YAY!
1. [Pokechu22's Burger](https://github.com/pokechu22/Burger)
   1. he has built a script to pull data out of the jar file, YAY!

using Redwolf's repo will help me update faster as I can import the item & block lists then filter dupes out to start adding values almost as soon as the jar is available from Mojang.
