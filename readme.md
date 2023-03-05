## Wanhao Duplicator 6 // Monoprice Maker Ultimate configs

- printer.cfg --  Kliper config
  - Bltouch support
  - 10x10 mesh height map calibration
  - Force move Z without homing
- petg-superslicer-config.ini -- PETG settings for SuperSlicer
  - Features a prime line after heating from 05, 30 -> 05, 170 -> 07, 170 -> 07, 30
    - This eliminates the need for skirts or brims!

If you wish to use these configs as a starting point for your Wanhao D6, you may want to consider the modifcations I've made.


Mods:
- OEM enclosure
- Microswiss all metal hotend 
- Triangle Labs direct drive extruder (mounted with Bondtech machined metal mount and Bondtech PCB holder)
- BLTouch 
  - Mount: https://www.thingiverse.com/thing:4108601
  - wired to both the z limit connector and analog connector. Power is from the analog connector pins 2 and 3, servo signal is z limit pin 1, and limit function moved to analog pin 1.
  - Wiring diagram: ![Wiring diagram](/pics/bltouch-wiring.png) ([taken from dot bob](https://www.thingiverse.com/thing:2483813))
- Left and right hand mounted 24v 4010 radial fans wired in parallel into PCB fan slot (no build area loss!)
  - Left mount: https://www.thingiverse.com/thing:4802449
  - Right mount is in this repo (fan_R_holder.stl) -- credit to tqzr from above thingiverse link for sending me the step file
    - ![fan holder stl](/pics/fan_r_holder.png)
- Silicone boot for hotend -- important to avoid cooling down the hotend and prevent errors: https://www.thingiverse.com/thing:2216683 
- Wire management clip for the direct drive mount
  - https://www.thingiverse.com/thing:3762718
- Mirror on top of build plate (removed the buildtak the printer came with)


Non functional (ish) mods:
- Feet to allow airflow: https://www.thingiverse.com/thing:1580480 
- Hole plugs to prevent filament/crap from going to the electronics section: https://www.thingiverse.com/thing:2872888
- Steam valve knob: https://www.thingiverse.com/thing:3152876 
- Custom crimped 16 pin dumont cable to replace the flat 16 pin IDE cable

Useful links:
- Mobo PCB overview: https://3dprint.wiki/reprap/wanhao/duplicator6/major_components/motherboard

![hot end top](/pics/hotend_top.png)
![hot end bottom](/pics/hotend_bottom.png)