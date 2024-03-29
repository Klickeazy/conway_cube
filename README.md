# Conway Cube

Cube desklights made from Adafruit's electronics kit for [Conway's Game of Life](https://www.adafruit.com/product/89)

![Demo video](resources/ConwayCube_Demo.mp4)

https://github.com/Klickeazy/conway_cube/assets/15553730/a8a9cece-7bf0-4001-8842-4d74c4a322be

### Parts
- 4 x [Conway's Game of Life Kit - v1.3](https://www.adafruit.com/product/89)
- 1 x [USB-A break out board](https://a.co/d/ib6OiX5)
- 1 x [USB-A male to USB-A male cable](https://a.co/d/3082f9x)

- 3D Printed parts
  - 2 x [Base](stl/Base.stl)
  - 3 x [Side Panel](stl/SidePanel.stl)
  - 1 x [Slotted Side Panel](stl/SidePanel_Slotted.stl)
  - 4 x [Cover Plate](stl/CoverPanel.stl) - this is a thin print and the LED lights shine through it

### Instructions
- Assemble each of the PCB kits SEPARATELY by [Adafruit's instructions](https://learn.adafruit.com/game-of-life). Ensure that all elements are as flush to the PCB as possible. If you are good at soldering and want a clean finish, mount all the LEDs on one side and all the other components on the reverse side.
- Place the PCB on the inner grooves of one of the *base* pieces
- Use inch long flexible wire to join the panels along the N-S direction. This orientation gives good flexibility and clearances while mounting panels
- Each glue-up pair used superglue and accelerant
- Match the slotted side panel and slotted arm of one of the bases to pass-through the USB cable

![Exploded View](resources/explode_view.png)

### Possible design updates
- Externally mounted reset / on-off switch
- Externally mounted USB-breakout board
