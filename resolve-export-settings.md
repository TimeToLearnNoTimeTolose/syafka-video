# Resolve Export Settings

This document contains all export presets used in my Syafka workflow.

---

## Blu-ray Clips for Resolume Avenue

### DaVinci Resolve

- Format: QuickTime
- Codec: H.264
- Resolution: 1920 × 1080
- Frame rate: Match the source (23.976 fps for this clip).
- Quality: Automatic
- Render: Select Single clip when exporting one marked In/Out range. Select Individual clips when each cut on the timeline should become a separate file.
- Audio: Disable Export Audio if only the visuals are needed.

### Resolume Alley

1. Drag the exported clips into Alley.
2. Select DXV 3, Normal Quality, No Alpha.
3. Keep the size and frame rate the same as the source.
4. Convert the clips, then drag the converted files into Avenue.

---

## Main YouTube Video

Purpose:
Final long-form upload.

### Syafka Title / Intro

- Resolve Title: Long Title Lower Third
- Text:
  SYAFKA |
  WHEN DISTORTION BECOMES NORMALITY
- Font: Open Sans
- Weight: Bold
- Colour: White
- Size: 0.0394
- Tracking: 1.165
- Duration: 5 seconds

### Title Usage

- Place title on V2 above the finished Avenue video.
- Position at the beginning of the timeline.
- Replace the second line with the current track title.
- Keep "SYAFKA |" as the standard first line.

### Master Audio Preparation

- Use the final mastered WAV on A1.
- Mute/remove the audio recorded by Avenue after alignment.
- Use Audio Time Units for precise master alignment if required.

### Video Export

- Format: QuickTime
- Codec: H.264
- Resolution: Timeline Resolution (1920x1080)
- Frame Rate: Timeline Frame Rate (30fps)
- Quality: Restrict to 30000 Kb/s
- Encoding Profile: High
- Key Frames: Automatic
- Frame Reordering: Enabled

- Render: Single Clip
- Hardware Acceleration: Enabled
- Network Optimization: Disabled
- Entropy Mode: Auto
- Multi-pass Encode: Disabled

### Audio Export

- Codec: Linear PCM
- Sample Rate: Same as Project (48000Hz)
- Bit Depth: 24-bit

---

## Social Media

Purpose:
Instagram, TikTok and YouTube Shorts.

### Timeline

- Resolution: 1080 x 1920
- Frame Rate: 30fps

### Export

- Format: QuickTime
- Codec: H.264
- Quality: 30000 Kb/s
- Encoding Profile: High
- Audio: Linear PCM
- Bit Depth: 24-bit
