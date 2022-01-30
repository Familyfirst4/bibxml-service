
===============================
``bibxml``: Django project root
===============================

.. module:: bibxml

URLs
====

.. automodule:: bibxml.urls
   :members:

URL configuration tries to be self-explanatory,
see :github:`bibxml/urls.py`.

Includes aren’t preferred, instead we have a single hierarchy
that exposes all service URLs at a glance.

Django settings
===============

.. seealso::

   - For settings recognized by Django core and contrib apps,
     by Django Compressor, Whitenoise, Celery, etc.:
     their respective docs online
   - For environment variables that influence settings,
     look for those marked as accepted or required by Django in :doc:`/ref/env`
   - :github:`bibxml/settings.py` for undocumented members

.. automodule:: bibxml.settings
   :members:

Views
=====

``views``
---------

.. automodule:: bibxml.views
   :members:


``error_views``
---------------

.. automodule:: bibxml.error_views
   :members:



Deployment helpers
==================

``asgi``
--------

.. automodule:: bibxml.asgi
   :members:


``wsgi``
--------

.. automodule:: bibxml.wsgi
   :members:
