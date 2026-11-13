# Lab 7: AI Video Localization & Dubbing (One Tutorial, Two Languages)

**Topic:** AI Video Localization & Dubbing  
**Tool:** OmniMedia → Avatar → Video Translation  
**Level:** Beginner  
**Video format:** 16:9 (horizontal) or 9:16 (vertical) — preserves the original video aspect ratio

---

## Goal

Translate an existing video tutorial or product walkthrough into a second language while preserving the original speaker's vocal tone, pacing, and emotional delivery. The AI Video Translation engine automatically performs speech-to-speech translation, voice cloning, and photorealistic lip-syncing without requiring any text prompt.

---

## Before You Start

You will need:

- An **OmniMedia** account with sufficient credits (credits are calculated dynamically based on the length of the uploaded video).
- A clear source video file in **MP4, MOV, MKV, or WebM** format.
- *(Optional sample asset)* You can use the provided sample tutorial video: [tutorial_sample.mp4](../sample-assets/VIDEOs/tutorial_sample.mp4) located in the [sample-assets/VIDEOs/](../sample-assets/VIDEOs/) directory.
- **Audio Clarity Check**: Ensure the source video has clear, audible speech. Videos with clear front-facing presenters and minimal background music or overlapping crosstalk yield the cleanest lip-sync and audio quality.
- **No Prompt Required**: Unlike generative video creation tools that require detailed written prompts, Video Translation is a fully automated audio-visual pipeline. It directly analyzes the audio track and visual facial movements of your source video.

---

## Step 1: Open Video Translation

1. Sign in to **OmniMedia**.
2. Open **Avatar** in the top navigation bar.
3. Under **Create / Tools**, select **Video Translation**.

---

## Step 2: Upload Your Source Video

1. In the **Source Video** box, click **Upload**.
2. Select your tutorial video (e.g., your own `.mp4` file or the demo file: [tutorial_sample.mp4](../sample-assets/VIDEOs/tutorial_sample.mp4)).
3. Verify that the video preview and duration load properly in the player.

> [!NOTE]
> Supported video formats include `.mp4`, `.mov`, `.mkv`, and `.webm`.

---

## Step 3: Configure Localization Settings

Select your target language and desired processing mode:

| Setting | Selection | Why This Value |
| :--- | :--- | :--- |
| **Source Video** | Uploaded video file | The base video containing speech and a visible speaker. |
| **Target Language** | **Spanish** *(or your desired language)* | The language your video will be translated and dubbed into. |
| **Processing Mode** | **Precision** | Advanced multi-pass processing offering tighter lip-sync alignment and voice timbre preservation (recommended for tutorials and product webinars). |

### About Processing Modes:
- **Speed Mode**: Faster turnaround time. Best for quick drafts, internal reviews, and rapid social media tests.
- **Precision Mode**: Performs higher-accuracy acoustic alignment and finer phoneme-to-lip matching. Recommended for customer-facing tutorials, webinars, and commercial marketing.

---

## Step 4: Generate the Localized Video

1. Confirm your source video is loaded and the target language is selected.
2. Check the dynamic credit estimate displayed next to the **Translate Video** button (based on video duration).
3. Click **Translate Video** once.
4. The automated pipeline will run through the following stages:
   - *Phase 1 — Ingestion*: Video upload, audio extraction, and duration verification.
   - *Phase 2 — Translation & Dubbing*: Speech recognition, natural language translation, and voice cloning in the target language.
   - *Phase 3 — Lip-Sync Synthesis*: Re-rendering mouth movements to match the new language phonemes seamlessly.
   - *Phase 4 — Packaging*: Final muxing of high-definition video and translated audio.
5. Once complete, view the localized result in **History → Creations**.

---

## Step 5: Check and Download

Before sharing or presenting the localized video in your webinar, verify the output against this checklist:

- [ ] **Voice Likeness**: The translated voice matches the pitch, tone, and character of the original speaker.
- [ ] **Lip Synchronization**: Mouth movements realistically match the translated words rather than the original language.
- [ ] **Visual Integrity**: The original video resolution, aspect ratio (16:9 or 9:16), visual timing, and on-screen actions remain intact.
- [ ] **Speech Clarity**: The dubbed audio is clear, well-paced, and free of audio distortion.

Click **Download** to save your localized `.mp4` video locally.

---

## Troubleshooting

| Problem | Root Cause | Solution |
| :--- | :--- | :--- |
| **"video_file is required" / Generate disabled** | No video file was uploaded. | Click **Upload** and select a valid video file before proceeding. |
| **"video_file must be .mp4/.mov/.mkv/.webm"** | The uploaded video is in an unsupported container format (e.g., `.avi` or `.wmv`). | Convert the video to standard `.mp4` (H.264 / AAC) and re-upload. |
| **"Could not read video duration"** | The video file is corrupted, empty, or missing an audio track. | Ensure the video plays normally on your local machine and contains an active spoken audio stream. |
| **"Insufficient credits" error** | Account balance is lower than the amount required for the video duration. | Check your available credit balance or translate a shorter sample clip. |
| **Muffled or unnatural lip-sync** | The original video had loud background music, heavy echo, or multiple overlapping speakers. | Use a source video with clear, isolated dialogue and a clear view of the speaker's face. |

---

## Expected Result

A downloaded localized video tutorial that:
1. Retains your original visuals, aspect ratio, and pacing.
2. Speaks fluently in your chosen target language with the original presenter's voice profile.
3. Features seamless, natural lip-syncing aligned with the translated speech.
4. Allows you to expand existing product tutorials and webinars to international markets in minutes.

