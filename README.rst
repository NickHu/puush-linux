===========
puush-linux
===========
------------
Version: git
------------

An enhanced fork of `blha303's original puush-linux`_ bash script.

.. _blha303's original puush-linux: https://github.com/blha303/puush-linux/

Usage
-----

.. code:: bash

  Usage: puush [options] [file]

    Options:
    -d	Delete file
    -f	No delete prompt
    -h	Show this message
    -l [search]	List uploaded files

The variable ``PUUSH_API_KEY`` must be set, either in the environment or at the top of ``puush``. This can be obtained from `puush account settings`_.

If a hyphen is given for the file parameter, puush-linux will attempt to read the filename from STDIN.

.. _puush account settings: http://puush.me/account/settings
