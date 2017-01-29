# Docker Media Server #

## Description ##

* my docker-based media server configuration for ubuntu
* pulls and runs the following docker images via [docker-compose](https://github.com/docker/compose):

Image | Size | Version
--- | --- | ---
[plexinc/pms-docker](https://hub.docker.com/r/plexinc/pms-docker/) | [![](https://images.microbadger.com/badges/image/plexinc/pms-docker.svg)](https://microbadger.com/images/plexinc/pms-docker "plexinc/pms-docker") | [![](https://images.microbadger.com/badges/version/plexinc/pms-docker.svg)](https://microbadger.com/images/plexinc/pms-docker "plexinc/pms-docker")
[portainer/portainer](https://hub.docker.com/r/portainer/portainer/) | [![](https://images.microbadger.com/badges/image/portainer/portainer.svg)](https://microbadger.com/images/portainer/portainer "portainer/portainer") | [![](https://images.microbadger.com/badges/version/portainer/portainer.svg)](https://microbadger.com/images/portainer/portainer "portainer/portainer")
[linuxserver/nzbget](https://hub.docker.com/r/linuxserver/nzbget/) | [![](https://images.microbadger.com/badges/image/linuxserver/nzbget.svg)](https://microbadger.com/images/linuxserver/nzbget "linuxserver/nzbget") | [![](https://images.microbadger.com/badges/version/linuxserver/nzbget.svg)](https://microbadger.com/images/linuxserver/nzbget "linuxserver/nzbget")
[linuxserver/sonarr](https://hub.docker.com/r/linuxserver/sonarr/) | [![](https://images.microbadger.com/badges/image/linuxserver/sonarr.svg)](https://microbadger.com/images/linuxserver/sonarr "linuxserver/sonarr") | [![](https://images.microbadger.com/badges/version/linuxserver/sonarr.svg)](https://microbadger.com/images/linuxserver/sonarr "linuxserver/sonarr")
[linuxserver/radarr](https://hub.docker.com/r/linuxserver/radarr/) | [![](https://images.microbadger.com/badges/image/linuxserver/radarr.svg)](https://microbadger.com/images/linuxserver/radarr "linuxserver/radarr") | [![](https://images.microbadger.com/badges/version/linuxserver/radarr.svg)](https://microbadger.com/images/linuxserver/radarr "linuxserver/radarr")
[linuxserver/plexpy](https://hub.docker.com/r/linuxserver/plexpy/) | [![](https://images.microbadger.com/badges/image/linuxserver/plexpy.svg)](https://microbadger.com/images/linuxserver/plexpy "linuxserver/plexpy") | [![](https://images.microbadger.com/badges/version/linuxserver/plexpy.svg)](https://microbadger.com/images/linuxserver/plexpy "linuxserver/plexpy")
[linuxserver/transmission](https://hub.docker.com/r/linuxserver/transmission/) | [![](https://images.microbadger.com/badges/image/linuxserver/transmission.svg)](https://microbadger.com/images/linuxserver/transmission "linuxserver/transmission") | [![](https://images.microbadger.com/badges/version/linuxserver/transmission.svg)](https://microbadger.com/images/linuxserver/transmission "linuxserver/transmission")
[linuxserver/hydra](https://hub.docker.com/r/linuxserver/hydra/) | [![](https://images.microbadger.com/badges/image/linuxserver/hydra.svg)](https://microbadger.com/images/linuxserver/hydra "linuxserver/hydra") | [![](https://images.microbadger.com/badges/version/linuxserver/hydra.svg)](https://microbadger.com/images/linuxserver/hydra "linuxserver/hydra")
[linuxserver/letsencrypt](https://hub.docker.com/r/linuxserver/letsencrypt/) | [![](https://images.microbadger.com/badges/image/linuxserver/letsencrypt.svg)](https://microbadger.com/images/linuxserver/letsencrypt "linuxserver/letsencrypt") | [![](https://images.microbadger.com/badges/version/linuxserver/letsencrypt.svg)](https://microbadger.com/images/linuxserver/letsencrypt "linuxserver/letsencrypt")

## Installing ##

```bash
git clone git@github.com:klutchell/docker-mediaserver.git ~/mediaserver
sudo ~/mediaserver/bin/install
~/mediaserver/bin/configure
```

## Running ##

```bash
~/mediaserver/bin/pull
~/mediaserver/bin/up
```

## Contributing ##

* n/a

## Author ##

* Kyle Harding <kylemharding@gmail.com>

## Credit ##

I give credit where it's due and would like to give a shoutout to [LinuxServer.io](https://www.linuxserver.io/). Several of their Docker images were used for this project.