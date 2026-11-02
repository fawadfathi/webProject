# HTML Links

## Description

The HTML `<a>` (anchor) tag is used to create hyperlinks. Links allow users to navigate between webpages, open external websites, download files, send emails, or jump to specific sections of a page.

The `href` attribute specifies the destination of a link.

## Basic Syntax

```html
<a href="https://www.example.com">Visit Example</a>
```

## Common Attributes

| Attribute | Description                                                            |
| --------- | ---------------------------------------------------------------------- |
| `href`    | Specifies the link's destination.                                      |
| `target`  | Specifies where to open the linked document.                           |
| `rel`     | Defines the relationship between the current page and the linked page. |
| `title`   | Provides additional information about the link.                        |

## Common `href` Values

| Value                      | Description                                                     |
| -------------------------- | --------------------------------------------------------------- |
| `https://example.com`      | Links to an external website.                                   |
| `about.html`               | Links to another file using a relative path.                    |
| `#contact`                 | Links to an element with the matching `id` on the same page.    |
| `mailto:hello@example.com` | Opens the user's default email application to compose an email. |
| `tel:+1234567890`          | Creates a link for calling a phone number on supported devices. |

## Common `target` Values

| Value     | Description                                                      |
| --------- | ---------------------------------------------------------------- |
| `_self`   | Opens the link in the current browsing context.                  |
| `_blank`  | Opens the link in a new tab or window, depending on the browser. |
| `_parent` | Opens the link in the parent browsing context.                   |
| `_top`    | Opens the link in the full browsing context.                     |

## Examples

Explore the HTML files in this folder to learn how to:

- Create basic hyperlinks.
- Link to external websites.
- Open links in new tabs.
- Create email links.
- Navigate to sections within a webpage.
- Make images clickable.
- Download linked files.

## Best Practices

- Use descriptive link text instead of vague text like "click here."
- Always provide a meaningful destination in the `href` attribute.
- Use relative paths for links between files in the same project.
- When using `target="_blank"`, use `rel="noopener"` when appropriate for security.
- Make sure links are accessible using a keyboard.
- Check that links point to valid destinations.
