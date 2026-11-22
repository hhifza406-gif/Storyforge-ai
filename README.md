# StoryForge AI — Automatic Movie Maker

## Deploy on Vercel (free static hosting)
1. Extract this ZIP.
2. Upload the `storyforge_ai_movie_maker` folder to a GitHub repository.
3. In Vercel, choose **Add New → Project** and import that repository.
4. Framework Preset: **Other**.
5. Build Command: leave empty.
6. Output Directory: `.` (or leave default if Vercel detects the static site).
7. Deploy.

## What works in this version
- Paste a story or screenplay.
- Detect scene headings such as `SCENE 1`, `منظر 1`, `سین 1`.
- Detect dialogue speaker names from lines like `علی: ...`.
- Edit cast, character continuity descriptions, scenes, backgrounds and dialogue.
- Select realistic, 3D animated, or anime visual prompt style.
- Select Urdu, Hindi, English or Arabic speech language.
- Generate scene-by-scene video prompts.
- Use browser speech synthesis if voices are available.
- Record an animated scene-card preview as WebM.
- Save project in browser storage or export project JSON.

## Honest limitation
This is a functional local-first pre-production and animatic MVP. The WebM is an animated storyboard/scene-card preview, **not** photorealistic AI-generated live-action video. True generative video requires an actual video-generation model and compute (local GPU or a hosted service). This project intentionally does not pretend that an API-free static website can generate unlimited realistic AI footage.
