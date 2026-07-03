# Your Photos Leak Your Location: What EXIF Data Is and How to Remove It

Every photo from a phone carries an invisible payload: **EXIF metadata**. It typically includes the exact GPS coordinates where the photo was taken, the timestamp down to the second, your device model, and sometimes camera serial numbers. Post the photo, and anyone who downloads it can read all of that with free tools.

## When it actually matters

Big platforms (Instagram, Facebook, X) strip EXIF on upload, which lulls people into thinking it's handled. But metadata survives intact when you:

- attach a photo to an **email**
- share via **cloud drive links** or file transfer
- post to **forums, marketplaces, and smaller sites** (many don't strip it)
- send "original quality" in some messaging apps
- publish images on **your own website or blog**

Selling furniture on a marketplace with photos taken in your living room? The listing may contain your home's GPS coordinates. The same applies to photos of kids, daily-routine locations, and anything posted pseudonymously — EXIF can link an "anonymous" account to a real place and time.

## Check what your photos are carrying

On iPhone: open a photo → swipe up or tap ⓘ — you'll see the map. On Windows: right-click → Properties → Details. If there's a location and precise timestamp there, that data travels with every copy you share.

## Removing it

The clean way is to strip metadata from a copy before sharing:

1. Open the [Remove EXIF tool](https://dengfan.top/remove-exif.html) — it works entirely in your browser, so you're not uploading your photo (with its GPS data) to yet another server to remove the GPS data. You can even load the page, go offline, and process.
2. Drop in the photo, download the cleaned copy.
3. Share the copy; keep the original for yourself — the metadata is genuinely useful for your own archive.

Prevention also helps: both iOS and Android let you deny camera apps location access, and iOS lets you strip location per-share (share sheet → Options → Location off).

## Metadata isn't the only leak

EXIF removal doesn't blur what's *visible* in the image: street signs, mail with your address, screen contents, reflections. For screenshots with sensitive info, [pixelate the sensitive regions](https://dengfan.top/blur-pixelate.html) — and note that heavy pixelation, not light blur, is the safer choice since weak blurs can sometimes be reversed. For documents, consider a [tiled watermark](https://dengfan.top/add-watermark.html) ("For X verification only") so the copy can't be reused elsewhere.

---

*More guides: [How to compress ID photos safely](compress-image-to-100kb.md) · [HEIC to JPG guide](heic-to-jpg-guide.md)*
