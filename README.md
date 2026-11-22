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

* M3 steel machine bolts (two 20mm, three 25mm) and three nuts
[I bought [these](https://www.amazon.com/dp/B0FGV5FCBN?th=1)]

* M6 steel machine bolts (one 30mm) 
[I bought [these](https://www.amazon.com/dp/B0FGV89DVB)]

* M2 nylons machine bolts and standoffs
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

6. [Insert](media/Inner_Ring_Bolt.jpg) the two 25mm M3 bolts into the
inner ring.  When you're done the inner ring should look like 
[this](media/Inner_Ring.jpg).

7. [Screw](media/Base_Core_Outer_Half_Ring.jpg) the outer half-ring onto the
30mm M6 bolt on the base cylinder.

8. Use an M3 25mm bolt and nut to
[affix](media/Base_Core_Outer_Half_Ring_Tripod_Attachment.jpg)
the base cylinder to the
[tripod attachment](stl/Tripod_Attachment.stl).

9. [Insert](/media/Vehicle_Mount._Nut.jpg) an M3 nut into either end of the
[vehicle mount](stl/Vehicle_Mount.stl), again using a dab of E6000 if needed.

10. Screw the two remaining 25mm M3 bolts outward through the nuts in the
vehicle mount.  When you're done the vehicle mount should look like 
[this](media/Vehicle_Mount.jpg).

11. Screw the quick-release plate from your tripod into the tripod
attachment. When you're done you should have an assembly like
[this](media/Tripod_Quick_Release.jpg).

12. Holding the inner ring near one of its bolts, gently push the bolt through
the bearing in the inner half-ring.  By gently squeezing the inner ring you
should be able to push the other bolt through the other bearing.  Attaching the
assembly to your tripod you should get somethig like
[this](media/With_Tripod.jpg).
