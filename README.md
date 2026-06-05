# Food Handler Training (FHT)

A web-based food safety certification app for temporary food event operators at USAG Humphreys.

**Live:** <https://kimmybadger.github.io/FHT/>

-----

## Overview

- **Standard:** TB MED 530 / FDA Food Code
- **Organization:** DHA Public Health / 65th Medical Brigade
- **Language:** English + Korean (bilingual)
- **Format:** Single-page app — no install, no build required

-----

## How It Works

1. Complete all 6 learning modules
1. Pass the quiz (25 questions, 80% to pass)
1. Enter your name and download the certificate (PDF)
1. Bring the certificate to your food event

Certificate is valid for **1 year** from date of issue.

-----

## Files

|File            |Description                                      |
|----------------|-------------------------------------------------|
|`index.html`    |Full app — UI, logic, base64 images              |
|`lessons.json`  |6 modules, 26 sections of content                |
|`questions.json`|157-question bank (25 randomly selected per quiz)|

-----

## Modules

|#|Module                 |Topics                                          |
|-|-----------------------|------------------------------------------------|
|1|🦠 Foodborne Illness    |Big 6, risk factors, contamination types        |
|2|🙌 Personal Hygiene     |Handwashing, health rules, allergens            |
|3|🌡️ Time & Temperature   |TCS foods, danger zone, cooking temps           |
|4|⚠️ Cross-Contamination  |Prevention, storage order, transport            |
|5|🧼 Cleaning & Sanitizing|Wash-rinse-sanitize, pests, chemicals           |
|6|🎪 Event Operations     |TCS vs Non-TCS, equipment, hot holding, labeling|

-----

## Features

- **Bilingual** — all content and quiz questions in English and Korean
- **TTS narration** — Web Speech API reads English content aloud; Next button unlocks after narration
- **Quiz** — Fisher-Yates shuffle, 25 random questions, instant feedback with explanations
- **Certificate** — matches physical DHA/65th Med Bde certificate; PDF download via html2canvas + jsPDF
- **Engineer mode** — unlock all locks (for testing)

-----

## Deployment

Hosted on GitHub Pages. To update, replace files in the repository root.

No dependencies to install. Libraries are loaded via CDN:

- [html2canvas](https://html2canvas.hertzen.com/)
- [jsPDF](https://parall.ax/products/jspdf/)

-----

## Contact

**Evan Schmidt** — Sanitarian, EH Program Manager  
DHA Public Health / 65th Med Bde, Bldg #6370  
DSN: 315-737-5703
