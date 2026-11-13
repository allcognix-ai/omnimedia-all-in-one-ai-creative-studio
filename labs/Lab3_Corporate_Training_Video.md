# Lab 3: Workplace Cybersecurity: Three Habits

**Topic:** AI Corporate Training Videos  
**Tool:** OmniMedia → Video → Ingredients to Video  
**Level:** Beginner  
**Video format:** 16:9 (widescreen landscape)

## Goal

Create a 60-second employee training video that features a professional workplace presenter introducing **three practical phishing-prevention habits**, demonstrates a realistic email scam example, displays readable do-and-don't captions, and closes with a memorable recap and reporting reminder.

## Before You Start

You will need:

- An OmniMedia account with access to **Video Studio** and sufficient credits for video generation.
- The sample reference assets pre-loaded in `sample-assets/IMGs/` (presenter reference image and phishing email mockup).
- Three confirmed workplace security habits from your approved corporate policy. (The ready-to-use prompt below uses industry-standard security awareness practices).

## Sample Assets

The sample assets for this lab are pre-loaded in the [`sample-assets/IMGs/`](../sample-assets/IMGs) folder:

| Asset Type | Requirement | File Link | Description |
| :--- | :--- | :--- | :--- |
| **Presenter Reference** | **Required** | [presenter-reference.png](../sample-assets/IMGs/presenter-reference.png) | High-resolution image of a professional corporate workplace presenter |
| **Phishing Example** | **Required** | [phishing-email-reference.png](../sample-assets/IMGs/phishing-email-reference.png) | Mockup email demonstrating sender spoofing, artificial urgency, and unverified links |

> [!NOTE]
> In OmniMedia, **Ingredients to Video** allows you to supply multiple visual ingredients (such as a presenter image and an educational slide/mockup) and combine them with scene-by-scene prompt directives in widescreen **16:9** landscape format.

## Step 1: Open Ingredients to Video

1. Sign in to **OmniMedia**.
2. Click **Video** in the top navigation bar.
3. Under the **Create** column in the dropdown menu, select **Ingredients to Video**.

## Step 2: Add Your Reference Ingredients

1. In the **Ingredients** tray, click **+ Add Media** (or drag and drop your files).
2. Choose `sample-assets/IMGs/presenter-reference.png` and confirm it appears in the tray.
3. Click **+ Add Media** again and select `sample-assets/IMGs/phishing-email-reference.png`.
4. Confirm both reference assets are visible in your active ingredients bar.

## Step 3: Enter the Training Concept

Choose one of the prompts below and paste it into **“Describe your video concept...”**.

### Template Prompt

Use this template to customize the training with your organization's internal security policy:

```text
Create a 60-second employee training video with a professional presenter introducing three workplace phishing-prevention habits from [APPROVED POLICY]. Include one realistic email example, readable do-and-don't captions, a short recap and a closing reminder to report suspicious messages.

Using the uploaded presenter reference image and email mockup:
1. Introduction (0–12s): Professional presenter in modern tech office introduces the security briefing on phishing prevention.
2. Habit 1 & Realistic Example (12–28s): Cut to the email mockup on screen. Presenter highlights the spoofed sender address and artificial urgency red flag. Caption: "[HABIT 1]".
3. Habit 2 (28–42s): Presenter explains link and URL inspection. Caption: "[HABIT 2]".
4. Habit 3 (42–54s): Presenter explains verifying unexpected requests through secondary channels. Caption: "[HABIT 3]".
5. Conclusion (54–60s): Summary recap card highlighting all three habits, ending with "When in doubt, report it immediately to security."

Visual style: 16:9 widescreen landscape, crisp high-contrast captions, calm authoritative delivery, professional enterprise aesthetic.
```

### Ready-to-Use Prompt

Use this pre-configured prompt directly with the provided sample assets:

```text
Create a 60-second employee training video with a professional presenter introducing three workplace phishing-prevention habits from approved policy. Include one realistic email example, readable do-and-don't captions, a short recap and a closing reminder to report suspicious messages.

Using the uploaded presenter reference image and phishing email mockup:
1. Introduction (0–12s): The professional presenter in smart business attire stands in a modern tech office and introduces today's cybersecurity briefing on phishing defense.
2. Habit 1 & Realistic Example (12–28s): Transition to the uploaded phishing email on screen. The presenter points out the spoofed sender domain and the artificial 15-minute urgency red flag. Caption: "Habit 1: Scrutinize the Sender Address".
3. Habit 2 (28–42s): The presenter demonstrates hovering before clicking links. Caption: "Habit 2: Hover to Inspect URLs".
4. Habit 3 & Recap (42–54s): The presenter explains calling the purported sender to confirm unusual requests. Caption: "Habit 3: Verify Out-of-Band".
5. Conclusion (54–60s): Summary card with the 3 habits and closing text: "When in doubt, don't click — report immediately to IT Security."

Visual style: 16:9 widescreen, clean corporate training presentation, legible high-contrast captions, calm authoritative delivery.
```

