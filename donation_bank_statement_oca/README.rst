===========================
Donation Bank Statement OCA
===========================

.. !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fdonation-lightgray.png?logo=github
    :target: https://github.com/OCA/donation/tree/16.0/donation_bank_statement_oca
    :alt: OCA/donation
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/donation-16-0/donation-16-0-donation_bank_statement_oca
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runbot-Try%20me-875A7B.png
    :target: https://runbot.odoo-community.org/runbot/180/16.0
    :alt: Try me on Runbot

|badge1| |badge2| |badge3| |badge4| |badge5| 

This module is a glue module between the modules **donation** module and **account_reconcile_oca** from `OCA/account-reconcile <https://github.com/OCA/account-reconcile>`_ which contains the OCA bank statement reconcile interface. It is needed to support donations by credit transfer where the donation is created while processing the bank statement line.

**Table of contents**

.. contents::
   :local:

Usage
=====

In the OCA bank statement reconcile interface, you have a new button **Donation**.

.. figure:: https://raw.githubusercontent.com/OCA/donation/16.0/donation_bank_statement_oca/static/description/donation_bank_statement1.png
   :scale: 80 %
   :alt: OCA bank statement reconcile interface

When you click on that **Donation** button, Odoo opens a pop-up with a simplified pre-filled donation form view.

.. figure:: https://raw.githubusercontent.com/OCA/donation/16.0/donation_bank_statement_oca/static/description/donation_bank_statement2.png
   :scale: 80 %
   :alt: pre-filled donation form view

On this donation form view, you can modify the donation and then:

* validate-it
* or save it as draft

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/donation/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us smashing it by providing a detailed and welcomed
`feedback <https://github.com/OCA/donation/issues/new?body=module:%20donation_bank_statement_oca%0Aversion:%2016.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* Akretion

Contributors
~~~~~~~~~~~~

* Alexis de Lattre <alexis.delattre@akretion.com>

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

.. |maintainer-alexis-via| image:: https://github.com/alexis-via.png?size=40px
    :target: https://github.com/alexis-via
    :alt: alexis-via

Current `maintainer <https://odoo-community.org/page/maintainer-role>`__:

|maintainer-alexis-via| 

This module is part of the `OCA/donation <https://github.com/OCA/donation/tree/16.0/donation_bank_statement_oca>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
