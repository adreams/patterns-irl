
Command
-------
.. rubric:: when and how a request is fulfilled

Multi-level undo::

    build list of commands
    each command knows how to undo itself

Actions that can be called from multiple places + shortcuts, images::

    delphi

Macro recording::

    each command can be recorded/played

Task/thread pool::

    each task is a separate command
    threads take task and execute it

Networking::

    remote procedure calls


