# Lab 8: AI Personalized Marketing Videos (A Welcome Just for You)

**Topic:** AI Personalized Marketing Videos  
**Tool:** OmniMedia → Avatar → Script Avatar  
**Level:** Beginner  
**Video format:** 9:16 (vertical)  
**Target duration:** 5–15 seconds (recommended: approximately 10–12 seconds)

---

## Goal

Create a **5–15-second personalized welcome video** featuring a friendly AI presenter. The host greets a customer by name (`[FIRST NAME]`), highlights one benefit of your brand (`[BRAND]`), and provides one clear onboarding action (`[NEXT STEP]`). Use **Script Avatar** with a presenter image and matching voiceover audio to produce natural expressions and synchronized lip movements.

---

## Before You Start

You will need:

- An **OmniMedia** account with **Avatar Studio** access and sufficient video-generation credits.
- A clear, front-facing presenter portrait suitable for **9:16 vertical** framing.
- A voiceover audio file named **`Laura.mp3`** that matches the chosen script and is **5–15 seconds** long.
- An approved personalized welcome message containing the customer's name, a brand benefit, and a next step.

> **Important:** If you change the customer's name, brand, or spoken text, create a new matching voiceover MP3. Do not upload `Laura.mp3` with a different script and assume the avatar will speak the new words.

---

## Sample Assets

The sample assets for this lab are referenced from the [`sample-assets/`](../sample-assets/) directory:

| Asset Type                | Requirement  | File Link                                                    | Description                                                                                                   |
| :------------------------ | :----------- | :----------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------ |
| **Presenter Avatar**      | **Required** | [woman_avatar.webp](../sample-assets/IMGs/woman_avatar.webp) | Friendly, professional presenter portrait suitable for a vertical video                                       |
| **Voiceover Audio Track** | **Required** | [Laura.mp3](../sample-assets/AUDIOs/Laura.mp3)               | Sample voiceover for the personalized welcome; verify that it matches the final script and lasts 5–15 seconds |

> **Note:** In OmniMedia, **Script Avatar** uses a selected presenter image and uploaded voiceover to generate a speaking avatar with lip synchronization. The written scripts below are **TTS-ready** if you need to create or replace the audio. The sample file must be available at the linked path in your workshop materials.

---

## Step 1: Open Script Avatar

1. Sign in to **OmniMedia**.
2. Open **Avatar** from the top navigation bar.
3. Under **Create**, select **Script Avatar**.

---

## Step 2: Add Your Presenter Avatar

1. Locate the **ADD AVATAR** box in the composer.
2. Click **ADD AVATAR**, then select a portrait or upload [`sample-assets/IMGs/woman_avatar.webp`](../sample-assets/IMGs/woman_avatar.webp).
3. Confirm that the preview shows the presenter clearly, facing forward, with even lighting.
4. Select **9:16 vertical** output if the composer offers an aspect-ratio setting.

> **Tip:** A vertically framed portrait supports mobile-friendly composition, but verify the final output's aspect ratio instead of assuming it automatically follows the image.

---

## Step 3: Prepare the Personalized Welcome Script

Choose **one** of the following. Only the words within the code blocks should be spoken; do not include headings, instructions, or visual directions in TTS.

### Template Script

Replace the placeholders with your customer's details and concise phrases **before** generating audio:

```text
Hi [FIRST NAME], welcome to [BRAND]! [ONE SHORT BENEFIT]. [ONE CLEAR NEXT STEP]. Let's get started!
```

**Example replacements:** `[ONE SHORT BENEFIT]` → `Create great videos in minutes`; `[ONE CLEAR NEXT STEP]` → `Open your dashboard and make your first video`.

### Ready-to-Use Script — OmniMedia

```text
Hi Alex, welcome to OmniMedia! Create professional videos in minutes. Open your dashboard and make your first video today!
```

### Duration and TTS Guidance

- **Target:** 5–15 seconds, ideally around **10–12 seconds**.
- **Script length:** Approximately **18–25 spoken words** is a useful starting point for a short, natural greeting. Actual audio duration varies with voice, pronunciation, and pauses.
- **Voice:** Choose a friendly, warm, clear voice with a natural conversational pace.
- **Script matching:** The uploaded `Laura.mp3` must contain the **exact approved narration**. If its words differ, regenerate the MP3 using your final script.
- **Personalization:** Replace `Alex` with the recipient's first name and listen for correct pronunciation before generating video.

