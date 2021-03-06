*BGS Groundhog Desktop*

User Guide v2.1.0 (BETA)

July 2020

|image1|

|image2|\ |image3|

**© Copyright British Geological Survey (UKRI) 2020. All rights
reserved.**

This document is intended as a general guide to the operation of the BGS
Groundhog Desktop software (Groundhog) and no warranty is given as to
the completeness or accuracy of the information contained within. The
contents of this document are subject to change without notice.

Except for any third-party images and content, logos or other corporate
branding materials, this document is licensed under the UK Open
Government License.

http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/

Topographic basemap images used within this user guide use OS open data
layers. Contains OS Data © Crown Copyright and Database Right.

**Versions**

BGS Groundhog Desktop (Groundhog) is available in two versions badged
(1) **Community** and (2) **Professional**. Community is free-to-use
under the UK Open Government Licence. Professional has extended features
for building conceptual and 3D site and geological models and is
available under a commercial license via our UK commercial reseller,
Land Quality Management Ltd. (LQM).

**Contact Information**

BGS Groundhog Desktop (Groundhog) is software created and maintained by
the British Geological Survey. Further information about the development
project, and the software download, can be found on our website.

`www.bgs.ac.uk/groundhog <http://www.bgs.ac.uk/groundhog>`__

For general enquiries about the Groundhog project, please email us.

groundhog@bgs.ac.uk

**Distribution**

Licenses for Groundhog Professional are distributed by Land Quality
Management Ltd. (LQM). Further information can be obtained via their
website.

https://www.lqm.co.uk/csm/

judith@lqm.co.uk

|image4|\ |image5|

Contents
========

Introduction 6

`About Groundhog 7 <#about-groundhog>`__

`Installation 7 <#installation>`__

`First Use 8 <#first-use>`__

`Digital License Activation 8 <#digital-license-activation>`__

`Data Objects 10 <#data-objects>`__

`Object Tree 11 <#object-tree>`__

`Site / Project Folder 11 <#site-project-folder>`__

`Models Folder 15 <#models-folder>`__

`System Objects Folder 15 <#system-objects-folder>`__

`User Interface 18 <#user-interface>`__

`Main Panels 19 <#main-panels>`__

`Main Toolbar [1] 19 <#main-toolbar-1>`__

`Session Panel [2] 19 <#session-panel-2>`__

`Map Window [3] 20 <#map-window-3>`__

`Map Window Layer Control [4] 24 <#map-window-layer-control-4>`__

`Cross-Section Window [5] 27 <#cross-section-window-5>`__

`Cross-Section Window Layer Control [6]
29 <#cross-section-window-layer-control-6>`__

`Status Bar [7] 32 <#status-bar-7>`__

`Importing & Exporting Data 33 <#_Toc46143806>`__

`Images 34 <#images>`__

`Shapefiles 38 <#shapefiles>`__

`ASCII Grids 39 <#ascii-grids>`__

`OBJ Files 40 <#obj-files>`__

`Working With Borehole Logs 42 <#_Toc46143811>`__

`Borehole Data Import 43 <#borehole-data-import>`__

`CSV/TXT Format 43 <#csvtxt-format>`__

`Importing CSV 44 <#importing-csv>`__

`Importing Tabular Data 52 <#importing-tabular-data>`__

`Importing AGS Format Data 57 <#importing-ags-format-data>`__

`Importing LAS Format Data 58 <#importing-las-format-data>`__

`BGS Borehole Records 62 <#bgs-borehole-records>`__

`Displaying Boreholes 66 <#displaying-boreholes>`__

`Creating Borehole Log Templates
67 <#creating-borehole-log-templates>`__

`Editing Borehole Log Templates 68 <#editing-borehole-log-templates>`__

`Editing Borehole Data 85 <#editing-borehole-data>`__

`Drawing Points, Shapes & Annotations 92 <#_Toc46143823>`__

`Creating New Layers 93 <#creating-new-layers>`__

`Creating and Editing Point Layers
93 <#creating-and-editing-point-layers>`__

`Creating & Editing Shape Layers 97 <#creating-editing-shape-layers>`__

`Creating & Editing Annotation Layers
105 <#creating-editing-annotation-layers>`__

`Drawing Cross-Sections 114 <#drawing-cross-sections>`__

`Creating the Cross-Section Alignment
115 <#creating-the-cross-section-alignment>`__

`Creating Cross-Sections Without an Alignment
115 <#creating-cross-sections-without-an-alignment>`__

`Drawing a Polyline for the Alignment
115 <#drawing-a-polyline-for-the-alignment>`__

`Including Boreholes in the Cross-Section Alignment
117 <#including-boreholes-in-the-cross-section-alignment>`__

`Modifying the Alignment 117 <#modifying-the-alignment>`__

`Viewing and Editing the Cross-Section
120 <#viewing-and-editing-the-cross-section>`__

`Topographic Profile 121 <#topographic-profile>`__

`Viewing Boreholes 122 <#viewing-boreholes>`__

`Buffering Boreholes Into a Cross-Section
124 <#buffering-boreholes-into-a-cross-section>`__

`Registering Images in Cross-Section
125 <#registering-images-in-cross-section>`__

`Drawing Geology 127 <#drawing-geology>`__

`Developing Conceptual Site Models 135 <#_Toc46143840>`__

`Introduction 136 <#introduction-1>`__

`Constructing the Data Model 136 <#constructing-the-data-model>`__

`Creating Pollutant Linkages 138 <#creating-pollutant-linkages>`__

`Displaying a Network Diagram 140 <#displaying-a-network-diagram>`__

`Drawing CSM Objects in Map and Cross-Section
144 <#drawing-csm-objects-in-map-and-cross-section>`__

`Shapes 144 <#shapes>`__

`Annotations 145 <#annotations>`__

`Drawing Water Levels and Defining Aquifers
146 <#drawing-water-levels-and-defining-aquifers>`__

`Accessing Historic Maps 150 <#accessing-historic-maps>`__

`Building Geological Models 153 <#_Toc46143850>`__

`Intro 154 <#intro>`__

`Defining the Model Grid 154 <#defining-the-model-grid>`__

`Creating Model Layers 156 <#creating-model-layers>`__

`Additional Tools 177 <#additional-tools>`__

`3D Graphics 186 <#_Toc46143855>`__

`About 187 <#about>`__

`First Use 187 <#first-use-1>`__

`User Interface 187 <#user-interface-1>`__

`The control panel 188 <#the-control-panel>`__

`Layer Control 188 <#layer-control>`__

`Object Explorer 190 <#object-explorer>`__

`Clipping Controls 190 <#clipping-controls>`__

`Configurations 192 <#configurations>`__

`The Hot Bar 193 <#the-hot-bar>`__

`The Scene 193 <#the-scene>`__

`Settings 194 <#settings>`__

`Borehole Settings 194 <#borehole-settings>`__

`Saving 195 <#saving>`__

`Cross Sections 196 <#cross-sections>`__

`Models 196 <#models>`__

`Surfaces 196 <#surfaces>`__

`Videos 196 <#videos>`__

`Configurations 197 <#configurations-1>`__

Introduction
============

This section provides an overview of Groundhog and information about how
to install the software and activate a license.

|image6|

*Photo by Hosea Georgeson on Unsplash*

About Groundhog
---------------

BGS Groundhog Desktop (Groundhog) is geological software created and
maintained by a team at the British Geological Survey. It is available
in two versions, (1) **Community** and (2) **Professional**.

**Community** is free-to-use, including for commercial applications,
under the UK Open Government Licence. You can use it to import and
explore your site geological data such as maps and boreholes. It allows
you to create custom borehole log templates, develop map line-work and
draw geological cross-sections.

**Professional** includes all of the features of Community and adds a
range of modelling capability. Use it to create annotated, conceptual
site models. You can also use it to develop full 3D geological framework
models. Professional requires a digital activation key which is
available from our commercial reseller, Land Quality Management
`www.lqm.co.uk <http://www.lqm.co.uk>`__

This user guide covers both versions. Please note that not all features
described here are available in all versions of the software. Where a
particular feature relates only to the Groundhog Professional version it
will be highlighted like this:

*Professional*

Groundhog is currently BETA software and not all of the available
features of Groundhog are necessarily documented in this guide. Whilst
considerable effort has gone into its design and testing, please be
aware that the software is still in very active development and may not
be completely stable in all situations. We are very happy to receive
feedback from users by email groundhog@bgs.ac.uk

A basic set of tutorial videos is available at;

https://www.youtube.com/channel/UCQc4rWxP2sMPNFhHq6xOthQ/videos

Installation
------------

**Please read all steps carefully to ensure correct installation of
Groundhog!**

You can obtain the installer for Groundhog from the BGS website. There
is only one installer, you do not need a separate installer for
Community and Professional because the two versions are controlled by
the digital license which is available from Land Quality Management.

`www.bgs.ac.uk/groundhog <http://www.bgs.ac.uk/groundhog>`__

`www.lqm.co.uk <http://www.lqm.co.uk>`__

Groundhog can only be installed on Windows computers. There are no
specific minimum system requirements to run Groundhog, but you may find
the 3D graphics capability performs better on a computer with a
dedicated graphics card.

The download is in ZIP archive format which contains an installer
executable (setup.exe). Extract the contents of the ZIP file to a
temporary location.

<Right-click> on the <setup.exe> file and choose <Run as administrator>

**IMPORTANT:** Depending on your organisation’s security policies you
may need assistance from your IT support department to carry out the
software install.

The installation wizard guides you through a series of screens.

You will be prompted to choose an **installation folder**, which is
usually C:\Program Files\BGS Groundhog Desktop, but you can install
Groundhog wherever you prefer.

First Use
---------

The first time you start Groundhog you will see a screen like this.

|image7|

If you have previously used Groundhog, you may already have a Groundhog
Home area set up on your computer. However, there have been many changes
in this release, so it is advisable to create a new area, which will
enable Groundhog to copy into this area all the files that are required
for successful running of Groundhog. You may have files which you wish
to keep in your previous Groundhog home area. These can be copied across
to your new Groundhog home area after the install process has completed.

Once you have provided a valid, writable area for the Groundhog home
folder, Groundhog will copy the required folders and files from the
install area to here and Groundhog will be ready to use. If you had
previously upgraded Groundhog to Professional and this is not
automatically enabled in your new Groundhog version, please contact the
Groundhog team.

Digital License Activation
--------------------------

Groundhog will automatically run in Community mode right away. There is
no need to activate this version in any way. You can get started using
it immediately and use it for as long as you like. We do humbly request
that you consider acknowledging your use of Groundhog in your projects
because this helps our project gain exposure, but you do not have to!

If you are upgrading to the Professional version of Groundhog you will
need a digital activation key. Keys can be obtained from our commercial
reseller, Land Quality Management Ltd.

`www.lqm.co.uk <http://www.lqm.co.uk>`__

When you purchase your digital license for Groundhog Professional you
will be asked for your email address. This information is only used for
the purposes of generating a unique digital key and is not stored
anywhere except on your own computer as part of the procedure.

By return you will receive an email containing a digital license
activation key. Start Groundhog and select <Help> <Licensing> <Activate
Professional Edition> from the main menu button.

|image8|

When prompted, enter your email address and the digital key you
received. |image9|

Once activated you will need to re-start Groundhog to switch to
Professional mode. From now on, Groundhog will run in Professional mode
for the duration of you license.

If you experience any difficulties with your activation, please contact
the person who issued your digital key by email.

Data Objects
============

This section provides an overview of the key data object types supported
by Groundhog, where they are held in the project structure and how to
both create and import your own data structures into a Groundhog
project.

|image10|

*Photo by João Silas on Unsplash*

Object Tree
-----------

Project data is held as various objects within the object tree. The
object tree is found along the left side of the main user interface
under the <Workspace> tab. For more details on the other components of
the user interface please refer to the next main section of the user
guide.

|image11|

This tree panel is a typical multi-level object structure, like a
Windows file explorer navigation panel. Expand the various folder nodes
to explore your data at different levels. Note that not all folder nodes
are available in all versions of Groundhog.

The object tree is arranged into three top-level folders.

|image12|

Site / Project Folder
~~~~~~~~~~~~~~~~~~~~~

Contains the key site investigation data types such as GIS-style point
and shape layers, borehole data, cross-sections, project phase and CSM
information, annotations and linked files such as images.

|image13|

Location Layers Folder
^^^^^^^^^^^^^^^^^^^^^^

This folder holds both GIS-style point layers and also borehole dataset
layers. Borehole layers are effectively treated as a special flavour of
point layer, which is why they are grouped together as Location Layers.

Make new, empty layers using <right-click> <New Layer>.

|image14|

Enter a name.

|image15|

Click <Yes> if you want to make a layer for boreholes, click <No> to
make a layer for point data.

|image16|

This is the effect of doing both a borehole layer and a point layer.
Note the different icons.

|image17|

In the case of boreholes, a <Right-Click> option allows for data import.
For more details on data import see the main user guide chapter
**Importing & Exporting Data**.

|image18|

Shape Layers Folder
^^^^^^^^^^^^^^^^^^^

This folder holds GIS-style shape layers (lines and polygons). Groundhog
makes no distinction between lines and polygons, so they are grouped
together into generic shape layers.

Make new, empty layers using <right-click> <New Layer>

|image19|

Enter a name.

|image20|

Empty layer is added to the folder.

|image21|

Cross-Sections Folder
^^^^^^^^^^^^^^^^^^^^^

This is where drawn cross-sections will appear. At the moment, Groundhog
stores all of these in a single folder. Typically you will create new
cross-sections by drawing them in the map – please refer to the
**Drawing Cross-Sections** chapter of the user guide for more
information. However, it is possible to create non-spatially referenced
cross-section objects directly from the tree if you just want to draw a
cross-section without placing it in the map context via <right-click>
<Tools> <Create New Cross-Section>.

|image22|

Enter a name.

|image23|

Specify a length in metres.

|image24|

|image25|

Cross-sections created in this way are all registered starting at [0, 0]
grid coordinates.

Annotations Folder
^^^^^^^^^^^^^^^^^^

Annotations layers hold labels, callouts and graphics icons to label and
represent objects within the project or the conceptual site model.
Create a new layer for holding annotation objects via <Right-Click> <New
Layer>.

*Professional*

|image26|

Enter a name.

|image27|

|image28|

Annotation layers can be created and edited in Professional mode and
viewed in Community mode.

Phases Folder
^^^^^^^^^^^^^

The phases folder is specific to developing conceptual site models
(CSMs) in Groundhog. For more details please refer to the **Developing
Conceptual Site Models** chapter of the user guide. Phases hold the
structure for the CSM, allowing multiple CSMs to be developed and
related back to different phases of a project or site development.
Create a new layer for holding phase objects via <Right-Click> <New
Phase>.

*Professional*

|image29|

Associated Files Folder
^^^^^^^^^^^^^^^^^^^^^^^

Certain types of imported file will appear in this folder when they are
imported. A good example is imported image files which have their own
specific sub-folder.

|image30|

Models Folder
~~~~~~~~~~~~~

Contains the key data types related to 2.5D and 3D models and related
information.

|image31|

Layer Models Folder
^^^^^^^^^^^^^^^^^^^

This folder holds layer-based 3D geological models as well as other
types of more 2.5D models such as surface or gridded property models
such as water levels or chemical concentration maps. In Community mode
this folder will display the available models in an existing project. In
Professional mode you are able to create new models and edit existing
models. Creating models is an in-depth topic. Please refer to the
chapter on **Building Geological Models** in this user guide for more
information.

*Professional*

Reference Grids Folder
^^^^^^^^^^^^^^^^^^^^^^

This folder holds any loaded grid layers. Typically, these are imported
from ESRI ASCII grid format. Examples include DEM or DTM layers that you
wish to use as topographic profiles for cross-section drawing and for
acting as the topographic cap of 3D geological models. You can also
bring in other layers such as water levels and engineering layers and
display these in various ways within the software. For more information
on how to get grid data into Groundhog workspaces and projects please
refer to the Importing and Exporting Data section of this user guide.

Modelled Objects Folder
^^^^^^^^^^^^^^^^^^^^^^^

This folder can be used to hold reference 3D objects such as models of
infrastructure and buildings and other site objects. These objects can
then be visualized using the 3D graphics window. Typically, such objects
are imported from an OBJ file. Note that OBJ files can only be viewed
using the 3D graphics window in Groundhog.

System Objects Folder
~~~~~~~~~~~~~~~~~~~~~

This folder stores system-level objects which are typically available
across all of your Groundhog projects.

|image32|

Pick Lists Folder
^^^^^^^^^^^^^^^^^

This folder holds pick list or dictionary objects. These are pre-set
lists of values and descriptions that are used in various places within
Groundhog to perform lookups. Although you can define your own pick
lists, typically you do not need to interact with this folder in the
current version of Groundhog. Examples include a pick list of possible
contaminants for conceptual site models, or dictionary lookups for
geotechnical data in AGS format.

|image33|

|image34|

Templates Folder
^^^^^^^^^^^^^^^^

This folder holds borehole log templates. When Groundhog is first
installed it will only contain a couple of default templates. You can
add your own blank Template objects and then design them using the log
window. For more information on how to design your own log templates
please refer to the **Working With Borehole Logs** chapter of this user
guide.

To make a new template use <right-click> <New Template>.

|image35|

Enter a name.

|image36|

If Project is selected, this template will be saved when you save the
project and will be available to this project only. Otherwise, when you
choose to save this template, it will be saved in the Ground Home
WORKSPACE folder and will be available to all projects in the future.

The new template is added to the folder and is ready to be worked on.

|image37|

Web Map Services Folder
^^^^^^^^^^^^^^^^^^^^^^^

This folder lists the available Web Map Services (WMS) in the workspace.
Groundhog comes pre-loaded with BGS WMS layers and these will always be
listed here, so long as Groundhog was able to load them at start up
(requires an internet connection). Typically you will not interact with
the object in this folder directly, but you will be able to add them as
layers to map window.

User Interface
==============

This section provides an overview of the graphical user interface and
key panels and buttons within Groundhog.

|image38|

*Original photo by Kobu Agency on Unsplash*

Main Panels
-----------

The Groundhog user interface is arranged into a number of panels
containing data objects and graphics. Because Groundhog is a highly
interactive graphical tool you will benefit significantly from using a
good-quality mouse equipped with a mouse wheel – a laptop track-pad is
not a good match with Groundhog.

|image39|

Main Toolbar **[1]**
~~~~~~~~~~~~~~~~~~~~

Contains high-level buttons for key operations.

+-----------+-----------------+--------------------------------------+
| |image50| | Main Menu       | This is the main menu button         |
|           |                 | providing access to a series of      |
|           |                 | high-level functions such as         |
|           |                 | import/export.                       |
+===========+=================+======================================+
| |image51| | Open Project    | Opens a file chooser for opening     |
|           |                 | Groundhog projects in the \*.gop     |
|           |                 | file format.                         |
+-----------+-----------------+--------------------------------------+
| |image52| | Save Project    | Opens a file chooser for saving the  |
|           |                 | current session to a Groundhog       |
|           |                 | \*.gop file format.                  |
+-----------+-----------------+--------------------------------------+
| |image53| | Open Map Window | Allows the creation of a new map     |
|           |                 | (plan-view) window. When you create  |
|           |                 | a new map window you will be         |
|           |                 | prompted to select the data layers   |
|           |                 | you want to see in the window. The   |
|           |                 | available layers will depend on the  |
|           |                 | data contained within your workspace |
|           |                 | or project. Press <Skip> to open a   |
|           |                 | blank window.                        |
+-----------+-----------------+--------------------------------------+
| |image54| | Open 3D Window  | Opens the 3D graphics window.        |
+-----------+-----------------+--------------------------------------+

Session Panel **[2]**
~~~~~~~~~~~~~~~~~~~~~

A tabbed panel containing a range of session-level objects.

|image55|

Workspace
^^^^^^^^^

This contains the main Object Tree panel with a hierarchical list of all
data objects in the session. For more details please refer to the Object
Tree section of this user guide.

Library
^^^^^^^

|image56|\ A panel containing a configurable library of available
drawing codes (geology codes and other special codes). Single-click on
an entry to select it as the active drawing code – this sets the code as
active in all windows. The below example shows “BOULDERS” as the
selected drawing code. Note that the special codes “SHAPE” and “FAULT”
are always at the top, and the rest of the list is sorted
alphabetically. Type into the search box to find codes. Click <All> to
reset the list back to all values after searching.

|image57|

+-----------+--------------+-----------------------------------------+
| |image66| | Add Code     | Add a drawing code, and optionally a    |
|           |              | matching colour, to the library.        |
+===========+==============+=========================================+
| |image67| | Add Colour   | Add a colour value to the library.      |
+-----------+--------------+-----------------------------------------+
| |image68| | Save Codes   | Saves all current drawing codes to the  |
|           |              | global workspace.                       |
+-----------+--------------+-----------------------------------------+
| |image69| | Save Colours | Saves all current colour values to the  |
|           |              | global workspace.                       |
+-----------+--------------+-----------------------------------------+

Time Controls
^^^^^^^^^^^^^

Where data and models have time-stamp information it is possible to use
this as a filter for selective display of a particular time interval
within the project. For example, you may have water level readings with
time-stamps in your borehole data which can be displayed and animated
with time. These features are currently undocumented. Please contact
groundhog@bgs.ac.uk for information.

|image70|

Map Window **[3]**
~~~~~~~~~~~~~~~~~~

A tabbed component capable of displaying multiple map panels. Each map
panel can display map data layers and can be used for digitizing points
and shapes, constructing cross-section alignments and for placing
borehole locations.

When you create a new map window you will be prompted to select the data
layers you want to see in the map. The icons for each layer indicate the
layer’s data type. The available layers will depend on what data you
have in your workspace and project.

|image71|

The panel on the left shows data layers in the session and the panel on
the right typically displays any web map services that are available.
Single-click on individual entries to select them. If you want to select
multiple layers hold the CTRL key, or to select a range of layer hold
the SHIFT key, as-per typical list controls in Windows programs.

Some layers are ALWAYS available, including **Cross-Sections** (the
default cross-sections folder) and **Graticule** (a grid overlay with
scale bar and north arrow).

You will also have the option here to **Create New Layer**.

When you save your project it will store the configuration and scale of
all opened map windows ready for your next session.

When you are working in the map view, if you are working in the UK it is
a good idea to always add the default **Topographic Basemap** layer that
is included with Groundhog for orientation purposes. Otherwise, you may
wish to import a geo-registered image of your site/project area for the
same purpose.

General Navigation
^^^^^^^^^^^^^^^^^^

Each graphics panel works like most interactive online map applications.
The mouse is inherently multi-mode, reducing the need to constantly
select different tools to pan and zoom. Click and hold mouse button 1
(typically the left button) and drag the mouse to pan the map around.
Use the mouse wheel to zoom in and out (a good mouse wheel is very
important for effective Groundhog operation). The mouse zoom is
dynamically targeted to the mouse cursor position, allowing for very
rapid and precise zoom in from small scale to large scale maps.

Certain types of object such as cross-sections and boreholes can be
previewed or queried by holding down the SHIFT key whilst hovering over
the object. Here is an example of hovering over a cross-section
alignment whilst holding the SHIFT key.

|image72|

Toolbar
^^^^^^^

|image73|

