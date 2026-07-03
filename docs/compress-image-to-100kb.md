# How to Compress an Image to 100KB Without Ruining It

Upload forms are picky. Job applications, visa portals, exam registrations, and government websites routinely reject anything over 100KB — while a single phone photo is 3–8MB. Here's how to hit that target reliably, and keep the photo recognizable.

## Why "just lower the quality" usually fails

Most people open an editor, drag a quality slider, export, check the file size, and repeat. Two problems:

1. **You're guessing.** JPEG quality 60 might produce 90KB for one photo and 400KB for another — output size depends on image content, not just the slider.
2. **You often overshoot.** To be safe, people compress far below the limit and end up with a blurry mess, which matters a lot for ID photos where a face must stay sharp.

The reliable method is a **binary search on quality**: compress at quality 50, check size, adjust up or down, repeat until the file lands just under the target. Tedious by hand — trivial for a tool.

## The 2-step method

1. Open the free [Compress to 100KB tool](https://dengfan.top/compress-100kb.html) — it runs entirely in your browser, so the photo is never uploaded anywhere (relevant if it's your passport or ID).
2. Drop in your image. It automatically binary-searches the highest quality that fits under 100KB, then lets you download.

Different limit? There are dedicated pages for [20KB](https://dengfan.top/compress-20kb.html), [50KB](https://dengfan.top/compress-50kb.html), [200KB](https://dengfan.top/compress-200kb.html), [500KB](https://dengfan.top/compress-500kb.html) and [1MB](https://dengfan.top/compress-1mb.html).

## Tips that actually move the needle

- **Resize first, compress second.** A 4000px-wide photo squeezed to 100KB looks worse than the same photo resized to 1200px and lightly compressed. If the form displays the image small, [resize it](https://dengfan.top/resize.html) before compressing.
- **Crop away what you don't need.** Fewer pixels = smaller file at the same quality. Use a [crop tool](https://dengfan.top/crop.html) to remove dead space.
- **PNG screenshots compress poorly as PNG.** Convert [PNG to JPG](https://dengfan.top/png-to-jpg.html) first if photographic; keep PNG only for text/UI screenshots.
- **Mind the lower bound.** Some portals require 20–100KB. Aim for ~80KB, not 21KB.
- **ID photos:** use a [dedicated ID photo compressor](https://dengfan.top/id-photo-compress.html) that keeps pixel dimensions fixed while hitting the KB target — many portals check both.

## Privacy note

If the image is an identity document, prefer tools that process locally in the browser. You can verify this: load the page, disconnect from the internet, and compress — if it still works, nothing was uploaded. The tools above pass this test.

---

*More guides: [JPG vs PNG vs WebP](jpg-vs-png-vs-webp.md) · [Remove EXIF data before sharing](remove-exif-data-privacy.md)*
