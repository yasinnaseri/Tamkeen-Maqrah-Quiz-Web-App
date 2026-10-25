# Tamkeen Maqra’ah

Public community website for Tamkeen Youth: weekly quizzes, group standings, and teacher-approved funny answers.

## Hosting

GitHub Pages serves the standalone `index.html` from the root of `main`. The interface fetches live data and submits quizzes to the existing Tamkeen server. Teacher sign-in opens that server for private quiz creation, grading and Gemini drafting.

The API key and teacher access key are stored only on the server. This publication contains no credentials, database export, or unpublished quiz content.

## Updating the site

The editable source is maintained in the Tamkeen app workspace. Run `pnpm build:pages`, then replace `index.html` and the font license files with the files from `dist-pages`. Quiz publication, scores and approved funny answers update from the server and do not need a new Pages build.

Figtree and Barlow Condensed are distributed under the included SIL Open Font Licenses.
