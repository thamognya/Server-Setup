# Server Necesites

- Fail2Ban
- ufw

# What I need?

- MailCow
- Gitea
- code-server
- Caprover
- SearXNG
- KDE-in-Docker
- Docker-Firefox
- owncloud
- MaliceScan
- The Lounge (irc)
- element + matrix
- (Video): Sonarr (for series) + Radarr (for movies) + prowlarr + deluge + jellyfin + Emby + jellyseerr (for requests) + qbittorrent (for downloading)
- (audio): audiobookshelf + Airsonic

# Reccomended Urls and what they contain

## Public

- matrix.\* -> matrix
- files.\* -> just html list

## Private

- mail.chat.\* -> mailcow
- git.\* -> gitea
- code.\* -> code-server
- paas.\* -> caprover
- search.\* -> searxng
- irc.chat.\* -> the lounge
- matrix.chat.\* -> element
- kde.os.\* -> KDE-in-Docker
- firefox.os.\* -> KDE-in-Docker
- drive.\* - owncloud
- malice.\* - malicescan

# Layout

```
Nginx + letsencrypt
|
|--> MailCow
|
|--> Gitea
|
|--> VsCode
|
|--> SearXNG
|
|--> Caprover
```

Make config changes at `conf/main.conf`
