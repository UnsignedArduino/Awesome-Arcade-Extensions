# MakeCode Arcade Extensions
This is a list of MakeCode Arcade extensions that I find super useful in my projects. If you would like to suggest an extension be added, please open an issue with a link to the extension on Github. Or even better, open a pull request for adding an extension! Make sure to include a description, import url, and links to it's Github repo, Github Pages example if any, and forum post showcasing the extension if any.

You can find the old gist [here](https://gist.github.com/UnsignedArduino/3bc2adce4b3f687ea1967578449d014d).

## Table of contents
- [**Built-in extensions**](https://github.com/UnsignedArduino/Awesome-Arcade-Extensions#built-in-extensions)
  - [arcade-sprite-data](https://github.com/UnsignedArduino/Awesome-Arcade-Extensions#arcade-sprite-data)
  - [Timers](https://github.com/UnsignedArduino/Awesome-Arcade-Extensions#timers)
  - [settings-blocks](https://github.com/UnsignedArduino/Awesome-Arcade-Extensions#settings-blocks)
  - [Color Fading](https://github.com/UnsignedArduino/Awesome-Arcade-Extensions#color-fading)
- [**Not built-in extensions**](https://github.com/UnsignedArduino/Awesome-Arcade-Extensions#not-built-in-extensions)
  - [character-animations](https://github.com/UnsignedArduino/Awesome-Arcade-Extensions#character-animations)
  - [arcade-tilemap-a-star](https://github.com/UnsignedArduino/Awesome-Arcade-Extensions#arcade-tilemap-a-star)
  - [arcade-custome-menu](https://github.com/UnsignedArduino/Awesome-Arcade-Extensions#arcade-custom-menu)
  - [arcade-block-objects](https://github.com/UnsignedArduino/Awesome-Arcade-Extensions#arcade-block-objects)
  - [arcade-story](https://github.com/UnsignedArduino/Awesome-Arcade-Extensions#arcade-story)
  - [arcade-sprite-util](https://github.com/UnsignedArduino/Awesome-Arcade-Extensions#arcade-sprite-util)
  - [arcade-image-text](https://github.com/UnsignedArduino/Awesome-Arcade-Extensions#arcade-image-text)
  - [pxt-lantern](https://github.com/UnsignedArduino/Awesome-Arcade-Extensions#pxt-lantern)
  - [pxt-rtttl](https://github.com/UnsignedArduino/Awesome-Arcade-Extensions#pxt-rtttl)
  - [arcade-shader](https://github.com/UnsignedArduino/Awesome-Arcade-Extensions#arcade-shader)
- [**Tools**](https://github.com/UnsignedArduino/Awesome-Arcade-Extensions#tools)
  - [Convert-Image-to-MakeCode-Arcade-Sprite](https://github.com/UnsignedArduino/Awesome-Arcade-Extensions#convert-image-to-makecode-arcade-sprite)
  - [pxt-arcade-asset-tool](https://github.com/UnsignedArduino/Awesome-Arcade-Extensions#pxt-arcade-asset-tool)
  - [arcade-sprite-pack](https://github.com/UnsignedArduino/Awesome-Arcade-Extensions#arcade-sprite-pack)

## Built-in extensions
These extensions are already built in to the editor, all you have to do is go to the toolbox, open the `Advanced` tab, click on `Extensions`, and click on the extension you want to import!
### arcade-sprite-data
It's local variables, but for sprites! Super useful for saving certain attributes of a sprite like the health of an enemy. This will add a section full of blocks called `Data` under the `Sprites` category in the toolbox.

[Official docs](https://arcade.makecode.com/pkg/microsoft/arcade-sprite-data) | [Github repo](https://github.com/microsoft/arcade-sprite-data) | [Forum post](https://forum.makecode.com/t/sprite-data-extension/1590)
### Timers
It's literal multithreading! Setup a callback for your code or run it in a separate fiber (thread) with this extension! This will add another category in the toolbox called `Timer`. 

[Official docs](https://arcade.makecode.com/pkg/microsoft/arcade-timers) | [Github repo](https://github.com/microsoft/arcade-timers) | [Forum post](https://forum.makecode.com/t/timers-extension-after-x-debounce-throttle-and-in-background/1925)
### settings-blocks
Save data in an easy-to-use JSON-like format, now avaliable for the block users! This will add another category in the toolbox called `settings`.

[Official docs](https://arcade.makecode.com/pkg/microsoft/pxt-settings-blocks) | [Github repo for block defs](https://github.com/microsoft/pxt-settings-blocks) | [Github repo for implementation](https://github.com/microsoft/pxt-common-packages/tree/master/libs/settings) | [Forum post](https://forum.makecode.com/t/settings-extension/1594)
### Color Fading
Want some cool fade-in and fade-out effects for your cutscenes? Or want to change the default colors at runtime? This is the extension for you! This extension goes together nicely with the Story extension linked down below. This will add another category in the toolbox called `Color`.

[Official docs](https://arcade.makecode.com/pkg/jwunderl/pxt-color) | [Github repo](https://github.com/jwunderl/pxt-color) | [Forum post](https://forum.makecode.com/t/fireworks-and-pxt-color-extension/315)
## Not built-in extensions
The following extensions, while just as good as the ones listed above, will require some slightly different steps while importing. First go to the toolbox, open the `Advanced` tab, click on `Extensions`, and you will see a text box that says `Search or enter project URL...`. This is where you will paste in the URL to the extension. The URL will be posted along with the listing.
### character-animations
Import this extension with the URL:
> https://github.com/riknoll/character-animations

A version of the `Animation` extension but much more easier to handle if your sprites (Ex. main player) has a lot of different movements, like moving up, down, left, and right. The `character-animations` extension will automatically start and stop animations depending on what the player is doing. This will add another category in the toolbox called `Character`.

[Github repo](https://github.com/riknoll/character-animations)
### arcade-tilemap-a-star
Import this extension with the URL:
> https://github.com/jwunderl/arcade-tilemap-a-star

Help your sprites find their way around your tilemaps with this extension! Just provide 2 locations on a tilemap and it will automagically compute the fastest path between the 2 spots while also moving around walls using the [A* algorithm](https://en.wikipedia.org/wiki/A*_search_algorithm)! This will add another section in the `Scene` category called `Path Following` in the toolbox.

[Github repo](https://github.com/jwunderl/arcade-tilemap-a-star) | [Forum post](https://forum.makecode.com/t/tilemap-path-finding-a-beta/1846) | [Wikipedia article on the A* algorithm](https://en.wikipedia.org/wiki/A*_search_algorithm)
### arcade-custom-menu
Import this extension with the URL:
> https://github.com/riknoll/arcade-custom-menu

One of my favorite extensions, it allows you to make a menu out of a list of strings! Use this for selecting options where using `game.askForNumber()` and `game.askForString()` would be unintuitive or clumsy. This will add another category in the toolbox called `BlockMenu`.

[Github repo](https://github.com/riknoll/arcade-custom-menu)
### arcade-block-objects
Import this extension with the URL:
> https://github.com/microsoft/arcade-block-objects

Object-oriented programming is no doubt an important topic in prograaming. This extension will help you make objects in blocks! Attach all sorts of data to an object, like numbers, strings, images, sprites, locations, and more! This will add a category in the toolbox called `BlockObject` with 7 sub-categories.

[Github repo](https://github.com/microsoft/arcade-block-objects)
### arcade-story
Import this extension with the URL:
> https://github.com/riknoll/arcade-story

Need some cutscenes with dialog? This extension is for you! Comes with a variety of blocks designed to make writing stories and scenes much easier. This extension pairs great with the `Color Fading` extension linked above. This will add a new category called `Story` in the toolbox.

[Github repo](https://github.com/riknoll/arcade-story)
### arcade-sprite-util
Import this extension with the URL:
> https://github.com/jwunderl/arcade-sprite-util

As the name says, this extension has a bunch of utilities for sprites and more, especially anything dealing with trigonometry. This extension adds a new category called `Sprite Utils` in the toolbox.

[Github repo](https://github.com/jwunderl/arcade-sprite-util) | [Github pages demo](https://jwunderl.github.io/arcade-sprite-util/)
### arcade-image-text
Import this extension with the URL:
> https://github.com/pelikhan/arcade-image-text

Simple but sweet, this extension adds the very much-need blocks to print text onto images. This will add a new section called `Text` under the `Images` category in the toolbox.

[Official docs](https://pelikhan.github.io/arcade-image-text/README) | [Github repo](https://github.com/pelikhan/arcade-image-text) | [Forum post](https://forum.makecode.com/t/arcade-print-text-extension/1827)
### pxt-lantern
Import this extension with the URL
> https://github.com/felixtsu/pxt-lantern

Light up your games with this extension! It allows you to turn the lights on or off and add lanterns to sprites so that they have light around them when you turn the lights off. This will add 2 categories called `Lantern` and `Multilights` under the toolbox.

[Github repo](https://github.com/felixtsu/pxt-lantern) | [Github pages demo*](https://riknoll.github.io/pxt-lantern/) | [Forum post](https://forum.makecode.com/t/hope-this-ext-can-bring-some-light-s/3229)

*Note that the Github pages demo only demonstrates the original features of the lantern extension written by @riknoll [here](https://github.com/riknoll/pxt-lantern). A more up-to-date example can be found [here](https://arcade.makecode.com/25139-51900-79237-05503).

### pxt-rtttl
Import this extension with the URL:
> https://github.com/pelikhan/pxt-rtttl

Play beautiful melodies encoded in the RTTTL language in MakeCode with this extension! You can use this [website]([http://midi.mathewvp.com/midi2RTTL.php](http://midi.mathewvp.com/midi2RTTL.php)) to turn yoru `.mid` and `.midi` files into a RTTTL-compatible string of text! This extension adds a block in the `Melody` section in the `Music` category in the toolbox.

[Github repo](https://github.com/pelikhan/pxt-rtttl) | [Github pages demo](https://pelikhan.github.io/pxt-rtttl/) | [Forum post](https://forum.makecode.com/t/rtttl-tunes-extension/4193/6) | [MIDI to RTTTL converter]([http://midi.mathewvp.com/midi2RTTL.php](http://midi.mathewvp.com/midi2RTTL.php))

### arcade-shader
Import this extension with the URL:
> https://github.com/riknoll/arcade-shader/tree/master

Arcade games can get more realistic with shadows! This extension will add a category called `Shaders` in the toolbox.

[Github repo](https://github.com/riknoll/arcade-shader) | [Forum post](https://forum.makecode.com/t/shader-extension/4860) 
## Tools
Yes, this is about useful MakeCode Arcade extensions but these tools will level up your game-making experience!
### Convert-Image-to-MakeCode-Arcade-Sprite
This tool will convert your images (like `.png` files) to Arcade code! Simply copy the output, open JavaScript mode in your project, navigate to where you want the image block to go, and paste in the image code! You may need to remove some redundant characters. Remember that Arcade has a maximum image size of 500x500!

Find this tool here:
> https://kristianpedersen.github.io/Convert-Image-to-MakeCode-Arcade-Sprite/

[Github repo](https://github.com/kristianpedersen/Convert-Image-to-MakeCode-Arcade-Sprite) | [Forum post](https://forum.makecode.com/t/ive-made-an-image-file-to-arcade-sprite-converter-feedback-and-code-improvements-wanted/2076)

### pxt-arcade-asset-tool
This tool will also convert you images to Arcade code, but it also supports using 16-color palettes, in case you don't want to use the default palette! Simply copy the output, open JavaScript mode, navigate to where you want the image to go, and paste away! You may need to remove some redundant characters. Remember that Arcade has a maximum image size of 500x500!

Find this tool here:
> https://riknoll.github.io/pxt-arcade-asset-tool/

[Github repo](https://github.com/riknoll/pxt-arcade-asset-tool/)

### arcade-sprite-pack
Have a bunch of images you want to send to someone, but they hate exercising their pinkie and pointer finger? This will convert a set of images into a MakeCode project that, when you import, will put the images into the image gallery!

Find this tool here:
> https://shakao.github.io/arcade-sprite-pack/

[Github repo](https://github.com/shakao/arcade-sprite-pack)
***
Written with [StackEdit](https://stackedit.io/).
