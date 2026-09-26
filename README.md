## Release notes

**Changes since MPS4 Fenix 20260804.1**

### New Sources

- Add Amazon Music streaming with playlists, stations, track metadata and album art
- Add Calm Radio streaming, track metadata and album art
- Add KKBOX streaming with charts, featured playlists, collections, track metadata and album art

### Integration

- Add Chromecast Audio, Sonos, HEOS, Denon/Marantz, Yamaha MusicCast and Onkyo/Pioneer/Integra devices as MCS sources and zones
- Add an Auxiliary page with automatic discovery
- Add Bluetooth and AirPlay speakers as wireless zones, managed on a new Wireless page

### General Software Improvements

- Improve update installation reliability, progress reporting and recovery messages
- Improve album art and now-playing refresh across the apps
- Improve metadata character handling for accented and non-English speaker names
- Add custom zone display names shown in the apps in local-language names

### Config Web Application

- Fix a spurious "saved" banner on the Sources page
- Add Wireless and Auxiliary pages
- Hide retired sources on the Content page
- Simplify the Server page and improve firmware update progress

### Fenix and MusicPort PWA (Progressive Web App for iOS/Android) and Web

- Keep Fenix zones on the player source you select, with more reliable source switching and playback updates
- Rebuild MusicPort with zone list, source picker, player and queue, and desktop navigation refinements
- Remember the MusicPort zone, tab and streaming account between visits

### Spotify

- Improve Spotify account authorization on Windows 7

### TIDAL

- Improve TIDAL account authorization on Windows 7

## Release notes

**Changes since 5.35.20210128.0**

### New features

- Add support for multiple USB, Bluetooth, HDMI and built-in audio outputs
- Add Windows volume control for systems without an amplifier
- Add modern Fenix Web/PWA UI at http://ipOfServer/Fenix/
- Add modern Musicport Web/PWA UI at http://ipOfServer/Musicport/
- Add optional zone tone, balance and loudness controls for NuVo amplifiers with Nuvo Web
- Add automatic zone power-off after extended inactivity

### General Software Improvements

- Improve restart, reconnection and shell recovery reliability
- Improve audio-device identification and playback routing
- Improve metadata character handling
- Preserve existing firewall and Remote Desktop settings during installation
- Improve TLS compatibility support for Windows 7

### Mirage Web Application

- Restore Playlists in the main navigation
- Fix Next Track ordering during playlist playback

### Spotify

- Enable local account authorization
- Improve playlist and Spotify Connect Next Track handling

### TIDAL

- Enable local account authorization
- Add Windows 7 TLS compatibility support

### Installer

- Add common installation support for Windows 7 SP1, Windows 10 and Windows 11
- Install VLC, Bonjour and Visual C++ prerequisites only when required
