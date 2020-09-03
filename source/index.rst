.. Ahu Airside Userguide documentation master file, created by
   sphinx-quickstart on Thu Sep  3 12:47:46 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Ahu Airside Userguide
=====================
Importing Master Driver Configuration Store
*******************************************
At the initial homepage, the user will be prompted to upload the **Master Driver** file. Values within the Master Driver Configuration Store will be parsed to provide options for Campus, Buidling, Device and Points throughout the application.

.. image:: _images/ahu_Frontpage.jpg

Once the user has selected the Master Driver Configuration Store, this homepage will not appear again. 

.. Warning:: Uploading a new Master Driver Configuration Store will remove all current data in the application.

.. image:: _images/master_Driver.jpg

After a *Master Driver* File is uploaded, there will be two new buttons that will appear 
in green below. 

Below The *Master Driver* button, there are two buttons that say:
*AHU File* and *Generate configuration file for...* The *Ahu File* will allow the user to submit a file that has been created by the AHU config 
previously, and the *Generate configuration file for...* will allow the user to create a new configuration file for either the *ECONOMIZER* or *AIRSIDE*. 

Once *Airside* is selected, a new page will appear. 

Airside
*******

This section will go over all of the items that are located within the *Airside* button located in the *Generate configuration file for...* 
button. 

When *Airside* is selected, there will be a popup on screen that appears:

.. image:: _images/selection.jpg

When the Economizer is selected there will be a prompt to select *Campus*,
*Building*, and *Device*. These will all be selected as dropdown inputs. 

.. image:: _images/dropdowns.jpg



AHU Application Configuration
*****************************

The *AHU* Application behavior is controlled through these
configuration Pages:

1.  **Point Mapping**
2.  **Settings**
3.  **Thresholds**

.. toctree::
   :maxdepth: 2
   :caption: Contents:



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
