# Multimedia Systems Course Portfolio

This repository contains the personal portfolio website of **Raiza Lhyn Antonio Gloria** for **Multimedia Systems (CTMLSYSL)**, **ITE305**, Academic Year **2026–2027**.

The portfolio presents the course outputs and projects in an interactive, scrapbook-inspired interface. It includes design exercises, vector studies, branding work, poster composition, video production, and post-production projects.

## Featured Projects

### IT and CS Promotional Video

- **Role:** Director and Editor
- **Block:** ITE305
- **Term:** 1st Term
- **Academic Year:** 2026–2027
- **Event:** Department Multimedia Showdown
- **Awards:**
  - Champion — Promotional Video Category
  - Best Concept and Pitch
  - Best Motion Graphics and VFX
  - Best On-Screen Presenter/Brand Ambassador
- **Tools:** DaVinci Resolve, CapCut Desktop, Motion Graphics, VFX

The project highlights creative direction, storytelling, editing, motion graphics, and visual effects.

### Short Film — “Punyagi”

- **Role:** Co-Editor, alongside Kristine Mae Madronero
- **Poster:** Created by Lawrence Batac
- **Block:** ITE305
- **Term:** 1st Term
- **Academic Year:** 2026–2027
- **Event:** Department Multimedia Showdown
- **Awards:**
  - Champion — Short Film Category
  - Best Actress
  - Best Supporting Cast
  - Best Editing and Post-Production
- **Tools:** DaVinci Resolve, CapCut Desktop, Co-Editing, Post-Production, Storytelling

The project highlights collaborative editing, post-production, pacing, story flow, and visual storytelling.

## Technologies and Tools

- HTML
- CSS
- Vanilla JavaScript
- DaVinci Resolve
- CapCut Desktop
- GIMP
- Inkscape
- Canva

The website uses locally stored assets and does not require a JavaScript framework or build process.

## Project Structure

```text
.
├── index.html
├── profile-pic.png
├── icons/
│   └── Decorative images and interface assets
└── outputs/
    ├── ITE305_PromotionalVideo.mp4
    ├── ITE305_Shortfilm.mp4
    ├── ITE305_Shortfilm_web.mp4
    ├── ITE305_ShortFilmPoster.png
    ├── output1.png
    ├── output2.svg
    ├── output3.svg
    ├── output4.svg
    ├── output5.svg
    ├── output6.svg
    └── output7.png
```

`ITE305_Shortfilm_web.mp4` is the browser-compatible H.264 version used by the portfolio. The original `ITE305_Shortfilm.mp4` is preserved as the source video.

## Vercel Deployment

The MP4 files are tracked with Git LFS because they exceed GitHub's regular file-size limit. To deploy the videos correctly on Vercel:

1. Open the Vercel project settings.
2. Go to **Settings → Git**.
3. Enable **Git LFS**.
4. Trigger a new deployment.

If Git LFS is disabled, the deployment may contain small LFS pointer files instead of the actual MP4 media, causing the browser video controls to appear without playable video frames.

## Running the Portfolio

Because the portfolio is a static website, it can be opened directly:

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Use the navigation links to browse the portfolio sections.
4. Open project cards to view descriptions, tools, awards, metadata, poster previews, and video controls.

For the most reliable local video playback, serve the folder through a local web server instead of opening the HTML file directly. For example, with Python installed:

```bash
python -m http.server 8000
```

Then open <http://localhost:8000> in a browser.

## Accessibility and Responsiveness

The portfolio includes:

- Semantic navigation and project card content
- Accessible labels for controls and media
- Keyboard navigation for the output deck and project modal
- Responsive layouts for smaller screens
- Support for reduced-motion preferences
- Native video controls for project playback

## Credits

- Portfolio author: **Raiza Lhyn Antonio Gloria**
- Short film poster: **Lawrence Batac**
- Short film co-editor: **Kristine Mae Madronero**