+-----------+---------------------+----------------------------------+
| |image94| | Zoom To Extent      | Zooms to the full extent of all  |
|           |                     | layers in the map panel, or to   |
|           |                     | the currently active layer, if   |
|           |                     | one is selected.                 |
+===========+=====================+==================================+
| |image95| | Zoom In             | Incrementally zooms the map to a |
|           |                     | larger scale with each           |
|           |                     | successive click.                |
+-----------+---------------------+----------------------------------+
| |image96| | Zoom Out            | Incrementally zooms the map to a |
|           |                     | smaller scale with each          |
|           |                     | successive click.                |
+-----------+---------------------+----------------------------------+
| |image97| | Gazetteer           | Search for places (UK only) by   |
|           |                     | place name, street+placement or  |
|           |                     | county. Examples:                |
|           |                     |                                  |
|           |                     | “Nottingham”                     |
|           |                     |                                  |
|           |                     | “Main Street, Keyworth”          |
|           |                     |                                  |
|           |                     | “Rutland”                        |
+-----------+---------------------+----------------------------------+
| |image98| | Select Drawing Code | Click to open the drawing code   |
|           |                     | library panel in order to change |
|           |                     | the active drawing code. Also    |
|           |                     | displays the currently active    |
|           |                     | drawing code, including its      |
|           |                     | colour and ornament if they are  |
|           |                     | available.                       |
+-----------+---------------------+----------------------------------+
| |image99| | Print               | Send the current map view to a   |
|           |                     | printer.                         |
+-----------+---------------------+----------------------------------+
| |         | Save Image          | Save the current map view to an  |
| image100| |                     | image (JPEG or PNG).             |
+-----------+---------------------+----------------------------------+
| |         | Save PDF            | Save the current map view to a   |
| image101| |                     | PDF document.                    |
+-----------+---------------------+----------------------------------+
| |         | Toggle Slider       | The layer slider allows partial  |
| image102| |                     | view of a user-defined           |
|           |                     | collection of map data layers    |
|           |                     | for rapid comparison. With the   |
|           |                     | slider toggled on, use the mouse |
|           |                     | to drag the slider position in   |
|           |                     | the map panel. The below example |
|           |                     | shows the BGS geology map WMS    |
|           |                     | active as the active slider      |
|           |                     | layer on top of a topographic    |
|           |                     | basemap. For information about   |
|           |                     | how to make a particular layer   |
|           |                     | active in the slider refer to    |
|           |                     | the section on the Map Window    |
|           |                     | Layer Control below.             |
|           |                     |                                  |
|           |                     | |image103|                       |
+-----------+---------------------+----------------------------------+

Right-Click Operations
^^^^^^^^^^^^^^^^^^^^^^

The map panel supports a number of context-sensitive right-click
operations. These will depend on whether you are right-clicking on a
specific data object such as a cross-section alignment or a point
object, or whether you are in a “whitespace” area (a non-specific
portion of the panel). In general, a “whitespace” click will present the
following options.

|image104|

+--------------------+------------------------------------------------+
| Centre The Map     | Enter a [X, Y] coordinate to centre the map at |
|                    | a specific location.                           |
+====================+================================================+
| Set Map Scale      | Enter a value to zoom the map to an            |
|                    | approximate scale. For example, enter “10000”  |
|                    | to scale to 1:10k. Note that the exact scaling |
|                    | is dependent on screen resolution.             |
+--------------------+------------------------------------------------+
| Find A Place       | (Gazetteer) Search for places (UK only) by     |
|                    | place name, street+place name or county.       |
|                    | Examples:                                      |
|                    |                                                |
|                    | “Nottingham”                                   |
|                    |                                                |
|                    | “Main Street, Keyworth”                        |
|                    |                                                |
|                    | “Rutland”                                      |
+--------------------+------------------------------------------------+
| Show Grid Info     | Show UK grid reference for the mouse cursor    |
|                    | position, e.g. |image107|                      |
+--------------------+------------------------------------------------+
| Site Investigation | Currently contains one option to hyperlink out |
|                    | to the historic map(s) available from the NLS  |
|                    | for the clicked-on location. For more          |
|                    | information please refer to the main section   |
|                    | on developing conceptual site models.          |
+--------------------+------------------------------------------------+

Map Window Layer Control **[4]**
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

When you create a new map window you will be prompted to select which
data layers you want to add to the window. You can add layers layer on
too. The layers you choose will be added to this layer control panel.
The panel also has its own toolbar.

.. _toolbar-1:

Toolbar
^^^^^^^

|image108|

+------------+-------------------+-----------------------------------+
| |image121| | Add Layers        | Opens a list of available layers  |
|            |                   | that can be added to the map.     |
|            |                   | Note that the list does not       |
|            |                   | present layers which are already  |
|            |                   | in the map.                       |
+============+===================+===================================+
| |image122| | Undo              | Undo on the last operation.       |
|            |                   | **IMPORTANT:** please note that   |
|            |                   | the undo only becomes active when |
|            |                   | a data layer is made active –     |
|            |                   | i.e., the undo is layer-specific. |
+------------+-------------------+-----------------------------------+
| |image123| | Redo              | Redo on the last operation.       |
|            |                   | **IMPORTANT:** please note that   |
|            |                   | the redo only becomes active when |
|            |                   | a data layer is made active –     |
|            |                   | i.e., the redo is layer-specific. |
+------------+-------------------+-----------------------------------+
| |image124| | Remove All Layers | Clears the map of all data        |
|            |                   | layers.                           |
+------------+-------------------+-----------------------------------+
| |image125| | Window Settings   | Access high-level settings for    |
|            |                   | the map window.                   |
+------------+-------------------+-----------------------------------+
| |image126| | Background Colour | Change the background colour of   |
|            |                   | the map panel. This can be useful |
|            |                   | for improving clarity of certain  |
|            |                   | types of data.                    |
+------------+-------------------+-----------------------------------+

Layers
^^^^^^

The layers panel lists all currently loaded layers within the map
window. Different map windows can have different layers loaded.

|image127|

Checking the main tick-box on and off controls the visibility of each
layer. In the example below, **Topographic Basemap** is not visible in
the map panel, and **Graticule** is.

|image128|

The slider controls under the name of each layer control the
transparency of the layers. Slide the bar all the way to the left to
make the layer completely transparent. Slide the bar all the way to the
right to make the layer completely opaque.

|image129|

Single-click on a layer to make it the active layer. Depending on the
layer type this may activate drawing/editing tools, query tools, or it
may do nothing. When a layer is active it displays in orange. Only one
layer can be active at a time. Single-click on the active layer to
de-activate it. The example below shows the Cross-Sections layer as
active.

|image130|

The order of the layers in the panel dictates the drawing order in the
map panel. The layer at the top of the list will be drawn as the top
layer in the map graphics panel. The exception to this is that the
active layer is always drawn on top of everything else.

To change the drawing order of a layer, single-click and hold on the
layer, and drag it to re-position it in the list. In the example below,
the Cross-Sections layer is being dragged upwards.

|image131|

Each layer has four buttons on the right-hand side of its row.

|image132|

+----------------------+---------------------+----------------------+
| |image143|           | Settings            | Access               |
|                      |                     | layer-specific       |
|                      |                     | settings.            |
+======================+=====================+======================+
| |image144|           | Toggle Slider Layer | Toggles the layer in |
| |image145|           |                     | and out of the       |
|                      |                     | active slider layer  |
|                      |                     | (see above for       |
|                      |                     | information about    |
|                      |                     | the slider           |
|                      |                     | controls). When the  |
|                      |                     | toggle button is     |
|                      |                     | orange it means the  |
|                      |                     | layer is active in   |
|                      |                     | the slider.          |
+----------------------+---------------------+----------------------+
| |image146|           | Filter              | At the moment this   |
|                      |                     | button is disabled   |
|                      |                     | for all layers       |
|                      |                     | pending future       |
|                      |                     | filtering            |
|                      |                     | capability.          |
+----------------------+---------------------+----------------------+
| |image147|           | Remove              | Removes the layer    |
|                      |                     | from the current     |
|                      |                     | window (does **not** |
|                      |                     | delete the layer     |
|                      |                     | from the project!)   |
+----------------------+---------------------+----------------------+

There are a number of operations available by right-clicking in any
blank or “whitespace” portion of the layer control.

|image148|

**Add Layers** is the same as the Add Layers button at the top of the
layer control panel. The other options allow for the creation of new
data layers directly in the map, but (depending on version) are
currently restricted to Point, Borehole, Shape and Annotation*.

\* *Professional*

Active Layer: Draw, Edit & Identify
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Depending on the type of the layer certain editing, drawing and querying
operations may be available on the active map layer. When a layer can be
edited or drawn into it typically presents a tool palette in the map
graphics panel when the layer becomes active. The example below shows
the palette which has appeared in the top-left of the map panel by
making a shape layer active in the layer control.

|image149|

You can move the palette around in the map panel by dragging the green
bar along the top of the box. Note that the palette becomes less
transparent when the mouse cursor is over it.

|image150|

For more detailed information on the various tools available in the
palette, depending on the layer type, please refer to the section
**Drawing Points & Shapes** within this user guide.

When a layer is active you may see variations on the right-click option
available in the map window and also depending on whether you have
right-clicked on an object or whitespace.

Some layers have identify capability when they are active. The identify
operation is not a separate tool within groundhog – instead, with a
layer active, just single-click on an object or location. A good example
is the BGS WMS layers where the identify is active everywhere on the
geology map. If the identify query yields results they will be displayed
in the lower half of the map window layer control.

|image151|

Notice the two options circled in red. These are **Copy the identify
data to the clipboard** and **Add the lexicon code to the library
panel**.

Cross-Section Window **[5]**
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

A tabbed component capable of displaying multiple cross-section panels.
Each cross-section panel can display profile data layers and can be used
for drawing geological interpretations, viewing borehole transects and
digitizing points and shapes. Unlike the map window, you can’t just
create a new, empty window. To open a section window you must open a
specific cross-section object. You can do this either by double-clicking
on its entry in the object tree, or by right-click on the section
alignment in a map window.

When you open a cross-section in the cross-section window, some data
layers are ALWAYS available, including **Terrain Profile** (the
topographic profile for the cross-section), **Geology** (for drawing a
geological interpretation), **Graticule** (a grid overlay with scale
bars) and **Boreholes** (even if there are no boreholes in the
alignment).

When you save your project it will store the configuration and scale of
all opened cross-section windows ready for your next session.

.. _general-navigation-1:

General Navigation
^^^^^^^^^^^^^^^^^^

Each graphics panel works like most interactive online map applications.
The mouse is inherently multi-mode, reducing the need to constantly
select different tools to pan and zoom. Click and hold mouse button 1
(typically the left button) and drag the mouse to pan the cross-section
around. Use the mouse wheel to zoom in and out (a good mouse wheel is
very important for effective Groundhog operation). The mouse zoom is
dynamically targeted to the mouse cursor position, allowing for very
rapid and precise zoom in from small scale to large scale views.

.. _toolbar-2:

Toolbar
^^^^^^^

|image152|

+------------+---------------------------+---------------------------+
| |image175| | Vertical Exaggeration     | Sets the vertical         |
|            |                           | exaggeration for the      |
|            |                           | panel. Contains a list of |
|            |                           | pre-set values and can    |
|            |                           | also be typed into for    |
|            |                           | custom values.            |
+============+===========================+===========================+
| |image176| | Zoom To Extent            | Zooms to the full extent  |
|            |                           | of all the cross-section. |
+------------+---------------------------+---------------------------+
| |image177| | Marquee Zoom              | Draw a box to zoom to     |
|            |                           | that area of the panel.   |
+------------+---------------------------+---------------------------+
| |image178| | Incrementally zooms the   | Incrementally zooms the   |
|            | panel to a smaller scale  | cross-section to a        |
|            | with each successive      | smaller scale with each   |
|            | click.                    | successive click.         |
+------------+---------------------------+---------------------------+
| |image179| | Refresh                   | Refreshes the graphics    |
|            |                           | panel.                    |
+------------+---------------------------+---------------------------+
| |image180| | Select Drawing Code       | Click to open the drawing |
|            |                           | code library panel in     |
|            |                           | order to change the       |
|            |                           | active drawing code. Also |
|            |                           | displays the currently    |
|            |                           | active drawing code,      |
|            |                           | including its colour and  |
|            |                           | ornament if they are      |
|            |                           | available.                |
+------------+---------------------------+---------------------------+
| |image181| | Print                     | Send the current          |
|            |                           | cross-section view to a   |
|            |                           | printer.                  |
+------------+---------------------------+---------------------------+
| |image182| | Save Image                | Save the current          |
|            |                           | cross-section view to an  |
|            |                           | image (JPEG or PNG).      |
+------------+---------------------------+---------------------------+
| |image183| | Save PDF                  | Save the current          |
|            |                           | cross-section view to a   |
|            |                           | PDF document.             |
+------------+---------------------------+---------------------------+
| |image184| | Toggle Slider             | The layer slider allows   |
|            |                           | partial view of a         |
|            |                           | user-defined collection   |
|            |                           | of cross-section data     |
|            |                           | layers for rapid          |
|            |                           | comparison. With the      |
|            |                           | slider toggled on, use    |
|            |                           | the mouse to drag the     |
|            |                           | slider position in the    |
|            |                           | graphics panel. The below |
|            |                           | example shows the Geology |
|            |                           | layer as the active       |
|            |                           | slider layer on top of a  |
|            |                           | Terrain Profile layer.    |
|            |                           | For information about how |
|            |                           | to make a particular      |
|            |                           | layer active in the       |
|            |                           | slider refer to the       |
|            |                           | section on the            |
|            |                           | Cross-Section Window      |
|            |                           | Layer Control below.      |
|            |                           |                           |
|            |                           | |image185|                |
+------------+---------------------------+---------------------------+

.. _right-click-operations-1:

Right-Click Operations
^^^^^^^^^^^^^^^^^^^^^^

The map panel supports a number of context-sensitive right-click
operations. These will depend on whether you are right-clicking on a
specific data object such as a geology line or a shape object, or
whether you are in a “whitespace” area (a non-specific portion of the
panel). In general, a “whitespace” click will present the following
options.

|image186|

+----------------------+----------------------------------------------+
| Create Line [CODE]   | Allows creation of a fixed-elevation geology |
|                      | line using the currently active drawing      |
|                      | code.                                        |
+======================+==============================================+
| New Shape Layer      | Creates a new cross-section shape layer      |
|                      | which you can draw into.                     |
+----------------------+----------------------------------------------+
| New Annotation Layer | Creates a new annotation layer which can be  |
|                      | used to add labels, arrows and graphics to   |
|                      | the cross-section.                           |
|                      |                                              |
|                      | *Professional*                               |
+----------------------+----------------------------------------------+

Cross-Section Window Layer Control **[6]**
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

This panel lists the data layers which are currently added to the
cross-section window. The panel also has its own toolbar.

.. _toolbar-3:

Toolbar
^^^^^^^

|image187|

+------------+-------------------+-----------------------------------+
| |image198| | Add Layers        | Opens a list of available layers  |
|            |                   | that can be added to the window.  |
|            |                   | Note that the list does not       |
|            |                   | present layers which are already  |
|            |                   | in the list.                      |
+============+===================+===================================+
| |image199| | Undo              | Undo on the last operation.       |
|            |                   | **IMPORTANT:** please note that   |
|            |                   | the undo is global across all     |
|            |                   | layers.                           |
+------------+-------------------+-----------------------------------+
| |image200| | Redo              | Redo on the last operation.       |
|            |                   | **IMPORTANT:** please note that   |
|            |                   | the redo is global across all     |
|            |                   | layers.                           |
+------------+-------------------+-----------------------------------+
| |image201| | Window Settings   | Access high-level settings for    |
|            |                   | the cross-section window.         |
+------------+-------------------+-----------------------------------+
| |image202| | Background Colour | Change the background colour of   |
|            |                   | the graphics panel. This can be   |
|            |                   | useful for improving clarity of   |
|            |                   | certain types of data.            |
+------------+-------------------+-----------------------------------+

.. _layers-1:

Layers
^^^^^^

The layers panel lists all currently loaded layers within the
cross-section window. Different windows can have different layers
loaded.

|image203|

Checking the main tick-box on and off controls the visibility of each
layer. In the example below, **Terrain Profile** is not visible in the
section panel, and **Graticule** is.

|image204|

The slider controls under the name of each layer control the
transparency of the layers. Slide the bar all the way to the left to
make the layer completely transparent. Slide the bar all the way to the
right to make the layer completely opaque.

|image205|

Single-click on a layer to make it the active layer. Depending on the
layer type this may activate drawing/editing tools, query tools, or it
may do nothing. When a layer is active it displays in orange. Only one
layer can be active at a time. Single-click on the active layer to
de-activate it. The example below shows the **Geology** layer as active.

|image206|

The order of the layers in the panel dictates the drawing order in the
cross-section panel. The layer at the top of the list will be drawn as
the top layer in the graphics panel. The exception to this is that the
active layer is always drawn on top of everything else.

To change the drawing order of a layer, single-click and hold on the
layer, and drag it to re-position it in the list. In the example below,
the Cross-Sections layer is being dragged upwards.

|image207|

Each layer has four buttons on the right-hand side of its row.

|image208|

+----------------------+---------------------+----------------------+
| |image219|           | Settings            | Access               |
|                      |                     | layer-specific       |
|                      |                     | settings.            |
+======================+=====================+======================+
| |image220|           | Toggle Slider Layer | Toggles the layer in |
| |image221|           |                     | and out of the       |
|                      |                     | active slider layer  |
|                      |                     | (see above for       |
|                      |                     | information about    |
|                      |                     | the slider           |
|                      |                     | controls). When the  |
|                      |                     | toggle button is     |
|                      |                     | orange it means the  |
|                      |                     | layer is active in   |
|                      |                     | the slider.          |
+----------------------+---------------------+----------------------+
| |image222|           | Filter              | At the moment this   |
|                      |                     | button is disabled   |
|                      |                     | for all layers       |
|                      |                     | pending future       |
|                      |                     | filtering            |
|                      |                     | capability.          |
+----------------------+---------------------+----------------------+
| |image223|           | Remove              | Removes the layer    |
|                      |                     | from the current     |
|                      |                     | window (does **not** |
|                      |                     | delete the layer     |
|                      |                     | from the project!)   |
+----------------------+---------------------+----------------------+

There are a number of operations available by right-clicking in any
blank or “whitespace” portion of the layer control.

|image224|

The **Add Layer** option presents the same dialogue as choosing this
option from the top of this panel. The other options allow for the
creation of new data layers directly in the section, but (depending on
version) are currently restricted to Shape and Annotation*.

\* *Professional*

.. _active-layer-draw-edit-identify-1:

Active Layer: Draw, Edit & Identify
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Depending on the type of the layer certain editing, drawing and querying
operations may be available on the active cross-section window layer.
When a layer can be edited or drawn into it typically presents a tool
palette in the graphics panel when the layer becomes active. The example
below shows the palette which has appeared in the top-left of the map
panel by making the Geology layer active in the layer control.

|image225|

You can move the palette around in the panel by dragging the green bar
along the top of the box. Note that the palette becomes less transparent
when the mouse cursor is over it.

|image226|

For more detailed information on the various tools available in the
palette, depending on the layer type, please refer to the **Drawing
Points, Shapes & Annotations** and the **Drawing Cross-Sections**
chapters within this user guide.

When a layer is active you may see variations on the right-click option
available in the cross-section window and also depending on whether you
have right-clicked on an object or whitespace.

Status Bar **[7]**
~~~~~~~~~~~~~~~~~~

The status bar displays certain information and controls related to the
current session.

Global Borehole Log Template 
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

User this to set the default (global) borehole log template to use for
the session.

|image227|

Progress Bar
^^^^^^^^^^^^

This displays the progress of certain processing operations, such as
project loading and model building operations.

|image228|

Importing & Exporting Data
==========================

This section provides details of the various import and export
capabilities of Groundhog.

|image229|

*Photo by Mika Baumeister on Unsplash*

Images
------

You can import images into your project in JPG/JPEG and PNG file
formats. There are several ways to import them.

<Main Menu> <Import> <Image>.

|image230|

<Right-Click> on Images sub-folder.

|image231|

Drag image file from folder or desktop.

|image232|

Drag image from web browser (browser dependent, test using Google
Chrome).

|image233|

If you have difficulty dragging an image from the web browser,
right-click on the image and open it in a new browser tab and try again.

When images are loaded they appear in the object tree under <Site /
Project> <Associated Files> <Images>.

|image234|

Double-click the entry in the tree, or use <Right-Click> <View Image> to
view the image.

|image235|

|image236|

If the image is geo-registered and the world file is present, Groundhog
will load the image together with its geo-registration information. When
you add the image to a map window as a new layer it will display in the
correct spatial location.

If you have an image that is not geo-registered, you can still add it to
a map window as a layer. By default it will fill the available panel.
Make the image layer editable and use the blue drag handles to register
the image to the correct location.

|image237|

|image238|

|image239|

When the project is saved, Groundhog will generate a world file for the
registration information.

Shapefiles
----------

Groundhog has basic support for ESRI shapefiles (*.shp). However, the
shapefile format is proprietary and Groundhog relies on 3\ :sup:`rd`
party libraries to support the import filter. Therefore, not all
features of the file format are necessarily available, but most Point
and Line type files should load. Complex multi-polygon files may be less
reliable.

Import the file using <Main Menu> <Import> <Shapefile (*.shp)>.

|image240|

Alternatively, drag the \*.shp file into Groundhog from a folder or the
desktop.

The data is imported as a new folder under the Location Layers (points)
of Shape Layers (polyline), respectively. These folders can be added to
any map window as a layer for display.

|image241|

A right-click option provides access to a simple view (non-editable) of
the attribute table.

|image242|

|image243|

You can export Point and Shape type layers to shapefile format using
<Right-Click> <Import / Export> <Export> <Shapefile (*.SHP)>

|image244|

|image245|

ASCII Grids
-----------

ASCII grids can be imported and used either to display profiles or set
as the surface layer (topography, i.e. DEM/DTM). Groundhog supports
grids in ESRI’s ASCII format.

https://en.wikipedia.org/wiki/Esri_grid

The grid data can be imported manually via <Main Menu> <Import> <ESRI
ASCII Grid (*.asc)>

|image246|

Alternatively, and especially for a series of files, paste them into
either the WORKSPACE or the PROJECT directory and restart Groundhog.

When ASCII grids are loaded into Groundhog they are converted to a
binary equivalent called a BGRID. This is so that the data can be
queried more efficiently without loading the whole grid to memory.

Loaded grids appear in the object tree under <Models> <Reference Grids>
and each label displays the extent of the grid object.

|image247|

At present there is only a simple way to display the grid in the map,
and that is as a simple extent rectangle. To do so, highlight the
desired grid object in the tree and a blue rectangle will appear in the
map window showing the extent of that grid.

|image248|

You can set a grid to be the default topographic surface layer within
the project. This means the grid will be used as the basis of terrain
profile (topography) generation in cross-sections by default.

<Right-Click> <Set As ‘Surface Layer’>

|image249|

The currently set ‘surface layer’ grid will be displayed as bold in the
object tree list.

|image250|

OBJ Files
---------

3D objects can be imported from the industry-standard OBJ data format.

|image251|

Loaded objects will appear in the data tree.

|image252|

OBJ objects can be added to the 3D view.

Working With Borehole Logs
==========================

This section provides details on how to import and display your borehole
data, make edits to the data and design your own custom log templates.
It includes discussion of how to handle geotechnical and geophysical
borehole data in AGS and LAS formats.

|image253|

*Photo by Sven Mieke on Unsplash*

