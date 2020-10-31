# GameboyMacro MK2
3d printing stl files and Fusion 360 f3d file for a Gameboy Macro body / faceplate.

<img src="img/variant_gameboy_logo/final-product.jpeg" style="max-width:60%;"></img>

This design is based on the upstream of this repository, please see also see the original readme:
https://github.com/gb9k/GameboyMacro

## Photos of printed parts
| part      | description                            | photo                                  |
|-----------|----------------------------------------|----------------------------------------|
| face+back | glued together                         | ![](img/variant_gameboy_logo/face_complete.jpeg)       |
| face      | indent for ABXY and start/select       | ![](img/variant_gameboy_logo/face_button_indents.jpeg) |
| face      | indent for D-Pad                       | ![](img/variant_gameboy_logo/face_dpad.jpeg)           |
| face      | full view of the face                  | ![](img/variant_gameboy_logo/face_full.jpeg)           |
| back      | full view of the back                  | ![](img/variant_gameboy_logo/inner_full.jpeg)          |
| back      | led hole and screw hole reinforcements | ![](img/variant_gameboy_logo/inner_top_left.jpeg)      |
| back      | inner dpad with reinforcements                 | ![](img/variant_gameboy_logo/inner-dpad.jpeg)          |


## Goals of the design
- Game Boy logo
- smooth transitions from all button indents to the top face (edge fillets)
- a recessed frame using the top screen plastic lense as a cover for the display, because it is unprotected without having the touch screen attached
- Full screen sized cutout in order to accomodate the entire display. (I use it with an R4-sdhc card so I wanted see all of the menus)
- .2 mm / 2 layers at the led "hole" to still see it but not fearing water or debris getting in

## Printing instructions
The body is split in two parts because it would be hard to impossible to get a clean result by using support structures.

### Face part
- print with `.15` or `.1` layer height

### Back part
- `.2` layer height is enough
- `2-3` outlines 
- I think I went with .5 line width, but please check in the slicer preview if all of the important lines are printed only as lines to give good structural support and clean outlines
- get your retraction settings right to avoid stringing and manual cleanup afterswards

### Assembly
- glue parts together with superglue, or what you works best for the material you use