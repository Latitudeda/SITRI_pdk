auto_link.py
=============

Define the auto link policies between different waveguide type.

For example:

``(type(WG.STRIP.C.WIRE) >> type(WG.STRIP.C.WIRE), LinkPrefer(WG.STRIP.C.WIRE), BendUsing(WG.STRIP.C.WIRE.BEND))``

It means that when the start and end waveguide are both ``WG.STRIP.C.WIRE``, the automated waveguide type for routing will be ``WG.STRIP.C.WIRE`` and an automated bend ``WG.STRIP.C.WIRE.BEND`` will be added at a 90 degree turn.


Users are allowed to define and set ``DEFAULT`` to their own specific linking policy.

