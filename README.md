<h1>Media-Stack</h1>

Media Docker-Compose stack for use either through CLI or portainer.


<b>Current config:</b>

Jackett

Radarr

Sonarr

Transmission

Flame


NOTE: The ports are boud to the loopback IP, so you will not be able to access the services remotely. Use Cloudflared Tunnels if this is something you want. 
Point the tunnels to localhost:[PORT OF SERVICE]

