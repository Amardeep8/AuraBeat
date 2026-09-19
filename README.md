

IMPORTANT:
Use the two attached reference images as the visual/functional reference for the FULL-SCREEN PLAYER controls.

I want a NEW Appearance option inside AuraBeat Settings named:

“Apple Music Inspired”

When this Appearance option is enabled, completely change ONLY the visual layout/style of the Full-Screen Music Player controls to match the design language shown in the reference images.

DO NOT copy Apple Music branding, logos, artwork, or proprietary assets.
This must remain an ORIGINAL AuraBeat design inspired by the clean, minimal, translucent, rounded media-control style shown in the references.

==================================================
1. NEW APPEARANCE OPTION
==================================================

Go to:

Settings
→ Appearance

Add a new appearance option:

APPLE MUSIC INSPIRED

Display it as a selectable appearance/style option.

Example:

Appearance

○ Default
○ AMOLED
○ Glass
● Apple Music Inspired

When selected:

- Immediately apply the new Full-Screen Player visual style.
- Do not restart the app.
- Do not restart the current song.
- Do not pause playback.
- Do not recreate ExoPlayer.
- Do not recreate the MediaSession.
- Preserve the currently playing track and position.

When disabled:

→ Restore the previously selected AuraBeat player appearance.

==================================================
2. SCOPE — VERY IMPORTANT
==================================================

This new Appearance option should primarily modify the:

FULL-SCREEN MUSIC PLAYER

Do NOT redesign:

- Home
- Search
- Explore
- Library
- Playlist
- Settings layout
- Mini Player
- Notification
- Lock Screen

unless the existing Appearance architecture already applies shared visual properties.

Do not change functionality outside the requested appearance/player-control changes.

==================================================
3. FULL-SCREEN PLAYER — REFERENCE 1
==================================================

Use the FIRST attached reference image as the base layout reference.

The player should have:

TOP / UPPER AREA:

Large unobstructed album artwork/background.

The artwork should fill the available player area.

Apply:

- Dynamic artwork
- Soft blur where appropriate
- Dark translucent overlay
- Smooth gradient
- High-quality image scaling
- AMOLED-friendly background

The artwork must remain visually dominant.

==================================================
4. TOP PLAYER CONTROLS
==================================================

Keep the existing AuraBeat navigation/back behavior.

Top controls should remain minimal.

Use:

LEFT:
Back button

RIGHT:
Three-dot More button

The three-dot button must remain clearly visible over the artwork.

Use a subtle translucent circular or glass background if necessary to maintain visibility.

Do not make the top bar visually heavy.

==================================================
5. THREE-DOT MENU
==================================================

The RIGHT-SIDE THREE-DOT BUTTON in the Full-Screen Player must open the existing player options.

Do NOT remove existing functionality.

The menu should contain the existing AuraBeat options such as:

- Add to Playlist
- Add to Favorites
- Queue
- Equalizer
- Lyrics
- Sleep Timer
- Playback settings
- Audio settings
- Song Information
- Download
- Share

Use the existing functionality.

Do not create duplicate implementations.

==================================================
6. MAIN PLAYBACK CONTROLS
==================================================

Match the clean visual hierarchy from the references.

Near the lower-middle portion of the screen:

PREVIOUS
PLAY / PAUSE
NEXT

Controls must be:

- Large
- Simple
- White/light
- Centered
- Easy to tap
- Visually balanced

The PLAY button must be the primary control.

Use smooth transitions:

Play → Pause
Pause → Play

Do not restart the song when the icon changes.

==================================================
7. PROGRESS BAR
==================================================

Add a clean horizontal progress slider.

Layout:

Current position
──────────────●──────────────
                         Total duration

The slider should have:

- Thin track
- Smooth thumb
- High contrast
- Rounded edges
- Smooth progress animation

Dragging must seek the EXISTING ExoPlayer.

Do not create a second playback system.

Display:

Current time on the left.

Total duration on the right.

The progress position must remain synchronized with the real player position.

==================================================
8. VOLUME CONTROL
==================================================

Below or around the progress area, provide the clean volume control appearance shown in the reference style when supported by the existing AuraBeat player.

Use:

Low volume icon
──────────── slider ────────────
High volume icon

Important:

Volume changes must control the existing playback engine.

Do not create a fake volume slider.

