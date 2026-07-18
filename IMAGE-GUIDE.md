# Adding your images

I couldn't download the site's photos directly from this environment (network access to your WordPress domain is blocked from here), so there's one manual step left: save these 6 images into the `images/` folder, using the exact filenames listed below (the HTML already points to these names).

| Save as (in `images/` folder) | Right-click → "Save image as..." from this URL |
|---|---|
| `hero-coast.jpg` | https://etmcounselling.com.au/wp-content/uploads/2023/10/pexels-photo-133682.jpeg |
| `individuals.jpg` | https://etmcounselling.com.au/wp-content/uploads/2023/10/pexels-photo-516927.jpeg |
| `couples.jpg` | https://etmcounselling.com.au/wp-content/uploads/2023/10/pexels-photo-8957083.jpeg |
| `families.jpg` | https://etmcounselling.com.au/wp-content/uploads/2023/10/pexels-photo-4148842.jpeg |
| `evoke-portrait.jpg` | https://etmcounselling.com.au/wp-content/uploads/2023/10/pexels-photo-1726310.jpeg |
| `about-water.jpg` | https://etmcounselling.com.au/wp-content/uploads/2023/10/drops-of-water-water-nature-liquid-40784-1.jpeg |

**How to do it:**
1. Open each URL above in your browser.
2. Right-click the image → "Save image as…"
3. Save it into the `images` folder of this project, using the filename from the left column exactly as written (all lowercase, with the `.jpg` extension).

Once all 6 files are in `images/`, every page will show the photos correctly.

**Why this step is necessary:** these images currently live on your WordPress hosting. Once you cancel WordPress, those image URLs will likely stop working — so it's best to grab your own copies now and bundle them with the new site, rather than linking to the old ones.

**Favicon (now required):** every page now references a small logo icon for the browser tab. Save your old site's logo from `https://etmcounselling.com.au/wp-content/uploads/2024/01/cropped-mums-logo-final.png` as `images/favicon.png`, or use any square logo/image you like.
