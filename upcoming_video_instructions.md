# MoneyMuse — Upcoming Video Production Instructions

## How to Use This File

1. Pick a topic from `Ideas.html` or `moneymuse_content_ideas.html`
2. Use this instruction file to generate a complete video production file
3. Save the output as `product/<Video Title>.html` following the naming pattern
4. Each generated file will contain 8 scenes, each with 1 voiceover + 3 image prompts + 3 AI video prompts

---

## Topic Source

Choose any topic from the following files in the project root:

- **`Ideas.html`** — 20 YouTube video topic ideas (Money Psychology, Personal Finance, Financial Traps, Investing & Wealth Building)
- **`moneymuse_content_ideas.html`** — 30 content ideas for posts and reels (Budgeting & Saving, Investing & Wealth Building, Debt & Credit, Money Mindset & Psychology, Income & Financial Freedom, Engagement & Viral Formats)
- **`MoneyMuse - Master Production File.html`** — Previously completed videos (do not reuse these topics)

---

## Video Specifications

| Property | Value |
|----------|-------|
| **Scenes** | 8 |
| **Per Scene** | 1 voiceover + 3 image prompts + 3 AI video prompts |
| **Total images** | 24 per video |
| **Total video prompts** | 24 per video |
| **Est. video length** | 3-4 minutes |
| **Generation time per image/video** | ~8 seconds |

---

## Scene Output Format (Per Scene, Repeat for All 8 Scenes)

### SCENE N

**Description:** Short one-line description of what happens visually

**Voiceover:**
The narration script for this scene. Write in conversational, educational tone. Keep each voiceover segment roughly 15-30 seconds of spoken content.

**Image Prompts (3 per scene):**
Each image prompt must be unique — different angles, compositions, or visual metaphors that all represent the same voiceover content. Vary the focus across prompts:

- Prompt A: Wide / establishing shot of the scene
- Prompt B: Close-up / detail-focused version
- Prompt C: Alternative visual metaphor or different character perspective

**AI Video Prompts (3 per scene):**
Each video prompt describes how to animate the corresponding image. These prompts should be compatible with Grok image-to-video, Runway, Kling, Pika, or similar AI video generators.

- Video Prompt A: Matches Image Prompt A — describe the animation, motion, and camera movement
- Video Prompt B: Matches Image Prompt B — describe the animation, motion, and camera movement
- Video Prompt C: Matches Image Prompt C — describe the animation, motion, and camera movement

---

## Visual Style (Use for All Upcoming Videos)

### Primary Style: Whiteboard Sketching

