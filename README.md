# ResumeLens — Smart Resume Analyzer & Job Matcher

Responsive React + TypeScript project with resume text import, skill detection, resume readiness checks, ranked sample job matches, saved roles, custom job comparison and text report export.

## Run locally

Requires Node.js 22.13 or newer.

Extract the ZIP, open a terminal in the resume-lens folder (the folder containing package.json), then run:

```bash
npm install
npm run dev
```

Open the local URL printed in the terminal.

## Production build

```bash
npm run build
npm run preview
```

The dist folder can be deployed to static hosting such as Netlify.

## Usage and limitations

Click Analyze resume to paste your resume or import a TXT file smaller than 1 MB. For PDF or Word documents, copy their text into the editor. Job matches are illustrative listings, not live vacancies. All scores use local keyword matching and content checks; an external AI model is not connected. No API key is needed. Resume text stays in the browser. Analysis and saved roles reset when the page reloads. External Google Fonts are used with system-font fallbacks.

## Project files

src/App.tsx — interface, resume checks, sample jobs and matching logic.
src/styles.css — responsive styling.
src/main.tsx — React entry point.
