# Maison de la Fork Holiday Post Preview

An Instagram-style preview of the 7-slide holiday carousel, for sharing with the client.

- **Desktop** view: Instagram's desktop post layout (media left, caption and comments right).
- **Phone** view: Instagram's mobile feed card. Phones always get this view.
- Slides 3 and 5 have two versions; a **V1 / V2** switch appears on top of the slide (top-left) on those slides.
- Swipe or use the arrows / keyboard arrow keys to change slides. Double-click a slide to like it.
  Videos play muted; the speaker button turns sound on.

## Put it on GitHub Pages

1. Create a new repository and upload everything in this folder (`index.html`, `media/`, `README.md`).
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then **Save**.
4. After a minute the page is live at `https://<your-username>.github.io/<repository-name>/`.

## Change the content

Open `index.html` and edit the `POST` block near the top of the `<script>`:
username, verified tick, avatar, likes, caption, and the list of slides.
Each slide has one or more `versions`; add a second version to show the V1 / V2 switch on that slide.
Put new files in `media/`. Videos should be H.264 MP4, 1080 × 1440, ideally under 15 MB each.
