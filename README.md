# CALL in ALFA

A lightweight video editor that runs in your browser. It is built for low-RAM laptops and works fully offline once the page is open.

Your videos stay on your laptop. Nothing is uploaded.

## Features

- Loading screen and project setup (project name, video name, description)
- Media Pool with video thumbnails
- Multi-track timeline: V2 for titles, V1 for video, A1 for audio
- Split clips at the playhead, trim start and end, delete clips
- Title text overlays with a custom duration
- Basic color correction: brightness, contrast, saturation
- Playback controls and timecode, with Space to play or pause
- Export to 720p `.webm` with audio
- Resolve-style dark layout with Edit, Color and Deliver pages

## How to use

1. Open the page in Chrome or Edge on a laptop or desktop (screen width of at least 1024px).
2. Wait for the loading screen, then fill in the project details and press OK.
3. Click **+ Add video** to import clips. Double-click a thumbnail in the Media Pool to add it to the timeline again.
4. Drag the ruler to move the playhead. Use **Split at playhead** and the Trim sliders to cut.
5. Add titles in the Inspector. Adjust color on the Color page.
6. Go to Deliver and press **Export**.

## Limitations

- Single video track with simple audio. No separate audio editing, transitions or effects.
- Export runs in real time, so a 2-minute video takes about 2 minutes. Keep the page open.
- Output is `.webm`. Convert to MP4 with a tool like HandBrake if you need it.
- Color is not applied in Safari exports.
- Not designed for phones or small screens.

## Run locally

Open `index.html` in Chrome or Edge. No install or build step is needed.

## Notes

This is an independent project. It is not affiliated with or based on the code of DaVinci Resolve or Blackmagic Design.
