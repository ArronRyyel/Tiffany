# How to Customize Your Anniversary Website

## 1. Add Your Photos

Place your photos inside the `photos/` folder.
Name them however you like (e.g. `our-first-date.jpg`, `trip-to-paris.jpg`).

Supported formats: `.jpg`, `.jpeg`, `.png`, `.webp`

> **Note:** If a photo is missing or fails to load, the site automatically shows
> a soft colored gradient placeholder — so it won't break the layout.

---

## 2. Edit Your Memories

Open `index.html` and find the **MEMORY DATA** section near the bottom of the file.
It looks like this:

```js
const MEMORIES = [
  {
    image: "photos/memory-01.jpg",   // ← path to your photo
    date: "The Very Beginning",       // ← the date or era label
    title: "The Day We Met",          // ← short title shown on hover
    description: "I didn't know it then, but that was the day everything changed."
  },
  // ... more memories
];
```

You can:
- Change any `image`, `date`, `title`, or `description`
- Add as many memories as you like (10–30 work great)
- Remove any you don't need

---

## 3. Edit the Love Letter

Scroll down in `index.html` to the `#letter` section.
Look for the comment:

```html
<!-- ✏️  EDIT YOUR LETTER BELOW -->
```

Replace the `<p>` paragraphs between the two comments with your own words.

---

## 4. Open the Website

Just open `index.html` in any modern browser — no server needed.

For best results use Chrome, Edge, Firefox, or Safari.

---

## 5. Optional: Host Online

You can host this for free on:
- **GitHub Pages** — free, just push to a repo and enable Pages
- **Netlify** — drag & drop the folder at netlify.com
- **Vercel** — similar to Netlify

That way you can send her a link from anywhere.
