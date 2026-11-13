# Lab 9: Create an AI Virtual Influencer Video (Meet Nova, Your Virtual Style Guide)

**Topic:** AI Virtual Influencer Videos  
**Tool:** OmniMedia → Avatar → AI Influencer  
**Level:** Intermediate  
**Video format:** 9:16 (vertical)

---

## Goal

Launch and animate **Nova**, a fictional AI virtual fashion influencer. Using an approved character reference portrait, generate face-consistent fashion scenes and animate them into a high-fashion vertical video featuring casual outfit styling, natural human motion, and dynamic camera movement. The persona is clearly established as a digital/virtual creator, demonstrating how brands and agencies can deploy persistent virtual ambassadors without talent agency overhead.

---

## Before You Start

You will need:

- An **OmniMedia** account with **Avatar Studio** access and available generation credits.
- An approved high-resolution portrait reference for Nova in PNG, JPG/JPEG, or WebP format (or use the provided sample asset: [woman_avatar.webp](../sample-assets/IMGs/woman_avatar.webp)).
- Sample demo files can also be browsed directly in the [sample-assets/IMGs/](../sample-assets/IMGs/) directory.
- A clear vision of your virtual influencer's styling aesthetic, scene environment, and video motion.

---

## Step 1: Open AI Influencer

1. Sign in to **OmniMedia**.
2. Open **Avatar** in the top navigation bar.
3. Select the **AI Influencer** tab from the top menu.

---

## Step 2: Upload Your Persona Reference & Continue

1. On the left side of the panel, locate the **SOURCE** box.
2. Click **SOURCE** and upload the approved persona portrait: [woman_avatar.webp](../sample-assets/IMGs/woman_avatar.webp).
3. On the right side, enter your influencer's name in the **NAME** field:
   ```text
   Nova
   ```
4. *(Optional)* In the center field displaying **“Add optional context for the scene...”**, you may add initial background guidance or leave it blank.
5. Click the blue **Continue ✨** button.

> [!TIP]
> Using a high-resolution, front-facing portrait ensures that Nova's facial structure, hair color, and identity remain perfectly consistent throughout all subsequent scenes and video clips.

---

## Step 3: Generate Face-Consistent Scene Images

After clicking **Continue ✨**, the workspace updates to the scene creator view. Here you will place Nova into an aesthetic, fashion-forward environment:

1. In the text area displaying **“Describe a scene for your influencer...”**, enter your scene and outfit prompt:

   ```text
   Nova standing in a bright, sunlit minimalist architectural loft with warm afternoon light streaming through tall arched windows. She is wearing an aesthetic casual outfit: an oversized cream linen button-down shirt layered over a crisp white ribbed top, paired with tailored wide-leg trousers and delicate gold jewelry. Editorial lifestyle photography, soft natural shadows, clean 9:16 vertical composition.
   ```

2. Configure the scene parameters in the bottom controls:
   - **Model / Engine**: `omni-image-v1`
   - **Aspect Ratio**: Select **9:16** (or your desired campaign format)
   - **Variations**: Select your desired number of variations (choose how many scene options you want to generate)

3. Click **Generate Scene ✨**.
4. The engine will generate face-consistent variations of Nova in your specified outfit and setting.
5. Review the results and select your favorite generated scene image to serve as the base for your video.

---

## Step 4: Enter the Video Motion Prompt & Camera Direction

With your favorite scene image selected, enter the prompt describing Nova's dynamic physical actions, styling gestures, and camera movement.

### Template Video Prompt

```text
[INFLUENCER NAME] in [CHOSEN SCENE]. She [DYNAMIC MOVEMENT, e.g. turns smoothly toward the camera with a radiant, confident smile, gently touches her sleeve to highlight the relaxed cuff styling, and gives an engaging nod]. Soft natural lighting, subtle breeze moving through her hair, smooth cinematic depth of field, high-fashion 1080p vertical social video.
```

### Ready-to-Use Example (Webinar Showcase: Nova's Style Guide)

