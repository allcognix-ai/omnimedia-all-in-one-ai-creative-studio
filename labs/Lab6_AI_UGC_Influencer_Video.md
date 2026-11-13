# Lab 6: Create an AI UGC & Influencer-Style Product Video

**Topic:** AI UGC & Influencer-Style Videos  
**Tool:** OmniMedia → Avatar → UGC Videos  
**Level:** Beginner  
**Video format:** 9:16 (vertical)

---

## Goal

Create an authentic, first-person vertical UGC (User-Generated Content) video featuring an AI creator reviewing and interacting with a physical product (e.g., a daily productivity planner). Use dual reference conditioning (both a **product image** and a **creator avatar image**) to generate photorealistic physical interaction, native spoken dialogue, and a crisp on-screen text tagline.

---

## Before You Start

You will need:

- An **OmniMedia** account with **Avatar Studio** access and sufficient credits for video generation.
- A clear, well-lit image of the **physical product** in PNG, JPG/JPEG, or WebP format (or use the provided sample asset: [planner.png](../sample-assets/IMGs/planner.png)).
- A clear front-facing portrait photo of the **creator/avatar** in PNG, JPG/JPEG, or WebP format (or use the provided sample asset: [woman_avatar.webp](../sample-assets/IMGs/woman_avatar.webp)).
- Both sample demo files can also be browsed directly in the [sample-assets/IMGs/](../sample-assets/IMGs/) folder.
- Two or three verified product benefits to feature in the dialogue or visuals.

---

## Step 1: Open UGC Videos

1. Sign in to **OmniMedia**.
2. Open **Avatar** in the top navigation.
3. Select the **UGC Videos** tab in the top tab bar.

---

## Step 2: Add Your Product and Avatar Images

1. **Upload the Product**:
   - In the **Product Image** box, click **Upload**.
   - Select your product photo (or use the sample asset: [planner.png](../sample-assets/IMGs/planner.png)).
   - Confirm that the preview displays the product clearly with visible branding.
2. **Upload the Creator/Avatar**:
   - In the **Avatar Image** box, click **Upload**.
   - Select your creator's portrait (or use the sample asset: [woman_avatar.webp](../sample-assets/IMGs/woman_avatar.webp)).
   - Confirm that the face is unobstructed and well-lit.

> [!NOTE]
> In the **UGC Videos** tab, both image boxes (Product and Avatar) are provided. The AI engine conditions simultaneously on both references to preserve product shape and creator identity.

---

## Step 3: Enter the UGC Video Concept & Script

In **“Describe your product ad concept...”**, enter a sensory, action-oriented prompt. Include the creator's setting, how they physically handle the product, their exact spoken words in quotes, and an ending tagline.

### Template Prompt

```text
A relatable [CREATOR TYPE, e.g. young professional creator] sitting in a [SETTING, e.g. sunlit modern home office desk], looking directly at the camera with an engaging, authentic smile. They hold up the physical reference [PRODUCT NAME] in their hands, [PHYSICAL ACTION, e.g. gently fanning through its clean daily pages to showcase the layout]. They speak directly to the camera in a warm, enthusiastic conversational voice: "[EXACT SPOKEN DIALOGUE]". Natural handheld smartphone camera movement with subtle organic sway. Soft warm natural daylight, shallow depth of field with a cozy blurred background, high detail 1080p vertical UGC video. End with text: "[TAGLINE IN QUOTES]".
```

### Ready-to-Use Example (Webinar Showcase: Daily Planner)

```text
A relatable young professional creator sitting at an aesthetic sunlit oak desk in a modern studio apartment, looking directly at the camera with an engaging smile. She holds up the physical reference planner in her hands, gently fanning through its clean, crisp daily pages to demonstrate the layout. She speaks directly to the camera in a warm, enthusiastic conversational voice: "This simple layout doubled my daily productivity in just one week!" Natural smartphone handheld camera movement with subtle organic sway. Soft warm afternoon sunlight, shallow depth of field with a cozy blurred background, high detail 1080p vertical UGC video. End with text: "Plan With Clarity."
```

#### Why This Prompt Works:
- **Physical Interaction**: Explicitly instructs the engine how the avatar holds and displays the reference product.
- **Direct Dialogue**: Placing spoken words in quotes tells the native audio engine exactly what dialogue to generate.
- **Handheld Feel**: "Smartphone handheld camera movement with subtle organic sway" removes the stiff CGI look and creates genuine UGC authenticity.
- **Tagline Enforcement**: Ending with `End with text: "Plan With Clarity."` automatically triggers the platform's automated tagline extractor and spelling verification system.

