# 999 WRLD

999 WRLD is a Juice WRLD inspired music player for your computer and phone, built around your own music collection. It brings a rich, customisable look together with balanced playback, an optional AI radio host, and tools to discover, organise and enjoy different versions of your favourite songs.

- **Your music, organised:** Scan for MP3s on Windows or Android, browse songs and albums, search alternate titles, and edit track details.
- **Sound your way:** Use a 31-band equaliser, consistent-volume playback, and local-only pitch, reverb and speed controls.
- **Your own radio station:** Build a local queue with an optional AI DJ, natural male or female voices, and chilled, upbeat or hype delivery.
- **Talk to the DJ:** Ask for a skip, request a song, change the vibe or get a recommendation by typing or speaking.
- **Explore the catalogue:** Find Juice WRLD songs, alternate titles and newly added entries, or listen to live 999 FM with a compact artwork queue preview.
- **Compare song versions:** See documented differences and audio measurements to help choose the version you prefer.
- **Playlists that fit you:** Create normal or smart playlists, and collect favourites automatically in Loved songs.
- **Listen offline:** Download available catalogue songs and playlists in their original supplied quality.
- **Lyrics and editing:** Follow timed lyrics when available, fix tags, and trim or arrange audio without overwriting your originals.
- **Your listening story:** See song play counts, monthly recaps and the tracks you keep coming back to.
- **Make it yours:** Choose colours, backgrounds, fonts and layout preferences to match your style.
- **Stay current:** Get update notifications, download updates in Settings, and apply them through your platform’s installer or web-app reload.
- **Take it with you:** Use Windows, Android, iPhone and Mac web apps, with background playback preferences and media controls.


## Detailed features

<details>
<summary>Explore the full feature guide</summary>

### A music collection that feels like yours

Import local songs, browse automatically grouped albums, search titles and alternate names, and keep an editable queue. Love tracks from your library, catalogue or radio; the Loved songs playlist collects them. Create ordinary playlists yourself or smart playlists that follow rules across your library. Available catalogue tracks and playlists can be saved to this device in their original supplied quality.

### Balanced playback and a flexible equaliser

The 31-band equaliser includes preamp, editable frequency bands, presets and a response graph. The Juice WRLD inspired starter preset can be adjusted or replaced. Windows analyses whole songs for loudness and true peak, then applies playback gain so quieter and louder recordings sit closer together. Android device scans analyse audio in small native chunks; imported files and browser apps use a bounded, lower-memory loudness estimate. These paths report sample peak. ReplayGain track and album tags are supported, with album peak handling, a playback preamp, unanalysed-song gain and clipping prevention. Analysis results are reused, and processing intensity can be adjusted. Local files also have independent pitch controls (±12 semitones), playback speed (0.5–1.5×), reverb, reset and a slowed-and-reverb preset. These playback effects do not rewrite originals and are bypassed for API streams.

### Your own radio host

Local radio builds a queue from your music or playlists and works independently of the Juice WRLD API. Switch the in-app AI on or off, type requests, or use optional voice commands for skips, song requests and recommendations. The host speaks between every three to five qualifying songs; quick skips do not trigger extra breaks. Song introductions use available credits, source notes or your own notes. Choose male or female device/natural voices and calm, radio or hype delivery. The station name is spoken as “nine nine nine World”. Optional AI and natural-voice models download to your device when enabled and need a capable browser and sufficient memory.

### The catalogue and different song versions

Search the Juice WRLD API catalogue, explore eras and alternate titles, compare linked versions, and listen to the provider's live 999 FM station. Catalogue checks identify newly added entries after an initial baseline. Version comparisons combine documented metadata with available audio measurements, including duration and loudness. Smart catalogue radio compares linked versions, explains its pick and keeps a real queue. Audio comparison is enabled by default and measures each playable version before selection, caching results and preparing the next song in advance. Checks cover waveform clipping, silence, channel balance, mono cancellation and mastering loudness. Windows and supported browser jobs also provide a sampled spectral view. Android reads audio from a temporary download in small chunks, with a 60 MB original-file limit and no spectral or true-peak claim. Browser jobs have stricter memory limits; oversized files retain catalogue-based selection and are marked unmeasured. This needs extra original-file downloads and battery; checks describe measurable differences rather than proving artistic superiority. Higher bitrate alone is not treated as proof that a version sounds better. Streaming quality and data-saving settings depend on the files supplied by the provider.

### Lyrics, tags and audio tools

Read embedded or imported lyrics, including timestamps when supplied, and replace incorrect lyrics or edit LRC text. Genius links open the source website; full lyric text is not automatically scraped. Windows can edit supported file tags with backups; phone edits update the app's library metadata. The studio offers a waveform, clips, trimming, undo and exports while keeping original audio intact. Tempo, key and possible open-verse markers are estimates to help you choose edit points. Local DJ decks include cues, loops, tempo and EQ; automatic vocal stem separation is not included.

### Listening history and personal style

Count one listen after 30% of a song has actually played, and see monthly recaps of your most-played songs. Choose colours, backgrounds, typography, artwork and display density. Phone layouts use bottom navigation, touch controls and a compact player, with extra tools in the More menu. Layouts adapt to portrait, landscape and tablet sizes. Audio caches are bounded, paused processing sleeps, background refreshes are reduced, and idle AI models rest to release memory.

### Platforms and updates

Use the Windows portable app, Android APK, installable iPhone web app or Mac web app. On Mac, Safari → File → Add to Dock gives the same responsive desktop layout as Windows. An optional small universal macOS window supports Apple Silicon and Intel using the system WebKit engine, with multi-file imports, download/save dialogs and persistent on-device storage. It loads the hosted web app and needs an internet connection on first launch; Windows-specific file-tag rewriting and FFmpeg tools are not part of this web version. The downloadable Mac preview is ad-hoc signed and is not Apple notarized; Safari installation is the regular web-app route. In Safari, open the web app and choose Share → Add to Home Screen. GitHub releases provide update notifications inside the app and checks in Settings. Windows updates verify the download and preserve library data in a new installation; phone packages use their platform's installer and the web app refreshes in place. Android release packages use a stable private signing key for future data-preserving updates. Older preview APKs signed with a different debug key require a separate migration; export your data before replacing one. The iOS download is an unsigned simulator build for Xcode, not a signed physical-iPhone IPA. Native mobile projects include audio-session, lock-screen, headset and interruption handling. Compact media controls show song metadata, artwork when available, and the playback source. Background playback and a sleep timer have settings in the app; real-device testing remains necessary. Windows can scan local drives for MP3s and Android scans its indexed music library. iPhone and browsers use multiple-file import because they cannot scan private device storage. Browser storage limits, supported audio formats, AI performance and background playback vary by device. Libraries and listening history are currently per device, without automatic cloud sync.

</details>

## Version releases

Latest build: **0.2.5**.

[Downloads & release notes](https://github.com/hsob2nd/999-wrld-releases/releases) · [Open the web app](https://hsob2nd.github.io/999-wrld-releases/) · [Report an issue](https://github.com/hsob2nd/999-wrld-releases/issues/new/choose)
