NUVORA CARE WEBSITE — GITHUB PAGES SETUP

Included:
- index.html: responsive Nuvora Care website with a premium green-and-cream layout.
- Existing illustrations are reused from the current Nuvora Care GitHub Pages site:
  - images/hero-care.png (homepage hero)
  - images/role-nurse.png (Registered Nurse)
  - images/role-hca.png (Healthcare Assistant)
  - images/role-senior.png (Senior Care Assistant; fallback included if it fails to load)
  - images/role-support.png (Support Worker)
  - images/role-kitchen.png (Kitchen Assistant)
- These URLs were verified from the current published Nuvora Care website's image links.

BEFORE YOU PUBLISH
1. Open index.html in a browser and check the wording and images.
2. Confirm that 01482 555 019, info@nuvoracare.co.uk and Bridge View, HU4 7DY are correct.
3. The contact form opens the visitor's email app and prepares an email. It does not send automatically and does not store form submissions. For a real online form, connect a form service or backend.
4. The existing illustrations are loaded from your current GitHub Pages website. Keep the original /images/ files in the repository. If you rename or remove them, the redesigned site will no longer be able to load them.
5. Google Fonts are loaded externally and need an internet connection.
6. Check that all recruitment and vetting claims accurately describe Nuvora Care's current procedures.

GITHUB PAGES — STEP BY STEP
A. Open https://github.com and sign in.
B. Open your existing repository: https://github.com/ashisebaai-dot/nuvoracare.github.io
C. Make a backup first: use Code → Download ZIP, or create a new branch for a preview.
D. Click “Add file” → “Upload files”.
E. Upload the new index.html to the repository root. Do not delete the existing images folder.
F. Enter the commit message “Redesign Nuvora Care website using existing illustrations”.
G. Click “Commit changes” to the branch configured for publishing.
H. Open Settings → Pages. Check that the correct branch and “/(root)” folder are selected. Do not change these if Pages is already correctly configured.
I. Wait a minute or two, then visit https://ashisebaai-dot.github.io/nuvoracare.github.io/
J. If the old page appears, refresh with Cmd + Shift + R or wait for deployment to finish.

SAFER PREVIEW
Create a separate branch and upload the new index.html there first. GitHub Pages normally publishes from the configured branch, so the preview branch will not automatically replace the live site unless you change the Pages source. Review on mobile and desktop before updating the publishing branch.
