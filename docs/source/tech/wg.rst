wg.py
==========
There are two different waveguides in SITRI pdk, which are defined as follows:

#. ``STRIP``
    #. ``STRIP.C``

        * WG_WIDTH = 0.5 um

    #. ``STRIP.O``

        * WG_WIDTH = 0.41 um

    .. image:: ../images/WG.STRIP.png

#. ``RIB``
    #. ``RIB150.C``

        * CORE_WIDTH = 0.5 um
        * CLAD_WIDTH = 4.5 um

    #. ``RIB150.O``

        * CORE_WIDTH = 0.41 um
        * CLAD_WIDTH = 4.41 um

    .. image:: ../images/WG.RIB150.png

    #. ``RIB90.C``

        * CORE_WIDTH = 0.5 um
        * StripWG_WIDTH = 4.5 um
        * SlabWG_WIDTH = 8.5 um

    #. ``RIB90.O``

        * CORE_WIDTH = 0.41 um
        * StripWG_WIDTH = 4.41 um
        * SlabWG_WIDTH = 8.41 um

    .. image:: ../images/WG.RIB90.png





