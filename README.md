# Food Quest! — Year 5 English (Version 5)

A colourful, interactive learning website for **Unit 5: Food & Health — Creating My Healthy Recipe**, based on the user's Task 2 storyboard.

## What's included

- **Entry popup:** pupil nickname sign-up, food buddy avatar, and returning pupil selector. The popup appears *before* access to the menu on every new visit or reload.
- **Home:** two simple food-entry lists, Healthy Foods and Unhealthy Foods. Pupils add and remove examples; no games are on the homepage.
- **Learn (new):** an **original, 37-second animated Food & Health concept video** teaching everyday choices, sometimes treats and the Malaysian Healthy Plate. It **pauses for two answerable questions** with feedback. Includes a written transcript, replay, and optional **browser-generated read-aloud**. The MP4 itself has **no audio track**; read-aloud depends on the pupil's browser and is off by default.
- **Activities:** a 10-food Healthy Plate sorting challenge and a **pupil-led Recipe Studio** with an interactive Chef's Word Bank (food ideas, action verbs, useful phrases, sequence words). Pupils choose words and compose their own title, ingredients, and four instructions; there are no completed sample answers. Includes a self-checklist, live preview, and draft/completion saving.
- **Peer Review (new):** after completing a recipe, a partner can use the **same device** to check its clarity and leave one encouraging comment and one improvement suggestion. Feedback is shown to the writer, who can revise and resave the recipe. This is a classroom pass-the-device workflow, **not** online peer sharing.
- **Exit Ticket (new):** a final two-question food/sequence-word knowledge check plus two pupil-written reflections. Saves the score and personal improvement goal locally.
- **Games:** new **Healthy Market Mission** is the main game: pupils visit **three market stalls**, choose **12 foods**, and sort them between **Everyday choices** and **Sometimes treats**. Feedback explains choices; scores and streaks are saved per pupil. The original challenging 10-question **Food Hero Arena** remains available as an extra game, with its timer, three lives and streak bonuses.
- **Progress:** per-pupil activity scores, food-list count, recipe status, **best market score**, **latest exit-ticket score**, and original Arena personal best.
- **Teacher Preview:** a password prompt, class dashboard, individual pupil work viewer (including **market attempts, peer comments and exit-ticket reflections**), and updated CSV export.
- **Meet the Creator:** dedicated page featuring the supplied cartoon portrait, **Rosario Ivan anak Ambrose**, class **BI2824**, and a creator credit in the footer and page metadata.
- **Mr. Wan Thuthri:** a friendly floating, offline food-and-English chat helper, with an original cartoon mascot, suggested questions, food-group classification for 60+ named foods and variants, and prepared answers about healthy meals, the Malaysian Healthy Plate, writing recipes, the market game, peer reviews, video and exit ticket. Recipe advice provides guiding clues rather than finished sample instructions. The conversation can be cleared and is not saved.

## Open the website on your computer

Extract the **entire ZIP** and double-click `index.html`. Keep the folder structure as shown:

```
index.html
styles.css
app.js
chat-helper.js
v5.css
v5.js
assets/
  rosario-ivan.png
  mr-wan-thuthri.svg
  food-and-health.mp4
  food-lesson-poster.svg
  lesson-everyday.svg
  lesson-treats.svg
  lesson-plate.svg
README.md
```

Use Chrome or another current browser for the best experience.

## Upload to GitHub Pages

1. Create a GitHub repository (for example, `food-quest-year5`).
2. Upload `index.html`, `styles.css`, `app.js`, `chat-helper.js`, **`v5.css`, `v5.js`**, and the **entire `assets/` folder** into the repository root. Keep the MP4, SVGs and images inside `assets/`.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch **main**, folder **/(root)**, then **Save**.
6. Visit the published Pages URL once deployment finishes.

No build step or JavaScript installation is needed.

## Important privacy and security limitations

This is still a **classroom demonstration**, not a production account platform.

- Pupil records are saved in this browser's `localStorage` only. They **do not synchronise across devices**.
- The password gate is implemented in frontend JavaScript. Although the password is checked against a hash instead of being written in plaintext, **this does not securely restrict access**: someone can inspect or bypass client-side code.
- Do **not** use real pupil names, photographs, addresses, passwords, or sensitive information.
- Pupil accounts are nicknames without authentication. Data can be altered or lost on the device.
- Peer review works **only when pupils use the same browser and device**, for example handing the tablet to a partner; it does not automatically collect feedback across separate pupil devices.
- The teacher dashboard sees only records saved by that browser; it does not give a genuine class-wide overview when pupils use different devices. A protected school-approved database would be required for that.
- Before classroom deployment, use school-approved authentication, a protected server/database, authorised teacher access, and suitable privacy/retention policies.
- Never put database service-role keys, private API tokens, or real classroom credentials inside static website files.
- **Mr. Wan Thuthri is not a live generative AI.** This is a prepared offline question-answer chatbot; it does not make external API requests, save messages, or answer every imaginable question. A genuine AI model would need a separate, school-approved secure backend.
- The Creator picture and full creator name are **publicly visible** when you publish the website. Only publish these if you are comfortable sharing them publicly.

## Suggested next steps for the assignment

- Pilot the site with a few Year 5 pupils and ask for feedback about the market difficulty, lesson clarity, and recipe writing supports.
- Add a **separate evidence-based design report** citing and applying Mayer's Cognitive Theory of Multimedia Learning (for example, coherence, signaling, segmentation, contiguity and multimedia). Explain strengths, limitations, and proposed improvements as required by the rubric.
- Document a clear **synchronous classroom** mode (pairs discussing market choices, recipe peer review) and **asynchronous** mode (individual video, plate matching, recipe writing and exit ticket). The present peer review is a shared-device prototype.
- Keep source/asset credits and Creative Commons licence information accurate. The video slide art is original; the portrait was supplied by the creator. Do not claim that arbitrary third-party media have a Creative Commons licence.
- For real deployment with genuine pupil records, use properly secured teacher login and a school-approved backend before inviting pupils to enter identifying information.

The website uses original HTML, CSS and JavaScript. Food illustrations use standard system emoji; the animated video graphics and Mr. Wan Thuthri's SVG mascot are original artwork, and the creator portrait was supplied by the creator. External Google Fonts have local fallbacks. Nutrition teaching examples draw on the Ministry of Health Malaysia's Healthy Plate and the World Health Organization's Healthy Diet guidance; links are provided on the Creator page.
