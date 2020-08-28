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
 
 
The purpose of this document is to provide information related to the installation, materials used , network point areas and the amount of fiber filaments used per floor. This document also reflects how the physical network of the main building is built by putting an emphasis on the fact that the project is still undergoing construction and may undergo changes in the near future such as adding additional network points or removing those that are already in place. The materials used for this project were all selected based on their quality and technical properties so that when the project is in operations phase it will work at maximum performance. Single-mode fiber was selected and installed hence it provides an unlimited transmission limit, but this will only be used for the equipment that perform the function of transmitting (TX). It is also noted that UTP S/FTP cables were also selected due to the cable properties and ability of being able to work at 10GBASE-T speeds. All network points were installed with this type of cable, for both the access points and telephony connection systems. In regard to end user devices, UTP CAT6 was installed and last but not least it is important to mention that in some occasions, multi-mode fiber cable connections will be setup and installed for any technical equipment that requires it.  



.. figure:: /_static/Tabla.png 
    :name: Tabla
            :width: 700 px
            







Areas of interest
----------------------------


- First Floor
- Second Floor

The following documentation illustrates both copper and fiber optic connections installed both in the first and second floor of the new office building.

It is worth mentioning that all fiber optic connections that are fed with a signal in the technical rooms all come from the data center located in rack A1.

After several meetings and conversations, a consensus was made with the team that each office will support up to 6 data point connections.


There are some areas that are considered to be exceptions of course, these areas include the visiting room and the Rubin Observatory control room. Both of these areas have the largest amount of data points both mounted on the floor and walls.

All of these network data points are illustrated in the diagram below.

Please note that these network points are mixed, what this actually means is that these points are not predefined and set to be either data or VoIP. This will depend directly on the requirements made by the staff and the switch's configuration.

These data points were set up and installed based on an initial drawing that was submitted and approved.

This documentation will illustrate, the various network points along with its locations which include: floors, walls and ceilings.


The data points locations for the AP's or access points were delivered by the network engineer who used an optimal signal monitoring program to determine this.

When the construction of the building was finished, some of these network points that were already installed had undergone some modifications both by requests from personnel and by locations that required a change.

For both the first and second floor all network points located in these areas reach their corresponding technical room.

For each of these technical rooms, IT considered installing both 48 single-mode and 48 multi-mode optical fibers in an optical terminal that is located in the upper part of the pedestal rack for each one of these technical rooms.

In regard to the data point connections, these are different for both the first floor and the second floor hence they are similar but not the same request. 


First Floor
============


The first floor consists of the following characteristics in terms of materials and numbering of the network points.


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


The technical room inside the first floor consists of the following characteristics in terms of materials and the numbering used for the network points. 



- 181 Network points in total (in the patch panels)
- 8 Patch panel
- 4 48-port switch
- 2 PDUs (primary and backup)
- 1 42U Pedestal Rack
- 1 Optical terminal with 96 optical fibers (48 singlemode OS2 and 48 multimode OM3)


This room also houses the electrical equipment for the entire first floor and and the UPS systems that powers the network equipment.



Technical Room First Floor Images
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: /_static/tec1.png 
    :name: tec1
            :width: 700 px





Data Points / Access Points First Floor
-------------------------------------

In the first floor, we will find 7 access points installed in the locations instructed by the network engineer in charge. 

These areas were previously monitored with a program that certified the best locations for the propagation of the signals from these access points. 





Data Points Access Point First Floor Image
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: /_static/ap1.PNG 
    :name: ap1
            :width: 700 px









Second Floor
============



The second floor consists of the following elements in terms of materials and numbering of the various network points.



- 171 Network points in total
- 7 Access points


All data points start from the technical room.



Second Floor Image
--------------------------------------

.. figure:: /_static/piso2.PNG 
    :name: piso2
            :width: 700 px





https://confluence.lsstcorp.org/display/IT/Documentation+of+network+points+office+building+La+Serena+floor+2



The image shows a letter with a data point number and this letter corresponds to the numbering of the patch panel that connects the data point, for example:
1A to 24A / 25B to 48B / 49C to 72C. etc.)





Technical Room Second Floor
-----------------------------------------

The technical room, located inside the second floor contains the following characteristics in terms of materials and numbering used for the various network points. 


- 171 Network points in total (in the patch panels}
- 8 Patch panel
- 4 48-port switch
- 2 PDUs (primary and backup)
- 1 42U Pedestal Rack
- 1 Optical terminal with 96 optical fibers (48 singlemode OS2 and 48 multimode OM3)


This room also houses the electrical equipment for the entire first floor and the UPS systems that power the network equipment.



Technical Room Second Floor Images
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^


.. figure:: /_static/tec2.png 
    :name: tec2
            :width: 700 px





Data Point Access Point Second Floor
-------------------------------------

In the first floor of the building, we will find 7 access points installed in the locations assigned by the network engineer. 

These areas were previously monitored with a program that certified the best locations for the propagation of the signals from these access points. 



Data Point Access Point Second Floor
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^


.. figure:: /_static/ap2.PNG 
    :name: ap2
            :width: 700 px






.. Do not include the document title (it's automatically added from metadata.yaml).

.. .. rubric:: References

.. Make in-text citations with: :cite:`bibkey`.

.. .. bibliography:: local.bib lsstbib/books.bib lsstbib/lsst.bib lsstbib/lsst-dm.bib lsstbib/refs.bib lsstbib/refs_ads.bib
..    :style: lsst_aa
