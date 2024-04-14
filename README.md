# Synthia Music App v0.0.4
The React Native Frontend for the Synthia Music App, utilizing the database generated from the [MusicDatabaseGenerator](https://github.com/JeffreyGaydos/music-database-generator). Originally created to get over the limit of 1000 songs for Samsung Music.

# Installation

If you need the bleeding edge or I just haven't made a release for this, simply pull down the source code, navigate to the `Synthia` folder and run `./gradlew assembleDebug`. After the command completes, an apk file will be generated at `Synthia/android/src/build/apk/release`.

Now that you have the apk, copy it to your device's downloads folder. Next, enable your android device to download unknown apps from the "My Files" app or whatever file manager app you use. Do this by going to Settings > Security & Privacy > More Security Settings > Install Unknown Apps and then enabling your file management app.

Tap on the apk file from your file manager and android should prompt you for confirmation of installation assuming the previous steps were completed successfully. Finally, to ensure the app has all the permissions it needs, go to Settings > Apps > Synthia > Permissions and enable all available permissions. It should be ready to go at that point!

# WIP
Here's what I have so far:
- Playlist UI, but no data and no tracklist
- A Player that can play a subset of songs found on your device (for testing purposes)
  - Includes play pause and progress bar. Other buttons are dummy buttons and will be worked on later