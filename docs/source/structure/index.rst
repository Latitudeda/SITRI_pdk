PDK structure
======================

Process Design Kit (PDK) is a tool for designated users to generate circuit layouts based on SITRI design rules and technology settings.

``SITRI_pdk`` package includes four subfolders: ``components``, ``examples``, ``technology``, and ``util``.

* ``components``

    * BlackBox cells : All blackbox cells are named and designed by SITRI and cannot be changed.

    * Parametrized cells (PCells): Designed by **LDA**, including ``Bend``, ``Straight``. Please see ``gpdk > components`` for more designed components.

* ``examples``

    * ``link.py`` : Test circuit to test if the blackbox cell (``Sitri_Si_GC_Cband_TM_0p925_Blackbox``), auto routing, and auto link function works normally under the PDK setting. Please see ``gpdk > examples`` for more circuit examples.

* ``technology``

    * Store the technology setting which matched the SITRI design rules. We recommend users not to change the settings in technology folder.

    * See chapter ``Technology setting`` for more specific definition.

* ``util``

    * Useful functions when generating circuit layouts.

    * Please see **PhotoCAD** online manual for more information.

* ``layers.lyp`` : This file allows layout tools e.g. Klayout to recognize the layer information when displaying gds file to the layout tool.

    .. image:: ../images/lyp.png

