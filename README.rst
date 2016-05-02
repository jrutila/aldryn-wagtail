##############
Aldryn Wagtail
##############


|PyPI Version|

An opinionated Wagtail setup bundled as an Aldryn Addon.

This package will auto configure Wagtail including some extra tools.

======================
Installation & Updates
======================

*********************
Aldryn Platform Users
*********************

We will introduce modifications to the UI that will allow users to install project types (i.e. Wagtail) as easily as django CMS.
In the meantime, please do the following:

1. Click «Add new Project» on the `Control Panel`_
2. Choose «Add a blank new Project»
3. Give your project a name, select «Aldryn Blank Boilerplate», make sure to uncheck «Install django CMS» and click «Create Project»
4. Go to «Manage Addons» and search for «Aldryn Wagtail» and click «Install for free»
5. Define «Wagtail Sitename» and click «Install Aldryn Wagtail»
6. Go to «Dashboard» and click «Deploy Test» 
7. Once deployment is done click «open site»

*******************
Manual Installation
*******************

.. important:: Please follow the setup instructions for installing
               ``aldryn-addons`` and ``aldryn-django`` first!


Add ``aldryn-wagtail`` to your projects ``requirements.txt`` or pip
install it.::

    pip install aldryn-wagtail==1.4.3.0


The version is made up of the Wagtail release with an added digit for the
release version of this package itself.

If you followed the ``aldryn-addons`` and ``aldryn-django`` installation
instructions, you should already have a ``ALDRYN_ADDONS`` setting. Add
``aldryn-wagtail`` to it.::

    INSTALLED_ADDONS = [
        'aldryn-django',
        'aldryn-wagtail',
    ]

Create the ``addons/aldryn-wagtail`` directory at the same level as your
``manage.py``. Then copy ``addon.json``, ``aldryn_config.py`` from
the matching sourcecode into it.

============
Contributing
============

This is a community project. We love to get any feedback in the form of
`issues`_ and `pull requests`_.

===============
Wagtail Support
===============

Divio does not offer support for Wagtail itself. Please check out `wagtail.io`_ for help.

.. _Control Panel: https://control.aldryn.com/control/
.. _issues: https://github.com/aldryn/aldryn-wagtail/issues
.. _pull requests: https://github.com/aldryn/aldryn-wagtail/pulls
.. _aldryn-wagtail: https://github.com/aldryn/aldryn-wagtail
.. _wagtail.io: https://wagtail.io/

.. |PyPI Version| image:: http://img.shields.io/pypi/v/aldryn-wagtail.svg
   :target: https://pypi.python.org/pypi/aldryn-wagtail
