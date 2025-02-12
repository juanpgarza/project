===========================================
Project Administrator Restricted Visibility
===========================================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:de867514e6ceb53a66db538209e29f78ae1c31e32ee305f1ea8c8832c3173331
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fproject-lightgray.png?logo=github
    :target: https://github.com/OCA/project/tree/17.0/project_administrator_restricted_visibility
    :alt: OCA/project
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/project-17-0/project-17-0-project_administrator_restricted_visibility
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/project&target_branch=17.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

This module extends the functionality of 'Project' module to add a new
'Project Administrator' access group with restricted visibility to the
projects.

**Table of contents**

.. contents::
   :local:

Configuration
=============

To configure this module, you need to:

1. Go to *Settings > Users & Companies > Users*
2. Create a user or edit an existing one.
3. A new access group called 'Restricted Project Administrator' under
   the 'Projects' category can be selected.

Usage
=====

The new group has the same access rights as the administrator (and see
the same menus), but the project visibility is restricted as a project
user.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/project/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/project/issues/new?body=module:%20project_administrator_restricted_visibility%0Aversion:%2017.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
-------

* Tecnativa

Contributors
------------

- `Tecnativa <https://www.tecnativa.com>`__:

  - Ernesto Tejeda
  - Pilar Vargas

- `Moduon <https://www.moduon.team>`__:

  - Eduardo López

Maintainers
-----------

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

.. |maintainer-rafaelbn| image:: https://github.com/rafaelbn.png?size=40px
    :target: https://github.com/rafaelbn
    :alt: rafaelbn
.. |maintainer-edlopen| image:: https://github.com/edlopen.png?size=40px
    :target: https://github.com/edlopen
    :alt: edlopen

Current `maintainers <https://odoo-community.org/page/maintainer-role>`__:

|maintainer-rafaelbn| |maintainer-edlopen| 

This module is part of the `OCA/project <https://github.com/OCA/project/tree/17.0/project_administrator_restricted_visibility>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
