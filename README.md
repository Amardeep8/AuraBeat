# AuraBeat
🎵 AuraBeat — Feel Every Beat. Live Every Frame. A modern Android music player with free music, lossless audio support, powerful audio controls, playlists, equalizer, background playback, and a premium AMOLED experience.
# 🎵 AuraBeat

> **Feel Every Beat. Live Every Frame.**

AuraBeat is a modern, powerful and privacy-focused Android music player built for people who want a clean interface, high-quality audio and complete control over their music.

Designed with a premium AMOLED experience, AuraBeat brings music playback, playlists, equalizer controls, queue management and powerful customization together in one native Android application.

---

## ✨ Why AuraBeat?

AuraBeat is built around three principles:

- 🎵 **Great Music Experience**
- ⚡ **Fast & Smooth Performance**
- 🔒 **Local & Privacy-Focused**

No mandatory account. No complicated setup. Just open the app and enjoy your music.

---

# 🚀 Features

## 🎧 Music Player

- High-quality music playback
- Free music playback
- Compatible lossless audio playback
- Full-screen music player
- Mini player
- Play / Pause
- Previous / Next
- Seek control
- Progress bar
- Song duration
- Album artwork
- Artist information
- Album information
- Automatic next-track playback
- Resume playback
- Background playback
- Screen-lock playback
- Bluetooth media controls
- Headphone media controls
- Android MediaSession integration

---

# 🔊 Advanced Audio

AuraBeat provides powerful audio customization options.

### 🎚️ Equalizer

- Multi-band equalizer
- Custom EQ adjustment
- Presets
- Flat
- Rock
- Pop
- Classical
- Jazz
- Dance
- Hip-Hop
- Electronic
- Vocal
- Bass
- Custom profiles

### 🔥 Audio Enhancements

- Bass Boost
- Loudness enhancement where supported
- Stereo enhancement
- Spatial audio effects where supported
- Audio balance
- Pitch control where supported
- Tempo control where supported
- Replay/volume normalization where supported

> Audio capabilities depend on the Android device, audio source and supported format.

---

# 🌙 Sleep Timer

Listen before sleeping without worrying about manually stopping playback.

Available options:

- Off
- 5 minutes
- 10 minutes
- 15 minutes
- 20 minutes
- 30 minutes
- 45 minutes
- 60 minutes
- 90 minutes
- 120 minutes
- Custom timer
- End of current song

### Smooth Fade-Out

When the timer expires, AuraBeat smoothly fades the music instead of abruptly stopping it.

Example:

