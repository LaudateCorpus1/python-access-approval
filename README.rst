Python Client for Access Approval API
=====================================

|GA| |pypi| |versions|

`Access Approval API`_: An API for controlling access to data by Google personnel.

- `Client Library Documentation`_
- `Product Documentation`_

.. |GA| image:: https://img.shields.io/badge/support-GA-gold.svg
   :target: https://github.com/googleapis/google-cloud-python/blob/main/README.rst#general-availability
.. |pypi| image:: https://img.shields.io/pypi/v/google-cloud-access-approval.svg
   :target: https://pypi.org/project/google-cloud-access-approval/
.. |versions| image:: https://img.shields.io/pypi/pyversions/google-cloud-access-approval.svg
   :target: https://pypi.org/project/google-cloud-access-approval/
.. _Access Approval API: https://cloud.google.com/access-approval
.. _Client Library Documentation: https://cloud.google.com/python/docs/reference/accessapproval/latest
.. _Product Documentation:  https://cloud.google.com/access-approval

Quick Start
-----------

In order to use this library, you first need to go through the following steps:

1. `Select or create a Cloud Platform project.`_
2. `Enable billing for your project.`_
3. `Enable the Access Approval API.`_
4. `Setup Authentication.`_

.. _Select or create a Cloud Platform project.: https://console.cloud.google.com/project
.. _Enable billing for your project.: https://cloud.google.com/billing/docs/how-to/modify-project#enable_billing_for_a_project
.. _Enable the Access Approval API.:  https://cloud.google.com/accessapproval
.. _Setup Authentication.: https://googleapis.dev/python/google-api-core/latest/auth.html

Installation
~~~~~~~~~~~~

Install this library in a `virtualenv`_ using pip. `virtualenv`_ is a tool to
create isolated Python environments. The basic problem it addresses is one of
dependencies and versions, and indirectly permissions.

With `virtualenv`_, it's possible to install this library without needing system
install permissions, and without clashing with the installed system
dependencies.

.. _`virtualenv`: https://virtualenv.pypa.io/en/latest/


Supported Python Versions
^^^^^^^^^^^^^^^^^^^^^^^^^
Python >= 3.6

Deprecated Python Versions
^^^^^^^^^^^^^^^^^^^^^^^^^^
Python == 2.7.

The last version of this library compatible with Python 2.7 is google-cloud-access-approval==0.2.0.


Mac/Linux
^^^^^^^^^

.. code-block:: console

    pip install virtualenv
    virtualenv <your-env>
    source <your-env>/bin/activate
    <your-env>/bin/pip install google-cloud-access-approval


Windows
^^^^^^^

.. code-block:: console

    pip install virtualenv
    virtualenv <your-env>
    <your-env>\Scripts\activate
    <your-env>\Scripts\pip.exe install google-cloud-access-approval

Next Steps
~~~~~~~~~~

-  Read the `Client Library Documentation`_ for Access Approval API
   API to see other available methods on the client.
-  Read the `Access Approval API Product documentation`_ to learn
   more about the product and see How-to Guides.
-  View this `README`_ to see the full list of Cloud
   APIs that we cover.

.. _Access Approval API Product documentation:  https://cloud.google.com/access-approval
.. _README: https://github.com/googleapis/google-cloud-python/blob/main/README.rst
