
Prototype
----------------
.. rubric:: class of object that is instantiated

.. image:: ./DesignPatterns/Creational/images/Prototype.png

Overview
^^^^^^^^

.. note:: TODO Description and general idea of the pattern.

.. note:: TODO Diagram of the pattern.

Examples
^^^^^^^^

.. warning: examples not that great

Reduce inheritance
..................

Reducing inheritance by using prototype objects instead of classes::

    Creature -> Orc.clone() -> Creature of class Orc

.. note:: TODO Principle

.. note:: TODO Example of not using the pattern

.. note:: TODO Example of using the pattern.

Avoid instiating "expensive" classes
....................................

Avoid instiating "expensive" classes::

    Camera = Yaw x Roll x Location x Transformation
    for each p
        c = Camera.clone()
        c = c x p()

.. note:: TODO Principle

.. note:: TODO Example of not using the pattern

.. note:: TODO Example of using the pattern.

Tips
^^^^

.. note:: TODO Useful tips when to use.

Warnings
^^^^^^^^

.. note:: TODO Misuses and bad examples.

More
^^^^

.. note:: TODO Additional information resources.

