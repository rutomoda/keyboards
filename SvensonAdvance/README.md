Svenson Advance
===
The Svenson Advance is a layered / sandwich style case designed for the Levinson / Let's Split keyboard PCB. 

The case consists of a thick middle layer (middle.dxf) which surrounds the PCB and can be closed off in the back by a optional back layer (back.dxf). On top sits the wide switch plate (plate.dxf) and the middle is completed on the bottom with the bottom layer (bottom.dxf), which features cutouts matching the back layer. To make the case a high profile case a high profile layer (highProfile.dxf) can be added. Further customization of this high profile appearance is possible with a
second high profile embellishment layer (highProfileXEmbellishment.dxf).

Because Fusion360's DXF export is not always compatible with programms running their own DXF implementation especially regarding splines, the default files are exported with a spline to polyline converter and are rewritten by an import and export with QCAD. This can lead to a line multiplication artifact during import into a programm (witnessed in CoralDraw4X). If this occurs, check the import options first, usually the software should be able to detect and remove these automatically. The &ast;FUSION.dxf files are direct Fusion360 exports preserving the splines. File dimensions are millimeters.

Manufactoring and assembly notes
===
Be aware that different manufactoring processes and materials feature different tolerances regarding the final dimensions and that manual post processing might be neccessary to perfect the fit between parts.

Hole sizes
---
The middle layer features 3.1mm holes for a tight press fit of round brass M2 PCB spacers, which usually have a outer diameter of 3.15mm. For a loose fit either increase the size of the holes before manufacturing or use a 1/8in drill (3.175mm) to widen the holes after manufacturing. All other layers feature 2mm (tight fit) holes for M2 bolts.

Layer heights
---
If the vertical back layer is supposed to be used the middle layer has to be 12mm in height, the switch plate has to be 1.5mm in height and the back layer 3mm in height. The middle layer of course can be stacked from multiple layers using the same cutting shape like 4x 3mm layers or 2x 5mm + 1x 2mm layers. For a high profile build the recommended total height for the layers above the switch plate is 6mm (keycap bottom same height as high profile) to 10mm (sunken in look) with 8mm
being the preferred height. 

PCB spacers
---
The M2 round brass PCB spacers located in the middle layer are recommended to have the same height as the middle layer. The design is intended for female/female spacers, but can for example adapted to female/male spacers by changing hole dimensions and manufactoring threaded holes in the bottom layer or adapted to male/male spacers by using a 1.5mm bottom, no high profile layers and tightening the assembly with M2 nuts. For female/female spacers the recommended screw length is the height of layers between
screw head and spacer plus 3mm to 4mm.

Line color
---
The line color of the files may have to be changed for different manufactoring service providers.

Caution regarding the back layer
---
The back layer tries to offer a nice closure for the back side of case. This comes with restrictions regarding the components accessing the back. The current version should be compatible with TRRS jacks up to 10mm outer diameter and with 14mm x 9mm USB jacks, which should fit most USB 2 mini, USB 2 micro and USB-C plugs. The stock reset switch should be accessible in any reasonable position without pressure on the back plate accidentally activating the switch. The USB port
should be accessible regardless of position of the microcontoller PCB. Be aware that there might be configurations and tolerances between builds with which dimension might not adding up like they are supposed to. 

Hotswap socket support
---
There is currently no support for hotswap sockets as the design relies on the PCB being held up by the soldering joints to the switches. 

License and Warranty Disclaimer
===
The Svenson Advance case design and all its files are published and licensed under Creative Commons Attribution 4.0 International (CC BY 4.0). See also: https://creativecommons.org/licenses/by/4.0/

Use of the files for manufacturing is at own risk, no guarantee of any kind is provided.

THE FILES ARE PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE FILES OR THE USE OR OTHER DEALINGS WITH THE FILES.
