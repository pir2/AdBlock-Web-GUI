AdBlock Web GUI by Almaz
==============

AdBlock Web Gui for Jerrm script

Version: 1.41

Using Tomato firmware just put all the files in /var/wwwext/

You can access GUI by openning in browser http://routerIP/ext/ads.sh 

adblockpath="/var/wwwext/adblock.sh" 	-	location of adblock.sh by Jerrm

pixelservip="192.168.1.254"			 	-	Pixelserv IP address	
	
scriptname="ads.sh"						-	this script name

dnsmasqlog="/tmp/var/log/messages*"		-	dnsmasq log location, by default it's using syslog

tmpfolder="/tmp"						- 	location of your temp folder

dnsmasq_external_log="n"				-	for external dnsmasq log then enter "y" otherwise "n" for default syslog

dnsmasqconf="/etc/dnsmasq.custom"		-	location for dnsmasq.custom
