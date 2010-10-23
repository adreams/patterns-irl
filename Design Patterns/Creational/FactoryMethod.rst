
Factory Method
--------------
.. rubric:: subclass of object that is instantiated

Overview
^^^^^^^^

The creating method returns a decendant class of a class
based on parameters.

.. note:: TODO Diagram of the pattern.

Examples
^^^^^^^^

File or Directory creation
..........................

bleh::

    Factory.create('./file.txt')   -> File
    Factory.create('./directory/') -> Directory


.. note:: TODO Principle

.. note:: TODO Example of not using the pattern

.. note:: TODO Example of using the pattern.

Creating correct file reader
............................

bleh::

    ImageReader.create('./image.jpg') -> JPGReader
    ImageReader.create('./image.png') -> PNGReader

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

