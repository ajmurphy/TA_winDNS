TA_winDNS
=========

Splunk App to handle Windows Server DNS-Debug logs
This TA needs to be deployed on the search head and the forwarder in order to ensure that the DNS data that is being sent from a universal forwarder
is being appropriately indexed, parsed, and searched.

./apps/TA_winDNS-fwd needs to be deployed on the universal forwarder (likely sent by deployment-manager so needs to live in %SPLUNKDIR%/etc/deployment-apps/

If you have any questions on the use of this please contact austinj.murphy@gmail.com


