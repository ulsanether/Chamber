# Production files:
### Chamber_xxmm_tube.stl 
Print one of these per chamber.  
  - __24mm__: kimax centrifuge tube or other 24mm tubes.
  - __25mm__: pyrex vista tubes or other 25mm tubes.

### xxx_magnet_holder.stl
  - __fan__: The magnet holder for the computer fan stirrer (digikey part: _P12820-ND_)
  - __stepper__: The magnet holder for the stepper motor (MPN: ST-PM35-15-11C, sparkfun.com PN: ROB-10551)

### Parameters 
The designs here have been updated to build in openSCAD (http://www.openscad.org/).  The top of the design files contains all parameters, which you can adjust to compensate intricacies of your printer.  To adjust parameters:

  1) Open the source file (.scad) in openSCAD.
  2) Edit parameter of your choice (it's recommended that you only make small changes).
  3) Select Design->Render and wait for rendering to complete (may take several minutes).
  4) Select File->Export->Export as STL... and save the STL.  