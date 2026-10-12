# Heyer Heating & Air Conditioning – preview website

This is a free preview website for **Heyer Heating & Air Conditioning** (La Crosse, WI area), built by Hudson | Lacrosse Lawn & Landscape.
It is plain HTML and CSS: no build step, no monthly fees for hosting.

Live preview: https://megamower22.github.io/heyer-hvac-preview/

## How to change text on the site (on github.com)

1. Go to this repo on github.com and sign in.
2. Click **index.html**.
3. Click the **pencil icon** (Edit this file) at the top right of the file.
4. Find the words you want to change and type the new text. Only change the words between the tags, not the `<` `>` parts.
5. Scroll down (or click the green **Commit changes...** button), add a short note like "Update hours", and click **Commit changes**.
6. Wait about a minute, then refresh the website. Your change will be live.

## Good to know

- **Colors** are at the top of `style.css` (look for `--navy`, `--lime`, `--mist` and `--steel`).
- **Fonts** come from Google Fonts: **Archivo** (wide, bold) for the name and headings, **Inter** for body text (`--font-brand` and `--font-body` in `style.css`).
- Anything in yellow highlight that says **[Owner to confirm]** still needs real info from the owner. Once it's confirmed, delete the whole `<span class="placeholder">...</span>` part.
- **Services** are the `<article class="card">` blocks in the Services section. **Service towns** are the `<li>` items inside `class="towns"`.
- **Reviews** are real Google reviews, shown as `<blockquote>` blocks inside `class="quotes"`. When the review count changes, search for `65 Google` and update it.
- The phone number appears in several places. Search for `799-3538` (and `+16087993538` in the call and text links) to update all of them.
- The email appears in several places. Search for `heyerhtg@gmail.com` to update it.
- To remove the "Preview site" banner once the owner approves, delete the line with `class="preview-banner"` in `index.html`.
