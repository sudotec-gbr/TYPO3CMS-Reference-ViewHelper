.. include:: /Includes.rst.txt

.. _typo3-backend-modulelayout-button-linkbutton:

==============================
moduleLayout.button.linkButton
==============================


A ViewHelper for adding a link button to the doc header area.
It must be a child of :ref:`<be:moduleLayout> <typo3-backend-modulelayout>`.

Examples
--------

Default::

   <be:moduleLayout>
       <be:moduleLayout.button.linkButton
           icon="actions-add"
           title="Add record')}"
           link="{be:uri.newRecord(table: 'tx_my_table')}"
       />
   </be:moduleLayout>

Arguments
=========


.. _modulelayout.button.linkbutton_icon:
icon
----

:aspect:`DataType`
   string

:aspect:`Required`
   false
:aspect:`Description`
   Icon identifier for the button

.. _modulelayout.button.linkbutton_title:
title
-----

:aspect:`DataType`
   string

:aspect:`Required`
   false
:aspect:`Description`
   Title of the button

.. _modulelayout.button.linkbutton_disabled:
disabled
--------

:aspect:`DataType`
   mixed

:aspect:`Required`
   false
:aspect:`Description`
   Whether the button is disabled

.. _modulelayout.button.linkbutton_showlabel:
showLabel
---------

:aspect:`DataType`
   mixed

:aspect:`Required`
   false
:aspect:`Description`
   Defines whether to show the title as a label within the button

.. _modulelayout.button.linkbutton_position:
position
--------

:aspect:`DataType`
   string

:aspect:`Required`
   false
:aspect:`Description`
   Position of the button (left or right)

.. _modulelayout.button.linkbutton_group:
group
-----

:aspect:`DataType`
   integer

:aspect:`Required`
   false
:aspect:`Description`
   Button group of the button

.. _modulelayout.button.linkbutton_link:
link
----

:aspect:`DataType`
   string

:aspect:`Required`
   false
:aspect:`Description`
   Link for the button
