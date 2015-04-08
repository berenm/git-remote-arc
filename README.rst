===============================================
git-remote-arc: archive-backed git submodules
===============================================
.. image:: http://img.shields.io/badge/license-BSL%201.0-blue.svg?style=flat-square
    :alt: BSL 1.0 License
    :target: http://www.boost.org/LICENSE_1_0.txt

USAGE
````````````````````````````
1. Download git-remote-arc to a folder located in your path.

.. code:: bash

  sudo wget http://git.io/git-remote-arc -P /usr/local/bin/
  sudo chmod +x /usr/local/bin/git-remote-arc


2. Add submodules from any archive

.. code:: bash

  git submodule add arc::https://github.com/berenm/git-remote-arc/archive/master.tar.gz git-remote-arc


COPYING INFORMATION
````````````````````````````

 Distributed under the Boost Software License, Version 1.0.

 See accompanying file LICENSE or copy at http://www.boost.org/LICENSE_1_0.txt
