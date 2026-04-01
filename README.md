# Wazuh SIEM Lab Implementation

**By Rofiat** 
**Environment:** Ubuntu, Kali Linux, and VMware

## How I Fixed the Connection Error
When I first started, I ran into an API error that kept the dashboard from loading properly. I solved this by restarting the Wazuh services in the terminal. Before refreshing my Wazuh dashboard, I made sure to check the status of the services to ensure everything was active and running. Once the status showed it was up, I refreshed the page and the dashboard loaded perfectly.

## Navigating the Wazuh UI
The lab guide I was following mentioned a "Modules" tab that was not visible in this version. I discovered that in Wazuh 4.x, these features are now located in the sidebar under **Endpoint Security**. I successfully located **Configuration Assessment** and **Malware Detection** there.
