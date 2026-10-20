# Abhishek Pandey — academic website

A complete static academic website for GitHub Pages, inspired by the typography, layout, and colour palette of https://jindalabhay.github.io/. All HTML/CSS and the mathematical banner were created for this website. It uses Abhishek Pandey’s own portrait and information from his Google Site.

## Publish on GitHub Pages

1. Create or open a repository named **YOUR-USERNAME.github.io**, replacing YOUR-USERNAME with your actual GitHub username. For GitHub Free, use a public repository.
2. Upload the contents of this folder to the repository root, so `index.html` is at the top level. Do not upload the ZIP file itself or put the files inside an extra folder. If updating an existing website, first retain a copy of its source.
3. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, then choose **main** and **/(root)**. Save.
4. Once deployment finishes, visit **https://YOUR-USERNAME.github.io/**. GitHub says publication can take up to 10 minutes.

Official guide: https://docs.github.com/en/pages/quickstart

No package installation, framework, build command, or API key is needed. The fonts and images are included locally. Relative paths also support a project website hosted in a repository subdirectory.

## Update the website

- `index.html`: biography, research interests, position, education, and COMPASS seminar.
- `publications.html`: five preprints, five published/accepted papers, and two works in preparation.
- `teaching.html`: university teaching, NPTEL assistantships, and outreach.
- `style.css`: shared typography, colours, responsive layout, and print styles.
- `assets/portrait.jpg`: the portrait from the original Google Site.
- `assets/geometry.svg`: original decorative Poincaré-disk illustration.
- `assets/fonts/`: self-hosted Crimson Pro and Libre Franklin, with their SIL Open Font License files.
- `.nojekyll`: tells GitHub Pages to serve the static files directly.

The live website is plain HTML: edit a page and commit to update it. Repeated contact/header details appear in all three pages, so update all three when changing them. Update the footer date after later changes.

## Content and editorial decisions

Source pages, retrieved 20 October 2026:
- https://sites.google.com/view/abhishekpandey6797/home
- https://sites.google.com/view/abhishekpandey6797/publications
- https://sites.google.com/view/abhishekpandey6797/teaching

Publication titles, coauthors, statuses, years and destinations follow the live source. The accepted Studia Mathematica paper remains marked accepted. Coauthors are presented as “With …” because the source does not supply complete author ordering. Research descriptions summarize the listed research topics and papers. No CV download or dedicated Talks page was present in the source, so neither is invented. No additional positions or honours have been added.

The Vigyan Jyoti entry omits the source’s ambiguous dates (“15th March to 16th March” alongside “6–8 hours per week”, with no year). The JYU course is included without dates because its visible source does not give any.

## Checks and publication status

Local checks cover HTML structure, page titles, image alternative text, unique IDs, internal navigation, local assets, source publication counts, and self-contained preview links. Fonts and portrait were validated. Browser rendering has not been checked in this environment. External academic destinations were preserved from the source; they have not all been independently tested for availability.

This package has not yet been pushed to a GitHub account or deployed. The separately supplied self-contained HTML is a review copy of the three pages, not a public website.
