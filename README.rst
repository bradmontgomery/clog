clog
====

pretty-printed, color, logging (printing, really) for django


usage
-----

Just pass any data into clog and it'll get pretty-printed.

    >>> from clog import clog
    >>> data = {'here': 'is some data'}
    >>> clog(data)

You can also give it a title:

    >>> clog(data, title="My Data")


Or change the color:

    >>> clog(data, title="My Data", color="red")
