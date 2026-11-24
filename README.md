# FIXIT Karaoke

Karaoke for PC, TV boxes and phones. Guests join from their phones, search songs,
add them to the queue and get a score after each song.

## Download

Get the latest version from **[Releases](https://github.com/felexsayri/fixit-karaoke/releases/latest)**:

| Device | File |
|---|---|
| Windows PC / laptop | `FIXIT.Karaoke.Setup.<version>.exe` |
| Android TV box | `FIXIT.Karaoke-TV-<version>.apk` |
| Android phone / tablet | `FIXIT.Karaoke-Mobile-<version>.apk` |

Releases also carry the same files under the app's old name (`FIX-IT.KARAOKE...`),
so apps from 1.0.19 and older can still update themselves. Either file installs the same app.

### Installing on Windows

Run the Setup file. If Windows shows "Windows protected your PC", click
**More info**, then **Run anyway**.

### Installing on Android

Copy the APK to the device (or download it there) and open it. Allow
"Install unknown apps" for your browser or file manager when Android asks.

## Songs are not included

The apps come without songs. Put your own songs in a folder named
`FIXIT Karaoke` (on the device, an SD card or a USB drive). A `FIX-IT KARAOKE`
folder from an older version works as it is.

```
FIXIT Karaoke/
  karaoke/       karaoke videos (MP4, or MP4s inside ZIP files)
  midi/songs/    MIDI / KAR songs, or FIXIT song packs (.fixidx + .fixblob)
  midi/sound/    SoundFonts (optional)
  midi/bgv/      background videos for MIDI songs (optional)
```

The app finds the folder by itself and numbers the songs.

### Background videos

The apps come with background videos and photos for MIDI songs. To use your own,
put them in the library's `midi/bgv` (videos) or `midi/bgphoto` (photos) folder.