- **Style:** Whiteboard sketching — hand-drawn marker illustration on clean whiteboard background
- **Background:** Clean white whiteboard background with occasional marker scribble, smudge, or eraser dust effects
- **Character:** Consistent round-faced cartoon character drawn in sketch style across all scenes, black marker outlines with green sweater colored in marker
- **Drawing style:** Thick black marker outlines with slight hand-drawn wobble (not perfect vector), marker fill/stipple shading, hand-drawn look throughout
- **Color accents (marker only):**
  - Black marker: main outlines and primary drawing
  - Green marker (#16c79a): positive concepts, money, growth
  - Blue marker (#4a7cff): explanations, labels, calm concepts
  - Red marker (#e74c3c): warnings, emphasis, circled numbers, X marks
- **Common finance objects:** Hand-drawn piggy bank, coins, wallet, bank vault, bar charts, line graphs, house, money stacks, laptop, calendar, smartphone, treasure chest, clock — all drawn in doodle/sketch style
- **Visual effects:** Hand-drawn arrows, circled emphasis, marker underline effects, doodle sparkle lines, scribble fills, crosshatch shading
- **Composition:** Simple, uncluttered, one main focal point per image, whiteboard space around elements

### Tone
- Educational but engaging
- Friendly and relatable
- Hand-crafted sketch feel

---

## AI Video Prompt Guidelines

Video prompts should instruct how to animate the still image. Follow this structure in each prompt:

1. **Motion type:** Gentle camera pan, zoom in/out, slow push, parallax, subtle object animation
2. **What moves:** Character gestures (pointing, counting, walking), objects floating/growing, charts filling, coins stacking, money flowing
3. **Duration style:** Slow and smooth for explanation, faster for reveals
4. **Loop behavior:** Seamless loop or one-time motion

### Video Prompt Examples:

```
Pan: slow left-to-right reveal across the whiteboard, hand-drawn chart bars rise one by one as if being drawn in real-time with marker scribble effect, coin stacks stack upward with hand-drawn wobble, character's marker hand draws each element, 5-second smooth motion, seamless loop
```

```
Zoom: slow zoom into character's hand-drawn face with marker outline wobble, small doodle sparkle particles float around the number, subtle hand-drawn sketch animation effect (lines appear as if freshly drawn), 4-second motion, one-time animation with a 1-second hold at end
```

```
Push: gentle forward push past character into the whiteboard scene, marker lines draw the financial timeline growing from left with scribble fill effect, coin icons drop into a vault one by one with slight bounce like fresh marker strokes, 6-second motion with bounce easing
```

---

## Complete HTML Output Template

Each generated video must be saved as a self-contained HTML file in the `product/` directory following this structure:

### HTML Structure:

```
<!DOCTYPE html>
<html>
<head>
  <title>Video Title | MoneyMuse</title>
  <style>[copy CSS from existing product HTML files]</style>
</head>
<body>
  <div class="container">
    <h1>Video Title</h1>
    <div class="subtitle">Visual style description</div>

    <!-- Metadata -->
    <div class="meta-row">
      <span>Category: ...</span>
      <span>Est. Length: 3-4 min</span>
      <span>Style: Whiteboard Sketching</span>
    </div>

    <!-- 8 Scenes -->
    <div class="scene">
      SCENE 01 content (voiceover + 3 images + 3 video prompts)
    </div>
    ...
    <div class="scene">
      SCENE 08 content
    </div>

    <!-- Thumbnail Section -->
    <div class="thumbnail-box">
      Thumbnail idea + text + AI image prompt
    </div>

    <!-- SEO Section -->
    <div class="seo-grid">
      Title options, description, tags, keywords, hashtags
    </div>

    <!-- AI Voiceover Notes -->
    <div class="vonote">
      Tone, pace, emphasis, duration
    </div>
  </div>
</body>
</html>
```

---

## Production Workflow

1. **Pick a topic** from `Ideas.html` or `moneymuse_content_ideas.html`
2. **Write an 800-1000 word script** in conversational voiceover style (8 scenes, ~100-150 words per scene)
3. **Split script into 8 scenes** — each scene is one complete thought/paragraph
4. **For each scene,** write:
   - The voiceover text
   - 3 distinct AI image prompts (different visual treatments of the same concept)
   - 3 matching AI video prompts (animation instructions for each image)
5. **Generate thumbnails + SEO metadata** following the existing format
6. **Save the file** as `product/<Topic Title>.html`
7. **Generate assets:** Feed whiteboard image prompts into Midjourney / DALL-E / Leonardo AI / Stable Diffusion (all support whiteboard sketching style)
8. **Animate:** Feed generated whiteboard images into Grok image-to-video / Runway / Pika for video (whiteboard sketches animate well with hand-drawn wobble effect)
9. **Edit:** Assemble clips + voiceover + text + music in CapCut

---

## Scene Script Rules

- **Total script:** 800-1000 words across 8 scenes
- **Per scene:** ~100-150 words of voiceover
- **Tone:** Conversational, storytelling, curiosity-driven
- **Structure per scene:** Hook or set-up at start, insight or reveal at end
- **Avoid:** Scene directions, camera instructions, transition notes in voiceover
- **Include:** Relatable examples, psychological insights, simple comparisons

---

## Image Prompt Rules

- **3 per scene** — always exactly 3
- Each prompt must be visually distinct from the other two
- Maintain consistent character and style across ALL 24 prompts
- Include hand-drawn marker text labels, numbers, and scribbled annotations as part of the whiteboard illustration (circled emphasis, marker underlines, doodle arrows with labels)
- Do NOT generate the image — only write the prompt

---

## Video Prompt Rules

- **3 per scene** — one matching each image prompt
- Each video prompt must describe motion/animation for its corresponding image
- Vary the motion type across the 3 prompts (pan, zoom, push, tilt, etc.)
- Specify duration (3-8 seconds)
- Include easing style (smooth, bounce, ease-in-out)
- Compatible with: Grok image-to-video, Runway Gen, Pika, Kling, or Stable Video Diffusion

---

## Example Reference

See existing files in `product/` for the HTML format and CSS styling:

- `product/The $5 Lie — Why Small Spending Habits Keep You Stuck.html` (whiteboard style reference)
- `product/The Dopamine Trap of On Sale.html` (upcoming format — 3 images + 3 videos per scene, whiteboard style)

Note: Earlier videos used 1 image prompt per scene. All upcoming videos use 3 image prompts + 3 video prompts per scene.
