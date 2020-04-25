# Jitsi Videobridge Zabbix Stats
An simple implementation of Jitsi Videobridge Statistics, to Zabbix. 

Jitsi Videobridge Stats. Based on Colibri stats bulit-in api to present Staticis from Jitsi Videobridge. I've added the most important data, some stats not added, but it is easy to add them by using the Zabbix Server GUI. 

If you don't enabled Videobridge statistics, see Jitsi documenation below.

### Full Documentation of Jitsi Videobridge Colibri Stats

`https://github.com/jitsi/jitsi-videobridge/blob/master/doc/statistics.md`

`https://github.com/jitsi/jitsi-videobridge/blob/master/doc/rest.md`


The only thing what must you do is from Zabbix site is:

Add the XML template to throughout Zabbix GUI.

### Versions:

Tested and implemated on Zabbix 3.4


### To Do:

* Rewrite items to use with MACRO
