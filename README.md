# iconSetAutoReboot
CURL against Icon API to configure 'autoreboot' to ON at 5 AM local time for Icon systems listed in ExampleFile.txt

USAGE: You can invoke this script in two ways

- ./iconSetAutoReboot.sh \<Password> \<Filename> 
- ./iconSetAutoReboot.sh \<Filename> 
  
Notes* <br />
Customer will need a Linux or MAC machine with CURL utility installed.  
Password parameter is optional.  
Script assumes a default password of ‘admin/admin’ if no password parameter is given.  
Filename parameter is mandatory. This should be a list of IPs this script will operate over. See ExampleFile.txt for formatting examples.

