<!---
title: Guidelines
path: /foundation/guidelines
version: 1.0.0
last updated: 18/04/2021
authors:
    - @AmazingSundae <MeltedSundae#4479>
--->

# Guidelines

Below are some important building guidelines and rules to keep in mind while working on your builds.

## Building Rules

Please see the #building-tips-and-rules channel in our [Discord](https://discord.gg/buildtheearth) for more information:

* No ethnocentrism or offensive terminology
* No NSFW content
* If you are unable to finish your plot or wish to change your location, please contact the review committee.
* Do not build interiors of private buildings. Interiors for public buildings such as stores can be built, but it is not necessary, but any iconic landmarks should have interiors done.
	* It is suggested to cover up the inside of windows with concrete, or glowstone or sea lanterns to create a nice affect at night.
* It is not recommended to build cars, but for larger vehicles such as boats or planes, you are free to build as long as it is realistic.
* Do not add any additional or modded blocks. Only use the default blocks in vanilla 1.12.2 Minecraft (or a later version depending on the server you are on)
* Do not build anything that is on the border of your plot and another unclaimed plot.
    * When you submit your world, it will be cut at the borders of your claimed plot. You can either claim both plots, or if the neighboring plot has already been claimed, contact the builder of that plot and arrange a solution. You could also wait until the plot is claimed by someone else, but this relies on you keeping in contact with the project until then.
* Do not rotate buildings (small adjustments are allowed if necessary). The vast majority of buildings are diagonal because they do not point exactly towards a cardinal direction in real life, and therefore should not be rotated to be straight in-game.

**Things you *are* allowed to do but might be unsure about:**

* Change building outlines and roads to look more accurate to real life, as they are not always accurate (*Note that completely inaccurate building outlines should be edited in [OpenStreetMap](#building-outlines)*)
* Change the biome as it is randomly generated (the command is `//setbiome`) 
* Terraform, such as lowering or raising ground, smoothing out terrain, etc. to make it more accurate
* Change or remove trees, grass, caves, terrain blocks (i.e. water)
* Use custom heads and banners

## Prohibited blocks and items

There are certain blocks and items that you are *not* allowed to use in your builds since they will not transfer properly:

* Maps
* Paintings
* Armor stands
* Item frames
* Boats
* Minecarts
* Mobs

While you are allowed to use storage blocks such as shulker boxes and chests, it is discouraged as it does not render at a distance.

## Finding dimensions of buildings  

***1 Minecraft block is equal to 1 meter in real life.*** 

You can measure the dimensions of your building and other objects using [Google Earth Pro](https://www.google.com/earth/versions/#earth-pro). After installing the application on your PC, use the search bar to locate your building (by using the address or coordinates), and then use the ruler tool at the top to measure a building's length or width. In order to measure height, in the ruler menu, click the 3D Path option first before measuring. Check out the GIF below for more help: 

![](https://thumbs.gfycat.com/RingedInconsequentialDachshund-size_restricted.gif)

## Teleporting to a location

As your builds should be in the same location they are in real life, you have to first teleport to the spot of your building in your world. There are two ways you can teleport to real-life locations in-game:

### Using /tpll

Go to [Google Maps](https://www.maps.google.com), find and right click on the exact location you want to teleport to, and click the first option that appears which should show the coordinates for that spot. This will automatically copy the coords for you. Then, go in-game, and use the command `/tpll <coords>`. Check out the GIF below for more help:

![](https://thumbs.gfycat.com/FavoritePeacefulHoneybee-size_restricted.gif)

### Using Terramap

Press M while in-game to open up Terramap, and then find and right click the exact location you want to teleport to. Click the first option that appears which should say `Teleport here`. Check out the GIF below for more help:

![](https://thumbs.gfycat.com/SatisfiedBarrenArcherfish-size_restricted.gif)

## Building outlines

Building outlines are the brick shapes you'll find generated in the ground, and they are outlines of buildings there in real life. They serve as guides for starting new buildings, but they can sometimes be inaccurate. It is recommended to make sure your buildings are in the most accurate position first before relying on the outlines. One common method is by using either [/tpll or Terramap to teleport](#teleporting-to-a-location) to each corner of the building, and then using the `//line` command to connect them, making a custom outline for your build.

However, if you find that your building outlines are almost completely inaccurate, it is recommended to first edit the data on [OpenStreetMap](https://www.openstreetmap.org/) (OSM), a community-made map which provides all the data for our building outlines. To edit the outlines, Head to the website using the link above, create an account, and click `Edit`. It should give you a tutorial on how to properly edit the map. After you submit your edits, wait for about 30-60 minutes fo the changes to be stored. Then go in-game and do `//wand` to get the WorldEdit axe. Right click and left click two opposite corners of the area you edited to select that region, and then use `//regen` to update the outlines.

## References for your build

Before you begin building, you should make sure that you have enough reference material to start. The most popular street level image database is Google Street View. An alternative to this is [Mapillary](https://www.mapillary.com/app/?lat%3D20%26lng%3D0%26z%3D1.5) which has street level coverage of some places that Google Street View does not cover, but the main downside is that it is mostly restricted to large roads. Also, depending on where you are building, you may be able to find YouTube videos showing aerial coverage of the city you are building in, especially tourist attractions. 

However, if you are unable to find enough real life references for your build, using 3D view in Google Earth can also serve as a good reference.  

## Finding the borders of your plot 

To find the borders of your claimed plot in-game, first go to the [website map](https://www.buildtheearth.net/map), and locate your plot. Move the map so that the pointer in the center is on one of the corners, and use the `/tpll` command above the map:

![](https://bte.readthedocs.io/_images/image33.png)

After teleporting to a corner, do [F3] + [G]. This will bring up the chunk borders. Build a pillar on the corner *outside of the chunk* (if you place it on the inside, the border will show up in the world file when you upload it):

![](https://bte.readthedocs.io/_images/image22.png)

Now you can do the above with the other 3 corners, and after you have done so, use the WorldEdit `//line` command to connect the corners, creating a border so you know where your claim ends.
