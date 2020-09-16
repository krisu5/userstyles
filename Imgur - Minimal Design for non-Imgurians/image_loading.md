# Image loading in different browsers
*(And useragents.)*

When using Chrome or Chromium-based browsers (Brave, Opera, new Edge etc.), Imgur serves non-modal images (meaning images that aren't clicked to zoomed bigger) as much smaller WebP format instead of PNG or JPG.

Problem is that it's noticeably worse quality, specially when using "Minimal Design for non-Imgurians" userstyle. [This is the best example of gallery were this happens](https://imgur.com/gallery/ku9zlNu) (here's [side by side screenshot comparison of Firefox and Brave](../../../raw/master/Imgur%20-%20Minimal%20Design%20for%20non-Imgurians/quality_example.jpg)).

> **More in technical terms:** there's two IMG elements in image container, image with class "image-placeholder" and image with native HTML5 lazy loading (`loading=lazy`) property, both optimized WebPs.
> 
> Weirdly when right-clicking the image, it changes the URL of IMG of "image-placeholder" from WebP to original extension (maybe for prevent downloaders or something? Pretty useless solution, imo).
>
> The "image-placeholder" IMG is for right-clicking the image and getting the actual source image, but in some cases (like aggressive JS blocking), it doesn't give the source URL but WebP address instead.
> 
> So I made CSS fix that hides the lazy loading image so you can always load and get unoptimized version of image by right-clicking.

## TL;DR / Solutions

- I made CSS fix that loads the non-zoomed "original" picture by right-clicking the image.
- If you use Chromium-based browser (basically anything else then Firefox) and want better solution, install [User-Agent Switcher and Manager](https://chrome.google.com/webstore/detail/user-agent-switcher-and-m/bhchdcejhohfmigjafbampogmaanbfkg) extension and set that to "Firefox" in Imgur.