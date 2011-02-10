
Factory Method
--------------
.. rubric:: subclass of object that is instantiated

.. image:: ./DesignPatterns/Creational/images/FactoryMethod.png

Overview
^^^^^^^^

The creating method returns a object based on parameters/inheritance.

Factory method based on parameters is a way to find the
appropriate object to be created. This way we can collect different
object creation ways to one method.

Factory method based on inheritance is a way of subclass
defining the object being created. This way the object inherited
can create appropriate object or modify it accordingly to it's needs.

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