If Android/device limitations prevent direct system-volume control, use the existing supported AuraBeat volume behavior.

==================================================
9. REFERENCE 1 — LOWER CONTROL AREA
==================================================

The FIRST reference shows a minimal lower control area.

Recreate this visual philosophy:

LEFT:
Lyrics / lyrics-related button

CENTER:
A rounded translucent segmented control containing:

Headphones / output
|
User/profile or existing player destination control

RIGHT:
Queue / playlist button

The controls must feel lightweight and translucent.

Do not use large solid Material cards.

==================================================
10. REFERENCE 2 — ALTERNATIVE CONTROL STATE
==================================================

The SECOND attached reference shows another control configuration.

When appropriate, the same lower control area should support:

Shuffle
|
Repeat
|
∞ / Endless / AutoMix

and:

Queue button on the RIGHT.

Use a single clean rounded translucent control group.

For example:

┌────────────────────────────────────┐
│  Shuffle   │   Repeat   │   ∞      │
└────────────────────────────────────┘

and separately:

                         [ Queue ]

The selected mode should have a subtle translucent/highlighted background.

==================================================
11. CONTROL STATE LOGIC
==================================================

Do NOT display multiple duplicate controls.

The player should intelligently show the appropriate controls based on the current player state/configuration.

Possible lower control layout:

STATE A:

Lyrics        [ Output | Player ]        Queue

STATE B:

Lyrics        [ Shuffle | Repeat | ∞ ]   Queue

The exact implementation should fit the existing AuraBeat player architecture.

DO NOT create fake buttons.

Every button must connect to the actual existing functionality.

==================================================
12. SHUFFLE
==================================================

Shuffle button:

- Toggle existing shuffle mode.
- Use the existing queue/player.
- Update the icon state immediately.
- Persist state according to existing AuraBeat settings.

Do NOT create another queue.

Do NOT randomly select a song outside the existing playback architecture.

==================================================
13. REPEAT
==================================================

Repeat button should support the existing repeat modes:

Off
Repeat One
Repeat All

Use clear visual states.

Example:

Repeat OFF:
Normal icon

Repeat ALL:
Highlighted icon

Repeat ONE:
Icon with “1”

Connect directly to the existing Media3 repeat mode.

==================================================
14. ENDLESS / AUTOMIX
==================================================

The ∞ button should integrate with the EXISTING AuraBeat AutoMix/endless playback system.

Do not create another AutoMix engine.

If AutoMix is enabled:

- Keep the existing AutoMix behavior.
- Continue queue handling correctly.
- Preserve crossfade/fade settings.
- Do not create duplicate playback requests.

If AutoMix is disabled:

- Display the inactive state.

==================================================
15. QUEUE BUTTON
==================================================

Place the Queue button on the RIGHT side as shown in the second reference.

It should open the existing Queue screen/panel.

Queue icon should be:

- Three horizontal lines
- Small leading dots/lines if appropriate
- Clean white icon
- Rounded translucent background

Queue must show the real current queue.

Do not create a second queue.

==================================================
16. LYRICS BUTTON
==================================================

Place the lyrics button on the LEFT side where appropriate.

It should open AuraBeat's existing lyrics functionality.

If lyrics are unavailable:

Show the existing unavailable state.

Do not fabricate lyrics.

Do not change the current song.

==================================================
17. OUTPUT / DEVICE BUTTON
==================================================

Where the first reference shows the headphone/output area:

Use AuraBeat's existing audio-output functionality if available.

Possible destinations:

- This phone
- Bluetooth device
- Headphones
- Other supported audio output

The visual design should match the reference:

rounded translucent pill
+
simple white icon
+
clean divider
+
destination information.

Do not create fake Bluetooth/output functionality.

==================================================
18. GLASS / TRANSLUCENT STYLE
==================================================

The Apple Music Inspired appearance should use:

- Translucent controls
- Soft glass effect
- Rounded capsules
- Subtle background blur
- Soft highlights
- Minimal borders
- White/light icons
- Strong readability
- Large touch targets

Avoid:

- Heavy borders
- Bright colored cards
- Excessive shadows
- Standard rectangular Material buttons
- Clutter
- Oversized text
- Random gradients

==================================================
19. DYNAMIC ARTWORK
==================================================

