
Singleton
----------------
.. rubric:: the sole instance of a class

Overview
^^^^^^^^

.. note:: TODO Description and general idea of the pattern.

.. note:: TODO Diagram of the pattern.

Examples
^^^^^^^^

Lifetime management
...................

Abstract Factory that deals with global lifetime management::

    WindowManager that deals with all window management
    WindowManager.getInstance().createWindow()
    WindowManager.getInstance().MinmizeAll()

.. note:: TODO Principle

.. note:: TODO Example of not using the pattern

.. note:: TODO Example of using the pattern.


Global state
............

Holding a global state::

    Application-Wide Clipboard

.. note:: TODO Principle

.. note:: TODO Example of not using the pattern

.. note:: TODO Example of using the pattern.


Device accessing
................

Resource accessing classes::

    async file - filesystem accesses
    zip.open()
    zip.edit()
    zip.add()

.. note:: TODO Principle

.. note:: TODO Example of not using the pattern

.. note:: TODO Example of using the pattern.


Interfacing with module that has a global state
...............................................

Interfacing with modules/devices that have a global state::

    device.open()
    device.read()
    device.close()

.. note:: TODO Principle

.. note:: TODO Example of not using the pattern

.. note:: TODO Example of using the pattern.

Tips
^^^^

.. note:: TODO Useful tips when to use.

Warnings
^^^^^^^^

This pattern should be used when creating a new instance would break
or potentially break something.

If object is single does not mean it has to be a singleton.

Using a singleton basically hides that you are using a global variable.

.. note:: TODO

Bad example::

    singleton Logger class

More
^^^^

.. note:: TODO Additional information resources.

