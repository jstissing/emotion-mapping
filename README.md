# e4QGISImporter
A small plugin that allows importing a GPX file and an Empatica E4 EDA file to import the data in QGIS.

The plugin is using [ledapy] (https://github.com/HIIT/Ledapy) to calculate the phasic activity from the EDA if you need it.

So far this plugin has only been tested for QGIS 3.22 under Windows 10/11 and Ubuntu 21.10 / 20.04.

Copy the folder into the plugin folder of QGIS and activate the plugin and restart QGIS. Hopefully it will work :)

It should be also mentioned that if you chose to calculate the phasic activity this process is quite computationally intensive and might take a couple of minutes on older machines.
