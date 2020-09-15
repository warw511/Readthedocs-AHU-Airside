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

.. Note:: The *Campus* must be selected first before the other dropdown can be selected. 

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


Point Mapping
*************
*Point Mapping* will be the first tab on the left side of the Economizer page. This will be 
located underneath the main configuration file and the *Default Economizer*. 

.. image:: _images/point_Mapping.jpg

Once *Point Mapping* is selected, configurations will show on the center of the screen. 

.. image:: _images/point_Config.jpg

Once the configuration is shown in the center of the screen, the dropdown inputs 
may be selected to configure. 

All of the *Point Mapping* configuration settings will be drop down inputs that are dependant Upon the 
main configuration file selected for the page. 

.. image:: _images/point_Populate.jpg

Settings
********

Settings is the second tab inside of the Ahu configuration Economizer section. 
Once settings is selected the center section will populate with configurations. 

.. image:: _images/settings_Default.jpg

At the top of the settings page there are two options to choose from: 

.. image:: _images/sensitivity.jpg

**Default**

The settings default page will have preset data available as the settings tab is selected (Default).

When *Default* is selected, on the right side of the page, within the *JSON* code the default data will 
be displayed: 

.. image:: _images/default_Data.jpg 

Underneath the sensitivity options, there are two configuration options: 

**Autocorrect Flag**

Underneath the default selection, there will be another option of two choices: 

.. image:: _images/auto_Flag.jpg

If *False* is selected, there will only be the options of *Number Required Data* and 
*Warm-up Time*. More configuration options will appear if *true* is selected. 

.. image:: _images/auto_false.jpg


.. image:: _images/auto_True.jpg

**Supply Air-tempurature Retuning**

.. image:: _images/supply_Return.jpg

This selection will be a floating point variable type ranging from 1.0 to 3.0. 
The user may input an integer or use the slider to obtain the number required.

**Duct-Static pressure Retuning**

.. image:: _images/duct_Retuning.jpg

This selection will be a floating point variable type ranging from 0.05 to 0.25. 
The user may input an integer or use the slider to obtain the number required.

**Minimum Duct Static Pressure Setpoint**

.. image:: _images/min_Duct.jpg

This selection will be a floating point variable type ranging from 0.25 to 1.0. 
The user may input an integer or use the slider to obtain the number required.

**Maximum Duct Static Pressure Setpoint**

.. image:: _images/max_Duct.jpg

This selection will be an  variable type ranging from 0.25 to 3.0 degrees. 
The user may input an integer or use the slider to obtain the number required.

**Minimum Supply Air-Temperature Setpoint**

.. image:: _images/min_Air.jpg

This selection will be a floating point variable type ranging from 50 to 60. 
The user may input an integer or use the slider to obtain the number required.

**Maximum Supply Air-Temperature Setpoint**

.. image:: _images/max_Air.jpg

This selection will be a floating point variable type ranging from 55 to 75. 
The user may input an integer or use the slider to obtain the number required.

**Number Required Data**

.. image:: _images/number_Data.jpg 

This selection will be an integer type ranging from 1 to 100. 
The user may input an integer or use the slider to obtain the number required.

**Warm-up Time**

.. image:: _images/warm_Time.jpg 

This selection will be an integer type ranging from 5 to 30. 
The user may input an integer or use the slider to obtain the number required.

Thresholds
==========

Thresholds is the third tab in the AHU Airside configuration. 

.. image:: _images/thresholds.jpg 

Once the *Threshold* tab is selected, there will be an option in the center of the screen to choose from 
*Use default threshold (recommended)* or *Customize threshold parameters*. 

**Use Default Threshold**

.. image:: _images/threshold_Option.jpg 

When this option is selected, the default options will be used. The values will be shown inside of the
*JSON* code on the right side of the screen. 

.. image:: _images/default_Thres.jpg 

**Customize threshold parameters**
Once *Customize threshold parameters** is selected, there will be two options to customize:

**Supply-Air Temperature Setpoint Deviation Threshold**
.. image:: _images/supply_Thres.jpg 

This selection will be a integer variable type ranging from 2 to 10. 
The user may input an integer or use the slider to obtain the number required.

**Static Pressure Setpoint Deviation Threshold**

.. image:: _images/static_Dev.jpg 

This selection will be a integer variable type ranging from 10 to 30. 
The user may input an integer or use the slider to obtain the number required.

Saving Files
************

Once everything within the *Economizer* is configured, the last option will be to save the
AHU file. 

.. image:: _images/save_As.jpg

Once the *Save as* button is selected, a new input will appear in the center of the screen. 

.. image:: _images/save_Ascust.jpg

This will allow the user to name the file whatever is desired. The file will automatically create 
the file as a *.json* file as well. 

Once the save button is chosen, it will download to the browser as the file it was named. 

.. image:: _images/ahu_Filejson.jpg