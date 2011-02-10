
Mediator
--------
.. rubric:: how and which objects interact with each other

Avoid direct dependancy between classes:

    instead of
        Client -> Folder
    use
        Client -> ClientFolderMapping -> Folder

Rules of thumb::

    http://sourcemaking.com/design_patterns/mediator

