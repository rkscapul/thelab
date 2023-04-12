# Media Management - Music
Powered by Navidrome and OpenMediaVault.

## Infrastructure
Due to my annoyance with automatic metadata fetching for album arts, I manually insert the album arts on the files. Here's the approach:
1.  Using [MusicBee](https://www.getmusicbee.com/) to fix the missing metadata. Essentially the following:
    * Album Art - single art is more preferred
    * Artist
    * Title
2. [OpenMediaVault](https://www.openmediavault.org/) acts as network storage for all music.
3. Navidrome will distribute the music to the following ***local*** cient applications:
    * Web - [Navidrome](https://www.navidrome.org/)
    * Android - [substreamer](https://substreamerapp.com/)

## Music folder structure
For multi-artist collaborations, album will be located in first artist located.
```
Music/
├─ Artist/
│  ├─ Album/
│  │  ├─ Single
```
