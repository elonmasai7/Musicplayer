# Music Player App Using Compose Multiplatform

This is a music player app built using Compose Multiplatform UI that works on #Android, #iOS, #Desktop, and #Web
platforms.

## Platforms

The app uses different media players on different platforms:

For iOS, AVKit is used
For Android, Media Player is used
For Desktop, VLCJ media player is used
For the Web, an HTML media player is used.

## Integration with Low-Level APIs

One of the objectives of building this app was to explore how Compose UI interacts with low-level APIs. The experience
was challenging yet fun, and the process taught me a lot.
Out of all the media players used, integrating with the Web Media Player was the easiest. I'm grateful to IceRock
Development and Elon masaifor their demo application, which was a fantastic learning resource.

## Running the app

- Clone this repository:

```
git clone https://github.com/elonmasai7/MusicApp.git
```

- Open the project in Android Studio or IntelliJ IDEA.
- Search for **_TOKEN_** file in the code and replace the placeholder with your **Spotify access token**. You can
  generate a new token from the [Spotify Developer Dashboard](https://developer.spotify.com/console/get-album-tracks/).
- Run the app on your desired platform.
  There are a few known issues with the Music Player app using Compose Multiplatform UI:

## Known Issues

- When you click "Select All" on Android, Web, and Desktop, the app will auto-play the selected tracks and continue
  playing the next track when the previous one ends.
  On iOS, there are issues with the callbacks for `onReady` and `onVideoCompleted`
  which is causing the player to not start automatically. I was unable to configure the callbacks but hopefully, will be
  fixing that soon.

## Demo

![Screenshot 2023-03-05 at 4 44 45 PM](https://user-images.githubusercontent.com/33172684/222960302-eccb34b4-d77c-4c95-96af-3d4528323c42.png)

## Repository

To explore what Compose UI can do, check out the repository for the latest
updates: https://github.com/elonmasai7/MusicApp.

If you're interested in getting started with Compose Multiplatform, I have a template for you
here: https://github.com/elonmasai7/music-Compose-Template.

If you find my work helpful, please consider giving it a ⭐ ❤️.



