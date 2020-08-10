# GoldenOrb Easy Setup Guide. 
Configure ROOter for first use.

After you unbox your GoldenOrb router and power it on, you'll have 2 physical connection options to setup the ROOTer:
  - First and rcommended option is  via Ethernet. Plug one end of a standard Ethernet cable into the LAN ports on the ROOTer and  the opposing end into a computer or Ethernet ready device. Assuming both the ROOTer and the connecting device are set to default network connection settings, you should automatically connect. Disabling WiFi on the connecting device or computer during this process will elimate additional problems.

  - Second option is via  WiFi. The default WiFi password for ROOTer as of 08/2020  is "rooter2017"  without quotes.

Now that  you have sucessfully connected to the ROOTer, open a clean web browser and  go to http://192.168.1.1
Make  sure you are NOT conencting to https://192.168.1.1 - notice the s after http should be missing.

The main configuration we will do is changing the APN. The APN change should be the only default configuration change necessary to connect via cellular. From the left hand navigation menu select Modem > Connection Profile. From here we have the first form box labled simply, "APN". Here is a list of the default APN's  we should choose from depending on which SIM Card is being used, these are first choice Carrier Grade APN's. If an MVNO or 'reseller' SIM is being used, more APN research is necessarry outside this guide. (If these default APNs do not work, you do not have a proprer SIM, assuming ample signal is being provided and the ROOTer is fully functional):
_________________

 - Verizon
    - vzwinternet
 - AT&T
    - broadband
 - T-Mobile
    - fast.t-mobile.com
 - Sprint
    - r.ispsn
    - n.ispsn
_________________
Click Save & Apply and unplug the router from it's  power source. Wait 10 seconds for it to fully power down (why? cheap https://en.wikipedia.org/wiki/Capacitor) and replug it.

We should be connected  at this point and  to verify, simply log back in to the ROOTer at http://192.168.1.1 and go to Modem > Network Status.

Just to make sure the ROOTer and the cellular network are on the same page, we'll change the TTL values by navigating  to Firewall >  Custom TTL and clicking the checkbox for 65.

Click Save & Apply 

That's it!

_________________


# Setup the WiFi

https://ofmodemsandmen.com/configure.html

This guide and OpenWRT are FOSS.
