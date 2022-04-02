Securing Flask Applications with Two-Factor Authentication
==========================================================

This project is a simple implementation of multi-factor authentication using TOTP_, an open-source one-time password algorithm used for authentication.


**Note**: You will need to download and install the FreeOTP_ authenticator app for iOS_ or Android_ in order to test this out.

Installation
============


Install project dependencies

.. code-block:: console

    pip install -r requirements.txt


If you are using Pipenv_:

.. code-block:: console

    pipenv --three
    pipenv shell
    pipenv install



Run the application
===================

.. code-block:: console

    export FLASK_APP=login
    export FLASK_ENV=development
    python -m flask run

.. _TOTP: https://en.wikipedia.org/wiki/Time-based_One-time_Password_algorithm
.. _venv: https://docs.python.org/3/library/venv.html
.. _Pipenv: https://pipenv-fork.readthedocs.io/en/latest/
.. _iOS: https://apps.apple.com/us/app/freeotp-authenticator/id872559395
.. _Android: https://play.google.com/store/apps/details?id=org.fedorahosted.freeotp&hl=en_CA
.. _FreeOTP: https://en.wikipedia.org/wiki/FreeOTP
