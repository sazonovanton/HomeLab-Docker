# Example of home server setup

This is an example of home server setup (for eduction purposes). Every service has it own docker-compose file which placed in its specific folder. That's different from what I saw on GitHub, where people put everthing in one docker-compose.yml. My structure was just more convenient for me while I was troubleshooting and I'm not saying that it's better. 

## Services

* Traefik - routing traffik through subdomains and HTTPS support.
* Home Assistaint (HASS) - smarthome.
* Plex - media server.
* Jellyfin - also a media server, but it's better for using in mobile and it has hardware transcoding (Plex also has mobile app and hw trascoding, but with Plex Pass only).
* Nextcloud - private cloud server with functionality similar to Google Drive or Dropbox. 
* qBittorrent - BitTorrent client.
* Samba - implementation of the SMB networking protocol for file sharing.
* Filebrowser - web-based file browser.
* Radarr - movie collection manager.
* Sonarr - serials collection manager.
* Homer - static html/js dashboard.
* Jupyter - web-based interactive computational environment.

Also [Cockpit](https://cockpit-project.org/) is used for system monitoring and as a VM manager.