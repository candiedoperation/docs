Building Veyon from Source
============
Veyon can be Built from source by cloning it recursively from https://github.com/veyon/veyon.git

.. code-block::

       git clone --recursive https://github.com/veyon/veyon.git
       git checkout master

In order to build other versions of Veyon (say 4.6), use :code:`git checkout 4.6`. The List of versions can be found at https://github.com/veyon/veyon/branches

Building Veyon on Ubuntu 20.04
-------
Installing Dependencies

.. code-block::

    apt install g++ libc6-dev make cmake qtbase5-dev qtbase5-private-dev \
            qtbase5-dev-tools qttools5-dev qttools5-dev-tools \
            qtdeclarative5-dev qtquickcontrols2-5-dev libfakekey-dev \
            xorg-dev libxtst-dev libjpeg-dev zlib1g-dev libssl-dev libpam0g-dev \
            libprocps-dev liblzo2-dev libqca-qt5-2-dev libldap2-dev \
            libsasl2-dev libkf5itemmodels-dev libfakekey-dev
