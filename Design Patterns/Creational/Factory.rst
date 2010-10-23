
Factory
----------------
.. rubric:: easier object creation

Overview
^^^^^^^^

Instead of calling the constructor of a class directly
you use a method instead. This means that your creation of
object and setting the properties easily modified without
modifying the original class.

.. note:: TODO Diagram of the pattern.

Examples
^^^^^^^^

Avoid inheritance
.................

Avoiding useless inheritance and code duplication::

    Factory.createBlueButton() -> a button colored blue
    Factory.createRedButton()  -> a button colored red

.. note:: TODO Principle

.. note:: TODO Example of not using the pattern

.. note:: TODO Example of using the pattern.


Information containment
.......................

Information containment::

    Database.createSocket() -> socket with appropriate variables taken
                               from database object

.. note:: TODO Principle

.. note:: TODO Example of not using the pattern

.. note:: TODO Example of using the pattern.

Lifetime management
...................

Lifetime management of created objects::

    WindowManager.createWindow() -> Window, adds window to self
    WindowManager.MinimizeAll()  -> calls minimize for each window

Avoid object duplication
........................

Avoiding duplicate object creation::

    ResourceManager.createResource("somefile.jpg") -> FileX
    ResourceManager.createResource("somefile.jpg") -> FileX


Tips
^^^^

.. note:: TODO Useful tips when to use.

Warnings
^^^^^^^^

.. note:: TODO Misuses and bad examples.

More
^^^^

.. note:: TODO Additional information resources.

