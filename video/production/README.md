# Video production package for TNT — "我的第一个APP"

This commit adds storyboard frames, subtitles (30s + 15s), voiceover script, a hero poster and social images, a phone mockup, and a production README to help the editor assemble the final 30s ad.

Files added (paths in repo):
- assets/visuals/logo.svg (already committed)
- assets/visuals/hero_poster.svg
- assets/visuals/social_1080x1080.svg
- assets/visuals/social_1200x630.svg
- assets/video/storyboard/frame01.svg ... frame08.svg
- assets/video/subtitles/30s.srt
- assets/video/subtitles/15s.srt
- assets/video/voiceover/voiceover_30s.txt
- assets/video/mockup_phone.svg

Quick assembly instructions (for editor)
1. Assets: use the storyboard frames as guide frames for timing. Each SVG can be exported to PNG at 1920x1080 for rough animatic.
2. Subtitles: import assets/video/subtitles/30s.srt into Premiere/Final Cut/DaVinci and align with the voiceover track.
3. Voiceover: record the script in assets/video/voiceover/voiceover_30s.txt, single dry vocal take, 24-bit WAV, 48kHz.
4. Music & SFX: choose an upbeat electronic / light pop track (BPM 95–110). Layer click/whoosh/ding SFX as indicated in the storyboard notes.
5. Export settings: H.264 Main Profile, 1920x1080, 23.976 fps, bitrate ~12–18 Mbps for web; also export 1080p for social 30s and a 15s cut (crop to vertical 9:16 if needed).

If you want, I can now:
- Export PNG previews of each storyboard frame at 1920x1080 and add them to the repo; or
- Produce a simple animatic MP4 by combining the frames and the SRT placeholder (requires rendering capability — I can provide an FFmpeg command you can run locally); or
- Generate final-deliverable export presets and a Premiere/DaVinci project template (XML/EER) — tell me which DAW/NLE you use.

