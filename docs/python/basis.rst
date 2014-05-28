======================
Create your local environment
======================


Python package manager
======================

How to install python libraries::
    pip install <lib name>

Uninstall::

pip uninstall <lib name>

Creating requirements.txt file with all names of libraries and versions is good practice::

    $ touch requirements.txt
    $ vim requirements.txt

In the file::

    <nazwa-biblioteki>==<wersja-biblioteki>

To intstall dependencies from file execute command::

    $ pip install -r requirements.txt

To freeze state of environment to file execute command:

    $ pip freeze >> output_file.txt


Create Virtualenv
=================

What is virtual env
-------------------

Virtualenv is easy tool to create isolated Python environments.
It helps with dependencies and dependencies versions managemant.


Instalation
-----------

Python package::

    sudo pip install virtualenv

or::

    sudo apt-get install python-virtualenv

On other systems:
    (http://www.virtualenv.org/en/latest/#installation)

Create and activate
-------------------

Create dir to contain all virtual environment::

    $ mkdir .virtuals
    $ cd .virtuals

Create virtual environment::

    $ virtualenv example-virtualenv

Activate::

    $ cd example-virtualenv
    $ source bin/activate

Verify:

    (example-virtualenv)~/.virtuals/example-virtualenv$

