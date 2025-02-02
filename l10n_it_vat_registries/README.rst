==================
ITA - Registri IVA
==================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:4f0f6d9fb4978aeaa2c5514594f611a6c01643c7873fe19d384f33a17f392bfc
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Production%2FStable-green.png
    :target: https://odoo-community.org/page/development-status
    :alt: Production/Stable
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fl10n--italy-lightgray.png?logo=github
    :target: https://github.com/OCA/l10n-italy/tree/16.0/l10n_it_vat_registries
    :alt: OCA/l10n-italy
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/l10n-italy-16-0/l10n-italy-16-0-l10n_it_vat_registries
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/l10n-italy&target_branch=16.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

Law: Decreto del Presidente della Repubblica del 26 ottobre 1972 n. 633
https://goo.gl/31yTVj

**Table of contents**

.. contents::
   :local:

Configuration
=============

**Italiano**

È possibile configurare quali imposte escludere dai registri (ad esempio le ritenute)
impostando il campo dell'imposta 'Escludere dai registri IVA'

Per generare i periodi fiscali,
aprire Contabilità > Configurazione > Contabilità > Intervalli data > Generazione intervalli data:

* Prefisso nome intervallo: prefisso identificativo dell'anno dei periodi da generare
* Durata: 1 mese
* Numero di intervalli da generare: 12
* Tipo: creare un tipo o utilizzarne uno esistente, non è richiesta una configurazione particolare per il tipo
* Data iniziale: primo giorno dell'anno dei periodi da generare (ad esempio 01/01/2018)

Tramite
Contabilità -> Configurazione -> Contabilità -> Registri IVA
è possibile configurare i registri IVA, ad esempio 'vendite', 'acquisti' o 'corrispettivi'.
Per associare un registro contabile a un registro IVA, aprire il registro tramite
Contabilità -> Configurazione -> Contabilità -> Registri
e impostare il campo "Registro IVA".

Se non ci sono movimenti contabili da stampare, la stampa viene generata con totale zero.


**English**

You can configure which taxes to exclude from registries (like withholding tax)
setting the 'Exclude from VAT registries' field.

In order to generate fiscal periods,
open Accounting > Configuration > Accounting > Date ranges > Generate Date Ranges:

* Range name prefix: Prefix identifying the year of the periods to be generated
* Duration: 1 month
* Number of ranges to generate: 12
* Type: Create a type or use an existing one, no specific type's configuration is required
* Date start: first day of the period's year (for instance 01/01/2018)

Using the menu
Accounting -> Configuration -> Accounting -> VAT registries
you can configure VAT registries, like 'Sales', 'Purchases' or 'corrispettivi'.
In order to link a journal to a VAT registry, open journal by
Accounting -> Configuration -> Accounting -> Journals
and set the 'VAT registry' field.

If there are no account moves to be printed, the report is printed with total equal to zero.

Usage
=====

**Italiano**

Dal menu
Contabilità -> Rendicontazione -> Imposte -> Registri IVA
è possibile lanciare la procedura di stampa, nella quale è necessario impostare un intervallo di date. Qui è possibile utilizzare un periodo fiscale nel campo 'Intervallo Date'.

Nel campo 'Registro IVA' è possibile selezionare un registro preconfigurato, oppure è possibile andare direttamente a impostare i registri e la struttura nei campi sottostanti.


**English**

Using the menu
Accounting -> Reports -> Taxes -> VAT registries
it is possible to launch the print wizard, where you have to set a date range. You can use a fiscal period in the field 'date range'.

In the 'VAT registry' field you can select a preconfigured registry, or you can directly journals and layout in the fields below.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/l10n-italy/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/l10n-italy/issues/new?body=module:%20l10n_it_vat_registries%0Aversion:%2016.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* Agile Business Group
* LinkIt Srl

Contributors
~~~~~~~~~~~~

* Lorenzo Battistini <lorenzo.battistini@agilebg.com>
* Sergio Corato <sergiocorato@gmail.com>
* Elena Carlesso <ecarlesso@linkgroup.it>
* Alex Comba <alex.comba@agilebg.com>

Other credits
~~~~~~~~~~~~~

The development of this module has been financially supported by:

* Odoo Italia Network

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

This module is part of the `OCA/l10n-italy <https://github.com/OCA/l10n-italy/tree/16.0/l10n_it_vat_registries>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
