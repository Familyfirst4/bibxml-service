==============
BibXML Service
==============

For an overview, see https://github.com/ietf-ribose/bibxml-project.

This project uses Docker, Django and PostgreSQL.


Quick start
-----------

Documentation has a section on setting up BibXML service locally.

You can browse documentation `on GitHub <docs/index.rst>`_,
but as it makes use of Sphinx-specific directives unsupported by GitHub
it is recommended to build the documentation into HTML.
This can be done using Docker without any other dependencies.

Ensure you have Docker Desktop with Compose V2 enabled,
navigate to cloned repository root on your machine
and run the following commands::

    docker compose build
    cd docs
    docker compose up

.. note:: If you don’t use Docker Desktop,
          you may need to install Compose separately.

          If you install it as a separate binary,
          you should replace ``docker compose`` with ``docker-compose``,
          and depending on your installation
          you might need to prepend ``sudo``.

After that, point your browser to ``localhost:8001`` for further documentation.


Credits
-------

Authored by Ribose as produced under the IETF BibXML SOW.
