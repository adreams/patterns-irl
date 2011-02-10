
Builder
----------------
.. rubric:: how a composite object gets created

.. image:: ./DesignPatterns/Creational/images/Builder.png

Overview
^^^^^^^^

Classes for the pattern:

Builder:
    Abstract interface for creating objects (product)
Concrete Builder:
    Provides implementation for Builder.
Director:
    Director creates the product by using a Concrete Builder.
Product:
    The object that will be created.

This helps to split algorithm of creating something to
the algorithm and the creation process.

.. note:: TODO Diagram of the pattern.

Examples
^^^^^^^^

Different file writers
......................

You need to write different file formats and have
determined way of order of writing the document.

Builder: table writer
Concrete Builder: html writer, csv writer
Director: write rows, write columns
Product: a document

.. note:: TODO Example of not using the pattern

.. note:: TODO Example of using the pattern.

Creating complex objects
........................

You need to create a complex object using a
abstract factory (see Abstract Factory).

Builder: abstract factory
Concrete Builder: Win factory, Mac Factory
Director: creates a panel with aligned buttons
Product: panel with buttons

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
