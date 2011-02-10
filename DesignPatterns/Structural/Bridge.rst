
Bridge
------
.. rubric:: implementation of an object

Abstract away some part of an object implementation::

    Content
    ContentDrawer
      > ContentDrawerAlpha
      > ContentDrawerBeta

    Drawer
    DrawingAPI
      > GDI
      > PNG

Declare abstract class interface for switchable library::

    DBAdaptor
    db = SQLiteAdapter
    db = MySQLAdapter