---

## Step 4: Choose the Settings

Configure the parameters according to our platform's optimized configuration:

| Setting | Value | Why This Value |
| :--- | :--- | :--- |
| **Aspect Ratio** | **9:16** | Native vertical format for Instagram Reels, TikTok, and YouTube Shorts. |
| **Quality** | **Premium** | Activates our **Premium Engine**, which supports dual reference conditioning, 1080p resolution, and native audio generation. |
| **Duration** | **8s** | Supported duration setting for Premium Quality. |
| **Style** | **Casual / Lifestyle** | Keeps lighting and texture looking like genuine social media content. |
| **Lighting** | **Natural Sunlight** | Warm, inviting creator desk aesthetic. |
| **Camera** | **Eye Level** | Engages the viewer directly as if on a face-to-face video call. |

> [!IMPORTANT]
> Always check the credit estimate displayed beside **Generate** before starting. **Premium (8s)** uses Premium tier credits for full 1080p video and native audio synthesis.

---

## Step 5: Generate the Video

1. Verify that both reference images (Product: [planner.png](../sample-assets/IMGs/planner.png) and Avatar: [woman_avatar.webp](../sample-assets/IMGs/woman_avatar.webp), or your custom files) are uploaded and visible in their respective boxes.
2. Confirm the prompt text contains your dialogue in quotes and ending tagline.
3. Confirm settings: **9:16**, **Premium**, **8s**.
4. Click **Generate** once.
5. Track generation progress:
   - *Phase 1*: S3 asset upload and credit verification.
   - *Phase 2*: Premium AI video and native audio generation pipeline.
   - *Phase 3*: Spelling analysis and text overlay rendering.
6. When complete, navigate to **History → Creations** to view your video.

---

## Step 6: Check and Download

Before sharing or presenting in your webinar, review the checklist:

- [ ] **Product Consistency**: The planner/product in the video matches the uploaded reference image in color, size, and branding.
- [ ] **Avatar Consistency**: The creator's facial features match the uploaded avatar portrait.
- [ ] **Natural Interaction**: The creator holds and interacts with the product naturally without visual artifacts or warping.
- [ ] **Audio & Lip Sync**: Spoken dialogue is clear, audible, and matches the creator's mouth movements.
- [ ] **Text Overlay**: The ending tagline (e.g., *"Plan With Clarity."*) is spelled correctly and legible.
- [ ] **Framing & Aspect Ratio**: Full **9:16 vertical frame** with the product and creator clearly visible.

Click **Download** to save the `.mp4` file locally.

---

## Troubleshooting

| Problem | Root Cause | Solution |
| :--- | :--- | :--- |
| **"duration_sec must be one of 4, 6, or 8 for premium"** | An unsupported duration was entered for Premium quality. | Set **Duration** to **8s** (or 4s / 6s). |
| **"avatar_image is required"** | The Avatar upload box was left empty in the UGC Videos tab. | Upload a creator portrait photo (or switch to **Product Ad Video** tab if no creator is needed). |
| **Audio is muffled or missing dialogue** | The prompt lacked clear conversational dialogue in quotes. | Put the exact words the creator should speak in quotation marks (e.g., `"This planner changed my week!"`). |
| **Flagged by Safety Filter (E005 / Sensitive Content)** | The reference image triggered an automated safety false-positive. | The backend automatically applies an edge-crop retry. If it persists, use an image with neutral lighting and no intense background contrast. |
| **Tagline text is deformed or misspelled** | The tagline was embedded ambiguously in the prompt. | Use the explicit trigger format at the end: `End with text: "Your Tagline Here."` |
| **Insufficient Credits error** | Account balance is lower than the required amount for Premium Quality. | Check your credit balance in your account dashboard or upgrade tier. |

---

## Expected Result

A downloaded **9:16 vertical UGC video (8 seconds, 1080p)** featuring:
1. A photorealistic creator holding and interacting with your physical product.
2. Synchronized native spoken audio delivering your hook.
3. A clean text tagline overlay at the conclusion.
4. An engaging, authentic asset ready to showcase in webinars, client pitches, or paid ad campaigns.
