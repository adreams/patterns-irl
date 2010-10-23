
Chain of Responsibility
-----------------------
.. rubric:: pass request to object that can fulfill it

Build a tree of handling processing::

    multiple screen elements
    window -> no handle -- pass on to --> panel
    panel -> handle -> done

