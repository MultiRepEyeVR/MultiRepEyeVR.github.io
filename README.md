# MultiRepEyeVR.github.io

Project page for **Through the Eyes of Emotion: A Multi-faceted Eye Tracking
Dataset for Emotion Recognition in Virtual Reality** (ACM IMWUT 2025), served
by GitHub Pages at <https://multirepeyevr.github.io/>.

## Linking the Google Forms

Dataset access runs through two Google Forms. In `index.html`, search for the
prefix `REPLACE_WITH_` — it marks two `href` values in the *Dataset access*
section (the request form, then the agreement form). Paste the real links
there and push.

## Structure

- `index.html` — the whole page (no build step)
- `css/style.css` — styles
- `assets/` — teaser image and example clips, derived from
  [Through-the-Eyes-of-Emotion](https://github.com/MultiRepEyeVR/Through-the-Eyes-of-Emotion)
  `figures/` (GIFs re-encoded to MP4 with ffmpeg, teaser resized to 2000 px)

## Preview locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```
