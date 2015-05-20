# TI-83-SpaceInvaders
A simple Space Invaders clone for the ti83/84 calculators

####Usage

* Compile with [spasm](https://wabbit.codeplex.com/) with `spasm invaders.z80 invaders.8xp`
* Tested with the [wabbitemu](https://wabbit.codeplex.com/) emulator
* Tested and works on TI-83(+) and TI-84(+/SE)

######To run: 
1. Send to a ti83+/84+SE calculator using [TI-Connect](http://education.ti.com/en/us/products/computer_software/connectivity-software/ti-connect-software/tabs/overview)
2. Press `2nd`then `0` to open the catalog
3. Scroll down to `Asm(` and press `Enter`
4. Press the `PRGM` button and scroll down to `INVADERS`
5. Press `Enter` and the program will start running

######In-Game controls
* `Left` - move left
* `Right`- moves right
* `2nd` - shoot
* `Clear` - Quit

####TODO

* Add new/more invader sprite art
* Levels
* Fix invaders speed up bug
* Reimplement bullet walls
* Fix collision detection bug

####Dependencies

* Uses Sean McLaughlin's ClipSprXOR subroutine for displaying sprites (included in source)
http://tutorials.eeems.ca/ASMin28Days/lesson/day25.html

* Uses an 8-bit random number generator, rand8 (included in source)
http://www.cpcwiki.eu/index.php/Programming:Random_Number_Generator 

* ti83plus.inc (included as .inc)
