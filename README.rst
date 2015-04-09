===============================================
git-remote-arc: archive-backed git submodules
===============================================
.. image:: http://img.shields.io/badge/license-UNLICENSE-brightgreen.svg?style=flat-square
    :alt: Unlicense
    :target: http://www.boost.org/LICENSE_1_0.txt

USAGE
````````````````````````````
1. Download git-remote-arc to a folder located in your path:

.. code:: bash

  sudo wget http://git.io/git-remote-arc -P /usr/local/bin/
  sudo chmod +x /usr/local/bin/git-remote-arc


2. Add submodules from any archive:

.. code:: bash

  git submodule add arc::https://github.com/berenm/git-remote-arc/archive/master.tar.gz git-remote-arc


LICENSE
````````````````````````````

 This is free and unencumbered software released into the public domain.

 See accompanying file UNLICENSE or copy at http://unlicense.org/UNLICENSE
