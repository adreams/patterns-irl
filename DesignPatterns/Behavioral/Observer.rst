
Observer
--------
.. rubric:: number of objects that depend on another object;
            how the dependent objects stay up to date

Update when data changes::

    data.change --> listbox.datachanged

Avoid polling data for changes:

    data.change --> listbox.datachanged
    invalidated screen part -> redraw invalidated part

