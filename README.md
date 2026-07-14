# MultiRepEyeVR.github.io

Project page for **Through the Eyes of Emotion: A Multi-faceted Eye Tracking
Dataset for Emotion Recognition in Virtual Reality** (ACM IMWUT 2025), served
by GitHub Pages at <https://multirepeyevr.github.io/>.

## Dataset access flow

Access is gated: the *Dataset access* section links two Google Forms (access
request + data use agreement); approved requesters receive the download link
by email. The forms are managed from the MultiRepEyeVR Google account — edit
them there, not here.

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
