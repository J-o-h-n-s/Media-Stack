# Media-Stack
Media Docker-Compose stack for use either through CLI or portainer.


Current config:

Jackett

Radarr

Sonarr

Transmission

Flame



NOTE: The ports are boud to the loopback IP, so you will not be able to access the services remotely. Use Cloudflared Tunnels if this is something you want. 
Point the tunnels to localhost:<IP OF SERVICE>
