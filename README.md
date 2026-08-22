Purey Hydrate — One-Page Website
Three files, ready for GitHub Pages:
index.html — the site
logo.png — your logo (already wired into the nav + footer)
bottle-sample.jpg — your sample bottle photo (used in the hero section)
How to publish on GitHub Pages (free)
Create a public repository on github.com (e.g. purey-hydrate).
Click "Add file" → "Upload files" and upload all three files above together, keeping their exact names.
Commit the upload.
Go to Settings → Pages.
Source: Deploy from a branch → Branch: main → Folder: / (root) → Save.
Wait 1–2 minutes. Your live link appears at the top of that Pages screen:
https://YOUR-USERNAME.github.io/purey-hydrate/
That's the link you share on WhatsApp, Instagram bio, or hand to restaurant owners.Updating content later
Click on index.html in the repo → pencil (edit) icon → make changes → "Commit changes."
Live site updates automatically within ~1 minute.
What's already wired in
Colors: pulled from your logo (green #0F7A4E / gold #D4A54A) — defined once at the top of the <style> block under :root, so changing those few hex codes updates the entire site.
Pricing: Rs 40 / 500ml, Rs 75 / 1.5L, minimum order flexible — edit inside <section id="pricing">.
Supplier trust section: references Aabetahura Mineral Water's PSQCA certification — edit inside <section id="trust"> if anything changes with your supplier.
Contact: WhatsApp +92 323 8586905 and pureyhydrate@gmail.com — both are already live links.
Quote form: doesn't submit anywhere (this is a static site, no backend) — instead, it opens WhatsApp with all form fields pre-filled as a message. This is the simplest reliable option for a GitHub Pages site with no server.
Testimonials: intentionally left as a placeholder ("we're just getting started")rather than fake reviews — once you have 2–3 real clients, replace this section with their actual quotes and business names, which will build far more trust than filler content.
Swapping the logo or bottle photo
Just re-upload a new file to the repo with the exact same filename (logo.png or bottle-sample.jpg) — GitHub will ask "replace this file?", confirm yes, and the live site updates automatically. No code editing needed.
Adding a custom domain later
Once you register an actual domain (e.g. pureyhydrate.pk), go to Settings → Pages → "Custom domain" field and point it there. Not required to launch — the github.io link works immediately and is free.
