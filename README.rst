MUJIN Vision Controller C++ Client Library
---------------------------------------------

TODO: python api documentation

This is an open-source client library communicating with the MUJIN Vision Controller WebAPI.

`C++ API Documentation <https://github.com/mujin/mujinvision/blob/master/include/mujinvision/mujinvisionmanager.h>`_

(Note: this API is loosely based on the link above.)


Releases and Versioning
-----------------------

- Versions have three numbers: MAJOR.MINOR.PATCH
  
  - Official releases always have the MINOR and PATCH version as an even number. For example 0.2.4, 0.2.6, 0.4.0, 0.4.2.
  - All versions with the same MAJOR.MINOR number have the same API ande are ABI compatible.
  
- There are `git tags <https://github.com/mujin/mujinvisioncontrollerclientpy/tags>`_ for official release like v0.2.4.

Running on Windows
------------------

TODO: test on windows


Building on Windows
-------------------

TODO: test on windows


Running on Linux
----------------

TODO: open source C++ building.


Install on Linux
-----------------

.. code-block:: bash

  # TODO: make this sort of work at all.
  cmake

Uninstall on Linux
-------------------

.. code-block:: bash

  # TODO: I think it's just `make uninstall` but I haven't checked
  make uninstall


Licenses
--------

MUJIN Vision Controller C++ Client is Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

In other words, **commercial use and any modifications are allowed**.

Since OpenSSL is included, have to insert the following statement in commercial products::

  This product includes software developed by the OpenSSL Project for use in the OpenSSL Toolkit. (http://www.openssl.org/)


For Maintainers
---------------

TODO

To setup building documentation, checkout `this tutorial <https://gist.github.com/825950>`_ so setup **gh-pages** folder. Then run::

  cd gh-pages
  git pull origin gh-pages
  git rm -rf en ja
  cd ../docs
  rm doxygenhtml_installed_*
  make gh-pages
  cd ../gh-pages
  git commit -m "updated documentation" -a
  git push origin gh-pages
