# Lab 5: Meet Your Virtual Support Host

**Topic:** AI Avatar & Digital Human Videos  
**Tool:** OmniMedia → Avatar → Script Avatar  
**Level:** Beginner  
**Video format:** 16:9 (widescreen landscape)  
**Target duration:** 5–15 seconds (aim for approximately 10–13 seconds)

## Goal

Create a 5–15-second branded customer service video featuring a friendly, consistent AI avatar. The virtual support host should maintain natural eye contact against a neutral studio backdrop, introduce three customer help channels, and conclude with a support portal address approved by your company.

## Before You Start

You will need:

- An OmniMedia account with access to **Avatar Studio** and sufficient credits for avatar video generation.
- The sample assets pre-loaded in `sample-assets/` (virtual host avatar image and voiceover audio track), or your own brand media.
- Approved customer support details (the ready-to-use script below is customized for TGX Technologies).
- A **TTS voiceover that matches your chosen script exactly**. If you change the script, regenerate the audio before creating the avatar video.

## Sample Assets

The sample assets for this lab are pre-loaded in the [`sample-assets/`](../sample-assets) directory:

| Asset Type                | Requirement  | File Link                                                                                        | Description                                                                         |
| :------------------------ | :----------- | :----------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------- |
| **Virtual Host Avatar**   | **Required** | [support-host-avatar.png](../sample-assets/IMGs/support-host-avatar.png)                         | Friendly, professional customer support representative on a neutral studio backdrop |
| **Voiceover Audio Track** | **Required** | [virtual-support-host-voiceover.mp3](../sample-assets/AUDIOs/virtual-support-host-voiceover.mp3) | Regenerated 5–15-second MP3 containing the exact short narration below              |

> **Note:** In OmniMedia, **Script Avatar** pairs an avatar portrait with a voice audio file and a prompt to animate facial expressions, eye contact, and lip movements. Select **16:9** landscape format. The video duration follows the uploaded audio.

> **Important:** The original sample MP3 was designed for a 40-second video. **Do not reuse that recording unchanged.** Regenerate it using one of the short scripts below, then replace the sample file before the lab.

## Step 1: Open Script Avatar

1. Sign in to **OmniMedia**.
2. Click **Avatar** in the top navigation bar.
3. Under the **Create** column in the dropdown menu, select **Script Avatar**.

## Step 2: Select Your Virtual Host Avatar

1. Click the avatar slot on the left side of the composer.
2. In the modal, select a pre-made avatar from the catalog or click **Upload** to choose `sample-assets/IMGs/support-host-avatar.png`.
3. Confirm that the support host image appears in the avatar preview box.

## Step 3: Prepare and Attach the Voiceover Audio Track

1. Choose either the **Template Script** or **Ready-to-Use Script** in Step 4.
2. Generate the voiceover using a TTS tool. Use a warm, clear, friendly American English voice at a natural pace.
3. Preview the audio and confirm it lasts **between 5 and 15 seconds**. Aim for roughly **10–13 seconds**; do not rush the voice unnaturally.
4. Save the new audio as `virtual-support-host-voiceover.mp3`, replacing the old 40-second sample file if preparing workshop assets.
5. Click **Upload Audio** below the prompt box.
6. Select **Browse Files** and upload your new MP3.
7. Confirm that the audio pill displays the selected filename.

## Step 4: Enter the Script

Both options below contain **spoken words only**. They are ready to paste into a TTS tool. Do not include timing labels, stage directions, or visual instructions in the TTS input.

### Template Script

Replace `COMPANY` and `SUPPORT ADDRESS` with your actual company name and TTS-friendly, verified support address **before** generating the audio. Do not feed the placeholders to TTS:

```text
Welcome to COMPANY! Need help? Explore our Knowledge Base, start Live Chat, or submit a support ticket. Visit SUPPORT ADDRESS.
```

### Ready-to-Use Script — TGX Technologies

Use this short narration for the TGX Technologies virtual support host. It contains approximately 27 spoken words and is intended to fit under 15 seconds at a natural speaking pace:

```text
Welcome to TGX Technologies! Need help? Explore our Knowledge Base, start Live Chat, or submit a support ticket. Visit support dot T G X technologies dot com.
```

> **Before publishing:** Confirm that `support.tgxtechnologies.com` is your official, active support portal. The spoken URL above is written phonetically for TTS and has **not been independently verified**. Replace it if the approved address differs. Preview the final audio because pauses and pronunciation can change its duration.

> **Visual guidance (not for TTS):** Use a friendly, professional male support host, a clean neutral studio background, warm lighting, direct eye contact, and 16:9 framing. If your video workflow supports text overlays, show **Knowledge Base**, **Live Chat**, and **Support Ticket**, plus the verified support URL at the end. Add overlays separately; do not paste these instructions into the TTS script.

## Step 5: Generate the Video

1. Verify that your avatar is selected and the correct audio track is attached.
2. Enter the selected script in the prompt field if the workflow requires text, ensuring it matches the uploaded audio.
3. Check that **16:9** landscape orientation is selected and the audio lasts **no more than 15 seconds**.
4. Click **Generate** once.
5. Track generation progress in the top notification tray or **History**.
6. Once completed, navigate to **History → Creations** to preview the digital human host.

## Step 6: Review and Download

Audit the completed video against this checklist:

- [ ] **Eye Contact:** Does the avatar maintain natural, friendly eye contact?
- [ ] **Lip-Sync Accuracy:** Are lip movements synchronized with the uploaded speech?
- [ ] **Channel Presentation:** Are the Knowledge Base, Live Chat, and support ticket mentioned clearly?
- [ ] **Studio Setting:** Is the background clean, neutral, and free of obvious artifacts?
- [ ] **16:9 Framing:** Is the video correctly framed in widescreen landscape mode?
- [ ] **Support Address:** Does the closing line use the company-approved URL?
- [ ] **Audio Consistency:** Does the spoken narration exactly match the selected script?
- [ ] **Duration:** Is the finished video between **5 and 15 seconds**?

When satisfied, click **Download** to save the MP4 file.

## Troubleshooting

| Problem                                             | What to Do                                                                                                          |
| :-------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------ |
| **“Please upload an audio file before generating”** | Click **Upload Audio** and attach the matching MP3 voiceover.                                                       |
| **Generate button is disabled**                     | Confirm an avatar is selected, the required prompt is present, and an audio file is attached.                       |
| **Avatar appears in portrait orientation**          | Change the orientation setting to **16:9** before generating.                                                       |
| **Audio and lip movements do not match**            | Make sure the MP3 contains the exact final script; regenerate the voiceover if you edited the text.                 |
| **TTS reads the URL awkwardly**                     | Use spoken wording such as “support dot T G X technologies dot com.”                                                |
| **Video runs longer than 15 seconds**               | Regenerate the MP3 with the short script, trim long pauses, and confirm the new audio duration before trying again. |
| **Credit limit notice appears**                     | Review your Avatar Studio credits with the workshop instructor.                                                     |

## Expected Result

A downloadable **5–15-second, 16:9 widescreen digital human video** featuring a friendly TGX Technologies virtual host introducing the Knowledge Base, Live Chat, and support tickets with natural eye contact and synchronized speech, then ending with a company-approved support address. Aim for **10–13 seconds**; confirm the actual runtime in the exported video.
