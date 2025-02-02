======================
ITA - Imposta di bollo
======================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:9e3bd7115f16ba30901aa7ad44960d1c8450689b0cf8601bb2bb9be562a4d724
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-LGPL--3-blue.png
    :target: http://www.gnu.org/licenses/lgpl-3.0-standalone.html
    :alt: License: LGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fl10n--italy-lightgray.png?logo=github
    :target: https://github.com/OCA/l10n-italy/tree/16.0/l10n_it_account_stamp
    :alt: OCA/l10n-italy
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/l10n-italy-16-0/l10n-italy-16-0-l10n_it_account_stamp
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/l10n-italy&target_branch=16.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

**Italiano**

Questo modulo aggiunge il supporto all'imposta di bollo italiana nelle fatture e nelle ricevute.

**English**

This module adds Italian Tax Stamp support in invoices and receipts.

**Table of contents**

.. contents::
   :local:

Configuration
=============

**Italiano**

Per modificare le impostazioni sul prodotto "Imposta di bollo 2 euro" è necessario abilitare le funzioni complete per la contabilità:

1. Impostazioni -> Utenti e aziende -> Gruppi
2. Cercare il gruppo "Mostrare funzionalità contabili complete" e selezionarlo
3. Nel tab "Utenti" aggiungere l'utente e salvare


Modalità automatica:

- andare sul prodotto "Imposta di bollo 2 euro" e configurare "Imposte marca da bollo" (Imposte in esenzione).

- per ciascuna fattura o ricevuta, l'applicabilità dell'imposta di bollo verrà calcolata in modo automatico in base alla somma degli imponibili relativi alle imposte selezionate.

Modalità manuale:

- andare sul prodotto "Imposta di bollo 2 euro" e deselezionare la casella "Calcolo automatico".

- per ciascuna fattura o ricevuta, abilitare manualmente la casella di selezione "Imposta di bollo". L'applicabilità dell'imposta di bollo verrà calcolata in base alla somma degli imponibili relativi alle imposte selezionate.

Impostare i conti di ricavo/costo nella scheda "Contabilità", generalmente ricavo="Debiti per bolli" e costo="Valori bollati".

**English**

In order to change Tax Stamp 2 euro product settings, enable full accounting features:

1. Settings -> Users & Companies -> Groups
2. Search "Show Full Accounting Features" group and select it
3. In "Users" Tab, add user and save

Automatic mode:

- Go to 'Tax Stamp 2 euro' product and configure 'Stamp taxes' (exemption taxes).

- For each invoice or receipt, the base amount for each selected tax will be added up and used to determine the application of the account stamp.

Manual mode:

- Go to 'Tax Stamp 2 euro' product and deselect 'Auto-compute' checkbox.

- For each invoice or receipt, manually enable 'Tax Stamp' checkbox.

Also set income/expense accounts, typically income = 'Debiti per bolli' and expense = 'Valori bollati'.

Usage
=====

**Italiano**

Se nella fattura o ricevuta è previsto l'addebito dell'imposta di bollo al cliente, fare clic sul pulsante "Aggiungi riga bollo" per aggiungere una riga relativa all'imposta di bollo.

In caso contrario, l'imposta di bollo verrà comunque considerata ma non verrà addebitata al cliente.

**English**

In invoice or receipt form, when applicable, click 'Add tax stamp line' button to add tax stamp as invoice line, thus charging customer.

Otherwise, tax stamp will be anyway accounted, without charging customer.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/l10n-italy/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/l10n-italy/issues/new?body=module:%20l10n_it_account_stamp%0Aversion:%2016.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* Ermanno Gnan
* Sergio Corato
* Enrico Ganzaroli

Contributors
~~~~~~~~~~~~

* Lorenzo Battistini <https://github.com/eLBati>
* Sergio Corato
* Ermanno Gnan
* Enrico Ganzaroli
* Sergio Zanchetta <https://github.com/primes2h>
* Marco Colombo <https://github.com/TheMule71>
* Gianmarco Conte <gconte@dinamicheaziendali.it>
* Giovanni Serra <giovanni@gslab.it>

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

This module is part of the `OCA/l10n-italy <https://github.com/OCA/l10n-italy/tree/16.0/l10n_it_account_stamp>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
