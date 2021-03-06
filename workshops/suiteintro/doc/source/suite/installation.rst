.. _suite.installation:

Installing the OpenGeo Suite
============================

In this section we will install the OpenGeo Suite on your workshop machine.

Installation
------------

The OpenGeo Suite executable file is located in the workshop package in the :file:`software` folder.

.. note:: During this installation, please keep all of the default settings.

#. **Double-click** the file :file:`OpenGeoSuite-ee-<version>.exe` to begin the installation.

#. On some systems, you might see a Windows Security warning. We promise the software is safe, so click :guilabel:`Run` to launch the installer.

   .. figure:: img/installation_security.png
      :align: center
      
      *Windows Security warning*

#. At the ``Welcome`` screen, click :guilabel:`Next`.

   .. figure:: img/installation_welcome.png
      :align: center

      *OpenGeo Suite installation Welcome screen*

#. Read the *License Agreement*, then click :guilabel:`I Agree`.

   .. figure:: img/installation_license.png
      :align: center

      *License Agreement*

#. Select the *Destination Folder* where you would like to install the OpenGeo Suite, and click :guilabel:`Next`.

   .. figure:: img/installation_directory.png
      :align: center

      *Destination folder for the installation*

#. Select the name and location of the *Start Menu Folder* that will be created for the Suite components, and click :guilabel:`Next`.

   .. figure:: img/installation_startmenu.png
      :align: center

      *Start Menu Folder to be created for the installation*

#. Choose the components you wish to install.

   .. figure:: img/installation_components.png
      :align: center

      *Component selection*

   .. note::  All components are installed by default except for the optional ArcSDE and Oracle Spatial extensions. As these extensions require additional files to function, we will not be using them in this workshop.

#. When you are ready, click :guilabel:`Install` to start the installation.

   .. figure:: img/installation_ready.png
      :align: center

      *Ready to install*

#. Please wait while the installation proceeds.

   .. figure:: img/installation_install.png
      :align: center

      *Installation progress*

#. After installation, click :guilabel:`Finish` to start the OpenGeo Suite and launch the Dashboard.

   .. figure:: img/installation_finish.png
      :align: center

      *The OpenGeo Suite has been installed*
      
The Dashboard is presented in detail the next section.

However, to complete this installation process, we're going to review a few of the initialization steps that need to be performed when you run the OpenGeo Suite Dashboard for the first time.

#. This *Welcome* screen confirms your (default) credentials for authenticating to GeoServer. Click **Close** to proceed. You can uncheck the :guilabel:`Show this dialog ...` box to prevent this dialog from launching in the future if you'd like.

   .. figure:: img/dashboard_geoservercredentials.png
      :align: center
      
      *GeoServer Administration credentials*
      
Although the OpenGeo Suite has been installed, it's not actually running yet. In fact, if you ever re-start your machine, it does not start automatically. Whenever the software isn't running, the Dashboard will display a green :guilabel:`Start` button in the top right corner.

#. Click :guilabel:`Start` to launch the service components that make up the OpenGeo Suite. A dialog will display during the startup process, and will disappear once the software is running.

   .. figure:: img/dashboard_startup.png
      :align: center
   
   *Starting the OpenGeo Suite from the Dashboard*
   
#. On certain operating systems, you might be presented with a *Security Alert* about your PostgreSQL Server. You can click **OK** here. PostgreSQL is the database server that sits underneath PostGIS; we trust it. Optionally, you can check the box to not *show this message again*. 

   .. figure:: img/dashboard_postgresql.png
      :align: center
      
      *Security Alert for PostgreSQL Server*
  
#. Again, on certain operating systems, you might see a *Security Alert* about your Java platform trying to make changes to the local firewall. You can click **Unblock** here. The Java platform is the web application container that GeoServer and other web-applications run in; we also trust this component.

   .. figure:: img/dashboard_javavm.png
      :align: center
      
      *Security Alert for the Java Platform*

#. Once completed, you'll be back at the main Dashboard interface with the OpenGeo Suite up and running.

   .. figure:: img/dashboard_running.png
      :align: center
      
      *The OpenGeo Suite Dashboard (running)*