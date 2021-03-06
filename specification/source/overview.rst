Overview
========

The software to develop is a graphical user interface for editing Modelica models of HVAC and control systems. It relies on two main components.

#. A graphical user interface for editing Modelica classes in a diagrammatic form, see :numref:`sec_functionalities` and :numref:`sec_modelica_gui`.

#. A configuration widget supporting assisted modeling based on a simple HTML input form, see :numref:`sec_configuration_widget`. This widget is mostly needed for integrating advanced control sequences that can have dozens of I/O variables. The intent is to reduce the complexity to the mere definition of the system layout and the selection of standard control sequences already transcribed in Modelica.

We plan a phased development where

#. the configuration widget will be first implemented as part of Phase 1 and integrated into an existing graphical editor for Modelica,

#. the full-featured editor will be developed in a future phase, providing diagrammatic editing capabilities and integrating the configuration widget natively.


.. admonition:: Revision Note (11/2020)
   :class: danger

   The current version of the specification is limited to Phase 1. Each part related to the full-featured editor is provided for informative purposes only.


.. raw:: html

   <iframe src="_static/overview.html" width="100%" height="800px" frameBorder="0">


.. only:: latex

   .. figure:: img/overview_1.*

   .. figure:: img/overview_2.*

   .. figure:: img/overview_3.*

