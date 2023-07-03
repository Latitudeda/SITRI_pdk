waveguide_factory.py
========================

Define the straight and bend waveguide factories for auto-routing function in **PhotoCAD**.

#. ``StraightFactory`` : Import the straight waveguide to use it for straight connection.

#. ``BendFactory`` : Import ``Bend``, ``Bend90``, from ``bend_circular`` and assigned each component to different situations.

    * Note that the default bend radius of every 90-degree bend used for auto-routing was set to be 20 um. However, users should define the bend radius themselves to meet the design requirements. A warning label and warning box are added in the component ``Bend90``, users can remove it after setting the right bend radius.

    .. image:: ../images/bend90warning.png



