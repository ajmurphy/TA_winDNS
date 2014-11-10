TA_winDNS
=========

Splunk technology add-on to handle Windows Server DNS-Debug logs
This TA needs to be deployed on the search head and the indexer in order to ensure that the DNS data that is being sent from a universal forwarder is being appropriately parsed, indexed, and the fields are extracted properly.

./apps/TA_winDNS-universalForwarder needs to be deployed on the universal forwarder (likely sent by deployment-manager so needs to live in %SPLUNKDIR%/etc/deployment-apps/

NOTE: You will have to change the IP/FQDN of your indexer in the TA_winDNS-universalForwarder/local/outputs.conf so that your universal forwarder knows where to send the DNS logs

If you have any questions on the use of this please contact austinj.murphy@gmail.com


