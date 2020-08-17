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
 
 
The following documentation provides information related to the installation, materials used network point areas and the amount of fiber filaments used per floor. This document also reflects how the physical network of the main building is built, putting and emphasis on the fact that the project is still undergoing construction and may undergo changes in the near future such as adding additional network points or removing those that are already in place. The materials used were all selected based on their quality and technical properties so that when the project is in operations phase it will work at maximum performance. Single-mode fiber was selected and installed hence it provides an unlimited transmission limit, but this will only be used for the equipment that perform the function of transmitting (TX). It is also noted that UTP S/FTP cables were also selected due to their transmission properties and being able to work at 10G Base T speeds. All network points will be installed with this type of cable, for both the access points and telephony connections. In regard to end user devices, UTP CAT6 will be installed. It is also important to mention that in some occasions, multi-mode fiber cable connections will be setup and installed for any technical equipment that requires it.  



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
    :name: piso1
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

.. figure:: /_static/tec1.png 
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
