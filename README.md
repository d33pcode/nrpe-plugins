Install NRPE server on the machine, locate the installation folder (usually /etc/nagios/) and clone this repo replacing the folder content.

To keep it up-to-date, install a cron like this:
```cron
 */5 * * * * root cd /usr/local/nagios/etc && git pull && restart nagios-nrpe-server
```
