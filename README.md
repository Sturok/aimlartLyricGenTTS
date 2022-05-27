# Text to Speech Web

Simple Demonstration of Text to Speech

Installation
------------
Create an isolated environment e.g. with docker-compose:

.. code-block:: bash

  $ GOOGLE_APPLICATION_CREDENTIALS_BASE=$(base64 -w 0 < ./data-manager.json) docker-compose up --build -d