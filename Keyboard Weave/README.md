Weave
===
![weave render](/weave-render.png)

The Weave is a layered / sandwich style case designed for the Prime_E keyboard PCB. 

The design is intended to be stacked like so:
1. weave-top-top-2mm
2. weave-top-mid-3mm
3. weave-top-bot-3mm
4. weave-plate-5mm
5. weave-bot-top-3mm
6. weave-bot-mid-3mm
7. weave-bot-bot-2mm
Recommended thicknesses are in millimeters at the end of the file name.

My original build uses 3mm PMMA for all layers, but the plate, which was done in 5mm POM, and does not use top-top.

Manufactoring and assembly notes
===
Be aware that different manufactoring processes and materials feature different tolerances regarding the final dimensions and that manual post processing might be neccessary to perfect the fit between parts.

Stabilizers
---
The 5mm thick plate DOES NOT support PCB mounted stabilizers (without the use of a dremel or similar). There are cutouts that might accept plate mounted stabilizers, although this has never been verified.

Hole sizes
---
All screw holes are 3mm and should fit M3 bolts, which then can be tightened with nuts on one of the sides. All forms of chamfering for countersunk screws need to be done manually. If items like heat inserts or PCB spacers are supposed to be used, please adjust the hole sizes accordingly. 

The LED holes are 1mm and are supposed to accept 1mm PMMA rods, but that fit depends a lot on the tolerance of your manufacturer.

Hotswap socket support
---
There is currently no explicit support for hotswap sockets as the design relies on the PCB being held up by the soldering joints to the switches. It can be achieved by fitting a piece of foam under the PCB.

Fusion DXF export
===
Because Fusion360's DXF export is not always compatible with programms running their own DXF implementation especially regarding splines, the default files are exported with a spline to polyline converter and are rewritten by an import and export with QCAD. This can lead to a line multiplication artifact during import into a programm (witnessed in CoralDraw4X). If this occurs, check the import options first, usually the software should be able to detect and remove these automatically. File dimensions are millimeters.

License and Warranty Disclaimer
===
All designs and their corresponding files in this repository are published and licensed under a [Creative Commons Attribution 4.0 International
License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

Use of the files for manufacturing is at own risk, no guarantee of any kind is provided!

THE FILES ARE PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE FILES OR THE USE OR OTHER DEALINGS WITH THE FILES

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
