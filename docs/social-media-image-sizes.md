# Correct Image Sizes for Every Social Platform (and How to Make Them Fast)

Post an image at the wrong ratio and the platform crops it for you — usually through someone's face. This is the current cheat sheet, plus a fast way to produce each format without opening Photoshop.

## The cheat sheet

| Platform | Asset | Size (px) | Ratio |
|---|---|---|---|
| YouTube | Thumbnail | 1280 × 720 | 16:9 |
| TikTok | Cover | 1080 × 1920 | 9:16 |
| Instagram | Square post | 1080 × 1080 | 1:1 |
| Instagram | Portrait post | 1080 × 1350 | 4:5 |
| Instagram | Story / Reel | 1080 × 1920 | 9:16 |
| X (Twitter) | In-feed image | 1600 × 900 | 16:9 |
| X (Twitter) | Header | 1500 × 500 | 3:1 |
| Facebook | Shared image | 1200 × 630 | ~1.91:1 |
| Facebook | Cover | 820 × 312 (desktop) | — |
| LinkedIn | Shared image | 1200 × 627 | ~1.91:1 |
| Pinterest | Pin | 1000 × 1500 | 2:3 |

Two rules cover most mistakes: **always export at least the listed size** (platforms downscale well, upscale badly), and **keep faces and text away from edges** — most feeds crop the preview.

## Making them without a designer

Each of these free editors is preset to its platform's exact canvas, runs in the browser, and exports ready-to-upload files — no upload to any server, no watermark:

- [YouTube Thumbnail Maker](https://dengfan.top/youtube-thumbnail-maker.html) — 1280×720 with big-text presets, since thumbnails are viewed at postage-stamp size.
- [TikTok Cover Maker](https://dengfan.top/tiktok-cover-maker.html) — 9:16 with safe-zone guides for UI overlays.
- [Instagram Post Maker](https://dengfan.top/instagram-post-maker.html) — square, portrait, and story canvases.
- [X Post Image Maker](https://dengfan.top/x-post-maker.html) — 16:9 in-feed images.
- [Facebook Cover Maker](https://dengfan.top/facebook-cover-maker.html) — cover and shared-image sizes.

For adapting an existing photo instead of designing from scratch: [crop to exact ratio](https://dengfan.top/crop.html), then [resize to target pixels](https://dengfan.top/resize.html).

## Don't forget the file-size ceiling

Sharp is only half the job — big uploads get re-compressed aggressively by the platform, which is where artifacts come from. Exporting yourself to a sane size (e.g. [under 500KB](https://dengfan.top/compress-500kb.html) for a thumbnail, [under 1MB](https://dengfan.top/compress-1mb.html) for a full-size post) keeps the platform's re-compression gentle.

Profile pictures are their own case: they render as circles nearly everywhere now, so [crop them as a circle preview](https://dengfan.top/avatar-crop.html) before uploading to check nothing important gets cut.

---

*More guides: [JPG vs PNG vs WebP](jpg-vs-png-vs-webp.md) · [How to compress to an exact KB target](compress-image-to-100kb.md)*
