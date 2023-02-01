# Intro
###
### most of the components on the PCB are small "surface mount" components. they have no leads (wires), and are soldered on the same side they are placed. these can be hand-soldered, but on this board they're machine-populated and soldered by an oven.
###
### however, there's a handful of "through hole" components that must be soldered on the opposite side. these days, it's more expensive to machine-populate that kind of part, so you'll solder them by hand. "through hole" components also form a more robust connection to the PCB, so all user-adjustable parts (like the trimpot and jumper) must be "through hole" so they don't get ripped off the board accidentally.
###
### equivalents to these "through hole" components are available in "surface mount" versions, but they're more expensive in that format (sometimes much more expensive). so it's cheaper use the "through hole" version and to pay someone to solder them.
###
# Step by Step
### first, use a black sharpie to cross out the text "jan2020" at the bottom edge of the PCB.
### use a single stroke to create a clear black bar:
![](img/IMG_6652_c.jpg)
###
### JST 2.0mm 2-pin connector:
![](img/IMG_6654_c.jpg)
### (these are used to connect the DC power jack and the footswitch)
###
### film box cap: 0.1uF (100nF):
![](img/IMG_6657_c.jpg)
### ONLY on C7, bend leads down before soldering (this prevents them from touching the switch that will be soldered above them).
###
### 100nF populated:
![](img/IMG_6659_c.jpg)
###
### film box cap: 2.2nF (2200pF):
![](img/IMG_6660_c.jpg)
###
### film box cap: 0.47uF (470nF):
![](img/IMG_6665_c.jpg)
### the 0.47uF cap is slightly taller than other film box caps, so solder last.
###
### trimpot: 10k ohmomo (103):
![](img/IMG_6667_c.jpg)
### if this won't stay in place easily, you can solder it before the caps.
###
### pin header: 2.54mm 3-pin:
![](img/IMG_6671_c.jpg)
###
### add white jumper to the upper pins:
![](img/IMG_6673_c.jpg)
### this forms a connection between them. electrically the same as a switch but much cheaper.
###
### POLAR!!
### electrolytic cap: 47uF.
### black half of circle with round pad is for negative pin of cap.
![](img/IMG_6680_c.jpg)
###
### trim electrolytic leads.
![](img/IMG_6675_c.jpg)
###
### trimmed:
![](img/IMG_6677_c.jpg)
###
### add 3 wires:
![](img/IMG_6683_c.jpg)
### we order these wires pre-trimmed to save on assembly time.
### these are used to connect the jacks. only one jack needs a wire to ground, because their grounds are connected through the metal enclosure.
### done.
