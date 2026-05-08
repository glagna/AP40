# BIOL 40C Backup Site — GitHub Pages

A single-page backup of Week 4 (current) and Week 5 (Midterm) for BIOL 40C while Canvas is offline.

## Folder structure to push to GitHub

```
your-repo/
├── index.html           ← already built (this is the page students see)
├── README.md            ← this file (optional to push)
├── slides/              ← PDFs of all lecture slides
│   ├── BIOL40C_Class1_Slides.pdf
│   ├── BIOL40C_Class2_Slides.pdf
│   ├── ...
│   ├── BIOL40C_Class10_Slides.pdf
│   └── BIOL40C_Class11_Slides.pdf   (post Sun May 10)
└── worksheets/          ← PDFs students download
    ├── BIOL40C-RCS-4_Fluid_Electrolyte_AcidBase.pdf
    ├── BIOL40C_Week4_StudentLectureOutline.pdf
    ├── BIOL40C_Practice_Midterm.pdf       (post Sun May 10)
    └── BIOL40C_Cumulative_Study_Sheet.pdf (post Sun May 10)
```

`index.html` uses **relative links** for files in `slides/` and `worksheets/`, plus **absolute links** for the AA2 (Reyna), AA3 (Oscar), and AA1 (Pearson IP2) activities. Keep the folder layout above and every link in the page resolves correctly once the repo is on GitHub Pages.

## Status of each link

### Already wired up (no action needed beyond your existing files)

- **Email:** `lagnagiorgio@fhda.edu` — 3 places in `index.html`.
- **AA1 Pearson IP2 (Urine Concentration & Volume):** absolute URL to the Pearson activity. Already working.
- **AA2 Reyna's Case:** Google Doc force-copy URL — `https://docs.google.com/document/d/16sMaBphQIMQBKWJ3BxGOX6XJbN7KbpFNUCE5gLBVGIo/copy`
- **AA3 Oscar's Case:** Google Doc force-copy URL — `https://docs.google.com/document/d/1klLRfSZ-NBfG7636OyJepKIaYRMJl-uBB54HOcFUWZE/copy`

> **Important — Google Doc sharing settings.** The `/copy` URL only works if each Doc is set to "Anyone with the link → Viewer." Open each Doc, click *Share* → *General access* → set to "Anyone with the link." If they are restricted, students will be locked out. Verify before pushing.

### Files you still need to drop into the repo

- `slides/BIOL40C_Class1_Slides.pdf` through `BIOL40C_Class10_Slides.pdf` — you said these PDFs are ready. Drop them into `slides/`.
- `slides/BIOL40C_Class11_Slides.pdf` — post by Sunday May 10 (the practice-midterm session deck).
- `worksheets/BIOL40C-RCS-4_Fluid_Electrolyte_AcidBase.pdf` — the actual Week 4 RCS quiz PDF (the file in your `RCS/` folder is RCS 2, not 4).
- `worksheets/BIOL40C_Week4_StudentLectureOutline.pdf` — your Week 4 SLO. Optional. If you don't have one, edit `index.html` and remove the line in the "Week 4 Class Materials" section that links to it.
- `worksheets/BIOL40C_Practice_Midterm.pdf` — post by Sunday May 10.
- `worksheets/BIOL40C_Cumulative_Study_Sheet.pdf` — post by Sunday May 10.

If any worksheet PDF is missing on launch day, students will hit a 404. Either drop in the file, replace the link with a Google Doc URL (same `/copy` pattern), or remove the link from `index.html`.

## Things you may want to tweak

- **Office hours:** the page says "Tuesday afternoons (see your syllabus)" because I do not have your specific time/room. Edit the Contact section if you want to be specific.
- **Late penalty during outage:** I wrote "none" with a soft trust note. Adjust if you want stricter language.
- **Last-updated date:** Search for the date string `Thursday, May 7, 2026` and bump it whenever you push changes.

## Push and share

1. Drop `index.html`, the `slides/` folder, and the `worksheets/` folder into the root of your existing GitHub Pages repo. Commit. Push.
2. Verify the live URL loads in a browser. Click each link in the in-page nav and the deadlines table to confirm nothing 404s.
3. Email students the URL. Subject suggestion: *"BIOL 40C: backup site for Weeks 4 & 5 while Canvas is offline."*

## When Canvas comes back

This page is read-only for students. When Canvas is restored:

1. Re-collect their email submissions and upload to the corresponding Canvas assignment so the gradebook stays canonical.
2. Either keep the GitHub site as a permanent backup or take it down. If you keep it, swap the red banner at the top of `index.html` for a neutral one (search for "Canvas is offline").
