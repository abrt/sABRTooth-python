Tutorial
========

Example
-------

.. warning::
    You will need to set `allow-unpackaged` to `True` in `/etc/faf/faf.conf`.

.. code-block::

    import sabrtooth

    NAME = "application"
    FAF_URI = "http://localhost:8080/faf/" # ABRT Analytics instance to use for reporting

    sabrtooth.register(NAME, FAF_URI)

    0/0