```text
Nova standing in the sunlit modern loft. She turns smoothly toward the camera with a confident, radiant smile, gently adjusts her sleeve to spotlight the relaxed linen cuff styling, and gives an engaging, warm nod of approval. Soft natural afternoon sunlight, gentle breeze in her hair, shallow depth of field, crisp 1080p vertical social video.
```

### Video Configuration Settings:

| Setting | Value | Why This Value |
| :--- | :--- | :--- |
| **Aspect Ratio** | **9:16** | Full-screen vertical format optimized for Instagram Reels, TikTok, and YouTube Shorts. |
| **Resolution** | **1080p** | Ensures high-definition fabric detail, hair realism, and sharp facial features. |
| **Camera Motion** | **Dolly In** | Creates a smooth, high-end cinematic push toward the creator as she presents her look. |

> [!NOTE]
> Selecting **Camera Motion: Dolly In** applies automated camera dolly mechanics, enhancing the editorial production value without requiring manual keyframing.

---

## Step 5: Generate the Influencer Video

1. Verify that your selected scene image of Nova is active as the reference.
2. Confirm your video motion prompt contains clear physical actions (turn, sleeve adjustment, smile).
3. Confirm settings: **9:16**, **1080p**, and **Camera Motion: Dolly In**.
4. Review the credit estimate beside **Generate ✨**.
5. Click **Generate ✨**.
6. Track generation progress:
   - *Phase 1*: Identity encoding and feature mapping from the selected scene.
   - *Phase 2*: Physical simulation, fabric movement, and camera path dynamics.
   - *Phase 3*: 1080p rendering and final MP4 encoding.
7. Once processing completes, navigate to **History → Creations** to preview your video.

---

## Step 6: Verify and Download

Inspect your final video against this quality checklist before presenting it in demos or campaigns:

- [ ] **Identity Consistency**: Nova’s facial structure, hair color, and expressions remain identical to the original reference image.
- [ ] **Natural Motion**: The body turn, arm movement, and facial expressions flow smoothly without rubbery distortions.
- [ ] **Fabric & Garment Fidelity**: The texture of the linen button-down and layered top reacts naturally to body movement.
- [ ] **Camera Dynamics**: The smooth dolly-in motion maintains stable perspective and sharp focal depth.
- [ ] **Virtual Persona Transparency**: Suitable for transparent branding as an official digital ambassador or virtual style guide.

Click **Download** to save your final `.mp4` video file locally.

---

## Troubleshooting

| Problem | Root Cause | Solution |
| :--- | :--- | :--- |
| **"Continue" button disabled** | Reference image was not uploaded or **NAME** field is empty. | Ensure an image is loaded into the **SOURCE** box and enter a name (e.g. `Nova`) in the **NAME** field. |
| **Persona face shifts across scenes** | Source reference image had extreme angles, heavy shadowing, or low resolution. | Use a clean, brightly lit, front-facing reference photo like [woman_avatar.webp](../sample-assets/IMGs/woman_avatar.webp). |
| **Motion feels static or rigid** | Video prompt lacked descriptive action verbs. | Include clear physical actions like *"turns smoothly toward camera"*, *"adjusts her sleeve"*, or *"gestures to her outfit"*. |
| **Scene aspect ratio mismatch** | Aspect ratio dropdown in Step 3 was left at 1:1 instead of 9:16. | Set the aspect ratio dropdown to **9:16** before clicking **Generate Scene ✨** for vertical social content. |
| **Insufficient Credits error** | Account balance is lower than the required amount. | Verify your credit balance in your account dashboard before starting generation. |

---

## Expected Result

A downloaded **9:16 vertical AI Influencer video (1080p)** featuring:
1. A consistent, photorealistic virtual fashion influencer (**Nova**).
2. Face-consistent scene imagery aligned with the approved reference asset.
3. Natural body movement, fabric motion, and an authentic editorial lifestyle aesthetic.
4. A complete branded asset ready for fashion lookbooks, social reels, or virtual brand ambassador campaigns.
