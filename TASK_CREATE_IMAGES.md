Please complete all visual materials for my VNPS Level 1 course:

“FLASH PHOTOGRAPHY — From Fundamentals to One-Light Portraits”

Work directly inside the current project directory.

OBJECTIVE

Read the complete course HTML first. Then create appropriate teaching photographs for every chapter from Chapter 01 through Chapter 18, save them in the correct media folder, and display them in the corresponding chapters.

Do not change, shorten, rewrite, or remove the existing teaching content.

==================================================
1. INSPECT THE PROJECT FIRST
==================================================

Before making changes:

1. Locate and read the main HTML file completely.
2. Identify Chapters 01–18 and understand the teaching objective of each chapter.
3. Inspect the existing directory structure, especially:

   media/
   media/photos/
   media/images/
   media/icons/

4. Find all existing image placeholders, image paths, captions, and previously generated photographs.
5. Check whether the following images already exist:

   01.*
   02.*
   03.*
   ...
   18.*

6. Preserve good existing photographs. Do not overwrite them unless:
   - the image is missing,
   - the image is broken,
   - the dimensions are incorrect,
   - or the image does not teach the chapter clearly.

7. Before editing, create a backup copy of the original HTML file.

==================================================
2. IMAGE REQUIREMENTS
==================================================

Create 1–2 realistic teaching photographs for each chapter.

Every photograph must:

- Look like a real professional photograph, not a cartoon or generic illustration.
- Clearly demonstrate the specific flash-photography concept taught in that chapter.
- Be suitable for beginning photography students.
- Use realistic people, cameras, speedlights, triggers, modifiers, studios, rooms, and outdoor environments.
- Show physically believable flash direction, shadows, reflections, exposure, and ambient light.
- Avoid distorted hands, duplicated equipment, malformed cameras, incorrect flash placement, and impossible lighting.
- Avoid logos, trademarks, watermarks, decorative borders, and unrelated text.
- Avoid placing long explanations inside the photograph.
- Use diverse adult subjects when portraits are required.
- Keep the visual style professional and consistent throughout the course.

IMAGE FORMAT

- Landscape orientation
- 16:9 aspect ratio
- Preferred size: 1672 × 941 pixels
- PNG format
- sRGB color space
- Web optimized without visibly reducing image quality

Save all photographs in:

media/photos/

==================================================
3. FILE-NAMING RULE
==================================================

Every filename must begin with the two-digit chapter number:

01.descriptive-filename.png
02.descriptive-filename.png
03.descriptive-filename.png
...
18.descriptive-filename.png

Use lowercase English words separated by hyphens.

Examples:

media/photos/01.ambient-only-vs-balanced-flash.png
media/photos/02.hard-light-vs-soft-light.png
media/photos/03.flash-controls-and-display.png
media/photos/04.ttl-vs-manual-flash.png

If a chapter requires two photographs, use two descriptive filenames:

media/photos/05.flash-power-levels.png
media/photos/05.flash-distance-comparison.png

Do not use names such as:

image1.png
photo-final.png
chapter-photo.png
untitled.png

==================================================
4. VISUAL PLANNING FOR EACH CHAPTER
==================================================

For every chapter:

1. Read the chapter’s complete content.
2. Identify its main learning objective.
3. Decide whether one photograph or a two-image comparison teaches it best.
4. Create the photograph or photographs.
5. Insert them near the relevant teaching text.
6. Write a concise English caption describing what students should observe.
7. Add useful English alt text for accessibility.

Use comparison photographs when appropriate, including:

- Ambient light only vs balanced flash
- Direct flash vs bounced flash
- Hard light vs soft light
- TTL vs Manual flash
- Low flash power vs high flash power
- Flash power levels: 1/4, 1/8, and 1/16
- One-light portrait lighting patterns
- Main light vs fill light
- Flash ratios: 1:1, 1:2, 1:4, and 1:8
- Normal synchronization vs High-Speed Sync
- Bright ambient background vs darkened background
- Subject correctly exposed with ambient light retained
- White background vs gray or dark background
- Master/Transmitter vs Slave/Receiver
- Channel and Group configurations
- Multi/Stroboscopic flash sequence
- Common mistakes vs corrected results

The exact visual for each chapter must be based on the actual HTML content, not only on this example list.

==================================================
5. SPECIAL TECHNICAL ACCURACY
==================================================

The photographs must correctly represent these principles wherever relevant:

A. FLASH POWER

- Full power is written as 1/1.
- Lower manual power levels include 1/2, 1/4, 1/8, 1/16, 1/32, and 1/64.
- Do not confuse individual flash power settings with lighting ratios.

B. TWO-LIGHT RATIOS

When demonstrating two-flash lighting, correctly show ratios such as:

- 1:1
- 1:2
- 1:4
- 1:8

Clearly distinguish the key light from the fill light.

C. AMBIENT AND FLASH BALANCE

Demonstrate that:

- Shutter speed mainly controls recorded ambient light within normal sync limits.
- Aperture, ISO, flash power, and flash-to-subject distance affect flash exposure.
- The subject may be illuminated by flash while ambient light remains visible.
- Avoid showing a completely black environment unless the lesson specifically requires it.

