# Dockerized HTPC Setup 
Trying to make something that's as close as possible to a 1-click install. 

## Services

  - [Traefik](https://hub.docker.com/_/traefik/)
  - [Portainer](https://hub.docker.com/r/portainer/portainer/)
  - [Organizr](https://hub.docker.com/r/lsiocommunity/organizr/)
  - [Plex](https://hub.docker.com/r/linuxserver/plex/)
  - [Radarr](https://hub.docker.com/r/linuxserver/radarr/)
  - [Sonarr](https://hub.docker.com/r/linuxserver/sonarr/)
  - [Jackett](https://hub.docker.com/r/linuxserver/jackett/)
  - [Cardigann](https://hub.docker.com/r/linuxserver/cardigann/)
  - [Ombi](https://hub.docker.com/r/linuxserver/ombi/)
  - [Deluge + PIA](https://hub.docker.com/r/binhex/arch-delugevpn/)

## TODO/Missing services
  > Note that Windows users can use WSL to avoid having to rebind paths and can simply symlink if needed
- [ ] Create cross-platform overrides to allow this to work on Windows
- [ ] Add Prometheus or Fluentd logging
- [ ] Add a media manager to download trailers

### Contributing
Feel free to open an issue or submit a PR if you have suggestions on services or improvements.