```text
🌙 24:38 Sleep Timer

The countdown updates every second.


---

♾️ Queue Endless

Queue Endless allows playback to continue automatically when the current queue reaches its end.

Features:

Automatic continuation

Works with background playback

Works with MediaSession

Works with notifications

Compatible with Shuffle

Compatible with Repeat

Prevents unnecessary duplicate queue entries


Queue Endless can be enabled or disabled from Settings.


---

📋 Playlists

Create and manage local playlists without an account.

Create Your Playlist

From:

Library → Playlists → +

Create a playlist by entering a name.

After creation, AuraBeat opens the playlist in a full-screen interface.


---

🖼️ Custom Playlist Artwork

Every playlist can have its own custom image.

Choose an image from the device Gallery and use it as:

Playlist cover

Playlist wallpaper

Full-screen playlist background


The image is stored locally and remains available after restarting the app.

Each playlist has its own independent artwork.


---

📊 Playlist Information

The playlist automatically displays:

24 Songs • 1h 32m

Song count and total duration update automatically whenever the playlist changes.


---

🎵 Playlist Controls

Play All

Shuffle

Add Songs

Remove Songs

Rename Playlist

Change Cover

Use Default Cover

Clear Playlist

Delete Playlist

Select Songs

Sort Songs

Custom Arrange



---

🔤 Playlist Sorting

Available sorting options:

Default Order

A → Z

Z → A

Artist A → Z

Artist Z → A

Album A → Z

Newest Added

Oldest Added

Most Played

Least Played



---

↕️ Custom Arrange

Manually organize songs in any order.

Press and hold a song

Drag it up or down

Release it in the desired position

Order is saved locally


Your custom order remains available after restarting the app.


---

🔎 Music Search

Search your music quickly using the built-in search system.

Search for:

Songs

Artists

Albums

Available music


Search results can be played directly through the existing music player.


---

🕘 Recently Searched

AuraBeat can locally remember searched music.

Every time you search:

Song A
Song B
Song C
Song D

the searched items can appear in the Recently Searched section.

Features:

Newest searches first

Duplicate searches handled intelligently

Local search history

Remove individual searches

Clear search history


No account is required.


---

📚 Library

The Library provides quick access to your music collection.

Possible sections include:

Songs

Artists

Albums

Playlists

Recently Played

Most Played

Liked Music

Downloaded/Offline Music



---

❤️ Favorites

Save your favorite songs for quick access.

Favorites are stored locally and can be accessed from the Library.


---

🎨 User Interface

AuraBeat is designed with a modern AMOLED-first interface.

UI Principles

AMOLED-friendly dark interface

Material 3

Rounded cards

Smooth animations

Clean typography

Modern icons

Responsive layouts

Immersive full-screen player

Elegant album artwork

Smooth transitions

Minimal visual clutter



---

🔐 Privacy

AuraBeat follows a local-first approach.

No Required Account

You do not need to create:

An AuraBeat account

A username

A password

A cloud profile


Local Data

Where applicable, AuraBeat stores user data locally, including:

Playlists

Playlist order

Playlist artwork references

Search history

Playback-related settings

App preferences



---

🚫 No Ads

AuraBeat is designed without intrusive advertisements inside the core music-player experience.


---

☁️ No Mandatory Cloud Sync

Playlists and local preferences do not require cloud synchronization.

Your locally created playlists remain on your device.


---

🛠️ Technology Stack

AuraBeat is built using modern Android technologies.

Language

Kotlin


UI

Jetpack Compose

Material 3


Architecture

MVVM

Repository Pattern

Clean Architecture principles

StateFlow

Coroutines


Local Storage

Room Database


Playback

AndroidX Media3

ExoPlayer

MediaSession


Image Loading

Coil


Networking

Retrofit

OkHttp


where required by existing app functionality.


---

📱 Android

AuraBeat is designed as a native Android application.

The project is intended to run efficiently across supported Android devices while adapting the interface to different screen sizes.


---

⚡ Performance

AuraBeat focuses on:

Fast startup

Smooth scrolling

Efficient image loading

Asynchronous database operations

Efficient audio playback

Low unnecessary background work

Stable queue management

Memory-conscious artwork loading



---

🎛️ Playback Controls

AuraBeat supports standard media controls through Android's media system.

Controls can work with:

Notification

Lock screen

Bluetooth devices

Headphones

Background playback

External media controls where supported



---

🔔 Media Notification

While music is playing in the background, the media notification can provide:

Album artwork

Song title

Artist

Previous

Play/Pause

Next

Seek controls where supported



---

📂 Local Music

AuraBeat can work with compatible music files available to the Android media/library system.

Supported playback formats depend on the device and Android/Media3 decoder capabilities.

For lossless playback, the actual result depends on:

Source file

Codec

Bit depth

Sample rate

Device hardware

Android audio path



---

🔄 Updates

AuraBeat can use GitHub Releases for distributing new versions.

A future/update-enabled build can provide:

Current version

Latest version

Update availability

Release notes

Update notification

GitHub Release page

APK release asset


Example:

Current Version: v1.0.0
Latest Version: v1.1.0

New Update Available


---

📦 Installation

Download

Download the latest Android APK from the project's GitHub Releases.

Install the APK on a compatible Android device.

> Android may require permission to install applications from the source used to obtain the APK.




---

🧑‍💻 Build From Source

Clone the repository:

git clone https://github.com/YOUR_USERNAME/AuraBeat-Android.git

Open the project in Android Studio.

Allow Gradle to sync.

Then run the application on a compatible Android device or emulator.


---

🔨 Build APK

Debug APK

./gradlew assembleDebug

Release APK

./gradlew assembleRelease

Android App Bundle

./gradlew bundleRelease

The generated files will be available inside the project's Gradle build output directories.


---

🧪 Testing

Before releasing a new version, test:

Music playback

Background playback

Lock-screen controls

Notification controls

Queue

Queue Endless

Shuffle

Repeat

Sleep Timer

Equalizer

Playlist creation

Playlist editing

Playlist sorting

Custom song arrangement

Gallery playlist artwork

App restart

Search

Recently Searched

Library

Favorites

Different screen sizes

Different Android versions



---

🗺️ Roadmap

✅ Completed / Planned Core Features

[x] Native Android music player

[x] AMOLED UI

[x] Background playback

[x] Media notification

[x] MediaSession

[x] Queue management

[x] Queue Endless

[x] Sleep Timer

[x] Equalizer

[x] Playlists

[x] Playlist sorting

[x] Custom playlist arrangement

[x] Custom playlist artwork

[x] Gallery wallpaper

[x] Local playlist storage

[x] Local search history


🚀 Future Improvements

[ ] More audio presets

[ ] More visualizer styles

[ ] Additional customization options

[ ] Performance improvements

[ ] Additional supported audio formats where available

[ ] More playlist customization

[ ] More playback customization



---

🤝 Contributing

Contributions, suggestions and improvements are welcome.

If you want to contribute:

1. Fork the repository.


2. Create a new branch.


3. Make your changes.


4. Test your changes.


5. Create a Pull Request.



Example:

git checkout -b feature/new-feature
git add .
git commit -m "Add new feature"
git push origin feature/new-feature


---

🐛 Bug Reports

If you find a bug, create a GitHub Issue and include:

Android version

Device model

AuraBeat version

Steps to reproduce

Expected behavior

Actual behavior

Screenshots/logs if useful


Please do not include private information in bug reports.


---

💡 Feature Requests

Have an idea for AuraBeat?

Create a GitHub Issue with:

Feature:
Why it would be useful:
How it should work:
Optional screenshots/references:


---

📸 Screenshots

Add AuraBeat screenshots here:

screenshots/
├── home.png
├── player.png
├── library.png
├── playlists.png
├── playlist.png
├── equalizer.png
└── settings.png

Example Markdown:

![AuraBeat Home](screenshots/home.png)
![AuraBeat Player](screenshots/player.png)
![AuraBeat Playlist](screenshots/playlist.png)


---

📄 License

Choose and add the license that matches how you want AuraBeat to be distributed.

For example:

Copyright © 2026 AuraBeat.

All rights reserved unless otherwise stated by the repository license.

Do not claim an open-source license unless the repository actually includes that license.


---

👨‍💻 Developer

AuraBeat

Instagram:

@Mr.amardeep_singh


---

🎵 AuraBeat

Feel Every Beat. Live Every Frame.

Built for music lovers who want a clean, powerful and immersive Android music experience.

⭐ Star the repository if you like AuraBeat.

🎵 Listen. Customize. Feel Every Beat.
