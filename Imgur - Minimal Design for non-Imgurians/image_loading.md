# Image loading in different browsers
*(And useragents.)*

When using Chrome or Chromium-based browsers (Brave, Opera, new Edge etc.), Imgur serves non-modal images (meaning images that aren't clicked to zoomed bigger) as much smaller WebP format instead of PNG or JPG.

Problem is that it's noticeably worse quality, specially when using "Minimal Design for non-Imgurians" userstyle. [This is the best example of gallery were this happens](https://imgur.com/gallery/ku9zlNu) (here's [side by side screenshot comparison of Firefox and Brave](../../../raw/master/Imgur%20-%20Minimal%20Design%20for%20non-Imgurians/quality_example.jpg)).

> **More in technical terms:** there's two IMG elements in image container, image with class "image-placeholder" and image with native HTML5 lazy loading (`loading=lazy`) property, both optimized WebPs. I'm not sure that IMG with "image-placeholder" class there does, maybe someone with more knowledge of JavaScript knows.
> 
> But what I garnered, it weirdly when right-clicking the image, it changes the URL of IMG of "image-placeholder" from WebP to original extension.
> 
> But opening that to new tab doesn't bring the unoptimized image, because the "image-placeholder" is always below the image with lazy loading. So I made CSS fix that hides the lazy loading image so you can load and get unoptimized version of image by right-clicking.

## TL;DR / Solutions

- I made CSS fix that loads the non-zoomed "original" picture by right-clicking the image.
- If you use Chromium-based browser (basically anything else then Firefox) and want better solution, install [User-Agent Switcher and Manager](https://chrome.google.com/webstore/detail/user-agent-switcher-and-m/bhchdcejhohfmigjafbampogmaanbfkg) extension and set that to "Firefox" in Imgur.