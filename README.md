# Lynn's Table — Final Launch Version

**Brand:** Cook with joy. Eat with love.  
**Promise:** Easy everyday meals · Restaurant-at-home

This version is English-first. Vietnamese appears as a dedicated section near the bottom of recipe/menu pages, which keeps the main North American reading experience clean while preserving the Vietnamese version.

## What is included
- Responsive homepage
- English-first recipe index with search
- Featured Steamed Mussels recipe with measurements, cooking notes, Vietnamese version and embedded vertical video
- Sườn Rim Nước Mắm recipe
- Vietnamese grilled pork skewers recipe
- 2-night camping menu
- Print-friendly recipe layout
- Newsletter UI placeholder
- Starter privacy and affiliate disclosure pages
- Basic Recipe structured data on the mussels page

## Launch free with Cloudflare Pages
1. Create a GitHub account at github.com.
2. Create a new repository, e.g. `lynns-table`.
3. Unzip this package. Upload the CONTENTS of the `lynns-table-final` folder, including `assets`, to the repository.
4. Go to Cloudflare Pages: pages.cloudflare.com.
5. Choose **Create a project → Connect to Git** and connect GitHub.
6. Select the `lynns-table` repository.
7. This is a plain static site: no framework/build command is needed. Set the output/root directory to the repository root if Cloudflare asks.
8. Deploy. Cloudflare will provide a temporary `*.pages.dev` address.
9. Open every page on desktop and mobile before sharing publicly.

## Before public launch
- Connect the newsletter form to a real email provider (Buttondown, MailerLite, Kit, etc.).
- Buy/connect a custom domain when ready.
- Replace or add food photography as you create more recipes.
- Add social profile links once the accounts are live.
- Replace starter privacy/disclosure text when analytics, ads or affiliate programs are enabled.
- Consider separate `/vi/` URLs later if Vietnamese content grows enough to justify independent SEO pages.

## Editing
All content is plain HTML/CSS/JS. To add a recipe, duplicate one recipe HTML file, edit the content, add its image/video to `assets`, then add a card to `recipes.html`.
