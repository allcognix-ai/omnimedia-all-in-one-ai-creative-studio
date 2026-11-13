# Lab 10: Create an AI Multi-Character Dialogue Video (A Customer Story: Q&A Interview)

**Topic:** Multi-Character Interaction & Dialogue Videos  
**Tool:** OmniMedia → Avatar → Multi Character Videos  
**Level:** Intermediate  
**Video format:** 9:16 (vertical)

---

## Goal

Create a dynamic multi-character video featuring two distinct AI avatars engaging in a natural back-and-forth dialogue (a host interviewer and a client sharing their success story). By assigning dedicated images, unique names, and distinct voices to each character, the **Multi Character Videos** engine automatically synthesizes character-specific speech, animates individual lip-sync per turn, and seamlessly stitches the scene switches into one cohesive video.

---

## Before You Start

You will need:

- An **OmniMedia** account with **Avatar Studio** access and available video credits.
- Two distinct character portrait images in PNG, JPG/JPEG, or WebP format:
  - **Character 1 (Host / Interviewer)**: [woman_avatar.webp](../sample-assets/IMGs/woman_avatar.webp)
  - **Character 2 (Client / Founder)**: [man_avatar.webp](../sample-assets/IMGs/man_avatar.webp)
- Both sample demo files can also be browsed directly in the [sample-assets/IMGs/](../sample-assets/IMGs/) directory.
- A concise, punchy conversational script (~35–40 words total) formatted with speaker tags.

> [!TIP]
> For live webinars and customer presentations, keeping the dialogue punchy (~12 to 15 seconds total) ensures rapid generation while delivering maximum visual impact.

---

## Step 1: Open Multi Character Videos

1. Sign in to **OmniMedia**.
2. Open **Avatar** in the top navigation bar.
3. Select the **Multi Character Videos** tab from the top menu.

---

## Step 2: Configure Your Two Characters

In the character setup panels, define your two speakers with unique names, photos, and voice profiles:

### Character 1 (Host / Interviewer)
1. **Name**: Enter `Maya`.
2. **Image**: Click **Upload Image** and select the host portrait: [woman_avatar.webp](../sample-assets/IMGs/woman_avatar.webp).
3. **Voice**: Select a preferred voice from the voice library (or upload a custom voice sample).

### Character 2 (Client / Founder)
1. **Name**: Enter `David`.
2. **Image**: Click **Upload Image** and select the guest portrait: [man_avatar.webp](../sample-assets/IMGs/man_avatar.webp).
3. **Voice**: Select a distinct contrasting voice from the voice library (or upload a custom voice sample).

> [!IMPORTANT]
> Character names in the setup panel must match the speaker prefixes in your script exactly (e.g. `Maya` and `David`).

---

## Step 3: Enter the Multi-Speaker Script

In the script editor, enter your dialogue. Format each line with the character's name followed by a colon (`Name: text`). Blank lines between speaking turns indicate natural scene transitions.

### Ready-to-Use 14-Second Example (~37 Words)

```text
Maya: David, what was the biggest change after switching your workflow to OmniMedia?

David: We cut our video production time by ninety percent and doubled client engagement in just two weeks!

Maya: That is what we love to hear. Ready to transform your creative workflow? Start today!
```

#### Why This Script Works:
- **Fast, High-Impact Pacing**: At ~37 words across 3 turns, generation completes quickly during live demos while showcasing two clean speaker transitions.
- **Clear Speaker Tags**: `Maya:` and `David:` tell the engine exactly who speaks each line and when to switch avatars on screen.
- **Authentic Turn-Taking**: Natural question-and-answer dynamic breaks the monotony of single-speaker talking heads.

---

## Step 4: Generate the Video

1. Verify that both characters (**Maya** and **David**) have their respective portraits and voices assigned.
2. Review your script in the editor to ensure speaker names match the character fields.
3. Check the credit estimate displayed beside **Generate ✨**.
4. Click **Generate ✨**.
5. Track generation progress:
   - *Phase 1*: Script parsing and scene segmentation by speaker.
   - *Phase 2*: Individual voice synthesis for Maya and David.
   - *Phase 3*: Facial animation and lip-sync rendering per scene.
   - *Phase 4*: Automated video concatenation and audio normalization.
6. Once processing is complete, navigate to **History → Creations** to preview your video.

---

## Step 5: Verify and Download

Inspect your final multi-character video against this quality checklist before sharing:

- [ ] **Speaker Alignment**: Maya speaks only her lines with her assigned voice; David speaks only his lines with his assigned voice.
- [ ] **Clean Scene Cuts**: The visual transition between Maya and David occurs smoothly between dialogue turns.
- [ ] **Lip Synchronization**: Each avatar’s lip movements stay locked to their respective spoken dialogue.
- [ ] **Visual Clarity**: Both portraits maintain high definition and realistic facial expressions.
- [ ] **Audio Balance**: Volume levels between both speakers are consistent and natural.

Click **Download** to save your final `.mp4` video locally.

---

## Troubleshooting

| Problem | Root Cause | Solution |
| :--- | :--- | :--- |
| **"Unknown speaker in script" error** | Speaker name in the script does not match the configured character names. | Check that names before the colon (e.g., `Maya:`) match the **Name** input fields exactly. |
| **"Character names must be unique"** | Both character slots have the same name. | Assign distinct names to Character 1 and Character 2 (e.g., `Maya` and `David`). |
| **Generation takes too long** | The script contains too many dialogue turns or long paragraphs. | Keep demo scripts concise (3 to 4 turns, under 45 words total) for rapid processing. |
| **Missing voice for a character** | A character was uploaded without selecting a voice. | Ensure each character has a voice selected from the library or an uploaded voice file. |
| **One character is ignored** | Character 2 name or image was left blank. | If creating a two-character video, ensure both name and image are supplied for Character 2. |

---

## Expected Result

A downloaded **multi-character dialogue video (~14 seconds)** featuring:
1. Two distinct, lifelike avatars (**Maya** and **David**) alternating smoothly in a conversational Q&A format.
2. Individual voices matched to each avatar.
3. Precise, synchronized lip movements for each speaker.
4. An engaging, high-retention video asset demonstrating advanced multi-character AI orchestration.

