# HTML Video Tag

## Description

The HTML `<video>` tag is used to display videos on a webpage. It allows users to watch videos and control playback directly in their browser.

Common video formats include MP4, WebM, and Ogg.

## Basic Syntax

```html
<video controls width="500">
  <source src="assets/sample.mp4" type="video/mp4" />
  Your browser does not support the video element.
</video>
```

## Common Attributes

| Attribute     | Description                                                         |
| ------------- | ------------------------------------------------------------------- |
| `src`         | Specifies the path or URL of the video file.                        |
| `controls`    | Displays playback controls, such as play, pause, and volume.        |
| `width`       | Sets the width of the video player.                                 |
| `height`      | Sets the height of the video player.                                |
| `autoplay`    | Starts playing the video automatically when allowed by the browser. |
| `muted`       | Starts the video without sound.                                     |
| `loop`        | Repeats the video when it finishes.                                 |
| `poster`      | Displays an image before the video starts playing.                  |
| `preload`     | Suggests how the browser should load the video before playback.     |
| `playsinline` | Allows the video to play inline on supported mobile browsers.       |

## Video Formats

| Format | Description                                        |
| ------ | -------------------------------------------------- |
| MP4    | Widely supported and commonly used for web videos. |
| WebM   | A web-focused video format.                        |
| Ogg    | An open multimedia format that can contain video.  |

## Examples

Explore the HTML files in this folder to learn how to:

- Add videos to a webpage.
- Display video controls.
- Set video dimensions.
- Use a poster image.
- Apply autoplay, muted, and loop attributes.

## Best Practices

- Use the `controls` attribute so users can control playback.
- Compress videos to reduce loading time and data usage.
- Provide a `poster` image to preview the video.
- Avoid autoplay with sound.
- Use the appropriate `type` attribute inside the `<source>` element.
- Add fallback text for browsers that do not support the video element.
- Keep video files organized inside an `assets/` folder.
