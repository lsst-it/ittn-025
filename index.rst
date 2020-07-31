..
  Technote content.

  See https://developer.lsst.io/restructuredtext/style.html
  for a guide to reStructuredText writing.

  Do not put the title, authors or other metadata in this document;
  those are automatically added.

  Use the following syntax for sections:

  Sections
  ========

  and

  Subsections
  -----------

  and

  Subsubsections
  ^^^^^^^^^^^^^^

  To add images, add the image file (png, svg or jpeg preferred) to the
  _static/ directory. The reST syntax for adding the image is

  .. figure:: /_static/filename.ext
     :name: fig-label

     Caption text.

   Run: ``make html`` and ``open _build/html/index.html`` to preview your work.
   See the README at https://github.com/lsst-sqre/lsst-technote-bootstrap or
   this repo's README for more info.

   Feel free to delete this instructional comment.

:tocdepth: 1

.. Please do not modify tocdepth; will be fixed when a new Sphinx theme is shipped.

.. sectnum::

.. TODO: Delete the note below before merging new content to the master branch.

.. note::

   **This technote is not yet published.**

   Fibers and copper deployed at La Serena

.. Add content here.


Introduction
================
 
 
In the following document and information to be provided, it is related to the installation, the material, and the location of the network points, such as fiber optics. This document will present information on the location of the points, quantity, and also the location and quantity of fiber filaments per floor. This document reflects how the physical network of the main building is built and how it is a project still under construction that may undergo changes in the future such as adding connection points and taking out. The materials used were selected for their quality and properties so that the project in its operation works at its maximum performance The fiber optic points single-mode cable was installed since in practice there is no transmission limit, only the equipment that transmits. The UTP S/FTP cable was selected for its properties to work at 10G / base T and all network points will be installed with this type of cable, both for AP and telephone connections. As for everything that is user cord is with UTP cat 6 cable On some occasions, the multimode cable will be installed, only on the occasions that the equipment needs it. 



.. figure:: /_static/Tabla.png 
    :name: Tabla
            :width: 700 px
            







Places To Treat The Document
----------------------------


- First Floor
- Second Floor


This document details the connections for both copper and fiber optic floors.

It is worth mentioning that all the fiber optic connections that are fed with a signal in the technical rooms come from the data center rack A1.

After meetings and conversations, a consensus is reached that each office will have 6 to 4 data point connections.

In some places, we have exceptions such as a visiting room that considers data points on the floor with the largest amount.

Also, Rubin's control room that sees many spots on the floor and on the walls.

All points are available in the diagram below.

Now the data points are mixed (it is not specified if they are data or phone since that will depend on the request and configuration on the switch).

The data points were installed according to a drawing that was submitted and approved.

In the document, we will find data points on the wall, on the ceiling, and on the floor.

The data points for the Access Points were delivered by the network engineer and at the same time from an optical signal monitoring program.

From the end of the construction of the building, some modifications were made to the installation of the data points, both by requests and by locations necessary for changes.

On the first floor as well as on the second floor, all points per floor reach their corresponding technical room.

In each technical room, it was considered to install 48 single-mode optical fibers and 48 multi-mode optical fibers in an optical terminal that is located in the upper part of the pedestal rack in each technical room.

As for the data points, they are different on the first floor and the second floor since they are not the same requests but they are very similar.



First Floor
============


On this floor, it consists of the following characteristics in terms of materials and numbering of network points.


- 181 Network points in total
- 7 Access Point



All data points start from the technical room.


First Floor Image
--------------------------


.. figure:: /_static/piso1.PNG 
    :name:piso 1
            :width: 700 px









https://confluence.lsstcorp.org/display/IT/Documentation+of+network+points+office+building+La+Serena+floor+1





The image shows a letter with the data point number and this letter corresponds to the numbering of the patch panel that connects the data point, for example:
1A to 24A / 25B to 48B / 49C to 72C. etc.)



Technical Room First Floor
---------------------------


In the technical room on the first floor, it consists of the following characteristics in terms of materials and numbering of network points.



- 181 Network points in total (in the patch panels}
- 8 Patch panel
- 4 48-port switch
- 2 PDUs (primary and backup)
- 1 42U Pedestal Rack
- 1 Optical terminal with 96 optical fibers (48 singlemode OS2 and 48 multimode OM3)


This room also houses the electrical equipment for the entire first floor and also the UPS that powers the network equipment.



Technical Room First Floor Images
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: /_static/tec1.PNG 
    :name: tec1
            :width: 700 px





Data Points Access Point First Floor
-------------------------------------

On the first floor, we find 7 access points installed in the locations that the network engineer gave us.
These locations are monitored with a program that certifies their propagation of signals from the access point.




Data Points Access Point First Floor Image
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: /_static/ap1.PNG 
    :name: ap1
            :width: 700 px









Second Floor
============



On this floor, it consists of the following characteristics in terms of materials and numbering of network points.



- 171 Network points in total
- 7 Access points


All data points start from the technical room.



Second Floor Image
--------------------------------------

.. figure:: /_static/piso2.PNG 
    :name: piso2
            :width: 700 px





https://confluence.lsstcorp.org/display/IT/Documentation+of+network+points+office+building+La+Serena+floor+2



The image shows a letter with the data point number and this letter corresponds to the numbering of the patch panel that connects the data point, for example:
1A to 24A / 25B to 48B / 49C to 72C. etc.)





Technical Room Second Floor
-----------------------------------------


In the technical room on the second floor, it consists of the following characteristics in terms of materials and numbering of network points.



- 171 Network points in total (in the patch panels}
- 8 Patch panel
- 4 48-port switch
- 2 PDUs (primary and backup)
- 1 42U Pedestal Rack
- 1 Optical terminal with 96 optical fibers (48 singlemode OS2 and 48 multimode OM3)


This room also houses the electrical equipment for the entire first floor and also the UPS that powers the network equipment.



Technical Room Second Floor Images
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^


.. figure:: /_static/tec2.png 
    :name: tec2
            :width: 700 px





Data Point Access Point First Floor
-------------------------------------


On the second floor, we find 7 access points installed in the locations that the network engineer gave us.
These locations are monitored with a program that certifies their propagation of signals from the access point.



Data Point Access Point First Floor
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^


.. figure:: /_static/ap2.PNG 
    :name: ap2
            :width: 700 px






.. Do not include the document title (it's automatically added from metadata.yaml).

.. .. rubric:: References

.. Make in-text citations with: :cite:`bibkey`.

.. .. bibliography:: local.bib lsstbib/books.bib lsstbib/lsst.bib lsstbib/lsst-dm.bib lsstbib/refs.bib lsstbib/refs_ads.bib
..    :style: lsst_aa
