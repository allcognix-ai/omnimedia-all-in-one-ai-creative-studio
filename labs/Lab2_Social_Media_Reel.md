# Lab 2: 3 Reasons to Try This Coffee

**Topic:** AI Social Media Videos & Reels  
**Tool:** OmniMedia → Video → Ingredients to Video  
**Level:** Beginner  
**Video format:** 9:16 (vertical)

## Goal

Create a punchy social media reel for a coffee brand that opens with a dramatic coffee-pour hook, communicates **three approved selling points** with bold on-screen captions, and closes with an invitation to try it alongside the brand logo.

## Before You Start

You will need:

- An OmniMedia account with access to Video Studio and sufficient generation credits.
- The sample assets pre-loaded in `sample-assets/IMGs/` (brand logo and optional coffee pour reference image), or your own brand media.
- Three approved product benefits. The ready-to-use prompt uses verified gourmet coffee attributes. For your own brand, draw facts only from approved marketing or product copy.

## Sample Assets

The sample assets for this lab are pre-loaded in the [`sample-assets/IMGs/`](../sample-assets/IMGs) folder:

| Asset Type | Requirement | File Link | Description |
| :--- | :--- | :--- | :--- |
| **Brand Logo** | **Required** | [coffee-brand-logo.png](../sample-assets/IMGs/coffee-brand-logo.png) | High-contrast circular brand logo for OmniRoast Artisan Coffee |
| **Pour Reference** | *Optional* | [coffee-pour-reference.png](../sample-assets/IMGs/coffee-pour-reference.png) | Visual style reference depicting a steaming coffee pour on a rustic cafe table |

> [!NOTE]
> The **Ingredients to Video** tool in OmniMedia lets you compose video scenes by combining one or more visual assets (logos, photos, or reference clips) with a detailed scene-by-scene prompt.

## Step 1: Open Ingredients to Video

1. Sign in to **OmniMedia**.
2. Open **Video** in the top navigation bar.
3. Under the **Create** column in the dropdown menu, select **Ingredients to Video**.

## Step 2: Add Your Reference Ingredients

1. In the **Ingredients** composer area, click **+ Add Media** (or drag and drop your asset).
2. Select **Uploads → Browse Files** and choose `sample-assets/IMGs/coffee-brand-logo.png`.
3. Confirm that the logo appears in your active ingredients tray.
4. *(Optional)* Add `sample-assets/IMGs/coffee-pour-reference.png` if you want the generator to visually align with the rustic cafe aesthetic and steam style shown in the reference.

## Step 3: Enter the Reel Concept

Choose one of the prompts below and paste it into the **“Describe your video concept...”** prompt box.

### Template Prompt

Use this template for your own coffee or consumer brand. Replace the bracketed placeholders with your approved brand details and factual claims:

```text
Create a punchy 25-second social reel for [COFFEE BRAND]. Hook with a dramatic
coffee-pour shot, show three benefits drawn only from [APPROVED FACTS], add bold
captions and upbeat cuts. Close with "Try it today!" and supplied brand logo.

Scene breakdown:
- Hook (0-4s): Dynamic macro slow-motion pour of rich dark coffee into a ceramic mug, steam rising.
- Benefit 1 (4-10s): Close-up of roasted beans with bold caption: "[BENEFIT 1]".
- Benefit 2 (10-16s): Smooth pour showing crema swirl with caption: "[BENEFIT 2]".
- Benefit 3 (16-21s): Fresh cup held in hands in warm cafe light with caption: "[BENEFIT 3]".
- Outro (21-25s): Clean end-card displaying the supplied brand logo with animated text "Try it today!".

Pacing: Upbeat modern social reel, snappy transitions, vibrant contrast, vertical 9:16 composition.
```

### Ready-to-Use Prompt

Use this prompt directly with the provided sample assets (`coffee-brand-logo.png` and `coffee-pour-reference.png`). It contains confirmed, ready-to-generate details:

```text
Create a punchy vertical 9:16 social reel for OmniRoast Artisan Coffee. Hook with a dramatic coffee-pour shot, show three benefits drawn only from approved facts, add bold captions and upbeat cuts. Close with "Try it today!" and supplied brand logo.

Scene progression:
1. Hook (0-5s): Extreme close-up slow-motion shot of dark, velvety coffee pouring into a ceramic cup on a rustic wooden table with delicate steam rising.
2. Reason 1: "100% Single-Origin Arabica" — crisp shot of sun-dried coffee beans being hand-selected.
3. Reason 2: "Rich Dark Cocoa & Caramel Notes" — swirl of golden crema in the fresh brew.
4. Reason 3: "Ethically Sourced & Freshly Roasted" — modern artisan cafe background with warm morning light.
5. Outro: The camera pulls back slightly, displaying the supplied OmniRoast brand logo clearly centered on screen with the caption "Try it today!".

Visual style: Cinematic warm tones, shallow depth of field, bold legible on-screen captions, high energy social media pacing.
```

