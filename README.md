# Saifullah's portfolio — GitHub Pages

Ready-to-upload static website. No npm, build command, backend, or API keys needed.
The existing Sites website is separate and remains unchanged.

## Publish for the first time

1. Sign in at https://github.com and create a PUBLIC repository named exactly:
   msaifullah-tahir.github.io
   If that repository already exists, do not overwrite it blindly; back it up first.
2. Extract the ZIP on your computer.
3. Upload the CONTENTS of the github-portfolio folder into the repository root.
   index.html must appear directly in the repository, not inside another folder.
   Upload all files and the assets folder. Do not upload the ZIP itself.
4. Click Commit changes.
5. Open repository Settings > Pages.
6. Under Build and deployment, select Deploy from a branch.
7. Choose main and / (root), then Save.
8. Wait for the Pages deployment to finish. GitHub shows the live link in Settings > Pages:
   https://msaifullah-tahir.github.io/

Official guide: https://docs.github.com/en/pages/quickstart

## Replace your profile photo

Upload your photo as assets/images/profile.jpg.
Or edit the photo path in content.js if you use another filename or format.
The placeholder disappears when the image loads.

## Add your resume

Upload the PDF as assets/cv/resume.pdf.
In content.js change:
  "resume": ""
to:
  "resume": "assets/cv/resume.pdf"
The Request resume button becomes Download resume.
Later replace that PDF with the same filename to update it.

## Add screenshots

Each project in content.js has screens (captions) and images (matching file paths).
For example upload assets/images/skill-1.jpg for the first Skill Connect image.
Use the filenames already listed, or change the paths to your own filenames.
Use straight, full-resolution screenshots; images are contained without cropping.
Missing images display clearly labelled placeholders.
You can add more images and matching captions; all appear in the case study.
The first two appear on its homepage card. Use at least two for each project.

## Update text, experience, or projects

Open content.js in GitHub and click the pencil/Edit button.
Change the relevant text, then Commit changes.
Keep quotation marks, commas, and brackets intact.
To add a project, duplicate one complete project object in the projects array,
use a unique id, and update its fields. Its card and case study are created automatically.
The project count updates automatically.
Dates are based on the information provided: review your current job dates before publication.

## Change the layout or other copy

index.html: homepage headings, about supporting paragraph, contact wording, metadata.
style.css: colors, layout, typography, responsive styles, animation.
app.js: rendering and interactions; expertise card text is here.
content.js: profile links, intro, about text, experience, all projects and asset paths.

Changes committed to the publishing branch trigger another Pages deployment.
There is no website login or upload manager in this static edition.
Only upload material you intend to show publicly. Client source code is not included.

## Preview locally

Serve this folder using VS Code Live Server, or run `python -m http.server 8000`
and visit http://localhost:8000. No compilation is required.

## Included project status

Resume Builder: preparing for release, not a claimed live store release.
Buying & Selling: checkout incomplete, as supplied.
All screenshots and portrait start as placeholders; no real assets were supplied for this export.
No invented CV is included. Upload your own reviewed PDF.
