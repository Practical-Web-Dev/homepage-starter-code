# Student Portfolio Template

A coded version of the Alex Carter homepage mockup, provided for Practical Web Dev students. It keeps the light background, teal accent, large introduction, social links, coffee project preview, contact section, and footer.

## Open the website

Unzip the folder and open `index.html` in your browser. You can also open the folder in VS Code and use Live Server. There is nothing to install and no build step.

The page uses HTML and CSS. This design does not need JavaScript.

## Files

- `index.html` — all page text, sections, image paths, and links.
- `style.css` — styling and responsive media queries, separated by section comments.
- `img/northside-coffee.svg` — the coffee website preview shown in the mockup.
- `img/linkedin.svg`, `img/github.svg`, `img/youtube.svg` — local social icons.

Keep the `img` folder next to `index.html`.

## Make it your own

1. In `index.html`, replace **Alex Carter** and **Alex** with your name. Update the page title and meta description, too.
2. Update the introductory paragraph to honestly describe your skills and what you are building.
3. Replace **hello@alexcarter.dev** in both `mailto:` links and in the visible contact email.
4. Update every LinkedIn, GitHub, and YouTube link with your own profile URL. The supplied links open the services' homepages as placeholders.
5. Replace the practice project heading, description, badge, and image with your own work.
6. Replace `https://example.com/` with your actual live project URL. Replace the project card's `https://github.com/` link with its actual code repository URL. These are sample links, not a hosted Northside Coffee website or repository.

The sample name, email, and practice project are illustrative. Replace them before publishing your portfolio.

## Change the project image

Put your screenshot in `img/`, then change the project's image tag, for example:

```html
<img class="project-img" src="img/my-project.png" width="1600" height="900"
  alt="Homepage of my project">
```

Use your image's actual width and height. The stylesheet uses `width: 100%` and `height: auto`, so it scales without cropping.

The included coffee preview is an SVG viewport containing the relevant part of the supplied mockup. It is a local, self-contained asset. You do not need to edit the SVG markup; replace its image path in `index.html` when adding your own screenshot. All portfolio text and the surrounding page layout are actual editable HTML and CSS.

## Add more projects

Copy the entire `<article class="project-container">` block inside the project section and paste it below the existing article. Update its details and links. The CSS already adds spacing between project articles.

Change **My First Project** to **My Projects**, and update the navigation link and hero button label when appropriate. Keep the section's `id="project"` unless you also update its anchor links.

## Change the design

The colors and dimensions are written directly in `style.css`:

- `#007f8a` — teal accent.
- `#005f69` — darker hover accent.
- `#091731` — main navy text and icons.
- `#f8fafc` — page background.
- `.container` — page width.
- `.hero-heading` — large introduction.

Search for a color and replace its occurrences to change the palette. Social icon colors can be changed in the small SVG files.

The page adapts to smaller screens using the media queries at the bottom of the stylesheet. The project image and description stack on mobile.

## Font and offline use

Inter loads from Google Fonts when an internet connection is available. Without it, the page falls back to Arial. All project imagery and icons are included locally; there is no external icon kit, package manager, framework, or JavaScript dependency.

## Student use

You may use, edit, and publish this template for your own portfolio and adapt the design for your projects. Add your own work and describe practice projects honestly.

## Verification

Local asset references, anchor links, HTML structure, image dimensions, and the ZIP contents were checked. A browser preview was unavailable in the authoring environment, so exact pixel alignment has not been browser-verified.
