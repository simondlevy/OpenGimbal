# OpenGimbal

This is a standalone fork of Suryansh Sharma's
[OpenGimbal](https://github.com/tristandijkstra/OpenGimbal) project, q.v. for
details For this fork I simplified the original with the following changes:

1. Support only the tripod version (no tabletop).

2. Exploit the larger bed size of the Bambu 1S printer (256x256mm) to support
a single piece for the inner ring and vehicle mount, resulting in only five
STL files.

3. Redesign the
[vehicle mount](https://github.com/simondlevy/OpenGimbal/blob/main/stl/Vehicle_Mount.stl)
to accommodate the popular 25.5x25.5mm TinyWhoop flight-controller mounting holes.

4. Add brackets to immobilize the pitch and/or roll axis as needed.

5. Add assembly instructions with photos

## Parts

* M3 steel machine screws (three 20mm, two 25mm) and two nuts
[I bought [these](https://www.amazon.com/dp/B0FGV5FCBN?th=1)]

* M6 steel machine screws (one 30mm) 
[I bought [these](https://www.amazon.com/dp/B0FGV89DVB)]

* M2 nylons machine screws and standoffs
[I bought [these](https://www.amazon.com/dp/B07D78PFQL)]

* Ball Bearing ID 3mm x OD 9mm x Width 5mm (four)
[I bought [these](https://www.amazon.com/dp/B0CH2Y5KWF)]

* Ball Bearing ID 6mm x OD 12mm x Width 4mm (two)
[I bought [these](https://www.amazon.com/HiPicco-MR126-2RS-Bearings-Miniature-Pre-Lubricated/dp/B0C74WQ9HM)

## Assembly

1. 3D print the five main [parts](stl/).  Again, you will need a printer with a bed
big enough to print the 22x22cm [inner ring](stl/Inner_Ring.stl).

2. Add the [inner](media/Base_Core_Inner_Bearing.jpg) and
[top](/media/Base_Core_Top_Bearing.jpg) 6x12x4 bearings to the base cylinder.

3. [Insert](media/Base_Core_Main_Bolt.jpg) the 30mm M6 bolt into the
the base cylinder.

4. [Insert](media/Outer_Half_Ring_Bearing.jpg) two of the four 3x9x5 bearings to the
[outer half-ring](stl/Outer_Half_Ring.stl).  If there's not enough friction
to keep a bearing firmly in place, a dab of smeared
[E6000 adhesive](https://www.amazon.com/6000-Clear-Crafts-Purpose-Transparent/dp/B0BNJN4S53)
around the perimeter of the hole should do the trick.

5. [Insert](media/Inner_Ring_Bearing.jpg) the remaining two 3x9x5 bearings to the
[inner ring](stl/Inner_Ring.stl), again using a dab of E6000 if needed.

6.  [Insert](media/Inner_Ring_Bolt.jpg) two of the 25mm M3 bolts into the
inner ring.  When you're done the inner ring should look like 
[this](media/Inner_Ring.jpg).