D. HIGH-SPEED SYNC

When demonstrating HSS:

- Show an outdoor portrait in bright daylight.
- Use a shutter speed faster than the camera’s normal sync speed.
- Keep the subject correctly exposed with flash.
- Darken the background intentionally.
- If settings are shown in the caption, use realistic values such as:

  1/2000 sec · f/2.8 · ISO 100 · HSS

E. WHITE BACKGROUND

When demonstrating a clean white background:

- Light the background separately when appropriate.
- Keep the background brighter than the subject exposure.
- Avoid excessive light spill and loss of edge detail.
- Show the subject clearly separated from the white background.

F. TRIGGERS, CHANNELS, AND GROUPS

Accurately demonstrate:

- The transmitter mounted on the camera.
- Remote flashes functioning as receivers/slaves.
- Matching channel numbers between transmitter and flashes.
- Groups A, B, and C controlling separate flash units.
- Master/Commander and Slave/Receiver relationships.

G. FLASH MODES

Correctly demonstrate:

- TTL mode
- Manual mode
- Multi/Stroboscopic mode
- HSS mode
- Optical or radio wireless operation when covered

==================================================
6. HTML INTEGRATION
==================================================

For every created image:

1. Insert it into the correct chapter.
2. Use a relative path such as:

   media/photos/04.ttl-vs-manual-flash.png

3. Preserve the existing page design:
   - typography,
   - colors,
   - chapter numbering,
   - cards,
   - navigation,
   - spacing,
   - buttons,
   - header,
   - footer,
   - responsive layout.

4. Do not redesign the course.
5. Do not remove existing content.
6. Do not replace real photographs with plain placeholder graphics.
7. Make the image container responsive.
8. Preserve a 16:9 space before the image loads to prevent layout shifting.
9. Use object-fit appropriately without cropping important teaching content.
10. Make each image clickable so students can open the full-resolution version in a new browser tab.

Use semantic HTML similar to:

<figure class="chapter-photo">
  <a href="media/photos/04.ttl-vs-manual-flash.png"
     target="_blank"
     rel="noopener">
    <img
      src="media/photos/04.ttl-vs-manual-flash.png"
      alt="Comparison of TTL and manual flash exposure in a portrait setup"
      width="1672"
      height="941"
      loading="lazy">
  </a>
  <figcaption>
    TTL automatically adjusts flash output, while Manual mode provides fixed and repeatable power.
  </figcaption>
</figure>

Adapt the class names to the existing HTML design when necessary.

==================================================
7. EXERCISES AND ANSWERS
==================================================

Inspect all exercises in the course.

For each exercise:

- Preserve the original question.
- Make sure the student task is clearly visible.
- Add or preserve a collapsible “Suggested Answer” or “Instructor Answer.”
- Include exposure reasoning, flash settings, and troubleshooting guidance where appropriate.
- If a photograph is needed to explain the exercise, create one using the chapter-number filename convention.
- Do not display the answer automatically if the current design uses an answer-reveal button.

All exercise and answer text must remain in English.

==================================================
8. QUALITY CONTROL
==================================================

After completing the images and HTML:

1. Confirm that Chapters 01–18 all contain at least one relevant photograph.
2. Confirm that all image files exist.
3. Confirm that every image uses a correct relative path.
4. Confirm that there are no broken images.
5. Confirm that filenames start with 01 through 18.
6. Confirm that all generated images are 1672 × 941 pixels or another exact 16:9 size approved by the existing design.
7. Confirm that captions and alt text are written in English.
8. Confirm that the page works on desktop, tablet, and mobile widths.
9. Confirm that clicking a photograph opens the full image.
10. Check the browser console for missing-file or HTML errors.
11. Do not leave temporary files, unused placeholders, or duplicate images in the final project.
12. Do not modify unrelated project files.

==================================================
9. FINAL REPORT
==================================================

When the work is complete, provide a chapter-by-chapter report in this format:

Chapter 01
- Teaching concept:
- Image filename:
- Image dimensions:
- HTML insertion location:
- Status:

Chapter 02
- Teaching concept:
- Image filename:
- Image dimensions:
- HTML insertion location:
- Status:

Continue through Chapter 18.

Also report:

- Main HTML filename
- Backup HTML filename
- Total number of images created
- Total number of existing images preserved
- Any images that could not be generated
- Any remaining placeholders
- Confirmation that all image paths were tested
- Confirmation that the original written course content was preserved

IMPORTANT

Do not merely create empty placeholders.

If image generation is available, create the actual photographs and integrate them into the HTML.

If image generation is not available:

1. Do not create fake blank PNG files.
2. Preserve properly sized 16:9 spaces in the HTML.
3. Create a production-ready image prompt for every missing photograph.
4. Save all prompts in:

   media/photos/IMAGE_GENERATION_PROMPTS.md

5. Clearly report which photographs still need to be generated.
6. Do not claim that an image was created unless the actual PNG file exists and has been verified.