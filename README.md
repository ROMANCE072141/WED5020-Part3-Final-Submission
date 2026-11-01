# WED5020 Website Project — YEAST Artisan Bakery & Grocer

**Student:** Romance Phogole  
**Student number:** ST10524545  
**Module:** WED5020  
**Target organisation:** YEAST Artisan Bakery & Grocer  
**Portfolio of Evidence:** Summative 1, Parts 1, 2 and 3

## Project overview
This is a multi-page responsive website project. It demonstrates website structure, responsive styling, JavaScript interactions, form validation, basic on-page SEO, an embedded Google Maps search, and deployment preparation.

## Pages
- `index.html` — Home
- `about.html` — Organisation overview, mission, vision and interactive accordion
- `products.html` — Product categories, search/filter and image lightbox
- `enquiry.html` — Product/general enquiry form with client-side validation
- `contact.html` — Contact form, email-draft behaviour and embedded map

## Folder structure
- `styles/common.css` — Shared responsive styles and animations
- `js/script.js` — Navigation, accordion, product filter, lightbox, form validation and back-to-top behaviour
- `images/` — Product image assets
- `robots.txt` — Search engine crawler guidance
- `sitemap.xml` — List of public website pages for crawlers
- `CHANGELOG.md` — Record of work completed for each portfolio part

## Part 3 functionality
1. Responsive mobile navigation toggle and current-page indicator.
2. Accessible accordion for mission, vision and values.
3. Product search and category filtering.
4. Product image lightbox using the HTML dialog element.
5. CSS reveal animation and hover transitions, respecting reduced-motion preferences.
6. Enquiry form validation with a confirmation message for the demonstration.
7. Contact form validation and `mailto:` email-draft preparation.
8. Google Maps iframe embed and an external Google Maps link.
9. SEO title, description, keywords, author, robots metadata, semantic headings, alt text, descriptive internal links and sitemap/robots files.
10. Responsive layout and image lazy-loading.

## Form and deployment limitations
- The enquiry form demonstrates client-side validation only. It does not save or send data to a server.
- The contact form opens a pre-addressed email draft only after a real recipient is configured in `js/script.js`. It does not send automatically.
- `hello@example.com` and `+27 00 000 0000` are placeholders. Replace them with approved contact details before a live demonstration.
- The map is an illustrative Google Maps search for Johannesburg, not a verified business address.
- Confirm the deployed GitHub Pages URL. If it differs from the URL used in `sitemap.xml` and `robots.txt`, update those files to match the actual published location.
- SEO metadata helps search engines understand pages but does not guarantee ranking or indexing.

## How to run locally
1. Open the `WED5020-Website-Project` folder in Visual Studio Code.
2. Open `index.html` in a browser, or use the Live Server extension.
3. Test all navigation links, the product filter, the lightbox, the accordion and both forms.
4. Test at desktop and mobile widths.

## GitHub workflow
After testing:
1. Review changes in GitHub Desktop.
2. Commit with a descriptive message such as `Complete Part 3 JavaScript, forms and SEO`.
3. Push to the `main` branch.
4. Confirm the GitHub Pages deployment and test the published website.

## Changelog
See `CHANGELOG.md` for the detailed Part 1, Part 2 and Part 3 change record.

## References
- Google. (n.d.). *Google Maps*. https://www.google.com/maps
- Google Search Central. (n.d.). *SEO Starter Guide*. https://developers.google.com/search/docs/fundamentals/seo-starter-guide
- MDN Web Docs. (n.d.). *HTML forms*. https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Forms
- MDN Web Docs. (n.d.). *Constraint validation*. https://developer.mozilla.org/en-US/docs/Web/HTML/Constraint_validation
- MDN Web Docs. (n.d.). *HTML dialog element*. https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dialog
- MDN Web Docs. (n.d.). *CSS media queries*. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries
- MDN Web Docs. (n.d.). *CSS Grid Layout*. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout
- GitHub Docs. (n.d.). *GitHub Pages*. https://docs.github.com/en/pages