## Step 4: Choose the Settings & Model

Configure the generation parameters:

| Setting | Select | Description |
| :--- | :--- | :--- |
| **Model** | **Kling V3 Omni (`omni-ingr-3.0`)** *(Recommended)* | High-tier multi-reference model supporting vertical 9:16 reels, 1080p, and native audio |
| **Aspect Ratio** | **9:16** | Vertical orientation optimized for Instagram Reels, TikTok, and YouTube Shorts |
| **Resolution** | **1080p** | Crisp high-definition output |
| **Duration** | **10s–15s** | Standard social media reel duration |
| **Generate Audio** | **On** | Automatically generates synchronized ambient coffeehouse sounds and upbeat audio |
| **Enhance Prompt** | **On** | Optimizes prompt descriptive fidelity for the AI model |

### Choosing the Right Model for Ingredients to Video

OmniMedia provides multiple model tiers for **Ingredients to Video**. For a vertical social reel, model selection depends on aspect ratio compatibility, multi-reference handling, and visual fidelity:

| Model Tier | Model Name | Key Features | Best Suited For |
| :--- | :--- | :--- | :--- |
| **High (Recommended)** | **Kling V3 Omni (`omni-ingr-3.0`)** | Multi-reference (up to 7 images + 1 video), native audio, 1080p, full 9:16 vertical support | **Best choice for this reel**: Preserves the brand logo reference, incorporates cafe style elements, and generates native ambient audio. |
| **High** | **Seedance 2 (`omni-ingr-3.1`)** | Up to 12 combined inputs (images/videos/audio) using `[Video1] [Audio1]` tokens | Complex multi-modal reels combining pre-recorded video clips and audio tracks. |
| **Standard** | **Wan R2V (`omni-ingr-2.0`)** | Up to 4 reference images/videos, character binding, shot type control | Cost-effective 1080p generation with controlled shot camera movement. |

> [!NOTE]
> **Veo 3.1 (`omni-ingr-4.0`)** is not suitable for Lab 2 because it strictly requires a 16:9 widescreen aspect ratio, whereas this reel is formatted in 9:16 vertical.

Check the credit estimate beside the **Generate** button before proceeding.

## Step 5: Generate the Video

1. Verify that your logo is attached in the Ingredients tray.
2. Confirm your prompt and settings (**Model: Kling V3 Omni**, **9:16**, **1080p**).
3. Click **Generate Video** once.
4. Track generation progress in the top notification tray or open **History**.
5. Once completed, navigate to **History → Creations** to preview the finished reel.

## Step 6: Check and Download

Before exporting, review your generated reel against this quality checklist:

- [ ] **Hook:** Does the video open immediately with a clear, dramatic coffee pour?
- [ ] **Features:** Are the three selling points clearly communicated with legible text/captions?
- [ ] **Branding:** Does the closing scene incorporate the supplied OmniRoast brand logo?
- [ ] **Formatting:** Is the video properly framed in vertical **9:16** with no key elements cut off?
- [ ] **Pacing:** Are cuts upbeat and natural for social media audiences?

If any element needs improvement, tweak the scene description in your prompt and re-run. When satisfied, click **Download** to save your MP4 file.

## Troubleshooting

| Problem | What to Do |
| :--- | :--- |
| **Generate is disabled** | Ensure at least one ingredient asset is uploaded and your prompt is not empty. |
| **Logo does not appear at the end** | Explicitly reinforce the closing instruction in the prompt: *"End with the uploaded brand logo centered against a clean background."* |
| **Pacing is too slow** | Include terms like *"snappy cuts"*, *"fast-paced transitions"*, and *"dynamic camera motion"* in the prompt. |
| **Captions are blurry or missing** | State caption wording in quotation marks (e.g. `caption: "100% Single-Origin"`) and ensure resolution is set to 1080p. |
| **Credit limit notice appears** | Review your active plan credits with your workshop instructor. |

## Expected Result

A completed, downloaded **9:16 vertical social reel** featuring a dramatic coffee pour hook, three bold product value propositions, and an outro showcasing the OmniRoast brand logo.
