# Quick Check (Quiz 2)

Everyday Workplace Communication · Module 1 · Segment 5: Reading Signs — The Wrong Room · **Stage 5.8**, in the Swift AI Academy frame.

A static website: plain HTML, JavaScript, CSS, fonts, images and audio. No server and no build step are needed to host it.
Built from `module1-segment1/` with `node scripts/build-site.mjs 5.8`. Do not edit these files by hand; change the source and rebuild.

## Publish on GitHub + Vercel

1. Put this folder in a GitHub repository (it can be the whole repository, or one folder in it) and push.
2. In Vercel choose **Add New → Project** and import the repository.
3. If this folder is not the repository root, set **Root Directory** to this folder.
4. Set **Framework Preset** to **Other**. Leave the build command and output directory empty.
5. Choose **Deploy**. Vercel gives you an `https://….vercel.app` link.

GitHub Pages also works: Settings → Pages → deploy from the branch and folder that hold `index.html`.

## Try it on your own computer

```bash
npx serve .
```

Then open the address it prints. Double-clicking `index.html` does not work, because browsers block these scripts on `file://` pages.

## Content status

How it works: eight questions, one per screen, with progress dots; immediate feedback (right: tick and chime; wrong: gentle shake and an amber card, try again); no negative marking; ungraded self-check, not the Module Assessment. The whole quiz has a 10-minute limit; when it lapses, or when the learner resumes after a pause, the quiz starts again from the first question. Each attempt is recorded in the browser as `5.8.quiz-log` (answers, tries, right first time). Words dragged into a blank or a box can always be dragged back, or tapped to send them back.

There is no audio in this quiz (the brief gives none). The sign pictures, the hand-painted room boards and the corridor are **interim art** drawn for this build (`media/images/M1_S05_08_IMG_*.svg`): replace a file with the illustrator's art of the same name and push again. Questions 5–8 were added from what Segment 5 teaches; their wording is a draft for review. **Single file:** `Module1_Quiz2_Stage5.8_Quick_Check.html` is the same quiz as one plain HTML file (made with `node scripts/plain-quiz58.mjs`). It opens with a double-click and needs nothing else.
