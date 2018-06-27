# NetworkMonitor
A simple way to control and log all devices connected to a local network

Just set the proper fields marked in the files and run the `./setup.sh`  
Every 15 minutes that script will perform a scan of the network and register all found devices in a LDAP server for logging

## Dependency
This script needs `crontab`, `nmap`, `awk` and `ldapadd` to run  
NEEDS A CONFIGURED LDAP SERVICE
