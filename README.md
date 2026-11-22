# আসমাউল হুসনা — আল্লাহর ৯৯টি নাম

Neumorphic (soft-shadow, orange) single-page web app for Allah's 99 Beautiful Names — Asmaul Husna.

## What it is

A single self-contained `index.html` (no build step, no backend). Open it in any browser, or host it with GitHub Pages.

- 99 names with Arabic, transliteration, Bengali + English meanings and a one-line Bengali explanation
- Search (Arabic / transliteration / Bengali / English) and category filter pills
- Today's name (rotates daily)
- Favourites and "learned" marks with a memorisation progress bar — saved in the browser (localStorage)
- Detail sheet for each name with prev/next
- Tasbih counter per name with 33 / 99 / 100 targets and a progress ring

## Design

Based on the reference neumorphic shopping-app UI: light grey-blue canvas, soft dual shadows, orange gradient bubble/pills/buttons, raised centre bottom-nav button.

## Source note

The well-known list of the 99 names follows the enumeration in Jami' at-Tirmidhi. The hadith on the number ninety-nine is authentic (Sahih al-Bukhari 2736); scholars note the specific enumeration varies slightly between narrations.

## Run locally

Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```
