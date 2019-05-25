# KEECO HW Node - Vertical design with power module

**WARNING - Should you build the devices described below you will work with hazardous high voltages!**

**Only continue if you have experience in working with high voltages!** 

**Always disconnect your circuitry before touching any component!** 

**Always use appropriate housing for the device that provides mechanical stability and electrical insulation!**

**The PCBs were designed to provide appropriate spacing between different potential signals, however incorrect mounting of through-hole components can result is short circuits and/or connecting low-voltage wires to high potentials!**

**Never connect the wemos's USB port to your computer while the AC mains are connected on the KEECO HW node power module. However this should cause no problem there can be unforeseen circumstances where this scenario could damage your laptop!**


## KEECO_HW_Node_Vertical.dxf
Editable PCB schema for the board that hosts the wemos d1 mini device


### Bill of Materials (BOM)
- wemos d1 mini board
- shipping connector kit for the wemos d1 mini board
- PCB (can be ordered using the gerber zip file)



## KEECO_HW_Node_Vertical_PowerModule.dxf
Editable PCB schema for the power module board that supplies 5V to the KEECO HW Node from 110..230VAC


### Bill of Materials (BOM)
- V1 - 230V varistor (B72220S0231K101)
- F1 - fuse (37002000430)
- F2 - fuse (0467.500NRHF)
- 5V supply (HLK-PM01)
- PCB (can be ordered using the gerber zip file) 
