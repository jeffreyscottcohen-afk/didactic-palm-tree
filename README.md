# Matter Launch Case Files

An interactive, web-based version of the **Matter Launch Case Files** project: a 5th grade Properties of Matter research project (NGSS 5-PS1-1 to 5-PS1-4). Students work in trios as "material scientists," research one real-world case, and decide whether the matter became a new substance.

The whole site is one file, `index.html`. It needs no server, no accounts, and no build step.

## What students get

Everything from the Student Packet, laid out day by day:

| Day | Pages |
| --- | --- |
| Start | Your Mission, Big Question, Project Map |
| 1 | Two Kinds of Change (reading, vocabulary, 3 check questions; Q2 self-checks), Our Trio (roles + four rules), Choose Your Case (rank top 3 of 13 cases) |
| 2 | **Case Brief** for their case (guiding questions, copyable search words, approved sites, common traps), Organizer 1 + property chart, Source Log + trust checklist |
| 3 | Organizer 2 (change story), Organizer 3 (**drawing pad** for before/after particle models), Organizer 4 (mass) |
| 4 | CER with tap-to-insert sentence starters and a live self-check, Final Product Planner + slide plan |
| 5 | Gallery Walk (Glow and Grow), Reflection, rubric self-score |
| 6–8 | Be the Material Scientist: plan, product sketch pad, design CER (optional) |
| Every day | Project Log, **My Case File** (all work in one view) |

- Work **autosaves in the browser on that device**. The left menu shows a dot for each page (empty, partly done, done) and an overall progress bar.
- **My Case File** shows everything a student wrote, including their drawings. Students can **Copy all my work** (paste into a Google Doc or LMS), **Print**, or **Save a backup file** and **Load** it on another computer (handy on shared Chromebooks).
- The teacher answer key is **not** included anywhere in the site, since students can view page source. Day 1, Q2 does self-check (P/C), which the sub plan's key already treats as a low-stakes reading check.

## Putting it online

Any static host works. With GitHub Pages: repo **Settings → Pages → Deploy from a branch**, pick the branch and `/ (root)`. Share the resulting URL with students. You can also open `index.html` directly from a USB drive or shared folder.

## Notes for the teacher

- **Case menu.** The sub plan says 12 cases; the packet's menu showed 6 (including Glow Sticks, which isn't in the answer key). The site offers all 13: the 12 from the answer key plus Glow Sticks. Glow Sticks key: **chemical**. Snapping breaks an inner glass vial so two liquids mix and react, releasing energy as light (chemiluminescence). It can't be recharged; it glows longer but dimmer in the cold because the reaction slows. The stick is sealed, so mass stays the same.
- **Research links** go to site home pages (Britannica School, Britannica Kids, National Geographic Kids, Exploratorium). Students copy search words from the Case Brief into the site's search box. Edit the `sites` list in `index.html` to match your approved list.
- **Saving is per device and per browser.** If students switch computers or clear browser data, they need their backup file or their copied text. Remind them on Day 1 to use "Save a backup file" at the end of class.
- **Roles** say "devices" instead of "MacBooks" so they fit Chromebooks or library books.
