===============================================
git-remote-arc: archive-backed git submodules
===============================================
.. image:: http://img.shields.io/badge/license-UNLICENSE-brightgreen.svg?style=flat-square
    :alt: Unlicense
    :target: http://unlicense.org/UNLICENSE

USAGE
````````````````````````````
1. Download git-remote-arc to a folder located in your path:

.. code:: bash

  sudo wget http://git.io/git-remote-arc -P /usr/local/bin/
  sudo chmod +x /usr/local/bin/git-remote-arc

2. Configure git to allow ``arc`` protocol for submodules:

.. code:: bash

  git config --global protocol.arc.allow always

3. Add submodules from any archive:

.. code:: bash

  git submodule add arc::https://github.com/berenm/git-remote-arc/archive/master.tar.gz git-remote-arc

The script expects that ``wget`` or ``curl``, and ``tar`` or ``7za`` are
available in the ``PATH``. Archive type support depend on the available
tools for extraction.

LICENSE
````````````````````````````

 This is free and unencumbered software released into the public domain.

 See accompanying file UNLICENSE or copy at http://unlicense.org/UNLICENSE