---

## Step 4: Upload the Voiceover Audio

1. Click **Upload Audio** below the prompt box.
2. Select **Browse Files**.
3. Upload [`sample-assets/AUDIOs/Laura.mp3`](../sample-assets/AUDIOs/Laura.mp3), or the newly generated MP3 if you customized the script.
4. Confirm that the audio attachment displays **`Laura.mp3`** (or your replacement filename).
5. Play or review the audio if available. Check that the narration matches your selected script and lasts **between 5 and 15 seconds**.

> **Important:** If the supplied `Laura.mp3` contains different words or has a different duration, replace it with audio generated from the final narration. The MP3—not the target duration written in the prompt—determines how long the spoken segment will be.

---

## Step 5: Generate the Video

1. Verify that your presenter is selected in **ADD AVATAR**.
2. Confirm that **`Laura.mp3`**, or its matching personalized replacement, is attached.
3. If the composer requires a text prompt, use the **same spoken script** as the audio. Keep any visual instructions separate from the TTS input.
4. Verify the recipient's name, brand benefit, next action, and **9:16 vertical** format.
5. Check the displayed credit estimate, then click **Generate** once.
6. When generation is complete, navigate to **History → Creations** and preview your video.

---

## Step 6: Review and Download

Before using the personalized video, verify:

- [ ] **Duration:** The final video lasts **5–15 seconds**.
- [ ] **Personalization:** The presenter says the correct customer's name and brand.
- [ ] **Benefit and Next Step:** One relevant benefit and one clear action are spoken.
- [ ] **Audio Match:** The video uses the intended `Laura.mp3` narration or its correctly personalized replacement.
- [ ] **Lip-Sync:** Mouth movements match the audio throughout the video.
- [ ] **Eye Contact:** The presenter looks naturally toward the camera.
- [ ] **Visual Quality:** The face remains sharp, realistic, and well lit.
- [ ] **Tone:** Delivery sounds warm, clear, and unhurried.
- [ ] **Aspect Ratio:** The completed video is **9:16 vertical**.

Click **Download** to save the final `.mp4` file.

---

## Troubleshooting

| Problem                                             | Likely Cause                                                    | Solution                                                                                  |
| :-------------------------------------------------- | :-------------------------------------------------------------- | :---------------------------------------------------------------------------------------- |
| **“Please upload an audio file before generating”** | Voiceover audio was not attached.                               | Click **Upload Audio** and select `Laura.mp3` or your matching personalized MP3.          |
| **ADD AVATAR is empty or Generate is disabled**     | The presenter image or another required input is missing.       | Select an avatar, attach audio, and provide the required prompt.                          |
| **Video is longer than 15 seconds**                 | The audio is too long or contains excessive pauses.             | Shorten the narration, regenerate the MP3, and verify its length before generating again. |
| **Video is shorter than 5 seconds**                 | The audio is too short or spoken too quickly.                   | Use a slightly longer narration or a natural TTS speed, then recreate the MP3.            |
| **Recipient's name is mispronounced**               | The TTS voice has difficulty with the name.                     | Test a phonetic spelling when generating audio, then listen to the result.                |
| **Avatar says the wrong words**                     | `Laura.mp3` does not match the customized text.                 | Regenerate a voiceover from the final personalized script and upload it.                  |
| **Lip-sync is inaccurate**                          | Audio is unclear or does not align with the intended narration. | Use clean, matching audio without overlapping voices or music.                            |
| **Video is not vertical**                           | The output setting is incorrect.                                | Select **9:16** where available and confirm the framing.                                  |
| **Insufficient credits**                            | The account has fewer credits than required.                    | Check your credits before retrying.                                                       |
| **Avatar looks unnatural**                          | The portrait is blurry, angled, or poorly lit.                  | Use a sharp front-facing image with clear eyes and even lighting.                         |

---

## Expected Result

A downloadable **5–15-second, 9:16 vertical personalized welcome video** featuring:

1. A friendly AI presenter greeting the customer by first name.
2. One concise and relevant OmniMedia or company benefit.
3. One clear onboarding action.
4. Natural speech sourced from **`Laura.mp3`** (or a matching personalized MP3), with eye contact and synchronized lip movements.

The finished video can be used in welcome messages, onboarding flows, and personalized marketing campaigns.
