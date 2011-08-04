#format dojo_rst

dojox.mobile.SpinWheelDatePicker
================================

:Authors: Yoshiroh Kamiyama
:Developers: Yoshiroh Kamiyama
:Available: since V1.7

.. contents::
    :depth: 2

SpinWheelDatePicker  is a date picker widget. It is a subclass of dojox.mobile.SpinWheel. It has the year, month, and day slots.

.. image:: SpinWheelDatePicker.png

=====
Usage
=====

SpinWheelDatePicker is in a separate module file from _base.js. You need to dojo.require SpinWheelDatePicker as below.

.. code-block :: javascript

  <link href="../themes/common/SpinWheel.css" rel="stylesheet">

  dojo.require("dojox.mobile.SpinWheelDatePicker");

========
Examples
========

Declarative example
-------------------

.. code-block :: html

  <div id="spin1" dojoType="dojox.mobile.SpinWheelDatePicker"></div>