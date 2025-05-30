# LED-501 SMD Adapter
Adapter Mount for the LED-501 mount from Instrument Systems  

Fit any SMD LED or other Parts onto this mount


<img src="Adapter_Image.png" width="500">

## Parts Needed:
- 3D Printer (To Manufacture the Adapter and Assembly Tools, any 3D Print service does the job)
- 2x Standard 2.54mm Female 01x02 Pin Headers 
- 2x Standard 2.54mm Male 01x02 Pin Headers
- PCBs
- SMD LEDs
- 5mm THT LED (Serves as adapter for the LED-501 mount)
- Flat Side cutter (Knipex 78 61 125 or similar)
- Superglue
- Soldering Iron for Headers
- Hot Air Station for SMD LEDs

## Custom PCBs
If you want to test other SMD LEDs than the included 2835 footprint, you can create your own LED Board.
Doing this is simple and can be done in any EDA Software within minutes.

#### Specifications
- The PCB Outline is a 25mm Circle.
- The LED is placed in the exact centre of the circle.
- The Header pins are placed +/- 8.5mm from the Centre.
- Make sure the GND and VCC contacts are each on the same side as the Base PCB. (e.g. GND Both Left, VCC Both Right) You can swap polarities by roating the PCB.

<img src="PCB_Spacings.png" width="500">

## Assembly

#### Printing Instructions

All parts, except the Adapter (010) can be printed directly without supports.
Be sure to enable rectangular supports for the Adapter.

If you cannot get a somewhat even surface for the PCB to sit on after removing the supports, try angling the adapter 45°, print at a low layerheight (< 0.12 mm) and use a raft and supports (Increase the threshold angle!) for adhesion.

#### Bottom PCB

- Take The Round Assembly Tool Spacer (100) and place the PCB into the Marked Section onto the Assembly Tool.
- Use the PCB Holder (110) to fix the PCB in place
- Insert the 5mm LED and fix it in place using the LED Holder Guide (120), then place and fix the LED with the holder (130)
- Solder the LED in place
- Remove the Assembly Tools
- Use a flat side cutter (Knipex 78 61 125 or similar) to cut off the top LED portion   
- Place the PCB into the Heaxagonal Tool (200)
- Insert the Female 2.54mm 1x2 headers 
- The Headers should face in the opposite direction from the Leads (The LED Leads go upwards, the Headers downwards)
- Place the Assembly upside down onto a flat surface, the headers are now aligned
- Solder the Headers onto the PCB
- Glue the PCB into the Adapter Part (010)   
- Glue the Front cover (020) onto the Adapter
- To protect the LED Leads from damage, you can use the Contact Cover (030)

#### Top PCB

- Solder your SMD LED onto the Top PCB
- Insert the Male 2.54mm 1x2 headers facing away from the SMD LED
- Put the PCB with the headers into the Base PCB, ensuring that the contacts are aligned
- Solder the Headers

The Adapter is now finished and ready for use
