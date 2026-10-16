# Quick Check (Quiz 2)

Everyday Workplace Communication · Module 1 · Segment 5: Reading Signs — The Wrong Room · **Stage 5.8**, in the Swift AI Academy frame.

The whole quiz is one plain HTML page (`index.html`). The pictures are inside the file, and no framework or build step is needed. `Module1_Quiz2_Stage5.8_Quick_Check.html` is the same file, kept for downloading. It opens with a double-click.
It is generated from `module1-segment1/` with `node scripts/plain-quiz58.mjs <out.html>`, from `scripts/quiz58-plain.template.html`. Do not edit it by hand: change the template and generate it again.

## Publish on GitHub + Vercel

1. In Vercel choose **Add New → Project** and import this repository.
2. Set **Framework Preset** to **Other**. Leave the build command and output directory empty.
3. Choose **Deploy**. Vercel gives you an `https://….vercel.app` link.

GitHub Pages also works: Settings → Pages → deploy from the `main` branch, root folder.

## Content status

- Eight questions, one per screen, with progress dots.
- Feedback comes straight away. A right answer shows a tick and a one-line reason; a wrong answer shows an amber card, and the learner tries again. There is no negative marking.
- It is an ungraded self-check, not the Module Assessment.
- A countdown in the top bar shows the 10 minutes left; there is no Pause button. When the time runs out, the quiz starts again from the first question.
- The layout is compact, so each question fits on a laptop screen and a phone needs little or no scrolling.
- Each attempt is recorded in the browser as `5.8.quiz-log` (tries per question). The quiz still works where browser storage is blocked.
- Meanings dragged into a box can always be dragged back, or tapped to send them back.
- There is no audio in this quiz (the brief gives none).
- The sign pictures, the hand-painted room boards and the corridor are **interim art** drawn for this build (`public/media/images/M1_S05_08_IMG_*.svg` in the source). Replace them there with the illustrator's art and generate the file again.
- Questions 5–8 were added from what Segment 5 teaches; their wording is a draft for review.