The Full-Screen Player background should automatically adapt to the current song artwork.

When Song A → Song B:

Artwork changes smoothly.

Background changes smoothly.

Do NOT flash white/black.

Do NOT restart playback.

Do NOT reset playback position.

Do NOT reload the player unnecessarily.

Use the existing artwork data.

==================================================
20. CURRENT SONG INFORMATION
==================================================

Keep the current song information accurate.

Display:

Song title
Artist
Optional album

Use the exact metadata associated with the currently playing track.

IMPORTANT:

Never identify the current song using only:

- title
- list index
- artist name

Use the existing stable track/video ID.

Do not rename songs.

Do not replace metadata with generated values.

==================================================
21. PLAYER STATE SYNCHRONIZATION
==================================================

The UI must always reflect the real Media3/ExoPlayer state.

Synchronize:

- Play/Pause
- Current position
- Duration
- Shuffle
- Repeat
- AutoMix
- Queue
- Current song
- Loading
- Buffering
- Ended

When the player changes from Song A → Song B:

The UI must immediately update:

Artwork
Title
Artist
Duration
Progress
Queue state
Playback controls

Do not show Song A controls while Song B is already playing.

==================================================
22. IMPORTANT — DO NOT CAUSE PLAYBACK BUGS
==================================================

This Appearance redesign MUST NOT introduce the existing AuraBeat playback problems.

Do NOT:

- Create another ExoPlayer
- Create another MediaSession
- Call prepare() unnecessarily
- Call stop() during UI recomposition
- Call pause() when the screen redraws
- Call play() repeatedly
- Restart the current song when appearance changes
- Reload the current MediaItem unnecessarily
- Recreate the playback service
- Clear the queue

Compose recomposition must NEVER affect playback.

==================================================
23. APPEARANCE SWITCHING
==================================================

When user changes:

Default
→ Apple Music Inspired

or:

Apple Music Inspired
→ Default

the current song must continue from the exact same position.

Example:

Song playing at:

02:17

User changes Appearance.

Result:

Song still playing at approximately:

02:17

No pause.

No restart.

No buffering caused by the appearance switch.

No MediaItem replacement.

==================================================
24. ANIMATIONS
==================================================

Add premium animations:

- Play/pause morph
- Artwork transition
- Progress movement
- Control selection
- Shuffle activation
- Repeat activation
- AutoMix activation
- Queue opening
- Lyrics opening
- Appearance switching

Animations should be subtle and smooth.

Do not animate the actual audio engine.

Do not introduce playback delay.

==================================================
25. RESPONSIVE DESIGN
==================================================

Support:

- Small phones
- Large phones
- Different aspect ratios
- Portrait
- Existing supported landscape behavior

Controls must never:

- overlap artwork
- overlap song information
- go below the screen
- become unreachable
- collide with navigation bars

Respect:

- status bar
- navigation bar
- display cutouts
- gesture navigation

==================================================
26. AMOLED OPTIMIZATION
==================================================

The Apple Music Inspired appearance should remain compatible with AuraBeat's AMOLED philosophy.

Use very dark background regions around the artwork.

Do not force a bright white background.

Dark mode should remain the primary experience.

==================================================
27. ACCESSIBILITY
==================================================

Every control must have a proper content description.

Examples:

"Previous track"
"Play"
"Pause"
"Next track"
"Seek position"
"Volume"
"Lyrics"
"Audio output"
"Shuffle"
"Repeat"
"AutoMix"
"Queue"
"More options"

Ensure touch targets are comfortably usable.

==================================================
28. SETTINGS PREVIEW
==================================================

Inside:

Settings → Appearance

Show a small visual preview for:

Apple Music Inspired

The preview should communicate:

- Dark artwork background
- Large playback controls
- Translucent pill controls
- Queue button
- Minimal player layout

Do not load an actual player instance inside Settings.

The preview must be static.

==================================================
29. PERSISTENCE
==================================================

Save the selected appearance locally using AuraBeat's existing settings/preferences system.

If the user selects:

Apple Music Inspired

then closes/reopens the app:

Apple Music Inspired should remain selected.

Do not add Firebase or cloud storage.

==================================================
30. EXISTING FULL-SCREEN PLAYER MENU
==================================================

The existing Full-Screen Player three-dot menu must continue working.

Do not remove existing options.

