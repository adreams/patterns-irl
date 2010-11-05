
Abstract Factory
----------------
.. rubric:: families of product objects

Overview
^^^^^^^^

This pattern uses one interface to define a factory with methods for
constructing interfaced or abstract classes.

.. note:: TODO

Examples
^^^^^^^^

Platform independant factory
............................

blah::

    Filesystem <- Mac FS -> new File with line end set to #10
                  Win FS -> new File with line end set to #13#10

.. note:: TODO

Different GUI implementations
.............................

blah::

    GUIFactory <- Mac factory -> MacButton, MacPanel
                  Win factory -> WinButton, WinPanel
                  Anim factory -> AnimatedButton, AnimatedPanel

.. note:: TODO

Tips
^^^^

.. note:: TODO

Warnings
^^^^^^^^

.. note:: TODO

More
^^^^

.. note:: TODO
