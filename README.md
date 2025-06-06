<picture> <source media="(prefers-color-scheme: dark)" srcset="Images/Logo-Light.png" width="800"> <img src="Images/Logo-Dark.png" width="1000"> </picture> 

USB-GC2 is new generation GameCube Power Board. It allows powering the console with USB-C Power Delivery.
It also contains a switch to select between 12V or 15V input, making it compatible with a variety of Power Delivery chargers.
This second revision also integrates securities, which protects the GameCube against voltage spikes.
But most importantly, USB-GC2 is now open-source!

Check this Bitbuilt Thread for further informations: [BitBuilt Thread](https://bitbuilt.net/forums/index.php?threads/usb-gc2-next-gen-gamecube-power-board.6925/)
<img src="Images/USB-GC2-Top.jpg" width="800" /> 
<img src="Images/Render1.png" width="400" /><img src="Images/Render2.png" width="400" />
<img src="Images/USB-GC2-Bottom.jpg" width="400" /><img src="Images/Cover.jpg" width="400" />


# PCB
USB-GC2 PCB is available in the [PCB section](https://github.com/Xenii1642/USB-GC2/tree/main/PCB) of the repository. 
Components are all listed in the [BOM file](https://github.com/Xenii1642/USB-GC2/blob/main/BOM.pdf).

### Ordering PCB:
For ordering, you can simply use the Gerber files. Upload it through your favorite manufacturer. 
I ordered mine, and personnaly suggest [JLCPCB](https://jlcpcb.com/) for that board.

For the settings, USB-GC2 doesn't need any. You should however keep the thickness to 1.6mm.
You can also change the color, it's up to you!

### Ordering components:
All the components can be ordered through Digikey or Mouser
⚠️ The links are currently only for Digikey ⚠️

# Requirements:
Except for the soldering stuff, you need a compatible USB-C Power Delivery Charger.
The charger needs to be compatible with 12V or 15V. It should also be able to deliver 2.5A of intensity.
Here are two USB-C Power Delivery chargers:
<img src="Images/Charger.png" width="550" />
### Top charger:
Its tension is 12V ✅
Its current is 1.67A ❌
➡️ This charger is not compatible 😭

### Bottom charger:
Tension is 12V, but it also has 15V ✅
Current is 5A for 12V ✅
Current is 4.33A for 15V ✅
➡️ This charger is 100% compatible, and you will be able to use it with both input mods! 😊
💡 If that's the case, you should use the 12V input instead of 15V. 



# Assembling:
### PCB Assembly:
USB-GC2 PCB has been designed to be assembled in one time, using a hot plate.
My suggestion is to first apply solder paste (stencil makes life easier). Then, place the components using the [BOM file](https://github.com/Xenii1642/USB-GC2/blob/main/BOM.pdf)
I personally use BI58SN42 solder paste, but all work. Choose the one you're the most confident with 👍
Once the components are placed, I used my mini hot plate to solder everything.
It should then look like this:
<img src="Images/USB-GC2 Paste.jpg" width="400" /><img src="Images/USB-GC2 Paste + Components.jpg" width="400" />

⚠️ Please take note that the original power connector (J2) and the Power Switch (SW1) should / must be took from an original board. ⚠️
💡The Step Down converter (U2) is the trickest part to solder. I just apply a really little bit of solder paste, and then apply some flux.
My recommendation is the [SMD291](https://www.digikey.com/en/products/detail/chip-quik-inc/SMD291NL/1160000)from ChipQuick.

Finally, the last step is to solder the USB-C connector. You can use hot air, but I decided to use my solder iron with the solder paste + plenty of flux.
⚠️ Do not forget to make a good clean of the board to avoid flux / solder paste making shorts between multiples pads. ⚠️

### 3D:
The USB-GC2 only needs one 3D printed cover. It is used to fill the old port and make everything prettier.
There is two version of that cover. One [with](https://github.com/Xenii1642/USB-GC2/blob/main/3D/USB%20Cover%20(with%20logo).stl) the logo, and one [without](https://github.com/Xenii1642/USB-GC2/blob/main/3D/USB%20Cover%20(without%20logo).stl).
Both files are available in STL and STEP, allowing 3D printing / ordering and modifying.
If you don't have a 3D printer, you can simply order the cover through [JLC3DP](https://jlc3dp.com/).

The USB-GC2 covers are also available on my Printable account: [Printables 3D files](https://www.printables.com/model/1306430-usb-gc2)

Once printed, simply place the cover and push it against the USB-C port. Using the friction fit technology, it should stay in without moving.

### GameCube Installation:
To install the new USB-GC2 in your Nintendo GamCube console, you first need to open it up using the 3.5mm security bit.
I won't detail the whole dissasembling process here, but you can follow the [iFixit guide](https://www.ifixit.com/Guide/Nintendo+GameCube+Fan+replacement+for+cleaning/1405).

Once the original power board is removed, you can just swap the new USB-GC2 module back in.
Do not forget to plug the cables in the correct orientation.

### Testing:
Once everything is installed, simply grab a compatible USB-C Power Delivery Charger.
Plug it carefully and press the switch. You see the GameCube booting on the screen? It means it's working! Congrats!
You can now reassemble your GameCube and enjoy hours of gameplay with the same and universal charger!
<img src="Images/USB-GC2-Working.jpg" width="800" />


# Support
If you see anything wrong with the repository, the USB-GC itself, or else, please let me know.
You can also contact me for questions or suggestions!
Thanks for your support, and have fun!
