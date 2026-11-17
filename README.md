# Fletcher's Tavern website

A one-page static website for Fletcher's Tavern, a bar and grill at 212 Brown Street in Westbrook, Maine. It highlights NFL football, Thursday karaoke, pizza and the full kitchen, pool tables and darts, and drink specials.

No build step. It is plain HTML, CSS and a few lines of JavaScript:

- `index.html` has all the content
- `styles.css` has the look
- `script.js` runs the mobile menu
- `assets/` holds the icon (and is where photos should go)

## Filling in the placeholders

Anything the tavern still needs to confirm is wrapped in `<span class="tbd">` (or has `class="tbd"`) and shows on the page as grey italic text with a dashed underline. Search `index.html` for `tbd` to find every one:

- Hours for each day, and kitchen hours
- Phone number
- Drink specials and happy hour
- The rest of the menu
- Pizza toppings
- Karaoke sign-up time
- Specials for Tuesday, Wednesday and Friday

When you replace a placeholder with real info, remove the `tbd` class so it shows as normal text.

## Adding photos

Put photos in `assets/` and swap one into any of the illustration boxes, for example:

```html
<div class="feature__art"><img src="assets/pool.jpg" alt="Pool tables at Fletcher's Tavern"></div>
```

## Previewing

Open `index.html` in a browser, or run `python3 -m http.server` in this folder and visit http://localhost:8000.

## Publishing on GitHub Pages (free)

1. In the repo on GitHub, go to **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, and save.
3. After a minute the site is live at `https://<your-github-username>.github.io/fletcherstavern/`. You can point a custom domain at it from the same page.
