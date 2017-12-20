Server for **YUPPIENALLE**
==========================

## First - Install Conda

requirements: python, numpy, autobahn

    $ conda config --add channels conda-forge 
    $ conda create --name yuppienalle numpy autobahn
    $ source activate yuppienalle
    $ cd path/to/yuppienalle/server 
    $ python setup.py develop
    $ run-yuppie