## Step 4: Choose Settings & Model

Configure the generation parameters:

| Setting | Selection | Purpose |
| :--- | :--- | :--- |
| **Model** | **Veo 3.1 (`omni-ingr-4.0`)** *(Recommended)* or **Kling V3 Omni (`omni-ingr-3.0`)** | High-tier cinematic models supporting subject consistency, native audio, and 1080p |
| **Aspect Ratio** | **16:9** | Standard widescreen landscape format for corporate LMS, desktop monitors, and team presentations |
| **Resolution** | **1080p** | High-definition clarity for legible on-screen email text |
| **Duration** | **8s** (for Veo 3.1) / **10s–15s** (for Kling V3 Omni) | Cinematic training scene duration |
| **Generate Audio** | **On** | Generates clear, professional corporate narration and background audio |
| **Enhance Prompt** | **On** | Optimizes prompt descriptive fidelity for the AI model |

### Choosing the Right Model for Ingredients to Video

OmniMedia provides multiple model tiers for **Ingredients to Video**. For a widescreen 16:9 corporate training video with a presenter and document mockup, model selection depends on subject consistency, aspect ratio, and composition depth:

| Model Tier | Model Name | Key Features | Best Suited For |
| :--- | :--- | :--- | :--- |
| **High (Recommended)** | **Veo 3.1 (`omni-ingr-4.0`)** | Subject-consistent generation (up to 3 reference images), 8s cinematic clips, native audio, requires 16:9 | **Best choice for corporate training**: Purpose-built for 16:9 widescreen landscape with strong subject consistency, keeping the instructor identity stable alongside the phishing email mockup. |
| **High** | **Kling V3 Omni (`omni-ingr-3.0`)** | Multi-reference composition (up to 7 images + 1 video), native audio, 1080p, up to 15s | Excellent alternative when you need longer single clip durations (up to 15s) or more visual reference inputs. |
| **High** | **Seedance 2 (`omni-ingr-3.1`)** | Up to 12 combined inputs (images/videos/audio) using `[Video1] [Audio1]` tokens | Multi-media modules incorporating pre-recorded audio tracks or existing video demos. |
| **Standard** | **Wan R2V (`omni-ingr-2.0`)** | Up to 4 reference images/videos, character binding, shot type control | Cost-effective 1080p corporate training drafts with camera shot control. |

Check the credit estimate beside the **Generate** button before proceeding.

## Step 5: Generate the Video

1. Verify that both `presenter-reference.png` and `phishing-email-reference.png` are in the Ingredients tray.
2. Check your prompt text and confirm settings (**Model: Veo 3.1 or Kling V3 Omni**, **16:9**, **1080p**).
3. Click **Generate Video** once.
4. Track generation progress in the top notification tray or **History**.
5. Once completed, navigate to **History → Creations** to preview the rendered video.

## Step 6: Review and Download

Audit your completed corporate training video against this checklist:

- [ ] **Presenter Consistency:** Does the presenter match the uploaded professional reference image?
- [ ] **Email Demonstration:** Is the phishing email mockup clearly shown with legible red flags?
- [ ] **Habit Captions:** Are all three habits displayed with clear, bold on-screen subtitles?
- [ ] **Aspect Ratio:** Is the video properly formatted in **16:9** widescreen landscape?
- [ ] **Closing CTA:** Does the outro clearly remind employees to report suspicious messages?

When satisfied, click **Download** to save the video file (MP4).

## Troubleshooting

| Problem | What to Do |
| :--- | :--- |
| **Generate button is disabled** | Ensure both ingredient images are uploaded and the prompt box is not empty. |
| **Email text is too small or blurry** | Verify that **Resolution** is set to **1080p** and specify *"close-up focus on the email warning banner"* in the prompt. |
| **Video renders vertically** | Double-check that **Aspect Ratio** is set to **16:9** instead of 9:16. |
| **Credit limit notice appears** | Review your active Video Studio credits with the workshop instructor. |

## Expected Result

A downloaded **16:9 widescreen corporate training video** featuring a professional AI workplace presenter teaching three essential phishing prevention habits, showing a realistic email threat simulation, and closing with a clear reporting reminder.
