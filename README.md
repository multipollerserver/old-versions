# old-versions
All older versions as zip

Here you can download all old vresions from the plugin.

--- 0.8.8h ---
	-change:	work correcktly with cacti 0.8.8h.
	
--- 0.8.8g ---
	-change:	work correcktly with cacti 0.8.8g.
	
--- 0.8.8f ---
	-change:	work correcktly with cacti 0.8.8f.

--- 0.8.8e ---
	-change:	work correcktly with cacti 0.8.8e.
	
--- 0.8.8d ---
	-fix:		path correction in setup.php (thx Nino Kambach).
				PHP Notice:  Undefined variable: poller_server_id in /usr/share/cacti/poller.php on line 533
	-change:	work correcktly with cacti 0.8.8d.

--- 0.8.8c ---
	-new:		completly overhauled the backend. Now the installation works without root privileges.
	-change:	work correcktly with cacti 0.8.8c.

--- 0.2.3 ---
	-new:		fallback all poller to poller_id from master if update cacti to 089 before the plugin is prepared (sorry) but all settings are saved
	-change:	better query for hostcount.
					thanks to prosodie from cacti.net

--- 0.2.2 ---
	-new: Now the masterserver is ready for polling.
	-new: Choose the devices on an listing for the pollerserver
	-new: Show number of polling hosts
	
	-fix: Tidy sourcecode
	-fix: Failuremessage in pollerlog on polling (include once)
	
--- 0.2.1 ---
	-new: update routine inserted
	-fix: Error when pollerserver ist not registerd or is disabled
	      match small errors

--- 0.2 ---
	-bug: Fix match error

--- 0.1 ---
		Initial Release
