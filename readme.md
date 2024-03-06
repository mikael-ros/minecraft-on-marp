# Minecraft on Marp!
A yanky theme that uses Minecraft assets to create an accurate Minecraft experience.

Originally made for a Minecraft presentation I held in a networking course, where I measured the network usage of Minecraft. See ![](this repo) for some more tools I used to make graphs!

## Preview
### Main menu
### Other slides

## How to use
> Note! this theme will likely not work very well together with others.

### Template
1. Download this GitHub repository, either by downloading the latest release .zip or cloning.
2. Download/extract the necessary third-party assets. See "Mining for assets"
3. Put them by the project root, according to the patterns defined in the CSS file, unless you wish to change it:
  - assets/fonts
  - assets/texturepack <-- put textures here!
  - assets/images
4. Follow the guide ![](here) to assign the theme, or look at the configurations I left in the .vscode folder
### Into existing project
1. Download this GitHub repository, either by downloading the latest release .zip or cloning.
2. Put the files where you'd like them, but make the necessary modifications to integrate it.
3. Download/extract the necessary third-party assets. See "Mining for assets"
4. Put them by the project root, according to the patterns defined in the CSS file, unless you wish to change it:
  - assets/fonts
  - assets/texturepack <-- put textures here!
  - assets/images
5. Follow the guide ![](here) to assign the theme, or look at the configurations I left in the .vscode folder

### Main menu
The main menu is defined inline, by importing the main-menu.css file. See the code snippet in example-menu.md to see how you should implement it.

With knowledge of CSS, you can modify these to add more buttons.

The menu is implemented by forcing and choking list elements to behave like buttons. This is not only cruel, but extremely yank. Feel free to provide a better solution if you have one.

For credits sake, I have to mention that this menu was originally based on ![](this codesnippet) by ![](AUTHOR), but has since been heavily modified (and updated to look like more recent versions of Minecraft).

## Mining for assets
### Font
By default, this theme uses Minecraft Seven for the font (which you can ![](find here)) 

### Resource/texture pack
This stylesheet sources almost all graphics from a resource pack.

To use the default resource pack, follow ![](this guide), which explains how to "mine" it out of the Minecraft client. Otherwise you can use any resource pack you like, just unzip it and drop it in the "assets/texturepack" folder. The way things are configured, any resource pack can act as a drop -in replacement, owing to the static nature of resource pack file structures.

### Borders
You'll have to make these yourself, but the process is fairly simple:
1. In your favorite design tool*, create a square canvas. The size of it is dictated by your needs, but a basic border would be 3 x <size of texture> px in both height and width.
2. Slap your textures in there, and tile them to fill the canvas. In GIMP you can do this with the paint bucket, using the image fill tool (![](see this guide))
3. Export it as png, and put it where you'd like. Preferably in "assets/borders". See examples for how to use.

(examples)

### Panorama
The menu uses a stitched together set of screenshots, laid out like the way the game does it  (![](see this wiki article)). This image is provided for you, since it's nothing more than some screenshots. If you wish to create your own, use my image as reference together with ![](this video).

(example)

### Copyright
For obvious reasons, I won't provide or host these resources myself, since they're protected under copyright law. 

Similarly, **I would strongly advise you not to use this theme for a presentation from which you will monetarily gain** - unless you get written permission from both the font author AND Mojang or replace these assets with ones you have rights to use. 

As for my stylesheet, I grant you full permission to use it and modify it as you please, but I would be glad if you credited me :)

