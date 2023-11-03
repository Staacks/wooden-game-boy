# wooden-game-boy

An entire classical Game Boy made out of wood (on a CNC router).

[![Youtube Video: WiFi Game Boy Cartridge](https://img.youtube.com/vi/rECMivhOat4/0.jpg)](https://youtu.be/rECMivhOat4)

This was requested after I published my little [wooden Game Boy cartridge](https://github.com/Staacks/wooden-game-boy-cartridge).

<a href="https://www.buymeacoffee.com/there.oughta.be" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-blue.png" alt="Buy Me A Coffee" height="47" width="174" ></a>

## Instructions / details

The documentation with explanations for all toolpaths and a list of tools and bits I used can be found on my blog at (there.oughta.be/a/wooden-game-boy)[https://there.oughta.be/a/wooden-game-boy].

## File overview

The project has been done using the [Blender CAM plugin](https://github.com/vilemduha/blendercam). So, the main folder contains blend files for the different parts of the Game Boy shell and accessoires:
* `reference-frame.blend`: The drills I use to align the workpiece after flipping it.
* `common-case.blend`: The base model from which I derived the more specific files below.
* `bottom-outside.blend`: Toolpaths for the outside of the bottom half of the shell.
* `bottom-inside.blend`: Toolpaths for the inside of the bottom half of the shell.
* `top-outside.blend`: Toolpaths for the outside of the top half of the shell.
* `top-inside.blend`: Toolpaths for the inside of the top half of the shell.
* `battery-lid-outside.blend`: Outside of the battery cover.
* `battery-lid-inside.blend`: Inside of the battery cover.
* `cartridge-outside.blend`: Outside of the Game Boy cartridge. Not that this contains the oak and walnut version and is derived from the [wooden Game Boy cartridge](https://github.com/Staacks/wooden-game-boy-cartridge) with more efficient and better toolpaths.
* `cartridge-inside.blend`: Inside of the Game Boy cartridge.

The folders are mostly for reference:
* `gcode` contains the original machine code that I used. Probably only usefull as reference and should not be sent directly to a different machine.
* `photo` contains the photo and graphic I used for the logo and labels on the front. Note, that obviously trademarks apply to the brand "Nintendo".
* `pokemon` contains the Pokemon Oak and Walnut logos as well as my reference file (which is a public domain image from Wikipedia). Note, that obviously trademarks apply to the brand "Pokemon".

## Licence

I release everything here under the Creative Commons Attribution 4.0 International license (CC-BY 4.0). Enjoy :)

<a href="https://www.buymeacoffee.com/there.oughta.be" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-blue.png" alt="Buy Me A Coffee" height="47" width="174" ></a>