Integrate existing options cleanly with the new appearance.

Existing features such as:

- Equalizer
- Sleep Timer
- Lyrics
- Stats for Nerds
- Audio settings
- Download
- Playlist actions

must remain functional.

Do not create duplicate settings.

==================================================
31. VISUAL DETAIL — REFERENCE MATCH
==================================================

Use the attached images carefully.

I want the visual language of:

IMAGE 1:
- Minimal upper controls
- Large artwork/background
- Large previous/play/next controls
- Thin progress slider
- Volume slider
- Translucent rounded lower control group
- Output/device area
- Queue button
- Minimal typography

IMAGE 2:
- Same overall player
- Lower control group changed to:
  Shuffle | Repeat | ∞
- Queue button positioned separately on the right
- Translucent capsule design
- Selected control has a subtle lighter/translucent state

Keep the two control arrangements visually consistent.

==================================================
32. DO NOT COPY BRANDING
==================================================

This is an Apple Music INSPIRED appearance only.

Do NOT add:

- Apple logo
- Apple Music logo
- Apple branding
- Apple proprietary icons
- Apple trademark text
- Apple-specific promotional content

Use AuraBeat branding and original icons/components.

==================================================
33. DO NOT REDESIGN OTHER AURABEAT SCREENS
==================================================

Strictly protect:

Home
Search
Explore
Library
Playlist
Mini Player
Notification
Settings functionality
Download system
Playback service
Audio engine

Only add:

Settings → Appearance → Apple Music Inspired

and apply the requested visual treatment to the Full-Screen Player.

==================================================
34. TECHNICAL IMPLEMENTATION
==================================================

Before coding:

Inspect the existing:

- Appearance settings
- Settings ViewModel
- Full-Screen Player Composable
- Player ViewModel
- Playback Controller
- Media3/ExoPlayer
- MediaSession
- Queue manager
- Audio output system
- Existing lyrics system
- Existing Equalizer
- Existing AutoMix
- Existing Repeat/Shuffle state

Reuse the existing architecture.

Do not create duplicate classes when an existing implementation can be reused.

Create reusable Compose components if appropriate:

AppleInspiredPlayerControls
AppleInspiredProgressBar
AppleInspiredControlPill
AppleInspiredQueueButton
AppleInspiredOutputControl

Use the existing theme/state system.

==================================================
35. FINAL QUALITY CHECK
==================================================

Before finishing, verify:

[ ] Appearance setting exists
[ ] Apple Music Inspired option exists
[ ] Selection persists
[ ] Player changes immediately
[ ] Full-screen player uses the new visual style
[ ] Artwork remains high quality
[ ] Back button works
[ ] Three-dot button works
[ ] Previous works
[ ] Play works
[ ] Pause works
[ ] Next works
[ ] Progress slider works
[ ] Volume control works where supported
[ ] Lyrics works
[ ] Output/device control works where supported
[ ] Shuffle works
[ ] Repeat works
[ ] AutoMix/∞ integrates with existing system
[ ] Queue button works
[ ] Queue displays the real queue
[ ] Current song metadata is correct
[ ] Artwork changes correctly with songs
[ ] Appearance switching does not pause music
[ ] Appearance switching does not restart music
[ ] Appearance switching does not reload MediaItem
[ ] Lock-screen playback remains unaffected
[ ] Notification remains unaffected
[ ] Background playback remains unaffected
[ ] No duplicate ExoPlayer
[ ] No duplicate MediaSession
[ ] No duplicate audio engine
[ ] No duplicate queue
[ ] No playback race condition
[ ] No Compose recomposition playback bug
[ ] No Kotlin errors
[ ] No Compose errors
[ ] No resource errors
[ ] App builds successfully

==================================================
FINAL GOAL
==================================================

Create a premium AuraBeat Full-Screen Player appearance inspired by the attached references.

The result should feel:

MINIMAL
PREMIUM
AMOLED
TRANSLUCENT
CINEMATIC
CLEAN
MODERN
MUSIC-FIRST

The first reference should define the primary player layout.

The second reference should define the alternate lower control arrangement with:

Shuffle | Repeat | ∞

and the separate Queue button on the right.

Most importantly:

THIS IS A VISUAL/UX APPEARANCE CHANGE.

