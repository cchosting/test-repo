This repo contains only 3 files:

1. all-servers
2. vps-servers
3. shared-servers

These 3 files are updated here by a 24 hours cron that runs on tools machine. 
The cron runs every 24 hours and checks WHMCS installation at lab.chemicloud.com for any new active server.
The active servers are all exported to "all-servers" file.
At the tools machine level, we sort the "all-servers" file and export the other 2 files:

a. vps-servers ( all servers that start with "cvps" )
b. shared-servers ( all server that start with "rs" )

These files are updated every 24 hours.

That's pretty much it!

