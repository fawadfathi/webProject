# HTML Audio Tag

## Description

The HTML `<audio>` tag is used to add sound or music to a webpage. It allows users to play, pause, and control audio directly in their browser.

The `<audio>` tag supports audio formats such as MP3, WAV, and OGG.

## Basic Syntax

```html
<audio controls>
  <source src="assets/beat.wav" type="audio/mpeg" />
  Your browser does not support the audio element.
</audio>
```

## Common Attributes

| Attribute  | Description                                                         |
| ---------- | ------------------------------------------------------------------- |
| `src`      | Specifies the path or URL of the audio file.                        |
| `controls` | Displays audio controls, such as play, pause, and volume.           |
| `autoplay` | Starts playing the audio automatically when allowed by the browser. |
| `loop`     | Repeats the audio when it finishes.                                 |
| `muted`    | Starts the audio in a muted state.                                  |

## Audio Formats

| Format | Description                                             |
| ------ | ------------------------------------------------------- |
| MP3    | Widely supported and commonly used for music and audio. |
| WAV    | Often provides uncompressed, high-quality audio.        |
| OGG    | An open audio format supported by many modern browsers. |

## Examples

Explore the HTML files in this folder to learn how to:

- Add audio to a webpage.
- Display audio controls.
- Repeat audio using `loop`.
- Use autoplay and muted attributes.

## Best Practices

- Use the `controls` attribute so users can control playback.
- Provide alternative text for browsers that do not support the audio element.
- Compress audio files to reduce loading time.
- Avoid unexpected autoplay, especially when audio has sound.
- Use the correct `type` attribute inside the `<source>` element.
- Keep audio files organized inside an `assets/` folder.