DO NOT TOUCH OR DUPLICATE THE EXISTING AUDIO ENGINE.

DO NOT INTRODUCE ANY NEW AUTO-PAUSE, AUTO-STOP, LOADING, AUTO-NEXT, QUEUE, OR PLAYBACK BUG.

The current song must continue playing normally while the new appearance is applied.         ==================================================
DEFAULT APPEARANCE — APPLE MUSIC INSPIRED
==================================================

IMPORTANT:

Set:

“Apple Music Inspired”

as the DEFAULT AuraBeat Appearance.

On a fresh installation, first launch, or when Appearance settings have never been configured before:

Settings → Appearance → Apple Music Inspired

must be automatically selected.

The Full-Screen Player must therefore open in the Apple Music Inspired design by default.

DEFAULT VALUE:

appearanceStyle = APPLE_MUSIC_INSPIRED

Do NOT default to:

- Default
- Classic
- Standard
- AMOLED
- Glass

Apple Music Inspired must be the initial/default appearance.

==================================================
PERSISTENCE RULE
==================================================

If the user has never manually selected an Appearance:

→ Apple Music Inspired is used automatically.

If the user manually selects another Appearance:

→ Respect the user's selection.
→ Save it using the existing local settings/preferences system.
→ Do not automatically switch it back to Apple Music Inspired.

If the user clears/resets Appearance settings:

→ Reset Appearance to Apple Music Inspired.

If the app is updated:

→ Preserve the user's existing Appearance selection.
→ Do not overwrite an existing user preference.

Only a missing/uninitialized Appearance value should default to:

APPLE_MUSIC_INSPIRED

==================================================
IMPORTANT PLAYBACK RULE
==================================================

Setting Apple Music Inspired as the default appearance MUST NOT:

- Pause music
- Stop music
- Restart music
- Reload the current MediaItem
- Reset playback position
- Recreate ExoPlayer
- Recreate MediaSession
- Recreate the audio engine
- Clear the queue

Appearance initialization must be purely a UI/settings operation.

If music is already playing while the appearance preference is initialized or changed, playback must continue seamlessly.<img width="675" height="1200" alt="WhatsApp Image 2026-09-10 at 12 54 44 PM" src="https://github.com/user-attachments/assets/ddd01d64-4ab9-4ede-87c2-5b826a7136ca" />

<img width="750" height="1598" alt="WhatsApp Image 2026-09-10 at 9 37 56 PM" src="https://github.com/user-attachments/assets/26b461ab-b2ba-40e9-9379-8a7f9639e05d" />
<img width="750" height="1598" alt="WhatsApp Image 2026-09-10 at 9 37 41 PM" src="https://github.com/user-attachments/assets/b8af0c5d-bc42-4c31-b9f4-a959f3436afd" />
<img width="750" height="1598" alt="WhatsApp Image 2026-09-10 at 9 37 41 PM (1)" src="https://github.com/user-attachments/assets/e050796e-4376-41dd-8573-c1375507a970" />
<img width="750" height="1598" alt="WhatsApp Image 2026-09-10 at 9 37 40 PM" src="https://github.com/user-attachments/assets/b8513e25-0ecb-4bff-b628-13343aa873d0" />
<img width="750" height="1598" alt="WhatsApp Image 2026-09-10 at 9 37 40 PM (3)" src="https://github.com/user-attachments/assets/c9a4198e-d6c5-4b47-b5eb-8dfccc7f857e" />
<img width="750" height="1598" alt="WhatsApp Image 2026-09-10 at 9 37 40 PM (2)" src="https://github.com/user-attachments/assets/c5b751e1-d31a-410c-8d62-b6c7f4249d52" />
<img width="750" height="1598" alt="WhatsApp Image 2026-09-10 at 9 37 40 PM (1)" src="https://github.com/user-attachments/assets/b1238545-6ab8-4f5f-ac29-0237c9ba9c75" />
<img width="750" height="1598" alt="WhatsApp Image 2026-09-10 at 9 37 39 PM" src="https://github.com/user-attachments/assets/7088bf12-a9c4-461d-8d09-fb683d4c0889" />
<img width="750" height="1598" alt="WhatsApp Image 2026-09-10 at 9 37 39 PM (1)" src="https://github.com/user-attachments/assets/d6028bd0-273e-413e-8089-d4f01f45b923" />