Borehole Data Import
--------------------

Groundhog supports a range of borehole data models and import options.
When borehole data is loaded it will appear in the object tree under
**Site / Project > Location Layers**.

|image254|

Borehole datasets are arranged into folders. Each data import will
create a separate folder. Within each folder there are three types of
sub-folder;

1. Attributes,

2. Data Tables,

3. 0, 1, or more borehole objects.

The **Attributes** sub-folder contains the attribution at the dataset or
project level. The **Data Tables** sub-folder contains associated
tabular data (see later section on tabular data). Each **Borehole**
object acts as a sub-folder and contains the geology/interval log and
any additional metadata attributes for each individual location.

CSV/TXT Format
~~~~~~~~~~~~~~

You can import borehole data from delimited text files. The data can
either be contained in a single file, or in two files (one containing
the collar information and one containing the log data). If the data is
split between two files make sure each file contains an ID field that
can be used to match the logs to the correct collar.

Here is a very simple example of a suitable format as text and as loaded
into MS Excel. **This is a single file** containing the collar
information and the geology log for **two boreholes**, BH 1 and BH 2.
Note that because this is a single file, **the collar information is
repeated for each geology interval**. It is also possible to store the
collar information and the geology log **in separate files**.

In this example the NAME field can be used as the borehole ID. Groundhog
can import as many fields as you like for each log interval, so you can
include fields for lithology, litho-stratigraphy, descriptions, etc. The
field names are not prescribed as they will be mapped during the import.

|image255|

|image256|

In the following example the collar and geology data are split between
two separate CSV files. Note that both files have a field that contains
the name of the borehole, which will be mapped as the ID field for
matching up the geology records to the correct location. This field does
not have to be called NAME, it can be called anything as it will be
mapped on import. It can also have different names in the collar and
geology files. The file names are also not important.

|image257|

Collar.csv

|image258|

Geology.csv

|image259|

Importing CSV
~~~~~~~~~~~~~

There are two routes to import boreholes from CSV.

1. Combined collar and geology import,

2. Individual import.

Combined Import
^^^^^^^^^^^^^^^

This option allows provides a short-cut to import both the collar and
geology data in a single step. It will work whether your data is split
into separate collar and geology data files, or merged into a single
file.

**Main Menu > Import > Borehole Data**

|image260|

The dialog contains a tab for the collar and a tab for the geology.
Click on the **Choose File** button on each tab to load up the data.

|image261|

The names of the fields in the data file are listed to the left of the
panel. Ignore the UNIT and TYPE columns.

Use the drop-down options in the **ALIAS** column to tell Groundhog the
meaning of each field in the imported data file. Choose **<< Exclude
From Import >>** for any redundant fields. The required fields for the
import type are marked in red in the drop-down list of possible
**ALIAS** values.

|image262|

In this example we are working with the combined data file that contains
both the collar and geology data. Note the mappings, including the
fields that have been excluded.

|image263|

Note that the **LEVEL** field from the data file (which is the start
height or elevation of the borehole) has been mapped to **Z**. This
field is not mandatory for the import, but if there is a value available
for this you should always map it.

Next, switch to the Geology tab and bring in the CSV file containing the
geology data. Again, in this example, the data is in the same single
file as the collar data.

The fields required for the geology import are different than for the
collar data. Again, they are highlighted in red in the drop-down list.

|image264|

|image265|

**IMPORTANT:** Make sure to use the correct field to map the **LOCATION
ID** alias, as this will be used to match the records between the collar
and geology data. GEOL and DESCRIPTION are both important fields that we
want to see in the geology log, but they do not need to be mapped to any
specific expected Groundhog field. So, they will just be imported using
the name used in the data file.

Click **OK**.

If you have missed out any required fields in the **ALIAS** mappings,
you will see this message. Go back into the mappings panels and correct
these.

|image266|

Otherwise, the import will proceed and a new borehole dataset folder
will be created in the data tree.

|image267|

Individual Import
^^^^^^^^^^^^^^^^^

This option allows the borehole dataset to be assembled one data file at
a time. It also leads into the import of generic tabular data which is
described in the following section.

First, create an empty borehole dataset folder in the tree.

|image268|

Enter a name for the folder.

|image269|

When prompted, click **Yes** to specify a borehole layer.

|image270|

The new, empty borehole dataset folder will be created in the data tree.

Use **Right-Click > Import / Export > Import > Collar** on the borehole
folder and select the file containing the collar data.

|image271|

|image272|

Use the pull-down ALIAS options to map the imported fields to the fields
expected by Groundhog and click Apply. In the case of collar data this
could be;

-  LOCATION ID

-  X

-  Y

-  Z (collar height or ground level)

|image273|

The imported collar entries are added to the data tree.

|image274|

Next, import the geology data using **Right-Click > Import /Export >
Import > Geology Intervals** on the borehole folder and select the file
containing the geology interval/log data.

|image275|

|image276|

If the depth values in the log file are elevation, as opposed to
depth-down-hole, check the special option box on the right of the file
chooser dialog (**NOTE:** this function will only work if the collar has
a Z, or ground level, value).

Map the fields using the drop-down options in the **ALIAS** column of
the import screen. Required fields are highlighted in red. Click Apply.

|image277|

Inspect the data tree to see the imported geology logs.

|image278|

Importing Tabular Data
~~~~~~~~~~~~~~~~~~~~~~

Besides the collar data and geology interval logs, Groundhog can also
import any arbitrary down-hole data in tabular format. For example,
sample and test data (in-situ and laboratory), geophysical measurements,
installation and monitoring data, etc.

It is important to note that tabular data is held at the borehole
dataset folder level and not against individual boreholes.

|image279|

The rows within each table are mapped to the appropriate borehole object
using an ID field.

To import a table of data use **Right-Click > Import / Export > Import >
Tabular Data**

|image280|

Use the file chooser dialog to select the CSV file containing the data.

|image281|

Next, use the field mapping dialog to specify the meaning of the key
fields in the import file and to choose whether to exclude any. When
importing tabular data you will need to map the fields within the data
file to those expected, or treated specially, within Groundhog. This is
done by selecting ALIAS values for each field in the data file in the
mapping dialog. All fields are imported with their original name from
the data file, but the ALIAS field tells Groundhog to treat particular
fields as special values, such as depth, id, etc. Use the pull-down
options against each field in the mapping dialog. You can also choose to
exclude specific fields from the import. The image below shows a set of
mappings for a typical import.

|image282|

You can also preview the data in the file using the Data tab, **but
currently you can’t edit the data**.

|image283|

Here is an example of a CSV file viewed in Excel, containing sample
information for two boreholes with FROM and TO depth fields.

|image284|

|image285|

Once imported, the table will appear in the data tree.

|image286|

Double-click on the table entry, or use right-click, to view the table
and edit the field mappings once loaded.

|image287|

The following example shows how to import a depth-related value, such as
geophysical test data, with a single test DEPTH field.

|image288|

|image289|

The following image below shows how the data from the tables can be used
in log templates, for example.

|image290|

Importing AGS Format Data
~~~~~~~~~~~~~~~~~~~~~~~~~

The AGS standard is a file format for the transfer of factual site
investigation data in the UK and elsewhere. It is supported as an import
option within Groundhog and, once imported, is treated as a set of data
tables, much the same as a standard CSV import would be.

From the main menu, choose **Import > AGS Data Format Tables**

|image291|

Select the AGS file (v3.1 and v4 is are both supported). The imported
data will take the form of a borehole dataset folder. Expand the folder
to explore the imported geology logs (if present in the data file) and
the various test and descriptive tables.

|image292|

Sample AGS data taken from the AGS data format v4 example data file.

Importing LAS Format Data
~~~~~~~~~~~~~~~~~~~~~~~~~

Groundhog supports the industry-standard Canadian Well Logging LAS data
format for geophysical wireline log data. The imported data is stored in
Groundhog data tables, similar to data imported from a tabular format
such as CSV.

From the main menu, choose **Import > Well Log Data (*.las)**

|image293|

The collar data is attached to the borehole entry in the data tree as a
series of attributes.

|image294|

