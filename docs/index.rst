The Hypermodern Pypras Project
==============================

.. toctree::
   :hidden:
   :maxdepth: 1

   license
   reference

The exercise project created from the example project for the
`Hypermodern Python <https://medium.com/@cjolowicz/hypermodern-python-d44485d9d769>`_
article series.
The command-line interface prints random facts to your console,
using the `Wikipedia API <https://en.wikipedia.org/api/rest_v1/#/>`_.


Installation
------------

To install the Hypermodern Pypras project,
run this command in your terminal:

.. code-block:: console

   $ pip install hypermodern-pypras


Usage
-----

Hypermodern Pypras's usage looks like:

.. code-block:: console

   $ hypermodern-pypras [OPTIONS]

.. option:: -l <language>, --language <language>

   The Wikipedia language edition,
   as identified by its subdomain on
   `wikipedia.org <https://www.wikipedia.org/>`_.
   By default, the English Wikipedia is selected.

.. option:: --version

   Display the version and exit.

.. option:: --help

   Display a short usage message and exit.
