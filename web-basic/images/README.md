# HTML Image Tag

## Description

The HTML `<img>` tag is used to display images on a webpage. Images can make websites more attractive and help users understand information visually.

The `<img>` tag is an empty element, which means it does not need a closing tag.

## Basic Syntax

```html
<img src="landscape.jpg" alt="Description of the image" />
```

## Common Attributes

| Attribute | Description                                                                                      |
| --------- | ------------------------------------------------------------------------------------------------ |
| `src`     | Specifies the path or URL of the image.                                                          |
| `alt`     | Provides alternative text if the image cannot be displayed and helps screen readers describe it. |
| `width`   | Sets the width of the image.                                                                     |
| `height`  | Sets the height of the image.                                                                    |
| `title`   | Provides additional information, often shown when hovering over the image.                       |

## Image Formats

| Format     | Common Use                                     |
| ---------- | ---------------------------------------------- |
| JPG / JPEG | Photographs                                    |
| PNG        | Images that need transparency                  |
| GIF        | Simple animations                              |
| SVG        | Logos and icons                                |
| WebP       | Optimized web images                           |
| AVIF       | High-quality images with efficient compression |

## Examples

Explore the HTML files in this folder to learn how to display images, set their dimensions, use alternative text, create clickable images, and apply CSS styles.

## Best Practices

- Always provide meaningful `alt` text for informative images.
- Use descriptive file names, such as `mountain-landscape.jpg`.
- Specify image dimensions when appropriate to reduce layout shifts.
- Use optimized image formats to improve page loading speed.
- Keep your images organized in an `assets/` or `images/` subfolder.
