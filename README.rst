Cacti monitoring scripts
========================

What is Cacti?
--------------

Cacti is open source software for monitoring devices. If a device supports SNMP then Cacti can regularly poll it and graph the results. You can find out more about Cacti on `their website <http://www.cacti.net/>`_.

And what are these templates?
-----------------------------

These templates are host, device and graph templates we have found useful in monitoring devices in our datacentres. Some have been modified from scripts on the Cacti forums - others have been written by us for more specific purposes.

And I can just use them?
------------------------

You can download and use these scripts in any way you like! It goes without saying there are no warranties and we accept no liability for anything these scripts do. They work for us but that's all we are saying.

What scripts are there?
-----------------------

The scripts are listed below:

 * APC Smart-UPS with AP9606 network card:	This host template will work with any APC Smart-UPS with an AP9606 or AP9619 network card, providing battery status, device temperature, line voltage and output load, voltage and current details.
 * APC 9619 Environmental Monitoring External Probe: These data/graph templates will provide temperature and humidity readings from the external probe connected to an APC AP9619 environmental monitoring card. You can add these data templates to an existing host template such as the Smart-UPS template above. (Probe 1 Temp)
 * APC 9619 Environmental Monitoring External Probe: These data/graph templates will provide temperature and humidity readings from the external probe connected to an APC AP9619 environmental monitoring card. You can add these data templates to an existing host template such as the Smart-UPS template above. (Probe 1 Humidity)
 * APC AP7721 Rack Automatic Transfer Switch	This host template provide voltage, power, load and current for Source A and B inputs and the output on an APC AP7721 Automatic Transfer Switch as well as details of the current input source and redundancy state.
 
Help! It doesn't work!
----------------------

There is no warranty for these templates. In particular, if you are using a different device or even a different firmware revision, then that can cause these templates to fail. We would suggest you post a message in the `Cacti forums <http://forums.cacti.net/>`_, where someone may be able to assist.