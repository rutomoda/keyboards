OASIS case for MiRaGe
===
This is a case for the MiRaGe keyboard by Zack Freedman.

<img src="https://github.com/rutomoda/keyboards/tree/master/Keyboard%20Fetlon%20Series/Oasis%20for%20MiRaGe/example_render.png" width="512" height="341">

The cases for left and right side are the same in structure for each side but have slightly different dimensions and are basically mirrored.

All connection points (tray mount and connector tenons) expect M2 heat set inserts. This also means you are going to need M2x6mm screws to screw everything together.

How to print
===
The big rounded case pieces are designed to be printed on their side. Align seams on the underside to get a clean top surface. To help with bridging certain gaps you can load the print_plug-files as parts into the models in your slicer. Be aware that those plugs will have to be removed with a sharp tool after printing. All parts are designed to be easily printable with no (use printing plugs) supports on a smallish print volume.

If the print_plug-parts get ignored in your slicer, you either need to lower your layer height or scale the Z-level of only the print_plug-part.

USB shroud and pen rest are friction fit. Adjust scaling in your slicer if they come out too loose or too tight.

Make sure to print the tenons at 100% infill or 100% perimeter and later heat set the inserts from the bottom!

Configurations
===
The case is tray mounted and supports 6.5mm and 8mm mounting depths. 8mm is default, 6.5mm needs the 1_5mm_spacer on each mounting point (use soft filament for extra dampening).

The side appearance of the cases can be changed by loading the 01 module into your slicer and then consecutively adding 02 and 03 as parts to change the final print. These are available for all big and small side modules:
- 01 alone is a small bezel design, which needs the plates additionally manufactured to be closed properly
- 02 added is a big bezel design, which does NOT use the plates and allows access to the TRRS connector
- 03 added with 02 is 02, but closes TRRS connector access on the side

The plates support 6.5mm and 8mm mounting for the side panel according to their file name. The wide bezel modules support all mounting depths. The USB shroud is reversible to support 6.5mm and 8mm mounting.

The pen rest void can be filled by loading the pen_rest_plug as a part in your slicer, if you prefer to not have it.

STEP-files
===
Some of the STEP-files are missing, because the export keeps crashing. I will maybe someday fix that. Also naming in the STEP-files is inconsistent, because of copy-pasting in my original design, which I need to clean up one day, maybe.

MCU cover
===
There is currently no model / design / file for the MCU cover.

License and Warranty Disclaimer
===
All designs and their corresponding files in this repository are published and licensed under a [Creative Commons Attribution 4.0 International
License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

Use of the files for manufacturing is at own risk, no guarantee of any kind is provided!

THE FILES ARE PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE FILES OR THE USE OR OTHER DEALINGS WITH THE FILES

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