The test data appears as a table called Curve Data under the Data Tables
sub-folder of the borehole dataset folder (example file shown courtesy
of Kansas Geological Survey download portal -
http://www.kgs.ku.edu/Magellan/Logs/).

|image295|

Double-click the table, or use right-click to view and edit the table
mappings and to preview the data values (not editable).

|image296|

|image297|

The data in the table can be used in log templates, as-per any tabular
data.

|image298|

BGS Borehole Records
~~~~~~~~~~~~~~~~~~~~

There are two ways to view borehole records held by the BGS, (1) view
original driller’s logs and (2) download AGS data.

Viewing Driller’s Logs From BGS
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

BGS holds driller’s logs as scanned images for many of the borehole
records. The locations of the records are available as a WMS (Web Map
Service) which can be displayed in the Groundhog map window as a layer.

|image299|

From the panel on the right of the layer selection dialog, select the
layer called **[GeoIndex Boreholes theme] Borehole records**.

|image300|

Zoom into an area to see the available records as a point layer.

|image301|

Make the WMS points layer active by clicking on it in the layer control.
When it is active it will turn orange. Now that the layer is active,
click on any dot in the map to perform an identify query. The results
will display in a panel on the right.

|image302|

In the identify results panel, click on the borehole stick icon to
hyperlink to the BGS record (opens in default web browser).

|image303|

|image304|

Downloading AGS Data From BGS
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The BGS’ NGDC Digital Data Deposit Application can be used by industry
and the public to deposit data into the BGS archives.

http://transfer.bgs.ac.uk/ingestion

Any AGS format data locations that are ingested are served back at as a
WMS (Web Map Service) layer that can be displayed and queried within
Groundhog.

In a map window, open the add layers dialog.

|image305|

From the panel on the right of the layer selection dialog, select the
layer called **[AGS Export] Boreholes**.

|image306|

Zoom into an area to see the available records as a point layer.

|image307|

Make the WMS points layer active by clicking on it in the layer control.
When it is active it will turn orange. Now that the layer is active,
click on any dot in the map to perform an identify query. The results
will display in a panel on the right.

|image308|

|image309|

Click on the AGS save button in the identify results panel to attempt a
download of the corresponding AGS data from the BGS database. Not all
records have AGS data attached, but most should work.

|image310|

Click <No>

|image311|

|image312|

The data will appear in the object tree as a new borehole dataset folder
ad can be worked with like any imported borehole dataset.

.. _section-1:

Displaying Boreholes
--------------------

Borehole data is displayed using custom templates. These are
column-based design templates and you can create your own within
Groundhog. Once you have designed your template you can re-use it in
each session and you can also share it with other Groundhog users.

Creating Borehole Log Templates
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The first step is to create a new, blank template in the object tree via
<System Objects> <Templates> <right-click> <New Template>

|image313|

Enter a name.

|image314|

Next, send a borehole to the blank template using <right-click> <View
Borehole Log> either in the object tree on from a borehole position in a
map window.

|image315|

|image316|

When prompted, choose the new template that you just created.

|image317|

Decide whether to always use this template for this borehole.

|image318|

The borehole will attempt to display in the blank template, but will
most likely look incorrect/blank because at this stage the template has
no way of knowing which data fields to display. To make the template
look how you want it you will need to make some edits to the design.

|image319|

Editing Borehole Log Templates
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

This section assumes a new, blank template (see previous section) is the
starting point for creating a template design, but the same principles
also apply to existing templates.

Switch the template to edit mode. You can use either the edit mode
button, or you can right-click in the template itself and choose <Edit
Template>.

|image320|

When the log template is in edit mode, the border lines will turn blue
and an editing label will appear in red at the top of the page. To exit
edit mode, press the <Stop Editing Template> button again.

|image321|

Groundhog arranges the log design into three areas, the header, columns
and footer.

|image322|

The size and width of the top-level areas can be modified by hovering
over a template line and dragging it. When a line is drag-able, as the
mouse hovers over it, it will highlight as an extended green line.

|image323|

Header
^^^^^^

The header is a tabular component which can be used to display a
document title, data fields, free-text labels and a corporate logo. To
edit the contents of a cell, use right-click.

|image324|

|image325|

|image326|

The field and title values can be free text or taken from data fields in
the borehole data itself. When you edit such a cell, you will be
presented with the field editing dialog. This dialog presents a list of
available dynamic fields, both pre-set (e.g. date/time, page number) and
data-driven (e.g. borehole attributes).

|image327|

The text field at the top contains the value that will be displayed. The
list below presents a range of data fields that can be inserted into the
value to create dynamic values. The available data fields are a mixture
of fields found in the borehole data and default fields such as
date/time and page numbers. The output value can be formed of any
combination of free-text and dynamic fields. To add a dynamic field to
the value, place the cursor at the desired position in the Value field,
highlight the desired data field in the list below, and click the
<Insert> button. Note that dynamic fields must have a space each side of
them.

Here is an example of a field value using a field called LOCA_ID and
some free-text. LOCA_ID is a field typically found in UK AGS format
geotechnical log files and is just used here as an example of a field.
The fields available will depend on the format and nature of your own
borehole data.

|image328|

And this is how the value appears in the template once applied.

|image329|

You can also add values from any of the data tables attached to the
borehole dataset using the Table Lookup button.

|image330|

Drill down to extract the desired field. In the example below, the
project name field is being added from an AGS 4 dataset. In the case of
AGS this is the PROJ_NAME field within the attached PROJ table. The
Label field is not used in this feature.

|image331|

If you select a field from a table that has multiple rows, the value
will be assigned according to the following policy;

1. If the data table contains a borehole ID field, the first row with a
   matching ID will be used as the basis of the query,

2. If the data table has no ID field, the first row in the table will be
   used as the basis of the query.

You can add/remove columns and rows to the header table using
right-click.

|image332|

Here is an example of a header table with a number of rows and columns
added and some field defined.

|image333|

You can add a logo to the template using <right-click> <Import Logo From
[Workspace or File]>.

|image334|

Select the image to use. Here we are choosing one that is already loaded
as an image in the session or workspace.

|image335|

|image336|

Columns
^^^^^^^

The columns area is where the borehole log data is placed. It is
arranged as one or more data columns. Each column can have a different
graphical type and pull on different data fields within the borehole.
Each column is divided into a header and a log column.

Start by adding a new column to the blank template. Hover over the
header portion of a pre-existing log column and <Insert Column on [Left
or Right]>.

|image337|

A prompt asks you to choose a graphical column type. Note that not all
column types will work with all types of borehole or data field. Here we
are adding a text column.

|image338|

The available column types are;

-  **Borehole Installation** – can be used to show backfill and pipe
   installation details.

-  **Curve** – plots values at a depth in the form of a curve or a
   series of dots, for example a Gamma Log or CPT log.

-  **Depth Scale** – a vertical depth scale in metres or feet.

-  **Interval (Geology Log)** – used to plot geology intervals in an
   interpreted log.

-  **Marker Depths** – plots depth boxes for intervals within the log.

-  **Samples** – displays depths and types of samples.

-  **Test Results** – displays any test result data as a label,
   including in-situ and laboratory test values. Can also be used to
   display water levels.

-  **Text** – shows any text-based data down the log, for example a
   detailed stratum description.

-  **Water Strikes** – shows strike and rest levels as symbols.

When a new column is inserted into the template typically you will be
prompted to choose the field containing the data to use for that column.
The exception is the depth scale, which is not based on a data field.
The prompt usually takes the form of a drill-down. Select the folder or
table, and then the field containing the data. Below are some examples
based on an imported AGS 4 file;

|image339|

GEOL_LEG field from the geology log (geology intervals folder)

|image340|

ISPT_MAIN data field in the ISPT test result table.

Come column types show more than one data field simultaneously. For
example the borehole installation column, which can show backfill and
pipe data together. In such cases the mapping dialog will contain
multiple tabs allowing the necessary field to be mapped.

|image341|

Once the data field mapping is completed, the column will be added to
the template. You can access and edit the settings after the column is
added using <Right-Click> <Edit TYPE Column> <Column Settings> in the
header of each column, for example;

|image342|

|image343|

The settings dialog will look slightly different, depending on the type
of the column. Often, the settings dialogs have additional settings that
are not accessible when you first add the column, so they are worth
exploring.

To remove a column from the template <Right-Click> on the column header
and select <Delete Column>

|image344|

Here are typical examples of each of the available column types, shown
here using an example AGS 4 format borehole data file and a LAS format
geophysical file.

**Borehole Installation Column**

|image345|

Example using BKFL.BKFL_LEG for the backfill mapping and PIPE.PIPE_TYPE
for the pipe installation mapping.

**Curve Column**

|image346|

Example using GR field from an imported LAS Curve Data table.

**Depth Scale Log**

|image347|

Showing feet and metres scales.

**Interval (Geology Log) Column**

|image348|

Example using GEOL.GEOL_LEG field.

**Marker Depths Column**

|image349|

Example using GEOL.GEOL_LEG field, shown against a corresponding
interval column.

**Samples Column**

|image350|

Example using SAMP.SAMP_TYPE field.

**Test Results Column**

|image351|

Example using ISPT.ISPT_REP field.

**Text Column**

|image352|

Example using GEOL.GEOL_DESC field.

**Water Strikes Column**

|image353|

Example using dual mapping of WSTD.WSTD_DPTH and WSTD.WSTD_POST for
strike and rest level.

Here is an example with several different column types added to a
template based on AGS data.

|image354|

**IMPORTANT:** As you build up your template it is a good idea to save
it regularly. Templates are held in the global workspace of Groundhog so
that they can be used across all of your projects, so they need to be
saved separately.

Footer
^^^^^^

Having added some columns, let’s set up the template footer.

|image355|

|image356|

Page Setup
^^^^^^^^^^

And finally, let’s set the page size to A4, set the number of metres to
display per-page, and fit the template to the page.

|image357|

|image358|

Flip to landscape orientation.

|image359|

<Right-Click> anywhere <Fit To Page>

|image360|

|image361|

Here is an example of a wireline log style template.

|image362|

Note that the design template can also be used in the cross-section
view.

|image363|

.. _section-2:

Editing Borehole Data
---------------------

You can enter and edit borehole data directly within Groundhog. To
demonstrate this, we will create a blank borehole dataset to work into.

From the object tree Location Layers folder <right-click> <New Layer>.

|image364|

|image365|

|image366|

Or from the layers panel of a map window.\ |image367|

|image368|

If the new layer is not already visible in a map window, add it.

|image369|

|image370|

Make the layer active in the map by clicking on it in the layers panel
(turns orange when active).

|image371|

In the drawing palette, pick up the borehole placement tool (turns
orange when selected).

|image372|

Single-click in the map to place new borehole object. Borehole collar
dialog appears. Enter a name for the new borehole, adjust X,Y as desired
to set a specific location. Also, if you have a suitable DEM/DTM loaded
and set as the surface layer in the session, click the <Set from Surface
Layer> button for the start height (ground level) field to set an
elevation value for the top of the borehole, or type one manually if you
have a more accurate one.

|image373|

Borehole appears in the map. Add as many boreholes as you like and then
de-activate the borehole layer in the map.

|image374|

Hover the mouse over a borehole location and select <right-click> <New
Geology Log>

|image375|

When prompted for a name for the log, just enter “1”.

|image376|

This creates a geology interval log with 1m interval of SAND added to
initialize the data structure. The log turns blue in the map to indicate
the presence of a geology log.

|image377|

In the object tree, note the options available on the interval of SAND.

|image378|

Edit the interval using the dialog. Here we change the depth to the base
of the first interval to be 7.4m (all values are depths, not elevations)
and change its geology code to PEAT by typing it in.

|image379|

Use the <Add/Delete Attribute> button to set new attribution on the
interval. Here we add a field for a description.

|image380|

|image381|

|image382|

|image383|

Type a value for the new field into the new entry row that has appeared.

|image384|

Add new geology intervals in the same way using the interval editing
dialog.

|image385|

|image386|

|image387|

Drawing Points, Shapes & Annotations
====================================

This section provides details on how to digitize into point and shape
layers, including borehole-type point layers. It also covers how to add
annotations such as labels, callouts, arrows and graphical icons. It
does not include how to draw into the Geology layer of a cross-section –
for that please refer to **Drawing Cross-Sections**.

|image388|

*Photo by Plush Design Studio on Unsplash*

Creating New Layers
-------------------

You can use Groundhog to create and draw point and shape layers and to
create annotation layers containing labels, callouts, arrows and icon
graphics. You can also import GIS shapefiles as these types of layers –
for more details please refer to the chapter on **Importing & Exporting
Data**.

Points and shapes can carry attribution and be styled in certain simple
ways. Their attribution can form the basis of geological interpretation,
for example by carrying a geology code they can be used to develop
geological contact maps and structure contour maps, which can then be
used as inputs to 3D models.

Shapes drawn into the map plane can be projected into the alignments of
cross-sections so that you can match your subsurface correlation to the
map line-work in order to create spatially and geologically consistent
conceptual models.

Creating and Editing Point Layers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Point layers are map layers only (they can’t be drawn into
cross-sections). Create a new point layer from the object tree by
right-clicking on the Location Layers folder, or from the map layer
control panel by right-clicking in a blank whitespace area of the panel.

|image389|

Or…

|image390|

Enter a name for the layer.

|image391|

Make the layer active in the map by clicking on it in the layer control
panel. It will turn orange when active.

|image392|

The drawing tool for points appears as a floating drawing tools palette.
You can drag the palette around using the green bar at the top.

|image393|

To draw points, pick up the point drawing tool from the palette by
clicking on it. When it is active it will turn orange.

|image394|

Single-click in the map to place points at the desired locations. When
you are finished, de-activate the point layer in the map.

|image395|

|image396|

Set the colour of the points using the point layer settings in the layer
control panel.

|image397|

|image398|

|image399|

|image400|

Attributing Points
^^^^^^^^^^^^^^^^^^

You can set name-value pair attributes on any point objects. With the
layer active in the map, hover the mouse over a point and use
<right-click> <Attribute Location>.

|image401|

Specify an attribute name and value.

|image402|

The dictionary on button on the right allows you to select from a list
of commonly used attribute names.

You can then set the field as the label for the points using the layer
settings.

Add Dip Measurement
^^^^^^^^^^^^^^^^^^^

Presents a dialogue box requesting Dip, Azimuth, Radius and Geology.

Radius is the distance in metres that the point affects and setting this
measurement varies the size of the dip measurement

|image403| |image404|

Geology is optional and is available as a shortcut way of entering this
attribute.

|image405|

|image406|

|image407|

Creating & Editing Shape Layers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Shape layers are map or cross-section layers (they can also be drawn
into cross-sections). Create a new shape layer from the object tree by
right-clicking on the Shape Layers folder, or from the map layer control
panel by right-clicking in a blank whitespace area of the panel.

|image408|

Or…

|image409|

Enter a name for the layer.

|image410|

Make the layer active in the map by clicking on it in the layer control
panel. It will turn orange when active.

|image411|

The drawing tool for points appears as a floating drawing tools palette.
You can drag the palette around using the green bar at the top.

|image412|

The drawing palette contains a number of drawing tools. Hover over each
tool to see a short description.

|image413|

The following tools are available,

-  **Polyline** – a digitizing tool, single-click to place vertices,
   double-click to finish,

-  **Pen** – hodl the mouse down and drag to create a free-form line

-  **Polygon** – same as the polyline tool but snaps the two ends of the
   line to form a polygon

-  **Rectangle** – click and drag to create a rectangle

-  **Ellipse** – click and drag to create an ellipse

Single-click on a tool to select it. When a tool is active it will turn
orange. In the following example we are using the polyline tool to
digitize lines.

|image414|

|image415|

If you want to convert a polyline to a polygon, drag the last vertex
towards the first vertex until it “snaps”. Alternatively, on the line
itself, <right-click> <Male Polygon>.

When a line is active its vertices show as green dots and the line can
be edited;

-  Move vertices by dragging them,

-  Delete vertices by double-clicking on top of them,

-  Add new vertices by double clicking on a line segment.

|image416|

When editing a line, labels appear showing the angles (in degrees)
between adjacent segments.

|image417|

Attributing & Tagging Shapes
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

You can set name-value pair attributes on any shape objects. With the
layer active in the map, hover the mouse over a line and use
<right-click> <Attribute Shape>.

|image418|

Specify an attribute name and value. In this example we are setting a Z
value so that the line could represent a structure contour, for example.

|image419|

You can then set the field as the label for the shapes using the layer
settings and also set colour and line thickness.

|image420|

|image421|

|image422|

You can tag shapes with a geology code automatically as you draw just by
setting an active drawing code other than “Shape”.

|image423|

|image424|

With a geology drawing code set, draw the shape and it will be attribute
with a field called “GEOLOGY” containing the drawing code that was
active at the time.

|image425|

You can also tag a shape with certain pre-set special attribute value.
These are accessible by hover on the line and using <right-click>

|image426|

|image427|

These tags cause the objects to act in certain special ways. For
example, tagging a site boundary will style the shape as a bold, red
line.

|image428|

Polygons With Holes
^^^^^^^^^^^^^^^^^^^

You can draw polygons with holes and Groundhog can automatically convert
them into coverage envelopes. First, draw a series of polygons into a
shape layer. Make sure each shape is a polygon either by dragging the
last vertex towards the first to snap together, or via <Right-Click>
<Make Polygon> on each line.

|image429|

Next, in the data tree, use <Right-Click> <Tools> <Build Multi-Polygons>
on the shape layer.

|image430|

|image431|

Groundhog will auto-detect the holes. This function operates to any
level of nested detail. For very complex shape layers the auto-detection
may take several moments to complete.

|image432|

Creating & Editing Annotation Layers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

*Professional*

Annotation layers let you add a descriptive and symbolic layer to your
projects, both in map and cross-section views. You can only create or
edit annotation layers using Groundhog Professional, but you can view
annotations in existing projects using Community.

Annotations can take the form of;

-  Labels – styled labels with boxes,

-  Callouts – like labels, but with a pointer,

-  Arrows – styled arrow shapes,

-  Graphics – icon pictures that can be placed to represent key
   components of a conceptual model or interpretation.

Use <right-click> <New Annotation Layer> in the layer control panel of
either a map window or a cross-section window. In the following example
we are working into a cross-section.

|image433|

Enter a name. Note that you can have as many annotation layers as you
like.

|image434|

Make the layer active so that we can draw into it. When active it will
display in orange.

|image435|

When the layer is active the floating drawing tool palette will appear
with a series of annotation-specific tools available.

|image436|

========== ======= ===================================
|image437| Label   Place a label into the layer
========== ======= ===================================
|image438| Callout Place a callout into the layer
|image439| Graphic Place a graphic into the layer
|image440| Arrow   Place an arrow shape into the layer
========== ======= ===================================

Labels
^^^^^^

Select a tool to start drawing. In this case, the labels tool. When the
tool is active is will highlight in orange and it will stay active for
as long as you want to keep placing annotations of that type. Click the
button again to switch the tool off.

|image441|

Single-click in the graphics panel (map or cross-section) to place the
annotation object. Continue clicking to add more.

|image442|

With the annotations layer active, each annotation will have green
control nodes visible. Drag these to move the annotations around.

<Right-Click> on the green control nodes shows a context menu. In the
case of labels we can use this to edit the label text.

|image443|

|image444|

When the annotations layer is active the labels appear orange to show
they are in the active layer. De-activate the annotations layer to see
them in their standard colour.

|image445|

Callouts
^^^^^^^^

Activate the callout tool and place some callouts.

|image446|

Note that callouts are like labels, but with a tail.

|image447|

Move the label portion of the callout using the green control node
inside the label.

|image448|

Move the tail by dragging the green control node at the end of the tail.

|image449|

Right-click on the control node at the end of the tail to access the
label editing dialog.

|image450|

|image451|

Arrows
^^^^^^

Activate the arrow tool in the drawing palette and single-click in the
panel to place arrows.

|image452|

|image453|

Drag the green nodes at either end of the arrows to size and position
them.

|image454|

<Right-Click> on the first node of the arrow to access editing and
ordering option.

|image455|

Use the dialog accessible under <Edit Arrow Text/Settings> option to set
the appearance and label (if one is needed) of each arrow.

|image456|

You can also set global setting for the entire layer via the settings
button of the annotations layer.

|image457|

|image458|

Graphics (Pictures)
^^^^^^^^^^^^^^^^^^^

You can add graphical pictures into an annotation layer in both map and
cross-section. Groundhog comes pre-loaded with a suite of pictures that
you can use.

Select the graphic tool from the drawing palette.

|image459|

Single-click in the graphics panel to place pictures. You will be
prompted to select the graphic picture to use. Click on the picture you
want and click <OK>.

|cid:56bf7827-d83e-41d9-a893-ba263016cf41|

Use the green and white control nodes to move and re-size the picture,
respectively.

|image460|

Annotation layers have two zoom modes. By default, the pictures will
re-scale as you zoom in and out (dynamic re-sizing).

|image461|

|image462|

Alternatively, you can switch to non dynamic re-sizing via the layer
settings dialog.

|image463|

|image464|

Add as many annotations as you wish. Here are some examples of the
graphics supported within Groundhog. You are free to use these in
outputs/reports, including for commercial projects.

|image465|

Drawing Cross-Sections
======================

This section provides details on how to construct and digitise
spatially-referenced geological cross-sections using Groundhog.

|image466|

*Photo by Ivars Krutainis on Unsplash*

Creating the Cross-Section Alignment
------------------------------------

The first step in creating a cross-section is to construct its alignment
on the map.

Creating Cross-Sections Without an Alignment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

If you do not care about the map alignment and you just want to draw a
cross-section of a specific length in isolation then you can use
<right-click> <Tools> <Create New Cross-Section> in the object tree.

|image467|

This will prompt you for a name and a length and will then open up the
cross-section in a new window ready for drawing, etc. Note that the
cross-section does still have a spatial alignment beginning at [0, 0] in
the map.

Drawing a Polyline for the Alignment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

However, you typically want to draw the cross-section alignment in the
map interactively. First, make sure you have a map window open. Create a
new map window for this purpose if necessary. If you are working in the
UK it is a good idea to add the default **Topographic Basemap** layer
that is included with Groundhog for orientation purposes or
alternatively import a geo-registered image of your site/project.

|image468|

In the map window, zoom in to the approximate desired location of the
cross-section, making sure that the extent of the map covers the entire
cross-section alignment.

If it isn’t already there, add the default **Cross-Sections** layer to
the window.

|image469|

|image470|

You are going to be drawing into the Cross-Sections layer, so make it
active by single-clicking on it in the layer control panel. When it’s
active it will highlight in orange colour.

|image471|

When the layer becomes active a drawing tool palette will appear in the
map panel. There is only one tool available in cross-section layer mode,
which is polyline. Pick this tool up by single-clicking on its icon in
the palette. When it is active the tool will highlight in orange.

|image472|

Start drawing the alignment. **Single-click to add positions** to the
alignment. **Double-click at the last vertex** of the alignment to
complete the operation. Cross-sections can have as many inflections as
you like, or they can be just straight by only placing two vertices into
the polyline.

|image473|

Enter a name for the cross-section. If you wish to abandon the line you
have drawn, simply cancel the name input dialog.

|image474|

Continue drawing polylines to create cross-section alignments. When you
are done drawing, make sure to de-activate the polyline tool by clicking
on it so that it is no longer highlighted in orange.

|image475|

With the cross-section drawing complete it will be added to the object
tree and is now available for display and digitizing operations (see
later sub-section of this chapter).

Including Boreholes in the Cross-Section Alignment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can force cross-section alignments through borehole locations so
that you can use them for correlation. First, make sure to add the
desired borehole folder to the map as a layer so that the borehole
locations are visible. Now, as you draw the polyline for the
cross-section alignment in the map, if you move the mouse cursor close
to the location of a borehole object it will show a log preview of the
borehole. This confirms that Groundhog has detected the borehole
location, so single-clicking at that location will add the borehole
itself to the cross-section alignment.

|image476|

Modifying the Alignment
~~~~~~~~~~~~~~~~~~~~~~~

Once a cross-section alignment has been drawn in the map you can still
modify it. First, make sure the **Cross-Sections** layer is visible and
active in the map.

|image477|

Insert New Position
^^^^^^^^^^^^^^^^^^^

Right-click on the segment of the polyline where you wish to insert a
new map position and choose <Insert New Position Into Cross-Section>.

|image478|

|image479|

Click on the desired location in the map to insert it into that segment
of the line.

|image480|

Extending a Cross-Section
^^^^^^^^^^^^^^^^^^^^^^^^^

You can extend a cross-section at either end. Right-click on the segment
at the desired end of the cross-section. If the cross-section only has
one segment (i.e. it is a straight section), make sure to right click
closer to the end of the line that you wish to extent. Choose <Extend
Cross-Section>. The examples below show extending the cross-sections to
the East (right).

|image481|

|image482|

|image483|

|image484|

Removing a Position From the Alignment
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

To remove a specific position from the alignment polyline, right click
on the desired position (one of the section ends or an inflection point)
and choose <Remove Position From Cross-Section>.

|image485|

|image486|

**IMPORTANT:** Please note that modifying cross-section alignments may
have adverse effects on any correlated geology linework or other
geometry objects that have already been drawn into the cross-section.

Viewing and Editing the Cross-Section
-------------------------------------

To open a cross-section in a cross-section window, (1) double-click on
it in the object tree or (2) use <right-click> <View Cross-Section> in
the tree or (3) <right-click> on the alignment in the map and choose
<View Cross-Section>. The cross-section window opens in a new tab.

|image487|

|image488|

Zoom to full extent to centre the data in the panel.

Topographic Profile
~~~~~~~~~~~~~~~~~~~

If a default surface layer (topography grid such as a DEM/DTM) is loaded
and configured in the session then a topographic profile will be
automatically generated and added as a **Terrain Profile** layer.

|image489|

If there is no grid available for this a flat profile will be generated.
To change or update the topographic profile, open the settings for the
**Terrain Profile** layer.

|image490|

Choose which grid layer to use for the profile generation and set a
level of detail. If you want to sample the grid at full resolution,
select “FULL” in this list.

|image491|

Click <Apply> to make the changes. The profile will be updated. When
using “FULL” resolution on fine grids the update may take a few moments
as the grid query is performed. Also, with the profile at very
high-resolution you may find the graphics a little slower.

If you do not have a suitable grid to use for the topographic profile,
simply drop an ASCII grid (*.asc) file into the folder where your
Groundhog project is saved and restart Groundhog. The grid will be
picked up and added to the session as an option. For more detail on
working with grid data please refer to the **Importing & Exporting
Data** chapter.

Viewing Boreholes
~~~~~~~~~~~~~~~~~

If you have drawn your cross-section alignment through any borehole
locations they will be displayed as a **Boreholes** layer.

|image492|

To begin with you may find that your boreholes appear as empty boxes
with odd labels.

|image493|

This usually happens when the active log template is unsuitable for the
data contained within the boreholes themselves. Change to a more
suitable template using either the global template settings in the main
status bar of Groundhog.

|image494|

Or, access the settings for the Borehole layer in the section window and
choose a more appropriate template.

|image495|

In the settings dialog choose a suitable template and also specify the
width (in metres) of the log sticks until the logs appear as you want
them.

|image496|

|image497|

If you don’t have a suitable log template then you can design one. For
more details please refer to the **Working With Borehole Logs** chapter.
You can design templates to show different types of borehole data such
as geotechnical test data and geophysical logs.

Buffering Boreholes Into a Cross-Section
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

If you have not drawn your alignment directly through the boreholes,
with the **Cross-Sections** layer active in the map, you can use a
buffering operation to project them into the alignment using
<right-click> <Project Nearby Boreholes Into Cross-Section>. Enter a
buffer distance. The projection is performed orthogonal to the
alignment. To remove the buffered boreholes, perform the same operation
and enter a buffer distance of 0 (zero).

|image498|

Registering Images in Cross-Section
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can add images to a cross-sections as layers. This can be useful for
showing geophysical data, for example. First, load the desired image
into the project via <Main Menu> <Import> <Image>.

|image499|

Position the cross-section panel to the approximate extent where you
want the image to display. Add the image as a layer to the cross-section
window.

|image500|

Select the image you wish to add.

|image501|

Image will appear, filling the visible extent of the graphics panel.

|image502|

Click on the image layer to make it active. Note that square, blue
control handles appear in the top-left and bottom-right of the image.

|image503|

Use the top-left handle to move the image around and use the
bottom-right handle to re-size the image. Whenever possible, try to use
an image that has scale-bars included so that you can compare the values
to the mouse cursor position in order to fine-tune the image
registration.

|image504|

Drawing Geology
~~~~~~~~~~~~~~~

Geological interpretation is drawn into the **Geology** layer. The
**Geology** layer is added to cross-section windows by default, but if
you can’t see it then you can re-add it.

|image505|

|image506|

Make the Geology layer the active layer by clicking on it. It will turn
orange when it is active (to de-activate it, click on it again).

|image507|

When the Geology layer is active the drawing tool palette will appear in
the graphics panel, with the polyline and pen tools available.

|image508|

Before you start to draw geology you need to select a drawing code. The
default drawing code is a generic code labelled “Shape”. Instead, you
need to select a geology code. Click on the drawing code selector button
and pick a geology code from the list.

|image509|

|image510|

Note that the drawing code you select is then set as the active code and
the button changes to display that code. In the above example, PEAT has
been selected.

Polyline Tool
^^^^^^^^^^^^^

The polyline tool allows for accurate digitizing by placing each vertex
individually. Click the button in the drawing tools palette to activate
the polyline tool. When it is active it will turn orange.

|image511|

Single-click in the section to place vertices. Double-click to finish
the line. Switch the polyline tool off when you are done drawing by
clicking on it again in the palette.

|image512|

Pen Tool
^^^^^^^^

The pen tool allows for rapid, fluid drawing. Click the button in the
drawing tools palette to activate the pen tool. When it is active it
will turn orange.

|image513|

Click and hold at the start of the line and drag the mouse to draw.
Release the mouse button to stop drawing the line. When you are done
drawing, switch off the pen tool by clicking on it again in the palette.

|image514|

To re-shape a line, click on it to make it active (vertices turn green)
and then drag any of the vertices to re-shape. Double-click on a vertex
to delete it. Double click on a line segment to insert a new vertex.

Snapping Geology Lines
^^^^^^^^^^^^^^^^^^^^^^

To begin with, just draw approximate lines when correlating the geology.
Once you have drawn a line you then need to snap it to other lines in
the section in order to get it to colour up as polygons. There are a few
rules to follow and you need to remember that Groundhog treats geology
lines as deposit BASES, not tops. When snapping, you can -

1. Snap the end of lines to the edges of the cross-section,

2. Snap the end of lines to the topographic (terrain) profile,

3. Snap the end of lines **upwards** onto other correlation lines
   (because the lines are deposit bases).

To snap the end of a line to something else, first make the line active
by clicking on it. When the line is active its vertices will turn green.
Once active, drag the vertex at each end of the line towards another
line, based on the three rules listed above.

|image515|

If you snap the end of a line to the terrain profile, you will be
prompted like this. Click <No> if you just want to keep a static
profile, or <Yes> to sample more accurate Z values from the terrain grid
at the snap location.

|image516|

A special icon will appear at any snap positions.

|image517|

When both ends of a geology correlation line are snapped to something,
the polygon builder will create a filled polygon for the deposit.

|image518|

Click away from the active line to de-activate it. Continue drawing and
snapping to build up the cross-section. Remember to select the
appropriate drawing code before drawing each line. If you forget, make
the line active by clicking on it then use <right-click> <Change Geology
Code> and type in the new geology code.

|image519|

|image520|

|image521|

Don’t worry if some existing polygons fail to render as you continue
drawing. They should resolve themselves as soon as you snap the line you
are working on. For example –

|image522|

|image523|

Moving any snapped positions will cause an edit to both correlation
lines (except at the topographic profile).

|image524|

If you need to un-snap a snap location, hold the CTRL key as you drag
the node away from the snap location.

|image525|

Create a correlation line at a fixed elevation using <right-click>
<Create Line [DRAWING CODE]> anywhere in the panel.

|image526|

Choose the datum (O.D. or DEPTH).

|image527|

|image528|

|image529|

The geology that has been drawn into a cross-section can be previewed
rapidly in the map by holding the SHIFT key and hovering over the
alignment. If there is geological line-work at that location the
sequence and thicknesses will be shown in a schematic image.

|image530|

Split Geology Line
^^^^^^^^^^^^^^^^^^

A geology line can now be split into two lines by right clicking on the
line at the position where it should be split and selecting **<split>**

|image531|

|image532|

In order to move the new node that has been placed in the split
position, you will need to hold down the CTRL key, to prevent the two
lines from re-joining together.

Developing Conceptual Site Models
=================================

This section provides details on how to develop a conceptual model based
around your site data within Groundhog.

*Professional*

|image533|

*Photo by Shane McLendon on Unsplash*

.. _introduction-1:

Introduction
------------

With a *Professional* license, you can use Groundhog to develop site
conceptual models (CSM). A CSM in Groundhog is a digital representation
of the pathways, or linkages, between contaminants, sources of
contaminants, the potential receptors and the migration pathways that
connect them. The CSM exists as a separate data structure or layer on
top of the Groundhog project and allows you to integrate your conceptual
understanding of pollutant linkages, for example within a catchment or a
site, with the available site data and geological interpretation.

*Professional*

Constructing the Data Model
---------------------------

A CSM is attached to a notional project “Phase”. This allows you to
develop separate models for different phases of a project, for example
desk study, remediation, monitoring. Create a Phase object to contain
the CSM using on Phases Folder.

|image534|

Enter a name.

|image535|

This initializes a CSM structure in the object tree as a series of
folders, one per component type within the CSM.

|image536|

The available CSM component types are;

   *1. Contaminants*

   *2. Sources*

   *3. Pathways*

   *4. Receptors*

Create any one of these using <Right-click> on the appropriate folder
<Add [Component Type]> for example <Add Source>.

|image537|

Enter a name for the component and an optional description. You can also
use the picklist key to browse a list of pre-set options.

|image538|

The component is added to the folder. In this case, expanding the new
source object reveals a series of attributes.

|image539|

The CSM_HANDLE is the unique ID attributed to the component in the
system.

Continue adding as many components as you wish to the model.

|image540|

Creating Pollutant Linkages 
---------------------------

With the desired model components in place you can now define the
pollutant linkages within the system. on any model component to create a
linkage to or from that linkage.

Here we link the contaminant “Benzene” to the Source “Filling Station”.

|image541|

Click <Contaminant -> Source> button.

|image542|

Highlight the Source component you wish to link to the Benzene
contaminant (in this case, there is only one, “Filling Station”).

|image543|

Click <Copy to selection >>> to add “Filling Station” to the panel on
the right and click <Apply> to create the linkage in the data model.

|image544|

Continue in this way, creating all of the conceptual linkages within the
model. You can create the following types of linkage;

¬ Contaminant ◊ Source – a linkage between a particular source component
and its potential contaminants.

-  **Contaminant -> Pathway** – linkages which describe how particular
   contaminants are able physically to migrate.

-  **Source -> Pathway** – linkages which show how particular sources
   are connected to particular migration pathways.

-  **Pathway -> Receptor** – linkages which show how particular pathways
   are connected to particular receptors.

Note that the linkage dialog will only present the currently available
options for creating new links. If no further linking is possible a
warning message will be displayed.

The linkages are displayed in the Pollutant Linkages folder.

|image545|

<Right-Click> on a linkage to delete it. You can also “break” the
linkage, which allows you to record information about how the linkage
has been broken within the conceptual model.

|image546|

When a linkage is broken it shows that it has been addressed and will
display with a green tick mark. Hovering over the linkage will display
the description of the break. The break can be removed using

<Right-Click><Un-break Linkage>.

|image547|

|image548|

**IMPORTANT:** note that if you decide to delete a CSM component that is
used by any of the linkages, all of those linkages will also be
automatically deleted from the model.

Displaying a Network Diagram
----------------------------

With the conceptual model data structure in place, and the pollutant
linkages configured, you can create network diagrams automatically.
Network diagrams show schematically and conceptually how all of the
components of the model are connected in terms of pollutant linkages.

<Right-Click> on the Network Diagrams sub-folder of the CSM structure in
the object tree and click <Create Network Diagram>.

|image549|

There are three types of diagram to choose from.

|image550|

1. S-P-R – Source-Pathway-Receptor

2. C-P-R – Contaminant-Pathway-Receptor

3. S-C-P-R – Source-Contaminant-Pathway-Receptor

Here we show an S-C-P-R diagram.

|image551|

Drag the component boxes and the labels around as desired.

|image552|

Use the handles in the bottom-right of each box to re-size.

|image553|

<Right-Click> in a CSM model component box to edit settings like colour
and to create new linkages.

|image554|

<Right-Click> <Add Label> in any whitespace region of the panel to
create new text labels.

|image555|

<Right-Click> on individual labels to edit the text or delete the label.

|image556|

<Right-Click> <Add Arrow Label> in any whitespace region of the panel to
create new labels which will be attached to a line, which can be used to
point to the required linkage arrow.

|image557|

|image558|

<Right-Click> on the label to edit it

|image559|

Click and drag the blue box at the end of the line to move it

|image560|

Note the **Add Image** option does not currently work.

<Right-Click> near to the end of a linkage, close to where it enters the
next component box and select <Break Linkage> to break the linkage in
the system.

|image561|

Broken linkages display as partial grey lines with a red cross on them.

|image562|

You can un-break a linkage using <Right-Click> <Un-break Linkage>.

**IMPORTANT:** at the moment, network diagrams are not saved as part of
the project. Once you have the diagram looking how you want it, make
sure to export it as an image for use in reports.

The following buttons are available in the network diagram toolbar.

+------------+-----------------+-------------------------------------+
| |image573| | Export Image    | Save a copy of the diagram to JPEG  |
|            |                 | or PNG format image.                |
+============+=================+=====================================+
| |image574| | Refresh         | Re-builds the diagram, picking up   |
|            |                 | any new CSM model components that   |
|            |                 | have been added and removing those  |
|            |                 | that have been deleted.             |
+------------+-----------------+-------------------------------------+
| |image575| | Hide components | Hides any non-linked CSM model      |
|            |                 | components from the diagram.        |
+------------+-----------------+-------------------------------------+
| |image576| | New colours     | Allocates new, random, colours to   |
|            |                 | the linkages. Useful if the default |
|            |                 | colour scheme is undesirable.       |
+------------+-----------------+-------------------------------------+
| |image577| | Print           | Send the diagram to a printer.      |
+------------+-----------------+-------------------------------------+

Drawing CSM Objects in Map and Cross-Section
--------------------------------------------

Certain objects that you draw or place into both map and cross-section
can be tagged as being related to CSM model components. For example, you
could draw the boundary of a landfill and attach it to the landfill
object in your CSM.

More details on how to use the drawing tools please refer to the chapter
on **Drawing Points, Shapes & Annotations**.

Shapes
~~~~~~

First, add the Phase object to the window (map or cross-section) as a
layer and click on it to make it active. The layer will turn orange when
it is active.

|image578|

Once active, the drawing tools will appear allowing you to draw into the
Phase layer. Draw a shape into the layer. When you double-click to
finish the shape you will be prompted to tag it as a CSM model
component. All shapes drawn into Phase layers MUST be tagged with a CSM
model component.

|image579|

If you have drawn a polyline, you can make the line active and then snap
the two ends together to form a polygon.

The shape will adopt the default colour for the component type (in this
case receptor colour) and a label with the name of the component will
appear. The example below show a polygon drawn to indicate the extent of
a proposed residential development.

|image580|

Annotations
~~~~~~~~~~~

You can also tag picture objects and arrows in annotation layers as CSM
model component objects.

**Pictures**

When a picture is added, if a Phase exists within the session, you will
be prompted to tag the picture with a CSM component. Pressing <Cancel>
on this prompt results in the picture being added with no tag.

|image581|

|image582|

A picture can also be tagged with a CSM component after it has been
added to the Map or Section window. To do this, with an annotation layer
active, <Right-Click> on the centre node of a picture object and select
a component type from the <Site Investigation> menu.

**Arrows**

Arrows work in the same manner as pictures, in that they can be tagged
with a CSM component when they are added, or after they have been added.
To do this, with an annotation layer active, <Right-Click> on the first
node of an arrow object and select a component type from the <Site
Investigation> menu.

|image583|

Drawing Water Levels and Defining Aquifers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Special tools have been added to allow the definition of aquifer layers
in drawn cross-sections and a water level can also be superimposed to
define the saturated zone.

First, draw the geology into the cross-section.

|image584|

To draw the water level, create a new shape layer in the cross-section
using <Right-Click> <New Shape Layer> in the layer control panel.

|image585|

Enter a name (the name is not important).

|image586|

The layer will be added and will become active automatically so that you
can draw into it. Pick up a drawing tool and draw the water level.

|image587|

Switch off the drawing tool and click on the line to make it active.
When it is active the line vertices will turn green.

|image588|

<Right-Click> on the line and select <Tag Shape As…>

|image589|

In the options that appear, select “WATER LEVEL”.

|image590|

De-activate the shape layer in the layer control. The water level line
will appear styled in a particular way to denote water level.

|image591|

Next, you need to tell Groundhog which geological unit is the aquifer
unit. This is linked to the CSM, so you will need to make sure you have
an aquifer model component defined (i.e. as a receptor component) within
the model.

|image592|

Make the Geology layer active in the layer control. <Right-Click> in the
cross-section on the geological unit that corresponds to the aquifer and
select <Site Investigation> <Tag as Aquifer?>.

|image593|

Select the Phase.

|image594|

Select the aquifer from the list of receptors.

|image595|

Click <Yes>

|image596|

The aquifer unit will be outlined in blue and the saturated zone shaded
in blue. Use the transparency of the Geology layer to get the best
image.

|image597|

Accessing Historic Maps
-----------------------

Historic maps are important in contaminated land and brownfield site
studies because they provide insight into the historic land use. To help
with this, Groundhog has a hyperlink functionality that will take you to
the website of the National Library of Scotland, which has an archive of
high-resolution scanned historic maps for the UK.

https://maps.nls.uk/

This feature is provided as a convenient 3\ :sup:`rd` party web link and
in no way implies that the NLS has any connection to, or endorsement of,
the Groundhog software.

<Right-Click> at the desired location in the map and select <Site
Investigation> <Browse Historic Maps>.

|image598|

You will be shown this message:

|image599|

The NLS website should open in your default web browser. Typically, when
the website first opens, an info box obscures the map view. Click the
cross in the top right corner to close this.

|image600|

You should now see the historic map view zoomed to approximately the
same scale and location as your Groundhog map view.

|image601|

Single-click anywhere in the map. A panel should appear on the right
showing a list view of the vintages of historic map available for that
location.

|image602|

Click on the hyperlinks in this list panel to open the map you want to
view. The interactive map view will load. Zoom and pan in the historic
map to see the area you are interested in.

|image603|

*NLS Website Image*

Building Geological Models
==========================

This section provides details on how to construct 2.5D and 3D property
and structural framework models of measurements and geology within
Groundhog.

*Professional*

|image604|

*Photo by Ruslan Keba on Unsplash*

Intro
-----

You can use the *Professional* edition of Groundhog to build simple 3D
geological models. Model building in Groundhog is based on a
multi-input, dynamic workflow and uses a gridding method to build each
deposit or layer within the model sequence. The workflow allows you to
use a range of different inputs in various combination, together with
simple algorithm selection, in order to rapidly build models. You can
work directly from your data, or layer on your own interpretation using
additional points and lines to shape the model. The workflow is rapid
and allows for testing of different hypotheses and application of
different datasets to see the effect. Each layer is constrained by
inputs in the form of;

-  Fixed thickness, depth or elevation,

-  Borehole picks,

-  Control points,

-  Drawn-cross-sections,

-  Structure contours,

-  Map linework,

-  Dip and azimuth values,

-  Variable thickness rules.

Models are based on a simple grid data structure, but can be clipped out
to project boundaries or other irregular polygonal shapes.

*Professional*

Defining the Model Grid
-----------------------

In the object tree, navigate to *Models > Layer Models* and select
*Right-Click > New Model*.

|image605|

The model editing dialog appears. Enter the necessary information to set
the name of the model (free-text), choose which elevation model from the
workspace to use as the topographic top of the model, and then enter the
bounding box of the model area and an initial cellsize to use. Set a
coarse resolution for the moment, you can refine it later. If you have a
map window open and zoomed to the model area, you can use the *Extent
From Map* button to populate the bounding box fields automatically.

|image606|

Review the input dialog an make sure you have set the following;

1. Min/max X and Y,

2. Cellsize (set this to a large value, i.e. low resolution, to begin
   with – you can change it later)

3. Name

4. Clipping Layer – select a grid, e.g. a DEM, from the workspace.

Click *Apply*. The model definition will be added to the object tree.

|image607|

Add the model to a map window.

|image608|

|image609|

Open the settings for the model in the map window.

|image610|

Check-on Model Outline and Model Grid.

|image611|

Model outline and grid are now visible in the map.

|image612|

**IMPORTANT: Now save the project.** For model building, Groundhog needs
an output folder.

Creating Model Layers
---------------------

Each layer in the model can be based on a range of different inputs,
including (depending on the layer type);

1. Borehole picks

2. Outcrop/subcrop points

3. Control points

4. Outcrop/subcrop linework

5. Structure contours

6. Cross-sections

7. Fixed depth or elevation

8. Dip and azimuth values

9. Fixed or graduated thickness values

The following example shows how to build up a layer from a set of
different inputs. To begin with we will create some bedrock-style layers
which are based on an implicit function controlled by a set of
user-added inputs.

To get started, let’s define some outcrop positions. Right-click to
create a new point layer in the map.

|image613|

|image614|

Make the new layer editable and place some points. Here we are using the
BGS 50k Bedrock Web Map Service as a guide to positioning these points
at the BASE of a mapped unit. When the points have been placed,
de-activate the point layer.

|image615|

In the object tree, *right-click on the model object > Edit Model*

|image616|

Click the Create Layer button in the model editing dialog.

|image617|

If the model is new and the project has not been saved, you will see
this.

|image618|

As models are calculated, their outputs are saved to the project folder.
For this, Groundhog needs to know where the folder lives, so save the
project somewhere and then repeat the Create Layer action again.

In the create layer dialog, enter a name for the layer and click the Add
Inputs button.

|image619|

This is where we can select which data or parameters to use as input to
the layer. Select the point layer we created as the input and click OK.

|image620|

The points are now added as an input to the layer. Click *Apply*.

|image621|

In the model editing dialog, click *Apply and Build*. If the model
editing dialog is not open, right-click on the model in the object tree
and select *Build*. The model will calculate, and the progress will be
shown in the main progress bar.

|image622|

Or…

|image623|

Go back to the settings dialog for the model layer in the map window and
tick-on the new layer. Also, switch to map coverage view.

|image624|

|image625|

The calculated extent of the layer will be shown in the map. If it is
unclear on top of the other layers, decrease the layer transparency
using the slider bar in the layer control.

|image626|

Next we will add some geological map linework. This could be imported
from a shapefile, but for this example we will draw it by hand. Create a
new shape layer in the map window and make it editable.

|image627|

|image628|

In the model editing dialog, open the settings for Layer A.

|image629|

Add the new linework to the layer input list.

|image630|

|image631|

Apply and then re-build the model.

|image632|

Note that there is a portion of Layer A in the south-west that does not
match the geological map. Draw a cross-section through the model to
inspect it at this location.

|image633|

View the cross-section and add the model to the view as a layer.

|image634|

Let’s add a component of dip to the layer using a structure contour.
Draw a new line into the Layer A map.

|image635|

Switch the drawing tool off and right-click on the new line > *Attribute
Shape*.

|image636|

Set an attribute called “Z” with a value of “10”. This attributes an
elevation value of ten metres to the line, thereby making it a structure
contour.

|image637|

This adds some additional dip to the layer, but still has not resolved
the unwanted outlier in the south west.

|image638|

Draw another structure contour in the West, setting a Z value of 60m.
This is effectively a structure contour in the air which can be used to
pull the calculated surface up out of the ground.

|image639|

Re-build the model. The layer is now correctly resolved relative to the
outcrop pattern.

|image640|

In the model editing dialog, increase the resolution of the model (e.g.
to 10m cellsize from 100m) and re-build it.

|image641|

|image642|

Next we will add another bedrock layer with a fixed elevation. Add a new
layer to the model using the model editing dialog.

|image643|

Make the input to this layer a Fixed Elevation parameter.

|image644|

Here we set the elevation at 30m, for example.

|image645|

There are now two layers in the model. Re-build the model.

|image646|

Go to the settings for the model layer in the map window and check-on
the visibility of the new layer.

|image647|

|image648|

Note that the outcrop pattern of the new layer has been generated
automatically, based on the intersection with the topography, and also
that the sub-crop position caused by the erosional contact against the
base of the layer above has also been detected automatically. Setting
the model as semi-transparent in the map window shows the sub-crop map
of Layer B beneath Layer A.

|image649|

Next we will create a Quaternary-style layer based on map linework and a
thickness value. Create a new shape layer in the map to draw into.

|image650|

|image651|

Make the new line active and snap the two ends together to form a
polygon or right-click on the line and select *Make Polygon*.

|image652|

Create a new layer using the model editing dialog. Add the Quaternary
map layer as the input and make sure to select a layer type of
“Patches”.

|image653|

Switch to the Algorithm tab of the dialog and set the thickness value to
8 (m).

|image654|

In the model editing dialog, note that the layer is at the bottom of the
list. This list is used as the stratigraphic scheme and we need the
Quaternary layer on top of the stack, so drag it to reposition at the
top of the list.

|image655|

|image656|

Re-build the model and make the new layer visible in the map. Note that
the “patches” type layer honours the drawn map exactly, unlike the
bedrock model layers which predict the outcrop pattern automatically.

|image657|

In profile, see how the layer thins out towards the edges of the mapped
polygon.

|image658|

Toggle the map view to isopach (thickness) view to get an impression of
how the thickness setting has been graduated within the mapped polygon.

|image659|

|image660|

Edit the map layer and add some windows into the layer.

|image661|

Re-build the model. Note how the hierarchy of windows and islands within
the deposit is resolved automatically. This can be taken to any level or
nesting required.

|image662|

By default, model extents are rectangular. To define a polygonal
boundary, create a shape layer and draw the boundary. Make sure to
convert the shape to a polygon.

|image663|

In the model editing dialog, click the *Extent From Shape* button and
select the model boundary shape layer as the input.

|image664|

|image665|

Re-build the model.

|image666|

Draw into the cross-section to use as an input to bedrock layers. Choose
a drawing code for the layer. Here we use GRAVEL, but the code can be
whatever you like. To draw geology, make the Geology layer active in the
section window.

|image667|

|image668|

Add the cross-section information as an input to Layer A. Go to the
settings for Layer A and choose Cross-Sections as a new input to the
layer. When prompted, choose the drawing code “GRAVEL” as the filter for
the input. This will use all instances of “Gravel” from all
cross-sections as input to the layer calculation.

|image669|

|image670|

|image671|

Re-build the model. Note that the correlation linework in the
cross-section has been used to control the Layer A surface.

|image672|

You can add models as a layer to the 3D view to visualise them. For more
details, refer to the next chapter on using the 3D graphics window.

|image673|

Additional Tools
~~~~~~~~~~~~~~~~

The above section provides a general introduction to building layer
models using Groundhog. Here we detail a few extra, specific tools that
are of use during the modelling process.

Dip and Azimuth Inputs
^^^^^^^^^^^^^^^^^^^^^^

Dip and azimuth (structural) inputs are treated as points. To convert a
point object to a structural point that can be used in the modelling,
first make the point layer active. **<Right-click>** on the desired
point and choose **<Add Dip Measurement>**

|image674|

Use the input dialog to set the DIP, AZIMUTH and RADIUS values. RADIUS
controls the zone of influence of the data point. You can also set a
GEOLOGY code if you wish to have a single point layer containing
structural points from different model layers.

|image675|

The point becomes an arrow showing the AZIMUTH. The length of the arrow
shows the RADIUS of influence the point will have if used in a
calculation.

|image676|

Coverage Mode
^^^^^^^^^^^^^

When working with stratigraphic layers, by default Groundhog will
auto-predict the outcrop/subcrop of each layer in the model. However, if
you wish to have hard control over the calculation boundaries then you
can draw (or import) a polygonal map to act as the boundary of the model
calculation for the layer. This is known as COVERAGE mode. When you are
working in this mode, Groundhog will not compute the presence of the
layer anywhere outside the coverage polygon.

Draw the polygons for the coverage map into a shape layer (or import
from a Shapefile, but make sure they are polygons). After drawing each
shape, ensure it is a polygon either by dragging the last node towards
the first node to snap it, or using **<Right-Click> <Make Polygon>**

|image677|

Here is an example if a coverage polygon drawn for a layer.

|image678|

Note that a coverage can be composed of multiple polygons, including
polygons-with-holes (nested to any level of detail.

Next, add the shape layer to the desired model layer as an input.

|image679|

When prompted to set the shape input as a COVERAGE layer, click
**<Yes>**

|image680|

Note that shape layers which are acting as coverage layers are labelled
thus in the input list.

|image681|

If you need to change the status of the layer you should delete it from
the inputs list and then re-add it.

Calculate the model. Note that the calculation of the layer stays within
the shapes of the coverage layer.

|image682|

Working at a higher resolution shows the effect of this more clearly,
especially if the coverage map is very detailed with lots of small holes
and islands.

|image683|

Control Points
^^^^^^^^^^^^^^

Points from point layers can be used as control points. Control points
act to remove an area of modelling and are a quick way to clean up
models. Below is an example of a model layer with an area that needs to
be cleaned up (highlighted by the arrows).

|image684|

To set a point as a control point, place the point in the desired
location and then use **<Right-Click> <Modelling Tools> <Clean Up>**

|image685|

The point is displayed as a cross icon.

|image686|

Re-build the model.

|image687|

3D Graphics
===========

This section provides details on how to operate the 3D graphics
component within Groundhog.

|image688|

*Photo by Nathan Duck on Unsplash*

About
-----

The 3D window in groundhog has been developed in order to visualize the
data that you import and create in 2D. All of the features of the 3D
window are available in community edition. From viewing boreholes and
cross sections, as you can in the map and section views, as solid,
spatially referenced objects to elevation grids as surfaces and block
geology models.

.. _first-use-1:

First Use
---------

To open the 3D window, click the |image689|\ 3D window button and you
will be presented with the user interface.

.. _user-interface-1:

User Interface
--------------

|image690|

The window has three main areas of control:

The control panel
~~~~~~~~~~~~~~~~~

|image691|

The control panel is where you will manipulate what data you are viewing
and how you will view it in 3D. The controls are split into tabs for
easy navigation and there are three controlling buttons at the top:

1. |image692| Move: This will allow you to rotate, pan and zoom in the
   3D scene.

2. |image693| Pick: This button is currently in beta but when the window
   is in this mode, you can no longer move around but instead select
   objects by clicking them. When an object is selected (clicked on) it
   will open in the object explorer tab which we will visit later. (As
   his is in beta only some data types are supported)

3. |image694|\ Save: Self-explanatory but with many functions, the save
   button will allow you to save a variety of items from the
   configuration of the window (camera position and layers) to mp4
   videos you record to .OBJ exports of supported layers in the window.

Layer Control
~~~~~~~~~~~~~

|image695|\ The first of the tabs in the control panel is the **layer
control** with which you will be familiar from the map and section
window. Along the top, left to right, there is:

1. The add layer button, opening the usual dialogue

2. The global setting button which opens this dialogue: |image696|

..

   Here you can set the vertical scale of the window, the maximum
   vertical scale for the slider and turn on and off the axes in the
   window.

3. The background colour button, which changes the background colour of
   the 3D window

4. The clear layers button which will remove all of the layers from the
   window.

The next item is the representation of a layer.

|image697|

Here you can see the name of the layer, the icon of the layers type, in
this case borehole, a checkbox for the visibility of the layer, a slider
for the transparency and 4 buttons. From left to right, top to bottom:

1. Settings: this will open up any settings for the layer (some of which
   will be described below)

2. Filter: this will open any filters for the layer

3. Object Explore: Will open the layer in the object explorer (the next
   tab we will look at)

4. Remove: which will remove the layer from the window.

When multiple layers are in the layer control, they can be dragged
around, just as in the map and section layer controls, to change the
drawing order and allow certain objects to be seen through others.

.. _section-3:

|image698|\ Object Explorer
~~~~~~~~~~~~~~~~~~~~~~~~~~~

The next tab is the **object explorer** which allows a particular layer
to be interrogated. By opening the above borehole layer in the object
explorer, we can see the two boreholes that are in the dataset are shown
in the panel. Each borehole can then be turned on and off with the
checkbox and its transparency changed with the slider. Right click on a
borehole or any object in the explorer, that item will become the
**pivot** of the window. There may also be settings for an object which
can be accessed through the settings button.

If you double click an object in the explorer, that object will be
“opened”.

|image699|\ Here, the object BH502 has been opened and you can now see
all of the logs and manipulate them as with any other object.

The arrow buttons can be used to move backwards and forwards in and out
of objects.

Clipping Controls
~~~~~~~~~~~~~~~~~

|image700|\ After the object explorer, you will find the **clipping
controls** tab. The add button will give you two options:

1. Add new clipping Plane: this will add a new clipping plane to the
   scene, allowing you to slice and interrogate your data at whatever
   angle you wish wherever.

This is particularly useful for viewing 3D geological models produced in
Groundhog Professional.

|image701|\ |image702|

When you create a clipping plane, you will be greeted with a control
that looks like this:

|image703|\ To rotate the plane, drag the circle at the end of the line,
and to move the center point of the plane, drag the center circle in
that direction.

If you are struggling with this control, by clicking the settings
button, you can also incrementally change the positions.

|image704|\ A is for azimuth as an angle in degrees.

If you choose a **clipping slice** the controls are much the same, with
the addition of a thickness. On the graphical control: |image705|\ and
by buttons is represented by T: |image706|

The difference with a clipping slice over a clipping plane is that there
is somewhat a slice of cake taken out of a model :

|image707|

Configurations
~~~~~~~~~~~~~~

**Configurations** is the final tab in the control panel and its purpose
is to provide shortcuts to nice “views” of your data.

If you like an angle of looking at your data or particular clip, you can
press the save button |image708|\ and all the information will be saved,
a link to it being shown then in the configurations tab.

|image709|\ Select the saved configuration you would like to see and you
will be taken there.

While a configuration is selected, selecting this button will allow you
to rename the configuration

The bin will remove all configurations.

The Hot Bar
~~~~~~~~~~~

|image710|

The hot bar is the area at the bottom of the groundhog 3D window which
looks like the screenshot above. Here you can find useful information
and some quick access tools.

The first item is the loading bar. |image711| This will give you
information on the progress of any actions such as loading and saving.

Next is the vertical exaggeration slider. |image712|\ By moving this
slider, you will increase or decrease the vertical exaggeration on the
window.

The following tools you will find are the recording and playback tools.
|image713| In order to create a playback, click the record button,
maneuver around the scene in the order you wish to re-watch and,
finally, click the stop button that will have replaced the record
button.\ |image714|

In order to watch your playback, simply click the play button.

When the play button becomes available, you will be able to save a
playback as an MP4 by clicking the save button |image715| and selecting
the playback option from the dropdown.

Finally, on the hot bar, there is the message area. |image716| Useful
tips will be displayed here.

The Scene
~~~~~~~~~

This is the final area of the 3D window and is where all of the data
appears.

|image717|

This area is very minimal, here we have:

1. The data: Whatever you have added to the scene from the add layers
   button.

2. The compass: Showing the direction you are looking

3. The axes: giving the scale of the data you are viewing

Navigation of the scene is broken into three types:

1. Rotation: press and hold left click and drag the mouse to rotate the
   scene.

2. Zoom: use scroll to zoom in and out from the data.

3. Pan: press down on the scroll wheel and hold then drag the mouse to
   pan around the scene.

Settings
--------

Borehole Settings
~~~~~~~~~~~~~~~~~

|image718|

Saving
------

The save button |image719| is a multi-functional save tool which will
allow the saving of any savable layers or items that are currently
existent within your current session. These could include 3D objects,
videos and the configuration of your window.

When the save button is pressed, the following dropdown box will appear.

|image720|

All of the options in the dropdown can be saved to their stated format
and the possible options are as follows.

Cross Sections
~~~~~~~~~~~~~~

Cross sections can be saved from the 3D window to the .OBJ format which
can then be imported into GeoVisionary and many other CAD platforms.
There will be a selection of files exported which will be one for each
unit and one which will represent all of the sections. All will be
placed in a single folder in your chosen location called “Cross
Sections”.

Models
~~~~~~

Geological models can also be saved to the .OBJ format and there will be
a file created for each stratigraphic layer of your model. These will
all be saved to the folder of your choosing.

Surfaces
~~~~~~~~

Keeping consistent with the other layers, surfaces too will be export as
.OBJ files. There will be three files output.

|image721|

These three should be kept together; there is one for the shapes, one
for the colours and optionally one which will be the image used for the
surface.

Videos
~~~~~~

If the playback function has been used then there will be the option to
save this to an mp4 video. During the saving of the video, the window
will be temporarily out of action and appear to move by itself, this is
so that the information can be collected. Please do not interrupt this.

.. _configurations-1:

Configurations
~~~~~~~~~~~~~~

|image722|\ The final option is the current map window configuration and
as previously mentioned will save the view on the screen as a waypoint
which you will be able to click and return to at a later date. Once you
have provided a memorable name, it will appear in the configurations tab
like this:

.. |image1| image:: ./media/image1.png
   :width: 6.15865in
   :height: 4.16279in
.. |image2| image:: ./media/image2.png
   :width: 2.05356in
   :height: 0.6017in
.. |image3| image:: ./media/image3.png
   :width: 1.3547in
   :height: 0.568in
.. |image4| image:: ./media/image3.png
   :width: 1.3547in
   :height: 0.568in
.. |image5| image:: ./media/image2.png
   :width: 2.05356in
   :height: 0.6017in
.. |image6| image:: ./media/image4.jpeg
   :width: 6.26806in
   :height: 4.17847in
.. |image7| image:: ./media/image5.PNG
   :width: 6.21389in
   :height: 2.85903in
.. |image8| image:: ./media/image6.png
   :width: 5.4375in
   :height: 2.91667in
.. |image9| image:: ./media/image7.png
   :width: 3.13542in
   :height: 1.61458in
.. |image10| image:: ./media/image8.jpeg
   :width: 6.26806in
   :height: 4.17847in
.. |image11| image:: ./media/image9.png
   :width: 1.96099in
   :height: 5.11304in
.. |image12| image:: ./media/image10.png
   :width: 1.47917in
   :height: 1.01042in
.. |image13| image:: ./media/image11.png
   :width: 1.58333in
   :height: 1.69792in
.. |image14| image:: ./media/image12.png
   :width: 2.13542in
   :height: 0.55208in
.. |image15| image:: ./media/image13.png
   :width: 2.36522in
   :height: 1.09302in
.. |image16| image:: ./media/image14.png
   :width: 2.63478in
   :height: 1.09315in
.. |image17| image:: ./media/image15.png
   :width: 1.58333in
   :height: 0.63542in
.. |image18| image:: ./media/image16.PNG
   :width: 5.37575in
   :height: 2.58369in
.. |image19| image:: ./media/image17.png
   :width: 1.83333in
   :height: 0.5625in
.. |image20| image:: ./media/image18.png
   :width: 2.53044in
   :height: 1.16937in
.. |image21| image:: ./media/image19.png
   :width: 2.10417in
   :height: 0.47917in
.. |image22| image:: ./media/image20.png
   :width: 4.97917in
   :height: 0.58333in
.. |image23| image:: ./media/image21.png
   :width: 2.4in
   :height: 1.10909in
.. |image24| image:: ./media/image22.png
   :width: 2.35652in
   :height: 1.089in
.. |image25| image:: ./media/image23.png
   :width: 1.33333in
   :height: 0.44792in
.. |image26| image:: ./media/image24.png
   :width: 1.86458in
   :height: 0.60417in
.. |image27| image:: ./media/image25.png
   :width: 2.30435in
   :height: 1.06489in
.. |image28| image:: ./media/image26.png
   :width: 1.375in
   :height: 0.48958in
.. |image29| image:: ./media/image27.png
   :width: 2.77083in
   :height: 0.52083in
.. |image30| image:: ./media/image28.png
   :width: 1.6875in
   :height: 0.875in
.. |image31| image:: ./media/image29.png
   :width: 1.57292in
   :height: 0.875in
.. |image32| image:: ./media/image30.png
   :width: 1.83333in
   :height: 0.98958in
.. |image33| image:: ./media/image31.png
   :width: 2.61458in
   :height: 1.9375in
.. |image34| image:: ./media/image32.png
   :width: 2.61458in
   :height: 1.10417in
.. |image35| image:: ./media/image33.png
   :width: 2.03125in
   :height: 0.58333in
.. |image36| image:: ./media/image34.PNG
   :width: 3.3301in
   :height: 1.34217in
.. |image37| image:: ./media/image35.PNG
   :width: 1.91693in
   :height: 0.26045in
.. |image38| image:: ./media/image36.jpeg
   :width: 6.26806in
   :height: 4.17847in
.. |image39| image:: ./media/image37.png
   :width: 6.26806in
   :height: 3.39514in
.. |image40| image:: ./media/image38.png
   :width: 0.41667in
   :height: 0.42708in
.. |image41| image:: ./media/image39.png
   :width: 0.39583in
   :height: 0.39583in
.. |image42| image:: ./media/image40.png
   :width: 0.38542in
   :height: 0.42708in
.. |image43| image:: ./media/image41.png
   :width: 0.39583in
   :height: 0.41667in
.. |image44| image:: ./media/image42.png
   :width: 0.42708in
   :height: 0.42708in
.. |image45| image:: ./media/image38.png
   :width: 0.41667in
   :height: 0.42708in
.. |image46| image:: ./media/image39.png
   :width: 0.39583in
   :height: 0.39583in
.. |image47| image:: ./media/image40.png
   :width: 0.38542in
   :height: 0.42708in
.. |image48| image:: ./media/image41.png
   :width: 0.39583in
   :height: 0.41667in
.. |image49| image:: ./media/image42.png
   :width: 0.42708in
   :height: 0.42708in
.. |image50| image:: ./media/image38.png
   :width: 0.41667in
   :height: 0.42708in
.. |image51| image:: ./media/image39.png
   :width: 0.39583in
   :height: 0.39583in
.. |image52| image:: ./media/image40.png
   :width: 0.38542in
   :height: 0.42708in
.. |image53| image:: ./media/image41.png
   :width: 0.39583in
   :height: 0.41667in
.. |image54| image:: ./media/image42.png
   :width: 0.42708in
   :height: 0.42708in
.. |image55| image:: ./media/image43.PNG
   :width: 2.66704in
   :height: 0.37505in
.. |image56| image:: ./media/image44.png
   :width: 0.86567in
   :height: 0.2929in
.. |image57| image:: ./media/image45.png
   :width: 3.18657in
   :height: 2.40134in
.. |image58| image:: ./media/image46.png
   :width: 0.72917in
   :height: 0.34375in
.. |image59| image:: ./media/image47.png
   :width: 0.69792in
   :height: 0.34375in
.. |image60| image:: ./media/image48.png
   :width: 0.82292in
   :height: 0.33333in
.. |image61| image:: ./media/image49.png
   :width: 0.84375in
   :height: 0.35417in
.. |image62| image:: ./media/image46.png
   :width: 0.72917in
   :height: 0.34375in
.. |image63| image:: ./media/image47.png
   :width: 0.69792in
   :height: 0.34375in
.. |image64| image:: ./media/image48.png
   :width: 0.82292in
   :height: 0.33333in
.. |image65| image:: ./media/image49.png
   :width: 0.84375in
   :height: 0.35417in
.. |image66| image:: ./media/image46.png
   :width: 0.72917in
   :height: 0.34375in
.. |image67| image:: ./media/image47.png
   :width: 0.69792in
   :height: 0.34375in
.. |image68| image:: ./media/image48.png
   :width: 0.82292in
   :height: 0.33333in
.. |image69| image:: ./media/image49.png
   :width: 0.84375in
   :height: 0.35417in
.. |image70| image:: ./media/image50.png
   :width: 6.26806in
   :height: 0.34306in
.. |image71| image:: ./media/image51.png
   :width: 6.26806in
   :height: 4.19861in
.. |image72| image:: ./media/image52.png
   :width: 5.20833in
   :height: 2.65625in
.. |image73| image:: ./media/image53.png
   :width: 3.73958in
   :height: 0.54167in
.. |image74| image:: ./media/image54.png
   :width: 0.29167in
   :height: 0.28125in
.. |image75| image:: ./media/image55.png
   :width: 0.27083in
   :height: 0.27083in
.. |image76| image:: ./media/image56.png
   :width: 0.26042in
   :height: 0.28125in
.. |image77| image:: ./media/image57.png
   :width: 0.26042in
   :height: 0.26042in
.. |image78| image:: ./media/image58.png
   :width: 0.79104in
   :height: 0.22356in
.. |image79| image:: ./media/image59.png
   :width: 0.27083in
   :height: 0.27083in
.. |image80| image:: ./media/image60.png
   :width: 0.30208in
   :height: 0.25in
.. |image81| image:: ./media/image61.png
   :width: 0.26042in
   :height: 0.26042in
.. |image82| image:: ./media/image62.png
   :width: 0.53125in
   :height: 0.26042in
.. |image83| image:: ./media/image63.png
   :width: 3.63433in
   :height: 1.75101in
.. |image84| image:: ./media/image54.png
   :width: 0.29167in
   :height: 0.28125in
.. |image85| image:: ./media/image55.png
   :width: 0.27083in
   :height: 0.27083in
.. |image86| image:: ./media/image56.png
   :width: 0.26042in
   :height: 0.28125in
.. |image87| image:: ./media/image57.png
   :width: 0.26042in
   :height: 0.26042in
.. |image88| image:: ./media/image58.png
   :width: 0.79104in
   :height: 0.22356in
.. |image89| image:: ./media/image59.png
   :width: 0.27083in
   :height: 0.27083in
.. |image90| image:: ./media/image60.png
   :width: 0.30208in
   :height: 0.25in
.. |image91| image:: ./media/image61.png
   :width: 0.26042in
   :height: 0.26042in
.. |image92| image:: ./media/image62.png
   :width: 0.53125in
   :height: 0.26042in
.. |image93| image:: ./media/image63.png
   :width: 3.63433in
   :height: 1.75101in
.. |image94| image:: ./media/image54.png
   :width: 0.29167in
   :height: 0.28125in
.. |image95| image:: ./media/image55.png
   :width: 0.27083in
   :height: 0.27083in
.. |image96| image:: ./media/image56.png
   :width: 0.26042in
   :height: 0.28125in
.. |image97| image:: ./media/image57.png
   :width: 0.26042in
   :height: 0.26042in
.. |image98| image:: ./media/image58.png
   :width: 0.79104in
   :height: 0.22356in
.. |image99| image:: ./media/image59.png
   :width: 0.27083in
   :height: 0.27083in
.. |image100| image:: ./media/image60.png
   :width: 0.30208in
   :height: 0.25in
.. |image101| image:: ./media/image61.png
   :width: 0.26042in
   :height: 0.26042in
.. |image102| image:: ./media/image62.png
   :width: 0.53125in
   :height: 0.26042in
.. |image103| image:: ./media/image63.png
   :width: 3.63433in
   :height: 1.75101in
.. |image104| image:: ./media/image64.png
   :width: 1.70833in
   :height: 1.17708in
.. |image105| image:: ./media/image65.png
   :width: 1.64925in
   :height: 0.73092in
.. |image106| image:: ./media/image65.png
   :width: 1.64925in
   :height: 0.73092in
.. |image107| image:: ./media/image65.png
   :width: 1.64925in
   :height: 0.73092in
.. |image108| image:: ./media/image66.png
   :width: 3.84375in
   :height: 0.39583in
.. |image109| image:: ./media/image67.png
   :width: 0.33333in
   :height: 0.32292in
.. |image110| image:: ./media/image68.png
   :width: 0.26042in
   :height: 0.28125in
.. |image111| image:: ./media/image69.png
   :width: 0.27083in
   :height: 0.27083in
.. |image112| image:: ./media/image70.png
   :width: 0.23958in
   :height: 0.27083in
.. |image113| image:: ./media/image71.png
   :width: 0.25in
   :height: 0.27083in
.. |image114| image:: ./media/image72.png
   :width: 0.26042in
   :height: 0.25in
.. |image115| image:: ./media/image67.png
   :width: 0.33333in
   :height: 0.32292in
.. |image116| image:: ./media/image68.png
   :width: 0.26042in
   :height: 0.28125in
.. |image117| image:: ./media/image69.png
   :width: 0.27083in
   :height: 0.27083in
.. |image118| image:: ./media/image70.png
   :width: 0.23958in
   :height: 0.27083in
.. |image119| image:: ./media/image71.png
   :width: 0.25in
   :height: 0.27083in
.. |image120| image:: ./media/image72.png
   :width: 0.26042in
   :height: 0.25in
.. |image121| image:: ./media/image67.png
   :width: 0.33333in
   :height: 0.32292in
.. |image122| image:: ./media/image68.png
   :width: 0.26042in
   :height: 0.28125in
.. |image123| image:: ./media/image69.png
   :width: 0.27083in
   :height: 0.27083in
.. |image124| image:: ./media/image70.png
   :width: 0.23958in
   :height: 0.27083in
.. |image125| image:: ./media/image71.png
   :width: 0.25in
   :height: 0.27083in
.. |image126| image:: ./media/image72.png
   :width: 0.26042in
   :height: 0.25in
.. |image127| image:: ./media/image73.png
   :width: 3.77083in
   :height: 1.44792in
.. |image128| image:: ./media/image74.png
   :width: 1.91667in
   :height: 1.05208in
.. |image129| image:: ./media/image75.png
   :width: 1.88542in
   :height: 1.47917in
.. |image130| image:: ./media/image76.png
   :width: 3.80208in
   :height: 1.41667in
.. |image131| image:: ./media/image77.png
   :width: 3.83333in
   :height: 1.40625in
.. |image132| image:: ./media/image78.png
   :width: 0.48958in
   :height: 0.46875in
.. |image133| image:: ./media/image79.png
   :width: 0.27083in
   :height: 0.25in
.. |image134| image:: ./media/image80.png
   :width: 0.28125in
   :height: 0.20833in
.. |image135| image:: ./media/image81.png
   :width: 0.23958in
   :height: 0.23958in
.. |image136| image:: ./media/image82.png
   :width: 0.23958in
   :height: 0.23958in
.. |image137| image:: ./media/image83.png
   :width: 0.25in
   :height: 0.22917in
.. |image138| image:: ./media/image79.png
   :width: 0.27083in
   :height: 0.25in
.. |image139| image:: ./media/image80.png
   :width: 0.28125in
   :height: 0.20833in
.. |image140| image:: ./media/image81.png
   :width: 0.23958in
   :height: 0.23958in
.. |image141| image:: ./media/image82.png
   :width: 0.23958in
   :height: 0.23958in
.. |image142| image:: ./media/image83.png
   :width: 0.25in
   :height: 0.22917in
.. |image143| image:: ./media/image79.png
   :width: 0.27083in
   :height: 0.25in
.. |image144| image:: ./media/image80.png
   :width: 0.28125in
   :height: 0.20833in
.. |image145| image:: ./media/image81.png
   :width: 0.23958in
   :height: 0.23958in
.. |image146| image:: ./media/image82.png
   :width: 0.23958in
   :height: 0.23958in
.. |image147| image:: ./media/image83.png
   :width: 0.25in
   :height: 0.22917in
.. |image148| image:: ./media/image84.PNG
   :width: 1.80233in
   :height: 1.25017in
.. |image149| image:: ./media/image85.png
   :width: 6.26806in
   :height: 1.74653in
.. |image150| image:: ./media/image86.png
   :width: 3.15672in
   :height: 1.71587in
.. |image151| image:: ./media/image87.PNG
   :width: 6.26806in
   :height: 2.07569in
.. |image152| image:: ./media/image88.png
   :width: 4.22917in
   :height: 0.58333in
.. |image153| image:: ./media/image89.png
   :width: 0.72917in
   :height: 0.35417in
.. |image154| image:: ./media/image90.png
   :width: 0.27083in
   :height: 0.27083in
.. |image155| image:: ./media/image91.png
   :width: 0.22917in
   :height: 0.25in
.. |image156| image:: ./media/image92.png
   :width: 0.30208in
   :height: 0.28125in
.. |image157| image:: ./media/image93.png
   :width: 0.28125in
   :height: 0.30208in
.. |image158| image:: ./media/image94.png
   :width: 0.75in
   :height: 0.29167in
.. |image159| image:: ./media/image59.png
   :width: 0.27083in
   :height: 0.27083in
.. |image160| image:: ./media/image60.png
   :width: 0.30208in
   :height: 0.25in
.. |image161| image:: ./media/image61.png
   :width: 0.26042in
   :height: 0.26042in
.. |image162| image:: ./media/image62.png
   :width: 0.53125in
   :height: 0.26042in
.. |image163| image:: ./media/image95.png
   :width: 3.53671in
   :height: 1.14181in
.. |image164| image:: ./media/image89.png
   :width: 0.72917in
   :height: 0.35417in
.. |image165| image:: ./media/image90.png
   :width: 0.27083in
   :height: 0.27083in
.. |image166| image:: ./media/image91.png
   :width: 0.22917in
   :height: 0.25in
.. |image167| image:: ./media/image92.png
   :width: 0.30208in
   :height: 0.28125in
.. |image168| image:: ./media/image93.png
   :width: 0.28125in
   :height: 0.30208in
.. |image169| image:: ./media/image94.png
   :width: 0.75in
   :height: 0.29167in
.. |image170| image:: ./media/image59.png
   :width: 0.27083in
   :height: 0.27083in
.. |image171| image:: ./media/image60.png
   :width: 0.30208in
   :height: 0.25in
.. |image172| image:: ./media/image61.png
   :width: 0.26042in
   :height: 0.26042in
.. |image173| image:: ./media/image62.png
   :width: 0.53125in
   :height: 0.26042in
.. |image174| image:: ./media/image95.png
   :width: 3.53671in
   :height: 1.14181in
.. |image175| image:: ./media/image89.png
   :width: 0.72917in
   :height: 0.35417in
.. |image176| image:: ./media/image90.png
   :width: 0.27083in
   :height: 0.27083in
.. |image177| image:: ./media/image91.png
   :width: 0.22917in
   :height: 0.25in
.. |image178| image:: ./media/image92.png
   :width: 0.30208in
   :height: 0.28125in
.. |image179| image:: ./media/image93.png
   :width: 0.28125in
   :height: 0.30208in
.. |image180| image:: ./media/image94.png
   :width: 0.75in
   :height: 0.29167in
.. |image181| image:: ./media/image59.png
   :width: 0.27083in
   :height: 0.27083in
.. |image182| image:: ./media/image60.png
   :width: 0.30208in
   :height: 0.25in
.. |image183| image:: ./media/image61.png
   :width: 0.26042in
   :height: 0.26042in
.. |image184| image:: ./media/image62.png
   :width: 0.53125in
   :height: 0.26042in
.. |image185| image:: ./media/image95.png
   :width: 3.53671in
   :height: 1.14181in
.. |image186| image:: ./media/image96.png
   :width: 1.85417in
   :height: 0.85417in
.. |image187| image:: ./media/image97.png
   :width: 3.03125in
   :height: 0.42708in
.. |image188| image:: ./media/image67.png
   :width: 0.33333in
   :height: 0.32292in
.. |image189| image:: ./media/image68.png
   :width: 0.26042in
   :height: 0.28125in
.. |image190| image:: ./media/image69.png
   :width: 0.27083in
   :height: 0.27083in
.. |image191| image:: ./media/image71.png
   :width: 0.25in
   :height: 0.27083in
.. |image192| image:: ./media/image72.png
   :width: 0.26042in
   :height: 0.25in
.. |image193| image:: ./media/image67.png
   :width: 0.33333in
   :height: 0.32292in
.. |image194| image:: ./media/image68.png
   :width: 0.26042in
   :height: 0.28125in
.. |image195| image:: ./media/image69.png
   :width: 0.27083in
   :height: 0.27083in
.. |image196| image:: ./media/image71.png
   :width: 0.25in
   :height: 0.27083in
.. |image197| image:: ./media/image72.png
   :width: 0.26042in
   :height: 0.25in
.. |image198| image:: ./media/image67.png
   :width: 0.33333in
   :height: 0.32292in
.. |image199| image:: ./media/image68.png
   :width: 0.26042in
   :height: 0.28125in
.. |image200| image:: ./media/image69.png
   :width: 0.27083in
   :height: 0.27083in
.. |image201| image:: ./media/image71.png
   :width: 0.25in
   :height: 0.27083in
.. |image202| image:: ./media/image72.png
   :width: 0.26042in
   :height: 0.25in
.. |image203| image:: ./media/image98.png
   :width: 4.27612in
   :height: 1.65214in
.. |image204| image:: ./media/image99.png
   :width: 1.61458in
   :height: 0.96875in
.. |image205| image:: ./media/image100.png
   :width: 1.35075in
   :height: 1.57449in
.. |image206| image:: ./media/image101.png
   :width: 3.6791in
   :height: 1.41327in
.. |image207| image:: ./media/image102.png
   :width: 3.96269in
   :height: 1.54105in
.. |image208| image:: ./media/image78.png
   :width: 0.48958in
   :height: 0.46875in
.. |image209| image:: ./media/image79.png
   :width: 0.27083in
   :height: 0.25in
.. |image210| image:: ./media/image80.png
   :width: 0.28125in
   :height: 0.20833in
.. |image211| image:: ./media/image81.png
   :width: 0.23958in
   :height: 0.23958in
.. |image212| image:: ./media/image82.png
   :width: 0.23958in
   :height: 0.23958in
.. |image213| image:: ./media/image83.png
   :width: 0.25in
   :height: 0.22917in
.. |image214| image:: ./media/image79.png
   :width: 0.27083in
   :height: 0.25in
.. |image215| image:: ./media/image80.png
   :width: 0.28125in
   :height: 0.20833in
.. |image216| image:: ./media/image81.png
   :width: 0.23958in
   :height: 0.23958in
.. |image217| image:: ./media/image82.png
   :width: 0.23958in
   :height: 0.23958in
.. |image218| image:: ./media/image83.png
   :width: 0.25in
   :height: 0.22917in
.. |image219| image:: ./media/image79.png
   :width: 0.27083in
   :height: 0.25in
.. |image220| image:: ./media/image80.png
   :width: 0.28125in
   :height: 0.20833in
.. |image221| image:: ./media/image81.png
   :width: 0.23958in
   :height: 0.23958in
.. |image222| image:: ./media/image82.png
   :width: 0.23958in
   :height: 0.23958in
.. |image223| image:: ./media/image83.png
   :width: 0.25in
   :height: 0.22917in
.. |image224| image:: ./media/image103.PNG
   :width: 2.72955in
   :height: 1.56272in
.. |image225| image:: ./media/image104.png
   :width: 4.51493in
   :height: 2.18943in
.. |image226| image:: ./media/image105.png
   :width: 4.11194in
   :height: 2.29359in
.. |image227| image:: ./media/image106.png
   :width: 1.98958in
   :height: 1.76042in
.. |image228| image:: ./media/image107.png
   :width: 2.21875in
   :height: 0.375in
.. |image229| image:: ./media/image108.jpeg
   :width: 6.26806in
   :height: 4.18472in
.. |image230| image:: ./media/image109.png
   :width: 4.53125in
   :height: 1.51042in
.. |image231| image:: ./media/image110.png
   :width: 2.4375in
   :height: 2.16667in
.. |image232| image:: ./media/image111.png
   :width: 3.42609in
   :height: 2.41743in
.. |image233| image:: ./media/image112.png
   :width: 6.26806in
   :height: 3.09931in
.. |image234| image:: ./media/image113.png
   :width: 3.39583in
   :height: 2.40625in
.. |image235| image:: ./media/image114.png
   :width: 3.95833in
   :height: 1.33333in
.. |image236| image:: ./media/image115.png
   :width: 4.2in
   :height: 2.10363in
.. |image237| image:: ./media/image116.png
   :width: 4.63478in
   :height: 2.15051in
.. |image238| image:: ./media/image117.png
   :width: 6.26806in
   :height: 4.57917in
.. |image239| image:: ./media/image118.png
   :width: 6.26806in
   :height: 3.89514in
.. |image240| image:: ./media/image119.png
   :width: 4.38542in
   :height: 1.84375in
.. |image241| image:: ./media/image120.png
   :width: 6.26806in
   :height: 1.51597in
.. |image242| image:: ./media/image121.png
   :width: 3.15625in
   :height: 0.9375in
.. |image243| image:: ./media/image122.png
   :width: 6.26806in
   :height: 1.75347in
.. |image244| image:: ./media/image123.png
   :width: 5.27083in
   :height: 1.5625in
.. |image245| image:: ./media/image124.png
   :width: 5.41667in
   :height: 1.4375in
.. |image246| image:: ./media/image125.png
   :width: 4.45833in
   :height: 1.61458in
.. |image247| image:: ./media/image126.png
   :width: 6.26806in
   :height: 2.78125in
.. |image248| image:: ./media/image127.png
   :width: 5.0625in
   :height: 1.625in
.. |image249| image:: ./media/image128.png
   :width: 2.88542in
   :height: 0.70833in
.. |image250| image:: ./media/image129.png
   :width: 2.85417in
   :height: 1.29167in
.. |image251| image:: ./media/image130.png
   :width: 6.26806in
   :height: 2.66597in
.. |image252| image:: ./media/image131.png
   :width: 2.35417in
   :height: 1.59375in
.. |image253| image:: ./media/image132.jpeg
   :width: 6.26806in
   :height: 4.17847in
.. |image254| image:: ./media/image133.PNG
   :width: 4.10474in
   :height: 1.77108in
.. |image255| image:: ./media/image134.PNG
   :width: 5.27157in
   :height: 1.59397in
.. |image256| image:: ./media/image135.PNG
   :width: 6.26806in
   :height: 1.56111in
.. |image257| image:: ./media/image136.PNG
   :width: 2.2399in
   :height: 1.34394in
.. |image258| image:: ./media/image137.PNG
   :width: 3.27129in
   :height: 1.10432in
.. |image259| image:: ./media/image138.PNG
   :width: 5.2924in
   :height: 2.25031in
.. |image260| image:: ./media/image139.PNG
   :width: 4.39645in
   :height: 1.22934in
.. |image261| image:: ./media/image140.PNG
   :width: 2.46909in
   :height: 1.26059in
.. |image262| image:: ./media/image141.PNG
   :width: 6.26806in
   :height: 3.07431in
.. |image263| image:: ./media/image142.PNG
   :width: 4.5423in
   :height: 2.93791in
.. |image264| image:: ./media/image143.PNG
   :width: 2.56286in
   :height: 1.68774in
.. |image265| image:: ./media/image144.PNG
   :width: 4.6569in
   :height: 3.81303in
.. |image266| image:: ./media/image145.png
   :width: 3.84375in
   :height: 1.21875in
.. |image267| image:: ./media/image146.PNG
   :width: 4.07349in
   :height: 4.91735in
.. |image268| image:: ./media/image147.PNG
   :width: 3.9693in
   :height: 1.27101in
.. |image269| image:: ./media/image148.png
   :width: 2.75in
   :height: 1.27083in
.. |image270| image:: ./media/image149.PNG
   :width: 3.42756in
   :height: 1.67732in
.. |image271| image:: ./media/image150.PNG
   :width: 5.88624in
   :height: 2.14613in
.. |image272| image:: ./media/image151.png
   :width: 5.21875in
   :height: 2.38542in
.. |image273| image:: ./media/image152.png
   :width: 6.26806in
   :height: 2.43194in
.. |image274| image:: ./media/image153.png
   :width: 2.65625in
   :height: 1.75in
.. |image275| image:: ./media/image154.PNG
   :width: 6.17795in
   :height: 2.52119in
.. |image276| image:: ./media/image155.png
   :width: 5.92708in
   :height: 3.05208in
.. |image277| image:: ./media/image156.PNG
   :width: 4.57356in
   :height: 2.00028in
.. |image278| image:: ./media/image157.PNG
   :width: 3.69843in
   :height: 4.68815in
.. |image279| image:: ./media/image158.PNG
   :width: 2.77122in
   :height: 1.76066in
.. |image280| image:: ./media/image159.PNG
   :width: 5.87582in
   :height: 2.78164in
.. |image281| image:: ./media/image160.png
   :width: 5.48958in
   :height: 2.76042in
.. |image282| image:: ./media/image161.png
   :width: 6.26806in
   :height: 4.40694in
.. |image283| image:: ./media/image162.png
   :width: 5.82292in
   :height: 2.22917in
.. |image284| image:: ./media/image163.PNG
   :width: 3.66718in
   :height: 1.5523in
.. |image285| image:: ./media/image164.PNG
   :width: 4.61523in
   :height: 1.76066in
.. |image286| image:: ./media/image165.PNG
   :width: 2.79206in
   :height: 1.96902in
.. |image287| image:: ./media/image166.PNG
   :width: 5.47993in
   :height: 2.25031in
.. |image288| image:: ./media/image167.PNG
   :width: 4.0839in
   :height: 2.60453in
.. |image289| image:: ./media/image168.png
   :width: 4.58333in
   :height: 1.72917in
.. |image290| image:: ./media/image169.PNG
   :width: 4.808in
   :height: 5.82649in
.. |image291| image:: ./media/image170.PNG
   :width: 4.43812in
   :height: 1.38561in
.. |image292| image:: ./media/image171.PNG
   :width: 4.28185in
   :height: 6.98014in
.. |image293| image:: ./media/image172.PNG
   :width: 4.33394in
   :height: 2.36491in
.. |image294| image:: ./media/image173.PNG
   :width: 3.63592in
   :height: 5.04237in
.. |image295| image:: ./media/image174.PNG
   :width: 3.02126in
   :height: 1.7815in
.. |image296| image:: ./media/image175.png
   :width: 3.808in
   :height: 3.13641in
.. |image297| image:: ./media/image176.png
   :width: 6.26806in
   :height: 3.85486in
.. |image298| image:: ./media/image177.png
   :width: 5.08333in
   :height: 6.25in
.. |image299| image:: ./media/image178.png
   :width: 5.53125in
   :height: 1.57292in
.. |image300| image:: ./media/image179.png
   :width: 6.26806in
   :height: 1.39306in
.. |image301| image:: ./media/image180.png
   :width: 4.42721in
   :height: 3.02609in
.. |image302| image:: ./media/image181.png
   :width: 6.26806in
   :height: 2.59861in
.. |image303| image:: ./media/image182.png
   :width: 2.11458in
   :height: 0.89583in
.. |image304| image:: ./media/image183.png
   :width: 6.26806in
   :height: 4.84236in
.. |image305| image:: ./media/image178.png
   :width: 5.53125in
   :height: 1.57292in
.. |image306| image:: ./media/image184.png
   :width: 6.26806in
   :height: 0.97639in
.. |image307| image:: ./media/image185.png
   :width: 6.26806in
   :height: 4.01597in
.. |image308| image:: ./media/image186.png
   :width: 2.26087in
   :height: 0.89138in
.. |image309| image:: ./media/image187.png
   :width: 6.26806in
   :height: 2.25903in
.. |image310| image:: ./media/image188.png
   :width: 3.41667in
   :height: 1.32292in
.. |image311| image:: ./media/image189.png
   :width: 4.42708in
   :height: 1.21875in
.. |image312| image:: ./media/image190.png
   :width: 2.75in
   :height: 1.21875in
.. |image313| image:: ./media/image191.png
   :width: 3.65625in
   :height: 1.86458in
.. |image314| image:: ./media/image192.png
   :width: 2.3806in
   :height: 1.10012in
.. |image315| image:: ./media/image193.png
   :width: 2.28358in
   :height: 1.4452in
.. |image316| image:: ./media/image194.png
   :width: 3.17164in
   :height: 2.38458in
.. |image317| image:: ./media/image195.png
   :width: 2.14925in
   :height: 0.99322in
.. |image318| image:: ./media/image196.png
   :width: 3.30597in
   :height: 0.91876in
.. |image319| image:: ./media/image197.png
   :width: 3.32836in
   :height: 1.95586in
.. |image320| image:: ./media/image198.png
   :width: 3.23958in
   :height: 2.09375in
.. |image321| image:: ./media/image199.png
   :width: 4.66956in
   :height: 1.78797in
.. |image322| image:: ./media/image200.png
   :width: 2.27574in
   :height: 2.94783in
.. |image323| image:: ./media/image201.png
   :width: 6.26806in
   :height: 1.80347in
.. |image324| image:: ./media/image202.png
   :width: 5.0087in
   :height: 1.10804in
.. |image325| image:: ./media/image203.png
   :width: 4.87826in
   :height: 1.15633in
.. |image326| image:: ./media/image204.png
   :width: 4.93044in
   :height: 1.2124in
.. |image327| image:: ./media/image205.png
   :width: 4.02083in
   :height: 6.17708in
.. |image328| image:: ./media/image206.png
   :width: 3.97917in
   :height: 2.11458in
.. |image329| image:: ./media/image207.png
   :width: 4.36458in
   :height: 0.82292in
.. |image330| image:: ./media/image208.png
   :width: 3.89583in
   :height: 1.92708in
.. |image331| image:: ./media/image209.png
   :width: 3.5in
   :height: 1.30208in
.. |image332| image:: ./media/image210.png
   :width: 4.73044in
   :height: 1.71204in
.. |image333| image:: ./media/image211.png
   :width: 6.26806in
   :height: 0.90764in
.. |image334| image:: ./media/image212.png
   :width: 2.98958in
   :height: 1.38542in
.. |image335| image:: ./media/image213.png
   :width: 3.17708in
   :height: 1.27083in
.. |image336| image:: ./media/image214.png
   :width: 4.65625in
   :height: 2.22917in
.. |image337| image:: ./media/image215.png
   :width: 5.375in
   :height: 2.83333in
.. |image338| image:: ./media/image216.png
   :width: 3.39583in
   :height: 2.70833in
.. |image339| image:: ./media/image217.png
   :width: 3.5in
   :height: 1.30208in
.. |image340| image:: ./media/image218.png
   :width: 3.5in
   :height: 1.30208in
.. |image341| image:: ./media/image219.png
   :width: 3.75in
   :height: 1.91667in
.. |image342| image:: ./media/image220.png
   :width: 4.63542in
   :height: 2.60417in
.. |image343| image:: ./media/image221.png
   :width: 5.17708in
   :height: 2.65625in
.. |image344| image:: ./media/image222.png
   :width: 4.0625in
   :height: 2.5625in
.. |image345| image:: ./media/image223.png
   :width: 0.65348in
   :height: 3.184in
.. |image346| image:: ./media/image224.png
   :width: 2.024in
   :height: 2.62704in
.. |image347| image:: ./media/image225.png
   :width: 0.95228in
   :height: 2.488in
.. |image348| image:: ./media/image226.png
   :width: 1.09375in
   :height: 2.77083in
.. |image349| image:: ./media/image227.png
   :width: 1.42708in
   :height: 2.76042in
.. |image350| image:: ./media/image228.png
   :width: 2.33333in
   :height: 2.13542in
.. |image351| image:: ./media/image229.png
   :width: 1.3125in
   :height: 2.86458in
.. |image352| image:: ./media/image230.png
   :width: 3.05208in
   :height: 2.88542in
.. |image353| image:: ./media/image231.png
   :width: 0.89583in
   :height: 2.1875in
.. |image354| image:: ./media/image232.png
   :width: 6.26806in
   :height: 2.67778in
.. |image355| image:: ./media/image233.png
   :width: 3.93044in
   :height: 1.7347in
.. |image356| image:: ./media/image234.png
   :width: 2.75726in
   :height: 3.32174in
.. |image357| image:: ./media/image235.png
   :width: 4.05208in
   :height: 1.14583in
.. |image358| image:: ./media/image236.png
   :width: 3.464in
   :height: 3.70901in
.. |image359| image:: ./media/image237.png
   :width: 2.76042in
   :height: 0.64583in
.. |image360| image:: ./media/image238.png
   :width: 3.4375in
   :height: 1.77083in
.. |image361| image:: ./media/image239.png
   :width: 6.26806in
   :height: 5.00764in
.. |image362| image:: ./media/image240.png
   :width: 3.05614in
   :height: 4.04348in
.. |image363| image:: ./media/image241.png
   :width: 4.32174in
   :height: 2.41416in
.. |image364| image:: ./media/image242.png
   :width: 4.22917in
   :height: 1.44792in
.. |image365| image:: ./media/image243.png
   :width: 2.17391in
   :height: 1.00461in
.. |image366| image:: ./media/image244.png
   :width: 2.17361in
   :height: 0.90312in
.. |image367| image:: ./media/image245.png
   :width: 4.73044in
   :height: 1.66923in
.. |image368| image:: ./media/image243.png
   :width: 2.17361in
   :height: 1.00447in
.. |image369| image:: ./media/image246.png
   :width: 3.3125in
   :height: 1.45833in
.. |image370| image:: ./media/image247.png
   :width: 3.09565in
   :height: 1.71418in
.. |image371| image:: ./media/image248.png
   :width: 2.82609in
   :height: 1.13211in
.. |image372| image:: ./media/image249.png
   :width: 3in
   :height: 1.4742in
.. |image373| image:: ./media/image250.png
   :width: 4.30435in
   :height: 1.98271in
.. |image374| image:: ./media/image251.png
   :width: 4.79167in
   :height: 2.09375in
.. |image375| image:: ./media/image252.png
   :width: 2.52174in
   :height: 1.67284in
.. |image376| image:: ./media/image253.png
   :width: 2.2087in
   :height: 1.02068in
.. |image377| image:: ./media/image254.png
   :width: 2.39583in
   :height: 1.60417in
.. |image378| image:: ./media/image255.png
   :width: 4.26042in
   :height: 2.15625in
.. |image379| image:: ./media/image256.png
   :width: 3.73044in
   :height: 2.85223in
.. |image380| image:: ./media/image257.png
   :width: 2.64348in
   :height: 1.19838in
.. |image381| image:: ./media/image258.png
   :width: 1.91523in
   :height: 2.53913in
.. |image382| image:: ./media/image259.png
   :width: 2.23478in
   :height: 1.03274in
.. |image383| image:: ./media/image260.png
   :width: 2.03948in
   :height: 2.67826in
.. |image384| image:: ./media/image261.png
   :width: 3.44821in
   :height: 2.87826in
.. |image385| image:: ./media/image262.png
   :width: 3.1913in
   :height: 1.83906in
.. |image386| image:: ./media/image263.png
   :width: 3.67826in
   :height: 3.04279in
.. |image387| image:: ./media/image264.png
   :width: 3.36458in
   :height: 2.17708in
.. |image388| image:: ./media/image265.jpeg
   :width: 6.26806in
   :height: 4.70139in
.. |image389| image:: ./media/image266.png
   :width: 2.41667in
   :height: 1.17708in
.. |image390| image:: ./media/image267.png
   :width: 4.88696in
   :height: 1.68764in
.. |image391| image:: ./media/image268.png
   :width: 2.37391in
   :height: 1.09704in
.. |image392| image:: ./media/image269.png
   :width: 4.47826in
   :height: 1.54634in
.. |image393| image:: ./media/image270.png
   :width: 4.66956in
   :height: 2.21838in
.. |image394| image:: ./media/image271.png
   :width: 2.69792in
   :height: 1.3125in
.. |image395| image:: ./media/image272.png
   :width: 4.03125in
   :height: 2.53125in
.. |image396| image:: ./media/image273.png
   :width: 3.84375in
   :height: 2.23958in
.. |image397| image:: ./media/image274.png
   :width: 5.61739in
   :height: 0.81715in
.. |image398| image:: ./media/image275.png
   :width: 2.63542in
   :height: 1.20833in
.. |image399| image:: ./media/image276.png
   :width: 3.71737in
   :height: 2.37391in
.. |image400| image:: ./media/image277.png
   :width: 3.45833in
   :height: 2.08333in
.. |image401| image:: ./media/image278.PNG
   :width: 2.0107in
   :height: 1.60439in
.. |image402| image:: ./media/image279.PNG
   :width: 5.19353in
   :height: 1.14692in
.. |image403| image:: ./media/image280.PNG
   :width: 0.51049in
   :height: 0.42714in
.. |image404| image:: ./media/image281.PNG
   :width: 2.47951in
   :height: 2.13572in
.. |image405| image:: ./media/image274.png
   :width: 5.61739in
   :height: 0.81715in
.. |image406| image:: ./media/image282.png
   :width: 2.67826in
   :height: 1.10727in
.. |image407| image:: ./media/image283.png
   :width: 2.38261in
   :height: 1.75604in
.. |image408| image:: ./media/image284.png
   :width: 3.47917in
   :height: 1.5in
.. |image409| image:: ./media/image285.png
   :width: 4.70435in
   :height: 1.89825in
.. |image410| image:: ./media/image286.png
   :width: 2.37391in
   :height: 1.09704in
.. |image411| image:: ./media/image287.png
   :width: 3.2in
   :height: 1.36658in
.. |image412| image:: ./media/image288.png
   :width: 4.94783in
   :height: 2.37031in
.. |image413| image:: ./media/image289.png
   :width: 2.29167in
   :height: 1in
.. |image414| image:: ./media/image290.png
   :width: 2.21875in
   :height: 0.94792in
.. |image415| image:: ./media/image291.png
   :width: 4.14878in
   :height: 3.07826in
.. |image416| image:: ./media/image292.png
   :width: 4.26087in
   :height: 3.31321in
.. |image417| image:: ./media/image293.png
   :width: 3.03478in
   :height: 1.80578in
.. |image418| image:: ./media/image294.png
   :width: 4.1913in
   :height: 2.66261in
.. |image419| image:: ./media/image295.PNG
   :width: 5.16667in
   :height: 1.17244in
.. |image420| image:: ./media/image296.png
   :width: 5.36458in
   :height: 0.72917in
.. |image421| image:: ./media/image297.png
   :width: 1.64583in
   :height: 1.84375in
.. |image422| image:: ./media/image298.png
   :width: 2.11231in
   :height: 2.97391in
.. |image423| image:: ./media/image299.png
   :width: 2.98261in
   :height: 1.11944in
.. |image424| image:: ./media/image300.png
   :width: 3.02609in
   :height: 1.20722in
.. |image425| image:: ./media/image301.png
   :width: 2.92708in
   :height: 2.64583in
.. |image426| image:: ./media/image302.png
   :width: 4.22609in
   :height: 3.03523in
.. |image427| image:: ./media/image303.png
   :width: 2.75in
   :height: 1.27083in
.. |image428| image:: ./media/image304.png
   :width: 3.07826in
   :height: 2.36311in
.. |image429| image:: ./media/image305.png
   :width: 6.26806in
   :height: 4.88333in
.. |image430| image:: ./media/image306.png
   :width: 6.26806in
   :height: 3.09653in
.. |image431| image:: ./media/image307.png
   :width: 6.26806in
   :height: 4.625in
.. |image432| image:: ./media/image308.png
   :width: 3.024in
   :height: 2.05978in
.. |image433| image:: ./media/image309.png
   :width: 5.15652in
   :height: 1.92984in
.. |image434| image:: ./media/image310.png
   :width: 2.25217in
   :height: 1.04078in
.. |image435| image:: ./media/image311.png
   :width: 3.23478in
   :height: 1.24794in
.. |image436| image:: ./media/image312.png
   :width: 2.3125in
   :height: 1.04167in
.. |image437| image:: ./media/image313.png
   :width: 0.32292in
   :height: 0.34375in
.. |image438| image:: ./media/image314.png
   :width: 0.33333in
   :height: 0.30208in
.. |image439| image:: ./media/image315.png
   :width: 0.35417in
   :height: 0.33333in
.. |image440| image:: ./media/image316.png
   :width: 0.36458in
   :height: 0.34375in
.. |image441| image:: ./media/image317.png
   :width: 2.08333in
   :height: 0.98958in
.. |image442| image:: ./media/image318.png
   :width: 4.10435in
   :height: 1.77843in
.. |image443| image:: ./media/image319.png
   :width: 4.30208in
   :height: 1.79167in
.. |image444| image:: ./media/image320.png
   :width: 2.65625in
   :height: 1.38542in
.. |image445| image:: ./media/image321.png
   :width: 4.48958in
   :height: 1.84375in
.. |image446| image:: ./media/image322.png
   :width: 2.32292in
   :height: 1in
.. |image447| image:: ./media/image323.png
   :width: 2.41667in
   :height: 1.41667in
.. |image448| image:: ./media/image324.png
   :width: 3.5in
   :height: 1.47917in
.. |image449| image:: ./media/image325.png
   :width: 4.3125in
   :height: 1.98958in
.. |image450| image:: ./media/image326.png
   :width: 2.74107in
   :height: 2.03478in
.. |image451| image:: ./media/image327.png
   :width: 3.04522in
   :height: 1.7913in
.. |image452| image:: ./media/image328.png
   :width: 2.22917in
   :height: 0.98958in
.. |image453| image:: ./media/image329.png
   :width: 6.03125in
   :height: 1.86458in
.. |image454| image:: ./media/image330.png
   :width: 4.11458in
   :height: 2.32292in
.. |image455| image:: ./media/image331.PNG
   :width: 3.06293in
   :height: 1.54188in
.. |image456| image:: ./media/image332.PNG
   :width: 6.26806in
   :height: 1.34653in
.. |image457| image:: ./media/image333.png
   :width: 5.90625in
   :height: 1.0625in
.. |image458| image:: ./media/image334.PNG
   :width: 4.76181in
   :height: 4.98174in
.. |image459| image:: ./media/image335.png
   :width: 2.23958in
   :height: 1.01042in
.. |cid:56bf7827-d83e-41d9-a893-ba263016cf41| image:: ./media/image336.jpeg
   :width: 1.73194in
   :height: 2.88611in
.. |image460| image:: ./media/image337.png
   :width: 1.80208in
   :height: 1.73958in
.. |image461| image:: ./media/image338.png
   :width: 2.6748in
   :height: 2.02399in
.. |image462| image:: ./media/image339.png
   :width: 4.9375in
   :height: 1.44792in
.. |image463| image:: ./media/image340.png
   :width: 5.0625in
   :height: 0.90625in
.. |image464| image:: ./media/image341.png
   :width: 3.80505in
   :height: 3.82114in
.. |image465| image:: ./media/image342.png
   :width: 6.26806in
   :height: 2.00278in
.. |image466| image:: ./media/image343.jpeg
   :width: 6.26806in
   :height: 4.18333in
.. |image467| image:: ./media/image344.png
   :width: 5.1875in
   :height: 1.41667in
.. |image468| image:: ./media/image345.png
   :width: 2.3209in
   :height: 0.92007in
.. |image469| image:: ./media/image346.png
   :width: 2.27612in
   :height: 1.10262in
.. |image470| image:: ./media/image347.png
   :width: 2.62687in
   :height: 1.38453in
.. |image471| image:: ./media/image348.png
   :width: 2.83582in
   :height: 1.21963in
.. |image472| image:: ./media/image349.png
   :width: 2.8806in
   :height: 1.69597in
.. |image473| image:: ./media/image350.png
   :width: 4.31343in
   :height: 1.72136in
.. |image474| image:: ./media/image351.png
   :width: 2.75in
   :height: 1.27083in
.. |image475| image:: ./media/image352.png
   :width: 2.27083in
   :height: 1in
.. |image476| image:: ./media/image353.png
   :width: 4.28358in
   :height: 2.54376in
.. |image477| image:: ./media/image348.png
   :width: 2.83582in
   :height: 1.21963in
.. |image478| image:: ./media/image354.png
   :width: 6.26806in
   :height: 2.34514in
.. |image479| image:: ./media/image355.png
   :width: 2.79104in
   :height: 0.94912in
.. |image480| image:: ./media/image356.png
   :width: 4.54478in
   :height: 2.11076in
.. |image481| image:: ./media/image357.png
   :width: 4.16418in
   :height: 1.83896in
.. |image482| image:: ./media/image358.png
   :width: 4.35211in
   :height: 2.28358in
.. |image483| image:: ./media/image359.png
   :width: 4.41791in
   :height: 2.11449in
.. |image484| image:: ./media/image360.png
   :width: 4.28358in
   :height: 2.33637in
.. |image485| image:: ./media/image361.png
   :width: 4.11194in
   :height: 2.29879in
.. |image486| image:: ./media/image362.png
   :width: 4.25373in
   :height: 2.2494in
.. |image487| image:: ./media/image363.png
   :width: 4.06716in
   :height: 1.52665in
.. |image488| image:: ./media/image364.png
   :width: 6.09701in
   :height: 4.33465in
.. |image489| image:: ./media/image365.png
   :width: 6.26806in
   :height: 1.41319in
.. |image490| image:: ./media/image366.png
   :width: 4.0597in
   :height: 2.11653in
.. |image491| image:: ./media/image367.png
   :width: 2.89583in
   :height: 1.625in
.. |image492| image:: ./media/image368.png
   :width: 1.26866in
   :height: 1.26866in
.. |image493| image:: ./media/image369.png
   :width: 6.26806in
   :height: 2.25486in
.. |image494| image:: ./media/image370.png
   :width: 4.35417in
   :height: 2.28125in
.. |image495| image:: ./media/image371.png
   :width: 3.58209in
   :height: 1.18904in
.. |image496| image:: ./media/image372.png
   :width: 2.8209in
   :height: 2.45691in
.. |image497| image:: ./media/image373.png
   :width: 6.26806in
   :height: 2.28056in
.. |image498| image:: ./media/image374.png
   :width: 6.26806in
   :height: 2.38194in
.. |image499| image:: ./media/image375.png
   :width: 4.4375in
   :height: 1.52083in
.. |image500| image:: ./media/image376.png
   :width: 3.61739in
   :height: 1.66653in
.. |image501| image:: ./media/image377.png
   :width: 4.4087in
   :height: 2.00321in
.. |image502| image:: ./media/image378.png
   :width: 6.26806in
   :height: 2.66042in
.. |image503| image:: ./media/image379.png
   :width: 6.26806in
   :height: 2.39583in
.. |image504| image:: ./media/image380.png
   :width: 5.07826in
   :height: 2.46543in
.. |image505| image:: ./media/image381.png
   :width: 2.93284in
   :height: 1.45296in
.. |image506| image:: ./media/image382.png
   :width: 4.76119in
   :height: 2.12054in
.. |image507| image:: ./media/image383.png
   :width: 2.52239in
   :height: 1.21998in
.. |image508| image:: ./media/image384.png
   :width: 3.18657in
   :height: 1.77434in
.. |image509| image:: ./media/image385.png
   :width: 2.6194in
   :height: 1.35336in
.. |image510| image:: ./media/image386.png
   :width: 4.38806in
   :height: 2.65637in
.. |image511| image:: ./media/image387.png
   :width: 2.25in
   :height: 1in
.. |image512| image:: ./media/image388.png
   :width: 6.26806in
   :height: 2.59583in
.. |image513| image:: ./media/image389.png
   :width: 2.16667in
   :height: 0.95833in
.. |image514| image:: ./media/image390.png
   :width: 6.26806in
   :height: 2.48056in
.. |image515| image:: ./media/image391.png
   :width: 6.26806in
   :height: 2.11042in
.. |image516| image:: ./media/image392.png
   :width: 3.65672in
   :height: 1.83648in
.. |image517| image:: ./media/image393.png
   :width: 1.24627in
   :height: 0.70841in
.. |image518| image:: ./media/image394.png
   :width: 6.26806in
   :height: 1.15556in
.. |image519| image:: ./media/image395.png
   :width: 4.1913in
   :height: 1.56147in
.. |image520| image:: ./media/image396.png
   :width: 6.26806in
   :height: 1.83125in
.. |image521| image:: ./media/image397.png
   :width: 6.26806in
   :height: 2.3375in
.. |image522| image:: ./media/image398.png
   :width: 6.26806in
   :height: 2.34028in
.. |image523| image:: ./media/image399.png
   :width: 6.26806in
   :height: 2.16597in
.. |image524| image:: ./media/image400.png
   :width: 3.07463in
   :height: 2.0791in
.. |image525| image:: ./media/image401.png
   :width: 3.09952in
   :height: 1.64179in
.. |image526| image:: ./media/image402.png
   :width: 6.26806in
   :height: 2.44097in
.. |image527| image:: ./media/image403.png
   :width: 2.73134in
   :height: 0.98632in
.. |image528| image:: ./media/image404.png
   :width: 2.26866in
   :height: 1.04839in
.. |image529| image:: ./media/image405.png
   :width: 6.26806in
   :height: 2.35278in
.. |image530| image:: ./media/image52.png
   :width: 5.20833in
   :height: 2.65625in
.. |image531| image:: ./media/image406.PNG
   :width: 6.26806in
   :height: 2.67292in
.. |image532| image:: ./media/image407.PNG
   :width: 6.26806in
   :height: 2.08889in
.. |image533| image:: ./media/image408.jpeg
   :width: 6.26806in
   :height: 4.69792in
.. |image534| image:: ./media/image409.PNG
   :width: 2.96916in
   :height: 2.36491in
.. |image535| image:: ./media/image410.PNG
   :width: 2.79206in
   :height: 1.31268in
.. |image536| image:: ./media/image411.PNG
   :width: 2.26073in
   :height: 1.87526in
.. |image537| image:: ./media/image412.PNG
   :width: 3.03167in
   :height: 1.86484in
.. |image538| image:: ./media/image413.PNG
   :width: 4.05265in
   :height: 1.73983in
.. |image539| image:: ./media/image414.PNG
   :width: 2.52119in
   :height: 1.37519in
.. |image540| image:: ./media/image415.PNG
   :width: 3.05251in
   :height: 2.34408in
.. |image541| image:: ./media/image416.PNG
   :width: 6.26806in
   :height: 2.68333in
.. |image542| image:: ./media/image417.PNG
   :width: 3.64634in
   :height: 1.27101in
.. |image543| image:: ./media/image418.PNG
   :width: 5.4591in
   :height: 2.45868in
.. |image544| image:: ./media/image419.PNG
   :width: 5.42784in
   :height: 2.46909in
.. |image545| image:: ./media/image420.PNG
   :width: 3.89638in
   :height: 1.77108in
.. |image546| image:: ./media/image421.PNG
   :width: 3.97972in
   :height: 1.87526in
.. |image547| image:: ./media/image422.PNG
   :width: 2.80247in
   :height: 1.33352in
.. |image548| image:: ./media/image423.PNG
   :width: 3.87554in
   :height: 1.17725in
.. |image549| image:: ./media/image424.PNG
   :width: 5.64662in
   :height: 2.42742in
.. |image550| image:: ./media/image425.PNG
   :width: 2.75027in
   :height: 1.23942in
.. |image551| image:: ./media/image426.png
   :width: 6.26806in
   :height: 1.70903in
.. |image552| image:: ./media/image427.PNG
   :width: 6.26806in
   :height: 2.07569in
.. |image553| image:: ./media/image428.PNG
   :width: 2.7088in
   :height: 1.27273in
.. |image554| image:: ./media/image429.PNG
   :width: 3.17753in
   :height: 1.79192in
.. |image555| image:: ./media/image430.PNG
   :width: 2.51077in
   :height: 1.16683in
.. |image556| image:: ./media/image431.PNG
   :width: 2.33366in
   :height: 1.0939in
.. |image557| image:: ./media/image432.PNG
   :width: 2.417in
   :height: 1.22934in
.. |image558| image:: ./media/image433.PNG
   :width: 3.27129in
   :height: 1.28143in
.. |image559| image:: ./media/image434.PNG
   :width: 3.31296in
   :height: 1.57314in
.. |image560| image:: ./media/image435.PNG
   :width: 2.5316in
   :height: 1.08348in
.. |image561| image:: ./media/image436.PNG
   :width: 3.92763in
   :height: 1.79192in
.. |image562| image:: ./media/image437.PNG
   :width: 3.16711in
   :height: 1.88568in
.. |image563| image:: ./media/image438.png
   :width: 0.26042in
   :height: 0.29167in
.. |image564| image:: ./media/image439.png
   :width: 0.21875in
   :height: 0.26042in
.. |image565| image:: ./media/image440.png
   :width: 0.29167in
   :height: 0.27083in
.. |image566| image:: ./media/image441.png
   :width: 0.25in
   :height: 0.22917in
.. |image567| image:: ./media/image442.png
   :width: 0.26042in
   :height: 0.22917in
.. |image568| image:: ./media/image438.png
   :width: 0.26042in
   :height: 0.29167in
.. |image569| image:: ./media/image439.png
   :width: 0.21875in
   :height: 0.26042in
.. |image570| image:: ./media/image440.png
   :width: 0.29167in
   :height: 0.27083in
.. |image571| image:: ./media/image441.png
   :width: 0.25in
   :height: 0.22917in
.. |image572| image:: ./media/image442.png
   :width: 0.26042in
   :height: 0.22917in
.. |image573| image:: ./media/image438.png
   :width: 0.26042in
   :height: 0.29167in
.. |image574| image:: ./media/image439.png
   :width: 0.21875in
   :height: 0.26042in
.. |image575| image:: ./media/image440.png
   :width: 0.29167in
   :height: 0.27083in
.. |image576| image:: ./media/image441.png
   :width: 0.25in
   :height: 0.22917in
.. |image577| image:: ./media/image442.png
   :width: 0.26042in
   :height: 0.22917in
.. |image578| image:: ./media/image443.PNG
   :width: 5.4591in
   :height: 1.92735in
.. |image579| image:: ./media/image444.PNG
   :width: 4.05265in
   :height: 1.54188in
.. |image580| image:: ./media/image445.PNG
   :width: 2.62537in
   :height: 1.98986in
.. |image581| image:: ./media/image446.png
   :width: 4.01912in
   :height: 1.49028in
.. |image582| image:: ./media/image447.PNG
   :width: 1.87526in
   :height: 1.72941in
.. |image583| image:: ./media/image448.PNG
   :width: 2.0107in
   :height: 0.90638in
.. |image584| image:: ./media/image449.PNG
   :width: 6.26806in
   :height: 1.38217in
.. |image585| image:: ./media/image450.PNG
   :width: 2.85456in
   :height: 2.0107in
.. |image586| image:: ./media/image451.PNG
   :width: 2.73781in
   :height: 1.25665in
.. |image587| image:: ./media/image452.PNG
   :width: 6.26806in
   :height: 2.33264in
.. |image588| image:: ./media/image453.PNG
   :width: 4.87568in
   :height: 1.23976in
.. |image589| image:: ./media/image454.PNG
   :width: 5.35491in
   :height: 2.59411in
.. |image590| image:: ./media/image455.PNG
   :width: 2.7462in
   :height: 1.26389in
.. |image591| image:: ./media/image456.PNG
   :width: 6.26806in
   :height: 1.25486in
.. |image592| image:: ./media/image457.PNG
   :width: 2.1253in
   :height: 2.00028in
.. |image593| image:: ./media/image458.PNG
   :width: 6.26806in
   :height: 2.09097in
.. |image594| image:: ./media/image459.PNG
   :width: 2.75485in
   :height: 1.26528in
.. |image595| image:: ./media/image460.PNG
   :width: 4.01895in
   :height: 1.47917in
.. |image596| image:: ./media/image461.PNG
   :width: 2.74306in
   :height: 1.22467in
.. |image597| image:: ./media/image462.PNG
   :width: 6.26806in
   :height: 1.38889in
.. |image598| image:: ./media/image463.PNG
   :width: 6.13627in
   :height: 2.83373in
.. |image599| image:: ./media/image464.PNG
   :width: 4.54047in
   :height: 1.20694in
.. |image600| image:: ./media/image465.png
   :width: 6.26806in
   :height: 3.19583in
.. |image601| image:: ./media/image466.png
   :width: 6.26806in
   :height: 2.89583in
.. |image602| image:: ./media/image467.PNG
   :width: 4.40686in
   :height: 4.8861in
.. |image603| image:: ./media/image468.PNG
   :width: 6.26806in
   :height: 3.84028in
.. |image604| image:: ./media/image469.jpeg
   :width: 6.26806in
   :height: 6.26806in
.. |image605| image:: ./media/image470.png
   :width: 2.54545in
   :height: 1.92in
.. |image606| image:: ./media/image471.png
   :width: 4.66234in
   :height: 2.62353in
.. |image607| image:: ./media/image472.png
   :width: 1.875in
   :height: 0.6875in
.. |image608| image:: ./media/image473.png
   :width: 3.46104in
   :height: 1.27736in
.. |image609| image:: ./media/image474.png
   :width: 3.41558in
   :height: 2.06099in
.. |image610| image:: ./media/image475.png
   :width: 3.21875in
   :height: 1.11458in
.. |image611| image:: ./media/image476.png
   :width: 4.11039in
   :height: 1.48328in
.. |image612| image:: ./media/image477.png
   :width: 4.77273in
   :height: 3.72734in
.. |image613| image:: ./media/image478.png
   :width: 3.11039in
   :height: 1.60895in
.. |image614| image:: ./media/image479.png
   :width: 2.08442in
   :height: 0.96325in
.. |image615| image:: ./media/image480.png
   :width: 6.26806in
   :height: 2.88542in
.. |image616| image:: ./media/image481.png
   :width: 3.04167in
   :height: 1.89583in
.. |image617| image:: ./media/image482.png
   :width: 4.30519in
   :height: 2.42829in
.. |image618| image:: ./media/image483.png
   :width: 2.48052in
   :height: 1.07569in
.. |image619| image:: ./media/image484.png
   :width: 3.92208in
   :height: 1.91825in
.. |image620| image:: ./media/image485.png
   :width: 2.19481in
   :height: 1.01427in
.. |image621| image:: ./media/image486.png
   :width: 4.1039in
   :height: 2.1979in
.. |image622| image:: ./media/image487.png
   :width: 3.27922in
   :height: 2.27705in
.. |image623| image:: ./media/image488.png
   :width: 2.41558in
   :height: 1.23397in
.. |image624| image:: ./media/image489.png
   :width: 3.30519in
   :height: 1.17013in
.. |image625| image:: ./media/image490.png
   :width: 3.61087in
   :height: 1.63636in
.. |image626| image:: ./media/image491.png
   :width: 3.22129in
   :height: 3.61688in
.. |image627| image:: ./media/image492.png
   :width: 4.11039in
   :height: 2.82845in
.. |image628| image:: ./media/image493.png
   :width: 4.24675in
   :height: 2.62493in
.. |image629| image:: ./media/image494.png
   :width: 4.03896in
   :height: 2.25486in
.. |image630| image:: ./media/image495.png
   :width: 2.44805in
   :height: 1.1313in
.. |image631| image:: ./media/image496.png
   :width: 3.9026in
   :height: 2.26895in
.. |image632| image:: ./media/image497.png
   :width: 3.42664in
   :height: 3.99351in
.. |image633| image:: ./media/image498.png
   :width: 4.05844in
   :height: 2.38388in
.. |image634| image:: ./media/image499.png
   :width: 6.26806in
   :height: 2.9375in
.. |image635| image:: ./media/image500.png
   :width: 6.26806in
   :height: 3.12083in
.. |image636| image:: ./media/image501.png
   :width: 2.97403in
   :height: 2.35651in
.. |image637| image:: ./media/image502.png
   :width: 3.28571in
   :height: 0.9236in
.. |image638| image:: ./media/image503.png
   :width: 6.26806in
   :height: 1.56458in
.. |image639| image:: ./media/image504.png
   :width: 4.34416in
   :height: 2.65818in
.. |image640| image:: ./media/image505.png
   :width: 4.57792in
   :height: 3.7933in
.. |image641| image:: ./media/image506.png
   :width: 3.96526in
   :height: 2.25325in
.. |image642| image:: ./media/image507.png
   :width: 4.29345in
   :height: 3.48052in
.. |image643| image:: ./media/image508.png
   :width: 3.2013in
   :height: 1.72481in
.. |image644| image:: ./media/image509.png
   :width: 4.33766in
   :height: 2.28946in
.. |image645| image:: ./media/image510.png
   :width: 2.09091in
   :height: 0.96625in
.. |image646| image:: ./media/image511.png
   :width: 3.08442in
   :height: 1.60484in
.. |image647| image:: ./media/image512.png
   :width: 3.69481in
   :height: 1.37931in
.. |image648| image:: ./media/image513.png
   :width: 4.4576in
   :height: 3.67532in
.. |image649| image:: ./media/image514.png
   :width: 2.80495in
   :height: 3.22078in
.. |image650| image:: ./media/image515.png
   :width: 2in
   :height: 0.92424in
.. |image651| image:: ./media/image516.png
   :width: 4.23377in
   :height: 3.27688in
.. |image652| image:: ./media/image517.png
   :width: 4.06494in
   :height: 2.13515in
.. |image653| image:: ./media/image518.png
   :width: 4.25974in
   :height: 2.27145in
.. |image654| image:: ./media/image519.png
   :width: 4.07792in
   :height: 1.73775in
.. |image655| image:: ./media/image520.png
   :width: 3.99351in
   :height: 2.26355in
.. |image656| image:: ./media/image521.png
   :width: 4in
   :height: 2.22557in
.. |image657| image:: ./media/image522.png
   :width: 3.38424in
   :height: 4.05844in
.. |image658| image:: ./media/image523.png
   :width: 4.23582in
   :height: 4.61688in
.. |image659| image:: ./media/image524.png
   :width: 4.02597in
   :height: 2.05407in
.. |image660| image:: ./media/image525.png
   :width: 2.97336in
   :height: 3.6039in
.. |image661| image:: ./media/image526.png
   :width: 2.87801in
   :height: 3.62987in
.. |image662| image:: ./media/image527.png
   :width: 3.06494in
   :height: 3.48025in
.. |image663| image:: ./media/image528.png
   :width: 4.46104in
   :height: 3.08358in
.. |image664| image:: ./media/image529.png
   :width: 4.0974in
   :height: 2.30564in
.. |image665| image:: ./media/image530.png
   :width: 2.21429in
   :height: 1.02327in
.. |image666| image:: ./media/image531.png
   :width: 2.86214in
   :height: 3.38312in
.. |image667| image:: ./media/image532.png
   :width: 3.6699in
   :height: 3.1in
.. |image668| image:: ./media/image533.png
   :width: 4.825in
   :height: 1.88381in
.. |image669| image:: ./media/image534.png
   :width: 5.10585in
   :height: 2.7in
.. |image670| image:: ./media/image535.png
   :width: 2.75in
   :height: 1.27083in
.. |image671| image:: ./media/image536.png
   :width: 5.00833in
   :height: 2.68561in
.. |image672| image:: ./media/image537.png
   :width: 4.31667in
   :height: 3.13157in
.. |image673| image:: ./media/image538.png
   :width: 6.26806in
   :height: 4.09236in
.. |image674| image:: ./media/image539.png
   :width: 5.10417in
   :height: 3.48958in
.. |image675| image:: ./media/image540.png
   :width: 4.67708in
   :height: 1.28125in
.. |image676| image:: ./media/image541.png
   :width: 6.26806in
   :height: 3.38264in
.. |image677| image:: ./media/image542.png
   :width: 3.44792in
   :height: 2.8125in
.. |image678| image:: ./media/image543.png
   :width: 6.26806in
   :height: 3.43681in
.. |image679| image:: ./media/image544.png
   :width: 6.26806in
   :height: 3.05694in
.. |image680| image:: ./media/image545.png
   :width: 4.47917in
   :height: 2.53125in
.. |image681| image:: ./media/image546.png
   :width: 4in
   :height: 1.47917in
.. |image682| image:: ./media/image547.png
   :width: 6.26806in
   :height: 4.36042in
.. |image683| image:: ./media/image548.png
   :width: 6.26806in
   :height: 4.49097in
.. |image684| image:: ./media/image549.png
   :width: 6.26806in
   :height: 5.23125in
.. |image685| image:: ./media/image550.png
   :width: 6.07292in
   :height: 4.25in
.. |image686| image:: ./media/image551.png
   :width: 2.94792in
   :height: 2.09375in
.. |image687| image:: ./media/image552.png
   :width: 6.26806in
   :height: 5.57986in
.. |image688| image:: ./media/image553.jpeg
   :width: 6.26806in
   :height: 3.52569in
.. |image689| image:: ./media/image554.png
   :width: 0.3438in
   :height: 0.35422in
.. |image690| image:: ./media/image555.png
   :width: 6.26806in
   :height: 3.48472in
.. |image691| image:: ./media/image556.png
   :width: 1.552in
   :height: 6.13329in
.. |image692| image:: ./media/image557.png
   :width: 0.44798in
   :height: 0.48965in
.. |image693| image:: ./media/image558.png
   :width: 0.42714in
   :height: 0.35422in
.. |image694| image:: ./media/image559.png
   :width: 0.44798in
   :height: 0.40631in
.. |image695| image:: ./media/image560.png
   :width: 2.15655in
   :height: 1.28143in
.. |image696| image:: ./media/image561.png
   :width: 4.02139in
   :height: 1.48979in
.. |image697| image:: ./media/image562.png
   :width: 2.61495in
   :height: 0.66676in
.. |image698| image:: ./media/image563.png
   :width: 3.97972in
   :height: 2.82331in
.. |image699| image:: ./media/image564.png
   :width: 2.06279in
   :height: 2.17739in
.. |image700| image:: ./media/image565.png
   :width: 2.28474in
   :height: 1.616in
.. |image701| image:: ./media/image566.png
   :width: 2.904in
   :height: 1.696in
.. |image702| image:: ./media/image567.png
   :width: 2.90347in
   :height: 1.68785in
.. |image703| image:: ./media/image568.png
   :width: 2.07321in
   :height: 1.51063in
.. |image704| image:: ./media/image569.png
   :width: 1.98986in
   :height: 1.56272in
.. |image705| image:: ./media/image570.png
   :width: 1.2228in
   :height: 0.96937in
.. |image706| image:: ./media/image571.png
   :width: 1.17147in
   :height: 0.92in
.. |image707| image:: ./media/image572.png
   :width: 4.73311in
   :height: 4.72in
.. |image708| image:: ./media/image559.png
   :width: 0.44798in
   :height: 0.40631in
.. |image709| image:: ./media/image573.png
   :width: 2.08362in
   :height: 2.31282in
.. |image710| image:: ./media/image574.png
   :width: 6.26806in
   :height: 0.45903in
.. |image711| image:: ./media/image575.png
   :width: 2.14613in
   :height: 0.40631in
.. |image712| image:: ./media/image576.png
   :width: 2.5316in
   :height: 0.2292in
.. |image713| image:: ./media/image577.png
   :width: 1.26059in
   :height: 0.3438in
.. |image714| image:: ./media/image578.png
   :width: 1.39603in
   :height: 0.42714in
.. |image715| image:: ./media/image559.png
   :width: 0.44798in
   :height: 0.40631in
.. |image716| image:: ./media/image579.png
   :width: 3.11502in
   :height: 0.30213in
.. |image717| image:: ./media/image580.png
   :width: 6.26806in
   :height: 3.73472in
.. |image718| image:: ./media/image581.png
   :width: 4.33394in
   :height: 5.18822in
.. |image719| image:: ./media/image559.png
   :width: 0.44798in
   :height: 0.40631in
.. |image720| image:: ./media/image582.png
   :width: 3.3913in
   :height: 1.96164in
.. |image721| image:: ./media/image583.png
   :width: 6.26806in
   :height: 0.65625in
.. |image722| image:: ./media/image573.png
   :width: 2.08362in
   :height: 2.31282in
